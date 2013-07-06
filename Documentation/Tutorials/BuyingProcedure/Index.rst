

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


Buying procedure
^^^^^^^^^^^^^^^^

Let's start creating the required pages for the buying procedure.

In this tutorial we'll use sr\_feuser\_registration for user
registration .

#. Create a sysfolder and call it Orders, then set the pidOrders constant
   to this folder

#. Create another sysfolder to store users and set the pidUsers constant
   to this folder

#. Create a new page for the cart, into this page insert the Extended
   Shop plugin and set View mode to basket

#. Set pidBasket constant to this page

#. From now on the customer must be logged in, so create a new page and
   insert the frontend login plugin for the login of already registered
   users, and the sr\_feuser\_registration plugin for allow new clients
   to register.Insert the Extended Shop plugin and set View mode to User
   Registred, set the access property to the customers group.

#. Set pidUserInfo constant to this page

#. Create a new page, insert the Extended Shop plugin and set View mode
   to Payment.

#. Set pidPayment constant to this page

#. Create a new page, insert the Extended Shop plugin and set View mode
   to Finalize.

#. Set pidFinalize constant to this page

#. Now you have to configure the payment and the shipping methods.
   Default ones are bank transfer and cash on delivery. Go to 'Payment
   methods' and 'Shipping methods' section to know more.

