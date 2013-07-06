

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


**Mini basket**
^^^^^^^^^^^^^^^

A plugin to show a mini-basket in your website is also available. This
is a typoscript setup integration example :

page.20 < plugin.tx\_extendedshop\_pi2

If you make any change to the configuration of this plugin (ie you
want to use a custom html file as template) add this row after your
modifications:

plugin.tx\_extendedshop\_pi1.minibasket\_conf <
plugin.tx\_extendedshop\_pi2

