This is a fork of the D2R Server for the LinkedBrainz project.  For
more info about LinkedBrainz see

     http://linkedbrainz.c4dmpresents.org/

Changes so far:
 - remove "resource" from generated URIs (see [6])
 - changed D2RQ jar so that "uuid" Postgres DB data type is accepted (see [9,11])
 - extensible Translator class handling (looking for Translator class interface implementations in super classes as well; see [9,11]) 
 - hand crafting musicbrainz_mapping.n3 (see [8])
 - LinkedBrainz related D2RS Translator classes (see [12])


See [1] for a test suite (JUnit) of the MusicBrainz NGS [5] to Music Ontology [2] (etc. [3]) mappings.
See [6] for a maven [7] project of the LinkedBrainz specific D2R Server version. See [9] for a maven project of D2RQ [10].

The jar files from [10,6,12] are occasionally pushed to the 'lib' folder of this project. Handcrafted versions of these project have to be manually copied into this folder to resolve the dependencies.


D2R Server [10] is a Linked Data server and SPARQL endpoint for relational
databases.

Check doc/index.html for more information, or visit the website at

    http://www4.wiwiss.fu-berlin.de/bizer/d2r-server/ or [10]

for the latest updates on D2R Server.


[1] https://github.com/zazi/LinkedBrainzTestcases
[2] http://purl.org/ontology/mo/
[3] the mapping makes use of further Semantic Web Ontologies, e.g., FOAF [4]
[4] http://xmlns.com/foaf/0.1/
[5] http://wiki.musicbrainz.org/NGS
[6] https://github.com/zazi/D2RS-LinkedBrainz (maven project)
[7] http://maven.apache.org/
[8] https://github.com/BarryNorton/D2R-LinkedBrainz-Fork/blob/master/musicbrainz_mapping.n3
[9] https://github.com/zazi/D2RQ-maven (maven project)
[10] https://github.com/cygri/d2rq
[11] https://github.com/cygri/d2rq/pull/1
[12] https://github.com/zazi/linkedbrainz-d2rs-translators (maven project)
