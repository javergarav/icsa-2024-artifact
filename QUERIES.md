# QUERIES

## Query #1

Return the complete graph:

    MATCH (n)-[r]-()
    RETURN n, r

## Query #2

View information about the node that represents the weakness *Improper Authentication*:

    MATCH (n:weakness {name: 'Improper Authentication'}) RETURN n

## Query #3

Subgraph associated with the implementation details of the *Authenticator* architectural pattern:

    MATCH subgraph = (:architectural_pattern {name:'Authenticator'})-[:Involves|RequestAuthentication|Verifies|Creates*]-(n) RETURN subgraph

## Query #4

Subgraph associated with the REST architectural element, in terms of its possible weaknesses and countermeasures:

    MATCH subgraph = (a:detailed {short_name: 'REST'})-[:MayHave|CanAffect|IsRelatedTo|CanBeMitigatedBy|CanBeImplementedBy*]-(b) RETURN subgraph;