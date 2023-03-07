Uninstall Extension
===================

Uninstall (Copy-and-paste method)
`````````````````````````````````

#. Delete the following files and folders.

    :guilabel:`app/code/Logicrays/Callforprice`

#. Run the following commands::

    php bin/magento setup:upgrade

#. First of all, delete the following database tables:

    Now open a Mysql mangement such as :guilabel:`PHPMyAdmin`

    Open your database and find the table with the prefix: ``logicrays_callforprice``

    Delete all database tables associated with ``logicrays_callforprice`` see below image.

    .. figure:: img/phpmyadmin.png
        :alt: DB table format
        :align: center

.. note::
    
    If you have any questions, feel free to contact us at https://www.logicrays.com/contact-us