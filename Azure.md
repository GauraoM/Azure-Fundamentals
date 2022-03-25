## 1.Storage Services

### Azure Blob Storage
Object serverless Storage.Store very large and large amounts of unstructured files.Pay for what you store, unlimited storage, no-resizing volumes, filesystem protocols.

### Azure Disk Storage
A virtual volume.Choose SSD/HDD, encryption by default, attach volume to VMs

### Azure File Storage
A Shared volume that  you can access and manage like a file server. If you had multiple virtual machines, multiple servers and you wanted them all share the same hard drive, thats what it use it for.

### *Azure Queue Storage
Messaging Queue A data stored for queuing and reliably delivering messages between applications.This is actually for application Integration.

### Azure Table Storage
Wide-Column NoSQL Database A NoSQL store that hosts unstructured data independent of any schema.

### Azure Data Box/Azure Databox Heavy
This is a rugged briefcase, computer and storage designed to move terabytes or petabytes of data.

### Azure Archive Storage
Long term cold storage for when you need to hold onto files for year on the cheapset storage options.

### Azure Data Lake Storage
A centralized repository that allows you to store all your structured and unstructured data at any scale(big data) from multiple different sources and used to be in one place.

## 2.Database Services 

### Azure Cosmos DB
A fully managed NoSQL databases. Designed for scale with guaranteed of 99.999% availability

### Azure SQL Database
Fully managed MS SQL database with auto-scale, integral intelligence and robust security.

### Azure Database for MySQL/PSQL/ MariaDB
Fully managed and scalable MySQL/PSQL/ MariaDB database with high availability and security.

### SQL Server on VMs
Host enterprise SQL Server apps in the cloud.Lift and shift MS SQL servers from on-premises to Azure Cloud.Easiest way to get onto the cloud

### Azure Synapse Analytics(Azure SQL Data Warehouse)
Fully managed data warehouse with integral security at every level of scale at no extra cost.

### Azure Database Migration Service
Migrates your database to the cloud with no application code changes.

### Azure Cache for Redis
Cache frequently used and static data to reduce data and application latency.

### *Azure Table Storage
Wide Column NoSQL Database A NoSQL store that hosts unstructured data independent of any schema.

## 3.Application Integration Services
Designed to application talk to each other

### Azure Notifications Hub
Pub/Sub Send push notifications to any platform from any back end.

### Azure API Apps
API Gateway Quickly build and consume APIs in the cloud. Route APIs to Azure Services.

### Azure Service Bus
Service Bus Reliable cloud messaging as a service(MaaS) and simple hybrid integration.

### Azure Stream Analytics
Serverless real-time analytics, from the cloud to the edge.

### Azure Logic Apps
Schedule, automate and orchestrate tasks, business processes and workflows. Integration with Enterprise SaaS and Enterprise applications.

### Azure API Management
Hybrid, multi-cloud management platform for APIs across all environments. Put in-front of existing APIs to add additional functionality.

### *Azure Queue Storage
messaging Queue A data store for queuing and reliably delivering messages between applications.

## 4.Developer and Mobile Tools

### Azure SignalR Service
Real-Time Messaging Easily add real-time web functionality to applications. Think of it like the Pusher for Azure.

### Azure App Service
Easy to use for deploying and scaling web-applications with .Net,Node.js Java, Python and PHP.Developer focus on building their web apps, and not worry about the underlying infrastructure. Think of it like Heroku for Azure.

### Visual Studio
Code Editor The integrated development environment(IDE) designed for creating powerful, scalable, applications for Azure

### Xamarin
Mobile-App Framework Create powerful and scalable native mobile apps with .NET and Azure.

## 5.Azure DevOps Services
Plan smarter, collaborate and ship faster with a set of modern dev services.

### Azure Boards
Kanban Deliver value to your users faster using proven agile tools to plan, track and discuss work across your teams.

### Azure Pipelines
Build, test and deploy with CI/CD that works with any language, platform and cloud. Connect to Github or any other Git provider and deploy continuously.

### Azure Repos
Get unlimited, cloud-hosted private Git repos and collaborate to build better code with requests and advanced file management.

### Azure Test Plans
Test and ship with confidence using manual and exploratory testing tools.

### Azure Artifacts
Create, host and share packages with your team, and add artifacts to CI/CD pipelines with single click.

### Azure DevTest Labs
Fast, easy and lean dev-test environments.

## 6.Cloud -Native Networking Services

### Azure DNS
Provide ultra-fast DNS responses and ultra-high domain avilability.S if you have a domain name and you just want it to be managed by Azure, you can associate with Azure DNS.

### Azure Virtual Network(vNET)
A logical isolated section of the Azure network for customers to launch Azure resources within.

