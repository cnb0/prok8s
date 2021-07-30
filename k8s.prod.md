Chapter 1: Introduction To Kubernetes Infrastructure And Production-Readiness
  
            The basics of Kubernetes infrastructure
            Kubernetes components
            Why Kubernetes is challenging in production
            Kubernetes production-readiness
            The production-readiness checklist
            Kubernetes infrastructure best practices
            The 12 principles of infrastructure design and management
            Applications definition and deployment
            Processes, team, and culture
            Cloud-native approach
            The Cloud Native Computing Foundation
            Why we should care about cloud-native
            Cloud-native landscape and ecosystem
            Cloud-native trail map

        
Chapter 2: Architecting Production-Grade Kubernetes Infrastructure
  
            Understanding Kubernetes infrastructure design considerations
            Scaling and elasticity
            High availability and reliability
            Security and compliance
            Cost management and optimization
            Manageability and operational efficiency
            Exploring Kubernetes deployment strategy alternatives
            Designing an Amazon EKS infrastructure
            Choosing the infrastructure provider
            Choosing the cluster and node size
            Choosing tools for cluster deployment and management
            Deciding the cluster architecture
     
        
Chapter 3: Provisioning Kubernetes Clusters Using AWS And Terraform
  
          
            Installing Terraform
            Implementation principles and best practices
            Cluster deployment and rollout strategy
            Preparing Terraform
            Terraform directory structure
            Persisting the Terraform state
            Creating Terraform state configuration
            Provisioning the Terraform state
            Utilizing Terraform workspaces
            Creating the network infrastructure
            Developing the VPC Terraform module
            Developing the cluster VPC
            Provisioning the cluster VPC
            Creating the cluster infrastructure
            Developing the EKS Terraform module
            Developing the workers' Terraform module
            Developing the Kubernetes cluster Terraform module
            Putting all modules together
            Provisioning the cluster infrastructure
            Cleaning up and destroying infrastructure resources
            Destroying the cluster resources
            Destroying the VPC resources
            Destroying the shared state resources
     
        
Chapter 4: Managing Cluster Configuration With Ansible
            
            Installing the required tools
            Implementation principles
            Kubernetes configuration management
            Kubernetes configuration management workflow
            Configuration management with Ansible
            Configuring the clusters
            The ansible directory's structure
            Creating Ansible templates
            Creating Ansible variables
            Creating Ansible inventories
            Creating Ansible tasks
            Creating the cluster's playbook
            Applying the cluster's Ansible playbook
            Destroying the cluster's resources
     
        
Chapter 5: Configuring And Enhancing Kubernetes Networking Services
  
          
            Introducing networking production readiness
            Configuring Kube Proxy
            Configuring the Amazon CNI plugin
            Configuring CoreDNS
            Configuring ExternalDNS
            Configuring NGINX Ingress Controller
            Deploying the cluster's network services
            Destroying the cluster's resources
     
        
Chapter 6: Securing Kubernetes Effectively
  
          
            Securing Kubernetes infrastructure
            Managing cluster access
            Cluster authentication
            Cluster authorization
            Admission controller
            Managing secrets and certificates
            Creating and managing secrets
            Managing TLS certificates with Cert-Manager
            Securing workloads and apps
            Isolating critical workloads
            Hardening the default pod security policy
            Limiting pod access
            Creating network policies with Calico
            Monitoring runtime with Falco
            Ensuring cluster security and compliance
            Executing Kubernetes conformance tests
            Scanning cluster security configuration
            Executing the CIS Kubernetes benchmark
            Enabling audit logging
            Bonus security tips
            Deploying the security configurations
            Destroying the cluster
     
        
Chapter 7: Managing Storage And Stateful Applications
  
          Installing the required tools
          Implementation principles
          Understanding the challenges with stateful applications
          Tuning Kubernetes storage
          Understanding storage primitives in Kubernetes
          Choosing a persistent storage solution
          Deploying stateful applications
          Installing OpenEBS
          Deploying a stateful application on OpenEBS volumes
     
        
Chapter 8: Deploying Seamless And Reliable Applications
  
          
        Understanding the challenges with container images
        Exploring the components of container images
        Choosing the right container base image
        Reducing container image size
        Scanning container images for vulnerabilities
        Testing the download speed of a container image
        Applying container base images best practices
        Learning application deployment strategies
        Choosing the deployment model
        Monitoring deployments
        Using readiness and liveness container probes
        Scaling applications and achieving higher availability
     
        
Chapter 9: Monitoring, Logging, And Observability
  

          
        Understanding the challenges with Kubernetes observability
        Exploring the Kubernetes metrics
        Learning site reliability best practices
        Monitoring, metrics, and visualization
        Installing the Prometheus stack on Kubernetes
        Monitoring applications with Grafana
        Logging and tracing
        Installing the EFK stack on Kubernetes
     
        
Chapter 10: Operating And Maintaining Efficient Kubernetes Clusters
  
          
        Learning about cluster maintenance and upgrades
        Upgrading kubectl
        Upgrading the Kubernetes control plane
        Upgrading Kubernetes components
        Upgrading Kubernetes worker nodes
        Preparing for backups and disaster recovery
        Installing Velero on Kubernetes
        Taking a backup of specific resources using Velero
        Restoring an application resource from its backup using Velero
        Validating cluster quality
        Generating compliance reports
        Managing and improving the cost of cluster resources