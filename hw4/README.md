# Homework 4 Problem 2 Test Cases
Either download the tar.gz or the raw txt files and put them in your working directory.
There are 3 index files that you can ready from with varying sizes. Make sure your
executable is in root and not in the stress folder.

|page name|word count|
|---|---|
|lorem.txt|5k|
|dictionary.txt|500k|
|definitions.txt|2m|

`time ./search stress/index_easy.txt stress/query.txt stress/output.txt`  
`time ./search stress/index_medium.txt stress/query.txt stress/output.txt`  
`time ./search stress/index_hard.txt stress/query.txt stress/output.txt`  
