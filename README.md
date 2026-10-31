# xSu — free starter storefront

This is a static, mobile-friendly fashion storefront. It includes sample products, category filters, a shopping bag, and WhatsApp order submission.

## Before publishing
1. Open `index.html` in a text editor.
2. In the `STORE SETUP` section near the bottom, replace:
   - `WHATSAPP_NUMBER` with your WhatsApp number including country code, digits only (India example: `919876543210`).
   - `UPI_ID` with your actual business UPI ID.
   - `STORE_EMAIL` with your contact email.
3. Replace the sample product names, prices, and image URLs in the `products` array with your real catalogue.
4. Test the page locally by opening `index.html` in a browser.

## Publish free with GitHub Pages
1. Create/sign in to a GitHub account at https://github.com
2. Create a **public** repository named `xsu-store`.
3. Upload `index.html` to the repository root (the top-level folder).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
6. Wait for the Pages deployment to finish. Your site address will look like `https://YOUR-GITHUB-USERNAME.github.io/xsu-store/`.

## Important limitations
- Hosting on GitHub Pages is free, but this starter has no server/database, stock management, customer accounts, or automatic order dashboard.
- Orders are sent to your WhatsApp. Keep WhatsApp Web/app available and confirm each order manually.
- UPI is not automatically collected or verified by this site. The UPI ID is included in the WhatsApp order message; send payment instructions/QR to the customer and verify payment in your bank/UPI app before dispatch.
- COD orders are requests only until you confirm them.
- A custom domain, payment gateway, shipping integrations, and automated tax/invoice workflows may have costs.
- Add accurate product information, return/refund policy, shipping policy, privacy policy, and business contact details before accepting public orders.
- Use only product photos you own or have permission to use. The included Unsplash photos are demo imagery and should be replaced with photos representing your actual products.
