telize-ip-geolocate-google-maps-with-directions
===============================================

A JavaScript mash-up between Telize IP Geolocation API and Google Maps API to deliver automatic driving directions on your website that automatically detect the visitor's location and plot maps and directions to your location.

## What does it do?

This will determine your location (based on your IP-address) using the free Telize geolocation API, then feed that information into a Google Maps driving directions script as the starting point. The resulting output will provide directions from your approximate location to a location of your choosing.

DEMO HERE: http://dubows.com/demo.html

## How do I use it?

Just grab your own Google Maps API key and pop it into the HTML page in-between the comment blocks that say !--REPLACE WITH YOUR OWN API KEY HERE>, replace the destination address with one of your choosing in-between the other comment blocks that say !--REPLACE WITH YOUR CUSTOM ADDRESS HERE>. Other than that, nothing is needed for the bare-bones implementation to function on your site. 

## Important notes:

This is an update to a Max-Mind geolocation mashup I made some years ago, it's the same except that it uses Telize instead of Max-Mind, and it uses jQuery's document.ready(), .getJSON(), and .text() functions and callbacks to query the Telize API and update the DOM. You should be able to adjust the script accordingly to use vanilla JS or another framework without too much retooling. 

## Misc. and History:

I originally made this auto-locate map widget (using Max-Mind) for a freelance web development client many moons ago. I've since recycled the same code in one way or another for dozens of other sites. Unfortunately, Max-Mind recently changed their Terms of Service, and they now require a subscription to use their legacy API (or any of their APIs for that matter), so I have had to recently update my script. I hope you find it useful :o)
