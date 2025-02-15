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
