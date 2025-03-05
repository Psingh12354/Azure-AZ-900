# Azure AZ-900 Study Guide 🚀  

## 🌥️ Cloud Computing  

Cloud computing is the **on-demand delivery** of computing services over the internet, eliminating the need to manage physical infrastructure.  

### ✅ Benefits of Cloud Computing  
- **Flexibility:** Access services from anywhere with an internet connection  
- **Efficiency:** Rapidly develop and deploy applications  
- **Cost Savings:** Pay only for what you use  
- **Scalability:** Easily scale resources based on demand  

### 🔹 Examples of Cloud Services  
- 📧 Email (e.g., Gmail, Outlook)  
- 📦 Storage & Backup (e.g., OneDrive, Google Drive)  
- 🛠️ App Development & Testing  
- 📊 Data Analytics & AI  
- 🎥 Audio & Video Streaming  
- 💻 Software as a Service (e.g., Microsoft 365, Salesforce)  

---

## 🏗️ Cloud Computing Architecture  

Cloud architecture consists of **three main components**:  

1️⃣ **Front-End (User Interface)**  
   - Includes **Thin Clients** (web browsers) and **Fat Clients** (full-featured software)  

2️⃣ **Back-End (Cloud Infrastructure)**  
   - Contains **servers, storage, and application logic**  

3️⃣ **Cloud-Based Network**  
   - Uses **Internet, Intranet, and Intercloud** for data transfer and access

