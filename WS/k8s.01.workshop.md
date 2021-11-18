     
### Week 1. Fast Track To Kubernetes

1 Before You Begin
     
            1.1 Understanding Kubernetes
            1.2 Is this course for you?
            1.3 Creating your lab environment
            1.3.1 Download the src source code
            1.3.2 Install Docker  
            1.3.3 Install Docker Community Edition and K3s
            1.3.4 Install the Kubernetes command-line tool
            1.3.5 Run a single-node Kubernetes cluster in Azure
            1.3.6 Run a single-node Kubernetes cluster in AWS
            1.3.7 Verify your cluster
            1.4 Being immediately effective

2 Running Containers In Kubernetes With Pods And Deployments
     
            2.1 How Kubernetes runs and manages containers
            2.2 Running Pods with controllers
            2.3 Defining Deployments in application manifests
            2.4 Working with applications in Pods
            2.5 Understanding Kubernetes resource management

3 Connecting Pods Over The Network With Services
     
            3.1 How Kubernetes routes network traffic
            3.2 Routing traffic between Pods
            3.3 Routing external traffic to Pods
            3.4 Routing traffic outside Kubernetes
            3.5 Understanding Kubernetes Service resolution

4 Configuring Applications With ConfigMaps And Secrets
     
            4.1 How Kubernetes supplies configuration to apps
            4.2 Storing and using configuration files in ConfigMaps
            4.3 Surfacing configuration data from ConfigMaps
            4.4 Configuring sensitive data with Secrets
            4.5 Managing app configuration in Kubernetes

5 Storing Data With Volumes, Mounts, And Claims
     
            5.1 How Kubernetes builds the container filesystem
            5.2 Storing data on a node with volumes and mounts
            5.3 Storing clusterwide data with persistent volumes and claims
            5.4 Dynamic volume provisioning and storage classes
            5.5 Understanding storage choices in Kubernetes

6 Scaling Applications Across Multiple Pods With Controllers
     
            6.1 How Kubernetes runs apps at scale
            6.2 Scaling for load with Deployments and ReplicaSets
            6.3 Scaling for high availability with DaemonSets
            6.4 Understanding object ownership in Kubernetes

### Week 2. Kubernetes In The Real World
     
7 Extending Applications With Multicontainer Pods
     
            7.1 How containers communicate in a Pod
            7.2 Setting up applications with init containers
            7.3 Applying consistency with adapter containers
            7.4 Abstracting connections with ambassador containers
            7.5 Understanding the Pod environment

8 Running Data-Heavy Apps With StatefulSets And Jobs
     
            8.1 How Kubernetes models stability with StatefulSets
            8.2 Bootstrapping Pods with init containers in StatefulSets
            8.3 Requesting storage with volume claim templates
            8.4 Running maintenance tasks with Jobs and CronJobs
            8.5 Choosing your platform for stateful apps

9 Managing App Releases With Rollouts And Rollbacks
     
            9.1 How Kubernetes manages rollouts
            9.2 Updating Deployments with rollouts and rollbacks
            9.3 Configuring rolling updates for Deployments
            9.4 Rolling updates in DaemonSets and StatefulSets
            9.5 Understanding release strategies

10 Packaging And Managing Apps With Helm
     
            10.1 What Helm adds to Kubernetes
            10.2 Packaging your own apps with Helm
            10.3 Modeling dependencies in charts
            10.4 Upgrading and rolling back Helm releases
            10.5 Understanding where Helm fits in

11 App Development-Developer Workflows And CI/CD
     
            11.1 The Docker developer workflow
            11.2 The Kubernetes-as-a-Service developer workflow
            11.3 Isolating workloads with contexts and namespaces
            11.4 Continuous delivery in Kubernetes without Docker
            11.5 Evaluating developer workflows on Kubernetes

### Week 3. Preparing For Production
     
12 Empowering Self-Healing Apps
     
            12.1 Routing traffic to healthy Pods using readiness probes
            12.2 Restarting unhealthy Pods with liveness probes
            12.3 Deploying upgrades safely with Helm
            12.4 Protecting apps and nodes with resource limits
            12.5 Understanding the limits of self-healing apps

