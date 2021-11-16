### Cloud Native K8s

        – Setting Up Your Kubernetes Cluster
        – Running Application Containers on Kubernetes
        – Scaling and Deploying Your Application
        - Services and Ingress – Communicating with the Outside World
        – Kubernetes Application Configuration
        – Storage on Kubernetes
        – Pod Placement Controls
        – Observability on Kubernetes
        – Troubleshooting Kubernetes
        – Template Code Generation and CI/CD on Kubernetes
        – Kubernetes Security and Compliance
        – Extending Kubernetes with CRDs
        – Service Meshes and Serverless
        – Stateful Workloads on Kubernetes



Section 1: Setting Up Kubernetes

Chapter 1: Communicating With Kubernetes

                Introducing container orchestration
                What is container orchestration?
                Benefits of container orchestration
                Popular orchestration tools
                Kubernetes' architecture
                Kubernetes node types
                The Kubernetes control plane
                The Kubernetes API server
                The Kubernetes scheduler
                The Kubernetes controller manager
                etcd
                The Kubernetes worker nodes
                kubelet
                kube-proxy
                The container runtime
                Addons
                Authentication and authorization on Kubernetes
                Namespaces
                Users
                Authentication methods
                Kubernetes' certificate infrastructure for TLS and security
                Authorization options
                RBAC
                ABAC
                Using kubectl and YAML
                Setting up kubectl and kubeconfig
                Imperative versus declarative commands
                Writing Kubernetes resource YAML files

Chapter 2: Setting Up Your Kubernetes Cluster
                            
                Options for creating a cluster
                minikube – an easy way to start
                Installing minikube
                Creating a cluster on minikube
                Managed Kubernetes services
                Benefits of managed Kubernetes services
                Drawbacks of managed Kubernetes services
                AWS – Elastic Kubernetes Service
                Getting started
                Google Cloud – Google Kubernetes Engine
                Getting started
                Microsoft Azure – Azure Kubernetes Service
                Getting started
                Programmatic cluster creation tools
                Kubeadm
                Kops
                Kubespray
                Creating a cluster with Kubeadm
                Installing Kubeadm
                Starting the master nodes
                Starting the worker nodes
                Setting up kubectl
                Creating a cluster with Kops
                Installing on macOS
                Installing on Linux
                Installing on Windows
                Setting up credentials for Kops
                Setting up state storage
                Creating clusters
                Creating a cluster completely from scratch
                Provisioning your nodes
                Creating the Kubernetes certificate authority for TLS
                Creating config files
                Creating an etcd cluster and configuring encryption
                Bootstrapping the control plane component
                Bootstrapping the worker node

Chapter 3: Running Application Containers On Kubernetes
                        
                What is a Pod?
                Implementing Pods
                Pod paradigms
                Pod networking
                Pod storage
                Namespaces
                The Pod life cycle
                Understanding the Pod resource spec

Section 2: Configuring And Deploying Applications On Kubernetes

Chapter 4: Scaling And Deploying Your Application
                        
                Understanding Pod drawbacks and their solutions
                Pod controllers
                Using ReplicaSets
                Replicas
                Selector
                Template
                Testing a ReplicaSet
                Controlling Deployments
                Controlling Deployments with imperative commands
                Harnessing the Horizontal Pod Autoscaler
                Implementing DaemonSets
                Understanding StatefulSets
                Using Jobs
                CronJobs
                Putting it all together

Chapter 5: Services And Ingress – Communicating With The Outside World
                       
                Understanding Services and cluster DNS
                Cluster DNS
                Service proxy types
                Implementing ClusterIP
                Protocol
                Using NodePort
                Setting up a LoadBalancer Service
                Creating an ExternalName Service
                Configuring Ingress
                Ingress controllers

Chapter 6: Kubernetes Application Configuration
                    
                Configuring containerized applications using best practices
                Understanding ConfigMaps
                Understanding Secrets
                Implementing ConfigMaps
                From text values
                From files
                From environment files
                Mounting a ConfigMap as a volume
                Mounting a ConfigMap as an environment variable
                Using Secrets
                From files
                Manual declarative approach
                Mounting a Secret as a volume
                Mounting a Secret as an environment variable
                Implementing encrypted Secrets
                Checking whether your Secrets are encrypted
                Disabling cluster encryption


Chapter 7: Storage On Kubernetes
                          
              Understanding the difference between volumes and persistent volumes
              Volumes
              Persistent volumes
              Persistent volume claims
              Attaching Persistent Volume Claims (PVCs) to Pods
              Persistent volumes without cloud storage
              Installing Rook
              The rook-ceph-block storage class
              The Rook Ceph filesystem
