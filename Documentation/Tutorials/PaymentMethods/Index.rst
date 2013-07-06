

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


**Payment methods**
^^^^^^^^^^^^^^^^^^^

Default methods available are bank transfer and cash on delivery.

This is the typoscript setup to modify

plugin.tx\_extendedshop\_pi1.payment{10.title=Bank Transfer10.message=
Insert here the information for the
payment10.image.file=10.priceTax=10.priceNoTax=20.title=Cash on delive
ry(+3,00EURO)20.image.file=20.priceTax=3,0020.priceNoTax=20.maxAmount=
10020.minAmount=50}

\- title: labels for radio input

\- message: text shown in finalize page

\- image.file: path of an image to be shown near radio input

\- priceTax: price increment when this option is choosen

\- priceNoTax: same as before, but without taxes

\- maxAmount: max total products price for this option to be available

\- minAmount: min total products price for this option to be available

There is also the opportunity to use other preconfigured payment
gateways like “Credit Card with PayPal”, “Credit Card with Banca
Sella” and “Credit Card with Hosted Payment Page” by installing,
respectively, these extensions: wss\_paypal, wss\_bancasella and
wss\_constriv.

