# Changelog

## 2.1.0

* added support for batch inserts (page views, events, sessions)
* updated dependencies

## 2.0.2

* fixed build

## 2.0.1

* add title, screen_width and screen_height parameters
* fix trustedProxyHeaders behavior
* remove deprecated cf_connecting_ip, x_forwarded_for, forwarded and x_real_ip fields
* updated dependencies

## 2.0.0

* added support for browsers
* general improvements of the package interface
* updated dependencies

## 1.4.1

* added single access token that don't require to query an access token using oAuth

## 1.4.0

* added hourly visitor statistics, listing events, os and browser versions
* added filter options
* updated return types with new and modified fields
* updated dependencies

## 1.3.5

* fixed domain method returning an object instead of an array

## 1.3.4

* added new hourly visitor statistics
* fixed promise not being rejected in case the token cannot be refreshed

## 1.3.3

* added endpoint for total visitor statistics

## 1.3.2

* fixed copy-paste error

## 1.3.1

* fixed error handling

## 1.3.0

* added endpoint to extend sessions
* added entry page statistics
* added exit page statistics
* added number of sessions to referrer statistics
* added city statistics
* added entry page, exit page, city, and referrer name to filter

## 1.2.0

* added method to send events
* added reading event statistics
* fixed filter parameters to read statistics

## 1.1.1

* fixed build

## 1.1.0

* added `source` and `utm_source` to referrers
* added methods to read statistics
* updated dependencies
* fixed retry on 401

## 1.0.1

* added missing DNT (do not track) header

## 1.0.0

Initial release.
