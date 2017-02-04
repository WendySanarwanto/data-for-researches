# data-for-researches
A collection of JSON files, SQL DDL files which are created for supporting current &amp; future demo &amp; sample apps.

## How to import the data into your database
1. Importing `gamingpc.json` file into mongodb: Run `mongoimport --db "api-research" --collection "gamingpc" --type json --file "gamingpc.json" --jsonArray` command  on CLI box.
