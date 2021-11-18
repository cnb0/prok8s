
1. To Kubernetes And Containers

                        
            The Evolution of Software Development
            Virtual Machines versus Containers
            Docker Basics
            What's behind docker run?
            Dockerfiles and Docker Images
            Exercise 1.01: Creating a Docker Image and Uploading It to Docker Hub
            Exercise 1.02: Running Your First Application in Docker
            The Essence of Linux Container Technology
            Namespace
            Exercise 1.03: Joining a Container to the Network Namespace of Another Container
            Cgroups
            Containerization: The Mindset Change
            Several Applications in One Container
            One Application in One Container
            A Comparison of These Approaches
            The Need for Container Orchestration
            Container Interactions
            Network and Storage
            Resource Management and Scheduling
            Failover and Recovery
            Scalability
            Service Exposure
            Delivery Pipeline
            Orchestrator: Putting All the Things Together
            Welcome to the Kubernetes World
            Activity 1.01: Creating a Simple Page Count Application
          
2. An Overview Of Kubernetes
         
                        
            Setting up Kubernetes
            An Overview of Minikube
            Exercise 2.01: Getting Started with Minikube and Kubernetes Clusters
            Kubernetes Components Overview
            etcd
            API Server
            Scheduler
            Controller Manager
            Where Is the kubelet?
            kube-proxy
            Kubernetes Architecture
            Container Network Interface
            Migrating Containerized Application to Kubernetes
            Pod Specification
            Applying a YAML Manifest
            Exercise 2.02: Running a Pod in Kubernetes
            Service Specification
            Exercise 2.03: Accessing a Pod via a Service
            Services and Pods
            Delivering Kubernetes-Native Applications
            Exercise 2.04: Scaling a Kubernetes Application
            Pod Life Cycle and Kubernetes Components
            Exercise 2.05: How Kubernetes Manages a Pod's Life Cycle
            Activity 2.01: Running the Pageview App in Kubernetes
            A Glimpse into the Advantages of Kubernetes for Multi-Node Clusters
          
3. Kubectl – Kubernetes Command Center
           
            How kubectl Communicates with Kubernetes
            Setting up Environments with Autocompletion and Shortcuts
            Exercise 3.01: Setting up Autocompletion
            Setting up the kubeconfig Configuration File
            Common kubectl Commands
            Frequently Used kubectl Commands to Create, Manage, and Delete Kubernetes Objects
            Walkthrough of Some Simple kubectl Commands
            Some Useful Flags for the get Command
            Populating Deployments in Kubernetes
            Exercise 3.02: Creating a Deployment
            Exercise 3.03: Updating a Deployment
            Exercise 3.04: Deleting a Deployment
            Activity 3.01: Editing a Live Deployment for a Real-Life Application
          
4. How To Communicate With Kubernetes (API Server)
         
            
            The Kubernetes API Server
            Kubernetes HTTP Request Flow
            Authentication
            Authorization
            Admission Control
            Exercise 4.01: Starting Minikube with a Custom Set of Modules
            Validation
            The Kubernetes API
            Tracing kubectl HTTP Requests
            API Resource Type
            Scope of API Resources
            Namespace-Scoped Resources
            Cluster-Scoped Resources
            API Groups
            Core Group
            Named Group
            System-Wide
            API Versions
            Exercise 4.02: Getting Information about API Resources
            How to Enable/Disable API Resources, Groups, or Versions
            Exercise 4.03: Enabling and Disabling API Groups and Versions on a Minikube Cluster
            Interacting with Clusters Using the Kubernetes API
            Accessing the Kubernetes API Server Using kubectl as a Proxy
            Creating Objects Using curl
            Exercise 4.04: Creating and Verifying a Deployment Using kubectl proxy and curl
            Direct Access to the Kubernetes API Using Authentication Credentials
            Method 1: Using Client Certificate Authentication
            Method 2: Using a ServiceAccount Bearer Token
            Activity 4.01: Creating a Deployment Using a ServiceAccount Identity
          
