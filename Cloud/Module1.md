# **Module I: Cloud Computing Overview**

Topics to cover:

* Origins of Cloud Computing
* Cloud Components
* Essential Characteristics

  * On-demand self-service
  * Broad network access
  * Location-independent resource pooling
  * Rapid elasticity
  * Measured service
* Comparing cloud providers with traditional IT service providers
* Roots of cloud computing

---

# 1. Origins of Cloud Computing

Cloud computing did not start as “cloud.” It evolved gradually.

## Phase 1: Mainframe Computing (1960s–80s)

* One large central computer
* Many users accessed through terminals
* Very expensive
* Shared usage concept started here

This introduced the idea of **shared computing resources**.

---

## Phase 2: Client–Server Model (1990s)

* Personal computers connected to central servers
* Applications hosted on company-owned servers
* Infrastructure maintained internally

Problem:

* High cost
* Scaling difficult
* Hardware maintenance required

---

## Phase 3: Grid Computing

* Multiple computers connected to solve large problems
* Distributed workloads across systems
* Used in research and scientific computation

Introduced idea of:

> Distributed resource usage

---

## Phase 4: Utility Computing

Concept:

> Computing as a utility like electricity.

You pay for:

* CPU usage
* Storage
* Bandwidth

This became the billing foundation of cloud.

---

## Phase 5: Modern Cloud (2006 onwards)

When companies like:

* Amazon launched infrastructure services
* Microsoft launched Azure
* Google expanded cloud platform

Infrastructure became:

* On-demand
* Internet-based
* Scalable
* Pay-per-use

---

# 2. Roots of Cloud Computing

Cloud computing is built on several core technologies.

## 1. Virtualization

Most important root.

Allows:

* One physical server → multiple virtual machines
* Better hardware utilization
* Isolation between users

Without virtualization, cloud would not scale economically.

---

## 2. Distributed Computing

Workload split across multiple systems.

Used for:

* Big data processing
* Large-scale applications
* High availability systems

---

## 3. Networking & Internet

High-speed internet made remote infrastructure usable.

Without global internet:
Cloud cannot function.

---

## 4. Service-Oriented Architecture (SOA)

Applications delivered as services over network.

Cloud extends this idea.

---

## 5. Data Center Engineering

Large-scale server farms with:

* Power redundancy
* Cooling systems
* High-speed fiber connectivity

---

# 3. Cloud Components

Cloud computing has multiple structural components.

---

## 1. Front-End

This is what the user interacts with.

Includes:

* Web browser
* Mobile apps
* APIs
* Command-line tools

Example:
When you log into AWS console → that’s frontend.

---

## 2. Back-End

The actual infrastructure inside cloud provider.

Includes:

* Servers
* Storage systems
* Databases
* Hypervisors
* Networking devices

Users do not see this layer directly.

---

## 3. Cloud Infrastructure

Core infrastructure includes:

* Physical servers
* Virtual machines
* Containers
* Load balancers
* Virtual networks
* Storage systems

This layer handles:

* Computation
* Storage
* Networking
* Resource allocation

---

## 4. Management & Automation Layer

Cloud providers use automation to:

* Provision VMs
* Allocate storage
* Monitor usage
* Handle scaling
* Manage billing

This is what makes cloud “automatic.”

---

# 4. Essential Characteristics of Cloud Computing

These characteristics differentiate cloud from traditional IT.

---

## 1. On-Demand Self-Service

Users can:

* Create VM
* Allocate storage
* Deploy database

Without contacting provider.

Provisioning is automated.

Skill perspective:
This means infrastructure becomes programmable.

---

## 2. Broad Network Access

Resources accessible through:

* Internet
* APIs
* Mobile devices
* Web browsers

Cloud is location-independent in access.

This allows:

* Remote work
* Global applications
* Multi-device integration

---

## 3. Location-Independent Resource Pooling

Cloud provider pools resources for multiple customers.

Important concept:
**Multi-tenancy**

* Physical hardware shared
* Virtual machines isolated
* User unaware of exact physical location

Example:
You deploy a VM in “Asia region” but don’t know exact rack/server.

This improves:

* Efficiency
* Cost optimization
* Utilization rates

---

## 4. Rapid Elasticity

Resources can scale:

* Up (increase CPU/RAM)
* Out (add more instances)

Automatically or manually.

This enables:

* Handling traffic spikes
* Seasonal demand
* High-performance computing

Key idea:
Capacity appears “unlimited” to user.

---

## 5. Measured Service

Cloud monitors resource usage.

Billing based on:

* Compute hours
* Storage GB
* Data transfer
* API calls

This introduces:

* Cost transparency
* Usage accountability
* Operational flexibility

---

# 5. Comparing Cloud Providers with Traditional IT Service Providers

Let’s analyze structurally.

---

## Traditional IT Service Providers

They typically:

* Sell hardware
* Provide on-premise installation
* Require long-term contracts
* High upfront capital investment
* Manual scaling

Customer responsible for:

* Maintenance
* Updates
* Hardware replacement
* Security patches

Scaling requires:

* Purchasing new servers
* Installation time
* Downtime risk

---

## Cloud Service Providers

They provide:

* Infrastructure as a service
* Platform services
* Software services

Advantages:

* No hardware purchase
* No maintenance burden
* Instant provisioning
* Global infrastructure
* Usage-based pricing

Operational model:

* Operational expenditure (OpEx)
  Instead of:
* Capital expenditure (CapEx)

---

## Key Structural Differences

| Factor        | Traditional IT | Cloud         |
| ------------- | -------------- | ------------- |
| Investment    | High upfront   | Pay-as-you-go |
| Scaling       | Slow           | Instant       |
| Maintenance   | Customer       | Provider      |
| Accessibility | Limited        | Global        |
| Automation    | Low            | High          |

---

# 6. How All These Concepts Connect

Cloud computing =

Virtualization

* Distributed systems
* Internet-based delivery
* Utility pricing
* Automated management

All combined into one model.

---
