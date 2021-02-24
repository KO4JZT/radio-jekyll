---
layout: page
title: Amateur Radio
permalink: /amateur-radio/
updated: 2-20-2021
---

If you've stumbled upon this page, you're probably here for a few various reasons: you made a QSO with me on the air, you found my site and are interested in what amateur radio is, or you read one of my blog posts on ham radio.

I'm a Technician class amateur operator, callsign KO4JZT. Licensed in 2020, I have an interest in many facets of radio: DMR, satellite communications, and HF/DXing.

## Interests in Radio

### DMR

I enjoy working with DMR and other digital modes! My current setup for DMR is a Radioddity GD-77 running the OpenGD77 firmware and a [custom-built Pi-Star hotspot](/2021/01/26/my-dmr-hotspot/). 

You can typically catch me in Brandmeister talkgroups 98638 and 31621. I typically check-in at the weekly Ham Radio Village net at 8pm CT Tuesday nights on TG98638.

My upcoming goals in DMR and digital voice are: 

* Upgrade to the Anytone 878 radio for DMR
* Get more radios for operating other modes (D-Star, YSF)
*  Build my own small-scale DMR network

### Satellites

Working stations all over the world on Satellite passes with VHF/UHF seems very intriguing to me! At the moment, I am working on building up the capability to work satellites - if you've stumbled on this page after working me on a satellite let me know to update it!

I currently listen to satellites with a Baofeng UV-5R and a DIY tape measure yagi antenna built for 2m. I'm looking to get a Duplex setup going and then move to making contacts if possible!

### DXing

As of last updating this page - I am studying for my General class license and trying to get my hands on an HF station. Once I move to HF, I plan on trying to make many long distance contacts over SSB Voice, FT8, and JS8Call.

Below will be an updated count of my progress towards various awards! Hopefully I will soon be able to automate this.

<!-- TODO: Can this be automated? -->
* Worked All Continents - 0/6
* Worked All States - 0/50
* DXCC - 0/100

## My Equipment

* Baofeng UV-5R w/ Super Elastic Signal Stick Antenna
* Radioddity GD-77 w/ Nagoya NA-771 Antenna
* Random Mag-Mount Mobile Antenna on Car with BNC Connector for any Radio
* Custom Build Pi-Star DMR Hotspot

## Blog Posts
<!-- TODO: Update these links. -->
Below are my most recent blog posts specific to amateur radio - check them out here or at [the amateur radio category](), or at my [general blog page](/blog).

<ul>
    {%- for post in site.categories.amateur-radio limit:5 -%}
        <li>
        <a href="{{ post.url }}">
            <b>
              {{ post.title }}
            </b>
          </a>-
          <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </li>
    {%- endfor -%}
<ul>