# Reading Notes 3


## Read and Write Files

* A file is a contiguous set of bytes used to store data.

### 3 parts to a file

#### Header

* contains information about the file like name, type, size, etc...

#### Data

* contains the actual contents of the file as written by the creator.

#### EOF (End of File)

* special charachter which indicates the end of the file.

### Opening and Closing files

* open with the open() function.

* always make sure files are closed after using.

* close with close() function.

* To make sure the file closes even through an error use "with" statement

## Errors and Exceptions