Chapter 8: Pod Placement Controls
                          
              Identifying use cases for Pod placement
              Kubernetes node health placement controls
              Applications requiring different node types
              Applications requiring specific data compliance
              Multi-tenant clusters
              Multiple failure domains
              Using node selectors and node name
              Implementing taints and tolerations
              Multiple taints and tolerations
              Controlling Pods with node affinity
              Using requiredDuringSchedulingIgnoredDuringExecution node affinities
              Using preferredDuringSchedulingIgnoredDuringExecution node affinities
              Multiple node affinities
              Using inter-Pod affinity and anti-affinity
              Pod affinities
              Pod anti-affinities
              Combined affinity and anti-affinity
              Pod affinity and anti-affinity limitations
              Pod affinity and anti-affinity namespaces



Section 3: Running Kubernetes In Production

Chapter 9: Observability On Kubernetes
                        
            Understanding observability on Kubernetes
            Understanding what matters for Kubernetes cluster and application health
            Using default observability tooling
            Metrics on Kubernetes
            Logging on Kubernetes
            Installing Kubernetes Dashboard
            Alerts and traces on Kubernetes
            Enhancing Kubernetes observability using the best of the ecosystem
            Introducing Prometheus and Grafana
            Implementing the EFK stack on Kubernetes
            Implementing distributed tracing with Jaeger
            Third-party tooling


Chapter 10: Troubleshooting Kubernetes
                      
            Understanding failure modes for distributed applications
            The network is reliable
            Latency is zero
            Bandwidth is infinite
            The network is secure
            The topology doesn't change
            There is only one administrator
            Transport cost is zero
            The network is homogeneous
            Troubleshooting Kubernetes clusters
            Case study – Kubernetes Pod placement failure
            Troubleshooting applications on Kubernetes
            Case study 1 – Service not responding
            Case study 2 – Incorrect Pod startup command
            Case study 3 – Pod application malfunction with logs


Chapter 11: Template Code Generation And CI/CD On Kubernetes
                    
            Understanding options for template code generation on Kubernetes
            Helm
            Kustomize
            Implementing templates on Kubernetes with Helm and Kustomize
            Using Helm with Kubernetes
            Using Kustomize with Kubernetes
            Understanding CI/CD paradigms on Kubernetes – in-cluster and out-of-cluster
            Out-of-cluster CI/CD
            In-cluster CI/CD
            Implementing in-cluster and out-of-cluster CI/CD with Kubernetes
            Implementing Kubernetes CI with AWS Codebuild
            Implementing Kubernetes CI with FluxCD


Chapter 12: Kubernetes Security And Compliance
                        
            Understanding security on Kubernetes
            Reviewing CVEs and security audits for Kubernetes
            Understanding CVE-2016-1905 – Improper admission control
            Understanding CVE-2018-1002105 – Connection upgrading to the backend
            Understanding the 2019 security audit results
            Implementing tools for cluster configuration and container security
            Using admission controllers
            Enabling Pod security policies
            Using network policies
            Handling intrusion detection, runtime security, and compliance on Kubernetes
            Installing Falco
            Understanding Falco's capabilities
            Mapping Falco to compliance and runtime security use cases


Section 4: Extending Kubernetes

Chapter 13: Extending Kubernetes With CRDs
                        
            How to extend Kubernetes with custom resource definitions
            Writing a custom resource definition
            Self-managing functionality with Kubernetes operators
            Mapping the operator control loop
            Designing an operator for a custom resource definition
            Using cloud-specific Kubernetes extensions
            Understanding the cloud-controller-manager component
            Installing cloud-controller-manager
            Understanding the cloud-controller-manager capabilities
            Using external-dns with Kubernetes
            Using the cluster-autoscaler add-on
            Integrating with the ecosystem
            Introducing the Cloud Native Computing Foundation


Chapter 14: Service Meshes And Serverless
                        
            Using sidecar proxies
            Using NGINX as a sidecar reverse proxy
            Using Envoy as a sidecar proxy
            Adding a service mesh to Kubernetes
            Setting up Istio on Kubernetes
            Implementing serverless on Kubernetes
            Using Knative for FaaS on Kubernetes
            Using OpenFaaS for FaaS on Kubernetes


Chapter 15: Stateful Workloads On Kubernetes
                      
            Understanding stateful applications on Kubernetes
            Popular Kubernetes-native stateful applications
            Understanding strategies for running stateful applications on Kubernetes
            Deploying object storage on Kubernetes
            Installing the Minio Operator
            Installing Krew and the Minio kubectl plugin
            Starting the Minio Operator
            Creating a Minio tenant
            Accessing the Minio console
            Running DBs on Kubernetes
            Running CockroachDB on Kubernetes
            Testing CockroachDB with SQL
            Implementing messaging and queues on Kubernetes
            Deploying RabbitMQ on Kubernetes
