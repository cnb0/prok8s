### 1. Introduction To Cloud Native

            Distributed Systems
            Fallacies of Distributed Systems
            CAP Theorem
            The Twelve-Factor App
            Availability and Service-Level Agreements
          
### 2. Fundamentals
           
            Containers
            Container Isolation Levels
            Container Orchestration
            Kubernetes Overview
            Kubernetes and Containers
            Serverless Computing
            Functions
            From VMs to Cloud Native
            Lift-and-Shift
            Application Modernization
            Application Optimization
            Microservices
            Benefits of a Microservices Architecture
            Challenges with a Microservices Architecture
          
### 3. Designing Cloud Native Applications
           
            Fundamentals of Cloud Native Applications
            Operational Excellence
            Security
            Reliability and Availability
            Scalability and Cost
            Cloud Native versus Traditional Architectures
            Functions versus Services
            Function Scenarios
            Considerations for Using Functions
            Composite of Functions and Services
            API Design and Versioning
            API Backward and Forward Compatibility
            Semantic Versioning
            Service Communication
            Protocols
            Messaging Protocols
            Serialization Considerations
            Idempotency
            Request/Response
            Publisher/Subscriber
            Choosing Between Pub/Sub and Request Response
            Synchronous versus Asynchronous
            Gateways
            Routing
            Aggregation
            Offloading
            Implementing Gateways
            Egress
            Service Mesh
            Example Architecture
          
### 4. Working With Data
           
            Data Storage Systems
            Objects, Files, and Disks
            Databases
            Streams and            s
            Blockchain
            Selecting a Datastore
            Data in Multiple Datastores
            Change Data Capture
            Write Changes as an Event to a Change Log
            Transaction Supervisor
            Compensating Transactions
            Extract, Transform, and Load
            Microservices and Data Lakes
            Client Access to Data
            Restricted Client Tokens (Valet-Key)
            Database Services with Fine-Grained Access Control
            GraphQL Data Service
            Fast Scalable Data
            Sharding Data
            Caching Data
            Content Delivery Networks
            Analyzing Data
            Streams
            Batch
            Data Lakes on Object Storage
            Data Lakes and Data Warehouses
            Distributed Query Engines
            Databases on Kubernetes
            Storage Volumes
            StatefulSets
            DaemonSets
          
### 5. DevOps

            What Is DevOps?
            Collaboration
            Automation
            Lean Principles and Processes
            Measurement
            Sharing
            Testing
            Test Doubles
            Test Automation Pyramid
            When to Run Which Types of Tests
            Testing Cadence
            Testing in Production
            Development Environments and Tools
            Development Tools
            Development Environments
            Local Development Environments
            Local Development with a Remote Cluster
            Skaffold Development Workflow
            Remote Cluster Routed to Local Development
            Cloud Development Environments
            CI/CD
            Source Code Control
            Build Stage (CI)
            Test Stage (CI)
            Deploy Stage (CD)
            Release Stage (CD)
            Post-Release Stage
            Monitoring
            Collecting Metrics
            Observable Services
            Configuration Management
            Single-Environment Variable
            Multiple-Environment Variables
            Adding ConfigMap Data to a Volume
            Storing Secrets
            Deployment Configuration
            Sample CI/CD Flows
          
### 6. Best Practices
           

            Moving to Cloud Native
            Breaking Up the Monolith for the Right Reasons
            Decouple Simple Services First
            Learn to Operate on a Small Scale
            Use an Anticorruption Layer Pattern
            Use a Strangler Pattern
            Come Up with a Data Migration Strategy
            Rewrite Any Boilerplate Code
            Reconsider Frameworks, Languages, Data Structures, and Datastores
            Retire Code
            Ensuring Resiliency
            Handle Transient Failures with Retries
            Use a Finite Number of Retries
            Use Circuit Breakers for Nontransient Failures
            Graceful Degradation
            Use a Bulkhead Pattern
            Implement Health Checks and Readiness Checks
            Define CPU and Memory Limits for Your Containers
            Implement Rate Limiting and Throttling
            Ensuring Security
            Treat Security Requirements the Same as Any Other Requirements
            Incorporate Security in Your Designs
            Grant Least-Privileged Access
            Use Separate Accounts/Subscriptions/Tenants
            Securely Store All Secrets
            Obfuscate Data
            Encrypt Data in Transit
            Use Federated Identity Management
            Use Role-Based Access Control
            Isolate Kubernetes Pods
            Working with Data
            Use Managed Databases and Analytics Services
            Use a Datastore That Best Fits Data Requirements
            Keep Data in Multiple Regions or Zones
            Use Data Partitioning and Replication for Scale
            Avoid Overfetching and Chatty I/O
            Don’t Put Business Logic in the Database
            Test with Production-like Data
            Handle Transient Failures
            Performance and Scalability
            Design Stateless Services That Scale Out
            Use Platform Autoscaling Features
            Use Caching
            Use Partitioning to Scale Beyond Service Limits
            Functions
            Write Single-Purpose Functions
            Don’t Chain Functions
            Keep Functions Light and Simple
            Make Functions Stateless
            Separate Function Entry Point from the Function Logic
            Avoid Long-Running Functions
            Use queues for Cross-Function Communication
            Operations
            Deployments and Releases Are Separate Activities
            Keep Deployments Small
            CI/CD Definition Lives with the Component
            Consistent Application Deployment
            Use Zero-Downtime Releases
            Don’t Modify Deployed Infrastructure
            Use Containerized Build
            Describe Infrastructure Using Code
            Use Namespaces to Organize Services in Kubernetes
            Isolate the Environments
            Separate Function Source Code
            Correlate Deployments with Commits
            Logging, Monitoring, and Alerting
            Use a Unified Logging System
            Use Correlation IDs
            Include Context with Log Entries
            Common and Structured Logging Format
            Tag Your Metrics Appropriately
            Avoid Alert Fatigue
            Define and Alert on Key Performance Indicators
            Continuous Testing in Production
            Start with Basic Metrics
            Service Communication
            Design for Backward and Forward Compatibility
            Define Service Contracts That Do Not Leak Internal Details
            Prefer Asynchronous Communication
            Use Efficient Serialization Techniques
            Use   queues or Streams to Handle Heavy Loads and Traffic Spikes
            Batch Requests for Efficiency
            Split Up Large Messages
            Containers
            Store Images in a Trusted Registry
            Utilize the Docker Build Cache
            Don’t Run Containers in Privileged Mode
            Use Explicit Container Image Tags
            Keep Container Images Small
            Run One Application per Container
            Use Verified Images from Trusted Repositories
            Use Vulnerability Scanning Tools on Images
            Don’t Store Data in Containers
            Never Store Secrets or Configuration Inside an Image
          
### 7. Portability
           
            Why Make Applications Portable?
            The Costs of Portability
            Data Gravity and Portability
            When and How to Implement Portability
            Standardized Interfaces
            Common Services and Features
            Abstractions and Layers
            Managed Services from Other Vendors
            Portability Tooling
            Kubernetes as a Portability Layer