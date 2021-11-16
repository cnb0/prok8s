Introduction To DevOps
   
                        Software delivery challenges
                        Waterfall and physical delivery
                        Agile and electrical delivery
                        Software delivery on the cloud
                        Continuous Integration
                        Continuous Delivery
                        Configuration management
                        Infrastructure as code
                        Orchestration
                        Trend of microservices
                        Modular programming
                        Package management
                        MVC design pattern
                        Monolithic application
                        Remote Procedure Call
                        RESTful design
                        Microservices
                        Automation and tools
                        Continuous Integration tool
                        Continuous Delivery tool
                        Monitoring and logging tool
                        Communication tool
                        Public cloud
    
       

DevOps With Container
                        
                        Understanding container
                        Resource isolation
                        Linux container concept
                        Containerized delivery
                        Getting started with container
                        Installing Docker for Ubuntu
                        Installing Docker for CentOS
                        Container life cycle
                        Docker basics
                        Layer, image, container, and volume
                        Distributing images
                        Connect containers
                        Working with Dockerfile
                        Writing your first Dockerfile
                        Dockerfile syntax
                        Organizing a Dockerfile
                        Multi-containers orchestration
                        Piling up containers
                        Docker Compose overview
                        Composing containers
    

   
Getting Started With Kubernetes
   
                        Understanding Kubernetes
                        Kubernetes components
                        Master components
                        API server (kube-apiserver)
                        Controller Manager (kube-controller-manager)
                        etcd
                        Scheduler (kube-scheduler)
                        Node components
                        Kubelet
                        Proxy (kube-proxy)
                        Docker
                        Interaction between Kubernetes master and nodes
                        Getting started with Kubernetes
                        Preparing the environment
                        kubectl
                        Kubernetes resources
                        Kubernetes objects
                        Namespace
                        Name
                        Label and selector
                        Annotation
                        Pods
                        ReplicaSet (RS) 
                        Deployments
                        Services
                        Volumes
                        Secrets
                        ConfigMap
                        Using ConfigMap via volume
                        Using ConfigMap via environment variables
                        Multi-containers orchestration
   
    
   
Working With Storage And Resources
   

                        Kubernetes volume management
                        Container volume lifecycle
                        Sharing volume between containers within a pod
                        Stateless and stateful applications
                        Kubernetes Persistent Volume and dynamic provisioning
                        Persistent Volume claiming the abstraction layer
                        Dynamic Provisioning and StorageClass
                        A problem case of ephemeral and persistent setting
                        Replicating pods with a Persistent Volume using StatefulSet
                        Persistent Volume example
                        Elasticsearch cluster scenario
                        Elasticsearch master node
                        Elasticsearch master-eligible node
                        Elasticsearch data node
                        Elasticsearch coordinating node
                        Kubernetes resource management
                        Resource Quality of Service
                        Configuring the BestEffort pod
                        Configuring as the Guaranteed pod
                        Configuring as Burstable pod
                        Monitoring resource usage
   
    
   
Network And Security
   
                        Kubernetes networking
                        Docker networking
                        Container-to-container communications
                        Pod-to-pod communications
                        Pod communication within the same node
                        Pod communication across nodes
                        Pod-to-service communications
                        External-to-service communications
                        Ingress
                        Network policy
   
    
   
Monitoring And Logging
   
                        Inspecting a container
                        Kubernetes dashboard
                        Monitoring in Kubernetes
                        Application
                        Host
                        External resources
                        Container
                        Kubernetes
                        Getting monitoring essentials for Kubernetes
                        Hands-on monitoring
                        Meeting Prometheus
                        Deploying Prometheus
                        Working with PromQL
                        Discovering targets in Kubernetes
                        Gathering data from Kubernetes
                        Seeing metrics with Grafana
                        Logging events
                        Patterns of aggregating logs
                        Collecting logs with a logging agent per node
                        Running a sidecar container to forward logs
                        Ingesting Kubernetes events
                        Logging with Fluentd and Elasticsearch
                        Extracting metrics from logs
   
    
   
Continuous Delivery
   
                        Updating resources
                        Triggering updates
                        Managing rollouts
                        Updating DaemonSet and StatefulSet
                        DaemonSet
                        StatefulSet
                        Building a delivery pipeline
                        Choosing tools
                        Steps explained
                        env
                        script
                        after_success
                        deploy
                        Gaining deeper understanding of pods
                        Starting a pod
                        Liveness and readiness probes
                        Init containers
                        Terminating a pod
                        Handling SIGTERM
                        SIGTERM is not forwarded to the container process
                        SIGTERM doesn't invoke the termination handler
                        Container lifecycle hooks
                        Placing pods
    
    
   
Cluster Administration
   
                        Kubernetes namespaces
                        Default namespaces
                        Create a new namespace
                        Context
                        Create a context
                        Switch the current context
                        ResourceQuota
                        Create a ResourceQuota for a namespace
                        Request pods with default compute resource limits
                        Delete a namespace
                        Kubeconfig
                        Service account
                        Authentication and authorization
                        Authentication
                        Service account authentication
                        User account authentication
                        Authorization
                        Attribute-based access control (ABAC)
                        Role-based access control (RBAC)
                        Roles and ClusterRoles
                        RoleBinding and ClusterRoleBinding
                        Admission control
                        Namespace life cycle
                        LimitRanger
                        Service account
                        PersistentVolumeLabel
                        DefaultStorageClass
                        ResourceQuota
                        DefaultTolerationSeconds
                        Taints and tolerations
                        PodNodeSelector
                        AlwaysAdmit
                        AlwaysPullImages
                        AlwaysDeny
                        DenyEscalatingExec
                        Other admission controller plugins
   
    
   
Kubernetes On AWS
    
                        Introduction to AWS
                        Public cloud
                        API and infrastructure as code
                        AWS components
                        VPC and subnet
                        Internet gateway and NAT-GW
                        Security group
                        EC2 and EBS
                        Route 53
                        ELB
                        S3
                        Setup Kubernetes on AWS
                        Install kops
                        Run kops
                        Kubernetes cloud provider
                        L4 LoadBalancer
                        L7 LoadBalancer (ingress)
                        StorageClass
                        Maintenance Kubernetes cluster by kops
    
    
   
Kubernetes On GCP
   
                        Introduction to GCP
                        GCP components
                        VPC
                        Subnets
                        Firewall rules
                        VM instance
                        Load balancing
                        Health check
                        Backend service
                        Creating a LoadBalancer
                        Persistent Disk
                        Google Container Engine (GKE)
                        Setting up your first Kubernetes cluster on GKE
                        Node pool
                        Multi zone cluster
                        Cluster upgrade
                        Kubernetes cloud provider
                        StorageClass
                        L4 LoadBalancer
                        L7 LoadBalancer (ingress)
   

   
   
Exploring the possibilities of Kubernetes
   
                        Mastering Kubernetes
                        Job and CronJob
                        Affinity and anti-affinity between pods and nodes
                        Auto-scaling of pods
                        Prevention and mitigation of pod disruptions
                        Kubernetes federation
                        Cluster add-ons
                        Kubernetes and communities
                        Kubernetes incubator
                        Helm and charts
                        Gravitating towards a future infrastructure
                        Docker swarm mode
                        Amazon EC2 container service
                        Apache Mesos