+++
date = "2014-10-14T12:13:00-08:00"
draft = true
title = "America's Cup 34 Analysis"
summary = "The 34th America's Cup was amazing. I'm in the process of building interactive, web-based tools to fully appreciate the speed with which the AC72's sailed."
thumbnail = "/images/ac34-analysis-screenshot.png"

+++

{{< img src="/images/ac34-analysis-screenshot.png" caption="Analysis Screenshot" link="http://adamatus.github.io/ac-34-analysis/" >}}

America's Cup 34 was awesome. The new AC-72 catamarans were incredible. To help 
myself and others fully appreciate the speeds that these boats are capable of 
I'm creating this web-based interactive race analyzer. The end goal is to have 
detailed replays of the races, with additional information overlays 
(principally the apparent wind details).

This is currently very much a work in progress, as I work through integrating 
[d3.js][d3] and [Leaflet][leaflet].

The America's Cup Event Authority has provided detailed data on all of the 
races of the 34th America's Cup (as well as the events leading up to the Cup). 
These data were previously available [here][data], but they seem to have been 
removed. I'll try to locate the full dataset, but in the meantime, I've included 
the final race data in the repository.

You can check out the details of Race 19 (the final race) [here][demo]. 
The code is available at [GitHub][repo].

[d3]: http://d3js.org "d3.js"
[data]: http://noticeboard.americascup.com/Race-Data/
[demo]: http://adamatus.github.io/ac-34-analysis/
[leaflet]: http://leafletjs.com/
[repo]: https://github.com/adamatus/ac-34-analysis
