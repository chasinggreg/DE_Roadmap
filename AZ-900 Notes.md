# AZ-900 Notes

<p align="center">
  <img width="128" height="128" src="./Assets/microsoft-certified-fundamentals-badge.svg">
</p>

## Value

Azure Fundamentals provides the most expansive view of Cloud architecture and Azure.

<div style="padding: 15px; border: 1px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 4px; color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6;">
NOTE: Bird's-eye view - think foundation.
</div>

## Length of Study

![alt text](./Assets/lengthStudy.png)

---

## Why Cloud Computing?

1. High Speed - Quick Deployment
2. Automatic Software Updates and Integration
3. Efficiency and Cost Reduction
4. Unlimited Storage Capacity
5. Scalability

## Cloud Hosting Evolution

### Dedicated Server

![alt text](./Assets/dedicated_server.png)

- One physical machine dedicated to a single business.
- Runs a single web-app/site.
- **Very expensive, High Maintenace, High Security**

### Virtual Private Server (VPS)

![alt text](./Assets/vps.png)

- One physical machine dedicated to a single business.
- The physical machine is virtualized into sub-machines.
- Runs multiple web-apps/sites.
- **Better utilization and isolation of resources.**

### Shared Hosting

![alt text](./Assets/shared_hosting.png)

- One physical machine, shared by hundreds of businesses.
- Relies on most tenants under-utilizing their resources.
- Very cheap, limited functionality, poor isolation.

### Cloud Hosting

![alt text](./Assets/cloud_hosting.png)

- Muliple physical machines that act as one system.
- The system is abstracted into multiple cloud services.
- **Flexible, scalable, secure, cost-effective, high configurability.**

## Common Cloud Services

A cloud provider can have hundreds of cloud services that are grouped various types of services. The four most common types of cloud services for Infrastructure as a Service (IaaS) would be:

- Compute
- Storage
- Networking
- Databases

The term "cloud computing" can be used to refer to all categories, even though it has "compute" in the name.

### Compute

Imagine having a virtual computer that can run applications, programs, and code.

### Storage

Imagine having a virtual hard-drive that can store files.

### Networking

Imagine having a virtual network being able to define internet connections or network isolations.

### Databases

Imagine a virtual database for storing reporting data or a database for general purpose web-application.

## Cloud Services Models

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:left;vertical-align:top}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;margin: auto 0px;}}</style>
<div class="tg-wrap"><table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">SaaS<br></th>
    <th class="tg-0lax">PaaS</th>
    <th class="tg-0lax">IaaS</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">SaaS is a cloud-hosted, ready-to-use application software.
    <b>Don't worry about how the service is maintained. It just works and remains available.</b></td>
    <td class="tg-0lax">PaaS provides a cloud-based platform for developing, running, and managing applications.
    <b>Don't worry about, provisioning, configuring, or understanding the hardware or OS.</b></td>
    <td class="tg-0lax">IaaS is a type of cloud computing service that offers essential compute, storage, and networking resources on demand, on a pay-as-you-go basis.
    <b>Don't worry about IT staff, data centers and hardware.</b></td>
  </tr>
  <tr>
    <td class="tg-0lax">
    <img src="./Assets/Gmail_Logo_512px.png" width="38" height="38">
    <img src="./Assets/Amazon_Prime_logo_(2022).svg.png" width="78" height="48">
    <img src="./Assets/Netflix_N.png" width="28" height="48">
    </td>
    <td class="tg-0lax"><img src="./Assets/OpenShift-LogoType.svg.png" width="48" height="48"></td>
    <td class="tg-0lax"><img src="./Assets/google_cloud.png" width="48" height="48">
    <img src="./Assets/free-aws-1869025-1583149.png" width="48" height="48">
    <img src="./Assets/Microsoft_Azure.svg.png" width="48" height="48">
    </td>
  </tr>
</tbody>
</table></div>

## Benefits of Cloud Computing

| Benefit        | Desc.                                                                                                                             |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Cost-effective | You pay for what you consume, no up-front cost. Pay-as-you-go (PAYG) thousands of customers sharing the cost of resources.        |
| Global         | Launch workloads anywhere in the world, just choose a region.                                                                     |
| Reliable       | data backup, disaster recovery, and data replication, and fault tolerance                                                         |
| Scalable       | Increase or decrease resources and services based on demand                                                                       |
| Elastic        | Automate scaling during spikes and drop in demand                                                                                 |
| Current        | The underlying hardware and managed software is patched, upgraded and replaced by the cloud provider without interruption to you. |

