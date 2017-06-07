# RDF4J / OpenRDF Sesame Proxy

*Stand: 07.06.2017*

## SPARQL Proxy

` GET http://localhost:8084/rdfproxy/SPARQL`

### Description

Gibt ein SPARQL result zurück.

### Requires authentication

none

### Parameters

* **query** *(mendatory)* — encoded SPARQL query.
* **serverURL** *(mendatory)* — Server URL eines OpenRDF-Sesame oder RDF4J Triplestores.
* **repo** *(mendatory)* — repository im triplestore.
* **format** *(optional)* — {xml, json, csv, tsv, application/sparql-results+xml, application/sparql-results+json}.
* **file** *(optional)* — {true, false}.

### Headers

`Accept: application/sparql-results+xml`

`Accept: application/sparql-results+json`

### Return format

Ein SPARQL result Objekt.

### Response Codes

* *200 OK* — Everything worked fine.
* *500 Internal Server Error* — Some error on server side.