5. Pods
         
            
            Pod Configuration
            Exercise 5.01: Creating a Pod with a Single Container
            Name
            Namespace
            Exercise 5.02: Creating a Pod in a Different Namespace by Specifying the Namespace in the CLI
            Exercise 5.03: Creating a Pod in a Different Namespace by Specifying the Namespace in the Pod
                           Configuration YAML file
            Exercise 5.04: Changing the Namespace for All Subsequent kubectl Commands
            Node
            Status
            Containers
            Exercise 5.05: Using CLI Commands to Create a Pod Running a Container
            Exercise 5.06: Creating a Pod Running a Container That Exposes a Port
            Exercise 5.07: Creating a Pod Running a Container with Resource Requirements
            Exercise 5.08: Creating a Pod with Resource Requests That Can't Be Met by Any of the Nodes
            Exercise 5.09: Creating a Pod with Multiple Containers Running inside It
            Life Cycle of a Pod
            Phases of a Pod
            Probes/Health Checks
            Types of Probes
            Liveness Probe
            Readiness Probe
            Configuration of Probes
            Implementation of Probes
            Command Probe
            HTTP Request Probe
            TCP Socket Probe
            Restart Policy
            Exercise 5.10: Creating a Pod Running a Container with a Liveness Probe and No Restart Policy
            Exercise 5.11: Creating a Pod Running a Container with a Liveness Probe and a Restart Policy
            Exercise 5.12: Creating a Pod Running a Container with a Readiness Probe
            Best Practices While Using Probes
            Activity 5.01: Deploying an Application in a Pod
          
6. Labels And Annotations
         
            
            Labels
            Constraints for Labels
            Label Keys
            Label Values
            Why Do We Need Labels?
            Organizing Pods by Organization/Team/Project
            Running Selective Pods on Specific Nodes
            Exercise 6.01: Creating a Pod with Labels
            Exercise 6.02: Adding Labels to a Running Pod
            Exercise 6.03: Modifying And/Or Deleting Existing Labels for a Running Pod
            Selecting Kubernetes Objects Using Label Selectors
            Equality-Based Selectors
            Exercise 6.04: Selecting Pods Using Equality-Based Label Selectors
            Set-Based Selectors
            Exercise 6.05: Selecting Pods Using Set-Based Label Selectors
            Exercise 6.06: Selecting Pods Using a Mix of Label Selectors
            Annotations
            Constraints for Annotations
            Annotation Keys
            Annotation Values
            Use Case for Annotations
            Exercise 6.07: Adding Annotations to Help with Application Debugging
            Working with Annotations
            Activity 6.01: Creating Pods with Labels/Annotations and Grouping Them as per Given Criteria
          
7. Kubernetes Controllers
         
            ReplicaSets
            ReplicaSet Configuration
            Replicas
            Pod Template
            Pod Selector
            Exercise 7.01: Creating a Simple ReplicaSet with nginx Containers
            Labels on the ReplicaSet
            Selectors for the ReplicaSet
            Replicas
            Pods Status
            Pods Template
            Events
            Exercise 7.02: Deleting Pods Managed by a ReplicaSet
            Exercise 7.03: Creating a ReplicaSet Given That a Matching Pod Already Exists
            Exercise 7.04: Scaling a ReplicaSet after It Is Created
            Deployment
            Deployment Configuration
            Strategy
            Exercise 7.05: Creating a Simple Deployment with Nginx Containers
            Labels and Annotations on the Deployment
            Selectors for the Deployment
            Replicas
            Rolling Back a Deployment
            Exercise 7.06: Rolling Back a Deployment
            StatefulSets
            StatefulSet Configuration
            Use Cases for StatefulSets
            DaemonSets
            Use Cases for DaemonSets
            DaemonSet Configuration
            Jobs
            Job Configuration
            A Use Case for Jobs in Machine Learning
            Exercise 7.07: Creating a Simple Job That Finishes in Finite Time
            Activity 7.01: Creating a Deployment Running an Application
          
8. Service Discovery
                            
            Service
            Service Configuration
            Types of Services
            NodePort Service
            Exercise 8.01: Creating a Simple NodePort Service with Nginx Containers
            ClusterIP Service
            Service Configuration
            Exercise 8.02: Creating a Simple ClusterIP Service with Nginx Containers
            Choosing a Custom IP Address for the Service
            Exercise 8.03: Creating a ClusterIP Service with a Custom IP
            LoadBalancer Service
            ExternalName Service
            Ingress
            Activity 8.01: Creating a Service to Expose the Application Running on a Pod
            
