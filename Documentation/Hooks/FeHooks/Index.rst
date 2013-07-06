

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


FE hooks
^^^^^^^^

#. checkReturnValues: this can be used to do register parameters to be
   intercepted to decide if user is coming back from an online payment;

#. processAdvancedSearch: this can be used to manage the advanced search
   behaviour;

#. evaluateCustomBasketTotals: this can be used to manage custom total
   prices;

#. evaluateBasketArray: this can be used to manage the basket settings;

#. after\_finalization\_process: this can be used to do something after
   order finalization;

#. getDefaultConfiguration: this is used to init the payment options with
   external payment extensions;

#. evaluateShippingConfArray: thiscan be used to modify the shipping
   confArray before showing it to the user.

