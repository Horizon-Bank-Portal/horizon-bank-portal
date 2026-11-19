# Horizon Bank Demonstration Website

This is a **front-end preview** for a fictional bank-style demonstration website. It is not a real bank website.

## Open the preview
1. Unzip the project.
2. Open `index.html` in Safari, Chrome, or Edge.
3. Choose **Customer view** or **Admin demo**.
4. In Admin demo, add sample customers and simulated transactions.

## Important preview limitations
- This preview stores data in the browser's local storage.
- Data is not shared between devices or browsers.
- The admin preview has no secure login.
- It must not be used for real customer information, real account records, payment processing, or proof of funds.
- All records must remain clearly labelled as simulated.

## Next stage for a real hosted demonstration
To make customer profiles shared across devices and give each demo customer a private login, connect:
- **GitHub Pages** (free static website hosting)
- **Supabase** (authentication and database; configure row-level security)

Do not publish database secret/service-role keys in website code. The secure multi-user stage needs server-side permissions and testing before public deployment.