### Azure Load Balancer
OSI Level 4(Transport) Load Balancer.

### Azure Application Gateway
OSI Level 7 (HTTP) Load Balancer, can apply a Web Application Firewall. So it does understand like requests coming from a web server.What you acn do with it is you acn actually route based on HB requests to  specific services.

### Network Security Groups
A virtual firewall at the subnet level. Way to protecting the subnets.So, it'sa virtual firewall around your subnets.

## 7.Enterprise/Hybrid Networking Services

### Azure Front Door
Scalable and secure entry point for fast delivery of your global applications such as making sure you have a secure entry point into Azure from outside

### Azure Express Route
A connection between your on-premise to Azure cloud from 50 Mbps to 10 Gbps.

### Virtual WAN
A networking service that brings many networking,security and routing functionalities together to provide single operational interface.

### Azure Connection
A VPN connection securely connects two Azure local network via(IPsec). Its away of connection with Azure.

### Virtual Network Gateway
A site-to-site VPN connection between an Azure virtual network an your local network

## 8.Azure Traffic Manager
Azure Traffic Manager operates at the DNS layer to quickly and efficiently direct incoming DNS requests based on the routing method of your choice.

Route traffic to servers the geographically near by to reduce latency.
Fail-over to redundant systems in-case primary systems become unhealthy.
Route to random VM to simulate A/B testing.

## 9.IoT Services

### IoT Central
Connects your IoT devices to the cloud

### IoT Hub
Enable highly secure and reliable communication between your IoT application and the devices it manage.

### IoT Edge
A fully managed service built on Azure IoT Hub. It allows data processing and analysis nearest the IoT devices.edge computing is when you offload compute from the cloud to local computing hardware such as IoT devices,phones or home computers.

### Windows 10 IoT Core Services
A cloud services subscription that provides the essential services needed to commercialize a device on Windows 10 IoT Core. Long-term OS support and services to manage device updates and assess device health.

## 10.Big Data and Analytics Services
Big data is massive volume of structured/unstructured data that is so large it is difficult ot move and process using traditional databases and software techniques.

### Azure Synapse Analytics(SQL data warehouse)
Enterprise data warehousing and Bid Data analytics.Intended to run SQL queries against large databases for things such as reporting.

### HDInsight
Run open-source analytics software such as Hadoop, Kafka and Spark.

### Azure Databricks
An Apache Spark-base analytics platform optimized for Microsoft Azure cloud services platform. Third-party Databricks cloud services supported within Azure.

### Data Lake Analytics
An on-demand analytics job service that simplifies big data. A data lake is a storage repository that holds a vast amount of raw data in its native format until it is needed.

## 11.AI/ML Services

### Azure Machine Learning Service
A service for that simplifies running AI/ML related workloads allowing you to build flexible pipelines to automate the workflow. USe Python, R, Run DL workloads such as Tensorflow 

### Azure Machine Learning Studio(classic)
An older service manages AI/ML workloads. Doesn't have a pipeline and other limitations.Workloads are not easily transferable to from classic to new service.

### Personalizer
Deliver rich, personalised experience for every user.

### Translator
Add real-time, multi-language text translation to your apps, website and tools.

### Anomaly detector
Detect anomalies in data to quickly identify and troubleshoot issues.

### Azure Bot Service
Intelligent, serverless bot service that scales on demand.

### Form Recogniser
Automate the extraction of the text, key/value pairs and tables from your documents.

### Computer Vision
Easily customise computer vision models for your unique use case.

### Language Understanding
Build natural language understanding into apps, bots and IoT devices.

### QnA Maker
Create a conversational question and answer bot from your existing content.

### Text Analytics  
Extract information such as sentiment, key phrases, named entities and language from your text.

### Face
Face detect and identify people and emotions in images.

### Ink Recogniser
Recognise digital ink content, such as handwriting, shapes, and document layout.

## 12.Serverless Services
When the underlying servers, infrastructure and OS is taken care by the Cloud Service Provider(CSP) it will generally be highly available, scalable and cost-effective.

Event Driven Scales: a serverless function can be triggered or trigger other events allowing you to compose complex applications and its just scales.

Abstraction of Servers: Servers are abstracted away. Your code is described as functions. These functions can be running on different compute instances.

### Azure Functions
Run small amounts of code known as serverless functions in your favorite language: C#, java, JavaScript, Python and PowerShell.

### Blog Storage
Serverless Object Storage. Just upload files, don't think about the underlying file-systems, resizing.

### Logic Apps
Allows you to build serverless workflows composed of Azure Functions. Building a state machines for serverless compute.

### Event Grid
Uses Pub/Sub messaging sysyem to allow you react to events and trigger other Azure cloud services such as Azure Functions.

