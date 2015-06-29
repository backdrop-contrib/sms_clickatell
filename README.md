SMS Clickatell
=============
Description
-----------

This module provides integration between the clickatell SMS service and the 
SMS framework project.

Please note that Clickatel module only supports sending SMS, not receiving them.

Installation
-----------
1. Sign up for a Clickatel account (See below)
2. Drop the module into your modules directory
3. Enable the SMS Framework API module and this module
4. Set and configure Clickatell gateway at admin/smsframework/gateways
5. Check out the settings pages at admin/smsframework

Clickatell Signup
-----------------
- Visit and sign-up for an account using the API option.
- You will be asked to buy a minimum number of credits. At the time of writing 
the number is 400.
- Then go to the admin panel:
https://www.clickatell.com/central/manage_products.php
- Add an HTTP connection:
- Enter the following information:
  - Name: for example "MySite".
  - IP Lock Down: you may enter the IP of your website to restrict connection.
  - Dial Prefix: example, 33 for France.
  - Callback Type: ???
  - Callback Url: ???
  - Callback Username: ???
  - Callback Password: ???
- Validate.
- You API ID is now visible.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.


Maintainers
-----------
Ported to Backdrop by https://github.com/docwilmot

Seeking maintainers

Credits
-------
Drupal Maintainers

http://drupal.org/u/univate
