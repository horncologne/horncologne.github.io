---
layout: post
title: Hello World, We're Drupal! Drupalists in PHP Land
modified:
categories: blog
excerpt:
tags: []
image:
  feature:
date: 2015-07-20T15:52:07+02:00
published: false
---

<p>
  [Campbell Vertesi](https://www.drupal.org/u/ohthehugemanatee), Technical Architect at <a href="http://forumone.com/">Forum One</a>, and I presented a Drupal 8 technical/business session at the 2015 Dutch PHP Conference in Amsterdam. We were warmly welcomed by the 500+ delegate-developers and learned a great deal from them about the broader world of our "parent" programming language. At the same time, we took the chance to inform our PHP colleagues about what's been going on in Drupal lately and why it could be relevant and helpful to them. Thanks again to the conference organizers <a href="http://www.ibuildings.nl/">iBuildings</a>, we had a great time at a great conference!
</p>
<h2>
  We've learned a lot building D8, now we need to share it.
</h2>
<p>
  Drupal 8 is a great example of what great cooperation between open source projects can look like. Thanks to PHP-FIG, the PSR standards, Composer and several years of hard work, we've refactored Drupal to <a href="http://symfony.com/projects/drupal">incorporate Symfony 2 components</a>, the <a href="http://twig.sensiolabs.org/">Twig template engine</a>, and a number of external libraries. We've outsourced basic, commodity functionality to others so that we can specialize in what we're good at: data ingestion and output, and managing it in between.
</p>
<p>
  In Drupal land, we've been so busy and getting so excited about rebuilding Drupal, adopting up-to-date best practices and libraries, and building Drupal 8 to address the coming challenges of the post-browser world. But for all the "<a href="http://www.garfieldtech.com/blog/off-the-island-2013">Getting off the Island</a>" we've done technically, apparently we haven't been spreading the word about it very well outside of Drupal. Campbell and I spent a lot of our time telling other PHP developers about the exciting changes in Drupal 8 and countering some surprising misinformation about our project. I spoke with quite a few people who had been so horrified looking at Drupal 4, 5, 6, or even 7 that they thought they could never take our platform seriously. We've gotta fix this!
</p>
<p>
  We still have a lot we can learn from the broader PHP community. While we're out there, we need to make sure we're also telling everyone what we've got something useful (and that we're proud of) and how they can benefit from it, too.
</p>
<h2>
  Decoupled Drupal for Startups
</h2>
<p>
  Campbell and I presented "<a href="http://www.phpconference.nl/schedule#conference-day-2/0-mvp-40-minutes-decoupled-drupal-startups">From 0 to MVP in 40 minutes: decoupled Drupal for startups</a>" (<a href="http://www.slideshare.net/horncologne/0to-mvp-dutchphpcon">slide deck</a>). We talked about the world of fast-prototyping tools and application frameworks and after a quick look at Drupal 8 under the hood--<a href="http://symfony.com/projects/drupal">Symfony2 components</a>, OOP, etc.--demonstrated how Drupal 8 can help transform a demo app to a working minimal viable product (MVP) that ingests real data, transforms and manages it, and outputs it as content to the app. Along the way, we showed off the magic that is the Migrate API and Drupal's Views module.
</p>
<p>
  IMAGE - data stack
</p>
<p>
  In this modular app-creation model, each component does what it does best: Drupal ingests data, manages content and business logic, and functions as a web service. Angular.js (in our demo) provides an app front end and Bootstrap Material Design gives us "the pretty".
</p>
<p>
  IMAGE - decoupled app
</p>
<p>
  However elegant this may be, this solution leaves us with a number of @TODOs and problems to solve before we have an application that meets the needs of today's digital experiences: menu routing, layout/editing interface, accessibility and machine readability, login/account management, caching architecture, non-js fallback, localization/translation/multilingual, “big pipe” for REST limits, app architecture/documentation, unit tests, and getting a life :-)
</p>
<p>
  What if there were a way to address all of these issues at once? Hello, Drupal! If you choose to rely on Drupal 8 for data/logic plus the built in Twig template engine, you come very close to solving all of the @TODOs listed above in one stroke. What's more, you can still use this to feed anything else you need: native apps, websites, APIs, analytics, and more. We rounded out the presentation with a few use cases for each option and an example of a potential best practice: a dynamic, embedded Angular.js app running in real time inside a Drupal website.
</p>
<p>
  Thanks to Sebatian Siemssen for the excellent summary (<a href="http://www.zensations.at/blog/headless-drupal-cake-lie">"Headless Drupal" - The Cake is a Lie</a>) of the problems of the "headless" aka decoupled approach and the incredible suite of benefits Drupal's themeing layer offers.
</p>
<p>
  IMAGE - Drupal stack
</p>
<h2>
  About ForumOne &amp; Acquia
</h2>
<p>
  Acquia partner <a href="http://forumone.com/">ForumOne</a> is a digital agency with two decades of close partnership with think tanks, foundations, charities, and issue advocates. Working hand in hand with public officials, communicators, marketers, and policy analysts, ForumOne combines policy and passion to address the world’s most pressing problems.
</p>
<p>
  <a href="http://acquia.com">Acquia</a> is the digital experience company. Our digital innovation platform empowers market-leading enterprise organizations to move at the speed of the web, providing agility, integration and resiliency with products, services, and technical support for the open source Drupal social publishing system.
</p>
