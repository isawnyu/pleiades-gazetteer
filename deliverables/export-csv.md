# repackage nightly CSV export code and make it comprehensive

From [the Pleiades 3 proposal narrative](http://pleiades.stoa.org/files/pleiades-3-2015/proposal.pdf), page 4:

> We will continue to use the well-known and easily parsed Comma-Separated Value (CSV) format for nightly export of content from Pleiades, but extract the code that creates it from Plone so that we can make it reflect comprehensively the contents of the database without negative impact on web performance. ([See LOC Formats, CSV](http://www.digitalpreservation.gov/formats/fdd/fdd000323.shtml). Metadata and access to the Pleiades dump files: http://pleiades.stoa.org/downloads.)

From the Pleiades 3 proposal data management plan, page D1:

> Pleiades geographic data is published over the web from the system in a number of standard formats, and we will maintain the full suite of these going forward. Individual data serializations for each Pleiades place, as described in the “Innovations” section, are disseminated using HTTP via stable URIs. The current nightly export to CSV format will continue to be disseminated via the Pleiades Downloads page at http://pleiades.stoa.org/downloads/. It will be enhanced to include all published data items and their attributes, thereby constituting a complete, application-neutral copy of the gazetteer in a widely used, non-proprietary open format that is easy for digital repositories and collaborating third parties to maintain and use. Textual information in all files is encoded using the standard UTF-8 (Universal Character Set Transformation Format 8-bit). This export package is currently accompanied by a ReadMe.txt file explaining the content and its expected use. The PI, in collaboration with the Managing Editors, will enhance this metadata with the addition of appropriate documentation in accordance with ISO 19115:2003 “Geographic information – Metadata (corrigendum 1)” as recommended by the Federal Geographic Data Committee (FGDC).

