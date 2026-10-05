[Kawaii Life Site Owner's Guide](../README.md) › 13. Customers, sign-up and saved addresses

# 13. Customers, sign-up and saved addresses

## 13.1 How customers sign up and log in

Customers sign up on the **Sign up** page with their name, email, mobile number and a password. A code is texted to their phone to confirm it. They log in with their **phone number and a texted code**.

![The login card](../images/fe-login.png)

![The sign-up card](../images/fe-signup.png)

- Codes are sent through **Alpha SMS**, so keep its balance topped up (see [section 20](20-sms-email-newsletter.md)).
- **To stop new sign-ups**, go to **WooCommerce → Settings → Accounts & Privacy** and untick **Allow customers to create an account on the "My account" page**.

![WooCommerce account settings](../images/wc-accounts.png)

- Checkout is for signed-in customers only. A shopper who isn't signed in is asked to log in with their phone first.

## 13.2 Looking up a customer

**Where:** **Users → All Users** (or **WooCommerce → Customers**)

Click a customer to see their details. At the bottom, **Saved Addresses** lists their delivery addresses, the same ones they see in My Account. You can edit them here; the **Default** one is used at checkout.

![A customer's saved addresses](../images/user-addresses.png)

## 13.3 Staff accounts

**Where:** **Users → Add User**

Give each staff member their own account and a **Role**:

- **Shop Manager**: orders, products, coupons and reports, but not site settings or plugins. Best for most staff.
- **Editor**: pages and blog posts only.
- **Administrator**: everything. Keep this to one or two people.

---

← [12. Delivery zones, charges and dates](12-delivery-and-shipping.md) · [Contents](../README.md) · [14. What customers see: cart, checkout and My Account](14-customer-experience.md) →
