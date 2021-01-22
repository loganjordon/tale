---
layout: post
title: "About"
permalink: /about
image: "/assets/images/l-cropped2.jpg"
image_avif: "/assets/images/l-cropped2.avif"
---

{%   assign today = site.time | date: '%s'      %}
{%   assign start = '25-05-2019 11:11:00' | date: '%s'  %}
{%   assign secondsSince = today | minus: start     %}
{%   assign hoursSince = secondsSince | divided_by: 60 | divided_by: 60     %}
{%   assign daysSince = hoursSince | divided_by: 24  %}
{%   assign yearsSince = daysSince | divided_by: 365  %}

{%   assign k = 10   %}
{%   assign divisor = 365   %}
{%   assign modulus = daysSince | modulo: 365 | times: k | divided_by: divisor  %}

Howdy, I'm Logan Jordon.

I am a Christian, a software developer, a writer, a computer science graduate from the University of Arkansas, and a lifetime student of God's Word. I reside in Northwest Arkansas with my wife of {{ yearsSince }}.{{ modulus }} years.

I write with the aim of increasing your knowledge of the Lord, and your desire to know Jesus Christ personally. Here you will find articles, anecdotes, and analyses of various topics I find interesting, ranging from systematic theology to living the daily Christian life—plus the occasional YouTube video I think you should watch.

<a href="http://eepurl.com/heJUTb" target="_blank">Subscribe</a> to get my latest posts mailed directly to your inbox!

Have a question, comment, or prayer request? Send me a [message]({{ '/contact' | prepend: site.base_url }})!