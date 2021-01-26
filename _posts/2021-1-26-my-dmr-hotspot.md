---
title: 'How I setup my DMR Hotspot'
layout: post
date: 2021-1-25
---

On Black Friday I picked up a Radioddity GD-77 DMR radio on sale for around $75. Getting into radio, I had a great interest in these digital-over-internet modes and picked it up to see what I could do. Sadly, all DMR repeaters are barely reachable from my QTH and the ones I can barely reach are really hard to find good information on for a codeplug. Useful when I go out, not very useful for home operation. So, I picked up some equipment to build a Pi-Star DMR Hotspot and thought I'd share some information on how I did it.

## Equipment

* Raspberry Pi Zero W - I went with this because it worked best with the case I got, but for this I'd go with any generic kit if you don't already own a Pi. With a kit, you'll get a Pi, power cable, and a few accessories to make life easier as well as a potential SD card.
* SD Card - If your Pi kit does not comes with an SD card, you'll need to purchase one yourself. Any small MicroSD card will work.
* [MMDVM Hotspot Board + Aluminium Case](https://www.amazon.com/gp/product/B07Z8YP5VJ/ref=ppx_yo_dt_b_asin_title_o02_s01?ie=UTF8&psc=1) - The attached Amazon link is the exact one I used, although any MMDVM hat should also work. 
* Soldering Iron - A soldering iron should be a staple piece of equipment in any ham shack, so be sure to get one now for this project and you'll use it for forever!

## Steps

I'll keep this fairly quick because I don't want to take away from the many other great tutorials out there that go into more depth than I can.

1. Solder on the header pins on your Raspberry Pi Zero. You may have existing header pins on your Pi if it was used in the past, but if you bought it brand new your Hotspot Board should have come with some header pins. If you've never soldered before, I really enjoyed [this video](https://www.youtube.com/watch?v=UDdbaMk39tM&t=350s&ab_channel=BasvanderSluis) on soldering header pins on.
2. Setup the physical hotspot. Each one is different, but for the one I ordered I had to separate the two pieces of the aluminum case, attach the MMDVM hat, RPi, and case together with standoffs and two included screws. Everything was very intuitive, although it took using some pliers to be able to separate the case pieces.
3. Load Pi-Star onto the SD card and set it up. I found a link to [Amateur Radio Notes' page on Pi-Star](https://amateurradionotes.com/pi-star.htm) and it was very helpful in getting everything setup. It looks to be consistently updated and walks through everything from installation to booting it up and getting started.

## What next?

In theory, this digital hotspot will work with a variety of digital modes. If you have a radio capable of any of these, take a shot at using them. Experiment with the various options the Pi-Star has. If you go the route I did - running Brandmeister DMR - go search for some talk groups that meet your interests. On [Brandmeister's website](https://brandmeister.network/?page=talkgroups), you can search for talkgroups based on your interests in radio, where you live, or just scroll through everything. Have fun with your new hotspot - DMR and other digital modes are a great aspect of radio!