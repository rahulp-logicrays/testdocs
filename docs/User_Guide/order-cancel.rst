Order Cancel
==============

Overview
````````

Customers cannot cancel orders on Magento. So to overcome this issue, Logicrays has created an order cancellation extension.

.. note::
    Hope you are able to successfully install the module.

How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/ordercancel/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.
    
#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/ordercancel/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields
    
    .. figure:: img/ordercancel/Configuration-Settings-Stores-Magento-Admin_2.png
        :alt: module configuration fields
    
    :guilabel:`General`
        * **Enable**: Choose ``Enable`` to use the functions of this module.
        * **Order Cancel Button Title**: Enter the text for Button title of ``Ordercancel`` extension. If you check the ``Use System Value`` box, the default value will be used. 
        * **Order Cancel Reasons**: You must specify some reasons for order cancellation to be displayed on the front end.
        * **Order Cancel Popup Title**: Enter the title for the popup form. If you check the ``Use System Value`` box, the default value will be used.
        * **Order Cancel Popup Note**: Enter the note for the popup form. If you check the ``Use System Value`` box, the default value will be used.
        * **Customer Groups**: To enable this functionality, select a customer group. You can also select multiple customers.
        * **Order Status**: You must select either single or both order statuses here. When you choose that type of order status, apply the ``order cancel`` extension.
    
    .. figure:: img/ordercancel/Configuration-Settings-Stores-Magento-Admin_3.png
        :alt: module configuration fields
    
    :guilabel:`Email Configuration`
        * **Email Sender**: Select your Emial Sender.
        * **Email Template for Customer**: Select the customer template for mail.
        * **Email Template for Admin**: Select the admin template for mail.
        * **Send Email To Admin**: Enter an email address to send a message to the administrator.


.. note::
    Now save the configuration and cache flush.

.. note::
    Now we'll look at the front-end functionality of this module.

#. After login simply, go to ``My Account > My Orders``

    .. figure:: img/ordercancel/My-Orders.png
        :alt: My Order.

#. When you click the ``Cancel Order`` button, a popup form appears, as shown in the below image.

    .. figure:: img/ordercancel/My-Orders_popup.png
        :alt: My Order.
    
    .. note::

        After filling out the form and submitting it, one email is sent to the ``Customer`` and another to the ``Administrator``. You can see the images below.

#. Customer Mail sent

    .. figure:: img/ordercancel/Customer-mail.png


#. Admin Mail sent

    .. figure:: img/ordercancel/Order-Cancel-Admin-Email.png

#. Now you have to check admin side grid. Simply go to ``Logicrays > Order Cancel > Order Cancel`` see below image.

    .. figure:: img/ordercancel/Admin_Grid_home.png

#. After click on ``Order Cancel`` then you can redirect to ``Admin Grid`` see below image.
    
    If you wish to see order details, simply click on ``Order View``.
    
    .. figure:: img/ordercancel/Order-List.png

#. After click on ``Order View`` then you can redirect to ``Order view Page`` see below image.
    
    Here you can see status of order now is ``Canceled``

    .. figure:: img/ordercancel/Order-View.png