+++
date = "2015-06-03T12:12:14-08:00"
draft = true
title = "Mendota Breeze"
summary = "As a wind-junky (sailer/kiter/windersurfer), I'm always interested in the current wind conditions. For me, that's the wind on Lake Mendota in Madison, WI.  I coded up a project using d3.js to display data pulled and summarized from the wind meters on the lake."
thumbnail = "/images/mendota-breeze.png"

+++

{{< img src="/images/mendota-breeze.png" caption="Mendota Breeze" link="http://wind.riggall.info" >}}

As a wind-junky (sailer/kiter/windersurfer), I'm always interested in the
current wind conditions. For me, that's the wind on Lake Mendota in Madison, WI.
The Space Science and Engineering Center (SSEC) and Atmospheric and Oceanic
Sciences (AOS) department at the University of Wisconsin-Madison maintain
several instruments that measure the current weather and wind in the area. This
data is freely provided by [the Lake Mendota Bouy][bouy].

I wanted a quicklook summary of the recent conditions, so I coded up a project
using [d3.js][d3] to display data pulled and summarized from the AOS instruments.

You can check out the current condition [here][wind]. The code is available at 
[GitHub][repo].

[bouy]: http://metobs.ssec.wisc.edu/buoy/ "Lake Mendota Bouy"
[d3]: http://d3js.org "d3.js"
[repo]: https://github.com/adamatus/mendota-breeze
[wind]: http://wind.riggall.info "Current Lake Mendota Conditions"
