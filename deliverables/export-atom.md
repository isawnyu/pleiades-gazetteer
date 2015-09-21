# repackage code for Atom export

From [the Pleiades 3 proposal narrative](http://pleiades.stoa.org/files/pleiades-3-2015/proposal.pdf), page 4:

> To enhance the performance of the Pleiades API, we will also repackage and extend the code that produces the five different serialization formats we provide for each place record: KML (for Google Earth), **Atom (for feed readers and web syndication),** the two most common syntaxes of the LOD-oriented Resource Description Framework (RDF+XML and Turtle), and GeoJSON (a format for exchanging spatial data with external web applications). Note: Keyhole Markup Language (KML): LOC Formats, KML. Note: Atom Syndication Format: Nottingham 2005.

> In revising the code that creates each of these formats, we will alter it to write each discrete resource to a separate file on disk only when a change is made to the corresponding record in the database, instead of the current strategy of repeatedly generating serializations from the database each time they are requested by an external user (a time-consuming and compute-intensive task). This change will also make it possible for us to use a “disk caching” strategy for the content we deliver through the API, rather than the ineffective memory-based caching strategy we use now.
