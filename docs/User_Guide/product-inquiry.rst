Product Inquiry
===============

Overview
````````

This extension will help customers: when they have any doubts about products, they can send inquiries, and admin can give a response according to them.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/product-inquiry/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/product-inquiry/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields
    
    :guilabel:`General`

        * **Enable**: Choose ``Enable`` to use the functions of this module.
        * **Send Email**: In this field, you have to choose either ``Yes`` or ``No``. If you choose ``Yes,`` then Mail Send functionality becomes active. And you have to configure the fields below.
        
            * **Email sender**: You have to select your email sender from the drop-down list.
            * **Copy to email**: In this field, you have to enter your administrator's email address.
            * **Name**: In this field, you have to enter your administrator's name.
            * **Admin Template**: Select the admin template for mail.
            * **Customer Template**: Select the customer template for mail.
            * **Response Template**: Select the response template for mail.
        * **Show Frontend Question/Answers**: In this field, you have to choose either ``Yes`` or ``No``. If you choose ``Yes,`` then particular products' queries are shown in the front end. If you select ``no,`` then it will not.
    
    .. note::

        Now save the configuration and cache flush.

.. note::
    Now we'll look at the front-end functionality of this module.

#. Open the front end of your store.

    And open the product detail page of any product's. and scroll down your page here, you can see one tab that is ``Product Inquiry``. You must fill out a form in this tab if you have any questions.

    .. figure:: img/product-inquiry/Product-Detail-Page.png
        :alt: Inquiry form

#. After click on ``Send Inquiry`` button then your form successfully send the request to admin. Now you have to check Admin Request then go to ``Logicrays > ProductInquiry > ProductInquiry Details``.
    see below image.

    .. figure:: img/product-inquiry/Dashboard-Magento-Admin_1.png
        :alt: Inquiry form

#. You must be redirected to the admin side grid after clicking on the above path.