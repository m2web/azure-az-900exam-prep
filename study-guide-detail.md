# Skills Details

## Describe Cloud Concepts (25–30%)

### Describe Cloud Computing

- Define cloud computing - Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the internet (“the cloud”) to offer faster innovation, flexible resources, and economies of scale. Instead of owning their own computing infrastructure or data centers, companies can rent access to anything from applications to storage from a cloud service provider.
- Describe the shared responsibility model - The shared responsibility model in cloud computing delineates the responsibilities of the cloud service provider and the customer. In this model: `Cloud Provider`: Responsible for the security of the cloud infrastructure, including hardware, software, networking, and facilities. `Customer`: Responsible for securing their data, managing user access, and configuring security settings within the cloud environment.
- Define cloud models, including public, private, and hybrid - `Public Cloud`: Services are delivered over the public internet and shared across multiple organizations. Examples include Microsoft Azure, AWS, and Google Cloud. `Private Cloud`: Services are maintained on a private network and used exclusively by a single organization. This model offers greater control and security. `Hybrid Cloud`: Combines public and private clouds, allowing data and applications to be shared between them. This model provides greater flexibility and optimization of existing infrastructure, security, and compliance.
- Identify appropriate use cases for each cloud model - `Public Cloud`: Ideal for workloads with variable or unpredictable demand, such as web applications, development and testing environments, and big data analytics. `Private Cloud`: Suitable for organizations with strict regulatory or compliance requirements, sensitive data, or those needing high performance and control, such as financial institutions and government agencies. `Hybrid Cloud`: Best for businesses that need to balance between scalability and control, such as those with legacy systems that need to be integrated with cloud services or those requiring disaster recovery solutions.
- Describe the consumption-based model - In a consumption-based model, customers pay only for the cloud resources they use, similar to utility billing. This model allows for cost efficiency and scalability, as businesses can scale resources up or down based on demand without incurring costs for unused capacity.
- Compare cloud pricing models - `Pay-as-you-go`: Charges based on actual usage of resources. Ideal for variable workloads. `Reserved Instances`: Offers a discount for committing to use a certain amount of resources over a specified period. Suitable for predictable workloads. `Spot Instances`: Provides access to unused cloud capacity at reduced rates. Best for flexible, non-critical workloads that can tolerate interruptions.
- Describe serverless - Serverless computing allows developers to build and run applications without managing the underlying infrastructure. The cloud provider automatically provisions, scales, and manages the infrastructure required to run the code. Examples include Azure Functions and AWS Lambda. Serverless is ideal for event-driven applications, microservices, and applications with unpredictable scaling needs.

### Describe the Benefits of Using Cloud Services

- Describe the benefits of high availability and scalability in the cloud - `High Availability` ensures that cloud services are accessible and operational even in the event of hardware failures or other disruptions. This is achieved through redundancy and failover mechanisms. The benefits include: `Minimized Downtime`: Ensures continuous access to applications and services. `Improved User Experience`: Reliable access to services enhances user satisfaction. `Scalability` allows cloud resources to be adjusted dynamically based on demand. The benefits include: `Cost Efficiency`: Pay only for the resources you use, scaling up or down as needed. `Flexibility`: Easily accommodate growth or changes in workload without manual intervention.
- Describe the benefits of reliability and predictability in the cloud - `Reliability` in the cloud means consistent performance and uptime. The benefits include:
`Consistent Performance`: Ensures applications run smoothly without interruptions. `Trust`: Builds confidence in the service's ability to meet business needs. `Predictability` refers to the ability to forecast costs and performance. The benefits include: `Budget Management`: Easier to plan and manage expenses with predictable billing. `Performance Assurance`: Predictable performance helps in planning and optimizing workloads.
- Describe the benefits of security and governance in the cloud `Security` in the cloud involves protecting data and applications from threats. The benefits include: `Data Protection`: Advanced security measures safeguard sensitive information. `Compliance`: Helps meet regulatory requirements and industry standards. `Governance` ensures that cloud resources are used in accordance with policies and regulations. The benefits include: `Policy Enforcement`: Ensures adherence to organizational policies. `Risk Management`: Helps identify and mitigate risks associated with cloud usage.
- Describe the benefits of manageability in the cloud - `Manageability` refers to the ease of managing and maintaining cloud resources. The benefits include:
`Simplified Administration`: Centralized management tools streamline operations. `Automation`: Automated processes reduce manual intervention and errors. `Monitoring and Reporting`: Real-time insights into resource usage and performance help optimize operations.

