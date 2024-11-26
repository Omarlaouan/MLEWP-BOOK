# Chapter 05 : Deployment patters and tools  

### Tools
- Airflow = Orchestration of any python process. 
Alternative : 
    - ZenML
    - Kubeflow
### Architecting the sytem : principles
- Separation : Separate layers with distinct respnsabilities
- Principle of Least Surprise : Keep things clear and simple
- Principle of Least Effort : Your solution should be easy to use, for a long time. 
- SOLID : single resonsability, Open(for extension)/closed(for modification), Liskov subs, Interface segregation (don’t have multiple ways for components
to talk to one another), Dependency inverson

### Data warehouses VS Data lakes 
- Warehouses : dont scale well, only structured data
- Lakes : scale well, all type of data

### Micro services 
- Easier maintenance of parts (instead of the whole)
- Avoid a single point of failure.
- Increase maintainability and scalability. 
- Allow separate services to be owned by distinct teams with clearer responsibilities.
- Accelerate the development of complex products.

### Event-based design 
