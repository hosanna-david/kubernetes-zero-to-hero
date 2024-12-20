# kubernetes-zero-to-hero
Learn how to package, deploy and scale applications with Docker and Kubernetes. Scale your app with standard and custom metrics.

Here’s a small list of Kubernetes topics you will be learning vs what you will be performing in an actual job:
 
Basics you will learn first by your-self / courses:
 
1. Kubernetes Fundamentals:
- Understanding Kubernetes architecture
- Pods, Nodes, and Clusters
- Namespaces
 
2. Setup and Configuration:
- Installing Minikube or Kubernetes on local machine
- Understanding kubeadm, kops, and kubectl
 
3. Basic Objects and Concepts:
- Deployments
- Services
- ReplicaSets
- ConfigMaps and Secrets
 
4. Networking:
- Cluster IP
- NodePort
- LoadBalancer
- Ingress basics
 
5. Storage:
- Persistent Volumes (PV)
- Persistent Volume Claims (PVC)
- Storage Classes
 
6. Basic Usage:
- Creating and managing pods
- Scaling applications
- Rolling updates and rollbacks
- Basic troubleshooting
 
7. Security:
- Role-Based Access Control (RBAC)
- Service Accounts
 
8. Monitoring and Logging:
- Basics of monitoring with Prometheus
- Logging with Elasticsearch, Fluentd, and Kibana (EFK stack)
 
9. Understanding YAML:
- Writing basic YAML files for Kubernetes objects
 
Usual production tasks:
 
1. Deployments:
- Blue/Green deployments
- Canary deployments
- A/B testing
 
2. Networking:
- Service Meshes (Istio, Linkerd)
- Network Policies
- Advanced Ingress configurations
- CNI plugins (Calico, Flannel, Weave)
 
3. Storage:
- StatefulSets
- Dynamic provisioning
- CSI (Container Storage Interface)
 
4. Security:
- Pod Security Policies
- Network Policies
- Secrets management (Vault, Sealed Secrets)
- Image security and scanning (Trivy, Clair)
 
5. Advanced Configuration:
- Helm and Helm Charts
- Kustomize
- Operators and CRDs (Custom Resource Definitions)
 
6. Performance Tuning:
- Resource limits and requests
- Horizontal Pod Autoscaler (HPA)
- Vertical Pod Autoscaler (VPA)
- Cluster Autoscaler
 
7. Monitoring and Logging:
- Advanced Prometheus configuration
- Alerting with Alertmanager
- Distributed tracing (Jaeger, OpenTelemetry)
- Centralized logging
 
8. Cluster Management:
- Multi-cluster management
- Federation
- Backup and restore strategies
 
9. CI/CD Pipelines:
- Integrating CI/CD with Kubernetes (Jenkins X, Tekton)
- GitOps (ArgoCD, Flux)
 
10. Disaster Recovery:
- Backup and restore strategies
- High availability and failover planning
 
11. Scaling and Capacity Planning:
- Handling large-scale deployments
- Capacity planning and resource optimization
 
12. Service Catalog and Broker:
- Using the Kubernetes service catalog
- Integrating external services
 
13. Compliance and Auditing:
- Auditing with Kubernetes
- Ensuring compliance with regulatory requirements
 
14. Troubleshooting:
- Debugging complex issues
- Analyzing logs and metrics
- Using tools like k9s, kubectl-debug, and lens
 
15. Cost Management:
- Cost optimization strategies
- Using tools like Kubecost

Levels of Kubernetes:

 - level 1<br/>
Knows basic concepts. 
Limited troubleshooting skill.
 
- level 2<br/>
Managing deployments, namespaces & scaling apps. 
Troubleshoots issues with pods and deployments.
 
- level 3<br/>
Deep understanding of Kubernetes.
Automate deployments.
Debug advanced issues.
 
- level 4<br/>
Optimizes cluster performance.
Follow Kubernetes security best practices.
Designs & implements secure and scalable clusters.
 
- level 5<br/>
Ability to say - "We don't need Kubernetes for this problem."








