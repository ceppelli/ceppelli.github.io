---
layout: post
title:  "Custom Arduino TMC Shield"
description: "I created a custom Arduino shield with 4 TMC2130 SilentStepStick"
image: /notes/custom-arduino-tmc2130-shield/01.png
date: 2019-01-04
last_modified_at: 2019-01-04
tags: [TMC, arduino, PCB]
permalink: /notes/custom-arduino-tmc2130-shield/
published: true
---

In November 2018 I read about the Trinamic stepper driver [`TMC2130`][tmc2130] and its amazing Features:
`microstep table`, `CoolStep™`, `passive braking`, `short detection`, `SpreadCycle™`, `Stall detection`, `StallGuard2™`, `StealthChop™`.
I realized it was what I was looking for my project and I decided to create a prototype as an `Arduino Mega Shield` for 4 stepper motors.

[//]: ![image](01.png){:class="img" style="border-radius: 8px; max-width:640px; width:100%; height:auto; display: block; margin-left: auto; margin-right: auto;"}

{% include gallery-grid.html alt="image" max-width="640px" width="100%" files="01.png,02.png" %}

It tooks 3 days and around 250 tin welding with my trusty [`HAKKO Fx-888`]({% link _notes/hakko-fx888/index.md %}) welder for complete the shield.
Now I'm realize it was really crazy just to have thought about it !!!!!!

{% include gallery-grid.html alt="image" max-width="640px" width="100%" files="03.png,04.png,05.png,06.png,07.png" %}

## SilentStepStick TMC2130

I bought the TMC2130 driver as [`SilentStepStick`][silentstepstick] modules from the [`German Watterott Shop`][watterott]
{% include gallery-grid.html alt="image" max-width="640px" width="100%" files="08.png,09.png,10.png,11.png" %}

## The Results

{% include video-gallery-grid.html alt="video" max-width="640px" width="100%" height="360" files="m01s.mov,m02s.mov" %}


[tmc2130]: https://www.trinamic.com/products/integrated-circuits/details/tmc2130/
[silentstepstick]: https://learn.watterott.com/silentstepstick/
[watterott]: https://www.watterott.com