# AZ-900 Microsoft Azure Fundamentals Notes

<p align="center">
  <img width="128" height="128" src="./Assets/microsoft-certified-fundamentals-badge.svg">
</p>

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6;">
AZ-900 Microsoft Azure Fundamentals certification is the first and the most important certification for anyone who is just starting with Azure.
</div>

Path Overview

![AZ-900 Overview](./Assets/path.png)

## Module 1

🔷**Describe cloud concepts (15-20%)**

![alt text](./Assets/path-1.png)

### Cloud Computing, High Availability, Scalability, Elasticity, Agility, Fault Tolerance, and Disaster Recovery

#### Cloud Computing

Service delivery model over the internet (cloud). This includes but is not limited to:

![compute](./Assets/compute.png)

- **Compute Power** meaning servers such as windows, linux, hosting environments, etc.

![compute](./Assets/storage.png)

- **Storage** like files and/or databases

![compute](./Assets/networking.png)

- **Networking** in azure but also outside when connecting to your company network

![compute](./Assets/analytics.png)

- **Analytics services** for visualization and telemetry data

#### Cloud Key concepts

![alt text](./Assets/scalability.png)

- **Scalability** - the ability to scale, so allocate and deallocate resources at any time

![alt text](./Assets/elasticity.png)

- **Elasticity** - the ability to scale dynamically

![alt text](./Assets/agility.png)

- **Agility** - the ability to react fast (scale quickly)

![alt text](./Assets/fault_tolerance.png)

- **Fault Tolerance** - the ability to maintain system uptime while physical and service component failures happen

![alt text](./Assets/disaster_recovery.png)

- **Disaster Recovery** - the process and design principle which allows a system to recovers from natural or human induced disasters

![alt text](./Assets/high_availability.png)

- **High Availability** - the agreed level of operational uptime for the system. It is a simple calculation of system uptime versus whole lifetime of the system.

  - **Availability** = uptime/(uptime + downtime)

##### SUMMARY

![alt text](./Assets/image-4.png)
![alt text](./Assets/image.png)
![alt text](./Assets/image-3.png)
![alt text](./Assets/image-1.png)
![alt text](./Assets/image-2.png)

### Principles of economies of scale

#### Economies of Scale

![alt text](./Assets/economies_of_scale-1.png)

The principle of economies of scale states that as the companies grow they become more effective at managing shared operations. Be that HR and hiring, taxes, accounting, internal operations, marketing, big purchases via contracts meaning better discounts, etc. etc.

Because of those, companies can save/earn more which in return allows for reduction in cost of their services to their customers. This is so called ‘price per unit’.

![alt text](./Assets/price-per-unit.png)

It’s not possible to go to 0 because in the end some underlying infrastructure needs to run to provide the services. But the larger the scale the more benefits can be passed to customers.

In fact, in the current scale, Microsoft can already offer multiple services for free due to how small a fraction of the cost it is for them.

### Capital Expenditure (CapEx) vs Operational Expenditure (OpEx) and their differences

#### CapEx vs OpEx

Differences between Capital Expenditure and Operational Expenditure

![alt text](./Assets/CapEx_vs_OpEx.png)

|                   | Capital Expenditure | Operational Expenditure |
| ----------------- | ------------------- | ----------------------- |
| Up front cost     | Significant         | None                    |
| Ongoing cost      | Low                 | Based on usage          |
| Tax Deduction     | Over time           | Same year               |
| Early Termination | No                  | Anytime                 |
| Maintenance       | Significant         | Low                     |
| Value over time   | Lowers              | No change               |

### Consumption-based model

#### What is a consumption-based model?

The consumption-based model is a pricing model used in the cloud so that customers are only charged based on their resource usage.

![alt text](./Assets/consumption-based_model.png)

This model is characterized by:

