

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


**Change images appearance**
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Every product can be associated with more than one image, so there's
the possibility to create a different appearance for every photo you
selected.

Following the order in the product record selection box, first image
will be created by the default typoscript configuration:

plugin.tx\_extendedshop\_pi1.{image{file.maxW=250imageLinkWrap={$plugi
n.tx\_extendedshop\_pi1.clickEnlarge}imageLinkWrap{enable=1bodyTag=<BO
DYbgColor=black>wrap=<Ahref="javascript:close();">\|</A>width=400JSwin
dow=1JSwindow.newWindow=1JSwindow.expand=17,20}}}

For the following ones you can create your own typoscript code. Use
image2 for the second image, image3 for the third and so on.

For example: if you want the first image to be 200px wide , and all
others images 100px, insert into your custom template this code:

plugin.tx\_extendedshop\_pi1.{image{file.width=200}image2{file.width=1
00}}

image2 configuration applies to the second image and to all the
following ones.

Same rules apply on this images:

\- plugin.tx\_extendedshop\_pi1.listImage: these are the thumbnails in
the product list view mode

-plugin.tx\_extendedshop\_pi1.correlatedImage: images of the
correlated products

If you want all images in a particular product to have the same
apperance you created for image2, you can use the Thumbnails type
field in the product record. Simply insert image2 in the field.

