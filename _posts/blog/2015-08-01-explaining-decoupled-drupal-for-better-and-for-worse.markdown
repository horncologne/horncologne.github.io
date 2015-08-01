---
layout: post
title: Explaining Decoupled Drupal for Better and for Worse.
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2015-08-01T13:52:02+02:00
published: false
---

## Decoupled Drupal for Startups

Campbell and I presented [From 0 to MVP in 40 minutes: decoupled Drupal for startups](http://www.phpconference.nl/schedule#conference-day-2/0-mvp-40-minutes-decoupled-drupal-startups) [slide deck here](http://www.slideshare.net/horncologne/0to-mvp-dutchphpcon). We talked about the world of fast-prototyping tools and application frameworks and had a quick look at Drupal 8 under the hood--[Symfony2 components](http://symfony.com/projects/drupal), OOP, etc. We then demonstrated how Drupal 8 can help transform a demo app to a working minimal viable product (MVP) that ingests real data, transforms and manages it, and outputs it as content to the app. Along the way, we showed off the magic that is the Migrate API and Drupal's Views module.

In this modular app-creation model, each component does what it does best: Drupal ingests data, manages content and business logic, and functions as a web service. Angular.js (in our demo) provides an app front end and Bootstrap Material Design gives us "the pretty".

However elegant this may be, this solution leaves us with a number of @TODOs and problems to solve before we have an application that meets the needs of today's digital experiences: menu routing, layout/editing interface, accessibility and machine readability, login/account management, caching architecture, non-js fallback, localization/translation/multilingual, “big pipe” for REST limits, app architecture/documentation, unit tests, and getting a life :-)

What if there were a way to address all of these issues at once? Hello, Drupal! If you choose to rely on Drupal 8 for data/logic plus the built in Twig template engine, you come very close to solving all of the @TODOs listed above in one stroke. What's more, you can still use this to feed anything else you need: native apps, websites, APIs, analytics, and more. We rounded out the presentation with a few use cases for each option and an example of a potential best practice: a dynamic, embedded Angular.js app running in real time inside a Drupal website.

Thanks to Sebastian Siemssen for the excellent summary ["Headless Drupal" - The Cake is a Lie](http://www.zensations.at/blog/headless-drupal-cake-lie) of the problems of the "headless" (aka decoupled) approach and the incredible suite of benefits Drupal's themeing layer offers.