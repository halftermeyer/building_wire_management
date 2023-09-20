# building_wire_management

This is a place to store queries and data for a Neo4j QPP + GDS demo about wire management.

You can run [these queries](./building_queries.csv) from [neo4j workspace](https://workspace-preview.neo4j.io/).
You need a running Neo4j 5.9+ running with
- corresponding version of GDS installed
- (APOC **extended**)[https://neo4j.com/labs/apoc/5/installation/] to run `apoc.nodes.link`

The ingestion query downloads the data from this repo, you might need to uncomment this linein your settings:
`dbms.security.allow_csv_import_from_file_urls=true`
