# ELK Stack with Filebeat

This project sets up the ELK stack (Elasticsearch, Logstash, Kibana) along with Filebeat using Docker Compose.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone the repository
2. Navigate to the project directory
3. Create a `.env` file with the desired Elasticsearch version
4. Run `docker-compose up -d`

## Configuration

### Elasticsearch
- Configuration file: `elasticsearch/config/elasticsearch.yml`

### Kibana
- Configuration file: `kibana/config/kibana.yml`

### Logstash
- Configuration file: `logstash/config/logstash.yml`
- Pipeline configuration: `logstash/pipeline/logstash.conf`

### Filebeat
- Configuration file: `filebeat/config/filebeat.yml`

## Access

- Elasticsearch: [http://localhost:9200](http://localhost:9200)
- Kibana: [http://localhost:5601](http://localhost:5601)
