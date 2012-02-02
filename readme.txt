=== dpurlshortner ===
Contributors: danpai
Donate link: http://danilopaissan.net/blog/
Tags: links, bitly, goo.gl, shortner, url
Requires at least: 2.0
Tested up to: 3.3.1
Stable tag: 0.2

D(ifferent)P(lace) URL Shortner is a WordPress Plugin designed to use the most popular URL shortening services.

== Description ==

D(ifferent)P(lace) URL Shortner is a WordPress Plugin designed to use the most popular URL shortening services. At this moment the only supported services are Bitly.com and Google URL Shortner.

There are 3 ways to generate and obtain a shortlink:

1. When you publish a post or a page
2. When you update a published post or page
3. When you view a post or a page that use this code

	`<?php echo wp_get_shortlink(); ?>`

You can find the latest release on [GitHub](https://github.com/danpai/DPUrlShortner)

== Installation ==

Copy the folder dpurlshortner and its content into <your blog>/wp-content/plugins

== Frequently Asked Questions ==

= Is necessary an API key for Google URL Shortner? =

No at this moment, is not strictly necessary if the number of calls is limited.

= Where can I get an API key for Google URL Shortner service? =

[APIs Console](https://code.google.com/apis/console/)

= Is necessary an API key for bit.ly shortner service? =

Yes

= Where can I get an API key for bit.ly shortner service? =

[bitly API Documentation](http://code.google.com/p/bitly-api/wiki/ApiDocumentation#Authentication_and_Shared_Parameters)

== Changelog ==
= 0.1 =
* This version is quite stable but it can be used as long as you know what you are doing.
= 0.2 =
* This version bypass the error "SSL certificate problem, verify that the CA cert is OK. Details: error:14090086:SSL routines:SSL3_GET_SERVER_CERTIFICATE:certificate verify failed".