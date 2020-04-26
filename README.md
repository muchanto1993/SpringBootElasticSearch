# SpringBootElasticSearch
 Spring Boot Elastic Search

Source :
 * https://www.elastic.co/
 * https://javadeveloperzone.com/spring-boot/spring-boot-elastic-search-example/

# Tutorial
1. Download Elastic Search From This Link https://www.elastic.co/downloads/elasticsearch
2. unzip Elasticsearch
3. Run bin/elasticsearch (or bin\elasticsearch.bat on Windows)
4. Running The Solution 

# Example
If you success running elastic search you can look the result like this
{
  "name" : "Muhammads-MBP",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "mz8l2a1NQruGBBZbnBxVyw",
  "version" : {
    "number" : "7.6.2",
    "build_flavor" : "default",
    "build_type" : "tar",
    "build_hash" : "ef48eb35cf30adf4db14086e8aabd07ef6fb113f",
    "build_date" : "2020-03-26T06:34:37.794943Z",
    "build_snapshot" : false,
    "lucene_version" : "8.4.0",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}

After that you can import file Spring Boot Elastic Search Example.postman_collection.json to Postman
and you can try access http://localhost:8082/save for inital data and http://localhost:8082/getAll for look the result
