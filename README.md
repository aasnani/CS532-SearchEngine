# Project 1 - Systems for Data Science



## Requirements:
* Java 1.8 (IntelliJ)
* Maven (Enable Auto-Import of Maven projects)
  * org.apache.spark:spark-core_2.10:2.1.0
  * org.rocksdb:rocksdbjni:5.15.10
  * org.apache.hadoop:hadoop-common:3.1.1
* Apache Spark
* Apache Hadoop

## Included in Project:
* All source files
* Id_Urls.txt - File containing document ID and associated URL 
* Web Page Document Files - inside the projectdata folder 


## To Run:
* Open Project in IntelliJ 
* Enable Auto-Import from Maven, when prompt appears in bottom right corner. 
* Run class titled InvertedIndex. All code is stored in this class file. 
* Send any HTTP request method to: localhost:8843/search with space separated search terms (in the body in raw format, if using Postman to send request)

## Text processing done for the assignment:
* All text from document files is converted to lowercase and separated into individual tokens by whitespace only. Punctuation was not removed or separated. (ex. diatetes and obesity,) 
* Queries received from client are also converted to lower case before returning search results, this is done to match the lowercase text tokens.
* All duplicate URLs are removed from search results. 


## Testing:
We tested this search engine using Postman. 

Example result for query term obesity, diabetes: [Query Example](https://ibb.co/rMTNxMs)


## Authors:
Armand Asnani
Paige Calisi
