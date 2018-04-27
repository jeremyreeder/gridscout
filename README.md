# mgrs-search

Search Google Maps from the terminal, get results in MGRS (Military Grid Reference System).

This interactive Python script searches for places by using Google's "Places API".
Results are diplayed as a list of up to 60 places with MGRS coordinates.

Convenient for conduction map-based data collection in a way
that is easy to communicate, and for annotating physical overlays
of maps which use MGRS.

## Requirements

1. Python 2.7 required. Your OS probably already has it installed.

2. Install the following python modules:

    pip install --user googlemaps gmrs

3. Get a Google Places API key and store it in config/google_places.key.

    vi config/google_places.key

## Running mgrs-search

    ./mgrs-search
