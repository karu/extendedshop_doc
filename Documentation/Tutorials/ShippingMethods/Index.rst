

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


Shipping methods
^^^^^^^^^^^^^^^^

You can choose different Shipping methods and costs for any country
you like. Static\_info\_tables is required for this section

#. Create a new page (a sysfolder is suggested) where shipping methods
   should be stored.

#. Into this page create a 'shipping country' record and select country
   (e.g. Italy).

#. Click on 'create new' into the new shipping country form, open and
   fill the newly created record with at least a title (ie the carrier
   name) and the price.

Now all customers from Italy will have this shipping method available
during their buying procedure. You can add a lot of different shipping
methods for the same country.

You can also use preconfigured shipping methods like “DHL Shipping
method” by installing the extension wss\_dhl.

