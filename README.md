# GridScout


## Search Google Maps from the terminal, get results in MGRS

This interactive Python script searches for places by using Google's _Places
API_. Results are displayed as a concise list of up to 60 places, along with
MGRS coordinates.

Convenient for bulk collection of location data. For example, an intelligence
analyst could use this tool to create a list of distribution centers, antenna
farms, and other critical infrastructure. He would then print a curated version
of the log file (`log/gridscout.log`) and store it for a rainy apocalyptic
day when the Internet may be unavailable. Later, he would refer to it as he
annotates polyester overlays on MGRS-based maps. Waterproof maps, of course.
Remember, it'll be raining.


### What's MGRS?

[Military Grid Reference
System](https://en.wikipedia.org/wiki/Military_Grid_Reference_System).  It's
used by NATO militaries because it's concise, minimizes distortion, and makes
for easy math. It's a whole-world variant of the UTM coordinate system.
Latitude and longitude are so 1941.


## Installing GridScout

1. Python 2.7 required. Your OS probably already has it installed.

2. Install the following python modules:

    pip install --user colorama gmrs googlemaps schema

3. Download GridScout.

    cd

    git clone https://github.com/jeremyjohnreeder/gridscout.git

3. Get a Google Places API key and store it in the `config` subdirectory.

    vi ~/gridscout/config/google_places.key


## Running GridScout

    cd gridscout

    ./gridscout
