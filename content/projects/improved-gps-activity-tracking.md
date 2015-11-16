+++
date = "2013-05-01T12:13:38-08:00"
draft = true
title = "Improved GPS Activity Tracking"
summary = "Tracking activity metrics with an iPhone is great. I love having a record of my HR and cadence. The GPS tracking on the iPhone is not so great. To supplement, I have a Locosys GT-31 GPS, which has great accuracy. Here's a little code to put them together."
thumbnail = "/images/activity-map.png"

+++
{{< img src="/images/activity-traces.png" caption="Activity Traces" link="http://www.strava.com/activities/106617181" >}}

I've been using my iPhone to GPS track various activities for a number of years.
I love how easy it is to integrate various data sources via ANT+ and the [Wahoo
Fitness Key][wahoo]. Having heart rate, bike speed, and pedaling cadence tracked along
with GPS is fantastic for post-activity review. I was never particularly happy
with the GPS performance of the iPhone. When I directly compared the iPhone to a
purpose-built GPS, the [Locosys GT-31][gps] (which I bought to use windsurfing and
sailing), the results were as expected: the GPS tracks from the GT-31 were much
more accurate.

I wanted the accurate GPS along with all the extra data collected by the iPhone,
so I now carry both. To combine the two data sources I put together a simple
script in R that replaces the GPS track in the iPhone data with the more
accurate data from the GT-31. The script is available on [GitHub][repo].

[gps]: http://www.locosystech.com/product.php?id=30
[repo]: https://github.com/adamatus/gt31-plus-wahoo
[wahoo]: http://www.wahoofitness.com/devices/wahoo-key.html
