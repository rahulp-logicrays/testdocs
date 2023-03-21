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
        :alt: Configuration Settings

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/product-inquiry/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields
    
    :guilabel:`General`

        * **Enable**: Choose ``Enable`` to use the functions of this module.
        * **Guest**: In this field, you have to choose either ``Yes`` or ``No``. If you choose ``Yes,`` then this functionality will work for guest customers.
        * **Send Admin Email**: In this field, you have to choose either ``Yes`` or ``No``. If you choose ``Yes,`` then Mail Send functionality becomes active. And you have to configure the fields below.
        
            * **Email sender**: You have to select your email sender from the drop-down list.
            * **Send Email To**: In this field, you have to enter your administrator's email address.
            * **Admin Email Template**: Select the admin template for mail.
            * **Customer Email Template**: Select the customer template for mail.
            * **Admin Response Email Template**: Select the response template for mail.
        * **Show Frontend Question/Answers**: In this field, you have to choose either ``Yes`` or ``No``. If you choose ``Yes,`` then particular products' queries are shown in the front end. If you select ``no,`` then it will not.
    
    .. note::

        Now save the configuration and cache flush.

.. note::
    Now we'll look at the front-end functionality of this module.

#. Open the front end of your store.

    And open the product detail page of any product's. and scroll down your page here, you can see one tab that is ``Product Inquiry``. You must fill out a form in this tab if you have any questions.

    .. figure:: img/product-inquiry/Product-Detail-Page.png
        :alt: Product Details page

#. After click on ``Send Inquiry`` button then your form successfully send the request to admin. Now you have to check Admin Request then go to ``Logicrays > ProductInquiry > ProductInquiry Details``.
    
    see below image.

    .. figure:: img/product-inquiry/Dashboard-Magento-Admin_1.png
        :alt: Dashboard-Magento-Admin

#. You must be redirected to the admin side grid after clicking on the above path. see below image.

    .. figure:: img/product-inquiry/Product-Admin-Grid.png
        :alt: Inquiry form

#. By clicking the Edit button, you can now edit the record. The Edit form appears after you click the Edit button. In this form, you can edit the records and also reply to the customer's questions.

    .. figure:: img/product-inquiry/Product-Inquiry-Edit-form.png
        :alt: Product-Inquiry-Edit-form

#. After saving the admin's responses, you can view them on the frontend.
    
    .. figure:: img/product-inquiry/Admin-Response.png
        :alt: Admin-Response

.. note::
    After filling out the form and submitting it, one email is sent to the Customer and another to the Administrator. You can see the images below.

#. Customer received mail.

    .. figure:: img/product-inquiry/Customer-Mail.png
        :alt: Customer-Mail

#. Admin received mail.

    .. figure:: img/product-inquiry/Admin-Mail.png
        :alt: Admin-Mail

#. Admin response mail to customer.

    .. figure:: img/product-inquiry/Admin-Mail-Response.png
        :alt: Admin-Mail-Response