![image](https://github.com/user-attachments/assets/cafbd53e-3d3a-4ab5-8122-273de497d5e7)

---

## ☁️ Types of Cloud Computing Services  

### 🏗 Infrastructure as a Service (IaaS)  
🔹 **Definition:** Provides virtualized computing resources over the internet  
🔹 **Examples:** Azure Virtual Machines, AWS EC2, Google Compute Engine  
🔹 **Benefits:**  
   - Full control over OS & hardware  
   - Scalable on demand  

### 🛠 Platform as a Service (PaaS)  
🔹 **Definition:** A development platform for building, running, and managing apps  
🔹 **Examples:** Azure App Service, Google App Engine, AWS Elastic Beanstalk  
🔹 **Benefits:**  
   - Focus on application development  
   - Built-in scalability & monitoring  

### 🖥️ Software as a Service (SaaS)  
🔹 **Definition:** Cloud-hosted software accessible via the internet  
🔹 **Examples:** Microsoft 365, Dropbox, Salesforce  
🔹 **Benefits:**  
   - No installation required  
   - Accessible from any device  

---

# 🌍 Azure Regions & Availability Zones  

## 🚀 What are Azure Regions?  
An **Azure Region** is a **geographical area** containing **one or more data centers** that provide cloud services with low-latency connectivity. Each region is strategically located to offer **high availability, disaster recovery, and compliance** with local regulations.  

### 🔹 Key Features of Azure Regions  
✅ **Global Coverage** – Over 60+ regions worldwide  
✅ **Low Latency** – Services are deployed closer to users  
✅ **Compliance & Security** – Regions meet **local laws** and **industry standards**  
✅ **Resilient Infrastructure** – Redundant power, networking, and cooling  

### 🌎 Examples of Azure Regions  
- 🇺🇸 **East US, West US, Central US**  
- 🇪🇺 **North Europe, West Europe**  
- 🇮🇳 **Central India, South India**  
- 🇦🇺 **Australia East, Australia Southeast**  
- 🇯🇵 **Japan East, Japan West**  

🔗 [View All Azure Regions](https://azure.microsoft.com/en-us/explore/global-infrastructure/geographies/)  

---

## ⚡ What are Azure Availability Zones?  
**Availability Zones (AZs)** are **physically separate** data centers **within an Azure Region**, designed to protect applications from failures by providing **redundancy and high availability**.  

### 🔹 Key Features of Availability Zones  
✅ **High Availability** – Ensures **99.99% uptime** for mission-critical applications  
✅ **Fault Isolation** – Zones are independent of each other, reducing failure risks  
✅ **Data Redundancy** – Supports **replication across multiple zones**  
✅ **Disaster Recovery** – Helps mitigate **data center failures**  

### 🏗 How Availability Zones Work  
1️⃣ **Multiple Data Centers per Region** – Each zone has **separate power, networking, and cooling**  
2️⃣ **Zone-Redundant Services** – Services like **Virtual Machines, Storage, and Databases** can be deployed across zones  
3️⃣ **Load Balancing** – Ensures continuous operations even if one zone fails  

### 🔥 Examples of Azure Services Using Availability Zones  
- **Azure Virtual Machines (VMs)** – Deploy across zones for redundancy  
- **Azure SQL Database** – Geo-replication across different zones  
- **Azure Kubernetes Service (AKS)** – Distributes workloads across zones  
- **Azure Load Balancer** – Routes traffic between zones for failover  

🔗 [Learn More About Availability Zones](https://learn.microsoft.com/en-us/azure/availability-zones/az-overview)  

---

## 🔄 Region vs. Availability Zone Comparison  

| Feature | Azure Region | Availability Zone |
|---------|-------------|------------------|
| **Definition** | Geographical area with multiple data centers | Isolated data centers within a region |
| **Purpose** | Provides cloud services globally | Ensures high availability within a region |
| **Fault Tolerance** | Resilient within the region but not across different regions | Protects against zone failures within a region |
| **Example** | **East US, West Europe, Central India** | **Zone 1, Zone 2, Zone 3 within East US** |

---

## 🎯 Choosing the Right Deployment Strategy  
✅ **For Localized Apps:** Deploy in a single region for minimal latency  
✅ **For High Availability:** Use Availability Zones within a region  
✅ **For Disaster Recovery:** Use **multiple regions** for **geo-redundancy**  
✅ **For Global Scale:** Deploy workloads across **multiple Azure regions**  

---

## 📖 Learn More  
🔗 [Azure Regions Documentation](https://learn.microsoft.com/en-us/azure/global-infrastructure/geographies)  
🔗 [Azure Availability Zones Overview](https://learn.microsoft.com/en-us/azure/availability-zones/az-overview)  
🔗 [Azure Global Infrastructure](https://azure.microsoft.com/en-us/global-infrastructure/)  


---
## 🌎 Public Cloud Overview  

### 🏢 What is a Public Cloud?  
A **public cloud** is a shared computing environment managed by third-party providers.  

🔹 **Features:**  
- Multi-tenancy (shared resources)  
- Pay-as-you-go pricing  
- High scalability  

🔹 **Examples:**  
- Microsoft Azure  
- Amazon Web Services (AWS)  
- Google Cloud Platform (GCP)  

---

## 🔹 Azure Services Overview  

### 💻 Compute Services  
- **Azure Virtual Machines (VMs):** Run workloads on demand  
- **Azure Kubernetes Service (AKS):** Managed Kubernetes for containerized apps  

### 📦 Storage Services  
- **Azure Blob Storage:** Store unstructured data  
- **Azure File Storage:** Managed cloud-based file sharing  

### 🌐 Networking  
- **Azure Virtual Network (VNet):** Secure private network  
- **Azure Load Balancer:** Distributes traffic efficiently  

### 🔐 Security & Monitoring  
- **Azure Monitor:** Logging & diagnostics  
- **Azure Security Center:** Security management system  

---

## 🌐 Web Applications (Web Apps)  

A **Web Application (Web App)** is a browser-based application that runs on remote servers, accessible via the internet.  

### ✅ Advantages of Web Apps  
- No installation required  
- Accessible on any device  
- Maintenance & updates handled by the provider  

### 🔹 Examples of Web Apps  
- 🛒 **E-Commerce Sites** (Amazon, eBay)  
- 📧 **Web Email Services** (Gmail, Outlook)  
- 📊 **Online Collaboration Tools** (Google Docs, Microsoft 365)  

---

## 🛠 Kubernetes & Containerization  

### 🐳 What is Containerization?  
**Containerization** is a virtualization method that packages applications with their dependencies into **isolated containers** for consistent execution.  

🔹 **Benefits:**  
- Works consistently across environments  
- Lightweight & efficient  
- Faster deployment than traditional VMs  

### 🚀 What is Kubernetes?  
**Kubernetes (K8s)** is an open-source **container orchestration** tool that automates the deployment, scaling, and management of containers.  

🔹 **Key Features:**  
- **Pods:** Smallest deployable units in Kubernetes  
- **Nodes:** Machines running the containers  
- **Cluster:** A group of nodes managed by Kubernetes  
- **Service:** Exposes applications to the network  

🔹 **Advantages of Kubernetes:**  
- **Automated Scaling:** Adjust resources based on demand  
- **Self-Healing:** Restarts failed containers  
- **Load Balancing:** Distributes traffic efficiently  
- **Multi-Cloud Support:** Works across cloud providers  

🔹 **Use Cases:**  
- Microservices architecture  
- Continuous Deployment (CI/CD)  
- Hybrid & Multi-Cloud Deployments  

---

## 🏛️ Sovereign Cloud  

### 🔐 What is a Sovereign Cloud?  
A **Sovereign Cloud** ensures that data remains within a country's jurisdiction, complying with local regulations and security requirements.  

🔹 **Key Features:**  
- **Data Sovereignty:** Data remains within national borders  
- **Regulatory Compliance:** Adheres to laws like GDPR, CCPA  
- **Enhanced Security:** Protection from foreign access  

🔹 **Benefits:**  
- Prevents unauthorized data access  
- Supports industries like finance, healthcare, and government  

🔹 **Examples of Sovereign Cloud Implementations:**  
- 🇪🇺 **GAIA-X (Europe)** – European cloud sovereignty initiative  
- 🇮🇳 **India’s Digital Sovereignty Cloud** – Ensuring national data governance  
- 🇦🇺 **Australian Government Cloud Framework** – Compliance-driven infrastructure  

---

## 🚀 Getting Started with Azure  

1️⃣ **Sign Up:** Create a free Azure account  
2️⃣ **Explore the Azure Portal:** Get familiar with the management dashboard  
3️⃣ **Try a Quickstart:** Deploy a Virtual Machine or Web App  
4️⃣ **Learn with Docs:** Read Azure documentation for hands-on tutorials  

---

# ⚡ Azure Functions

## 🚀 What is Azure Functions?  
**Azure Functions** is a **serverless compute service** that enables developers to run event-driven applications **without managing infrastructure**. It **automatically scales** and **charges only for execution time**, making it ideal for cloud automation, API backends, and real-time data processing.

---

## 🔹 Key Features  
✅ **Serverless Execution** – No infrastructure management required  
✅ **Event-Driven** – Triggered by HTTP requests, queues, timers, and more  
✅ **Auto-Scaling** – Dynamically scales based on demand  
✅ **Pay-as-You-Go Pricing** – Only pay for execution time used  
✅ **Multi-Language Support** – Works with C#, Java, JavaScript, Python, PowerShell, and more  

---

## 🔥 Use Cases  
📧 **Automated Email Processing** – Trigger functions based on new emails  
📦 **Data Processing** – Handle IoT data, logs, or file uploads  
🔗 **API Backends** – Create lightweight RESTful APIs  
⏳ **Scheduled Jobs** – Run tasks at predefined intervals  
🔄 **Event-Driven Workflows** – Automate actions based on Azure events  

---

## 🏗 How Azure Functions Work  

1️⃣ **Triggers** – Define how the function starts (e.g., HTTP request, queue message)  
2️⃣ **Bindings** – Connect to input/output sources (e.g., Azure Blob Storage, Cosmos DB)  
3️⃣ **Execution** – Function runs based on the defined trigger  
4️⃣ **Auto-Scaling** – Azure automatically scales functions as needed  

---

## ⚡ Example: HTTP Triggered Azure Function (JavaScript)  
```javascript
module.exports = async function (context, req) {
    context.res = {
        status: 200,
        body: "Hello, Azure Functions!"
    };
};
```





---

### Some Addtional Learning

# ⭐ Star Schema  

## 🚀 What is Star Schema?  
A **Star Schema** is a type of **database schema** used in **data warehousing**. It is designed for **fast query performance** and **simplifies data retrieval** by organizing data into **fact tables** and **dimension tables**. The structure resembles a **star**, where a **central fact table** is connected to multiple **dimension tables**.

---

## 🔹 Key Components of Star Schema  

### 1️⃣ Fact Table  
- The **central table** in the schema  
- Stores **quantitative data (measurable metrics)**  
- Contains **foreign keys** linking to dimension tables  
- Example: **Sales Data Table** (Revenue, Quantity Sold, Discounts)  

### 2️⃣ Dimension Tables  
- Descriptive **reference data** for facts  
- Contains **attributes** used for filtering, grouping, and aggregation  
- Example: **Customer Table, Product Table, Time Table**  

---

## 🌟 Example of a Star Schema  

![image](https://github.com/user-attachments/assets/490dccc9-6b8d-499c-84e0-f6f9e16c4d13)



### 🔍 In this **Star Schema**, the **Fact Table (Sales Data)** is linked to multiple **Dimension Tables**:  
✅ **Customer Dimension** – Customer details like name, location  
✅ **Product Dimension** – Product name, category, price  
✅ **Time Dimension** – Date, month, quarter, year  
✅ **Store Dimension** – Store location, manager, region  

---

## 🔥 Advantages of Star Schema  

✅ **Fast Query Performance** – Simple joins and indexed data improve speed  
✅ **Easy to Understand** – Intuitive structure simplifies data analysis  
✅ **Efficient Aggregation** – Optimized for reporting and analytics  
✅ **High Read Performance** – Ideal for business intelligence (BI) tools  
✅ **Denormalized Structure** – Reduces complexity for analysts  

---

## ❌ Limitations of Star Schema  

⚠️ **Data Redundancy** – Dimension tables may duplicate data  
⚠️ **Not Ideal for Complex Relationships** – Doesn't handle many-to-many relationships efficiently  
⚠️ **Larger Storage Requirements** – Due to data denormalization  

---

## 🔄 Star Schema vs. Snowflake Schema  [youtube reference](https://www.youtube.com/watch?v=hQvCOBv_-LE)

| Feature         | Star Schema 🌟 | Snowflake Schema ❄️ |
|----------------|--------------|-----------------|
| **Structure**  | Simple, flat | Normalized, hierarchical |
| **Query Speed** | Faster (fewer joins) | Slower (more joins) |
| **Data Redundancy** | Higher | Lower |
| **Storage Usage** | More | Less |
| **Use Case** | BI tools, dashboards | Complex analytical queries |

---

# Azure IAM, MD5, and Entry ID Model Notes

## 🔹 Azure Identity and Access Management (IAM)
Azure IAM, now known as **Microsoft Entra ID** (formerly Azure Active Directory), is a cloud-based identity and access management service. It provides authentication and authorization mechanisms to manage user identities and access to resources securely.

### 🔑 Key Features:
- **Single Sign-On (SSO):** Users can log in once and access multiple applications seamlessly.
- **Multi-Factor Authentication (MFA):** Enhances security by requiring multiple forms of authentication.
- **Conditional Access Policies:** Restricts access based on conditions like user location, device security, and login behavior.
- **Role-Based Access Control (RBAC):** Assigns permissions based on predefined roles to minimize security risks.

🔗 [Learn More](https://azure.microsoft.com/en-us/products/category/identity)

---

## 🔹 MD5 Usage in Azure Services
**MD5 (Message Digest Algorithm 5)** is a cryptographic hash function producing a 128-bit hash value. While MD5 is widely used, it is **not recommended** for security-critical applications due to hash collision vulnerabilities.

### ⚡ Where MD5 is Used in Azure:
#### 1️⃣ **Azure Blob Storage Integrity Checks**
- Used for verifying data integrity when uploading large files.
- Each block in a large file upload can be validated using an MD5 checksum.
- ⚠️ **Note:** Computing MD5 for large files (>100MB) can be resource-intensive and may cause performance issues.
- 📌 [MD5 for Large Files](https://learn.microsoft.com/en-us/answers/questions/282572/md5-hash-calculation-for-large-files)

#### 2️⃣ **BGP Peering Sessions (Networking)**
- Used to authenticate peers in **Border Gateway Protocol (BGP)** sessions.
- Ensures both peers verify each other before establishing a connection.
- Configurable in Azure Portal under: 
  **Settings > Connections > IPv4/IPv6 > MD5 Authentication Key**
- 📌 [BGP MD5 Authentication](https://learn.microsoft.com/en-us/answers/questions/1025769/bgp-md5-auth-on-peering-setup-in-azure-portal)

⚠️ **MD5 is considered weak**—use **SHA-256** or stronger algorithms for security-sensitive applications.

---

## 🔹 Entry ID Model in Azure
The **Entry ID Model** in Azure refers to unique identifiers assigned to various resources within the platform. These IDs help in tracking, managing, and securing assets efficiently.

### 🛠 Common Usage:
- **Resource Management:** Unique IDs for VMs, storage accounts, and network configurations.
- **Logging & Monitoring:** Azure Monitor assigns Entry IDs for log entries.
- **Security & Auditing:** Entry IDs help track user actions and API calls for auditing purposes.

---

### 🔑 Authentication vs. Authorization

| Feature           | Authentication 🔐 | Authorization 🎟️ |
|------------------|-----------------|-----------------|
| **Definition**   | Verifies **who you are**. | Determines **what you can do**. |
| **Purpose**      | Confirms identity (e.g., login). | Grants or restricts access to resources. |
| **Example**      | Logging into GitHub with a password or SSH key. | Accessing a private repo or pushing to a branch. |
| **Handled By**   | Username, password, OAuth, SSH keys. | Permissions, roles, access control policies. |

# 🔐 MFA vs. 2FA

| Feature          | Multi-Factor Authentication (MFA) | Two-Factor Authentication (2FA) |
|-----------------|----------------------------------|--------------------------------|
| **Definition**  | Authentication using **two or more** factors. | Authentication using **exactly two** factors. |
| **Factors Used** | Can include 2FA but may also require additional layers (e.g., biometrics, security keys). | Always consists of two distinct factors (e.g., password + OTP). |
| **Security Level** | More secure due to multiple layers. | Secure, but limited to two factors. |
| **Examples**    | **GitHub:** Password + TOTP + Security Key <br> **Banking:** Card + PIN + Fingerprint <br> **Corporate Login:** Smart Card + PIN + Face Recognition | **GitHub:** Password + TOTP (Authenticator App) <br> **Banking:** Card + PIN <br> **Email Login:** Password + SMS Code |


---

# 🔐 Role-Based Access Control (RBAC)

## 📌 What is RBAC?
Role-Based Access Control (RBAC) is a security model that restricts system access based on user roles. Instead of granting permissions directly to users, access rights are assigned to roles, and users are assigned to those roles.

---

## 🔹 Types of RBAC

| Type                | Description | Example |
|---------------------|-------------|---------|
| **Flat RBAC**      | Basic role-based control where users are assigned a single role with specific permissions. | A **viewer** in GitHub can only read repositories but not modify them. |
| **Hierarchical RBAC** | Roles inherit permissions from other roles in a hierarchy. | A **Manager** inherits permissions from an **Employee** but has additional privileges. |
| **Constrained RBAC** | Enforces separation of duties (SoD), preventing users from having conflicting roles. | A user cannot be both a **developer** and an **approver** for the same code change. |
| **Dynamic RBAC**   | Roles and permissions change dynamically based on conditions (e.g., time, location). | A system admin can make changes **only during working hours** or when connected to a company VPN. |

---

### 🔥 **1. Built-in Roles (Predefined)**

Azure provides **predefined roles** to manage access to resources efficiently.  
Each role grants specific permissions and can be assigned at different **scopes** (Subscription, Resource Group, or Resource Level).

| Role Name                  | Description | Example Use Case |
|----------------------------|-------------|------------------|
| **Owner** 🏆 | Full access to manage resources and **assign roles**. | The IT Admin needs complete control over all Azure resources. |
| **Contributor** ✍️ | Can create, modify, and delete resources but **cannot assign roles**. | A DevOps Engineer needs to deploy and configure VMs but **shouldn't manage permissions**. |
| **Reader** 👀 | Can **view** resources but **cannot make changes**. | A Security Analyst needs read-only access to monitor cloud activity. |
| **User Access Administrator** 🔑 | Can **manage RBAC permissions** but **not resources**. | An HR Manager should be able to assign employees to roles without modifying resources. |

---

### 🛠 **Example Scenarios**
1️⃣ **Assigning an Owner Role**:  
- The **Cloud Admin** needs **full control** over an entire **subscription**.  
- Assign them the **Owner** role at the **Subscription Scope**.  

2️⃣ **Assigning a Contributor Role**:  
- A **Developer** needs to **deploy applications** but **should not modify RBAC settings**.  
- Assign them the **Contributor** role at the **Resource Group level**.  

3️⃣ **Assigning a Reader Role**:  
- The **Audit Team** needs to **monitor logs** without making changes.  
- Assign them the **Reader** role at the **Subscription Scope**.  

4️⃣ **Assigning a User Access Administrator Role**:  
- The **HR Team** wants to manage **who can access resources**, but not change configurations.  
- Assign them the **User Access Administrator** role at the **Subscription Scope**.  

---

### 📌 **Exam Tip for AZ-900**
> **"Owner" can assign roles, but "Contributor" cannot.**  
> **Use "Reader" for audit teams needing view-only access.**  
> **RBAC permissions are inherited at lower scopes unless overridden.**  

---

## 🛠️ Example of RBAC in GitHub

| Role              | Permissions |
|------------------|------------|
| **Owner**       | Full control over the repository, including managing roles. |
| **Admin**       | Can manage repo settings but cannot delete the organization. |
| **Maintainer**  | Can approve and merge pull requests but cannot change repo settings. |
| **Developer**   | Can push code and create pull requests but cannot merge them. |
| **Viewer**      | Read-only access to repositories. |

---

## 🔍 Benefits of RBAC
✔️ **Improved Security** – Minimizes unauthorized access.  
✔️ **Simplified Management** – Easier permission assignment through roles.  
✔️ **Compliance** – Helps meet regulatory requirements (e.g., HIPAA, GDPR).  
✔️ **Efficiency** – Reduces admin workload by assigning permissions to roles instead of individuals.  


----
# Agility, Fault Tolerance & High Availability in Azure

## 📌 Overview
In **cloud computing**, businesses prioritize **agility, fault tolerance, and high availability** to ensure **efficient operations, minimal downtime, and system resilience**. 

Azure provides multiple services and architectures to support these capabilities.

---

## 🚀 Agility
**Agility** refers to the ability to **quickly adapt** to changing business needs by scaling, deploying, and modifying infrastructure effortlessly.

### 🔹 Key Features in Azure:
- **Autoscaling**: Services like **Azure Virtual Machine Scale Sets (VMSS)** dynamically adjust resources.
- **DevOps & CI/CD**: **Azure DevOps** enables rapid deployment and testing.
- **Microservices**: **Azure Kubernetes Service (AKS)** facilitates agile application development.
- **Serverless Computing**: **Azure Functions** enables event-driven applications without managing servers.

### ✅ **Example in Azure**
A startup launches a new feature and needs to **scale up** rapidly. Azure **App Services** and **Azure SQL Database** allow quick adjustments without provisioning new hardware.

---

## 🛡️ Fault Tolerance
**Fault tolerance** ensures a system **continues operating** even if certain components fail.

### 🔹 Key Features in Azure:
- **Redundancy**: Azure services store multiple copies of data to prevent loss.
- **Geo-replication**: **Azure Storage and Azure SQL Database** offer automatic **replication** across regions.
- **Load Balancing**: **Azure Load Balancer & Azure Front Door** distribute traffic to prevent failures.
- **Backup & Disaster Recovery**: **Azure Backup & Azure Site Recovery** ensure data integrity.

### ✅ **Example in Azure**
A company's web app runs on **multiple VMs**. If one VM fails, **Azure Load Balancer** redirects traffic to healthy instances, ensuring **zero downtime**.

---

## 🔄 High Availability (HA)
**High availability** means a system is **always accessible** with minimal downtime.

### 🔹 Key Features in Azure:
- **Availability Zones**: Azure data centers are divided into multiple **fault-isolated zones**.
- **Active-Passive & Active-Active Architectures**: Services like **Azure Traffic Manager** ensure requests are routed to the nearest available resource.
- **99.99% Uptime SLAs**: Azure ensures uptime for critical services like **Azure SQL Managed Instance** and **Azure Virtual Machines**.
- **Health Monitoring**: **Azure Monitor & Azure Application Insights** track system health.

### ✅ **Example in Azure**
A bank runs an **online banking app** using **Azure SQL Database with Geo-Replication**. Even if the primary region fails, traffic is **seamlessly redirected** to the **secondary region**.

-----

# CapEx vs OpEx in Azure

## 📌 Overview
When considering cloud computing costs in **Microsoft Azure**, expenses fall into two primary categories:

- **CapEx (Capital Expenditure)** - Upfront investment in physical infrastructure.
- **OpEx (Operational Expenditure)** - Pay-as-you-go expenses for cloud services.

---

## 🆚 CapEx vs OpEx

| Aspect        | **CapEx (Capital Expenditure)** | **OpEx (Operational Expenditure)** |
|--------------|--------------------------------|------------------------------------|
| **Definition** | One-time upfront cost for acquiring IT infrastructure. | Ongoing expenses based on cloud service usage. |
| **Payment Model** | Large initial investment. | Pay-as-you-go or subscription-based model. |
| **Scalability** | Limited by initial investment; requires new purchases for upgrades. | Highly scalable; resources can be increased or decreased as needed. |
| **Example in Azure** | Purchasing on-premises servers, storage devices, or networking equipment. | Using Azure Virtual Machines (VMs), Azure SQL Database, or Azure Blob Storage. |
| **Maintenance** | Requires dedicated IT team for upkeep, repairs, and upgrades. | Managed by Azure, reducing operational overhead. |
| **Flexibility** | Less flexible; hardware must be fully utilized to justify cost. | More flexible; pay only for what is used. |
| **Risk** | Higher risk if demand fluctuates, as unused resources remain costly. | Lower risk due to cost optimization and dynamic scaling. |

---

## 💡 Azure and the Shift to OpEx

Most organizations prefer **OpEx** in Azure due to its **cost-efficiency, flexibility, and scalability**. Azure offers services like:

- **Azure Virtual Machines (VMs)** – Pay for compute power as needed.
- **Azure SQL Database** – No need to invest in physical database servers.
- **Azure Kubernetes Service (AKS)** – Scale containerized applications dynamically.

With **Azure Reserved Instances**, companies can mix **OpEx** and **CapEx** by committing to long-term cloud usage for discounts.


-----

# 🛡️ Network Security Groups (NSGs)

## 📌 Introduction  
A **Network Security Group (NSG)** is a security feature in cloud platforms (such as **Microsoft Azure**) that **controls inbound and outbound traffic** to network resources. NSGs use rules to filter traffic at both the **subnet** and **network interface** levels.

---

## 🔹 Features of NSGs  
- ✅ **Traffic Control** – Restricts incoming & outgoing traffic based on security rules.  
- ✅ **Stateful Rules** – If an inbound rule allows traffic, the response is automatically allowed.  
- ✅ **Rule Priority** – Rules are evaluated based on priority (lower number = higher priority).  
- ✅ **Association** – Can be applied to **subnets** or **network interfaces (NICs)**.  
- ✅ **Logging & Monitoring** – Can be integrated with Azure Monitor and NSG Flow Logs.  

---

## 📜 NSG Rule Components  
Each rule in an **NSG** consists of:  

| Component        | Description |
|-----------------|-------------|
| **Name**        | A unique identifier for the rule |
| **Priority**    | Determines rule evaluation order (lower = higher priority) |
| **Source**      | Defines where traffic originates from (IP, CIDR, Service Tag) |
| **Destination** | Defines where traffic is going (IP, CIDR, Service Tag) |
| **Port**        | Specifies the port or range of ports (e.g., 22, 80, 443) |
| **Protocol**    | Specifies **TCP, UDP, ICMP, or Any** |
| **Direction**   | Defines if the rule applies to **Inbound** or **Outbound** traffic |
| **Action**      | Specifies whether traffic is **Allowed** or **Denied** |

---

## 🔄 NSG Association  
NSGs can be **associated** with:  
1️⃣ **Subnets** – Affects all virtual machines (VMs) within the subnet.  
2️⃣ **Network Interfaces (NICs)** – Affects only specific VMs or services.  

**💡 Note:** If an NSG is applied at both **subnet** and **NIC** levels, **both rulesets** are enforced.

---

## ⚡ Default NSG Rules  
Azure automatically creates **default security rules** that **cannot** be deleted.  

| Rule Name                  | Priority | Source           | Destination | Port  | Action |
|----------------------------|----------|-----------------|-------------|--------|--------|
| AllowVnetInBound          | 65000    | Virtual Network | Virtual Network | Any | Allow  |
| AllowAzureLoadBalancerInBound | 65001 | Azure Load Balancer | Any | Any | Allow  |
| DenyAllInBound            | 65500    | Any             | Any         | Any    | Deny   |
| AllowVnetOutBound         | 65000    | Virtual Network | Virtual Network | Any | Allow  |
| AllowInternetOutBound     | 65001    | Any             | Internet    | Any    | Allow  |
| DenyAllOutBound           | 65500    | Any             | Any         | Any    | Deny   |

---

## 🛠️ Example NSG Rule (Allow SSH)

To allow **SSH traffic (port 22)** from any source, use the following **Azure CLI** command:

```sh
az network nsg rule create --resource-group MyResourceGroup \
  --nsg-name MyNSG --name AllowSSH --priority 100 \
  --source-address-prefixes '*' --destination-port-ranges 22 \
  --direction Inbound --access Allow --protocol TCP --description "Allow SSH access"
```

# ☁️ Public vs Private vs Hybrid Cloud in Azure

## 📌 Introduction  
Cloud computing offers three primary deployment models:  
- **Public Cloud** – Resources are hosted by a third-party provider and shared among multiple users.  
- **Private Cloud** – Resources are dedicated to a single organization for enhanced control and security.  
- **Hybrid Cloud** – A combination of public and private cloud, allowing flexibility and scalability.

Understanding these models is essential for the **Microsoft Azure Fundamentals (AZ-900)** exam.

---

## 🌍 Public Cloud  
### 🔹 Definition  
The **Public Cloud** is a cloud computing model where services and infrastructure are hosted and managed by a cloud provider. The resources are shared among multiple tenants over the **internet**.

### 🔹 Characteristics  
- 🌐 **Multi-Tenant Environment** – Multiple users share the same infrastructure.  
- 💰 **Pay-as-You-Go Pricing** – Cost-efficient, as you pay only for what you use.  
- 🚀 **Highly Scalable** – Resources can be quickly scaled up or down.  
- 🛠️ **Managed by Cloud Provider** – No hardware maintenance required.  

### 🔹 Advantages  
✅ **Lower Costs** – No upfront infrastructure costs.  
✅ **High Availability & Reliability** – Backed by large-scale data centers.  
✅ **Flexible & Scalable** – Ideal for businesses with fluctuating workloads.  

### 🔹 Disadvantages  
❌ **Less Control** – Limited access to backend configurations.  
❌ **Security Concerns** – Data is stored in a shared environment.  
❌ **Compliance Issues** – Some industries require private hosting for regulatory reasons.  

### 🔹 Examples in Azure  
- **Azure Virtual Machines (VMs)**
- **Azure App Services**
- **Azure Storage**
- **Microsoft 365 & OneDrive**

---

## 🏢 Private Cloud  
### 🔹 Definition  
A **Private Cloud** is a dedicated cloud environment exclusively for one organization, providing full control and customization.

### 🔹 Characteristics  
- 🔒 **Single-Tenant Environment** – Infrastructure is not shared with other organizations.  
- 🎯 **Greater Control** – Full access to configurations and customizations.  
- 🛡️ **Enhanced Security & Compliance** – Suitable for industries with strict regulations (e.g., finance, healthcare).  

### 🔹 Advantages  
✅ **Better Security & Compliance** – Data stays within the organization.  
✅ **Full Customization** – Adjust resources based on specific needs.  
✅ **Dedicated Performance** – No shared resources lead to better performance.  

### 🔹 Disadvantages  
❌ **Higher Costs** – Requires significant investment in infrastructure.  
❌ **Limited Scalability** – Not as easily scalable as public cloud.  
❌ **Complex Management** – Requires dedicated IT teams to manage resources.  

### 🔹 Examples in Azure  
- **Azure Stack Hub** – Extends Azure services to on-premises environments.  
- **Azure Dedicated Host** – Provides single-tenant, dedicated physical servers.  

---

## 🔄 Hybrid Cloud  
### 🔹 Definition  
A **Hybrid Cloud** combines both **public** and **private cloud** environments, allowing seamless interaction between the two.

### 🔹 Characteristics  
- 🔗 **Interoperability** – Connects on-premises resources with cloud services.  
- 📈 **Flexible Scalability** – Move workloads between private and public cloud as needed.  
- 🏛️ **Compliance & Security** – Store sensitive data in a private cloud while using public cloud for other tasks.  

### 🔹 Advantages  
✅ **Best of Both Worlds** – Balances flexibility, security, and cost.  
✅ **Optimized Cost Management** – Utilize public cloud when needed to save costs.  
✅ **Disaster Recovery & Backup** – Use public cloud as a backup for private resources.  

### 🔹 Disadvantages  
❌ **Complex Integration** – Requires a strong network and security setup.  
❌ **Higher Maintenance** – Managing multiple cloud environments can be challenging.  
❌ **Potential Latency Issues** – Data transfer between private and public clouds may introduce latency.  

### 🔹 Examples in Azure  
- **Azure Arc** – Enables hybrid cloud management across different environments.  
- **Azure ExpressRoute** – Provides private connections between on-premises and Azure.  
- **Azure Hybrid Benefit** – Allows cost savings when using existing Windows Server & SQL Server licenses.  

---

## 🏆 Comparison Table  

| Feature         | Public Cloud | Private Cloud | Hybrid Cloud |
|----------------|-------------|--------------|--------------|
| **Ownership**  | Cloud provider | Organization | Shared |
| **Cost**       | Low, pay-as-you-go | High, upfront investment | Medium |
| **Scalability** | High | Limited | High |
| **Security**   | Moderate | High | High |
| **Customization** | Low | High | Medium |
| **Management** | Fully managed | Organization-managed | Requires hybrid management |
| **Best for**   | Startups, businesses needing flexibility | Enterprises with strict security needs | Companies needing balance between security & flexibility |

---

## 🎯 Which Cloud Model Should You Choose?  
🔹 Use **Public Cloud** if you need **cost-effective**, **scalable**, and **low-maintenance** solutions.  
🔹 Use **Private Cloud** if you require **full control**, **customization**, and **high security**.  
🔹 Use **Hybrid Cloud** if you want a mix of **security**, **flexibility**, and **cost-efficiency**.  

---

# Service Level Agreements (SLA) in Microsoft Azure - AZ-900

## 📌 What is an SLA?
A **Service Level Agreement (SLA)** is a formal agreement between **Microsoft and Azure customers** that defines:
- **Uptime & Performance Guarantees** (e.g., 99.9%, 99.95%, 99.99%)
- **Compensation (Service Credits)** in case of downtime
- **Scope of Service Commitment**

---

## 🎯 **Key SLA Components**
### 1️⃣ **Uptime & Availability**
Microsoft guarantees **availability** for services based on their SLA tier.  
Typical uptime commitments:
| SLA (%) | Downtime per month |
|---------|-------------------|
| 99%     | ~7.3 hours |
| 99.9%   | ~43.8 minutes |
| 99.95%  | ~21.9 minutes |
| 99.99%  | ~4.3 minutes |
| 99.999% | ~26 seconds |

### 2️⃣ **Service Credit Compensation**
If Microsoft fails to meet the SLA, customers may receive service credits based on the **downtime**:
| Uptime Achieved | Service Credit (%) |
|----------------|------------------|
| < 99.9%       | 10%               |
| < 99%         | 25%               |
| < 95%         | 100%              |

---

## 📌 **SLA for Azure Services**
Different Azure services have different SLA commitments:

### 🔹 **Compute**
| Service | SLA (%) |
|---------|--------|
| Virtual Machines (with multiple instances) | 99.95% |
| Virtual Machines (with a single instance) | 99.9% |
| Azure Kubernetes Service (AKS) | 99.95% |

### 🔹 **Storage & Databases**
| Service | SLA (%) |
|---------|--------|
| Azure Blob Storage (RA-GRS) | 99.99% |
| Azure SQL Database (Business Critical) | 99.995% |
| Cosmos DB | 99.999% |

### 🔹 **Networking**
| Service | SLA (%) |
|---------|--------|
| Azure Load Balancer (Standard) | 99.99% |
| Azure DNS | 100% |
| Azure Virtual WAN | 99.95% |

---

## 🏆 **SLA Best Practices**
✅ Deploy **redundant resources** across **multiple regions**.  
✅ Use **Availability Zones** for high uptime.  
✅ Monitor **Azure Service Health** for real-time updates.  
✅ Implement **automatic failover & backup** strategies.  

---

# 🔐 Azure Active Directory (Azure AD) Release Programs

Azure Active Directory (Azure AD) follows a structured release cycle before features become widely available.  
These release stages include **Private Preview, Public Preview, and General Availability (GA)**.

---

## 📌 **Azure AD Release Stages**
### 1️⃣ **Private Preview (Early Access)**
🔹 Features are available to a **limited set of customers**.  
🔹 Requires **Microsoft invitation** to participate.  
🔹 Not supported for production workloads.  
🔹 Microsoft collects feedback to refine features.  

✅ **Who can access?** Selected customers under NDA.  
⚠️ **Risk Level**: High (features may change or be removed).  

---

### 2️⃣ **Public Preview (Beta Testing)**
🔹 Features are **open to all Azure customers** for testing.  
🔹 Users can enable preview features via the **Azure Portal**.  
🔹 Can be used in production **with caution** (not covered by SLA).  
🔹 Provides **early access** to upcoming capabilities.  

✅ **Who can access?** All Azure customers.  
⚠️ **Risk Level**: Medium (may not be stable for all scenarios).  

**🔗 Enabling Public Preview Features:**  
1. Sign in to [Azure Portal](https://portal.azure.com).  
2. Navigate to **Azure AD** > **Preview Features**.  
3. Select and enable the desired preview.  

---

### 3️⃣ **General Availability (GA)**
🔹 Fully tested, stable, and **officially released**.  
🔹 Available to **all customers** with **SLA-backed support**.  
🔹 Recommended for **production use**.  
🔹 Includes **official documentation & Microsoft support**.  

✅ **Who can access?** All customers & organizations.  
⚠️ **Risk Level**: Low (feature is stable and supported).  

---

## 🔍 **Comparison of Release Stages**
| Stage            | Availability       | Stability | SLA Coverage | Suitable for Production? |
|-----------------|-------------------|----------|--------------|--------------------------|
| **Private Preview** | Selected users (NDA) | Low | ❌ No | ❌ No |
| **Public Preview** | All customers | Medium | ❌ No | ⚠️ Cautiously |
| **General Availability (GA)** | All customers | High | ✅ Yes | ✅ Yes |

---

# 🏷️ Azure Storage Access Tiers

Azure Storage offers different **Access Tiers** to optimize **cost** and **performance** based on data access patterns.  
The available tiers are:  
- **Hot** 🔥 (Frequent Access)  
- **Cool** ❄️ (Infrequent Access)  
- **Archive** 📦 (Rare Access)  

---

## 📌 **Azure Storage Access Tiers Overview**
| Tier     | Use Case                     | Storage Cost 💰 | Access Cost 🔄 | Retrieval Time ⏳ |
|----------|------------------------------|---------------|--------------|----------------|
| **Hot** 🔥  | Frequently accessed data     | High          | Low          | Instant        |
| **Cool** ❄️ | Infrequently accessed data   | Medium        | Medium       | Instant        |
| **Archive** 📦 | Rarely accessed data       | Low           | High         | Hours (up to 15h) |

---

## 🔥 **Hot Tier**
- Designed for **frequent access**.  
- Best for **active data**, **real-time analytics**, and **transactional workloads**.  
- **Lower access costs**, but **higher storage costs**.  

✅ **Use Cases:**  
✔ Web applications  
✔ Databases  
✔ Frequently accessed logs  

---

## ❄️ **Cool Tier**
- Optimized for **infrequent access** (data not needed daily).  
- **Lower storage cost** than Hot, but **higher access cost**.  
- Data remains **immediately available**.  

✅ **Use Cases:**  
✔ Backup & disaster recovery  
✔ Media storage  
✔ Long-term logs  

---

## 📦 **Archive Tier**
- For **rarely accessed** data (e.g., compliance, legal records).  
- **Lowest storage cost**, but **highest access & retrieval cost**.  
- **Data retrieval takes hours** (up to **15 hours**).  

✅ **Use Cases:**  
✔ Long-term archival  
✔ Compliance & regulatory storage  
✔ Cold storage for backups  

---

## 🛠️ **Changing Access Tiers**
- You can manually **change tiers** using:  
  - **Azure Portal**  
  - **Azure CLI**  
  - **Azure PowerShell**  
  - **Azure Storage SDK**  
- Lifecycle policies can **automatically move** data between tiers based on usage.  

---

## 🚀 **Azure Blob Storage Lifecycle Management**
- Automate tier transitions based on **rules** (e.g., move to Cool after 30 days).  
- Reduce storage costs **without manual intervention**.  

Example policy (JSON format):

```json
{
  "rules": [
    {
      "name": "MoveToCoolTier",
      "enabled": true,
      "type": "Lifecycle",
      "definition": {
        "actions": {
          "baseBlob": {
            "tierToCool": { "daysAfterModificationGreaterThan": 30 }
          }
        }
      }
    }
  ]
}
```

## 🔍 Comparison of Azure Storage Tiers

| Feature             | Hot 🔥          | Cool ❄️         | Archive 📦       |
|---------------------|----------------|----------------|----------------|
| **Best for**       | Frequent access | Infrequent access | Rare access |
| **Storage Cost**   | High 💰         | Medium 💰       | Low 💰       |
| **Access Cost**    | Low 💵          | Medium 💵       | High 💵      |
| **Data Availability** | Instant ⚡    | Instant ⚡      | Hours (up to 15h) ⏳ |
| **Minimum Retention** | No minimum  | 30 days        | 180 days     |

----

# 🔄 Azure Storage Data Redundancy

Azure provides multiple **data redundancy options** to ensure **high availability**, **durability**, and **disaster recovery**.  
These options define **how and where** data is replicated across different locations.

---

## 📌 **Types of Azure Storage Redundancy**
Azure offers **four** redundancy options:

| Redundancy Type       | Copies of Data | Region Scope | Protection Against |
|----------------------|--------------|--------------|-------------------|
| **LRS** (Locally Redundant Storage) | 3 | Single Data Center | Hardware failures |
| **ZRS** (Zone-Redundant Storage) | 3 | Availability Zones | Data Center failures |
| **GRS** (Geo-Redundant Storage) | 6 | Secondary Region | Regional failures |
| **GZRS** (Geo-Zone-Redundant Storage) | 6 | Availability Zones + Secondary Region | Zone & Regional failures |

---

## 🔹 **1. Locally Redundant Storage (LRS)**
✅ **Stores 3 copies** of data **within a single data center**.  
✅ Protects against **hardware failures** (e.g., disk crashes).  
❌ **No protection** against data center failures.  
❌ **Cheapest option**, but limited durability.  

**Use Case:** Cost-effective storage for **non-critical workloads**.  

---

## 🔹 **2. Zone-Redundant Storage (ZRS)**
✅ **Stores 3 copies** across **different Availability Zones** within the same region.  
✅ Protects against **data center failures**.  
✅ Ensures **higher availability** than LRS.  
❌ **No cross-region backup**.  

**Use Case:** Critical apps needing **high availability** within a single region.  

---

## 🔹 **3. Geo-Redundant Storage (GRS)**
✅ **Stores 6 copies** (3 in the primary region + 3 in a secondary region).  
✅ **Secondary region** is hundreds of miles away.  
✅ Provides **disaster recovery** in case of a **regional outage**.  
❌ Secondary copies **read-only** until failover.  

**Use Case:** Business continuity and **disaster recovery**.  

---

## 🔹 **4. Geo-Zone-Redundant Storage (GZRS)**
✅ **Combines ZRS & GRS**: Stores **3 copies across Availability Zones** + **3 more in a secondary region**.  
✅ **Highest durability** with **zone + regional protection**.  
✅ Secondary region available for **failover**.  

**Use Case:** Mission-critical apps requiring **maximum availability & disaster recovery**.  

---

## 🔍 **Comparison of Azure Storage Redundancy Options**
| Feature         | **LRS** 🔹 | **ZRS** 🏢 | **GRS** 🌍 | **GZRS** 🌎 |
|---------------|-----------|-----------|-----------|-----------|
| **Replication** | 3 copies in 1 data center | 3 copies across 3 zones | 6 copies (3 local + 3 in another region) | 6 copies (ZRS + GRS) |
| **Availability Zone Protection** | ❌ No | ✅ Yes | ❌ No | ✅ Yes |
| **Region Failover Protection** | ❌ No | ❌ No | ✅ Yes | ✅ Yes |
| **Read Access to Secondary Region** | ❌ No | ❌ No | ❌ No (except RA-GRS) | ❌ No (except RA-GZRS) |
| **Use Case** | Low-cost, non-critical | High availability, zone failure | Disaster recovery | Maximum resilience |

---

## 🔄 **Read-Access Geo-Redundant Storage (RA-GRS & RA-GZRS)**
RA-GRS & RA-GZRS allow **read-only access** to the secondary region **before failover**.  
🔹 Useful for **global applications** needing **read access** from multiple regions.  
🔹 Enables **faster disaster recovery**.  

---

## 🚀 **Choosing the Right Redundancy**
| **If you need...** | **Choose** |
|-------------------|------------|
| Cheapest storage with basic protection | **LRS** |
| High availability within a region | **ZRS** |
| Disaster recovery with geo-redundancy | **GRS** |
| Maximum protection with zone + geo redundancy | **GZRS** |

---