### Describe Cloud Service Types

- Describe infrastructure as a service (IaaS) - Infrastructure as a Service (IaaS) provides virtualized computing resources over the internet. It offers fundamental building blocks such as virtual machines, storage, and networking, allowing users to rent and manage these resources as needed. IaaS is highly scalable and flexible, enabling businesses to avoid the costs and complexities of buying and managing physical servers.
- Describe platform as a service (PaaS) - Platform as a Service (PaaS) provides a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. PaaS includes services like operating systems, databases, development tools, and middleware. It simplifies the development process by handling infrastructure management, allowing developers to focus on writing code and deploying applications.
- Describe software as a service (SaaS) - Software as a Service (SaaS) delivers software applications over the internet on a subscription basis. Users can access these applications via a web browser without needing to install or maintain the software. SaaS providers handle all aspects of the application, including security, availability, and performance. Examples include email services, customer relationship management (CRM) systems, and collaboration tools.
- Identify appropriate use cases for each cloud service type (IaaS, PaaS, and SaaS):
- `IaaS`:
  - `Use Case`: Hosting websites and web applications, providing virtual data centers, disaster recovery, and development and testing environments.
  - `Example`: A company needs scalable infrastructure to host its e-commerce platform.

- `PaaS`:
  - `Use Case`: Developing and deploying web and mobile applications, integrating with databases, and automating workflows.
  - `Example`: A development team wants to build and deploy a new application quickly without managing the underlying infrastructure.

- `SaaS`:
  - `Use Case`: Providing business applications such as email, CRM, and collaboration tools to end-users.
  - `Example`: An organization uses a cloud-based CRM system to manage customer interactions and sales processes.

## Describe Azure Architecture and Services (35–40%)

### Describe the Core Architectural Components of Azure

- Describe Azure regions, region pairs, and sovereign regions
    **Azure Regions** are geographical areas containing one or more datacenters. They allow you to deploy resources close to your users to reduce latency and meet compliance requirements.
	  **Region Pairs** consist of two regions within the same geography, providing redundancy and disaster recovery. They offer benefits like prioritized recovery, staggered updates, and physical isolation.
	  **Sovereign Regions** are special regions operated by sovereign entities to meet specific compliance and legal requirements. Examples include Azure Government regions in the US and Azure China regions.
- Describe availability zones - `Availability Zones` are physically separate locations within an Azure region. Each zone has independent power, cooling, and networking to ensure high availability and resilience. They are designed to protect applications and data from datacenter failures.
- Describe Azure datacenters - `Azure Datacenters` are physical facilities that house the infrastructure supporting Azure services. They are strategically located around the world to provide global coverage, redundancy, and compliance with local regulations.
- Describe Azure resources and resource groups
    **Azure Resources** are instances of services you can create in Azure, such as virtual machines, storage accounts, and databases.
	  **Resource Groups** are containers that hold related resources for an Azure solution. They help manage and organize resources that share the same lifecycle, making it easier to deploy, update, and delete them as a group.
- Describe subscriptions - `Subscriptions` are agreements with Microsoft to use Azure services. They provide a way to manage billing, access, and resource quotas. Each subscription is associated with a specific Azure account and can contain multiple resource groups.
- Describe management groups - `Management Groups` are containers that help you manage access, policies, and compliance across multiple Azure subscriptions. They provide a hierarchical structure for organizing subscriptions and applying governance rules.
- Describe the hierarchy of resource groups, subscriptions, and management groups - The hierarchy in Azure is as follows:
    **Management Groups**: At the top level, they help manage multiple subscriptions.
    **Subscriptions**: Under management groups, they logically associate user accounts with resources.
    **Resource Groups**: Within subscriptions, they organize resources that share the same permissions and policies.
    **Resources**: The individual instances of services within resource groups.

