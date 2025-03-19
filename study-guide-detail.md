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
- Describe availability zones
- Describe Azure datacenters
- Describe Azure resources and resource groups
- Describe subscriptions
- Describe management groups
- Describe the hierarchy of resource groups, subscriptions, and management groups

### Describe Azure Compute and Networking Services

- Compare compute types, including containers, virtual machines, and functions
- Describe virtual machine options, including:
  - Azure Virtual Machines
  - Azure Virtual Machine Scale Sets
  - Availability sets
  - Azure Virtual Desktop
- Describe the resources required for virtual machines
- Describe application hosting options, including:
  - Web apps
  - Containers
  - Virtual machines
- Describe virtual networking, including:
  - Purpose of Azure virtual networks
  - Azure virtual subnets
  - Peering
  - Azure DNS
  - Azure VPN Gateway
  - ExpressRoute
- Define public and private endpoints

### Describe Azure Storage Services

- Compare Azure Storage services
- Describe storage tiers
- Describe redundancy options
- Describe storage account options and storage types
- Identify options for moving files, including:
  - AzCopy
  - Azure Storage Explorer
  - Azure File Sync
- Describe migration options, including:
  - Azure Migrate
  - Azure Data Box

### Describe Azure Identity, Access, and Security

- Describe directory services in Azure, including:
  - Microsoft Entra ID
  - Microsoft Entra Domain Services
- Describe authentication methods in Azure, including:
  - Single sign-on (SSO)
  - Multi-factor authentication (MFA)
  - Passwordless authentication
- Describe external identities in Azure, including:
  - Business-to-business (B2B)
  - Business-to-customer (B2C)
- Describe Microsoft Entra Conditional Access
- Describe Azure role-based access control (RBAC)
- Describe the concept of Zero Trust
- Describe the purpose of the defense-in-depth model
- Describe the purpose of Microsoft Defender for Cloud

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
