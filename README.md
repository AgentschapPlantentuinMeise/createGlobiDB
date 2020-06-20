# createGlobiDB
 To create an local SQLite database from GloBI

This script takes the file interactions.tsv downloaded from https://www.globalbioticinteractions.org/data.html
It then creates a SQLite database from it and adds a number of useful indexes.

Currently the interactions.tsv is about 9GB and the SQLite database created is 16GB. This script takes some time to run and requires plenty of memory.
