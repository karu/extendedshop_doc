

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


Basket hooks
^^^^^^^^^^^^

#. saveCustomFieldsInBasket:this can be used to save custom fields in the
   cookie;

#. getShippingTitle: this can be used to modify the shipping Title before
   showing it to the user;

#. getShippingPriceTax: this can be used to modify the shipping price
   with Tax included before showing it to the user;

#. freeshipping: this can be used to modify the freeshipping stringshown
   to the user (instead of '0');

#. getShippingPriceNoTax: this can be used to modify the shipping price
   without Tax included before showing it to the user;

#. checkFreeShipping: this can be used to force “free shipping”.