- **No associated upfront cost**
- **No wasted resources** as such no charges are incurred for unused resources\*. Unused in this case is different per service. For instance, blob storage that stores any data is considered to be used, as it consumes the storage space. Virtual Machines that are running consume CPU, memory and other resources even if there isn’t any traffic. Hence they are considered to be used and will incur charges.
- **Pay for what you need**
- **Stop paying when you don’t**

![alt text](./Assets/consumption-based_example.png)

**Consumption** is the virtual metric used to calculate how much each resource (service) in Azure was used. Each service has many smaller metrics that track its consumption to offer best possible pricing model. Those metrics are tracked on very granular level.

### IaaS, PaaS, SaaS and their differences

#### Service Models responsibilities

As a service means which party will manage the particular layer and all the layers below.

- Software layer consists the application (application code and set) & the application data
- Platform layer means all the supporting software and the operating system required to host the application
- Infrastructure layer consists hardware the infrastructure and virtualization required to host the platform

| Layer            | Layer          |
| ---------------- | -------------- |
| Application      | Software       |
| Data             | Software       |
| Runtime          | Platform       |
| Middleware       | Platform       |
| Operating System | Platform       |
| Virtualization   | Infrastructure |
| Servers          | Infrastructure |
| Networking       | Infrastructure |
| Storage          | Infrastructure |

#### Responsibility Matrix

##### On-Premises

![alt text](./Assets/on-premise.png)

##### IaaS

![alt text](./Assets/iaas.png)

##### PaaS

![alt text](./Assets/paas.png)

##### SaaS

![alt text](./Assets/saas.png)

As such following table represents responsibilities
| Layer | On-Premises | IaaS | PaaS | SaaS |
| --- | --- | --- | --- | --- |
| Application | You | You | You | Cloud provider |
| Data | You | You | You | Cloud provider |
| Runtime | You | You | Cloud provider | Cloud provider |
| Middleware | You | You | Cloud provider | Cloud provider |
| Operating System | You | You | Cloud provider | Cloud provider |
| Virtualization | You | Cloud provider | Cloud provider | Cloud provider |
| Servers | You | Cloud provider | Cloud provider | Cloud provider |
| Networking | You | Cloud provider | Cloud provider | Cloud provider |
| Storage | You | Cloud provider | Cloud provider | Cloud provider |

##### Summary

![alt text](./Assets/cloud_model_summary.png)

### Episode 6: Public, Private, Hybrid cloud and their differences

#### Cloud Deployment Model

**Cloud Deployment Model** is simple a separation which describes where are the company resources deployed. Whenever this is in public cloud provider environment or private datacenter.

Below table presents high level deployment model separation

| Layer   | Cloud Provider | Own Datacenter |
| ------- | -------------- | -------------- |
| Public  | ✅             | ✖              |
| Hybrid  | ✅             | ✅             |
| Private | ✖              | ✅             |

#### Public Cloud

![alt text](./Assets/public_cloud.png)

| Cloud Provider | Own Datacenter |
| -------------- | -------------- |
| ✅             | ✖              |

##### Key Characteristics

Everything runs on cloud provider hardware
No local hardware
Some services share hardware with other customers

##### Advantages

- No CapEx (No initial investment)
- High Availability
- Agility
- Pay as you Go (PAYG) pricing
- No hardware maintenance
- No deep technical skills required

##### Disadvantages

- Not all security and compliance policies can be met
- No ownership over the physical infrastructure
- Rare specific scenarios can’t be done

#### Private Cloud

![alt text](./Assets/private_cloud.png)

| Cloud Provider | Own Datacenter |
| -------------- | -------------- |
| ✖              | ✅             |

##### Key Characteristics

- Everything runs on your own datacenter
- Self-service should be provided
- You maintain the hardware

##### Advantages

- Can support any scenario
- Total control over security and infrastructure
- Can meet any security and compliance policy

##### Disadvantages

- Initial investment is required (CapEx)
- Limited agility constrained by server capacity and team skills
- Very dependent on IT skills & expertise

#### Hybrid Cloud

![alt text](./Assets/hybrid_cloud.png)

