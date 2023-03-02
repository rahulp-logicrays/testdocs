Google ReCaptcha
================


Overview
````````

The Google Recaptcha extension is the best solution to protect your e-commerce store from spam and fraud. It also protects the store from bots and enhances the security of Magento 2.

.. note::
    Hope you are able to successfully install the module.


How to Configure
````````````````

#. Open Admin Panel, go to ``Logicrays > Settings > Configuration``

    .. figure:: img/recaptcha/Dashboard-Magento-Admin.png
        :alt: Configuration Settings.

#. Now here you can see all the configure fields of the module. I'll explain them one by one at the end of the image.

    .. figure:: img/recaptcha/Configuration-Settings-Stores-Magento-Admin.png
        :alt: module configuration fields
    
    :guilabel:`General`
        * **Enable CAPTCHA on Store**: Choose ``Enable`` to use the functions of this module.
        * **Language Code**: Select the language in which the reCAPTCHA appears on the frontend and in the backend.
        * **Captcha Type**: You have to choose one of the options to apply reCAPTCHA to your store. The first is ``reCAPTCHA V2``, and the second is ``Invisible reCAPTCHA``. 

            ``reCAPTCHA V2``: This checkbox requires the user to click a checkbox indicating the user is not a robot.

            ``Invisible reCAPTCHA``: The invisible reCAPTCHA badge does not require the user to click on a checkbox; instead, it is invoked directly when the user clicks on an existing button on your site or can be invoked via a JavaScript API call.
        
        * **Site Key**: Whatever captcha type you select from the dropdown, you have to enter the respective site key.
        * **Secret Key**: Whatever captcha type you select from the dropdown, you have to enter the respective secret key.
        * **Forms**: Here, you can select single or multiple forms to apply the functionality of Google ReCaptcha.
    
    .. figure:: img/recaptcha/Configuration-Settings-Stores-Magento-Admin_2.png
        :alt: module configuration fields
    
    :guilabel:`Custom Form Position`
        * **Form Post Paths**: If you have a third-party form, you can also add Google ReCaptcha to the form's post path.
        * **CSS Selectors**: If you use a third-party form, you can also apply Google ReCaptcha to the form's CSS selectors.
    
    .. figure:: img/recaptcha/Configuration-Settings-Stores-Magento-Admin_3.png
        :alt: module configuration fields

    :guilabel:`Backend Configuration`
        * **Enable**: Choose ``Enable`` to use the functions of this module at the backend of Magento.
        * **Forms**: Here, you can select single or multiple forms to apply the functionality of Google ReCaptcha at the backend of Magento.

.. note::
    
    Now we have applied Google ReCaptcha to some front-end default forms; see the images below.

:guilabel:`Register Form`

    **I used visible ReCaptcha in this**.

    .. figure:: img/recaptcha/Create-New-Customer-Account.png
        :alt: Register Form

:guilabel:`Login Form`

    **I used Invisible ReCaptcha in this**.

    .. figure:: img/recaptcha/Customer-Login.png
        :alt: Login Form

:guilabel:`Contact-Us Form`

    **I used visible ReCaptcha in this**.

    .. figure:: img/recaptcha/Contact-Us.png
        :alt: Contact-Us Form

:guilabel:`Product Review Form`

    **I used Invisible ReCaptcha in this**.

    .. figure:: img/recaptcha/product-review.png
        :alt: Product Review Form


.. note::
    
    Now we have applied Google ReCaptcha to some back-end default forms; see the images below.

:guilabel:`Login Form`

    **I used visible ReCaptcha in this**.

    .. figure:: img/recaptcha/Magento-Admin.png
        :alt: Login Form


:guilabel:`Forgot Password Form`

    **I used Invisible ReCaptcha in this**.

    .. figure:: img/recaptcha/Magento-Admin_2.png
        :alt: Forgot Password Form