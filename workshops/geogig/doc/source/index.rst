GeoGig Workshop
===============

Welcome to the GeoGig workshop!

Welcome!
--------

This workshop will introduce attendees to GeoGig, a distributed version control system for geospatial data. We will start with a discussion of distributed version control as applied to the specific case of geospatial data, followed by a hands-on session with the GeoGig command-line interface, and finally the graphical GeoGig interface in QGIS. Attendees will learn how GeoGig can be a key tool in a workflow when managing geospatial data.

The workshop is geared toward those with no prior GeoGig experience, but familiarity with basic GIS concepts is suggested. It will also be useful to have familiarity with the desktop GIS client QGIS, along with Git, the distributed version control system, but neither of these are required.

Prerequisites and software setup
--------------------------------

In order to perform this workshop, you will need the following software installed on your system:

* `QGIS <http://boundlessgeo.com/solutions/solutions-software/qgis/qgis-download/>`_
* `GeoGig website <http://geogig.org>`_

Topics covered
--------------

The following material will be covered in this workshop:

:ref:`theory`
  Discussion of versioned geospatial data, common workflows, and the connection with other distributed version control systems.

:ref:`cmd`
  A tour of the GeoGig command line interface, including creating and managing commits and branches, as well as merging from different repositories.

:ref:`workflow`
  Introducing a workflow for a distributed team of GIS analysts and a data manager responsible for approving changes to the product.

:ref:`moreinfo`
  More information about GeoGit including links and a glossary of terms.

Workshop Materials
------------------

The following directories will be found inside of the workshop bundle:

:file:`doc`
  The workshop documentation in HTML format. (This document.)

:file:`data`
  Data and other project files to be used in the workshop.

These directories should be placed on your desktop.

Ready to Begin?
---------------

Great! Head to the first section, :ref:`theory`.

.. toctree::
   :maxdepth: 2
   :numbered:
   :hidden:

   theory/index
   cmd/index
   workflow/index
   moreinfo/index