| Cloud Provider | Own Datacenter |
| -------------- | -------------- |
| ✅             | ✅             |

##### Key Characteristic

- Combines both Public & Private cloud

##### Advantages

- Great flexibility
- You can run any legacy apps in private cloud
- Can utilize existing infrastructure
- Meet any security& compliance requirements
- Can take advantage of all public cloud benefits

##### Disadvantages

- Can be more expensive
- Complicated to manage due to larger landscape
- Most dependent on IT skills & expertise from all three models

## Module 2

🔷 Describe core Azure services (30-35%)

![alt text](./Assets/path-2.png)

Describe the core Azure architectural components

### Episode 7: Azure Regions and Availability Zones

#### Data Center

![alt text](./Assets/data_center.png)

- **Physical facility**
- **Hosting for** group of networked servers
- Own **power, cooling & networking** infrastructure

#### Regions

![alt text](./Assets/regions.png)

- **Geographical area** on the planet
- **One but usually more datacenters** connected with **low-latency network** (<2 milliseconds)
- **Location** for your services
- Some services are **available only in certain regions**
- Some services are **global services**, as such are not assigned/deployed in specific region
- Globally available with **50+ regions**
- Special **government regions** (US DoD Central, US Gov Virginia, etc.)
- Special **partnered regions** (China East, China North)

![alt text](./Assets/globabl_regions.png)

#### Availability Zone

![alt text](./Assets/availablitiy_zones.png)

- **Regional feature**
- Grouping of **physically separate** facilities (multiple datacenters)

  ![alt text](./Assets/multiple_datacenters.png)

- Designed to **protect from data center failures**
- If zone goes down **others continue working**
- Two service **categories**

  - **Zonal** services (Virtual Machines, Disks, etc.)
  - **Zone-redundant** services (SQL, Storage, etc.)

  ![alt text](./Assets/zone_redundant.png)

- **Not all** regions are **supported**
- **Supported** region has **three or more zones**
- A **zone** is **one or more data centers**

#### Region Pair

![alt text](./Assets/region_pair.png)

- **Each region** is **paired** with another region making it a region pair
- Region **pairs are static** and cannot be chosen
- Each pair resides within the **same geography**\*
  - Exception is Brazil South
- **Physical isolation** with at least 300 miles distance (when possible)
- Some services have **platform-provided replication**
- **Planned updates** across the pairs
- **Data residency** maintained for disaster recovery

| Region Pair A          | Region Pair B              |
| ---------------------- | -------------------------- |
| East US                | West US                    |
| UK West                | UK South                   |
| North Europe (Ireland) | West Europe (Netherlands)  |
| East Asia (Hong Kong)  | Southeast Asia (Singapore) |

#### Geographies

![alt text](./Assets/geographies.png)

- **Discrete market**
- Typically **contains two or more regions**
- Ensures **data residency, sovereignty, resiliency, and compliance** requirements are met
- **Fault tolerant** to protect from region wide failures
- Broken up into areas
  - **Americas**,
  - **Europe**,
  - **Asia Pacific**,
  - **Middle East** and **Africa**
- Each **region belongs only to one Geography**

### Episode 8: Azure Resource Groups and Resource Manager

![alt text](./Assets/azure_resources.png)

#### Azure Resource

- Object **used to manage services** in Azure
- Represents **service lifecycle**
- Saved as **JSON definition**

![alt text](./Assets/json_azure.png)

#### Resource Groups

![alt text](./Assets/resource_group.png)

- **Grouping** of resources
- Holds **logically related** resources
- Typically organizing by

  - **Type**

  ![alt text](./Assets/resource_group_type.png)

  - **Lifecycle** (app, environment)

  ![alt text](./Assets/resource_group_lifecycle.png)

  - **Department**
  - **Billing**,
  - **Location** or
  - **combination** of those

#### Resource Manager

- **Management Layer** for all resources and resource groups
- **Unified** language
- **Controls access** and **resources**

![alt text](./Assets/azure_resource_manager.png)

