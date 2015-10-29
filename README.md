# pleiades-gazetteer
This repository provides a home for tickets and other planning documents for [the *Pleiades* gazetteer of ancient places](http://pleiades.stoa.org), a joint project of the [Institute for the Study of the Ancient World](http://isaw.nyu.edu) at New York University, the [Ancient World Mapping Center](http://awmc.unc.edu) at the University of North Carolina at Chapel Hill, and [volunteer scholars, students, and enthusiasts](http://pleiades.stoa.org/credits/) around the world.


## Reporting bugs and requesting enhancements
Please feel free to open an issue in [our issue tracker](https://github.com/isawnyu/pleiades-gazetteer/issues) describing your difficulties and/or suggesting new features. Please note that there is a [help and documentation section on the *Pleiades* site](http://pleiades.stoa.org/help). You may also be able to get assistance (depending on availability of team members -- we don't have support staff) on the [*Pleiades* IRC Channel](http://pleiades.stoa.org/help/pleiades-irc).


## Pleiades 3
At the beginning of August 2015, the [National Endowment for the Humanities](http://www.neh.gov) announced the award of a $322,615 grant for major upgrades and improvements to the *P​leiades* gazetteer of ancient places. More information about the award is available [on the ISAW News Blog](http://isaw.nyu.edu/news/pleiades-grant-2015). A copy of the proposal narrative has been [posted online in PDF format](http://pleiades.stoa.org/files/pleiades-3-2015/proposal.pdf). Tickets (issues) related to the grant-funded work are kept in the main issue tracker on this repository; [they are labeled "p3"](https://github.com/isawnyu/pleiades-gazetteer/labels/p3). Other documents related to the *Pleiades* 3 effort may be found in [the pleiades3 branch of this repository](https://github.com/isawnyu/pleiades-gazetteer/tree/pleiades3).


## Code: Plone Buildout
Pleiades runs on [Plone](http://plone.org). With plenty of add-ons and customizations. Relevant repositories are listed in the following sectinos. 

The Plone buildout for Pleiades is [Pleiades 3 Buildout](https://github.com/isawnyu/pleiades3-buildout). The [pleiades-production.cfg config file](https://github.com/isawnyu/pleiades3-buildout/blob/master/pleiades-production.cfg) is used on production; it extends [buildout.cfg](https://github.com/isawnyu/pleiades3-buildout/blob/master/buildout.cfg) and [production-versions.cfg](https://github.com/isawnyu/pleiades3-buildout/blob/master/production-versions.cfg). Note that the buildout makes use of a static package distributions directory at http://atlantides.org/eggcarton/. 


## Other Pleiades Code for Plone
The following packages are developed by the Pleiades project and are included in the production buildout. Links to repositories are provided and version numbers, where pinned in the buildout, are indicated.

### Pleiades Atom (pleiades.atom)
 * Atom formatting of Pleiades entities
 * pinned to version 0.3
 * repository: [svn at atlantides.org](http://www.atlantides.org/trac/pleiades/browser/pleiades.atom)

### Pleiades Bulkup (pleiades.bulkup)
 * no readme
 * pinned to version 0.3
 * repository: [svn at atlantides.org](http://www.atlantides.org/trac/pleiades/browser/pleiades.bulkup)

### Pleiades CAP Grids (pleiades.capgrids)
 * Places in the Classical Atlas Project (http://www.unc.edu/depts/cl_atlas/)
gazetteer are located by map number and grid square within the map. This
package includes the bounding coordinates of all grid squares and a function to
get the (left, bottom, top, right) bounding box of any grid square or map.
 * repository: [github:isawnyu/capgrids](https://github.com/isawnyu/capgrids)

### Pleiades Content Ratings (pleiades.contentratings)
 * This product may contain traces of nuts.
 * repository: [svn at atlantides.org](http://www.atlantides.org/trac/pleiades/browser/pleiades.contentratings)

### Pleiades Dump (pleiades.dump)
 * Data about the locations, names, and places of Pleiades is regularly read from the site catalog and written to CSV format files. The descriptions of the records in these files and the code that writes them is contained in this package.
 * pinned to version 0.12.1
 * repository: [github:/isawnyu/pleiades-dump](https://github.com/isawnyu/pleiades-dump)
 
### [Pleiades Entity](https://github.com/isawnyu/PleiadesEntity)
 * The PleiadesEntity product provides Plone content types suitable for
constructing and managing collections of geographic data items, for
example, digital gazetteer entries.
 * **NB: PleiadesEntity is not installed by the buildout.** In the buildout, the products/README.txt file says: "Checkout or install PleiadesEntity into this folder."

### [Pleiades Geographer](http://www.atlantides.org/trac/pleiades/browser/pleiades.geographer)
 * no readme
 * off-github svn
 
### [Pleiades Iterate](http://www.atlantides.org/trac/pleiades/browser/pleiades.iterate)
 * no readme
 * off-github svn

### [Pleiades JSON](http://www.atlantides.org/trac/pleiades/browser/pleiades.json)
 * no readme
 * off-github svn

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

### [Pleiades RDF](https://github.com/isawnyu/pleiades-rdf)
 * This is the pleiades.rdf package. It provides RDF views of individual Pleiades places (such as http://pleiades.stoa.org/places/1043/turtle) and the comprehensive RDF dataset dumps at http://atlantides.org/downloads/pleiades/rdf/.

### [Pleiades Reconciliation](http://www.atlantides.org/trac/pleiades/browser/pleiades.reconciliation)
 * no readme
 * off-github svn

### [Pleiades Sitemap](http://www.atlantides.org/trac/pleiades/browser/pleiades.sitemap)
 * no readme
 * off-github svn

### Pleiades Theme (pleiades.theme)

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


## Third-Party Code Used in the Plone Buildout

### [CTypes]


### Keytree
 * Note now: [toblerity/keytree](https://github.com/Toblerity/keytree)


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


## Other Pleiades-Specific Website Components (i.e., non-Plone)

### [BA Bibl Web](https://github.com/isawnyu/babibl-web)
 * Code and data behind the Barrington Atlas Bibliography with Pleiades links.

### [CAP Grids Web](https://github.com/isawnyu/capgrids-web)
 * no readme

### [Pleiades API](https://github.com/isawnyu/pleiades-api)
 * Documentation and code for the Pleiades Place API http://api.pleiades.stoa.org

### [Pleiades Frontpage](https://github.com/isawnyu/pleiades-frontpage)
 * The not-part-of-the-Plone front page for http://pleiades.stoa.org. 

### [Pleiades GANE](https://github.com/isawnyu/pleiades-gane)
 * GANE data and Pleiades import scripts.

### [Pleiades Portlet References](http://www.atlantides.org/trac/pleiades/browser/pleiades.portlet.references)
 * Forked from collective.portlet.references 1.0 so that we could have different relations and back references as well.
 * off-github svn


## Other Pleiades Code

### [Pleiades Update Overlays](https://github.com/isawnyu/pleiades-update-overlays)
 * In several content development projects we've scripted broad, bulk updates to Pleiades places, locations, and names (henceforth "objects") using variations on the Pleiades dump format as input data formats. To open this avenue of bulk updates to more Pleiades partners we document herein what we will call the Pleiades Update Overlay Format (or Overlay Format, for short). This format is designed for Pleiades users who would like to create or update 40-1000 objects at a time.



## Possibly moribund/obsolete code
### [Pleiades Keytree](http://www.atlantides.org/trac/pleiades/browser/pleiades.keytree)
 * Keytree provides several functions for manipulating KML using the ElementTree API. Elements can be adapted to the Python geo interface and then used with packages like [Shapely](#shapely).
 * Off-GitHub SVN
 * NB: ***only specified in buildout in devel.cfg*** and plain old keytree **is** in the production buildout (see above)



## About
*Pleiades* provides open access to the most comprehensive geospatial dataset for antiquity available today. It serves as an indispensable component of at least 40 other important digital humanities projects, ranging from online editions of primary sources for students to expert systems supporting advanced research in fields like archaeology, epigraphy, and numismatics. It also constitutes a core resource for classroom activities focused on ancient geography.

Find out more on the *Pleiades* website: http://pleiades.stoa.org.

*Pleiades* has received significant support from the National Endowment for the Humanities since 2006. Any views, findings, conclusions, or recommendations expressed in this publication do not necessarily reflect those of the National Endowment for the Humanities.



