
## default config

input { stdin { } }
output {
  elasticsearch { hosts => ["localhost:9200"] }
  stdout { codec => rubydebug }
}


sending msg using java
https://github.com/apache/kafka/tree/trunk/clients/src/main/java/org/apache/kafka/clients/producer