13 Centralizing Logs With Fluentd And Elasticsearch
     
            13.1 How Kubernetes stores log entries
            13.2 Collecting logs from nodes with Fluentd
            13.3 Shipping logs to Elasticsearch
            13.4 Parsing and filtering log entries
            13.5 Understanding logging options in Kubernetes

14 Monitoring Applications And Kubernetes With Prometheus
     
            14.1 How Prometheus monitors Kubernetes workloads
            14.2 Monitoring apps built with Prometheus client libraries
            14.3 Monitoring third-party apps with metrics exporters
            14.4 Monitoring containers and Kubernetes objects
            14.5 Understanding the investment you make in monitoring

15 Managing Incoming Traffic With Ingress
     
            15.1 How Kubernetes routes traffic with Ingress
            15.2 Routing HTTP traffic with Ingress rules
            15.3 Comparing ingress controllers
            15.4 Using Ingress to secure your apps with HTTPS
            15.5 Understanding Ingress and ingress controllers

16 Securing Applications With Policies, Contexts, And Admission Control
     
            16.1 Securing communication with network policies
            16.2 Restricting container capabilities with security contexts
            16.3 Blocking and modifying workloads with webhooks
            16.4 Controlling admission with Open Policy Agent
            16.5 Understanding security in depth in Kubernetes

### Week 4. Pure And Applied Kubernetes
     
17 Securing Resources With Role-Based Access Control
     
            17.1 How Kubernetes secures access to resources
            17.2 Securing resource access within the cluster
            17.3 Binding roles to groups of users and service accounts
            17.4 Discovering and auditing permissions with plugins
            17.5 Planning your RBAC strategy

18 Deploying Kubernetes: Multinode And Multiarchitecture Clusters
     
            18.1 What’s inside a Kubernetes cluster?
            18.2 Initializing the control plane
            18.3 Adding nodes and running Linux workloads
            18.4 Adding Windows nodes and running hybrid workloads
            18.5 Understanding Kubernetes at scale

19 Controlling Workload Placement And Automatic Scaling
     
            19.1 How Kubernetes schedules workloads
            19.2 Directing Pod placement with affinity and antiaffinity
            19.3 Controlling capacity with automatic scaling
            19.4 Protecting resources with preemption and priorities
            19.5 Understanding the controls for managing workloads

20 Extending Kubernetes With Custom Resources And Operators
     
            20.1 How to extend Kubernetes with custom resources
            20.2 Triggering workflows with custom controllers
            20.3 Using Operators to manage third-party components
            20.4 Building Operators for your own applications
            20.5 Understanding when to extend Kubernetes

21 Running Serverless Functions In Kubernetes
     
            21.1 How serverless platforms work in Kubernetes
            21.2 Triggering functions from HTTP requests
            21.3 Triggering functions from events and schedules
            21.4 Abstracting serverless functions with Serverless
            21.5 Understanding where serverless functions fit

22 Never The End
     
            22.1 Further reading by chapter
            22.2 Choosing a Kubernetes platform
            22.3 Understanding how Kubernetes is built
            22.4 Joining the community


Appendix A. Packaging Applications From Source Code Into Docker Images     

            A.1 Who needs a build server when you have a Dockerfile?
            A.2 App walkthrough: Java source code
            A.3 App walkthrough: Node.js source code
            A.4 App walkthrough: Go source code
            A.5 Understanding multi-stage Dockerfiles

Appendix B. Adding Observability With Containerized Monitoring
     
            B.1 The monitoring stack for containerized applications
            B.2 Exposing metrics from your application
            B.3 Running a Prometheus container to collect metrics
            B.4 Running a Grafana container to visualize metrics
            B.5 Understanding the levels of observability

Appendix C. Application Configuration Management In Containers
     

            C.1 A multi-tiered approach to app configuration
            C.2 Packaging config for every environment
            C.3 Loading configuration from the runtime
            C.4 Configuring legacy apps in the same way as new apps
            C.5 Understanding why a flexible configuration model pays off

Appendix D. Writing And Managing Application Logs With Docker

            D.1 Welcome to stderr and stdout!
            D.2 Relaying logs from other sinks to stdout
            D.3 Collecting and forwarding container logs
            D.4 Managing your log output and collection
            D.5 Understanding the container logging model
