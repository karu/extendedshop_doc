

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


**Ajax functionalities**
^^^^^^^^^^^^^^^^^^^^^^^^

Webformat Extended Shop allows asynchronous calls for product
navigation and mini-basket updating, to use ajax functionalities you
have to install xajax library extension for TYPO3.

**Product preview**

You can have the datailed view of the product directly into the list
view, instead of loading another page.

In your template setup add this row:

plugin.tx\_extendedshop\_pi1.xajax\_preview = 1

if you still want to have a link to the detail page you can add this
in your template setup:

plugin.tx\_extendedshop\_pi1.xajax\_preview.linkTitle = 0

then create a new link into the shop.html file done as this:

<a href=”#” onclick=”###AJAX\_PREVIEW###”>Preview</a>

**Mini-basket update**

To have the minibasket auto-updating when a new product is putted into
the cart insert this row In your template setup:

plugin.tx\_extendedshop\_pi1.xajax\_cart\_update = 1

Update is connected with a visual effect.. Default animation in inside
the page, otherwise you can activate a full page message.

For the second one add this row in your template setup:

plugin.tx\_extendedshop\_pi1.minibasket\_lightbox = 1