## What is Azure?

<img src="./Assets/Microsoft_Azure.svg.png" width="48" height="48">

Azure is Microsoft's cloud computing platform with an ever-expanding services to help build solutions to meet your business goals.

## Azure Benefits

- High Availability / Disaster recovery
- Security
- Enhanced Flexibility
- Low Cost
- Speed

## Cloud Computing Responsibilities

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-ra6b{background-color:#dae8fc;color:#333333;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-djj2{background-color:#dae8fc;border-color:inherit;color:#333333;text-align:left;vertical-align:top}
.tg .tg-9rbh{background-color:#3166ff;border-color:inherit;color:#ffffff;text-align:left;vertical-align:top}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;margin: auto 0px;}}</style>
<div class="tg-wrap"><table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">On-Premise</th>
    <th class="tg-0pky">IaaS</th>
    <th class="tg-0pky">PaaS</th>
    <th class="tg-0pky">SaaS</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-ra6b">Applications</td>
    <td class="tg-djj2">Applications</td>
    <td class="tg-ra6b">Applications</td>
    <td class="tg-9rbh">Applications</td>
  </tr>
  <tr>
    <td class="tg-djj2">Data</td>
    <td class="tg-djj2">Data</td>
    <td class="tg-djj2">Data</td>
    <td class="tg-9rbh">Data</td>
  </tr>
  <tr>
    <td class="tg-djj2">Runtime</td>
    <td class="tg-djj2">Runtime</td>
    <td class="tg-9rbh">Runtime<br></td>
    <td class="tg-9rbh">Runtime</td>
  </tr>
  <tr>
    <td class="tg-djj2">Middleware</td>
    <td class="tg-djj2">Middleware</td>
    <td class="tg-9rbh">Middleware</td>
    <td class="tg-9rbh">Middleware</td>
  </tr>
  <tr>
    <td class="tg-djj2">OS</td>
    <td class="tg-djj2">OS</td>
    <td class="tg-9rbh">OS<br></td>
    <td class="tg-9rbh">OS</td>
  </tr>
  <tr>
    <td class="tg-djj2">Virtualization</td>
    <td class="tg-9rbh">Virtualization</td>
    <td class="tg-9rbh">Virtualization</td>
    <td class="tg-9rbh">Virtualization</td>
  </tr>
  <tr>
    <td class="tg-djj2">Servers</td>
    <td class="tg-9rbh">Servers</td>
    <td class="tg-9rbh">Servers</td>
    <td class="tg-9rbh">Servers</td>
  </tr>
  <tr>
    <td class="tg-djj2">Storage</td>
    <td class="tg-9rbh">Storage<br></td>
    <td class="tg-9rbh">Storage</td>
    <td class="tg-9rbh">Storage</td>
  </tr>
    <tr>
    <td class="tg-djj2">Networking</td>
    <td class="tg-9rbh">Networking<br></td>
    <td class="tg-9rbh">Networking</td>
    <td class="tg-9rbh">Networking</td>
  </tr>
</tbody>
</table></div>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-hfk9{background-color:#000000;border-color:#000000;text-align:left;vertical-align:top}
.tg .tg-ra6b{background-color:#dae8fc;color:#333333;text-align:left;vertical-align:top}
.tg .tg-ucgi{background-color:#3166ff;color:#ffffff;text-align:left;vertical-align:top}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;margin: auto 0px;}}</style>
<div class="tg-wrap"><table class="tg">
<thead>
  <tr>
    <td class="tg-hfk9">Legend:</td>
    <td class="tg-ra6b">Customer is Responsibile</td>
    <td class="tg-ucgi">CSP is Responsible</td>
  </tr>
</thead>
</table></div>

## Azure's Deployment Models

### Public Cloud

<span style="color:red"><b>Everything</b></span> built on the Cloud Provider
Also known as: Cloud-Native

![alt text](./Assets/public_deployment.png)

### Private Cloud

Everything built on company's datacenter
Also known as <span style="color:red"><b>On-Premise</b></span>
The Cloud could be <b>OpenStack</b>

![alt text](./Assets/private_deployment.png)

### Hybrid

Using both <span style="color:red"><b>On-Premise</b></span> and a <span style="color:red"><b>Cloud Service Provider</b></span>

![alt text](./Assets/hybrid_deployment.png)
