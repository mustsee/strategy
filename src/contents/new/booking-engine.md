---
author: Thomas
datetime: 2023-01-25T10:00:00Z
title: Booking engine
slug: booking-engine
featured: true
draft: false
tags:
  - docs
  - booking engine
ogImage: ""
description: Reflexions on booking engine
---

## Table of contents

## Current status

Currently we use [beds24](https://beds24.com/) and we only been using beds24. Beds24 is one of the cheapest booking engine on the market. The integration with our website is rather minimal. We just have "book now" buttons that link to the beds24 property booking page. Then you have to pick dates to see availabilities. The UI and the customer flow are not the best and we still don't have a booking widget on the website.

## Strategic options

We considered other booking engine options, like [mews](https://www.mews.com/en). They have better integrations with other tools (like WhatsApp) and are also much more expensive. Their booking engine page is nicer than the one we have and the integration would appear to be seamlessly.

## Objectives

- Translate the beds24 booking page (french and spanish).
- Change colors/UI on the booking page, make it less childish by removing colors (blue and yellow), png logo and follow new design guidelines.
- Add information about payment on the checkout page (we don't know if/when our credit card will be debited).
- Implement a booking widget on the website: by allowing to preselect dates it will enhance the user flow.
- Booking sources: as we need to follow a precise count of direct booking made via our website, we should create two separate categories for direct bookings : website direct booking and manual direct booking.
