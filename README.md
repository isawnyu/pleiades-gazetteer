# pleiades-gazetteer
This repository provides a home for tickets and other planning documents for [the *Pleiades* gazetteer of ancient places](http://pleiades.stoa.org), a joint project of the [Institute for the Study of the Ancient World](http://isaw.nyu.edu) at New York University, the [Ancient World Mapping Center](http://awmc.unc.edu) at the University of North Carolina at Chapel Hill, and [volunteer scholars, students, and enthusiasts](http://pleiades.stoa.org/credits/) around the world.

## Reporting bugs and requesting enhancements
Please feel free to open an issue in [our issue tracker](https://github.com/isawnyu/pleiades-gazetteer/issues) describing your difficulties and/or suggesting new features. Please note that there is a [help and documentation section on the *Pleiades* site](http://pleiades.stoa.org/help). You may also be able to get assistance (depending on availability of team members -- we don't have support staff) on the [*Pleiades* IRC Channel](http://pleiades.stoa.org/help/pleiades-irc).

## Pleiades 3
At the beginning of August 2015, the [National Endowment for the Humanities](http://www.neh.gov) announced the award of a $322,615 grant for major upgrades and improvements to the *P​leiades* gazetteer of ancient places. More information about the award is available [on the ISAW News Blog](http://isaw.nyu.edu/news/pleiades-grant-2015). A copy of the proposal narrative has been [posted online in PDF format](http://pleiades.stoa.org/files/pleiades-3-2015/proposal.pdf). Tickets (issues) related to the grant-funded work are kept in the main issue tracker on this repository; [they are labeled "p3"](https://github.com/isawnyu/pleiades-gazetteer/labels/p3). Other documents related to the *Pleiades* 3 effort may be found in [the pleiades3 branch of this repository](https://github.com/isawnyu/pleiades-gazetteer/tree/pleiades3).

## Code
This list is as present incomplete, but it's a start.

### [Pleiades Entity](https://github.com/isawnyu/PleiadesEntity)
The PleiadesEntity product provides Plone content types suitable for
constructing and managing collections of geographic data items, for
example, digital gazetteer entries.

### [Pleiades Frontpage](https://github.com/isawnyu/pleiades-frontpage)
The not-part-of-the-Plone front page for http://pleiades.stoa.org. 

### [Pleiades Dump](https://github.com/isawnyu/pleiades-dump)
Data about the locations, names, and places of Pleiades is regularly read from the site catalog and written to CSV format files. The descriptions of the records in these files and the code that writes them is contained in this package.

### [Pleiades KML](https://github.com/isawnyu/pleiades-kml)
**there was no readme**

### [Pleiades GANE](https://github.com/isawnyu/pleiades-gane)
GANE data and Pleiades import scripts.

### [Pleiades 3 Buildout](https://github.com/isawnyu/pleiades3-buildout)
Pleiades Buildout

### [Pleiades RDF](https://github.com/isawnyu/pleiades-rdf)
This is the pleiades.rdf package. It provides RDF views of individual Pleiades places (such as http://pleiades.stoa.org/places/1043/turtle) and the comprehensive RDF dataset dumps at http://atlantides.org/downloads/pleiades/rdf/.

### [Pleiades API](https://github.com/isawnyu/pleiades-api)
Documentation and code for the Pleiades Place API http://api.pleiades.stoa.org

### [Pleiades Update Overlays](https://github.com/isawnyu/pleiades-update-overlays)
In several content development projects (DARMC coordinate imports, Scott Vanderbilt's buildout of Hadrian's Wall milecastles, etc) work we've scripted broad, bulk updates to Pleiades places, locations, and names (henceforth "objects") using variations on the Pleiades dump format as input data formats. To open this avenue of bulk updates to more Pleiades partners we document herein what we will call the Pleiades Update Overlay Format (or Overlay Format, for short). This format is designed for Pleiades users who would like to create or update 40-1000 objects at a time.

### [BA Bibl Web](https://github.com/isawnyu/babibl-web)
Code and data behind the Barrington Atlas Bibliography with Pleiades links.

### [CAP Grids Web](https://github.com/isawnyu/capgrids-web)
**no readme**

### [CAP Grids](https://github.com/isawnyu/capgrids)
Places in the Classical Atlas Project (http://www.unc.edu/depts/cl_atlas/)
gazetteer are located by map number and grid square within the map. This
package includes the bounding coordinates of all grid squares and a function to
get the (left, bottom, top, right) bounding box of any grid square or map.

### Egg Carton
Pleiades package distributions are at http://atlantides.org/eggcarton/.

## About
*Pleiades* provides open access to the most comprehensive geospatial dataset for antiquity available today. It serves as an indispensable component of at least 40 other important digital humanities projects, ranging from online editions of primary sources for students to expert systems supporting advanced research in fields like archaeology, epigraphy, and numismatics. It also constitutes a core resource for classroom activities focused on ancient geography.

Find out more on the *Pleiades* website: http://pleiades.stoa.org.

*Pleiades* has received significant support from the National Endowment for the Humanities since 2006. Any views, findings, conclusions, or recommendations expressed in this publication do not necessarily reflect those of the National Endowment for the Humanities.



