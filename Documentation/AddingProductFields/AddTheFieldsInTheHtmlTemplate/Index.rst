

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


Add the fields in the HTML template
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You need to update the HTML template in order to include the fields
you have defined (remember to use upper case for field name).

The model for markers you have to use in the HTML template is like
###PRODUCT\_[fieldName]### for the value of field and
###LABEL\_[fieldName]### for the label.

You have also to add language labels for the additional database
fields, adding those lines to TypoScript Setup:

plugin.tx\_extendedshop\_pi1.\_LOCAL\_LANG.[languageCode].LABEL\_[fiel
dName] = [fieldLabel]

