

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


Setup
^^^^^

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
         RequiredFields
   
   Data type
         String
   
   Description
         List of the required fields for the integrated user registration
   
   Default
         name,address,city,zip,state,phone,email,authorization,conditions


.. container:: table-row

   Property
         RequiredFieldsSymbol
   
   Data type
         String
   
   Description
         Symbol that indicats a required field
   
   Default
         \*


.. container:: table-row

   Property
         orderEmail\_htmlmail
   
   Data type
         Boolean
   
   Description
         Send the order confirmation in HTML
   
   Default
         1(deprecated)


.. container:: table-row

   Property
         plainTextEmail
   
   Data type
         Boolean
   
   Description
         Set this to 1 if you want a plain text email instead of an HTML email
         when finalizing orders
   
   Default
         0


.. container:: table-row

   Property
         list.linkTitle
   
   Data type
         Boolean
   
   Description
         Set to 1 if you want the product title link to the detail view
   
   Default
         1


.. container:: table-row

   Property
         requiredDeliveryFields
   
   Data type
         String
   
   Description
         Required fields in the delivery address form
   
   Default
         name,address,city,zip,state,country


.. container:: table-row

   Property
         freeShippingMessage
   
   Data type
         Boolean
   
   Description
         Set this to 1 if you want to show a free shipping message instead of
         Price 0
   
   Default
         0


.. container:: table-row

   Property
         switchDeliveryIfEmpty
   
   Data type
         Boolean
   
   Description
         Set this to 1 if you want to show delivery address equal to billing
         address when delivery address is empty
   
   Default
         0


.. container:: table-row

   Property
         max\_for\_order
   
   Data type
         Numeric
   
   Description
         This is the max number of items for every single product in the cart
   
   Default
         999


.. container:: table-row

   Property
         clearBasketOnLogout
   
   Data type
         Boolean
   
   Description
         Set this to 1 if you want to clear basket on logout
   
   Default
         0


.. container:: table-row

   Property
         detail\_showListIfEmptyProduct
   
   Data type
         Boolean
   
   Description
         Set to 1 if list of product must be shown when Product Page Mode dont
         have a specified product to show.
         
         This configuration is usefull if you need to place a plugin in list
         mode and a plugin in product page mode in the same page.
   
   Default
         1


.. container:: table-row

   Property
         xajax\_preview
   
   Data type
         Boolean
   
   Description
         Set to 1 to activate tha Ajax visualization of the product list
   
   Default
         0


.. container:: table-row

   Property
         xajax\_preview.id
   
   Data type
         String
   
   Description
         Prefix for the id attribute of the tag to be updated by tha ajax
         function. Original id will be the uid number of the product
   
   Default
         shop\_product\_


.. container:: table-row

   Property
         xajax\_preview.linkTitle
   
   Data type
         Boolean
   
   Description
         Set to 0 if you want the product title link to the detail view,
         otherwise set to 1 open the preview
   
   Default
         1


.. container:: table-row

   Property
         xajax\_cart\_update
   
   Data type
         Boolean
   
   Description
         Set to 1 to updateasynchronously the minibasket when a product is
         loaded into the cart
   
   Default
         0


.. container:: table-row

   Property
         minibasket\_id
   
   Data type
         String
   
   Description
         Id attribute of the tag to be updated when a product is loaded into
         the cart
   
   Default
         shop\_minibasket


.. container:: table-row

   Property
         minibasket\_lightbox
   
   Data type
         Boolean
   
   Description
         Set to 1 to activate a full screen message when the cart is updated
   
   Default
         0


.. container:: table-row

   Property
         defaultCountry
   
   Data type
         String
   
   Description
         Default country for the delivery address
   
   Default
         ITA


.. container:: table-row

   Property
         countryTabIndex.personal
   
   Data type
         Numeric
   
   Description
         Tab order for the country list in personal info form
   
   Default
         6


.. container:: table-row

   Property
         countryTabIndex.delivery
   
   Data type
         Numeric
   
   Description
         Tab order for the country list in delivery address form
   
   Default
         25


.. container:: table-row

   Property
         dateFormat
   
   Data type
         String
   
   Description
         Date Format for the ###DATE### marker
   
   Default
         d/m/Y


