Stac Info
---------

Spatial Temporal Asset Catalog (STAC) is a specification for creating
metadata for geospatial assets. It is designed to be flexible and to be
able to describe a wide range of assets, from SAR imagery to point
clouds to full 3D scenes. It is designed to be easily extended to
support new domains and new types of data. STAC is based on GeoJSON and
is intended to be easily read by both humans and machines. STAC is
designed to be able to describe any type of geospatial asset.

stac-info package documentation
-------------------------------

This package contains the documentation for the ``stac-info`` package

Installation
------------

To install the package, run the following command:

.. code:: bash

   pip install stac-info

Usage
-----

To use the package, usage is similar to the following:

.. code:: python

   from stac_info.search import EarthSearch

   data = EarthSearch("https://earth-search.aws.element84.com/v0/search")

   # filter all collections by bounding box and datetime
   data.filter([-122.68, 45.52, -122.67, 45.53], "2017-01-01/2018-01-01")

Disclaimer
~~~~~~~~~~

This is not an official package and is not affiliated with the STAC
project. This package is a personal project and is not supported by any
organization.

License
-------

This project is licensed under the terms of the MIT license.

Contributing
------------

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
