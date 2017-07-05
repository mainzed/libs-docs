# Endpoints

## GeoNames JSON

*vorläufig*

`http://ls-dev.i3mainz.hs-mainz.de/geonames-json/getJSON`

Beispiele:

- [GeoNames Deutschland JSON](http://ls-dev.i3mainz.hs-mainz.de/geonames-json/getJSON?uri=http://sws.geonames.org/2921044)

- [GeoNames Deutschland GeoJSON](http://ls-dev.i3mainz.hs-mainz.de/geonames-json/getJSON?uri=http://sws.geonames.org/2921044&format=geojson)

## Getty TGN JSON

*vorläufig*

`http://ls-dev.i3mainz.hs-mainz.de/gettytgn-json/getJSON`

Beispiele:

- [Getty TGN Deutschland JSON](http://ls-dev.i3mainz.hs-mainz.de/gettytgn-json/getJSON?uri=http://vocab.getty.edu/tgn/7000084)

- [Getty TGN Deutschland GeoJSON](http://ls-dev.i3mainz.hs-mainz.de/gettytgn-json/getJSON?uri=http://vocab.getty.edu/tgn/7000084&format=geojson)

## RDF4J / OpenRDF Sesame Proxy

*vorläufig*

`http://ls-dev.i3mainz.hs-mainz.de/rdfproxy/SPARQL`

Beispiele:

- [Labeling System as SPARQL XML](http://ls-dev.i3mainz.hs-mainz.de/rdfproxy/SPARQL?serverURL=http://ls-dev.i3mainz.hs-mainz.de/rdf4j-server&repo=labelingsystem&query=SELECT%20*%20WHERE%20{%20?s%20?p%20?o.%20}%20LIMIT%20100&format=xml)

- [TexTelSem as SPARQL JSON](http://ls-dev.i3mainz.hs-mainz.de/rdfproxy/SPARQL?serverURL=http://higeomes.i3mainz.hs-mainz.de/openrdf-sesame&repo=textelsem&query=SELECT%20*%20WHERE%20{%20?s%20?p%20?o.%20}%20LIMIT%20100&format=json)
