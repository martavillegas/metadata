README
======

Ongoing draft version of the MetaShare model in LOD. Comments and suggestions are welcome. 

(1) license: 
	CC-BY (3.0)

(2) More info:
	See "Metadata as Linked Open Data: mapping disparate XML metadata registries into one RDF/OWL registry" Villegas, Melero &amp; Bel.  published in LREC-2014

(3) Name spaces updated:
	ms: http://lodserver.iula.upf.edu/Metashare/ontology/ (MS ontology)
	bio: http://lodserver.iula.upf.edu/Metashare/services/ (Service ontology)
	test: http://lodserver.iula.upf.edu/Metashare/resource/ (IULA-UPF records)

(4) File contents:
	MetaShare.ttl 			(contains MetaSahre ontology (imports BioServices.ttl))
	BioSerices.ttl 			(service ontology based on the BioCatalogue model)
	UPF-MetadataRecords.ttl (everything plus the records describing resources & services)
	browser.ttl 			(used by the IULA browser at http://lod.iula.upf.edu/)

(5) SPARQL endpoint:
	http://lodserver.iula.upf.edu/sparql
	GRAPH IRI: <http://MetashareLOD.org>

(6) Faceted Browser:
	http://lodserver.iula.upf.edu/fct
	
(7) IULA browser:
	http://lod.iula.upf.edu/



