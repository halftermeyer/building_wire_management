# building_wire_management

This is a place to store queries and data for a Neo4j QPP + GDS demo about wire management.

You can run [these queries (csv script)](./building_queries.csv) from [neo4j workspace](https://workspace-preview.neo4j.io/).
Just download it and import (⬆) the csv in workspace from the query tab.

You need a running Neo4j 5.9+ with
- corresponding version of GDS installed
- (APOC **extended**)[https://neo4j.com/labs/apoc/5/installation/] to run `apoc.nodes.link`

The ingestion query from the csv script downloads the data from this repo, you don't need to put any file in your `import/` directory but you might need to uncomment this line in your settings:
`dbms.security.allow_csv_import_from_file_urls=true`
