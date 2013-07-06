

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


Constants
^^^^^^^^^

plugin.tx\_extendedshop\_pi1

.. ### BEGIN~OF~TABLE ###

.. container:: table-row

   Property
         Property:
   
   Data type
         Data type:
   
   Description
         Description:
   
   Default
         Default:


.. container:: table-row

   Property
         file.templateFile
   
   Data type
         String
   
   Description
         Template file
   
   Default
         EXT:extendedshop/pi1/shop.html


.. container:: table-row

   Property
         file.cssFile
   
   Data type
         String
   
   Description
         CSS file
   
   Default
         EXT:extendedshop/pi1/stileShop.css


.. container:: table-row

   Property
         file.cssMail
   
   Data type
         String
   
   Description
         This is the style file to be used in the order confirmation
   
   Default
         EXT:extendedshop/pi1/stileShop.css


.. container:: table-row

   Property
         priceDec
   
   Data type
         Numeric
   
   Description
         Number of decimals
   
   Default
         2


.. container:: table-row

   Property
         priceDecPoint
   
   Data type
         string
   
   Description
         Decimal separator
   
   Default
         ,


.. container:: table-row

   Property
         priceThousandPoint
   
   Data type
         String
   
   Description
         Thousand separator
   
   Default
         .


.. container:: table-row

   Property
         clickEnlarge\_list
   
   Data type
         Boolan
   
   Description
         Set to 1 if you want to open a popup when the user clicks over the
         image in the list mode. If 0 the image is a link to the detail of the
         product
   
   Default
         0


.. container:: table-row

   Property
         clickEnlarge
   
   Data type
         Boolean
   
   Description
         Set to 1 if you want to open a popup when the user clicks over the
         image in the detail mode
   
   Default
         1


.. container:: table-row

   Property
         listMode
   
   Data type
         Boolean
   
   Description
         0 for the sequential listing, 1 for the table listing.
   
   Default
         0


.. container:: table-row

   Property
         listMaxItems
   
   Data type
         Numeric
   
   Description
         If modeImage==0, this is the max number of items to show in a page.
         (list mode)
   
   Default
         5


.. container:: table-row

   Property
         columnWidth
   
   Data type
         Numeric
   
   Description
         Min-Width of the column (table mode)
   
   Default
         140


.. container:: table-row

   Property
         numColumns
   
   Data type
         Numeric
   
   Description
         Number of products for row (table mode)
   
   Default
         4


.. container:: table-row

   Property
         numRows
   
   Data type
         Numeric
   
   Description
         Number of rows for page (table mode)
   
   Default
         2


.. container:: table-row

   Property
         pidBasket
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'basket' is located
   
   Default


.. container:: table-row

   Property
         pidUserInfo
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'User info' is located
   
   Default


.. container:: table-row

   Property
         pidOrders
   
   Data type
         Numeric
   
   Description
         Folder where the orders summaries should be stored
   
   Default


.. container:: table-row

   Property
         pidUsers
   
   Data type
         Numeric
   
   Description
         Folders where customer profiles are stored
   
   Default


.. container:: table-row

   Property
         pidPayment
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'Payment' is located
   
   Default


.. container:: table-row

   Property
         pidDelivery
   
   Data type
         Numeric
   
   Description
         Page were product's receiver will be stored, if different from the
         acquirer
   
   Default


.. container:: table-row

   Property
         pidFinalize
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'Finalize' is located
   
   Default


.. container:: table-row

   Property
         freeDelivery
   
   Data type
         Numeric
   
   Description
         Min amount for a free delivery.
   
   Default
         55,00


.. container:: table-row

   Property
         pidProductPage
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'Product Page' is located
   
   Default


.. container:: table-row

   Property
         minAmount
   
   Data type
         Numeric
   
   Description
         Min amount for an order.
   
   Default
         0,00


.. container:: table-row

   Property
         pidCategoryPage
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'Category Page' is located
   
   Default


