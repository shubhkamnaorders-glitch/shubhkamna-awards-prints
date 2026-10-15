# Shubhkamna Awards & Prints — free starter website

This is a mobile-friendly static shop catalogue intended for free GitHub Pages hosting.
It includes:
- Product search and category filters
- Sample products and editable sample prices
- Shopping cart with quantity controls
- Customer name, location/PIN code and notes
- WhatsApp checkout message
- Custom order enquiry button
- Responsive mobile layout

## 1. Important setup before publishing

1. Open `index.html` in a text editor.
2. Find this line:
   `const WHATSAPP_NUMBER = "91XXXXXXXXXX";`
3. The starter file is preconfigured with the WhatsApp number provided by the owner. Confirm it is correct before publishing.
   The configured format is country code + number, digits only.
4. Edit the `PRODUCTS` array with your actual product names, prices and descriptions.
   All included products/prices are examples, not verified shop prices.
5. Optional: add `imageUrl: "https://your-image-url.jpg"` to a product to display a real product image.
6. Save the file.

## 2. Test locally

Double-click `index.html` to open it in your browser. Add products to cart and test WhatsApp checkout after setting your own number. The WhatsApp message opens in a new tab/app; the customer sends it manually.

## 3. Publish free on GitHub Pages

1. Create or sign in to a GitHub account at https://github.com/
2. Create a new public repository named `shubhkamna-awards-prints`.
3. Upload `index.html` to the repository root and commit the change.
4. Open repository **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then save.
7. Wait for GitHub Pages to publish the site. The URL will be shown in Settings → Pages, usually like:
   `https://YOUR-USERNAME.github.io/shubhkamna-awards-prints/`

## Limitations

- Hosting is free on GitHub Pages, but the website does not have a server/database or private admin panel.
- To update prices/products, edit `index.html` and upload the new version.
- This starter does not collect online payments. Customers send their order on WhatsApp; you confirm stock, final price, shipping and payment instructions there.
- It does not automatically calculate courier fees, manage inventory, or store customer orders.
- Use your own product photos and confirm image usage rights.
- Add your actual contact details, shipping/returns/privacy policies before promoting the website.


## Premium design notes
- Uses DM Sans and Playfair Display web fonts (internet required for the external font files).
- Includes product-style images from external image hosts. Check each image host's licensing/availability before commercial launch.
- The trophy cutout image credit required by its CC BY 4.0 licence: “Gold Trophy Cup” by BudgetPixel AI (https://budgetpixel.com/images/gold-trophy-cup-7e0a62a3) — CC BY 4.0.
- Replace demo images with photos of your actual stock whenever possible.
