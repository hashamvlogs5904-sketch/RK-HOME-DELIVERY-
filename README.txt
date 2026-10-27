RK HOME DELIVERY — WEBSITE FILES
=================================

Files:
- index.html: responsive mobile-friendly ordering website.

Current setup:
- Shop name: RK Home Delivery
- Shops: Sneha Chicken Center + RK Electronics
- Delivery area: Ippaipally Village only
- WhatsApp order number: 6301485904
- Product prices are intentionally set to “Price on request” until you provide real prices.

HOW TO TEST:
1. Open index.html in a browser.
2. Add items to cart.
3. Enter customer details and tap WhatsApp order.
4. WhatsApp opens with the order message prepared. The customer must press Send.

HOW TO PUBLISH FREE:
1. Create/sign in to a GitHub account.
2. Create a new public repository named rk-home-delivery.
3. Upload index.html to the repository root.
4. In repository Settings -> Pages, select Deploy from a branch, choose main and /(root), then Save.
5. GitHub will provide the public website URL after publishing.

IMPORTANT:
- A free static website can prepare an order message and open WhatsApp, but it does not automatically store orders in a private admin dashboard.
- Do not add customer payment details or sensitive information to a public repository.
- To change the WhatsApp number, edit WHATSAPP_NUMBER in index.html to country code + number without + or spaces (India example: 91XXXXXXXXXX).
- To add prices, edit the products array in index.html. Replace price:null with a number, e.g. price:180.
- Test all products and order messages before sharing the website publicly.
