# CSV Filtering Task

## Objective
Read a CSV file, filter specific rows, and write the result to a new file.

## Instructions
1.  Read the input file located at `/app/input.csv`.
2.  The file contains the following columns: `id`, `name`, `role`, `department`.
3.  Filter the data to include ONLY rows where the `role` is exactly `Engineer`.
4.  Write the filtered data to a new CSV file at `/app/output.csv`.
5.  Ensure the output file includes the header row.

## Input Example (/app/input.csv)
```csv
id,name,role,department
1,Alice,Engineer,Engineering
2,Bob,Manager,Sales
```

## Expected Output Example (/app/output.csv)
```csv
id,name,role,department
1,Alice,Engineer,Engineering
```
