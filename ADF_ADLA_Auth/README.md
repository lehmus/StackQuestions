# Data Factory authentication to Data Lake

This repository contains all the necessary resources for reproducing the
ADF authorization issue with Data Lake.

[Stack Overflow: ACL verification fails for Data Factory Service Principal, although it has rwx permissions](https://stackoverflow.com/questions/51421000/acl-verification-fails-for-data-factory-service-principal-although-it-has-rwx-p)

## Contents

### Directory: [**adf**](./adf/)

Azure Data Factory templates for reproducing the environment.

### Directory: [**data**](./data/)

Input data which is inserted to the Data Lake table.
Data is in CSV format.

### File: [**Script.UpdateFile.usql**](./Script.UpdateFile.usql)

U-SQL script for inserting data to CSV file.
For example input, see the files in the directory: *data*.
