# SDM project


By default, Neo4j doesn't allow loading data from file URLs. And if allowed it reads files from the import directory only.

If you want to load files from other directories, you have to allow that in **neo4j.conf**


1. Go to terminal from Neo4j WebInterface
2. Comment this line(By adding # in the start):
```
dbms.directories.import=import
```