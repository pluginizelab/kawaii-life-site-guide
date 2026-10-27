[Kawaii Life Site Owner's Guide](../README.md) › 26. What we built on top of Alpha SMS

# 26. What we built on top of Alpha SMS

Every text the shop sends goes out through your **Alpha SMS** account and uses its credit. Alpha SMS sends the messages and the order-status texts. Everything customers do with their phone number was built for Kawaii Life: login, sign-up, guest checkout and changing their number.

## 26.1 What Alpha SMS does on its own

- **Sends the messages.** Login codes, sign-up codes, security notices and cart reminders all use your Alpha SMS credit.
- **Order status texts.** Texts customers when their order changes status, using the messages in **Alpha SMS → Settings** ([20.1](20-sms-email-newsletter.md#201-sms-alpha-sms)).
- **Campaigns.** Sends one message to many numbers from your Alpha SMS panel.

## 26.2 Limits that protect your SMS credit

Without limits, anyone could make the shop send text after text at your cost, or try to guess a code. Alpha SMS has only basic limits of its own, so login, sign-up, guest checkout and number changes all follow these stricter rules:

| Rule | Limit |
| --- | --- |
| A code works for | 5 minutes |
| Wrong tries before a code stops working | 5 |
| Wait before asking for a new code | 60 seconds |
| Codes per phone number | 5 an hour |
| Codes per device or network | 10 an hour |

A code asked for one thing, such as logging in, can't be used for another, such as signing up.

## 26.3 Logging in with a phone number

Customers log in on **My Account** and at checkout with their mobile number and a texted code. They don't need a password.

## 26.4 Signing up with a checked number

New customers sign up on the **Sign up** page with their name, email, mobile and password. The account is made only after they type in the code sent to their mobile, so every account has a phone number that's been checked.

## 26.5 Checking out without an account

A shopper with no account can still order once they've confirmed their number with a code. One code allows one order. If they sign up later with the same number, those orders show up in their new account.

## 26.6 The login number stays put

Each customer's login number is kept apart from their delivery phone. Customers can change the phone on a delivery address at checkout or in **Saved Address**, and they still log in with the same number.

## 26.7 Changing a phone number

Customers change their number in **My Account → Account Management** by clicking **Change** next to **Phone Number** and typing the code sent to the new number. Then:

- their login number, account phone and any saved addresses with the old number all move to the new one;
- the old number and the account email both get a message, in case someone else made the change;
- past orders keep the number they were placed with.

**If a customer can no longer get texts on their old number:**

1. Go to **Users** and click the customer's name.
2. Type the new number in **Login Phone**.
3. Click **Update User**.

The same updates and messages happen, without a code.

## 26.8 Order statuses with their own texts

Orders move through **Placed → Confirmed → Processing → Shipped → Delivered**, or **Returned**. Each status has its own message in **Alpha SMS → Settings**, so customers can get a text at each step. When Steadfast picks up or delivers a parcel, the order's status changes by itself and the matching text goes out.

## 26.9 Abandoned-cart text

A shopper who leaves items in their cart gets one text with a link back to it, sent with the first reminder email. Only one text goes out per cart, to keep costs down and avoid nagging. Switch it off in **Theme Options → General** ([2.5](02-theme-options.md#25-general)).

## 26.10 Customer list for SMS campaigns

**Kawaii Life → SMS Contacts** downloads a file ready to upload to your Alpha SMS panel (steps in [20.1](20-sms-email-newsletter.md#201-sms-alpha-sms)). It has:

- each customer's number once, written the way Alpha SMS expects (8801XXXXXXXXX);
- their name, number of orders, last order date and total spent;
- no numbers that appear only on failed or cancelled orders.

💡 Every customer is on the list for now. If you want only customers who agreed to promotional texts, ask Revo Interactive to add a choice for that.

💡 Staff logging in on the WordPress admin page get their code from Alpha SMS's own login check, set in **Alpha SMS → Settings**. Customers never see it.

---

← [25. Quick answers](25-quick-answers.md) · [Contents](../README.md)
