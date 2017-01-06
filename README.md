# gtpay-woo-payment-gateway
GTPay Woocommerce Payment Gateway allows you to accept payment on your Woocommerce store, GTPAY accepts both locally and internationally issued cards

#Description

This is a GTBank Payment gateway for Woocommerce.

To signup for GTPay visit any GTBank and register for your GTPay merchant account.

GTPay Woocommerce Payment Gateway allows you to accept payment on your Woocommerce store, GTPAY accepts both locally and internationally issued cards including Interswitch, MasterCard and VISA.

With this GTPay Woocommerce Payment Gateway plugin, you will be able to accept the following payment methods in your shop:

* __MasterCard__
* __Visa__
* __Interswitch__

# Note

This plugin is meant to be used by merchants in Nigeria.

# Plugin Features

*   __Accept payment__ via Interswitch, MasterCard, and Visa.
* 	__Seamless integration__ into the WooCommerce checkout page.
* 	__Add Naira__ currency symbol. To select it go to go to __WooCommerce > Settings__ from the left hand menu, then click __General__ from the top tab. From __Currency__ select Naira, then click on __Save Changes__ for your changes to be effected.
* 	__Send SMS notification__ to customer on successful payment. This feature has to be enabled and configured before it will work, you will need an SMS API.


# Suggestions / Feature Request 

If you have suggestions or a new feature request, feel free to get in touch with me via email elnino.akin@gmail.com

You can also add me on Facebook http://facebook.com/deluakin



# Installation

= Automatic Installation =
* 	Login to your WordPress Admin area
* 	Go to "Plugins > Add New" from the left hand menu
* 	In the search box type "Woocommerce GTPay Payment Plugin"
*	From the search result you will see "Woocommerce GTPay Payment Plugin" click on "Install Now" to install the plugin
*	A popup window will ask you to confirm your wish to install the Plugin.

# Note
If this is the first time you've installed a WordPress Plugin, you may need to enter the FTP login credential information. If you've installed a Plugin before, it will still have the login information. This information is available through your web server host.

*   Click "Proceed" to continue the installation. The resulting installation screen will list the installation as successful or note any problems during the install.
*   If successful, click "Activate Plugin" to activate it.
* 	Click the "Settings" link to Open the settings page for the plugin.
*	Configure your "GTPay" settings. See below for details.

# Manual Installation
* 	Download the plugin zip file
* 	Login to your WordPress Admin. Click on "Plugins > Add New" from the left hand menu.
*   Click on the "Upload" option, then click "Choose File" to select the zip file from your computer. Once selected, press "OK" and press the "Install Now" button.
*   Activate the plugin.
* 	Click the "Settings" link to Open the settings page for the plugin.
*	Configure your "GTPay" settings. See below for details.



# Configure the plugin
*       Goto plugins and find the "GTPay WooCommerce Payment Gateway" plugin, then click the Settings link.
*       __Enable/Disable__ - check the box to enable GTPay Payment Gateway.
*       __Title__ - allows you to determine what your customers will see this payment option as on the checkout page.
*       __Description__ - controls the message that appears under the payment fields on the checkout page. Here you can list the types of cards you accept.
*        __GTPay Merchant ID__  - enter your gtpay merchant id given to you by GTBank
*       __Hash Key__  - enter your hash key which was given to you by GTBank
*       __Currency__  - enter the currency code which would be used for payments. Currently GTPay supports two currencies,  Naira - (566). USD - (840)
*       Click on __Save Changes__ for the changes you made to be effected.





# Frequently Asked Questions

What Do I Need To Use The Plugin

1.	You need to have Woocommerce plugin installed and activated on your WordPress site.
2.	You need to register for a Merchant ID and Hash Key from any GTBank branch.



# Changelog

= 3.2 =
*   Changed the logo according to Interswitch recomendation.

= 3.1 =
*   Added shipping cost to the payment confirmation page to reflect the actual total.
*   Formated response message according to GTBank.
*   Added the interswitch logo to the GTPay payment option according to GTBank instruction.

= 3.0 =
*   Fixed some bugs.
*   Added payment confirmation page.

= 2.3 =
*   Fixed some bugs.

= 2.2 =
*   Fixed some bugs.

= 2.1 =
* Fixed the issue with GTPay "Continue" redirecting back to cart page.

= 2.0 =
*   Added SMS notification functionality.