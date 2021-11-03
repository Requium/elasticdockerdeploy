# elasticdockerdeploy
ElasticSearch Containers for Fast deploying
File to create a fast deployment ready to test elasticsearch

Stack Description:

1 Node of Elasticsearch (have to tweak some things for sharding and replications so i dont get yellow healtchecks on index)
1 Node of KIBANA
1 Node of Fleet

The stack is create based on a 16G RAM requirement, if you need less change it to 8G
