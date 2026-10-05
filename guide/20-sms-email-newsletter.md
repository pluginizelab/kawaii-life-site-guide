[Kawaii Life Site Owner's Guide](../README.md) › 20. SMS, email and newsletter

# 20. SMS, email and newsletter

## 20.1 SMS (Alpha SMS)

**Where:** **Alpha SMS → Settings**

![Alpha SMS settings](../images/alpha-sms.png)

Alpha SMS sends the login and sign-up codes, and can text customers when their order changes status.

- **Balance** shows how much SMS credit is left.
- **Notify Customer**: switch on the order statuses you want a text for (for example *Confirmed*, *Shipped* and *Delivered*), then click **Save all changes**. Every step of the order flow ([10.2](10-orders.md#102-the-order-flow)) is listed.
- **Notify Admin on New Order** texts you when an order comes in.
- **Alpha SMS → Campaign** sends one message to many customers at once.
- **Abandoned carts**: a shopper who leaves items in their cart gets one text with a link back to it, at the same time as Cart Abandonment Recovery's first reminder email, to the phone they typed at checkout. Switch it off in **Theme Options → General → Abandoned-cart SMS** ([2.5](02-theme-options.md#25-general)).

**Promotional campaigns: SMS Contacts**

**Where:** **Kawaii Life → SMS Contacts**

1. Optionally choose **Last ordered within** to keep only recent customers.
2. Click **Download CSV**. The file lists each customer's phone once, written as `8801XXXXXXXXX`, with their name, number of orders, last order date and total spent. Numbers seen only on failed or cancelled orders are left out.
3. Upload the file to your Alpha SMS panel and send the campaign from there.

![SMS Contacts](../images/sms-contacts.png)

⚠️ If the balance runs out, customers can't log in or sign up. Top it up on your Alpha SMS account. The record of sent messages is on the Alpha SMS website.

⚠️ Leave the **API Key** as it is; it connects the site to your Alpha SMS account.

## 20.2 Order emails

**Where:** **WooCommerce → Settings → Emails**

Customers get an email at each step of the order flow ([10.2](10-orders.md#102-the-order-flow)):

| Email | Sent when the order is |
| --- | --- |
| **Order placed** | Placed: a COD order before you call to confirm it, or a bank transfer before the money arrives |
| **Order confirmed** | Confirmed |
| **Order shipped** | Shipped, with the Steadfast tracking code and a **Track your order** button |
| **Order delivered** | Delivered |
| **Order returned** | Returned |

The others link to the order in the customer's **My Account** (or, for a guest, to the Order Tracking page). WooCommerce's own **Processing order** email is switched off, since Confirmed already tells the customer; switch it on here if you want it.

Each email can be switched on or off and its subject and heading changed: click **Manage**. The **Email sender options** at the bottom set the "From" name and address.

**The look.** Every email the shop sends (orders, accounts, password resets) is in the Kawaii Life style: the logo, a white rounded card with a pink-to-lavender stripe, a small emoji badge for the kind of email, and a dark footer with the tagline, links to the shop, Order Tracking and My Account, and your social links. The tagline and social links come from **Theme Options → General** ([2.5](02-theme-options.md#25-general)). To see one, scroll to **Email preview** at the bottom of this page and pick the email from the drop-down.

<img src="../images/email-preview.png" alt="An order email in the Kawaii Life style" width="420">

## 20.3 Newsletter (Brevo)

**Where:** **Brevo → Forms**

![Brevo forms](../images/brevo-forms.png)

The **Join the Kawaii Club** form in the footer is the Brevo form **Default Form**. Edit it here to change its fields, button and messages. New subscribers go to your Brevo contact list, where you send newsletters from your Brevo account.

---

← [19. Forms and messages](19-forms-and-messages.md) · [Contents](../README.md) · [21. SEO (Google and social sharing)](21-seo.md) →
