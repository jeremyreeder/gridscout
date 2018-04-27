# MGRS Search

## Search Google Maps from the terminal, get results in MGRS

This interactive Python script searches for places by using Google's _Places
API_.  Results are diplayed as a concise list of up to 60 places, along with
MGRS coordinates.

*Convenient for bulk collection of location data.* For example, an intelligence
analyst could use it to create a list of distribution centers, antenna farms,
or other critical infrastructure. He would then print a curated version of the
log file (log/mgrs-search.log) and store it for a rainy apocalyptic day when
the Internet may be unavailable. Later, he would refer to it as he annotates
polyester overlays on MGRS-based maps. Waterproof maps, of course. Remember,
it'll be raining.

## What's MGRS?

[Military Grid Reference System](https://en.wikipedia.org/wiki/Military_Grid_Reference_System).
It's used by NATO militaries because it's concise, has minimal distortion, and
makes for easy math. It's a whole-world variant of the UTM coordinate system.
Latitude and longitude are so 1941.

## Requirements

1. Python 2.7 required. Your OS probably already has it installed.

2. Install the following python modules:

    pip install --user googlemaps gmrs

3. Get a Google Places API key and store it in config/google_places.key.

    vi config/google_places.key

## Running mgrs-search

    ./mgrs-search
