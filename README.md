# Giftship - Storefront Assets

This repository contains Shopify snippet and template assets for Giftship.
If you are using a Vintage theme on Shopify, the assets are already added to your theme files when you install the app.

## Installation

Onboarding instructions are also avaliable in [Giftship's documentation](https://docs.giftship.app/).

The files in this repository are added to the Snippets and Templates folders of your Online Store's theme files.

The following steps show how to create a Snippet. For the "collection.giftship.liquid" Template, only steps 1-3 are required and the file should be added to the **Templates directory**.

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

## Templates

**collection.giftship.liquid**

This template file is required for displaying Collection Filters in Giftship's Box Builder tool.

The file does not need to be referenced elsewhere in your theme files, however, setup may be required via Shopify's Search and Discovery app for the filters to display correctly. For more information, see our [documentation article on Collection filters](https://docs.giftship.app/article/displaying-collection-filters-in-your-box-builder-%f0%9f%8e%81/).
