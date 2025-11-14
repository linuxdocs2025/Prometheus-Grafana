# Install Prometheus and Grafana on Ubuntu

### What is Prometheus ?
- Prometheus is a open source Linux Server Monitoring tool mainly used for metrics monitoring, event monitoring, alert management, etc.
- Prometheus has changed the way of monitoring systems and that is why it has become the Top-Level project of Cloud Native Computing Foundation (CNCF).
- Prometheus uses a powerful query language i.e. “PromQL”.
- In Prometheus tabs are on and handles hundreds of services and microservices.
- Prometheus use multiple modes used for graphing and dashboarding support.

## Prometheus Components
1. Prometheus Server
   - Prometheus server is a first component of Prometheus architecture.
   - Prometheus server is a core of Prometheus architecture which is divided into several parts like Storage, PromQL, HTTP server, etc.
   - In Prometheus server data is scraped from the target nodes and then stored int the database.

1.a. Storage
 - Storage in Prometheus server has a local on disk storge.
 - Prometheus has many interfaces that allow integrating with remote storage systems.

1.b. PromQL
 - Prometheus uses its own query language i.e. PromQL which is very powerful querying language.
 - PromQL allows the user to select and aggregate the data.

2. Service Discovery
 - Next and very important component of Prometheus Server is the Service Discovery.
 - With the help of Service discovery the services are identified which are need to scraped.
 - To Pull metrics, identification of services and finding the targets are compulsory needed.
 - Through Service discovery we monitor the entities and can also locate its targets.

3. Scrape Target
 - Once the services are identified and the targets are ready then we can pull metrics from it and can scrape the target.
 - We can export the data of end point using node exporters.
 - Once the metrics or other data is pulled, Prometheus stores it in a local storage.

4. Alert Manager
 - Alert Manager handles the alerts which may occurs during the session.
 - Alert manager handles all the alerts which are sent by Prometheus server.
 - Alert manager is one of the very useful component of Prometheus tool.
 - If in case any big error or any issue occurs, alert manager manage those alerts and contact with human via E-mail, Text Messages, On-call, or any other chat application service.

5. User Interface
 - User interface is also a important component as it builds a bridge between the user and the system.
 - In Prometheus, user interface are note that much user friendly and can be used till graph queries.
 - For good exclusive dashboards Prometheus works together with Grafana (visualization tool).
 - Using Grafana over Prometheus to visualize properly we can use custom dashboards.
 - Grafana dashboards displays via pie charts, line charts, tables, good data graphs of CPU usage, RAM utilization, network load, etc with indicators.
 - Grafana supports and run with Prometheus by querying language i.e. PromQL.
 - To fetch data from Prometheus and to display the results on Grafana dashboards PromQL is used.

---
### What is Grafana ?





























































































































































