Call for Price
==============

Overview
````````

Nowadays, some stores or distributors don’t want to display the price of the product on the website; instead, they want to display the information only so that customers must contact the shop owners to ask the price or may bargain the price of the product. Logicrays has developed the Call for Price Magento 2 extension to hide the product prices and :guilabel:`Add to Cart` button and instead display :guilabel:`Call for Price` or any call to action button.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/callforprice/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.


#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/callforprice/Configuration-Settings-Stores-Magento-Admin_0.png
        :alt: module configuration fields
    
    :guilabel:`General`
        * **Call For Price**: Choose ``Enable`` to use the functions of this module.
        * **Call For Price Button Text**: When this module is apply then instead of ``Add to Cart`` button text show whatever you enter in this field. If you check the ``Use System Value`` box, the default value will be used.
        * **Enter Message to show on place of Price**: Whatever text you enter in this field will appear in the frontend in place of the price.
        * **Send Email To**: Enter an email address to send a message to the administrator.
        * **Email Sender**: Select your Emial Sender.
        * **Email Template For Customer**: Select the customer template for mail.
        * **Email Template For Admin**: Select the admin template for mail.
        * **Email Template Status Update**: Select the status update template for the customer.
        * **Customer Groups**: To enable this functionality, select a customer group. You can also select multiple customers. If you check the ``Use System Value`` box, the default value will be used.
        * **Show on Specific Date Range**: If set to yes, the ``Call for Price`` buttons will only be available in the front-end during a particular date range. If No is selected, the functionality will always be available.
  
.. note::
    Now save the configuration and cache flush.


#. Now we have to select some products to enable the functionality of this module.
    
    go to ``Catalog > Products`` see below image.

    .. figure:: img/callforprice/Dashboard-catalog-product.png
        :alt: Catalog Product

#. Here you can see a list of products, and from here you can open a product in Edit mode.

    .. figure:: img/callforprice/Products-Inventory-Catalog-Magento-Admin.png


#. Scroll down after opening a product in Edit mode to see the product attribute that is 
    
    ``Call for Price`` check ``Yes``

    .. figure:: img/callforprice/Joust-Duffle-Bag-Products-Inventory-Catalog-Magento-Admin.png


    .. note::
        Now save the product and flush the cache. You can enable the call for price functionality on any product in the same way.


#. Now open a product in the front-end; this is the ``category page``, as shown in the image below.

    .. figure:: img/callforprice/category_page.png


#. This is the ``product view page``. Here, you can see in place of the ``price``, display some text, and in place of the ``Add to Cart`` button, it's now shows ``Call for Price`` button, based on your admin-side configuration.

    .. figure:: img/callforprice/product-view-page.png

#. This is a ``Sidebar-wishlist`` section.

    .. figure:: img/callforprice/sidebar-wishlist.png

#. This is an ``Wishlist`` Section page.

    .. figure:: img/callforprice/wishlist-section.png

#. This is an ``Add-to-Compare`` page.

    .. figure:: img/callforprice/Add-to-compare.png

#. When we click the button ``Call for Price``, a popup form appears, as shown in the image below.

    .. image:: img/callforprice/popup.gif


    .. note::

        After filling out the form and submitting it, one email is sent to the ``Customer`` and another to the ``Administrator``. You can see the images below.


#. Customer Mail sent

    .. figure:: img/callforprice/Customer-mail.png


#. Admin recevied request

    .. figure:: img/callforprice/Admin-side-mail.png

#. Now you have to check admin side grid. Simply go to ``Logicrays > Call For Price > Manage Request`` see below image.

    .. figure:: img/callforprice/Grid.png

#. After click on ``Manage Request`` then you can redirect to ``Admin Grid`` see below image.
    
    If you wish to Edit details, simply click on ``Edit``.
    
    .. figure:: img/callforprice/Admin_Grid.png

#. When processing is done on your request, admin will change the status from ``New`` to ``Complete``.
    
    Concerning the status update email sent to the customer. Please see the image of the mail below.
    
    .. figure:: img/callforprice/Status-Update-mail.png