+++
title = "Example"
description = "Basic example for more examples see the [demo site](https://gamingrobot.github.io/zallery-demo)"
date = 2024-11-01
[taxonomies]
tags = ["Example"]
[extra]
thumbnail = "pexels-eberhardgross-1624438.jpg"
+++

{{ img(src="pexels-eberhardgross-1624438.jpg", alt="landscape" text="The default fit for images is fit to screen") }}
{{ img(src="pexels-eberhardgross-1624438.jpg", fit="max-width") }}

This image fit is set to `max-width` so it fills the width of the screen even if it overflows vertically

{{ img(src="pexels-eberhardgross-1624438.jpg", mobile_src="pexels-eberhardgross-1624438-mobile.jpg") }}

This image has a mobile friendly version