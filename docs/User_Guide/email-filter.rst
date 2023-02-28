EmailFilter
===========

Overview
````````

This extension allows you to prevent unauthorised access to certain domains or email addresses on your store.

.. note::
    Hope you are able to successfully install the module.

How to configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/emailfilter/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/emailfilter/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields

    * **Module Enable**: Choose ``Enable`` to use the functions of this module.
    * **Registration Email Restriction Enable**: If you select ``Enable``, you can avoid entering an unwanted email address on the Register Page. 
    * **Checkout Email Restriction Enable**: If you select ``Enable``, you can avoid entering an unwanted email address on the Checkout Page.
    * **Contact Us Email Restriction Enable**: If you select ``Enable``, you can avoid entering an unwanted email address on the Contact Us Page.
    * **Newslatter Email Restriction Enable**: If you select ``Enable``, you can avoid entering an unwanted email address on the Newslatter.
    * **Email Domain Restriction**: In this field, you have to specify which domain or which types of email you restrict on your website.

.. note::
    Now save the configuration and cache flush.


.. note::
    
    Now we have applied EmailFilter to some front-end default forms; see the images below.

:guilabel:`Register Form`

    .. figure:: img/emailfilter/Create-New-Customer-Account.png
        :alt: Register Form

:guilabel:`Contact-Us Form`

    .. figure:: img/emailfilter/Contact-Us.png
        :alt: Contact-Us Form

:guilabel:`Checkout Page`

    .. figure:: img/emailfilter/Checkout.png
        :alt: Checkout Page

:guilabel:`Newslatter`

    .. figure:: img/emailfilter/Newslatter.png
        :alt: Contact-Us Form