# cohpy.org

Contents of https://www.cohpy.org .

## Building

This folder contains the source used to generate a static site using Nikola.

Installation and documentation at https://getnikola.com/

1. Create and activate a [virtualenv](https://virtualenv.pypa.io/en/stable/).
1. Install the requirements: `python -m pip install -r requirements.txt`.

Configuration file for the site is ``conf.py``.

To build the site:

    nikola build

To see it:

    nikola serve -b

To check all available commands:

    nikola help