.. container:: table-row

   Property
         fromEmail
   
   Data type
         String
   
   Description
         Email of the sender of the order confirmation
   
   Default
         `MyShop@mySite.com <mailto:MyShop@mySite.com>`_


.. container:: table-row

   Property
         fromName
   
   Data type
         String
   
   Description
         Name of the sender of the order confirmation
   
   Default
         MyShop


.. container:: table-row

   Property
         pidSupplierPage
   
   Data type
         Numeric
   
   Description
         Page where the plugin with view mode = 'Supplier Page' is located
   
   Default


.. container:: table-row

   Property
         bccEmail
   
   Data type
         String
   
   Description
         Receive a copy of the order confirmation
   
   Default
         `MyShop@mySite.com <mailto:MyShop@mySite.com>`_


.. container:: table-row

   Property
         group\_customer
   
   Data type
         Numeric
   
   Description
         uid of the group for new customers
   
   Default
         1


.. container:: table-row

   Property
         ordersForPage
   
   Data type
         Numeric
   
   Description
         number of orders in a single page in the ORDERSINFO mode
   
   Default
         5


.. container:: table-row

   Property
         enable\_instock\_management
   
   Data type
         Boolean
   
   Description
         Set to 1 if you want to enable the stock management.
   
   Default
         0


.. container:: table-row

   Property
         insertProduct\_nextPage
   
   Data type
         Boolean
   
   Description
         Set to 0 if you want to go to the basket after the product insertion,
         set to 1 if you want to remain in the same page after the insertion of
         the product.
   
   Default
         0


.. container:: table-row

   Property
         orderCode
   
   Data type
         String
   
   Description
         string to prepend to the order number
   
   Default
         Order\_


.. container:: table-row

   Property
         enableStaticInfoTable
   
   Data type
         Boolean
   
   Description
         Set to 0 if you want want to mantain the old management, set to 1 if
         you want to menage shipping with static\_info\_table.
   
   Default
         0


.. container:: table-row

   Property
         enableUserManagement
   
   Data type
         Boolean
   
   Description
         Set to 0 if you want want to mantain the old management, set to 1 if
         you want to manage users with external extensions.
   
   Default
         0


.. container:: table-row

   Property
         resellersGroupID
   
   Data type
         Numeric
   
   Description
         Indicate the resellers ID group for a different price management for
         resellers
   
   Default


.. container:: table-row

   Property
         allert\_instock\_management
   
   Data type
         Numeric
   
   Description
         Under the quantity the system will advice by mail for the critical
         quantity
   
   Default


.. container:: table-row

   Property
         hideNoTax
   
   Data type
         Boolean
   
   Description
         Set to 1 if you want want hide the NoTax price for non-business
         customers.
   
   Default


.. container:: table-row

   Property
         wrapPriceB
   
   Data type
         wrap
   
   Description
         defines how to wrap the NoTax price.
   
   Default
         ( \| )


.. container:: table-row

   Property
         taxPercent
   
   Data type
         Numeric
   
   Description
         Percentage of tax applied to the price.
   
   Default
         20


.. container:: table-row

   Property
         disableVATUserCheck
   
   Data type
         Boolean
   
   Description
         Disable Italian VAT management: set it to 0 to enable custom Italian
         VAT management
   
   Default
         1


.. container:: table-row

   Property
         wrapWarnings
   
   Data type
         wrap
   
   Description
         Wrapper for warnings in basket and minibasket
   
   Default
         <p>\|</p>


.. container:: table-row

   Property
         taxMode
   
   Data type
         Boolean
   
   Description
         Tax Mode: Set to 1 if you want to insert price tax esclusive.
   
   Default
         0


.. container:: table-row

   Property
         debug
   
   Data type
         Boolean
   
   Description
         Debug Mode: Set to 1 if you want to view debug output.
   
   Default
         0


.. container:: table-row

   Property
         showOriginalPrice
   
   Data type
         Boolean
   
   Description
         Show original price: Set to 1 if you want to view the original price
         if a user or usergroup have a discount.
   
   Default
         0


.. ###### END~OF~TABLE ######

