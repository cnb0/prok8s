### Kubernetes Networking 

    - Kubernetes has become an essential part of the daily work for most system, network, and cluster administrators today. 
    But to work effectively together on a production-scale Kubernetes system, they must be able to speak the same language. 
    it provides a clear guide to the layers of complexity and abstraction that come with running a Kubernetes network.

    - Learn  on the intricacies that Kubernetes has to offer for large container deployments. 
    If you're to be effective in troubleshooting and maintaining a production cluster, 
    you need to be well versed in the abstraction provided at each layer. 
    
    - This practical shows you how.

        - Learn the Kubernetes networking model
        - Choose the best interface for your clusters from the CNCF Container Network Interface project
        - Explore the networking and Linux primitives that power Kubernetes
        - Quickly troubleshoot networking issues and prevent downtime
        - Examine cloud networking and Kubernetes using the three major providers: AWS, Google Cloud, and Microsoft Azure
        - Learn the pros and cons of various network tools--and how to select the best ones for your stack


1. Networking Introduction
  
            Networking History
            OSI Model
            TCP/IP
            Application
            Transport
            Network
            Internet Protocol
            Link Layer
            Revisiting Our Web Server
    
2. Linux Networking
  
            Basics
            The Network Interface
            The Bridge Interface
            Packet Handling in the Kernel
            Netfilter
            Conntrack
            Routing
            High-Level Routing
            iptables
            IPVS
            eBPF
            Network Troubleshooting Tools
            Security Warning
            ping
            traceroute
            dig
            telnet
            nmap
            netstat
            netcat
            Openssl
            cURL
    
3. Container Networking Basics

            Introduction to Containers
            Applications
            Hypervisor
            Containers
            Container Primitives
            Control Groups
            Namespaces
            Setting Up Namespaces
            Container Network Basics
            Docker Networking Model
            Overlay Networking
            Container Network Interface
            Container Connectivity
            Container to Container
            Container to Container Separate Hosts
    
4. Kubernetes Networking Introduction
  
            The Kubernetes Networking Model
            Node and Pod Network Layout
            Isolated Networks
            Flat Networks
            Island Networks
            kube-controller-manager Configuration
            The Kubelet
            Pod Readiness and Probes
            The CNI Specification
            CNI Plugins
            The IPAM Interface
            Popular CNI Plugins
            kube-proxy
            userspace Mode
            iptables Mode
            ipvs Mode
            kernelspace Mode
            NetworkPolicy
            NetworkPolicy Example with Cilium
            Selecting Pods
            Rules
            DNS
            IPv4/IPv6 Dual Stack
    
5. Kubernetes Networking Abstractions
  
            StatefulSets
            Endpoints
            Endpoint Slices
            Kubernetes Services
            NodePort
            ClusterIP
            Headless
            ExternalName Service
            LoadBalancer
            Services     
            Ingress
            Ingress Controllers and Rules
            Service Meshes
    
6. Kubernetes And Cloud Networking
  
            Amazon Web Services
            AWS Network Services
            Amazon Elastic Kubernetes Service
            Deploying an Application on an AWS EKS Cluster
            Google Compute Cloud (GCP)
            GCP Network Services
            GKE
            Azure
            Azure Networking Services
            Azure Kubernetes Service
            Deploying an Application to Azure Kubernetes Service