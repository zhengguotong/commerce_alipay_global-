Commerce Alipay Global

Developer: Guotong Zheng (Tony)
Developer Website:http://zhengguotong.me

This Module is base on Drupal Module [Commerce Alipay] (https://www.drupal.org/project/commerce_alipay)
===============

Implements [Alipay Global](http://global.alipay.com/) payment services for use with
[Drupal Commerce](http://drupal.org/project/commerce).

Installation and configuration
------------------------------
a. Prerequisites:
Requires Drupal Commerce to be installed and more particularly the Commerce
Payment module to be enabled (more Commerce modules would also be required:
Commerce UI and Order).
More information at: Installation and uninstallation guide for Drupal Commerce
[https://drupal.org/node/1007434]

b. Download the module and copy it into your contributed modules folder:
[for example, your_drupal_path/sites/all/modules] and enable it from the
modules administration/management page.
More information at: Installing contributed modules (Drupal 7)
[http://drupal.org/documentation/install/modules-themes/modules-7]

2 - Configuration:
After successful installation, browse to the "Payment Methods" management page
under: Home » Administration » Store » Configuration » Payment methods
Path: admin/commerce/config/payment-methods or use the "Configure" link
displayed on the Modules management page.

Enable the Alipay payment method, as described in the Drupal Commerce Payments
User Guide at: http://www.drupalcommerce.org/user-guide/payments
Follow all other steps as described in the Payments User Guide, edit the Alipay
payment method (Rule) and then edit the Action "Enable payment method: Alipay".

Configure the form Payment Settings as required with:
- Seller's registered email address
- Partner ID and Key provided by Alipay's API after account registration for
the corresponding type of Service.



Useful Resources
----------------
For any questions, some help could be found on the Alipay official site:
1 - Merchant Help Center:
https://b.alipay.com/support/helperApply.htm?action=consultationApply
Apply for integration consultation, and you could expect a professional
technician to contact you.
2 - User Help Center:
http://help.alipay.com/support/232511-16307/0-16307.htm?sh=Y&info_type=9
3 - Alipay Forum:
http://club.alipay.com/read-htm-tid-8681712.html
4 - Alipay's Hotline: 0571-88158090 (Monday - Friday, 9:00 to 18:00)


Bugs/Features/Patches
---------------------
If you would like to report bugs, feature requests, or submit a patch, please
do so in the project's issue tracker at:
https://drupal.org/project/issues/commerce_alipay


Contributions are welcome!!
---------------------------
Feel free to follow up in the issue queue for any contributions, 
bug reports, feature requests.
Tests, feedback or comments in general are highly appreciated.
