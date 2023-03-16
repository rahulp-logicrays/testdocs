Quick Order
===========

Overview
````````

The Quick Order Extension allows customers to quickly order products in bulk without navigating the product pages.
Simply enter the SKU and quantity to add items to your cart. A unique feature is the ability to import products into your cart using a CSV file.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/quick-order/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/quick-order/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields
    
    :guilabel:`General`
        * **Enable**: Choose ``Enable`` to use the functions of this module.
        * **Enable Order by SKU on My Account in Storefront**: In this you have three options.
        
            ``Yes,for Specified Customer Groups`` If you choose this option, then you have to choose a customer group from the below drop-down list.

            ``Yes,for Everyone`` If you choose this option, then this functionality will be available to all customers.

            ``No`` If you choose this option, this functionality will not be available to any customers.
    
        * **Customer Groups**: To enable this functionality, select a customer group. You can also select multiple customers.
    
    .. note::

        Now save the configuration and cache flush.

.. note::
    Now we'll look at the front-end functionality of this module.

#. Open the home page of your site. If the extension was successfully installed, then at the header, you can see the ``Quick Order`` button; see the below image.

    .. figure:: img/quick-order/Home-Page.png
        :alt: Home-Page

#. After clicking the ``Quick Order`` button, you will be redirected to the Quick Order Page.

    Here you have to enter a product SKU, then search and select your quantity, and you can directly add your product to your cart.
    see below image.

    .. figure:: img/quick-order/Quick-Order_Page.png
        :alt: Quick-Order_Page

#. Now if you want search multiple product based on SKU then also you can do it by clicking 
    
    ``Enter Multiple SKUs`` see below image.

    .. image:: img/quick-order/mulitiple_sku.gif
        :alt: Multiple-SKU

#. We have made it possible to add products to your cart in bulk. You must first prepare a csv file, which you can then import by clicking on ``Import Skus``, as shown in the image below.

    .. image:: img/quick-order/import_sku.gif
        :alt: Import-SKU