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

    Open your database and find the table with the prefix: ``logicrays_Callforprice``

    Delete all database tables associated with ``logicrays_Callforprice`` see below image.

    .. image:: img/phpmyadmin.png

.. note::
    
    If you have any questions, feel free to contact us at https://www.logicrays.com/contact-us