

1. Security Strategy
   
            Security for Kubernetes - a new and different world
            Deploying a workload in Kubernetes - Security at each stage.
            Build Time Security: Shift Left
            Deploy Time Security
            Runtime Security
            Security Frameworks
            MITRE
            Threat Matrix for Kubernetes
      
2. Infrastructure Security
   
            Host hardening
            Choice of operating system
            Non-essential processes
            Host based firewalling
            Always research the latest best practices
            Cluster hardening
            Secure the Kubernetes datastore
            Secure the Kubernetes API server
            Encrypt Kubernetes secrets at rest
            Rotate credentials frequently
            Authentication & RBAC
            Restricting cloud metadata API access
            Enable auditing
            Restrict access to alpha or beta features
            Upgrade Kubernetes frequently
            Use a managed Kubernetes service
            CIS Benchmarks
            Network security
      
3. Workload Deployment Controls
   
            Image building and scanning
            Choice of a base image
            Container image hardening
            Container image scanning solution
            Privacy concerns
            Container threat analysis
            CI/CD
            Scan images by registry scanning services
            Scan images after builds
            Inline image scanning
            Kubernetes admission controller
            Securing CI/CD pipeline
            Organization policy
            Secrets management
            etcd to store secrets
            Secret management service
            Kubernetes secrets store CSI driver
            Secrets management best practises
            Authentication
            Authorization
      
4. Workload Runtime Security
   
            Pod Security Policies (PSPs)
            Using Pod Security Policies
            Pod Security Policy capabilities
            Pod security context
            Limitation of PSPs
            Process monitoring
            Kubernetes native monitoring
            Seccomp
            SELinux
            AppArmor
            Sysctl
      
5. Network Policy
   
            What is network policy?
            Why is network policy important?
            Network policy implementations
            Network policy best practices
            Ingress and egress
            Not just mission critical workloads
            Policy and label schemas
            Default deny and default app policy
            Policy tooling
            Development processes & microservices benefits
            Policy recommendations
            Policy impact previews
            Policy staging / audit modes

6. Managing Trust Across Teams
   
            Role based access control
            Limitations with Kubernetes network policies
            Richer network policy implementations
            Admissions controllers
      
7. Exposing Services To External Clients

            Understanding direct pod connections
            Understanding Kubernetes Services
            Cluster IP services
            Node port services
            Load Balancer Services
            externalTrafficPolicy:local
            Network policy extensions
            Alternatives to kube-proxy
            Direct Server Return
            Limiting service external IPs
            Advertising service IPs
            Understanding Kubernetes Ingress
            In-cluster ingress solutions
            External ingress solutions
      
8. Encryption Of Data In Transit
   
            Building encryption into your code
            Side-car or service mesh encryption
            Network layer encryption