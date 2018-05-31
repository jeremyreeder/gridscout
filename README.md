# GridScout™


## Search Google Maps from the terminal, get results in MGRS

GridScout™ is a console-based tool for bulk collection of location data,
including MGRS coordinates, to be used by intelligence analysts. It uses
Google's _Places API_.

For more information, see [gridscout.net][docs] or the _docs_ folder.


### What's MGRS?

[Military Grid Reference System][mgrs]. It's used by NATO militaries because
it's concise, minimizes distortion, and makes for easy math. It's a whole-world
variant of the UTM coordinate system.  Latitude and longitude are so 1941.


## Installing GridScout™

1. Python 2.7 required. Your OS probably already has it installed.

2. Install the following python modules:

    pip2 install --user colorama googlemaps mgrs schema

3. Download GridScout™.

    cd

    git clone https://github.com/jeremyreeder/gridscout.git

3. Get a [Google API key][api-key] for their "Places" API and store it in the
`config` subdirectory.

    vi ~/gridscout/config/google_places.key


## Running GridScout™

    cd gridscout

    ./gridscout

![Screenshot of a GridScout™ search for newspaper
publishers](docs/images/search-screenshot.png)


[api-key]: https://cloud.google.com/maps-platform/#get-started
[docs]:    https://www.gridscout.net
[mgrs]:    https://en.wikipedia.org/wiki/Military_Grid_Reference_System
