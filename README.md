=== OfferStack ===
Contributors: furqan-freed, jamesmills
Tags: Vouchers, Deals, Offers, Clicksco
Requires at least: 4.0
Tested up to: 5.2
Requires PHP: 5.6
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

We cover Vouchers, Deals, Offers and Click To Call campaigns.

== Description ==
We cover Vouchers, Deals, Offers and Click To Call campaigns.
Install Offerstack and use short code or call function in file to list Vouchers, Deals, Offers on the page.



== Installation ==
1. Upload plugin to the "/wp-content/plugins/" directory.
1. Activate the plugin through the "Plugins" menu in WordPress.
1. Get Offerstack.io API key and update settings
1. Click on Settings for plugin and add default keyword and offer API Key and select theme 
1. Call ['offerstack'] in your editor anywhere between content Or place "do_action( 'offerstack' );" in your templates.

*Below parameters add for dynamic keyword and limit item listing*


1- offers_keyword
2- widget_identifier
3- max_iteams
4- is_sidebar


=== calling widget in editor ===

[offerstack offers_keyword="holidays" widget_identifier='widget in editor' max_iteams='2']


=== calling widget in sidebar in code ===

do_shortcode("[offerstack is_sidebar='yes']");



Note: OfferStack API Key


`
offerstack_api_key= you can get API key form https://offerstack.io/
`


=== Settings ===


1- Offers Keyword = offer will be listed as per this keyword
2- Max Items = no of items to list 
3- Widget Identifier = where this components is loaded on page 

example 
    a. page top
    b. page bottom
    c. right side base
    note:  Identifier will be sluify when send to api
