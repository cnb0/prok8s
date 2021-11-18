1. Introduction

                The Path to Cloud Native
                Distributed Primitives
                Containers
                Pods
                Services
                Labels
                Annotations
                Namespaces
                Workshop

I. Foundational Patterns
   
        2. Predictable Demands

                Runtime Dependencies
                Resource Profiles
                Pod Priority
                Project Resources
                Capacity Planning
                Workshop
            
                
        3. Declarative Deployment

                Rolling Deployment
                Fixed Deployment
                Blue-Green Release
                Canary Release
                Workshop
            
                
        4. Health Probe

                Process Health Checks
                Liveness Probes
                Readiness Probes
                Workshop
            
                
        5. Managed Lifecycle
        
                SIGTERM Signal
                SIGKILL Signal
                Poststart Hook
                Prestop Hook
                Other Lifecycle Controls
                Workshop
            
                
        6. Automated Placement
        
                Available Node Resources
                Container Resource Demands
                Placement Policies
                Scheduling Process
                Node Affinity
                Pod Affinity and Antiaffinity
                Taints and Tolerations
                Workshop
      
        
II. Behavioral Patterns
   
                7. Batch Job
                        
                8. Periodic Job
                        
                9. Daemon Service
                    
                10. Singleton Service
                
                        Out-of-Application Locking
                        In-Application Locking
                        Pod Disruption Budget
                        Workshop
                        
                11. Stateful Service

                        Storage
                        Networking
                        Identity
                        Ordinality
                        Other Requirements
                        Solution
                        Storage
                        Networking
                        Identity
                        Ordinality
                        Workshop
                    
                        
                12. Service Discovery
                
                        Internal Service Discovery
                        Manual Service Discovery
                        Service Discovery from Outside the Cluster
                        Application Layer Service Discovery
                        Workshop
            
                
                13. Self Awareness
       
        
III. Structural Patterns
        
                14. Init Container
                        
                15. Sidecar
                        
                16. Adapter
            
                
                17. Ambassador
                    
                        
                IV. Configuration Patterns
                
                18. EnvVar Configuration
                        
                19. Configuration Resource
                        
                20. Immutable Configuration
                        Docker Volumes
                        Kubernetes Init Containers
                        OpenShift Templates
                    
                    
                21. Configuration Template
            
        
V. Advanced Patterns
   
                22. Controller
                    
                        
                23. Operator
                
                    Custom Resource Definitions
                        Controller and Operator Classification
                        Operator Development and Deployment
                        Example
                    
                        
                24. Elastic Scale
                

                        Problem
                        Solution
                        Manual Horizontal Scaling
                        Horizontal Pod Autoscaling
                        Vertical Pod Autoscaling
                        Cluster Autoscaling
                        Scaling Levels
                    
                        
                25. Image Builder
                
                        Problem
                        Solution
                        OpenShift Build
                        Knative Build