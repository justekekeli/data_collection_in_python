# DATA PROCESSING IN PYTHON WITH PANDAS LIBRARY

## Data sources : 
Data from with Duke University data engineering course  
\#duke-data-engineering
Link to the data : https://github.com/alfredodeza/mapping-data/tree/main/sample_data

## PHASE 1 : DATA COLLECTION 
I collect data about wine (name,ratings, notes (as description), wine type from the json file and the CSV files and I merged them in pandas dataframe
## PHASE 2 : DATA PREPARATION

1. Deletion of non-necessary columns
2. Decomposition of the multi-valued column 'name' into 'name' and 'year'
3. Deletion of columns with no name
4. Deletion duplicates records
5. Deletion of the records with the same name and the same year since they are the same
6. Renaming notes into description

### PHASE 3 : DATA INGESTION IN AZURE SQL DATABASE

