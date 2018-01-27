<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# WooGoSend

WooCommerce per kilometer shipping rates calculator for GoSend Go-Jek Indonesia courier.

**Contributors:** [sofyansitorus](https://profiles.wordpress.org/sofyansitorus)<br>
**Tags:** [woocommerce shipping](https://wordpress.org/plugins/tags/woocommerce shipping), [go-jek](https://wordpress.org/plugins/tags/go-jek), [ojek shipping](https://wordpress.org/plugins/tags/ojek shipping), [gosend](https://wordpress.org/plugins/tags/gosend), [gojek shipping](https://wordpress.org/plugins/tags/gojek shipping)<br>
**Requires at least:** 4.8<br>
**Tested up to:** 4.9.2<br>
**Stable tag:** 1.2.0<br>
**License:** [GPL-2.0+](http://www.gnu.org/licenses/gpl-2.0.txt)<br>
**Requires PHP:** 5.6<br>

## Description ##

WooCommerce per kilometer shipping rates calculator for GoSend Go-Jek Indonesia courier.

Please note that this plugin is not using official Gojek Indonesia API. This plugin just estimate the distance matrix using using Google Maps Distance Matrix API and then calculating the cost using the rates defined in the settings.
### Features ###
* Automatically split shipping for multiple items into several drivers if the package size exceeded package weight and dimensions limitation.
* Available 2 shipping services: Instant Delivery, Same Day Delivery.
* Set shipping cost per kilometer.
* Set minimum cost that will be billed to customer.
* Set maximum cost that will be billed to customer.
* Set maximum shipping distances that allowed to use the courier.
* Set maximum package weight and dimensions that allowed to use the courier.
* Set shipping origin info by coordinates using "Map Address Picker".
* Set travel mode: Driving, Walking, Bicycling.
* Set route restrictions: Avoid Tolls, Avoid Highways, Avoid Ferries, Avoid Indoor.
* Set visibility distance info to customer.


## Installation ##

### Minimum Requirements ###
* WordPress 4.8 or later
* WooCommerce 3.0 or later

### AUTOMATIC INSTALLATION ###
Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t even need to leave your web browser. To do an automatic install of WooGoSend, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type “WooGoSend” and click Search Plugins. You can install it by simply clicking Install Now. After clicking that link you will be asked if you’re sure you want to install the plugin. Click yes and WordPress will automatically complete the installation. After installation has finished, click the ‘activate plugin’ link.

### MANUAL INSTALLATION ###
1. Download the plugin zip file to your computer
1. Go to the WordPress admin panel menu Plugins > Add New
1. Choose upload
1. Upload the plugin zip file, the plugin will now be installed
1. After installation has finished, click the ‘activate plugin’ link


## Frequently Asked Questions ##

### How to set the plugin settings? ###
You can setup the plugin setting from the Shipping Zones settings. Please check the following video tutorial how to setup the WooCommerce Shipping Zones:

[![Play video on YouTube](https://i1.ytimg.com/vi/eThWmrnBP38/hqdefault.jpg)](https://www.youtube.com/watch?v=eThWmrnBP38)

[Video](https://www.youtube.com/watch?v=eThWmrnBP38) by [InMotion Hosting](https://www.inmotionhosting.com)

### Where can I get support? ###
You can either create ticket at plugin support forum or GitHub repository:

* [Plugin Support Forum](https://wordpress.org/support/plugin/woogosend)
* [Plugin GitHub Repository](https://github.com/sofyansitorus/WooGoSend)

### Where can I report bugs? ###
You can either create ticket at plugin support forum or GitHub repository:

* [Plugin Support Forum](https://wordpress.org/support/plugin/woogosend)
* [Plugin GitHub Repository](https://github.com/sofyansitorus/WooGoSend)

### Where can I request a feature? ###
You can either create ticket at plugin support forum or GitHub repository:

* [Plugin Support Forum](https://wordpress.org/support/plugin/woogosend)
* [Plugin GitHub Repository](https://github.com/sofyansitorus/WooGoSend)


## Screenshots ##

### Settings panel: General Options

![Settings panel: General Options](assets/screenshot-1.jpg)

### Settings panel: Instant Delivery Service Options

![Settings panel: Instant Delivery Service Options](assets/screenshot-2.jpg)

### Settings panel: Same Day Delivery Service Options

![Settings panel: Same Day Delivery Service Options](assets/screenshot-3.jpg)

### Shipping Calculator preview

![Shipping Calculator preview](assets/screenshot-4.jpg)

## Changelog ##

### 1.2.0 ###
* Improvemnets - Add "Map Location Picker" for store location setting.

### 1.1.1 ###
* Improvemnets - Add "Settings" link on the plugins.php page.

### 1.1.0 ###
* Improvements - Add new settings field to enable or disabled multiple drivers function.

### 1.0.2 ###
* Fix - A non-numeric value encountered warning.

### 1.0.1 ###
* Improvements - Add new filter hooks: woocommerce_woogosend_shipping_destination_info.
* Improvements - Add new filter hooks: woocommerce_woogosend_shipping_origin_info.

### 1.0.0 ###
* Feature - Automatically split shipping for multiple items into several drivers if the package size exceeded package weight and dimensions limitation.
* Feature - Available 2 shipping services: Instant Delivery, Same Day Delivery.
* Feature - Set shipping cost per kilometer.
* Feature - Set minimum cost that will be billed to customer.
* Feature - Set maximum cost that will be billed to customer.
* Feature - Set maximum shipping distances that allowed to use the courier.
* Feature - Set maximum package weight and dimensions that allowed to use the courier.
* Feature - Set shipping origin info by coordinates.
* Feature - Set travel mode: Driving, Walking, Bicycling.
* Feature - Set route restrictions: Avoid Tolls, Avoid Highways, Avoid Ferries, Avoid Indoor.
* Feature - Set visibility distance info to customer.


## Upgrade Notice ##

### 1.2.0 ###
This version add some improvements. Upgrade immediately.