9. Storing And Reading Data On Disk
            
            Volumes
            How to Use Volumes
            Defining Volumes
            Mounting Volumes
            Types of Volumes
            emptyDir
            hostPath
            Exercise 9.01: Creating a Pod with an emptyDir Volume
            Exercise 9.02: Creating a Pod with an emptyDir Volume Shared by Three Containers
            Persistent Volumes
            PersistentVolume Configuration
            storageClassName
            capacity
            volumeMode
            accessModes
            persistentVolumeReclaimPolicy
            PV Status
            PersistentVolumeClaim Configuration
            storageClassName
            resources
            volumeMode
            accessMode
            selectors
            How to Use Persistent Volumes
            Step 1 – Provisioning the Volume
            Step 2 – Binding the Volume to a Claim
            Step 3 – Using the Claim
            Exercise 9.03: Creating a Pod That Uses PersistentVolume for Storage
            Dynamic Provisioning
            Activity 9.01: Creating a Pod That Uses a Dynamically Provisioned PersistentVolume
          
10. ConfigMaps And Secrets
 
            What Is a ConfigMap?
            Exercise 10.01: Creating a ConfigMap from Literal Values and Mounting It on a Pod Using Environment Variables
            Defining a ConfigMap from a File and Loading It onto a Pod
            Exercise 10.02: Creating a ConfigMap from a File
            Exercise 10.03: Creating a ConfigMap from a Folder
            What Is a Secret?
            Secret versus ConfigMap
            Exercise 10.04: Defining a Secret from Literal Values and Loading the Values onto the Pod as an Environment Variable
            Exercise 10.05: Defining a Secret from a File and Loading the Values onto the Pod as a File
            Exercise 10.06: Creating a TLS Secret
            Exercise 10.07: Creating a docker-registry Secret
            Activity 10.01: Using a ConfigMap and Secret to Promote an Application through Different Stages
          
11. Build Your Own HA Cluster
           
            How the Components of Kubernetes Work Together to Achieve High Availability
            etcd
            Networking and DNS
            Nodes' and Master Servers' Locations and Resources
            Container Network Interface and Cluster DNS
            Container Runtime Interfaces
            Container Storage Interfaces
            Building a High-Availability Focused Kubernetes Cluster
            Self-Managed versus Vendor-Managed Kubernetes Solutions
            kops
            Other Commonly Used Tools
            Authentication and Identity in Kubernetes
            Exercise 11.01: Setting up Our Kubernetes Cluster
            Kubernetes Service Accounts
            Exercise 11.02: Deploying an Application on Our HA Cluster
            Activity 11.01: Testing the Resilience of a Highly Available Cluster
            Deleting Our Cluster
          
12. Your Application And HA
                     
            An Overview of Infrastructure Life Cycle Management
            Terraform
            Exercise 12.01: Creating an S3 Bucket with Terraform
            Exercise 12.02: Creating a Cluster with EKS Using Terraform
            Kubernetes Ingress
            Highly Available Applications Running on Top of Kubernetes
            Exercise 12.03: Deploying a Multi-Replica Non-HA Application in Kubernetes
            Working with Stateful Applications
            The CI/CD Pipeline
            Exercise 12.04: Deploying an Application with State Management
            Activity 12.01: Expanding the State Management of Our Application
            
13. Runtime And Network Security In Kubernetes
            
            Threat Modeling
            The 4Cs of Cloud Native Security
            Cluster Security
            Kubernetes RBAC
            Role
            RoleBinding
            ClusterRole
            ClusterRoleBinding
            Some Important Notes about RBAC Policies
            ServiceAccount
            Exercise 13.01: Creating a Kubernetes RBAC ClusterRole
            NetworkPolicies
            Exercise 13.02: Creating a NetworkPolicy
            PodSecurityPolicy
            Exercise 13.03: Creating and Testing a PodSecurityPolicy
            Activity 13.01: Securing Our App
          
