# pleiades-gazetteer
This repository provides a home for tickets and other planning documents for [the *Pleiades* gazetteer of ancient places](http://pleiades.stoa.org), a joint project of the [Institute for the Study of the Ancient World](http://isaw.nyu.edu) at New York University, the [Ancient World Mapping Center](http://awmc.unc.edu) at the University of North Carolina at Chapel Hill, and [volunteer scholars, students, and enthusiasts](http://pleiades.stoa.org/credits/) around the world.

## Reporting bugs and requesting enhancements
Please feel free to open an issue in [our issue tracker](https://github.com/isawnyu/pleiades-gazetteer/issues) describing your difficulties and/or suggesting new features. Please note that there is a [help and documentation section on the *Pleiades* site](http://pleiades.stoa.org/help). You may also be able to get assistance (depending on availability of team members -- we don't have support staff) on the [*Pleiades* IRC Channel](http://pleiades.stoa.org/help/pleiades-irc).

## Pleiades 3
At the beginning of August 2015, the [National Endowment for the Humanities](http://www.neh.gov) announced the award of a $322,615 grant for major upgrades and improvements to the *P​leiades* gazetteer of ancient places. More information about the award is available [on the ISAW News Blog](http://isaw.nyu.edu/news/pleiades-grant-2015). A copy of the proposal narrative has been [posted online in PDF format](http://pleiades.stoa.org/files/pleiades-3-2015/proposal.pdf). Tickets (issues) related to the grant-funded work are kept in the main issue tracker on this repository; [they are labeled "p3"](https://github.com/isawnyu/pleiades-gazetteer/labels/p3). Other documents related to the *Pleiades* 3 effort may be found in [the pleiades3 branch of this repository](https://github.com/isawnyu/pleiades-gazetteer/tree/pleiades3).

## Code
Pleiades runs on [Plone](http://plone.org). With plenty of add-ons and customizations. Relevant repositories are listed below in two sections: [Pleiades-Specific Code](#pleiades-specific-code) and [Other Essential Code](#other-essential-code). These lists are as present incomplete, but it's a start; they presently address everything Pleiades-related in the isawnyu organization at GitHub, as well as everything present in the Pleiades package distributions directory are at http://atlantides.org/eggcarton/. Some of these items are presumed to be moribund or no longer used. Next step is to collate against the buildout and see what's actually pulled into Plone and reorganize these lists.

## Pleiades-Specific Code

### [BA Bibl Web](https://github.com/isawnyu/babibl-web)
 * Code and data behind the Barrington Atlas Bibliography with Pleiades links.

### [CAP Grids Web](https://github.com/isawnyu/capgrids-web)
 * no readme

### [CAP Grids](https://github.com/isawnyu/capgrids)
 * Places in the Classical Atlas Project (http://www.unc.edu/depts/cl_atlas/)
gazetteer are located by map number and grid square within the map. This
package includes the bounding coordinates of all grid squares and a function to
get the (left, bottom, top, right) bounding box of any grid square or map.

### [Pleiades 3 Buildout](https://github.com/isawnyu/pleiades3-buildout)
 * Pleiades Buildout

### [Pleiades API](https://github.com/isawnyu/pleiades-api)
 * Documentation and code for the Pleiades Place API http://api.pleiades.stoa.org

### [Pleiades Atom](http://www.atlantides.org/trac/pleiades/browser/pleiades.atom)
 * Atom formatting of Pleiades entities
 * off-github svn

### [Pleiades Bulkup](http://www.atlantides.org/trac/pleiades/browser/pleiades.bulkup)
 * no readme
 * Off-GitHub SVN

### [Pleiades Content Ratings](http://www.atlantides.org/trac/pleiades/browser/pleiades.contentratings)
 * This product may contain traces of nuts.
 * Off-GitHub SVN

### [Pleiades Dump](https://github.com/isawnyu/pleiades-dump)
 * Data about the locations, names, and places of Pleiades is regularly read from the site catalog and written to CSV format files. The descriptions of the records in these files and the code that writes them is contained in this package.

### [Pleiades Entity](https://github.com/isawnyu/PleiadesEntity)
 * The PleiadesEntity product provides Plone content types suitable for
constructing and managing collections of geographic data items, for
example, digital gazetteer entries.

### [Pleiades Frontpage](https://github.com/isawnyu/pleiades-frontpage)
 * The not-part-of-the-Plone front page for http://pleiades.stoa.org. 

### [Pleiades GANE](https://github.com/isawnyu/pleiades-gane)
 * GANE data and Pleiades import scripts.

### [Pleiades Geographer](http://www.atlantides.org/trac/pleiades/browser/pleiades.geographer)
 * no readme
 * off-github svn
 
### [Pleiades Iterate](http://www.atlantides.org/trac/pleiades/browser/pleiades.iterate)
 * no readme
 * off-github svn

### [Pleiades JSON](http://www.atlantides.org/trac/pleiades/browser/pleiades.json)
 * no readme
 * off-github svn

### [Pleiades Keytree](http://www.atlantides.org/trac/pleiades/browser/pleiades.keytree)
 * Keytree provides several functions for manipulating KML using the ElementTree API. Elements can be adapted to the Python geo interface and then used with packages like [Shapely](#shapely).
 * Off-GitHub SVN
 * Note now (not yet used by Pleiades): [toblerity/keytree](https://github.com/Toblerity/keytree)

### [Pleiades KML](https://github.com/isawnyu/pleiades-kml)
 * no readme
 
### [Pleiades Neighbors](http://www.atlantides.org/trac/pleiades/browser/pleiades.neighbors)
 * no readme
 * off-github svn
 
### [Pleiades Normalizer](http://www.atlantides.org/trac/pleiades/browser/pleiades.normalizer)
 * This package provides a unicode to ascii normalizer for Barrington Atlas feature labels based on the Plone Foundation's plone.i18n.
 * off-github svn

### [Pleiades Notre Dame](http://www.atlantides.org/trac/pleiades/browser/pleiades.notredame)
 * Adapted Notre Dame theme for Plone 3 with color scheme based on new Plone Logo.
 * off-github svn

### [Pleiades Open Layers](http://www.atlantides.org/trac/pleiades/browser/pleiades.openlayers)
 * OpenLayers support for Pleiades
 * No longer used?
 * off-github svn

### [Pleiades Place Match](http://www.atlantides.org/trac/pleiades/browser/pleiades.placematch)
 * no readme
 * off-github svn
 
### [Pleiades Policy](http://www.atlantides.org/trac/pleiades/browser/pleiades.policy)
 * no readme
 * off-github svn

### [Pleiades Portlet Flickr](http://www.atlantides.org/trac/pleiades/browser/pleiades.portlet.flickr)
 * The Flickr Portlet synposizes Flickr content related to places via Pleiades machine tags.
 * off-github svn

### [Pleiades Portlet Pelagios](https://github.com/isawnyu/pleiades.portlet.pelagios)
 * The Pelagios Portlet synposizes Pelagios content related to places.

### [Pleiades Portlet References](http://www.atlantides.org/trac/pleiades/browser/pleiades.portlet.references)
 * Forked from collective.portlet.references 1.0 so that we could have different relations and back references as well.
 * off-github svn

### [Pleiades Reconciliation](http://www.atlantides.org/trac/pleiades/browser/pleiades.reconciliation)
 * no readme
 * off-github svn

### [Pleiades Sitemap](http://www.atlantides.org/trac/pleiades/browser/pleiades.sitemap)
 * no readme
 * off-github svn

### [Pleiades Transliteration](http://www.atlantides.org/trac/pleiades/browser/pleiades.transliteration)
 * This package provides modules for transliteration of names from Greek and Latin writing systems into our modern Roman writing system following conventions of the Classical Atlas Project.
 * No longer used?
 * off-github svn
 
### [Pleiades Vaytrou Index](http://www.atlantides.org/trac/pleiades/browser/pleiades.vaytrouindex)
 * no readme
 * off-github svn

### [Pleiades Vocabularies](http://www.atlantides.org/trac/pleiades/browser/pleiades.vocabularies)
 * no readme
 * off-github svn
 
### [Pleiades Workspace](http://www.atlantides.org/trac/pleiades/browser/pleiades.workspace)
 * no readme
 * off-github svn

### [Pleiades RDF](https://github.com/isawnyu/pleiades-rdf)
 * This is the pleiades.rdf package. It provides RDF views of individual Pleiades places (such as http://pleiades.stoa.org/places/1043/turtle) and the comprehensive RDF dataset dumps at http://atlantides.org/downloads/pleiades/rdf/.

### [Pleiades Update Overlays](https://github.com/isawnyu/pleiades-update-overlays)
 * In several content development projects we've scripted broad, bulk updates to Pleiades places, locations, and names (henceforth "objects") using variations on the Pleiades dump format as input data formats. To open this avenue of bulk updates to more Pleiades partners we document herein what we will call the Pleiades Update Overlay Format (or Overlay Format, for short). This format is designed for Pleiades users who would like to create or update 40-1000 objects at a time.

## Other Essential Code

### [CTypes]

### [PyProj]

### [Python LDAP]

### [Shapely](https://pypi.python.org/pypi/Shapely)
 * Manipulation and analysis of geometric objects in the Cartesian plane.

### [Simple JSON]

### [Tornado]

### [ZGeo Atom]

### [ZGeo Geographer]

### [ZGeo KML]

### [ZGeo Plone Atom]

### [ZGeo Plone Geographer]

### [ZGeo Plone KML]


## About
*Pleiades* provides open access to the most comprehensive geospatial dataset for antiquity available today. It serves as an indispensable component of at least 40 other important digital humanities projects, ranging from online editions of primary sources for students to expert systems supporting advanced research in fields like archaeology, epigraphy, and numismatics. It also constitutes a core resource for classroom activities focused on ancient geography.

Find out more on the *Pleiades* website: http://pleiades.stoa.org.

*Pleiades* has received significant support from the National Endowment for the Humanities since 2006. Any views, findings, conclusions, or recommendations expressed in this publication do not necessarily reflect those of the National Endowment for the Humanities.



