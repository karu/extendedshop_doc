

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


In stock management
^^^^^^^^^^^^^^^^^^^

You can activate the “in stock functionality”, so the products will be
automatically non more available when stocks are out.

#. Go to your typoscript constants editor and set
   enable\_instock\_management to 1.

#. Disable cache for the extension, otherwisesold out product's won't
   disappear. Setplugin.tx\_extendedshop\_pi1 to USER\_INT into your
   template's setup.

#. Fill the 'in stock' field into the product records with the stock
   quantity.

That's all, you'll get an email when a product runs out.

