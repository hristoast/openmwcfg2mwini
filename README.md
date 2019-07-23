# openmwcfg2mwini

Turn an OpenMW plugin load order into a vanilla-compatible one.

## Installation and Usage

1. Ensure you've got Python 3 (3.4 or greater)
1. Clone this repo
1. `cd` into this repo
1. Run the `openmw2mwini.py` script:

        ./openmw2mwini.py path/to/openmw.cfg

An ini-compatible load order is printed to stdout, you can save it to a file like this:

        ./openmw2mwini.py path/to/openmw.cfg > path/to/mwloadorder.ini

## Limitations

I didn't write this to be pretty or user-friendly in any way.  As such, there's a lack of user-facing messages and things you might expect from a more well thought out program (also possibly some bugs).
