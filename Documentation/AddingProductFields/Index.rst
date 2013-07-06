

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


Adding product fields
---------------------

The simplest way to add field on products records extending the
tx\_extended shop table is to create a small extension that will
define the required fields in the database and the TCA. Your small
extension will not contain any plugin or other processing.

The Extension Repository Kickstarter (kickstarter) extension is a
wizard that will help you create this small extension. Install it
using the Extension Manager. Once installed, you access the
Kickstarter Wizard through the Extension Manager Backend module. There
is a tutorial on how to use the Kickstarter Wizard. Just remember that
you will not need to create any plugin or TypoScript.

Once your extension is created, install it. This will make the fields
you have defined available to all other extensions.


.. toctree::
   :maxdepth: 5
   :titlesonly:
   :glob:

   AddTheFieldsInTheHtmlTemplate/Index

