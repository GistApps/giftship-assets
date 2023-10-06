# Giftship - Storefront Assets

This repository contains Shopify snippet assets for Giftship.
If you are using a Vintage theme on Shopify, the assets are already added to your theme files when you install the app.

## Installation

Onboarding instructions are also avaliable in [Giftship's documentation](https://docs.giftship.app/).

The files in this repository are added to the Snippets folder of your Online Store's theme files.

To create a new Snippet from your Shopify admin dashboard:
1. Navigate to the Online Store Sales Channel and open your theme's code editor.
2. In the Snippets directory, select *Add a new snippet* and name the file.
3. Paste the contents of the file from this repository.
4. You can render the snippet in another file using a liquid render tag.

**`{% render 'my-snippet-name' %}`**

## Snippets

**giftship-cart-item.liquid**

**giftship-cart-item-properties.liquid**

These snippets are required if you would like to display display Giftship’s bundle pricing and line item properties on the cart page.

For more information, see [our documentation article on the Product Bundle Install](https://docs.giftship.app/article/installing-product-bundle-snippets/).
