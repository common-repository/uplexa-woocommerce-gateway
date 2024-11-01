﻿=== uPlexa WooCommerce Extension ===
Contributors: quantumleaper
Tags: uplexa, woocommerce, integration, payment, merchant, cryptocurrency, accept uplexa, uplexa woocommerce
Requires at least: 4.0
Requires PHP: 5.2.4
Tested up to: 4.9.8
Stable tag: 0.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

uPlexa WooCommerce Extension is a Wordpress plugin that allows to accept bitcoins at WooCommerce-powered online stores.

== Description ==

An extension to WooCommerce for accepting uPlexa as payment in your store.

= Benefits =

* Accept payment directly into your personal uPlexa wallet.
* Accept payment in uplexa for physical and digital downloadable products.
* Add uplexa payments option to your existing online store with alternative main currency.
* Flexible exchange rate calculations fully managed via administrative settings.
* Zero fees and no commissions for uplexa payments processing from any third party.
* Automatic conversion to uPlexa via real time exchange rate feed and calculations.
* Ability to set exchange rate calculation multiplier to compensate for any possible losses due to bank conversions and funds transfer fees.

== Installation ==

1. Install "uPlexa WooCommerce extension" WordPress plugin just like any other WordPress plugin.
2. Activate
3. Setup your uplexa-wallet-rpc with a view-only wallet
4. Add your uplexa-wallet-rpc host address and uPlexa address in the settings panel
5. Click “Enable this payment gateway”
6. Enjoy it!

== Remove plugin ==

1. Deactivate plugin through the 'Plugins' menu in WordPress
2. Delete plugin through the 'Plugins' menu in WordPress

== Screenshots ==
1. uPlexa Payment Box
2. uPlexa Options

== Changelog ==

= 0.1 =
* First version ! Yay!

= 0.2 =
* Bug fixes

= 0.3 =
* Complete rewrite of how the plugin handles payments

== Upgrade Notice ==

soon

== Frequently Asked Questions ==

* What is uPlexa ?
uPlexa is completely private, cryptographically secure, digital cash used across the globe. See https://uplexa.com for more information

* What is a uPlexa wallet?
A uPlexa wallet is a piece of software that allows you to store your funds and interact with the uPlexa network. You can get a uPlexa wallet from https://uplexa.com/downloads

* What is uplexa-wallet-rpc ?
The uplexa-wallet-rpc is an RPC server that will allow this plugin to communicate with the uPlexa network. You can download it from https://uplexa.com/downloads with the command-line tools.

* Why do I see `[ERROR] Failed to connect to uplexa-wallet-rpc at localhost port 21060
Syntax error: Invalid response data structure: Request id: 1 is different from Response id: ` ?
This is most likely because this plugin can not reach your uplexa-wallet-rpc. Make sure that you have supplied the correct host IP and port to the plugin in their fields. If your uplexa-wallet-rpc is on a different server than your wordpress site, make sure that the appropriate port is open with port forwarding enabled.
