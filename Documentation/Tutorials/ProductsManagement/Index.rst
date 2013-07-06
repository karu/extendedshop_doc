

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


Products management
^^^^^^^^^^^^^^^^^^^

Let's create the products pages

#. Insert the Extended Shop plugin into your products page and set the
   view mode to 'product list'. If the products are located into another
   page you need to set the Starting Point.

#. You can already insert some products. In list module create a new
   “WebformatShop – Products” record. Required fields are item-number and
   title.There are a lot of useful fields (size, color, images etc.), for
   a detailed description look at the “Product records” section.

You can use another page as detailed view:

#. Create a new page, insert the Extended Shop plugin and set view mode
   to 'product page'.

#. Set the pidProductPage TypoScript constant to the uid of this page.

You can also create references to other products in the same category
or from the same supplier:

#. Create the categories you want with the toi\_category extension, then
   create the associations with the products

#. Create a new page, insert the Extended Shop plugin and set view mode
   to 'category page'.

#. Set pidCategoryPage constant to this page.

#. Create the suppliers as website users, and join them with the related
   products

#. Create a new page, insert the Extended Shop plugin and set view mode
   to 'supplier page'.

#. Set pidSupplierPage constant to this page.

To see more view modes for the Extendedshop plugin go to'Plugin
configuration'section.

