---
layout: post
title:  'Comparing the Elemnt Bolt to the Amazfit sports watch and a mobile'
date:   2019-05-21
img:   z_roundabout_title.jpg # Add image post (optional)
tags: [Blog, Engineering]
author: Moritz Beller # Add name author (optional)
---

**On one of my [first cycling trips,](/ing/) I tracked my ride using
  three different GPS'es: one [generated from my
  mobile](https://www.mi.com/global/mi-a1/), my [Amazfit sports
  watch](https://en.amazfit.com/stratos.html), and my [newly
  bought](/correct/) Wahoo Elemnt Bolt. In this post, I finally get
  around to comparing them.**

To compare them, using Strava does not make sense: Strava takes your
original track and maps them to known roads. Instead, for this
article, I exported the raw GPS data, uploaded them to a GPS
comparison site and imported them in Google Earth.

> I followed [DC Rainmaker's
  advice](https://www.dcrainmaker.com/analyzer) (who actually was in
  my old home Delft on [the
  weekend](https://www.dcrainmaker.com/2019/06/5-random-things-did-this-weekend-94.html))
  to use Satelite and not Map view for comparison of GPS tracks.

Actually, back off a bit: I found [this interesting
study,](https://www.tandfonline.com/doi/abs/10.3846/20296991.2017.1330767)
in which researchers tried to find out this exact question in 2017 --
it turns out that the offset in the city of Montreal (which ironically
I came back home from yesterday) is anywhere from 0.1 to 2.7 meters.

> I am not a GPS specialist and I do not know how accurate the
  calibration of Google Earth images is. We should use Google Earth's
  images as a reference for the shape of the track, and only in case
  of stark deviations as an absolute reference.

I compared two bespoke devices, my <span style="color:blue">**GPS
sports tracker, the Amazfit Stratos watch,**</span> and the <span
style="color:green">**Wahoo Elemnt Bolt**</span>, and <span
style="color:red">**my mobile phone, a cheapish Xiaomi
A1**</span>. What's amazing is that when using GPS on the phone, this
rapidly drains the battery. The tailored devices last much longer with
GPS enabled. My Amazfit Watch has at least 20 hours of continuous GPS
coverage, the Bolt 13 hours (I wonder whether something's wrong with
mine, as the [official
figure](https://eu.wahoofitness.com/devices/bike-computers/gps-elemnt-bolt?rmsrc=1&gclid=Cj0KCQjwitPnBRCQARIsAA5n84mhRR7GV7efAaEyTasCsak1ugowYmVdoF6QZxjE7zY184vWRxHrunEaAljoEALw_wcB)
is much higher at 15 hours), my mobile running Strava maybe 8 hours.

> Which device would do better? The specific GPS-trackers, or the
  mobile which has the benefit of triangulation?

Overall, the track lengths are similar enough -- note that on the
Wahoo, I forgot to track the slow ferry and about 250 hundred meters
(measured via Google Earth) after the start. So the total ride lengths
are 56.92km (Wahoo Bike computer), 56.12km (Amazift Watch), and
57.83km (Xiaomi mobile). That sounds close enough,
but when you start to look into the actual track, things start to
become different:

> To my surprise, the Elemnt Bolt and the energy-saving Amazfit
  Stratos were relatively similar. The mobile was significantly worse.

![Ok]({{site.baseurl}}/assets/img/z_everyone_doing_ok.jpg)

We can see all the devices doing a good job. The Amazfit Stratos seems to
be cutting the route a bit short, which is in line with its shortest
track. This might be caused by a lower sampling rate, i.e. saving
fewer points per given time interval. The file size confirms this: The
Stratos has about half the size of the Wahoo Bolt. This also makes the
process less energy-intense.

![Bad mobile]({{site.baseurl}}/assets/img/z_mobile_doing_bad.jpg)

At certain points, the mobile seemed to be doing particularly erratic
and bad, even though I was traveling in a straight line.

Looking at the speeds, the devices reported different average speeds
of 23.9km/h, 24.8km/h (smoothened out by my speed/cadence sensor which
uses the circumference of the wheel), and 24.5km/h respectively on
Strava (!). It makes sense that the Bolt is fastest as I deactivated
it for the slow ferry ride.

![Round about]({{site.baseurl}}/assets/img/z_roundabout.jpg)

I thought I'd show this picture because it summarizes my findings quite nicely:

1. All tracks are to a certain degree usable.
1. On the roundabout, we see a nice track for the mobile, though in
absolute terms, it seems to be a bit misaligned with the map,
1. The mobile is occasionally a bit erratic.
1. The Amazfit is cutting the corners a bit short and smoothens out the ride.
1. Arguably, the Bolt has the best track.


I was pretty surprised by the relatively bad performance of the
phone. The phone was not bad for the entirety of the route though. I
would be interested to hear how better phones do.

Tot zo,

![Moritz]({{site.baseurl}}/assets/img/moritz.png)