Midtrans Easy Digital Downloads Payment Gateway
=====================================

A WordPress plugin that let your Easy-Digital-Downloads store integrated with Midtrans payment gateway.

### Description

Midtrans payment gateway is an online payment gateway that is highly concerned with customer experience (UX). They strive to make payments simple for both the merchant and customers. With this plugin you can make your Easy Digital Downloads store integrated with Midtrans payment gateway.

Payment Method Feature:

* Credit card fullpayment and other payment methods.
* Bank transfer, internet banking for various banks
* Credit card Online & offline installment payment.
* Credit card BIN, bank transfer, and other channel promo payment.
* Custom expiry.
* Two-click & One-click feature.
* Midtrans Snap all payment method fullpayment.

### Installation

#### Minimum Requirements

* WordPress 3.9.1 or greater
* Easy Digital Downloads 2.0 or greater
* PHP version 5.4 or greater
* MySQL version 5.0 or greater

#### Manual Instalation

The manual installation method involves downloading our feature-rich plugin and uploading it to your webserver via your favourite FTP application..

1. [Download](https://github.com/rizdaprasetya/vtweb-edd/archive/master.zip) the plugin file to your computer and unzip it
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation `wp-content/plugins/` directory.
3. Activate **Easy Digital Downloads - Midtrans Gateway** plugin from Plugin menu in your WordPress admin page.

#### Midtrans MAP Configuration
1. Login to your [Midtrans Account](https://dashboard.midtrans.com/), select your environment (sandbox/production), go to menu ***settings > configuration***
 * Insert `http://[YourWeb].com/?edd-listener=midtrans` link as the Payment Notification URL in your MAP configuration.
 * Insert `http://[YourWeb].com` (or your desired URL) link as Finish/Unfinish/Error Redirect URL in your MAP configuration.
  

#### Plugin Configuration
In order to configure Midtrans plug-in:

1. Access your WordPress admin page.
2. Go to **Downloads - Settings** menu in the WordPress admin page, click **Payment Gateways** tab.
3. Click **Save Changes**.
4. Click **Payment Gateways** section, that you click before i.e. **Midtrans** next to **General**
5. Input required fields below. (alternatively you may refer to image below) 
  * **Checkout Label** : \<text that will be shown when customers pick payment options\>
  * **Production API Key**: \<your production server key\> (leave blank if you dont have production account)
  * **Sandbox API Key**: \<your sandbox server key\>
  * **Enable 3D Secure** : yes
6. Click **Save Changes**.

#### Get help

* [Midtrans registration](https://dashboard.midtrans.com/register)
* [Midtrans documentation](http://docs.midtrans.com)
* [Midtrans SNAP Documentation](http://snap-docs.midtrans.com)
* Technical support [support@midtrans.com](mailto:support@midtrans.com)
