# Jaeger Tracking Monitor Services
Example Jeager Tracking to monitor services in Microservices architects

"In microservice architecture, traditional monolithic applications are broken down into components that can be deployed independently. An application gradually becomes a group of microservices. When you have hundreds or thousands of small microservices working together, it will not be easy for you to understand which services are calling each other, and which service a request is going from. Which service?"

"To solve this problem, a technique is introduced called Distributed Tracing. Distributed Tracing is a method to profile and monitor applications, especially applications that use microservices architecture. It helps determine exactly which service is failing and what is affecting the application's performance."

## Deploy on Docker Swarm

The Jaeger Tracing backend includes 3 main components:
- Jaeger Agent
- Jaeger Collector: Collector will collect from Agent and save to DB (Here we use Elasticsearch, and Jaeger only supports using Elasticsearch ver 6.x)
- Jaeger Query/UI

Main config file: ``docker-compose.yml``

Configuration file for Elasticsearch is ``config/elasticsearch.yml``

### Jaeger Collector

### Jaeger Agent

### Jaeger Query
