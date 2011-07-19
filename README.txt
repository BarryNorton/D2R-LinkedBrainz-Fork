This is a fork of the D2R Server for the LinkedBrainz project.  For
more info about LinkedBrainz see

     http://linkedbrainz.c4dmpresents.org/

Changes so far:
 - remove "resource" from generated URIs
 - changed D2RQ jar so that "uuid" Postgres DB data type is accepted
 - hand crafting musicbrainz_mapping.n3 [8]


See [1] for a test suite (JUnit) of the MusicBrainz NGS [5] to Music Ontology [2] (etc. [3]) mappings.
See [6] for a maven [7] project of the LinkedBrainz specific D2R Server version.


D2R Server is a Linked Data server and SPARQL endpoint for relational
databases.

Check doc/index.html for more information, or visit the website at

    http://www4.wiwiss.fu-berlin.de/bizer/d2r-server/

for the latest updates on D2R Server.


[1] https://github.com/zazi/LinkedBrainzTestcases
[2] http://purl.org/ontology/mo/
[3] the mapping makes use of further Semantic Web Ontologies, e.g., FOAF [4]
[4] http://xmlns.com/foaf/0.1/
[5] http://wiki.musicbrainz.org/NGS
[6] https://github.com/zazi/D2RS-LinkedBrainz
[7] http://maven.apache.org/
[8] https://github.com/BarryNorton/D2R-LinkedBrainz-Fork/blob/master/musicbrainz_mapping.n3
