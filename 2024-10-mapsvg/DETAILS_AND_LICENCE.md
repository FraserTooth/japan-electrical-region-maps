## The Map

![Map of Japan Grid Regions](japan-grid-regions.svg?raw=true)

## Source

This map is based on a free Creative Commons map from [mapsvg](https://mapsvg.com), specifically from this URL: https://mapsvg.com/maps/japan

The map is under a Creative Commons Attribution 4.0 International License which requries reference to the source (as above) and the license, which can be found here: https://creativecommons.org/licenses/by/4.0/

I've added the Map Source file here under `map-source.svg`, which you can use as an overlay to show the original lines of the prefectures...if that floats your boat.

## Background

This was my first crack at making this map. There is no associated geojson or co-ordinates, and when I try to import it into a GIS program it errors out. I mainly made the changes by importing the SVG into Figma, overlaying Google Maps screenshots, tracing the new lines to split the SVG sections, then merging as needed. So, don't consider this a particularly accurate rendition!

But it looks quite nice and is perfectly useable for what I needed it for in the [denkicarbon.jp](https://denkicarbon.jp/) project. So, I'm happy with it!

## Changes Made to the Source

I fixed the map a bit, I can't remember what I changed specifically but I do remember that some islands were in the wrong prefectures, like Shodoshima, so...FYI.

## Other Notes

In order for me to easily hook into the SVG and color the sections, I have each region an ID, they are as follows:

- `HEPCO`
- `TOHOKUDEN`
- `TEPCO`
- `CHUDEN`
- `HOKURIKU`
- `KEPCO`
- `CHUGOKU`
- `YONDEN`
- `KYUDEN`
- `OKINAWADEN`
