# **Module III: Cloud Architecture – Layers and Models**

Topics:

* Layers in cloud architecture
* Software as a Service (SaaS) – features and benefits
* Platform as a Service (PaaS) – features and benefits
* Infrastructure as a Service (IaaS) – features and benefits
* Service providers
* Challenges and risks in cloud adoption
* Cloud deployment models:

  * Public cloud
  * Private cloud
  * Community cloud
  * Hybrid cloud
* Advantages of Cloud Computing

---

# 1. Layers in Cloud Architecture

Cloud architecture can be understood in layered form. Each layer builds on the layer below it.

---

## 1.1 Physical Layer (Infrastructure Layer)

This is the bottom-most layer.

Includes:

* Physical servers
* Storage systems
* Networking hardware
* Cooling and power systems
* Data center facilities

Owned and managed by cloud provider.

Users do not directly access this layer.

---

## 1.2 Virtualization Layer

This layer abstracts physical hardware.

Includes:

* Hypervisors (VMware, KVM, Hyper-V)
* Virtual machines
* Virtual storage
* Virtual networks

Purpose:

* Resource isolation
* Multi-tenancy
* Efficient utilization

This layer makes cloud scalable and economical.

---

## 1.3 Platform Layer

Provides:

* Operating systems
* Runtime environments
* Databases
* Middleware
* Development frameworks

Developers use this layer to build applications without managing hardware.

---

## 1.4 Application Layer

Top layer where:

* End-user applications run
* Business logic exists
* User interacts

Examples:

* CRM systems
* Email services
* ERP systems
* SaaS applications

---

## Layer Interaction Summary

Physical → Virtualized → Platform → Application

Each higher layer depends on services of lower layer.

---

# 2. Cloud Service Models

Cloud services are categorized into three main models.

These models define:

> Who manages what.

---

# 2.1 Infrastructure as a Service (IaaS)

IaaS provides:

* Virtual machines
* Storage
* Networking
* Load balancers

You manage:

* Operating system
* Applications
* Security configurations
* Runtime

Provider manages:

* Physical hardware
* Virtualization
* Data center operations

---

### Example Use Cases

* Hosting web servers
* Running custom applications
* Dev/test environments
* Disaster recovery

---

### Features of IaaS

* On-demand VM provisioning
* Elastic scaling
* Virtual networking
* Storage options
* API-based management

---

### Benefits of IaaS

* Full control over environment
* Flexible configuration
* No hardware investment
* Scalable infrastructure

---

### Responsibility Breakdown

Provider → Hardware
User → OS + Applications

---

# 2.2 Platform as a Service (PaaS)

PaaS provides:

* Runtime environment
* Middleware
* Database
* Development tools

You manage:

* Application code
* Application logic

Provider manages:

* Infrastructure
* OS
* Runtime
* Scaling

---

### Example Use Cases

* Web app development
* API development
* Microservices
* Application testing

---

### Features of PaaS

* Built-in scaling
* Integrated development tools
* Managed databases
* Continuous deployment support

---

### Benefits of PaaS

* Faster development
* No server management
* Reduced operational complexity
* Built-in security updates

---

### Responsibility Breakdown

Provider → Infrastructure + OS + Runtime
User → Application code

---

# 2.3 Software as a Service (SaaS)

SaaS provides:

* Complete applications over internet.

User only:

* Uses application.

Provider manages:

* Everything (infrastructure, platform, updates, security)

---

### Example Use Cases

* Email services
* CRM systems
* Project management tools
* Online collaboration tools

---

### Features of SaaS

* Web-based access
* Subscription model
* Automatic updates
* Multi-device accessibility

---

### Benefits of SaaS

* No installation required
* No maintenance
* Accessible from anywhere
* Lower upfront cost

---

### Responsibility Breakdown

Provider → Everything
User → Usage and configuration

---

# 3. Service Providers

Cloud service providers are organizations that offer:

* IaaS
* PaaS
* SaaS

They provide:

* Data center infrastructure
* Networking backbone
* Security frameworks
* Global availability

Major characteristics of providers:

* Global regions and availability zones
* SLA (Service Level Agreements)
* API-driven automation
* Compliance certifications

They compete on:

* Performance
* Pricing
* Service variety
* Ecosystem support

---

# 4. Challenges and Risks in Cloud Adoption

Moving to cloud introduces challenges.

---

## 4.1 Security Concerns

* Data breaches
* Misconfigurations
* Unauthorized access
* Insider threats

Improper configuration is major risk.

---

## 4.2 Vendor Lock-In

Applications tightly integrated with one provider may be hard to migrate.

---

## 4.3 Cost Management

Poor monitoring can cause:

* Unexpected billing
* Resource waste

---

## 4.4 Compliance & Legal Issues

Data residency requirements.
Regulatory restrictions.
Industry-specific compliance.

---

## 4.5 Downtime & Availability Risks

Cloud providers can have outages.
Applications must be designed for redundancy.

---

# 5. Cloud Deployment Models

Deployment model defines:

> Where infrastructure is hosted and who has access.

---

# 5.1 Public Cloud

Infrastructure:

* Owned by cloud provider
* Shared among multiple customers

Characteristics:

* Highly scalable
* Cost-effective
* No hardware ownership

Suitable for:

* Startups
* Web applications
* Dev/test environments

---

# 5.2 Private Cloud

Infrastructure:

* Dedicated to one organization
* Can be on-premise or hosted

Characteristics:

* Greater control
* Higher security
* Custom configurations

Used by:

* Banks
* Government agencies
* Large enterprises

---

# 5.3 Community Cloud

Infrastructure shared by:

* Multiple organizations
* Similar requirements

Example:

* Government departments
* Healthcare institutions

Shared costs.
Common compliance requirements.

---

# 5.4 Hybrid Cloud

Combination of:

* Public cloud
* Private cloud

Data or workloads distributed across both.

Example:
Sensitive data in private cloud.
Web application in public cloud.

Provides:

* Flexibility
* Cost optimization
* Security balance

---

# 6. Advantages of Cloud Computing

Module ends with advantages — let’s summarize properly.

---

## 6.1 Cost Efficiency

* No hardware purchase
* Operational expense model
* Pay-per-use billing

---

## 6.2 Scalability

* Elastic resource allocation
* Automatic scaling

---

## 6.3 High Availability

* Redundant infrastructure
* Multi-region deployments

---

## 6.4 Faster Deployment

* Resources provisioned instantly
* Reduced setup time

---

## 6.5 Accessibility

* Global access
* Remote collaboration support

---

## 6.6 Managed Infrastructure

* Automatic updates
* Patch management
* Reduced maintenance effort

---

# Integrated Understanding of Module III

Module III explains:

1. How cloud architecture is structured (layers)
2. How services are delivered (IaaS, PaaS, SaaS)
3. Who provides services (providers)
4. What risks exist during adoption
5. How cloud can be deployed (public, private, hybrid, community)
6. Why cloud is beneficial