.. container:: table-row

   Property
         searchFields
   
   Data type
         String
   
   Description
         Select the field where the search should look into
   
   Default
         code,title


.. container:: table-row

   Property
         quantity\_input
   
   Data type
         Boolean
   
   Description
         Set 1 if the quantity selector should be a text input, otherwise 0 for
         a select input
   
   Default
         0


.. container:: table-row

   Property
         tax\_mode
   
   Data type
         Boolean
   
   Description
         If 0 price inserted into product record is evaluted as tax included,
         set 1 if the price inserted is tax excluded
   
   Default
         0


.. ###### END~OF~TABLE ######

**Images**

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
         Image
   
   Data type
         Image
   
   Description
         Images of the product, used in the detail view
   
   Default


.. container:: table-row

   Property
         zoomimage
   
   Data type
         Image
   
   Description
         Image used for the zoom link
   
   Default


.. container:: table-row

   Property
         listImage
   
   Data type
         Image
   
   Description
         Images of the product, used in the list view
   
   Default


.. container:: table-row

   Property
         listImage.link\_to\_details
   
   Data type
         Boolean
   
   Description
         Links the image in list view to the detail view
   
   Default


.. container:: table-row

   Property
         ordersImage
   
   Data type
         Image
   
   Description
         Configuration for the images in the customer orders info view
   
   Default


.. container:: table-row

   Property
         next
   
   Data type
         Image
   
   Description
         Configuration for the image used as link to the next product
   
   Default


.. container:: table-row

   Property
         previous
   
   Data type
         Image
   
   Description
         Configuration for the image used as link to the previous product
   
   Default


.. container:: table-row

   Property
         correlatedImage
   
   Data type
         Image
   
   Description
         Set how the correlated products images should appear
   
   Default


.. ###### END~OF~TABLE ######

**Page Browser**

plugin.tx\_extendedshop\_pi1.pageBrowser

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
         maxPages
   
   Data type
         Numeric
   
   Description
         Max number of pages shown for window pagination
   
   Default
         7


.. container:: table-row

   Property
         showResultCount
   
   Data type
         Boolean
   
   Description
         Show the total count of items.
   
   Default
         1


.. container:: table-row

   Property
         dontLinkActivePage
   
   Data type
         Boolean
   
   Description
         Set to 1 to avoid the linking of the active page
   
   Default
         1


.. container:: table-row

   Property
         tableParams
   
   Data type
         String
   
   Description
         Parameters of the page browser table tag
   
   Default
         cellpadding="2" align="center"


.. container:: table-row

   Property
         showFirstLast
   
   Data type
         Boolean
   
   Description
         Show “First” and “Last” page link
   
   Default
         1


.. container:: table-row

   Property
         showRange
   
   Data type
         Boolean
   
   Description
         Show the range of the items displayed.
   
   Default
         1


.. container:: table-row

   Property
         disabledLinkWrap
   
   Data type
         wrap
   
   Description
         Wrap for disabled page links
   
   Default
         <span style="color:#bbb;">\|</span>


.. container:: table-row

   Property
         inactiveLinkWrap
   
   Data type
         wrap
   
   Description
         Wrap for inactive page link
   
   Default
         \|


.. container:: table-row

   Property
         activeLinkWrap
   
   Data type
         wrap
   
   Description
         Wrap for active page link
   
   Default
         <strong>\|</strong>


.. container:: table-row

   Property
         showResultsWrap
   
   Data type
         wrap
   
   Description
         Wrap for whole results count
   
   Default
         \|<br />


.. container:: table-row

   Property
         showResultsNumbersWrap
   
   Data type
         wrap
   
   Description
         Wrap for results count numbers
   
   Default


.. container:: table-row

   Property
         browseBoxWrap
   
   Data type
         wrap
   
   Description
         Wrap for the whole browser box
   
   Default


.. ###### END~OF~TABLE ######

plugin.tx\_extendedshop\_pi2

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
         templateFile
   
   Data type
         String
   
   Description
         Template file
   
   Default
         EXT:extendedshop/pi2/shop.html


.. ###### END~OF~TABLE ######

