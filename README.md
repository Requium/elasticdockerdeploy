# elasticdockerdeploy
ElasticSearch Containers for Fast deploying
File to create a fast deployment ready to test elasticsearch

Stack Description:

1 Node of Elasticsearch (have to tweak some things for sharding and replications so i dont get yellow healtchecks on index)
1 Node of KIBANA

The file needs 2 ENV VAR for USERNAME AND PASSWORD so it can create the username and password for the elasticsearch node