### Describe Azure Compute and Networking Services

- Compare compute types, including containers, virtual machines, and functions
  - **Containers**: Lightweight, portable, and efficient, containers package applications and their dependencies together. They run consistently across different environments and are ideal for microservices and scalable applications.
  - **Virtual Machines (VMs)**: Provide full control over the operating system and environment. VMs are suitable for applications requiring specific OS configurations, legacy applications, and custom software.
  - **Functions**: Serverless compute service that runs code in response to events. Functions are ideal for event-driven applications, microservices, and background tasks.
- Describe virtual machine options, including:
  - **Azure Virtual Machines**: On-demand, scalable computing resources that provide full control over the OS and environment. Suitable for a wide range of applications.
  - **Azure Virtual Machine Scale Sets**: Manage and scale a group of load-balanced VMs. Automatically increase or decrease the number of VM instances in response to demand.
  - **Availability Sets**: Logical grouping of VMs to ensure high availability. Distributes VMs across multiple fault domains to protect against hardware failures.
  - **Azure Virtual Desktop**: Virtualized desktop and application service. Provides a secure, scalable, and cost-effective solution for remote work.
- Describe the resources required for virtual machines
  - **Compute**: CPU and memory resources.
  - **Storage**: Disk storage for the OS, applications, and data.
  - **Networking**: Virtual network, network interface cards (NICs), and public/private IP addresses.
- Describe application hosting options, including:
  - **Web Apps**: Managed service for hosting web applications, RESTful APIs, and mobile backends. Provides built-in scaling and high availability.
  - **Containers**: Run containerized applications using services like Azure Kubernetes Service (AKS) or Azure Container Instances. Offers portability and efficient resource utilization.
  - **Virtual Machines**: Host applications that require full control over the OS and environment. Suitable for custom software and legacy applications.
- Describe virtual networking, including:
  - Purpose of Azure virtual networks - Provides a secure, isolated environment for Azure resources to communicate with each other, the internet, and on-premises networks
  - Azure virtual subnets - Subdivisions of a virtual network, allowing you to segment and organize resources.
  - Peering - Connects two or more virtual networks, enabling them to communicate as if they were on the same network.
  - Azure DNS - Provides domain name resolution for Azure resources, enabling them to communicate using domain names instead of IP addresses.
  - Azure VPN Gateway - Establishes secure, cross-premises connectivity between Azure and on-premises networks using IPsec/IKE VPN tunnels.
  - ExpressRoute - Provides a private, dedicated connection between Azure and on-premises networks, bypassing the public internet for enhanced security and reliability.
- Define public and private endpoints
  - **Public Endpoints**: Accessible over the internet, allowing resources to communicate with external clients.
  - **Private Endpoints**: Use private IP addresses within a virtual network, providing secure connectivity to Azure services without exposing them to the public internet.

### Describe Azure Storage Services

- Compare Azure Storage services
  - **Azure Blob Storage**: Massively scalable object storage for text and binary data. Ideal for storing unstructured data like documents, images, and videos [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).
  - **Azure Files**: Managed file shares that can be accessed via SMB and NFS protocols. Suitable for shared storage scenarios [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).
  - **Azure Queues**: Messaging store for reliable messaging between application components [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).
  - **Azure Tables**: NoSQL store for schemaless storage of structured data [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).
  - **Azure Managed Disks**: Block-level storage volumes for Azure VMs [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).

