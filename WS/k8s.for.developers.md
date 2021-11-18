
[Nodejs](https://github.com/kubernetes-for-developers/kfd-nodejs)
[flask](https://github.com/kubernetes-for-developers/kfd-flask)
[celery](https://github.com/kubernetes-for-developers/kfd-celery)


 - Setting Up Kubernetes For Development

        What you need for development
        Optional tools
        Getting a local cluster up and running
        Resetting and restarting your cluster
        Looking at what's built-in and included with Minikube
        Verifying Docker
        Clearing and cleaning Docker images
        Kubernetes concept , container
        Kubernetes resource  Pod
        Namespaces
        Writing your code for Pods and Containers
        Kubernetes resource  Node
        Networks
        Controllers
        Kubernetes resource  ReplicaSet
        Kubernetes resource  Deployment
        Representing Kubernetes resources
    
  - Packaging Your Code To Run In Kubernetes
    
        Container images
        Container registries
        Making your first container
        Dockerfile commands
        Example : Python/Flask container image
        Building the container
        Running your container
        Pod name
        Port forwarding
        Proxy
        How did the proxy know to connect to port 5000 on the container?
        Getting logs from your application
        Example   Node.js/Express container image
        Building the container
        Running your container
        Port forwarding
        Proxy
        Getting logs from your application
        Tagging your container images
    
    
    
- Interacting With Your Code In Kubernetes
    
        Practical notes for writing software to run in a container
        Getting options for your executable code
        Practical notes for building container images
        Sending output from your program
        Logs
        Pods with more than one container
        Streaming the logs
        Previous logs
        Timestamps
        More debugging techniques
        Interactive deployment of an image
        Attaching to a running Pod
        Running a second process in a container
        Kubernetes concepts  ; labels
        Organization of labels
        Kubernetes concepts ; selectors
        Viewing labels
        Listing resources with labels using kubectl
        Automatic labels and selectors
        Kubernetes resources  ; service
        Defining a service resource
        Endpoints
        Service type ; ExternalName
        Headless service
        Discovering services from within your Pod
        DNS for services
        Exposing services outside the cluster
        Service type ; LoadBalancer
        Service type ; NodePort
        Minikube service
        Example service ; Redis
        Finding the Redis service
        Using Redis from Python
        Updating the Flask deployment
        Deployments and rollouts
        Rollout history
        Rollout undo
        Updating with the kubectl set command
    
    
    
-  Declarative Infrastructure
    
        Imperative versus declarative commands
        A wall of YAML
        Creating a simple deployment
        Declaring your first application
        ImagePullPolicy
        Audit trail
        Kubernetes resource ; Annotations
        Exposing labels and annotations in Pods
        Kubernetes resource ; ConfigMap
        Creating a ConfigMap
        Managing ConfigMaps
        Exposing the configuration into your container images
        Environment variables
        Exposing ConfigMap as files inside the container
        Dependencies on ConfigMaps
        Kubernetes resource  ; Secrets
        Exposing Secrets into a container
        Secrets and security  ; how secret are the secrets?
        Example ; Python/Flask deployment with ConfigMap
        SIDEBAR ; JSONPATH
        Using the ConfigMap within Python/Flask
    
    
    
-  Pod And Container Lifecycles
    
        Pod lifecycle
        Container lifecycle
        Deployments, ReplicaSets, and Pods
        Getting a snapshot of the current state
        Probes;
        Liveness probe
        Readiness probe
        Adding a probe to our Python example
        Running the Python probes example
        Adding a probe to our Node.js example
        Container lifecycle hooks
        Initialization containers
        Quick interactive testing
        Handling a graceful shutdown
        SIGTERM in Python
        SIGTERM in Node.js
   
    
- Background Processing In Kubernetes
    
        Job
        CronJob
        A worker example with Python and Celery
        Celery worker example
        RabbitMQ and configuration
        Celery worker
        Persistence with Kubernetes
        Volumes
        PersistentVolume and PersistentVolumeClaim
        Stateful Sets
        A Node.js example using Stateful Set
        Custom Resource Definition
    
    
    
- Monitoring And Metrics
    
        Built-in metrics with Kubernetes
        Kubernetes concept &#x2013; Quality of Service
        Choosing requests and limits for your containers
        Capturing metrics with Prometheus
        Installing Helm
        Installing Prometheus using Helm
        Viewing metrics with Prometheus ;
        Installing Grafana
        Using Prometheus to view application metrics
        Flask metrics with Prometheus
        Node.js metrics with Prometheus
        Service signals in Prometheus
    
    
    
- Logging And Tracing
    
        A Kubernetes concept &#x2013; DaemonSet
        Installing and using Elasticsearch, Fluentd, and Kibana
        Log aggregation with EFK
        Viewing logs using Kibana
        Filtering by app
        Lucene query ;language
        Running Kibana in production
        Distributed tracing with Jaeger
        Spans and traces
        Architecture of Jaeger distributed tracing
        Trying out Jaeger
        Example ; adding tracing to your application
        Adding a tracing collector to your pod
        Add the libraries and code to generate traces
        Considerations for adding tracing
    
    
    
- Integration Testing
    
        Testing strategies using Kubernetes
        Reviewing resources needed for testing
        Patterns of using Kubernetes with testing
        Tests local and system-under-test in Kubernetes
        Tests local and system-under-test in Kubernetes namespaces
        Tests in Kubernetes and system-under-test in Kubernetes namespaces
        Simple validation with Bats
        Example ; integration testing with Python
        PyTest and pytest-dependency
        PyTest fixtures and the python-kubernetes client
        Waiting for state changes
        Accessing the deployment
        Example ; integration testing with Node.js
        Node.js tests and dependencies with mocha and chai
        Validating the cluster health
        Deploying with kubectl
        Waiting for the pods to become available
        Interacting with the deployment
        Continuous integration with Kubernetes
        Example : using Minikube with Travis.CI
        Example : using Jenkins and the Kubernetes plugin
        Installing Jenkins using Helm
        Accessing Jenkins
        Updating Jenkins
        Example pipeline
        Next steps with pipelines
    
    
    
- Troubleshooting Common Problems And Next Steps
    
        Common errors and how to resolve them
        Error validating data
        Navigating the documentation
        ErrImagePull
        CrashLoopBackOff
        Starting and inspecting the image
        Adding your own setup to the container&#xA0;
        No endpoints available for service
        Stuck in PodInitializing
        Missing resources
        Emerging projects for developers
        Linters
        Helm
        ksonnet
        Brigade
        skaffold
        img
        Draft
        ksync
        Telepresence
        Interacting with the Kubernetes project
        Slack
        YouTube
        Stack Overflow
        Mailing lists and forums
