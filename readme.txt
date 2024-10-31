=== RevOffers Advertiser Integration ===
Contributors: homeyjd
Tags: affiliate, revoffers, katalys, tracking
Requires at least: 5.6
Tested up to: 6.3.1
Requires PHP: 5.5
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Provides tightly-coupled integration with RevOffers Affiliate Network for WooCommerce order tracking and attribution.

== Description ==
Do you want more customers for your eCommerce brand? [RevOffers](https://www.revoffers.com/) is the performance-based advertising network for transformational health products and brands — and our plugin opens the door to high-converting in-market traffic from the RevOffers Advertiser Network.
Our plugin enables technical integration in one, no-hassle step. It listens for order-related hooks within your WordPress / WooCommerce installation and reports to the RevOffers Attribution Engine when the order is complete. Our back-end system does the rest, analyzing and reporting on how much growth RevOffers is driving for you, month after month.

## Open Your Account Now
Ready to drive more sales? It begins with qualified traffic. It’s easy to get started:

- Fill out our Advertiser Survey to apply for an account.
- We will review your application and may ask for verification before approving your account. Once it’s approved, we'll activate your account on our platform.
- Finally, install our [free WordPress plugin](https://wordpress.org/plugins/revoffers-advertiser-integration/) to complete the required Technical Integration.  The plugin will automatically configure itself based on your approved domain.
- Questions? Contact us at [support@revoffers.com](support@revoffers.com).

Our pricing structure is built specifically for your business needs.  We have the ability to structure our affiliate offers based on cart value, coupon, fixed fee, and more.  Since RevOffers is a performance network, you only pay when RevOffers drives verified/paid orders!

## Drive More Sales, Automatically
The RevOffers plugin for WordPress / WooCommerce enables you to easily and automatically drive more eCommerce sales. It’s designed to help you succeed in:

- Driving more traffic to your website
- Making connections with prospective customers for your products/services
- Attracting qualified leads to sign up for your mailing list
- Generating more sales, every day
- Paying only for sales that really happen
- Generating additional SEO-friendly links from publishers

*********

## Feature Highlights

### Easily Create Optimized Affiliate Campaigns
The RevOffers plugin for WordPress / WooCommerce helps you collect data in support of an effective affiliate program:

- Create CPS, CPA, or CPL offers
- Track hits and sales across your eCommerce website
- Set up special business rules and conditions for custom offers
- End-to-end campaign management

### Plugin Features

- Increase transparency through granular reporting and intelligent dashboards
- Industry’s only built-in fraud protection, which automatically detects and rejects click fraud for all RevOffers customers.
- SOC 2 Type II certification, EU-U.S. Privacy Shield certification, GDPR privacy certification, and other measures.
- With 99.9% system uptime and the most extensive documentation in the industry, you can relax knowing the best team in the business has got your back.

## Why Brands Love RevOffers

### Performance Marketing for Positive Change!
We acquire customers for you through our connections with hundreds of curated publishers, marketers, and influencers around the world. RevOffers is a performance-based ad network, which means we only get paid when our advertisers make sales.

### Affiliate Industry Knowledge
Our publishers and advertisers are in experienced hands when it comes to structuring offers and driving performance.

-   *Marketing Savvy*

    Let us help you grow your affiliate and eCommerce revenue with our collective decades of experience.

-   *We Care*

    We only allow transparent, transformative brands and safe, quality, compliant traffic from our publishers.

-   *Strong Relationships*

    We focus on building sustainable relationships with our Advertisers and Publishers, so everyone wins.

-   *Legal Cannabis Focus*

    Until RevOffers, there wasn’t a strong centralized place for legal cannabis Advertisers and Publishers to exchange services.

-   *Born to Rev*

    Driving results on performance is in our blood. Clicks and impressions are not enough if you want to grow a business.


## Privacy Statement
Your customers are your customers! Collected data is only used to attribute your sales growth, where appropriate, in accordance with our Privacy Policy.  RevOffers partners with brands to create strong relationships to help you drive performance — our focus is on your success!


== Changelog ==

2023-11-21: fix double-encoding of order-time

2023-10-25: fix reporting for archived orders

2022-08-10: clean category-string by removing HTML tags

2022-07-01: add support for PHP8, simplify order-status-change reporting

2022-02-16: fix order-archiving reporting issue for old orders

2021-12-07: fix product-category reporting

2021-09-01: resolve deprecation notices on WooCommerce v4.0+

2021-07-23: support RouteApp for reporting shipping-fees, report payment_status for better order-rejection matching

2021-06-11: support performance reporting by product-category

2020-11-10: add compatibility with Gatsby/REST themes

2020-06-04: fix minor order_value mis-match for advertising customers

2020-01-06: run WooCommerce order_number filter to properly disambiguate custom numbering system

2019-10-15: adding RevAds opt-in, performance optimization for order-record, making cron an opt-in feature

2019-09-16: Compatible with 2-stage HTTP proxies, smarter defaults with regards to domain association.

2019-07-25: Compatible with IPv6, capable of running without WooCommerce (tracking only).

2019-05-20: Make code more consistent in error handling.

2019-05-13: Use cron for offline processing, add database table for tracking state.

2019-05-12: Use MultiCurl, background processing, and custom query for counts. MASSIVE performance gain for larger databases!

2019-05-08: Change reporting key to be congruent with other tools.

2019-05-07: Filter out local/16 IP addresses

2019-05-02: Big update:
- Now reporting refunds for faster order reconciliation!
- Adding REST endpoints for receiving signed status-update messages. This allows additional automation between advertisers and affiliates if desired.
- Listening for more order-related events to be compatible with additional WooCommerce plugins
- Dropping support for PHP 5.4, now requires PHP 5.5

2018-06-16: Adding debug export features

2018-06-05: Bug fixes

2018-05-28: WooCommerce deep integration (now a dependency)

2018-05-25: First version