- Describe storage tiers
  - **Hot Tier**: Optimized for data that is accessed or modified frequently. Highest storage costs, lowest access costs [2](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview).
  - **Cool Tier**: Optimized for data that is infrequently accessed or modified. Lower storage costs, higher access costs compared to the hot tier [2](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview).
  - **Cold Tier**: Optimized for data that is rarely accessed but requires fast retrieval. Lower storage costs, higher access costs compared to the cool tier [2](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview).
  - **Archive Tier**: Optimized for data that is rarely accessed and has flexible latency requirements. Lowest storage costs, highest access costs [2](https://learn.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview).

- Describe redundancy options
  - **Locally Redundant Storage (LRS)**: Replicates data within a single datacenter. Least expensive option [3](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy).
  - **Zone-Redundant Storage (ZRS)**: Replicates data across multiple availability zones within a region [3](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy).
  - **Geo-Redundant Storage (GRS)**: Replicates data to a secondary region, providing protection against regional outages [3](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy).
  - **Read-Access Geo-Redundant Storage (RA-GRS)**: Provides read access to data in the secondary region [3](https://learn.microsoft.com/en-us/azure/storage/common/storage-redundancy).

- Describe storage account options and storage types
  - **Standard General-Purpose v2 (GPv2)**: Supports blobs, files, queues, and tables. Recommended for most scenarios [4](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview).
  - **Premium Block Blobs**: Optimized for high transaction rates and low latency [4](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview).
  - **Premium File Shares**: Supports SMB and NFS file shares. Suitable for high-performance applications[4](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview).
  - **Premium Page Blobs**: Optimized for page blobs only [4](https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview).

- Identify options for moving files, including:
  - **AzCopy**: Command-line utility for copying files to and from Azure Storage [5](https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-files).
  - **Azure Storage Explorer**: GUI tool for managing Azure Storage resources [1](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction).
  - **Azure File Sync**: Synchronizes Azure file shares with on-premises servers [6](https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-overview).

- Describe migration options, including:
  - **Azure Migrate**: Service for discovering, assessing, and migrating on-premises workloads to Azure [7](https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview).
  - **Azure Data Box**: Physical devices for transferring large amounts of data to Azure [8](https://techcommunity.microsoft.com/blog/itopstalkblog/how-to-use-azure-data-box-for-migrations/1177156).

### Describe Azure Identity, Access, and Security

- Describe directory services in Azure, including:
  - Microsoft Entra ID - Microsoft Entra ID (formerly Azure Active Directory) is a cloud-based identity and access management service. It helps employees sign in and access resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications. It provides features like single sign-on (SSO), multi-factor authentication (MFA), and conditional access to secure and manage identities [1](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id).
  - Microsoft Entra Domain Services - Microsoft Entra Domain Services provides managed domain services such as domain join, group policy, LDAP, and Kerberos/NTLM authentication without the need to deploy, manage, and patch domain controllers in the cloud. It allows you to lift and shift legacy applications to Azure without managing the underlying infrastructure [2](https://learn.microsoft.com/en-us/entra/identity/domain-services/overview) [3](https://azure.microsoft.com/en-us/products/microsoft-entra-ds/).
- Describe authentication methods in Azure, including:
  - Single sign-on (SSO) - Single sign-on (SSO) is an authentication method that allows users to log in with a single set of credentials to access multiple applications. It simplifies the user experience by reducing the number of times users need to log in and enhances security by centralizing authentication [4](https://en.wikipedia.org/wiki/Single_sign-on) [5](https://www.onelogin.com/learn/how-single-sign-on-works).
  - Multi-factor authentication (MFA) - Multi-factor authentication (MFA) requires users to provide two or more verification factors to gain access to a resource. This could include something they know (password), something they have (smartphone), or something they are (fingerprint). MFA adds an extra layer of security to the authentication process [6](https://support.microsoft.com/en-us/topic/what-is-multifactor-authentication-e5e39437-121c-be60-d123-eda06bddf661) [7](https://en.wikipedia.org/wiki/Multi-factor_authentication).
  - Passwordless authentication - Passwordless authentication verifies a user's identity without requiring a password. Common methods include biometric authentication (fingerprint or facial recognition), hardware tokens, and magic links sent to an email or phone. This method reduces the risk of password-related attacks and improves user experience [8](https://auth0.com/blog/what-is-passwordless-authentication/) [9](https://www.microsoft.com/en-us/security/business/solutions/passwordless-authentication).

- Describe external identities in Azure, including:
  - Business-to-business (B2B) - Business-to-business (B2B) allows organizations to securely share their applications and services with guest users from any other organization while maintaining control over their own corporate data. B2B collaboration enables external partners to use their own credentials to access resources [10](https://www.investopedia.com/terms/b/btob.asp) [11](https://businessmodelanalyst.com/business-to-business-b2b/).
  - Business-to-customer (B2C) - Business-to-customer (B2C) is a service that enables businesses to provide identity and access management solutions to their customers. It allows customers to sign up and sign in using their preferred social, enterprise, or local account identities [12](https://www.investopedia.com/terms/b/btoc.asp) [13](https://www.shopify.com/blog/what-is-business-to-consumer-b2c-definition-and-guide).

- Describe Microsoft Entra Conditional Access - Microsoft Entra Conditional Access is a tool used to enforce organizational policies based on identity-driven signals. It allows administrators to create policies that determine when and how users can access resources, using conditions such as user location, device state, and risk level. This helps balance security and productivity [15](https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview) [14](https://learn.microsoft.com/en-us/entra/identity/conditional-access/).
- Describe Azure role-based access control (RBAC) - Azure role-based access control (RBAC) is a system that provides fine-grained access management of Azure resources. It allows you to assign roles to users, groups, and applications, specifying what actions they can perform on specific resources. RBAC helps ensure that users have only the permissions they need to perform their tasks [16](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) [17](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles).
- Describe the concept of Zero Trust - Zero Trust is a security model that assumes breaches are inevitable and verifies each request as though it originates from an open network. It emphasizes verifying explicitly, using least privilege access, and assuming breach. Zero Trust protects user accounts, devices, applications, and data regardless of their location [18](https://learn.microsoft.com/en-us/security/zero-trust/zero-trust-overview) [19](https://en.wikipedia.org/wiki/Zero_trust_architecture).
- Describe the purpose of the defense-in-depth model - The defense-in-depth model is a security strategy that employs multiple layers of defense to protect information and resources. Each layer provides a different level of security, ensuring that if one layer is breached, others remain intact. This approach helps mitigate the risk of a single point of failure [18](https://learn.microsoft.com/en-us/security/zero-trust/zero-trust-overview).
- Describe the purpose of Microsoft Defender for Cloud - Microsoft Defender for Cloud is a security management tool that provides threat protection across your Azure, on-premises, and multi-cloud environments. It helps detect and respond to threats, provides security recommendations, and ensures compliance with security best practices [18](https://learn.microsoft.com/en-us/security/zero-trust/zero-trust-overview).

---

## Describe Azure Management and Governance (30–35%)

### Describe Cost Management in Azure

- Describe factors that can affect costs in Azure
- Compare the Pricing Calculator and the Total Cost of Ownership (TCO) Calculator
- Describe cost management capabilities in Azure
- Describe the purpose of tags

### Describe Features and Tools in Azure for Governance and Compliance

- Describe the purpose of Microsoft Purview in Azure
- Describe the purpose of Azure Policy
- Describe the purpose of resource locks

### Describe Features and Tools for Managing and Deploying Azure Resources

- Describe the Azure portal
- Describe Azure Cloud Shell, including:
  - Azure Command-Line Interface (CLI)
  - Azure PowerShell
- Describe the purpose of Azure Arc
- Describe infrastructure as code (IaC)
- Describe Azure Resource Manager (ARM) and ARM templates

### Describe Monitoring Tools in Azure

- Describe the purpose of Azure Advisor
- Describe Azure Service Health
- Describe Azure Monitor, including:
  - Log Analytics
  - Azure Monitor alerts
  - Application Insights
