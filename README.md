# Portfolio-project-3
*ELK Setup, this Project primarily focus on how to monitor the server,services and application using elasticsearch,logstash and kibana*

**What is ELK?**
  ELK is an acronym for 3 open source projects:Elastic search , Logstash and Kibana.
  
**Elasticsearch:** 
  Elastic search is a distributed serach and analytics engine.
  
**Logstash:** 
  Logstash is an open-source data ingestion tool that allows you to  collect data from various sources, transform it, and send it to your desired destination.
  
**Kibana:**
Kibana is a data visualization tool that provides search capabilities for data indexed in Elasticsearch.

**Filebeat:**
Filebeat is a lightweight shipper for forwarding and centralizing log data. Installed as an agent on your servers, Filebeat monitors the log files or locations that you specify, collects log events, and forwards them either to Logstash.

***Why to index the data in elastic search?***
Indexing is essential in Elasticsearch to ensure fast, efficient, and flexible data retrieval.

***What is the default port of these services?***
Default port of logstash: 5044
Default port of elasticsearch: 9200
Default port of kibana: 5601

**REQUIREMENTS:** 


Server1:
  *We install Elasticsearch , Logstash , Kibana and filebeat service. And instance type should be a minimum of m4.large and storage of 20 GB.*

  
Server2:
  *We need to just install filebeat.*

Step 1: Install ELK

Step 2: Install file beat on server1 to collect logs

Step 3: Configure logstash to collect the logs from filebeat

Step 4: Configure Kibana gui to view server 1's logs

Step 5: Create a python flask application and generate application logs in server2

Step 6: Enable connectivity between server1 and server2 to send and receive logs

Step 7: Install filebeat on server2 and configure it to send its logs to Servers 1's logstash

Step 8: Update the config file of logstash and filebeat in server1 to differentiate the logs being collected from both these servers by filebeat

Step 9: Configure kibana gui to view the logs generated by server2 aswell
  
