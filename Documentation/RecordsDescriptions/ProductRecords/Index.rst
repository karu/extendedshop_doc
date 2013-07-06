

.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. ==================================================
.. DEFINE SOME TEXTROLES
.. --------------------------------------------------
.. role::   underline
.. role::   typoscript(code)
.. role::   ts(typoscript)
   :class:  typoscript
.. role::   php(code)


Product records
^^^^^^^^^^^^^^^

To insert a product you can follow the link “Create new record” and
select “WebformatShop - products”. There are a lot of fields you can
use:

- Itemnumber: the code of the product (required)

- Title: the name of the product (required)

- Page title:the title of the page in the detail page of the product. If
  empty than the “Title” of the product will become the page title. This
  is true only if you have configured in the TypoScript this
  functionality.

- Summary: a short description of the product.

- Description: a complete description of the product.

- Image: the product images.

- Price: the product price.The point (.)is the decimal separator.
  Warning: if you want to insert the value ‘155.20’ you must write
  ‘155.2’, if you don’t follow this tip TYPO3 will generate a warning
  message.

- VAT: Value Added Tax.You have to create some“VAT option” record in a
  Sys Folder

- In stock: number of items available for selling.

- Category: the category of the product. You must use toi\_category
  extension for this purpose

- www: an external url.

- Ordered: shows the number of orders for this product.

- Weight: weight of the product. Soon the wss\_dhl extension will be
  available for the automaticreckoning of the shipping price for the DHL
  carrier.

- Volume: volume of the product. Soon the wss\_dhl extension will be
  available for the automaticreckoning of the shipping price for the DHL
  carrier.

- Offer price:the new price. If this field is filled, the new price of
  the product is this and the discount percentage will be calculated
  automatically.

- Discount:the percentage of discount. If this field is filled, the
  offer price will be calculated automatically. To be used only ifoffer
  price is empty.

- Sizes: the sizes of the product. If more then one the values need to
  be separated be the special character “!”

- Colors: as for sizes.

- Correlated products: the products that are correlated with this. You
  can select them from the list of the existing products.

- Documents list: you can include brochures or digital documentation
  relative to the product

- Document labels: here you can specify the labels displayed for related
  documents separating them with new line.

- Correlated pages: select one or more pages of your website which are
  related with this product

- Direct Price: price made to you by the supplier.

- Supplier: select here the supplier from a list of website users

- Thumbnails type: select which configuration to apply to images. For
  more information look at the 'Images configuration' section

- Categories: you can assign some toi\_categories to the products to let
  you organize them when you use 'Category Mode' in the plugin.

- Max items for order: you can define the maximum number of items at
  time that can be ordered.

You have the possibility to increase the number of fields available
for the product, see 'Adding product fields' section.

