# Specific Subject with the Relationships

```sql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX ar: <http://www.semanticweb.org/v0cn037/ontologies/2024/11/archimate32#>
SELECT ?s ?p ?o
WHERE {
	?s ?p ?o .
	FILTER(?s = ar:Application_Internal_Behavior_Element && ?p != rdf:type && ?p != rdfs:subClassOf && ?p != rdfs:comment)
}
ORDER BY ?o
```

# Filter certain suject and show their definition

```sql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX owl: <http://www.w3.org/2002/07/owl#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX xsd: <http://www.w3.org/2001/XMLSchema#>
PREFIX ar: <http://www.semanticweb.org/v0cn037/ontologies/2024/11/archimate32#>
SELECT ?s ?p ?o
WHERE {
	?s ?p ?o .
	FILTER(regex(str(?s), "Collaboration", "i") && ?p = rdfs:comment)
}
ORDER BY ?o
```