14. Running Stateful Components In Kubernetes
            
            Stateful Apps
            Understanding StatefulSets
            Deployments versus StatefulSets
            Further Refactoring Our Application
            Exercise 14.01: Deploying a Counter App with a MySQL Backend
            Exercise 14.02: Testing the Resilience of StatefulSet Data in PersistentVolumes
            Helm
            Exercise 14.03: Chart-ifying Our Redis-Based Counter Application
            Activity 14.01: Chart-ifying Our StatefulSet Deployment
          
15. Monitoring And Autoscaling In Kubernetes
         
            Kubernetes Monitoring
            Kubernetes Metrics API/Metrics Server
            Prometheus
            Grafana
            Monitoring Your Applications
            Exercise 15.01: Setting up the Metrics Server and Observing Kubernetes Objects
            Autoscaling in Kubernetes
            HorizontalPodAutoscaler
            Exercise 15.02: Scaling Workloads in Kubernetes
            ClusterAutoscaler
            Exercise 15.03: Configuring the ClusterAutoscaler
            Activity 15.01: Autoscaling Our Cluster Using ClusterAutoscaler
            Deleting Your Cluster Resources
          
16. Kubernetes Admission Controllers
         
            How Admission Controllers Work
            Creating Controllers with Custom Logic
            The Mutating Admission Webhook
            The Validating Admission Webhook
            How a Webhook Works
            Exercise 16.01: Modifying a ConfigMap Object through a Patch
            Guidelines for Building a Mutating Admission WebHook
            Exercise 16.02: Deploying a Webhook
            Configuring the Webhook to Work with Kubernetes
            How to Encode a Certificate in Base64 Format
            Activity 16.01: Creating a Mutating Webhook That Adds an Annotation to a Pod
            Validating a Webhook
            Coding a Simple Validating WebHook
            Activity 16.02: Creating a Validating Webhook That Checks for a Label in a Pod
            Controlling the Effect of a Webhook on Selected Namespaces
            Exercise 16.03: Creating a Validating Webhook with the Namespace Selector Defined
          
17. Advanced Scheduling In Kubernetes
         
            
            The Kubernetes Scheduler
            The Pod Scheduling Process
            Filtering
            Scoring
            Assigning
            Timeline of Pod Scheduling
            Managing the Kubernetes Scheduler
            Node Affinity and Anti-Affinity
            Exercise 17.01: Running a Pod with Node Affinity
            Pod Affinity and Anti-Affinity
            Exercise 17.02: Running Pods with Pod Affinity
            Pod Priority
            Exercise 17.03: Pod Priority and Preemption
            Taints and Tolerations
            Exercise 17.04: Taints and Tolerations
            Using a Custom Kubernetes Scheduler
            Activity 17.01: Configuring a Kubernetes Scheduler to Schedule Pods

18. Upgrading Your Cluster Without Downtime
         
            
            The Need to Upgrade Your Kubernetes Cluster
            Kubernetes Components – Refresher
            A Word of Caution
            The Upgrade Process
            Some Considerations for kops
            An overview of the Upgrade Process
            The Importance of Automation
            Backing up the etcd Datastore
            Exercise 18.01: Taking a Snapshot of the etcd Datastore
            Draining a Node and Making It Non-Schedulable
            Exercise 18.02: Draining All the Pods from the Nodes
            Upgrading Kubernetes Master Components
            Exercise 18.03: Upgrading Kubernetes Master Components
            Upgrading Kubernetes Worker Nodes
            Exercise 18.04: Upgrading the Worker Nodes
            Activity 18.01: Upgrading the Kubernetes Platform from Version 1.15.7 to 1.15.10
          
19. Custom Resource Definitions In Kubernetes
         
            
            What Is a Custom Controller?
            The Relationship between a CRD, a CR, and a Controller
            Standard Kubernetes API Resources
            Why We Need Custom Resources?
            Example Use Case 1
            Example Use Case 2
            Example Use Case 3
            How Our Custom Resources Are Defined
            apiVersion
            kind
            spec
            namespaceName and podLiveForThisMinutes
            The Definition of a CRD
            Exercise 19.01: Defining a CRD
            Exercise 19.02: Defining a CR Using a CRD
            Writing the Custom Controller
            The Components of the Custom Controller
            Activity 19.01: CRD and Custom Controller in Action
            Adding Data to Our Custom Resource
            Exercise 19.03: Adding Custom Information to the CR List Command



