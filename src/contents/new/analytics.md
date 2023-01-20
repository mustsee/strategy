---
author: Thomas
datetime: 2023-01-20T16:00:00Z
title: Analytics
slug: analytics
featured: true
draft: false
tags:
  - docs
  - analytics
ogImage: ""
description: Reflexions on analytics
---

Terms: `PSH-Nuxt`(actual website), `PSH-Atro`(new website)

## Table of contents

## Current status

On the actual PSH website (let's name it `PSH-Nuxt`) we currently use GA (google analytics). We don't have a cookie policy widget.

On the new website (let's name it `PSH-Astro`), we currently have implemented [goatcounter](https://www.goatcounter.com) analytics. It's privacy friendly and doesn't need a cookie policy widget.

## Strategic options

There is one flaw using goatcounter with `PSH-Astro`. As it is a SSG website ([Static Site Generator](https://www.netlify.com/blog/2020/04/14/what-is-a-static-site-generator-and-3-ways-to-find-the-best-one/?utm_source=jamstackorg&utm_medium=what-are-ssg-pnh&utm_campaign=devex)), goatcounter doesn't understand it is the same user navigating between pages. Or maybe it's a built-in privacy feature. But it is still left to be better understood.

But do we need to know the user flow or is it sufficient to know the total amount of pages seen ?

To have a clearer view we can do one or both of the following:

- Add GA to `PSH-Astro` in parallel of goatcounter, and compare the results. See if GA on a SSR website is able to track the complete user flow.
- Add goatcounter to `PSH-Nuxt` in parallel of GA, and compare the results.

## Objectives

We are using analytics to a minimum and we can improve it by doing the following:

- Monthly summary (appearance to be defined)
- Try out campaigns (get more informations about marketing campaigns)
- Try out following events (like clicks on the buttons book now)
- Remove our IP addresses from tracking
