Stock Notification
==================

Overview
````````

This extension allows customers to subscribe to ``out-of-stock`` products, and when they are back in ``stock``, they are notified via email and text message.

.. note::
    Hope you are able to successfully install the module.

.. important::
    Before using this extension, please run the command.
    ``php bin/magento cron:run``

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/stocknotification/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the images.

    .. figure:: img/stocknotification/Configuration-Settings-Stores-Magento-Admin_0.png
        :alt: module configuration fields
    
    :guilabel:`General`
        * **Module Enable**: Choose ``Enable`` to use the functions of this module.
        * **Select Customer Groups**: To enable this functionality, select a customer group. You can also select multiple customers.
        * **Email Sender**: Select your Emial Sender.
        * **Notification Type**:Choose what type of notification you want to send to the customer. ``SMS``, ``Email`` or ``SMS and Email Both``.
        * **Admin Email For Out Of Stock Notification**: Enter an email address to send a message to the administrator.
        * **Out Of Stock Notification Email Template For Customer**: Select the customer template for mail.
        * **Out Of Stock Notification Email Template For Admin**: Select the admin template for mail.
        * **Instock Notification Email Template For Customer**: Select the in-stock template for the customer.
    
    .. figure:: img/stocknotification/Configuration-Settings-Stores-Magento-Admin_3.png
        :alt: module configuration fields
    
    :guilabel:`Sms Configuration`
        * **Sender ID**: Enter your sender id.
        * **Authentication Key**: Enter your authentication key.
        * **API URL**: Enter your api url.
        * **Out Of Stock Notification SMS Text**: When a product is out of stock, what message do you send to the customer?
        * **Out Of Stock Notification SMS For Admin**: If you want to send a notification SMS to admin, choose ``Yes``.
        * **Admin Mobile Number For Out Of Stock Notification SMS**: Enter the mobile number of an administrator to send the notification.
        * **Out Of Stock Notification SMS Text For Admin**: when a product is out of stock, what message do you send to the admin?
    
    .. figure:: img/stocknotification/Configuration-Settings-Stores-Magento-Admin_4.png
        :alt: module configuration fields
    
    :guilabel:`Frontend Labels`
        * **Notification Title**: Whatever you enter here will be displayed in the frontend notification form.
        * **Button Text**: Whatever you enter here will be displayed in the frontend notification button.
        * **Success Message**: Whatever you enter here will be displayed in the frontend notification form success message.
    
    .. note::
        Now save the configuration and cache flush.
    
    .. note::
        Now we check the functionality from the front-end side.


#. Open any out of stock product, you can see ``Notify form`` see below image.

    .. figure:: img/stocknotification/Joust-Duffle-Bag.png
        :alt: module configuration fields

    .. note::

        After entering an email address and a mobile phone number, click the button, and two emails are sent: one to the customer and one to the administrator.

#. See below images

    **Customer Mail sent**

        .. figure:: img/stocknotification/Customer-Mail.png
            :alt: module configuration fields
    
    **Admin Mail sent**

        .. figure:: img/stocknotification/Admin-Mail.png
            :alt: module configuration fields
    
    .. note::

        Now suppose when your product is back in stock, one email is sent to the customer.

    
    **In Stock Mail sent to the customer**
        
        .. figure:: img/stocknotification/Instock-Notification.png
            :alt: module configuration fields

#. Now you have to check admin side grid.
    
    If you want to see the Out of Stock Notification List, simply go to ``Logicrays > Out Of Stock Notification > Out Of Stock Notification`` see below image.

    .. figure:: img/stocknotification/Admin_list.png
    
    After Click ``Out Of Stock Notification``  You have to redirect to admin grid, see below image.
    
    .. figure:: img/stocknotification/Stock-Notification-List.png
    
    If you want to see the Out of Product Stock Notification List, simply go to ``Logicrays > Out Of Stock Notification > Product Out Of Stock Notification`` see below image.

    .. figure:: img/stocknotification/Product-Admin-Grid.png
    
    After Click ``Product Out Of Stock Notification``  You have to redirect to admin grid, see below image.

    .. figure:: img/stocknotification/Product-Stock-Notification-List.png