#### Additional Info

- Each **resource must** be in one, and **only one resource group**
- Resource **groups have their own location** assigned
- Resources in the resource groups can **reside in a different locations**
- Resources **can be moved** between the resource groups
- Resource **groups can’t be nested**
- Organize based on your organization needs but consider
  - Billing
  - Security and access management
  - Application Lifecycle

### Episode 9: Azure Compute Services | Virtual Machine, VM Scale Set, App Service, Functions, Container ### Instances, Kubernetes Service

NOTE: [Watch this video first!](https://youtu.be/eyNBf1sqdBQ?si=LYm7f1gbLYLXa1oK)

#### Virtualization

![alt text](./Assets/virtualization.png)

- Emulation of physical machines
- Different virtual hardware configuration per machine/app
- Different operating systems per machine/app
- Total separation of environments
  - file systems,
  - services,
  - ports,
  - middleware,
  - configuration

#### Virtual Machines

![alt text](./Assets/azure_virtual_machines.png)

- Infrastructure as a Service (IaaS)
- Total control over the operating system and the software
- Supports marketplace and custom images
- Best suited for
  - Custom software requiring custom system configuration
  - Lift-and-shift scenarios
- Can run any application/scenario
  - web apps & web services,
  - databases,
  - desktop applications,
  - jumpboxes,
  - gateways, etc.

#### Virtual Machine Scale Sets

- Infrastructure as a Service (IaaS)
- Set of identical virtual machines
- Built-in auto scaling features
- Designed for manual and auto-scaled workloads like web services,\* batch processing, etc.

#### Containers

![alt text](./Assets/containers_vs_vms.png)

- Use host’s operating system
- Emulate operating system (VMs emulate hardware)
- Lightweight (no O/S)
  - Development Effort
  - Maintenance
  - Compute & storage requirements
- Respond quicker to demand changes
- Designed for almost any scenario

#### Azure Container Instances

![alt text](./Assets/azure_container_instance.png)

- Simplest and fastest way to run a container in Azure
- Platform as a Service
- Serverless Containers
- Designed for
  - Small and simple web apps/services
  - Background jobs
  - Scheduled scripts

#### Azure Kubernetes Service (AKS)

![alt text](./Assets/azure_kubernetes_services.png)

- Open-source container orchestration platform
- Platform as a Service
- Highly scalable and customizable
- Designed for high scale container deployments (anything really!)

#### App Service

![alt text](./Assets/app_service.png)

- Designed as enterprise grade web application service
- Platform as a Service
- Supports multiple programming languages and containers

#### Azure Functions (Function Apps)

- Platform as a Service
- Serverless
- Two hosting/pricing models
  - Consumption-based plan
  - Dedicated plan
- Designed for micro/nano-services

![alt text](./Assets/azure_functions_summary.png)

#### Azure Compute Services Summary

- **Virtual Machines (IaaS)** - Custom software, custom requirements, very specialized, high degree of control
- **VM Scale Sets (IaaS)** - Auto-scaled workloads for VMs
- **Container Instances (PaaS)** - Simple container hosting, easy to start
- **Kubernetes Service (PaaS)** - Highly scalable and customizable \* container hosting platform
- **App Services (PaaS)** - Web applications, a lot of enterprise web \* hosting features, easy to start
- **Functions (PaaS) (Function as a Service) (Serverless)** - micro/nano-services, excellent consumption-based pricing, easy to start

![alt text](./Assets/compute_services_summary.png)

### Episode 10: Azure Networking Services | Virtual Network, Load Balancer, VPN Gateway, Application ## #Gateway, CDN

#### Azure Networking

- Connect cloud and on-premises
- On-premise networking functionality

#### Azure Virtual Network

- Logically isolated networking components
- Segmented into one or more subnets
- Subnets are discrete sections
- Enable communication of resources with each-other, internet and on-premises
- Scoped to a single region
- VNet peering allow cross region communication
- Isolation, Segmentation, Communication, Filtering, Routing

![alt text](./Assets/azure_virtual_network.png)

![alt text](./Assets/network_security_group.png)

#### Azure Load Balancer

- Even traffic distribution
- Supports both inbound and outbound scenarios
- High-availability scenarios
- Both TCP (transmission control protocol) and UDP (user datagram protocol) applications
- Internal and External traffic
- Port Forwarding
- High scale with up to millions of flows

![alt text](./Assets/azure_load_balancer.png)

![alt text](./Assets/azure_load_balancer_segmented.png)

#### VPN Gateway

- Specific type of virtual network gateway for on-premises to azure traffic over the public internet

![alt text](./Assets/azure_vpn_gateway.png)

#### Application Gateway

- Web traffic load balancer
- Web application firewall
- Redirection
- Session affinity
- URL Routing
- SSL termination

![alt text](./Assets/azure_application_gateway.png)

#### Content Delivery Network

- Define content
- Minimize latency
- POP (points of presence) with many locations

![alt text](./Assets/content_delivery_network.png)

#### Networking Summary

- **Azure Virtual Network** - Emulation/representation of physical networking in the cloud, grouping, filtering and segmentation of network related resources
- **Azure VPN Gateway** - Connecting On-Premises with the Vitural Network and Virtual Networks with each other (remember about VNet Peering)
- **Azure Load Balancer** - Even traffic distribution for non-HTTP (non-web) traffic
- **Azure Application Gateway** - Even traffic distribution for HTTP (web) traffic
- **Azure Content Delivery** Network (CDN) - Global content caching & distribution to offload web applications and reduce latency

### Episode 11: Azure Storage Services | Blob, Disk, File and Archive

#### Data Types

- **Structured** - Data that can be represented using tables with very strict schema. Each row must follow defined schema. Some tables have defined relationships between them. Typically used in relational databases.
- **Semi-structured** - Data that can be represented using tables but without strict defined schema. Rows must only have unique key identifier.
- **Unstructured** - Any files in any format. Like binary files, application files, images, movies, etc.

![alt text](./Assets/data_types.png)

#### Storage Account

- Group of services which include
  - blob storage,
  - queue storage,
  - table storage, and
  - file storage
- Used to store
  - files,
  - messages, and
  - semi-structured data
- Highly scalable (up to petabytes of data)
- Highly durable (99.999999999% - 11 nines, up to 16 nines)
- Cheapest per GB storage

![alt text](./Assets/azure_storage_account.png)

#### Blob Storage

- BLOB – binary large object – file
- Designed for storage of files of any kind
- Three storage tiers
  - Hot – frequently accessed data
  - Cool – infrequently accessed data (lower availability, high durability)
  - Archive – rarely (if-ever) accessed data

![alt text](./Assets/blob_storage.png)

#### Queue Storage

- Storage for small pieces of data (messages)
- Designed for scalable asynchronous processing

![alt text](./Assets/queue_storage.png)

#### Table Storage

- Storage for semi-structured data (NoSQL)
  - No need for foreign joins, foreign keys, relationships or strict schema
  - Designed for fast access
- Many programming interfaces and SDKs

![alt text](./Assets/azure_table_storage.png)

#### File Storage

- Storage for files accessed via shared drive protocols
- Designed to extend on-premise file shares or implement lift-and-shift scenarios
- Similar to BLOB but are files transferred using SMB
  - They are both file storage services but BLOB has TONS and TONS of features for programming applications which need file storage capability whereas File Storage service is very simple and its only purpose is Share Drive connectivity. As such for 95%+ of cases use BLOB.

![alt text](./Assets/azure_file_storage.png)

#### Disk Storage

- Disk emulation in the cloud
- Persistent storage for Virtual Machines
- Different
  - sizes,
  - types (SSD, HDD)
  - performance tiers
- Disk can be unmanaged or managed

### Episode 12: Database Services | Cosmos DB, SQL Database, SQL DB for MySQL and PostgreSQL, SQL Managed ### Instance

#### Data Types - Once more

- **Structured** - Data that can be represented using tables with very strict schema. Each row must follow defined schema. Some tables have defined relationships between them. Typically used in relational databases.
- **Semi-structured** - Data that can be represented using tables but without strict defined schema. Rows must only have unique key identifier.
- **Unstructured** - Any files in any format. Like binary files, application files, images, movies, etc.

#### Cosmos DB

- Globally distributed NoSQL (semi-structured data) Database service
- Schema-less
- Multiple APIs (SQL, MongoDB, Cassandra, Gremlin, Table Storage)
- Designed for

  - Highly responsive (real time) applications with super low latency responses <10ms
  - Multi-regional applications

  ![alt text](./Assets/cosmos_db.png)

#### Azure SQL Database

- **Relational database** service in the cloud (PaaS) (DBaaS - Database as a Service)
- **Structured data** service defined using schema and relationships
- **Rich Query Capabilities** (SQL)
- **High-performance**, reliable, fully managed and secure database for building - applications

![alt text](./Assets/azure_sql_db.png)

![alt text](./Assets/sql_server_services.png)

#### Azure SQL product family

- Azure **SQL Database** – Reliable relational database based on SQL Server
- Azure **Database for MySQL** – Azure SQL version for MySQL database engine
- Azure **Database for PostgreSQL** – Azure SQL version for PostgreSQL database engine
- Azure **SQL Managed Instance** – Fully fledged SQL Server managed by cloud provider
- Azure **SQL on VM** – Fully fledged SQL Server on IaaS
- Azure **SQL DW (Synapse)** – Massively Parallel Processing (MPP) version of SQL Server

![alt text](./Assets/azure_sql_product_family.png)

### Episode 13: Azure Marketplace

Describe some of the solutions available on Azure

### Episode 14: Azure IoT Services | IoT Hub, IoT Central, Azure Sphere

### Episode 15: Azure Big Data and Analytics Services | Synapse Analytics (SQL Datawarehouse), HDInsight, ### Databricks

### Episode 16: Azure Artificial Intelligence (AI) Services | Machine Learning Studio and Service

### Episode 17: Azure Serverless Computing Services | Functions, Logic Apps, Event Grid

### Episode 18: Azure DevOps Solutions | Azure DevOps, DevTest Labs

Describe Azure management tools

### Episode 19: Azure Tools | Portal, PowerShell, CLI and CloudShell

### Episode 20: Azure Advisor

## Module 3

![alt text](./Assets/path-3.png)

🔷 Describe Security, Privacy, Compliance, and Trust (25-30%)

Describe securing network connectivity in Azure

### Episode 21: Security Groups | NSG and ASG | Network Security Groups and Application Security grouyps

### Episode 22: User-defined Routes (UDR)

### Episode 23: Azure Firewall

### Episode 24: Azure DDoS Protection

Describe core Azure Identity services

### Episode 25: Azure Identity Services | Identity, Authentication, Authorization & Azure AD

Describe security tools and features of Azure

### Episode 26: Azure Security Center and usage scenarios

### Episode 27: Key Vault

Describe Azure governance features

### Episode 28: Role-Based Access Control (RBAC)

### Episode 29: Resource Locks

### Episode 30: Tags

### Episode 31: Azure Policy

### Episode 32: Azure Blueprints

### Episode 33: Cloud Adoption Framework

Describe privacy and compliance resources

### Episode 34: Core tenets of Security, Privacy, and Compliance

## Module 4

![alt text](./Assets/path-4.png)

Describe Azure cost management and Service Level Agreements (10-15%)
Describe methods for planning and managing costs

### Episode 35: Cost Affecting Factors

### Episode 36: Cost Reduction Methods and Pricing, TCO Calculators

### Episode 37: Azure Cost Management

Describe Azure Service Level Agreements (SLAs) and service lifecycles

### Episode 38: Azure Service Level Agreement (SLA)

### Episode 39: Service lifecycle in Azure
