# OpenShift Container Platform

This documentation may not be available for all versions.

# OpenShift Container Platform

This documentation may not be available for all versions.

1. Discover
    1. About
        1. About
        2. OpenShift Container Platform 4.18 Documentation
        3. Learn more about OpenShift Container Platform
        4. Providing feedback on OpenShift Container Platform documentation
        5. About OpenShift Kubernetes Engine
    2. Architecture
        1. Architecture
        2. Architecture overview
        3. OpenShift Container Platform architecture
        4. Installation and update
        5. Red Hat OpenShift Cluster Manager
        6. About the multicluster engine for Kubernetes Operator
        7. Control plane architecture
        8. Understanding OpenShift Container Platform development
        9. Red Hat Enterprise Linux CoreOS (RHCOS)
        10. Admission plugins
2. Getting Started
    1. Getting started
        1. Getting started
        2. Kubernetes overview
        3. OpenShift Container Platform overview
        4. Creating and building an application using the web console
        5. Creating and building an application using the CLI
3. What's New
    1. Release notes
        1. Release notes
        2. OpenShift Container Platform 4.18 release notes
        3. Additional release notes
4. Disconnected Environments
    1. Disconnected environments
        1. Disconnected environments
        2. About disconnected environments
        3. Converting a connected cluster to a disconnected cluster
        4. Mirroring in disconnected environments
        5. Installing a cluster in a disconnected environment
        6. Using Operator Lifecycle Manager in disconnected environments
        7. Updating a cluster in a disconnected environment
5. Install
    1. Installation overview
        1. Installation overview
        2. OpenShift Container Platform installation overview
        3. Selecting a cluster installation method and preparing it for users
        4. Cluster capabilities
        5. Support for FIPS cryptography
    2. Installing on Alibaba Cloud
        1. Installing on Alibaba Cloud
        2. Installing a cluster on Alibaba Cloud by using the Assisted Installer
    3. Installing on AWS
        1. Installing on AWS
        2. Installation methods
        3. Configuring an AWS account
        4. Installer-provisioned infrastructure
        5. User-provisioned infrastructure
        6. Installing a three-node cluster on AWS
        7. Uninstalling a cluster on AWS
        8. Installation configuration parameters for AWS
        9. AWS Local Zone or Wavelength Zone tasks
    4. Installing on Azure
        1. Installing on Azure
        2. Installation methods
        3. Configuring an Azure account
        4. Installer-provisioned infrastructure
        5. User-provisioned infrastructure
        6. Installing a three-node cluster on Azure
        7. Uninstalling a cluster on Azure
        8. Installation configuration parameters for Azure
    5. Installing on Azure Stack Hub
        1. Installing on Azure Stack Hub
        2. Installation methods
        3. Configuring an Azure Stack Hub account
        4. Installer-provisioned infrastructure
        5. User-provisioned infrastructure
        6. Installation configuration parameters for Azure Stack Hub
        7. Uninstalling a cluster on Azure Stack Hub
    6. Installing on GCP
        1. Installing on GCP
        2. Preparing to install on GCP
        3. Configuring a GCP project
        4. Installing a cluster quickly on GCP
        5. Installing a cluster on GCP with customizations
        6. Installing a cluster on GCP with network customizations
        7. Installing a cluster on GCP in a disconnected environment
        8. Installing a cluster on GCP into an existing VPC
        9. Installing a cluster on GCP into a shared VPC
        10. Installing a private cluster on GCP
        11. Installing a cluster on user-provisioned infrastructure in GCP by using Deployment Manager templates
        12. Installing a cluster into a shared VPC on GCP using Deployment Manager templates
        13. Installing a cluster on GCP in a disconnected environment with user-provisioned infrastructure
        14. Installing a three-node cluster on GCP
        15. Installation configuration parameters for GCP
        16. Uninstalling a cluster on GCP
        17. Installing a cluster with the support for configuring multi-architecture compute machines
    7. Installing on IBM Cloud
        1. Installing on IBM Cloud
        2. Installation methods
        3. Configuring an IBM Cloud account
        4. Configuring IAM for IBM Cloud
        5. User-managed encryption for IBM Cloud
        6. Installing a cluster on IBM Cloud with customizations
        7. Installing a cluster on IBM Cloud with network customizations
        8. Installing a cluster on IBM Cloud into an existing VPC
        9. Installing a private cluster on IBM Cloud
        10. Installing a cluster on IBM Cloud in a disconnected environment
        11. Installation configuration parameters for IBM Cloud
        12. Uninstalling a cluster on IBM Cloud
    8. Installing on Nutanix
        1. Installing on Nutanix
        2. Preparing to install on Nutanix
        3. Fault tolerant deployments using multiple Prism Elements
        4. Installing a cluster on Nutanix
        5. Installing a cluster on Nutanix in a disconnected environment
        6. Installing a three-node cluster on Nutanix
        7. Uninstalling a cluster on Nutanix
        8. Installation configuration parameters for Nutanix
    9. Installing on-premise with Assisted Installer
        1. Installing on-premise with Assisted Installer
        2. Installing an on-premise cluster using the Assisted Installer
    10. Installing an on-premise cluster with the Agent-based Installer
        1. Installing an on-premise cluster with the Agent-based Installer
        2. Preparing to install with the Agent-based Installer
        3. Understanding disconnected installation mirroring
        4. Installing a cluster
        5. Installing a cluster with customizations
        6. Preparing PXE assets for OpenShift Container Platform
        7. Preparing installation assets for iSCSI booting
        8. Preparing an Agent-based installed cluster for the multicluster engine for Kubernetes Operator
        9. Installation configuration parameters for the Agent-based Installer
    11. Installing on a single node
        1. Installing on a single node
        2. Preparing to install on a single node
        3. Installing OpenShift on a single node
    12. Installing on bare metal
        1. Installing on bare metal
        2. Preparing for bare metal cluster installation
        3. User-provisioned infrastructure
        4. Installer-provisioned infrastructure
    13. Installing IBM Cloud Bare Metal (Classic)
        1. Installing IBM Cloud Bare Metal (Classic)
        2. Prerequisites
        3. Setting up the environment for an OpenShift Container Platform installation
    14. Installing on IBM Z and IBM LinuxONE
        1. Installing on IBM Z and IBM LinuxONE
        2. Installation methods
        3. User-provisioned infrastructure
        4. Installation configuration parameters for IBM Z and IBM LinuxONE
        5. Configuring additional devices in an IBM Z or IBM LinuxONE environment
    15. Installing on IBM Power
        1. Installing on IBM Power
        2. Installation methods
        3. Installing a cluster on IBM Power
        4. Installing a cluster on IBM Power in a disconnected environment
        5. Installation configuration parameters for IBM Power
    16. Installing on IBM Power Virtual Server
        1. Installing on IBM Power Virtual Server
        2. Installation methods
        3. Configuring an IBM Cloud account
        4. Creating an IBM Power Virtual Server workspace
        5. Installing a cluster on IBM Power Virtual Server with customizations
        6. Installing a cluster on IBM Power Virtual Server into an existing VPC
        7. Installing a private cluster on IBM Power Virtual Server
        8. Installing a cluster on IBM Power Virtual Server in a disconnected environment
        9. Uninstalling a cluster on IBM Power Virtual Server
        10. Installation configuration parameters for IBM Power Virtual Server
    17. Installing on OpenStack
        1. Installing on OpenStack
        2. Preparing to install on OpenStack
        3. Preparing to install a cluster that uses SR-IOV or OVS-DPDK on OpenStack
        4. Installing a cluster on OpenStack with customizations
        5. Installing a cluster on OpenStack on your own infrastructure
        6. Installing a cluster on OpenStack in a disconnected environment
        7. Installing a three-node cluster on OpenStack
        8. Configuring network settings after installing OpenStack
        9. OpenStack Cloud Controller Manager reference guide
        10. Deploying on OpenStack with rootVolume and etcd on local disk
        11. Uninstalling a cluster on OpenStack
        12. Uninstalling a cluster on RHOSP from your own infrastructure
        13. Installation configuration parameters for OpenStack
    18. Installing on OCI
        1. Installing on OCI
        2. Installing a cluster on Oracle Cloud Infrastructure (OCI) by using the Assisted Installer
        3. Installing a cluster on Oracle Cloud Infrastructure (OCI) by using the Agent-based Installer
        4. Installing a cluster on Oracle Compute Cloud@Customer by using the Agent-based Installer
        5. Installing a cluster on Oracle Private Cloud Appliance by using the Agent-based Installer
        6. Installing a cluster on Oracle Compute Cloud@Customer by using the Assisted Installer
    19. Installing on VMware vSphere
        1. Installing on VMware vSphere
        2. Installation methods
        3. Installer-provisioned infrastructure
        4. User-provisioned infrastructure
        5. Installing a cluster on vSphere using the Assisted Installer
        6. Installing a cluster on vSphere using the Agent-based Installer
        7. Installing a three-node cluster on vSphere
        8. Uninstalling a cluster on vSphere that uses installer-provisioned infrastructure
        9. Using the vSphere Problem Detector Operator
        10. Installation configuration parameters for vSphere
        11. Multiple regions and zones configuration for a cluster on VMware vSphere
        12. Enabling encryption on a vSphere cluster
        13. Configuring the vSphere connection settings after an installation
    20. Installing on any platform
        1. Installing on any platform
        2. Installing a cluster on any platform
    21. Installation configuration
        1. Installation configuration
        2. Customizing nodes
        3. Configuring your firewall
        4. Enabling Linux control group version 1 (cgroup v1)
    22. Validation and troubleshooting
        1. Validation and troubleshooting
        2. Validating an installation
        3. Troubleshooting installation issues
6. Upgrade and migrate
    1. Updating clusters
        1. Updating clusters
        2. Understanding OpenShift updates
        3. Preparing to update a cluster
        4. Performing a cluster update
        5. Troubleshooting a cluster update
    2. Migrating from version 3 to 4
        1. Migrating from version 3 to 4
        2. Migration from OpenShift Container Platform 3 to 4 overview
        3. About migrating from OpenShift Container Platform 3 to 4
        4. Differences between OpenShift Container Platform 3 and 4
        5. Network considerations
        6. About the Migration Toolkit for Containers
        7. Installing the Migration Toolkit for Containers
        8. Installing the Migration Toolkit for Containers in a restricted network environment
        9. Upgrading the Migration Toolkit for Containers
        10. Premigration checklists
        11. Migrating your applications
        12. Advanced migration options
        13. Troubleshooting
    3. Migration Toolkit for Containers
        1. Migration Toolkit for Containers
        2. About the Migration Toolkit for Containers
        3. MTC release notes
        4. Installing the Migration Toolkit for Containers
        5. Installing the Migration Toolkit for Containers in a restricted network environment
        6. Upgrading the Migration Toolkit for Containers
        7. Premigration checklists
        8. Network considerations
        9. Direct Migration Requirements
        10. Migrating your applications
        11. Advanced migration options
        12. Troubleshooting
7. Configure
    1. Postinstallation configuration
        1. Postinstallation configuration
        2. Postinstallation configuration overview
        3. Configuring a private cluster
        4. Configuring multi-architecture compute machines on an OpenShift cluster
        5. Postinstallation cluster tasks
        6. Postinstallation node tasks
        7. Postinstallation network configuration
        8. Configuring image streams and image registries
        9. Postinstallation storage configuration
        10. Preparing for users
        11. Changing the cloud provider credentials configuration
        12. Configuring alert notifications
        13. Converting a connected cluster to a disconnected cluster
    2. Backup and restore
        1. Backup and restore
        2. Backup and restore
        3. Shutting down the cluster gracefully
        4. Restarting the cluster gracefully
        5. Hibernating an OpenShift Container Platform cluster
        6. OADP Application backup and restore
        7. Control plane backup and restore
    3. Hosted control planes
        1. Hosted control planes
        2. Hosted control planes release notes
        3. Hosted control planes overview
        4. Preparing to deploy hosted control planes
        5. Deploying hosted control planes
        6. Managing hosted control planes
        7. Deploying hosted control planes in a disconnected environment
        8. Updating hosted control planes
        9. High availability for hosted control planes
        10. Authentication and authorization for hosted control planes
        11. Handling machine configuration for hosted control planes
        12. Using feature gates in a hosted cluster
        13. Observability for hosted control planes
        14. Networking for hosted control planes
        15. Troubleshooting hosted control planes
        16. Destroying a hosted cluster
        17. Manually importing a hosted cluster
    4. Storage
        1. Storage
        2. OpenShift Container Platform storage overview
        3. Understanding ephemeral storage
        4. Understanding persistent storage
        5. Configuring persistent storage
        6. Using Container Storage Interface (CSI)
        7. Generic ephemeral volumes
        8. Expanding persistent volumes
        9. Dynamic provisioning
        10. Detach volumes after non-graceful node shutdown
    5. Networking
        1. Networking
        2. Understanding networking
        3. Accessing hosts
        4. Networking dashboards
        5. Networking Operators
        6. Network security
        7. Configuring an Ingress Controller for manual DNS Management
        8. Verifying connectivity to an endpoint
        9. Changing the MTU for the cluster network
        10. Configuring the node port service range
        11. Configuring the cluster network range
        12. Configuring IP failover
        13. Configuring system controls and interface attributes using the tuning plugin
        14. Using the Stream Control Transmission Protocol (SCTP)
        15. Using Precision Time Protocol hardware
        16. CIDR range definitions
        17. Multiple networks
        18. Hardware networks
        19. OVN-Kubernetes network plugin
        20. Configuring Routes
        21. Configuring ingress cluster traffic
        22. Kubernetes NMState
        23. Configuring the cluster-wide proxy
        24. Configuring a custom PKI
        25. Load balancing on RHOSP
        26. Load balancing with MetalLB
        27. Associating secondary interfaces metrics to network attachments
    6. Nodes
        1. Nodes
        2. Overview of nodes
        3. Working with pods
        4. Automatically scaling pods with the Custom Metrics Autoscaler Operator
        5. Controlling pod placement onto nodes (scheduling)
        6. Using jobs and daemon sets
        7. Working with nodes
        8. Working with containers
        9. Working with clusters
        10. Remote worker nodes on the network edge
        11. Worker nodes for single-node OpenShift clusters
        12. Node metrics dashboard
        13. Manage secure signatures with sigstore
    7. Machine management
        1. Machine management
        2. Overview of machine management
        3. Managing compute machines with the Machine API
        4. Manually scaling a compute machine set
        5. Modifying a compute machine set
        6. Machine phases and lifecycle
        7. Deleting a machine
        8. Applying autoscaling to an OpenShift Container Platform cluster
        9. Creating infrastructure machine sets
        10. Adding RHEL compute machines to an OpenShift Container Platform cluster
        11. Adding more RHEL compute machines to an OpenShift Container Platform cluster
        12. Managing user-provisioned infrastructure manually
        13. Managing control plane machines
        14. Managing machines with the Cluster API
        15. Deploying machine health checks
    8. Machine configuration
        1. Machine configuration
        2. Machine configuration overview
        3. Using machine config objects to configure nodes
        4. Using node disruption policies to minimize disruption from machine config changes
        5. Configuring MCO-related custom resources
        6. Updated boot images
        7. Managing unused rendered machine configs
        8. RHCOS image layering
        9. Machine Config Daemon metrics overview
    9. CLI tools
        1. CLI tools
        2. OpenShift Container Platform CLI tools overview
        3. OpenShift CLI (oc)
        4. OpenShift CLI Manager
        5. Important update on odo
        6. Knative CLI for use with OpenShift Serverless
        7. Pipelines CLI (tkn)
        8. GitOps CLI for use with Red Hat OpenShift GitOps
        9. opm CLI
        10. Operator SDK
    10. Web console
        1. Web console
        2. Web Console Overview
        3. Accessing the web console
        4. Using the OpenShift Container Platform dashboard to get cluster information
        5. Adding user preferences
        6. Configuring the web console in OpenShift Container Platform
        7. Customizing the web console in OpenShift Container Platform
        8. Dynamic plugins
        9. Web terminal
        10. Disabling the web console in OpenShift Container Platform
        11. Creating quick start tutorials in the web console
        12. Optional capabilities and products in the web console
    11. Specialized hardware and driver enablement
        1. Specialized hardware and driver enablement
        2. About specialized hardware and driver enablement
        3. Driver Toolkit
        4. Node Feature Discovery Operator
        5. Kernel Module Management Operator
        6. Kernel Module Management Operator release notes
    12. Scalability and performance
        1. Scalability and performance
        2. Recommended performance and scalability practices
        3. Telco core reference design specifications
        4. Telco RAN DU reference design specifications
        5. Comparing cluster configurations
        6. Planning your environment according to object maximums
        7. Using quotas and limit ranges
        8. Recommended host practices for IBM Z &amp; IBM LinuxONE environments
        9. Using the Node Tuning Operator
        10. Using CPU Manager and Topology Manager
        11. Scheduling NUMA-aware workloads
        12. Scalability and performance optimization
        13. Managing bare-metal hosts
        14. What huge pages do and how they are consumed by applications
        15. Understanding low latency tuning for cluster nodes
        16. Tuning nodes for low latency with the performance profile
        17. Provisioning real-time and low latency workloads
        18. Debugging low latency node tuning status
        19. Performing latency tests for platform verification
        20. Improving cluster stability in high latency environments using worker latency profiles
        21. Workload partitioning
        22. Using the Node Observability Operator
8. Support
    1. Support
        1. Support
        2. Support overview
        3. Managing your cluster resources
        4. Getting support
        5. Remote health monitoring with connected clusters
        6. Gathering data about your cluster
        7. Summarizing cluster specifications
        8. Troubleshooting
9. Develop
    1. Building applications
        1. Building applications
        2. Building applications overview
        3. Projects
        4. Creating applications
        5. Viewing application composition by using the Topology view
        6. Exporting applications
        7. Working with Helm charts
        8. Deployments
        9. Quotas
        10. Using config maps with applications
        11. Monitoring project and application metrics using the Developer perspective
        12. Monitoring application health by using health checks
        13. Editing applications
        14. Pruning objects to reclaim resources
        15. Idling applications
        16. Deleting applications
        17. Using the Red Hat Marketplace
    2. Registry
        1. Registry
        2. OpenShift image registry overview
        3. Image Registry Operator in OpenShift Container Platform
        4. Setting up and configuring the registry
        5. Accessing the registry
        6. Exposing the registry
    3. Images
        1. Images
        2. Overview of images
        3. Configuring the Cluster Samples Operator
        4. Using the Cluster Samples Operator with an alternate registry
        5. Creating images
        6. Managing images
        7. Managing image streams
        8. Using image streams with Kubernetes resources
        9. Triggering updates on image stream changes
        10. Image configuration resources (Classic)
        11. Using images
    4. Serverless
        1. Serverless
        2. About Serverless
    5. OpenShift sandboxed containers
        1. OpenShift sandboxed containers
        2. Documentation moved
10. Security
    1. Security and compliance
        1. Security and compliance
        2. OpenShift Container Platform security and compliance
        3. Container security
        4. Configuring certificates
        5. Certificate types and descriptions
        6. Compliance Operator
        7. File Integrity Operator
        8. Security Profiles Operator
        9. NBDE Tang Server Operator
        10. cert-manager Operator for Red Hat OpenShift
        11. Viewing audit logs
        12. Configuring the audit log policy
        13. Configuring TLS security profiles
        14. Configuring seccomp profiles
        15. Allowing JavaScript-based access to the API server from additional hosts
        16. Encrypting etcd data
        17. Scanning pods for vulnerabilities
        18. Network-Bound Disk Encryption (NBDE)
    2. Authentication and authorization
        1. Authentication and authorization
        2. Overview of authentication and authorization
        3. Understanding authentication
        4. Configuring the internal OAuth server
        5. Configuring OAuth clients
        6. Managing user-owned OAuth access tokens
        7. Understanding identity provider configuration
        8. Configuring identity providers
        9. Using RBAC to define and apply permissions
        10. Removing the kubeadmin user
        11. Understanding and creating service accounts
        12. Using service accounts in applications
        13. Using a service account as an OAuth client
        14. Scoping tokens
        15. Using bound service account tokens
        16. Managing security context constraints
        17. Understanding and managing pod security admission
        18. Impersonating the system:admin user
        19. Syncing LDAP groups
        20. Managing cloud provider credentials
11. Virtualization
    1. Virtualization
        1. Virtualization
        2. About
        3. Release notes
        4. Getting started
        5. Installing
        6. Postinstallation configuration
        7. Updating
        8. Creating a virtual machine
        9. Advanced VM creation
        10. Managing VMs
        11. Networking
        12. Storage
        13. Live migration
        14. Nodes
        15. Monitoring
        16. Support
        17. Backup and restore
12. Edge Computing
    1. Edge computing
        1. Edge computing
        2. Challenges of the network far edge
        3. Preparing the hub cluster for GitOps ZTP
        4. Updating GitOps ZTP
        5. Installing managed clusters with RHACM and SiteConfig resources
        6. Manually installing a single-node OpenShift cluster with GitOps ZTP
        7. Recommended single-node OpenShift cluster configuration for vDU application workloads
        8. Validating single-node OpenShift cluster tuning for vDU application workloads
        9. Advanced managed cluster configuration with SiteConfig resources
        10. Managing cluster policies with PolicyGenerator resources
        11. Managing cluster policies with PolicyGenTemplate resources
        12. Using hub templates in PolicyGenerator or PolicyGenTemplate CRs
        13. Updating managed clusters with the Topology Aware Lifecycle Manager
        14. Expanding single-node OpenShift clusters with GitOps ZTP
        15. Pre-caching images for single-node OpenShift deployments
        16. Image-based upgrade for single-node OpenShift clusters
        17. Image-based installation for single-node OpenShift
        18. Day 2 operations for telco core CNF clusters
    2. Hardware accelerators
        1. Hardware accelerators
        2. About hardware accelerators
        3. NVIDIA GPU architecture
        4. AMD GPU Operator
13. Extend
    1. Extensions
        1. Extensions
        2. Extensions overview
        3. Architecture
        4. Operator Framework glossary of common terms
        5. Catalogs
        6. Catalog selection by name
        7. Catalog selection by labels or expressions
        8. Catalog exclusion by labels or expressions
        9. Catalog selection by priority
        10. Troubleshooting catalog selection errors
        11. Cluster extensions
    2. Operators
        1. Operators
        2. Operators overview
        3. Understanding Operators
        4. User tasks
        5. Administrator tasks
        6. Developing Operators
        7. Cluster Operators reference
        8. OLM v1
14. CI/CD
    1. CI/CD overview
        1. CI/CD overview
        2. About CI/CD
    2. Builds using Shipwright
        1. Builds using Shipwright
        2. Overview of Builds
    3. Builds using BuildConfig
        1. Builds using BuildConfig
        2. Understanding image builds
        3. Understanding build configurations
        4. Creating build inputs
        5. Managing build output
        6. Using build strategies
        7. Custom image builds with Buildah
        8. Performing and configuring basic builds
        9. Triggering and modifying builds
        10. Performing advanced builds
        11. Using Red Hat subscriptions in builds
        12. Securing builds by strategy
        13. Build configuration resources
        14. Troubleshooting builds
        15. Setting up additional trusted certificate authorities for builds
    4. GitOps
        1. GitOps
        2. About Red Hat OpenShift GitOps
    5. Pipelines
        1. Pipelines
        2. About Red Hat OpenShift Pipelines
    6. Jenkins
        1. Jenkins
        2. Configuring Jenkins images
        3. Jenkins agent
        4. Migrating from Jenkins to OpenShift Pipelines or Tekton
        5. Important changes to OpenShift Jenkins images
15. Observability
    1. Observability overview
        1. Observability overview
        2. About Observability
    2. Monitoring
        1. Monitoring
        2. About OpenShift Container Platform monitoring
        3. Getting started
        4. Configuring core platform monitoring
        5. Configuring user workload monitoring
        6. Accessing metrics
        7. Managing alerts
        8. Troubleshooting monitoring issues
        9. Config map reference for the Cluster Monitoring Operator
        10. Monitoring clusters that run on RHOSO
    3. Power Monitoring
        1. Power Monitoring
        2. Power monitoring for Red Hat OpenShift release notes
        3. Power monitoring overview
        4. Installing power monitoring for Red Hat OpenShift
        5. Configuring power monitoring
        6. Visualizing power monitoring metrics
        7. Uninstalling power monitoring
    4. Network Observability
        1. Network Observability
        2. Network Observability Operator release notes
        3. About Network Observability
        4. Installing the Network Observability Operator
        5. Network Observability Operator in OpenShift Container Platform
        6. Configuring the Network Observability Operator
        7. Network Policy
        8. Observing the network traffic
        9. Using metrics with dashboards and alerts
        10. Monitoring the Network Observability Operator
        11. Scheduling resources
        12. Secondary networks
        13. Network Observability CLI
        14. FlowCollector API reference
        15. FlowMetric configuration parameters
        16. Network flows format reference
        17. Troubleshooting Network Observability
    5. Logging
        1. Logging
        2. Logging 6.2
        3. Logging 6.1
    6. Cluster Observability Operator
        1. Cluster Observability Operator
        2. Cluster Observability Operator release notes
        3. Cluster Observability Operator overview
        4. Installing the Cluster Observability Operator
        5. Configuring the Cluster Observability Operator to monitor a service
        6. Observability UI plugins
    7. Red Hat build of OpenTelemetry
        1. Red Hat build of OpenTelemetry
        2. Release notes for the Red Hat build of OpenTelemetry
        3. Installing
        4. Configuring the Collector
        5. Configuring the instrumentation
        6. Sending traces and metrics to the OpenTelemetry Collector
        7. Configuring metrics for the monitoring stack
        8. Forwarding telemetry data
        9. Configuring the OpenTelemetry Collector metrics
        10. Gathering the observability data from multiple clusters
        11. Troubleshooting
        12. Migrating
        13. Upgrading
        14. Removing
    8. Distributed tracing
        1. Distributed tracing
        2. Release notes for the Red Hat OpenShift distributed tracing platform
        3. Distributed tracing architecture
        4. Distributed tracing platform (Tempo)
        5. Distributed tracing platform (Jaeger)
16. Integration
    1. Lightspeed
        1. Lightspeed
        2. About Lightspeed
    2. Service Mesh
        1. Service Mesh
        2. Service Mesh 3.x
        3. Service Mesh 2.x
        4. Service Mesh 1.x
    3. Windows Container Support for OpenShift
        1. Windows Container Support for OpenShift
        2. Red Hat OpenShift support for Windows Containers overview
        3. Release notes
        4. Getting support
        5. Understanding Windows container workloads
        6. Enabling Windows container workloads
        7. Creating Windows machine sets
        8. Scheduling Windows container workloads
        9. Windows node updates
        10. Using Bring-Your-Own-Host (BYOH) Windows instances as nodes
        11. Removing Windows nodes
        12. Disabling Windows container workloads
17. API Reference
    1. API overview
        1. API overview
        2. Understanding API tiers
        3. Understanding API compatibility guidelines
        4. Editing kubelet log level verbosity and gathering logs
        5. API index
    2. Common object reference
        1. Common object reference
        2. Common object reference
    3. Authorization APIs
        1. Authorization APIs
        2. Authorization APIs
        3. LocalResourceAccessReview [authorization.openshift.io/v1]
        4. LocalSubjectAccessReview [authorization.openshift.io/v1]
        5. ResourceAccessReview [authorization.openshift.io/v1]
        6. SelfSubjectRulesReview [authorization.openshift.io/v1]
        7. SubjectAccessReview [authorization.openshift.io/v1]
        8. SubjectRulesReview [authorization.openshift.io/v1]
        9. SelfSubjectReview [authentication.k8s.io/v1]
        10. TokenRequest [authentication.k8s.io/v1]
        11. TokenReview [authentication.k8s.io/v1]
        12. LocalSubjectAccessReview [authorization.k8s.io/v1]
        13. SelfSubjectAccessReview [authorization.k8s.io/v1]
        14. SelfSubjectRulesReview [authorization.k8s.io/v1]
        15. SubjectAccessReview [authorization.k8s.io/v1]
    4. Autoscale APIs
        1. Autoscale APIs
        2. Autoscale APIs
        3. ClusterAutoscaler [autoscaling.openshift.io/v1]
        4. MachineAutoscaler [autoscaling.openshift.io/v1beta1]
        5. HorizontalPodAutoscaler [autoscaling/v2]
        6. Scale [autoscaling/v1]
    5. Cluster APIs
        1. Cluster APIs
        2. Cluster APIs
        3. IPAddress [ipam.cluster.x-k8s.io/v1beta1]
        4. IPAddressClaim [ipam.cluster.x-k8s.io/v1beta1]
    6. Config APIs
        1. Config APIs
        2. Config APIs
        3. APIServer [config.openshift.io/v1]
        4. Authentication [config.openshift.io/v1]
        5. Build [config.openshift.io/v1]
        6. ClusterOperator [config.openshift.io/v1]
        7. ClusterVersion [config.openshift.io/v1]
        8. Console [config.openshift.io/v1]
        9. DNS [config.openshift.io/v1]
        10. FeatureGate [config.openshift.io/v1]
        11. HelmChartRepository [helm.openshift.io/v1beta1]
        12. Image [config.openshift.io/v1]
        13. ImageDigestMirrorSet [config.openshift.io/v1]
        14. ImageContentPolicy [config.openshift.io/v1]
        15. ImageTagMirrorSet [config.openshift.io/v1]
        16. Infrastructure [config.openshift.io/v1]
        17. Ingress [config.openshift.io/v1]
        18. Network [config.openshift.io/v1]
        19. Node [config.openshift.io/v1]
        20. OAuth [config.openshift.io/v1]
        21. OperatorHub [config.openshift.io/v1]
        22. Project [config.openshift.io/v1]
        23. ProjectHelmChartRepository [helm.openshift.io/v1beta1]
        24. Proxy [config.openshift.io/v1]
        25. Scheduler [config.openshift.io/v1]
    7. Console APIs
        1. Console APIs
        2. Console APIs
        3. ConsoleCLIDownload [console.openshift.io/v1]
        4. ConsoleExternalLogLink [console.openshift.io/v1]
        5. ConsoleLink [console.openshift.io/v1]
        6. ConsoleNotification [console.openshift.io/v1]
        7. ConsolePlugin [console.openshift.io/v1]
        8. ConsoleQuickStart [console.openshift.io/v1]
        9. ConsoleSample [console.openshift.io/v1]
        10. ConsoleYAMLSample [console.openshift.io/v1]
    8. Extension APIs
        1. Extension APIs
        2. Extension APIs
        3. APIService [apiregistration.k8s.io/v1]
        4. CustomResourceDefinition [apiextensions.k8s.io/v1]
        5. MutatingWebhookConfiguration [admissionregistration.k8s.io/v1]
        6. ValidatingAdmissionPolicy [admissionregistration.k8s.io/v1]
        7. ValidatingAdmissionPolicyBinding [admissionregistration.k8s.io/v1]
        8. ValidatingWebhookConfiguration [admissionregistration.k8s.io/v1]
    9. Image APIs
        1. Image APIs
        2. Image APIs
        3. Image [image.openshift.io/v1]
        4. ImageSignature [image.openshift.io/v1]
        5. ImageStreamImage [image.openshift.io/v1]
        6. ImageStreamImport [image.openshift.io/v1]
        7. ImageStreamLayers [image.openshift.io/v1]
        8. ImageStreamMapping [image.openshift.io/v1]
        9. ImageStream [image.openshift.io/v1]
        10. ImageStreamTag [image.openshift.io/v1]
        11. ImageTag [image.openshift.io/v1]
        12. SecretList [image.openshift.io/v1]
    10. Machine APIs
        1. Machine APIs
        2. Machine APIs
        3. ContainerRuntimeConfig [machineconfiguration.openshift.io/v1]
        4. ControllerConfig [machineconfiguration.openshift.io/v1]
        5. ControlPlaneMachineSet [machine.openshift.io/v1]
        6. KubeletConfig [machineconfiguration.openshift.io/v1]
        7. MachineConfig [machineconfiguration.openshift.io/v1]
        8. MachineConfigPool [machineconfiguration.openshift.io/v1]
        9. MachineHealthCheck [machine.openshift.io/v1beta1]
        10. Machine [machine.openshift.io/v1beta1]
        11. MachineSet [machine.openshift.io/v1beta1]
    11. Metadata APIs
        1. Metadata APIs
        2. Metadata APIs
        3. APIRequestCount [apiserver.openshift.io/v1]
        4. Binding [v1]
        5. ComponentStatus [v1]
        6. ConfigMap [v1]
        7. ControllerRevision [apps/v1]
        8. Event [events.k8s.io/v1]
        9. Event [v1]
        10. Lease [coordination.k8s.io/v1]
        11. Namespace [v1]
    12. Monitoring APIs
        1. Monitoring APIs
        2. Monitoring APIs
        3. Alertmanager [monitoring.coreos.com/v1]
        4. AlertmanagerConfig [monitoring.coreos.com/v1beta1]
        5. AlertRelabelConfig [monitoring.openshift.io/v1]
        6. AlertingRule [monitoring.openshift.io/v1]
        7. PodMonitor [monitoring.coreos.com/v1]
        8. Probe [monitoring.coreos.com/v1]
        9. Prometheus [monitoring.coreos.com/v1]
        10. PrometheusRule [monitoring.coreos.com/v1]
        11. ServiceMonitor [monitoring.coreos.com/v1]
        12. ThanosRuler [monitoring.coreos.com/v1]
        13. NodeMetrics [metrics.k8s.io/v1beta1]
        14. PodMetrics [metrics.k8s.io/v1beta1]
    13. Network APIs
        1. Network APIs
        2. Network APIs
        3. AdminNetworkPolicy [policy.networking.k8s.io/v1alpha1]
        4. AdminPolicyBasedExternalRoute [k8s.ovn.org/v1]
        5. BaselineAdminNetworkPolicy [policy.networking.k8s.io/v1alpha1]
        6. CloudPrivateIPConfig [cloud.network.openshift.io/v1]
        7. EgressFirewall [k8s.ovn.org/v1]
        8. EgressIP [k8s.ovn.org/v1]
        9. EgressQoS [k8s.ovn.org/v1]
        10. EgressService [k8s.ovn.org/v1]
        11. Endpoints [v1]
        12. EndpointSlice [discovery.k8s.io/v1]
        13. EgressRouter [network.operator.openshift.io/v1]
        14. Ingress [networking.k8s.io/v1]
        15. IngressClass [networking.k8s.io/v1]
        16. IPPool [whereabouts.cni.cncf.io/v1alpha1]
        17. MultiNetworkPolicy [k8s.cni.cncf.io/v1beta1]
        18. NetworkAttachmentDefinition [k8s.cni.cncf.io/v1]
        19. NetworkPolicy [networking.k8s.io/v1]
        20. OverlappingRangeIPReservation [whereabouts.cni.cncf.io/v1alpha1]
        21. PodNetworkConnectivityCheck [controlplane.operator.openshift.io/v1alpha1]
        22. Route [route.openshift.io/v1]
        23. Service [v1]
    14. Node APIs
        1. Node APIs
        2. Node APIs
        3. Node [v1]
        4. PerformanceProfile [performance.openshift.io/v2]
        5. Profile [tuned.openshift.io/v1]
        6. RuntimeClass [node.k8s.io/v1]
        7. Tuned [tuned.openshift.io/v1]
    15. OAuth APIs
        1. OAuth APIs
        2. OAuth APIs
        3. OAuthAccessToken [oauth.openshift.io/v1]
        4. OAuthAuthorizeToken [oauth.openshift.io/v1]
        5. OAuthClientAuthorization [oauth.openshift.io/v1]
        6. OAuthClient [oauth.openshift.io/v1]
        7. UserOAuthAccessToken [oauth.openshift.io/v1]
    16. Operator APIs
        1. Operator APIs
        2. Operator APIs
        3. Authentication [operator.openshift.io/v1]
        4. CloudCredential [operator.openshift.io/v1]
        5. ClusterCSIDriver [operator.openshift.io/v1]
        6. Console [operator.openshift.io/v1]
        7. Config [operator.openshift.io/v1]
        8. Config [imageregistry.operator.openshift.io/v1]
        9. Config [samples.operator.openshift.io/v1]
        10. CSISnapshotController [operator.openshift.io/v1]
        11. DNS [operator.openshift.io/v1]
        12. DNSRecord [ingress.operator.openshift.io/v1]
        13. Etcd [operator.openshift.io/v1]
        14. ImageContentSourcePolicy [operator.openshift.io/v1alpha1]
        15. ImagePruner [imageregistry.operator.openshift.io/v1]
        16. IngressController [operator.openshift.io/v1]
        17. InsightsOperator [operator.openshift.io/v1]
        18. KubeAPIServer [operator.openshift.io/v1]
        19. KubeControllerManager [operator.openshift.io/v1]
        20. KubeScheduler [operator.openshift.io/v1]
        21. KubeStorageVersionMigrator [operator.openshift.io/v1]
        22. MachineConfiguration [operator.openshift.io/v1]
        23. Network [operator.openshift.io/v1]
        24. OpenShiftAPIServer [operator.openshift.io/v1]
        25. OpenShiftControllerManager [operator.openshift.io/v1]
        26. OperatorPKI [network.operator.openshift.io/v1]
        27. ServiceCA [operator.openshift.io/v1]
        28. Storage [operator.openshift.io/v1]
    17. OperatorHub APIs
        1. OperatorHub APIs
        2. OperatorHub APIs
        3. CatalogSource [operators.coreos.com/v1alpha1]
        4. ClusterServiceVersion [operators.coreos.com/v1alpha1]
        5. InstallPlan [operators.coreos.com/v1alpha1]
        6. OLMConfig [operators.coreos.com/v1]
        7. Operator [operators.coreos.com/v1]
        8. OperatorCondition [operators.coreos.com/v2]
        9. OperatorGroup [operators.coreos.com/v1]
        10. PackageManifest [packages.operators.coreos.com/v1]
        11. Subscription [operators.coreos.com/v1alpha1]
    18. Policy APIs
        1. Policy APIs
        2. Policy APIs
        3. Eviction [policy/v1]
        4. PodDisruptionBudget [policy/v1]
    19. Project APIs
        1. Project APIs
        2. Project APIs
        3. Project [project.openshift.io/v1]
        4. ProjectRequest [project.openshift.io/v1]
    20. Provisioning APIs
        1. Provisioning APIs
        2. Provisioning APIs
        3. BMCEventSubscription [metal3.io/v1alpha1]
        4. BareMetalHost [metal3.io/v1alpha1]
        5. DataImage [metal3.io/v1alpha1]
        6. FirmwareSchema [metal3.io/v1alpha1]
        7. HardwareData [metal3.io/v1alpha1]
        8. HostFirmwareComponents [metal3.io/v1alpha1]
        9. HostFirmwareSettings [metal3.io/v1alpha1]
        10. Metal3Remediation [infrastructure.cluster.x-k8s.io/v1beta1]
        11. Metal3RemediationTemplate [infrastructure.cluster.x-k8s.io/v1beta1]
        12. PreprovisioningImage [metal3.io/v1alpha1]
        13. Provisioning [metal3.io/v1alpha1]
    21. RBAC APIs
        1. RBAC APIs
        2. RBAC APIs
        3. ClusterRoleBinding [rbac.authorization.k8s.io/v1]
        4. ClusterRole [rbac.authorization.k8s.io/v1]
        5. RoleBinding [rbac.authorization.k8s.io/v1]
        6. Role [rbac.authorization.k8s.io/v1]
    22. Role APIs
        1. Role APIs
        2. Role APIs
        3. ClusterRoleBinding [authorization.openshift.io/v1]
        4. ClusterRole [authorization.openshift.io/v1]
        5. RoleBindingRestriction [authorization.openshift.io/v1]
        6. RoleBinding [authorization.openshift.io/v1]
        7. Role [authorization.openshift.io/v1]
    23. Schedule and quota APIs
        1. Schedule and quota APIs
        2. Schedule and quota APIs
        3. AppliedClusterResourceQuota [quota.openshift.io/v1]
        4. ClusterResourceQuota [quota.openshift.io/v1]
        5. FlowSchema [flowcontrol.apiserver.k8s.io/v1]
        6. LimitRange [v1]
        7. PriorityClass [scheduling.k8s.io/v1]
        8. PriorityLevelConfiguration [flowcontrol.apiserver.k8s.io/v1]
        9. ResourceQuota [v1]
    24. Security APIs
        1. Security APIs
        2. Security APIs
        3. CertificateSigningRequest [certificates.k8s.io/v1]
        4. CredentialsRequest [cloudcredential.openshift.io/v1]
        5. PodSecurityPolicyReview [security.openshift.io/v1]
        6. PodSecurityPolicySelfSubjectReview [security.openshift.io/v1]
        7. PodSecurityPolicySubjectReview [security.openshift.io/v1]
        8. RangeAllocation [security.openshift.io/v1]
        9. Secret [v1]
        10. SecurityContextConstraints [security.openshift.io/v1]
        11. ServiceAccount [v1]
    25. Storage APIs
        1. Storage APIs
        2. Storage APIs
        3. CSIDriver [storage.k8s.io/v1]
        4. CSINode [storage.k8s.io/v1]
        5. CSIStorageCapacity [storage.k8s.io/v1]
        6. PersistentVolume [v1]
        7. PersistentVolumeClaim [v1]
        8. StorageClass [storage.k8s.io/v1]
        9. StorageState [migration.k8s.io/v1alpha1]
        10. StorageVersionMigration [migration.k8s.io/v1alpha1]
        11. VolumeAttachment [storage.k8s.io/v1]
        12. VolumeSnapshot [snapshot.storage.k8s.io/v1]
        13. VolumeSnapshotClass [snapshot.storage.k8s.io/v1]
        14. VolumeSnapshotContent [snapshot.storage.k8s.io/v1]
    26. Template APIs
        1. Template APIs
        2. Template APIs
        3. BrokerTemplateInstance [template.openshift.io/v1]
        4. PodTemplate [v1]
        5. Template [template.openshift.io/v1]
        6. TemplateInstance [template.openshift.io/v1]
18. Legal Notice

# Installation overview

#### Overview content for installing OpenShift Container Platform

Abstract

This document provides an overview on how to install OpenShift Container Platform.

### Chapter 1. OpenShift Container Platform installation overview

#### 1.1. About OpenShift Container Platform installation

The OpenShift Container Platform installation program offers four methods for deploying a cluster which are detailed in the following list:

- Interactive: You can deploy a cluster with the web-based Assisted Installer. This is an ideal approach for clusters with networks connected to the internet. The Assisted Installer is the easiest way to install OpenShift Container Platform, it provides smart defaults, and it performs pre-flight validations before installing the cluster. It also provides a RESTful API for automation and advanced configuration scenarios.
- Local Agent-based: You can deploy a cluster locally with the Agent-based Installer for disconnected environments or restricted networks. It provides many of the benefits of the Assisted Installer, but you must download and configure the Agent-based Installer first. Configuration is done with a command-line interface. This approach is ideal for disconnected environments.
- Automated: You can deploy a cluster on installer-provisioned infrastructure. The installation program uses each cluster host’s baseboard management controller (BMC) for provisioning. You can deploy clusters in connected or disconnected environments.
- Full control: You can deploy a cluster on infrastructure that you prepare and maintain, which provides maximum customizability. You can deploy clusters in connected or disconnected environments.

Each method deploys a cluster with the following characteristics:

- Highly available infrastructure with no single points of failure, which is available by default.
- Administrators can control what updates are applied and when.

##### 1.1.1. About the installation program

You can use the installation program to deploy each type of cluster. The installation program generates the main assets, such as Ignition config files for the bootstrap, control plane, and compute machines. You can start an OpenShift Container Platform cluster with these three machine configurations, provided you correctly configured the infrastructure.

The OpenShift Container Platform installation program uses a set of targets and dependencies to manage cluster installations. The installation program has a set of targets that it must achieve, and each target has a set of dependencies. Because each target is only concerned with its own dependencies, the installation program can act to achieve multiple targets in parallel with the ultimate target being a running cluster. The installation program recognizes and uses existing components instead of running commands to create them again because the program meets the dependencies.

Figure 1.1. OpenShift Container Platform installation targets and dependencies

<!-- 🖼️❌ Image not available. Please use `PdfPipelineOptions(generate_picture_images=True)` -->

##### 1.1.2. About Red Hat Enterprise Linux CoreOS (RHCOS)

Post-installation, each cluster machine uses Red Hat Enterprise Linux CoreOS (RHCOS) as the operating system. RHCOS is the immutable container host version of Red Hat Enterprise Linux (RHEL) and features a RHEL kernel with SELinux enabled by default. RHCOS includes the kubelet, which is the Kubernetes node agent, and the CRI-O container runtime, which is optimized for Kubernetes.

Every control plane machine in an OpenShift Container Platform 4.18 cluster must use RHCOS, which includes a critical first-boot provisioning tool called Ignition. This tool enables the cluster to configure the machines. Operating system updates are delivered as a bootable container image, using OSTree as a backend, that is deployed across the cluster by the Machine Config Operator. Actual operating system changes are made in-place on each machine as an atomic operation by using rpm-ostree. Together, these technologies enable OpenShift Container Platform to manage the operating system like it manages any other application on the cluster, by in-place upgrades that keep the entire platform up to date. These in-place updates can reduce the burden on operations teams.

If you use RHCOS as the operating system for all cluster machines, the cluster manages all aspects of its components and machines, including the operating system. Because of this, only the installation program and the Machine Config Operator can change machines. The installation program uses Ignition config files to set the exact state of each machine, and the Machine Config Operator completes more changes to the machines, such as the application of new certificates or keys, after installation.

##### 1.1.3. Glossary of common terms for OpenShift Container Platform installing

The glossary defines common terms that relate to the installation content. Read the following list of terms to better understand the installation process.

##### 1.1.4. Installation process

Except for the Assisted Installer, when you install an OpenShift Container Platform cluster, you must download the installation program from the appropriate Cluster Type page on the OpenShift Cluster Manager Hybrid Cloud Console. This console manages:

- REST API for accounts.
- Registry tokens, which are the pull secrets that you use to obtain the required components.
- Cluster registration, which associates the cluster identity to your Red Hat account to facilitate the gathering of usage metrics.

In OpenShift Container Platform 4.18, the installation program is a Go binary file that performs a series of file transformations on a set of assets. The way you interact with the installation program differs depending on your installation type. Consider the following installation use cases:

- To deploy a cluster with the Assisted Installer, you must configure the cluster settings by using the Assisted Installer. There is no installation program to download and configure. After you finish setting the cluster configuration, you download a discovery ISO and then boot cluster machines with that image. You can install clusters with the Assisted Installer on Nutanix, vSphere, and bare metal with full integration, and other platforms without integration. If you install on bare metal, you must provide all of the cluster infrastructure and resources, including the networking, load balancing, storage, and individual cluster machines.
- To deploy clusters with the Agent-based Installer, you can download the Agent-based Installer first. You can then configure the cluster and generate a discovery image. You boot cluster machines with the discovery image, which installs an agent that communicates with the installation program and handles the provisioning for you instead of you interacting with the installation program or setting up a provisioner machine yourself. You must provide all of the cluster infrastructure and resources, including the networking, load balancing, storage, and individual cluster machines. This approach is ideal for disconnected environments.
- For clusters with installer-provisioned infrastructure, you delegate the infrastructure bootstrapping and provisioning to the installation program instead of doing it yourself. The installation program creates all of the networking, machines, and operating systems that are required to support the cluster, except if you install on bare metal. If you install on bare metal, you must provide all of the cluster infrastructure and resources, including the bootstrap machine, networking, load balancing, storage, and individual cluster machines.
- If you provision and manage the infrastructure for your cluster, you must provide all of the cluster infrastructure and resources, including the bootstrap machine, networking, load balancing, storage, and individual cluster machines.

For the installation program, the program uses three sets of files during installation: an installation configuration file that is named install-config.yaml, Kubernetes manifests, and Ignition config files for your machine types.

Important

You can modify Kubernetes and the Ignition config files that control the underlying RHCOS operating system during installation. However, no validation is available to confirm the suitability of any modifications that you make to these objects. If you modify these objects, you might render your cluster non-functional. Because of this risk, modifying Kubernetes and Ignition config files is not supported unless you are following documented procedures or are instructed to do so by Red Hat support.

The installation configuration file is transformed into Kubernetes manifests, and then the manifests are wrapped into Ignition config files. The installation program uses these Ignition config files to create the cluster.

The installation configuration files are all pruned when you run the installation program, so be sure to back up all the configuration files that you want to use again.

Important

You cannot modify the parameters that you set during installation, but you can modify many cluster attributes after installation.

###### The installation process with the Assisted Installer

Installation with the Assisted Installer involves creating a cluster configuration interactively by using the web-based user interface or the RESTful API. The Assisted Installer user interface prompts you for required values and provides reasonable default values for the remaining parameters, unless you change them in the user interface or with the API. The Assisted Installer generates a discovery image, which you download and use to boot the cluster machines. The image installs RHCOS and an agent, and the agent handles the provisioning for you. You can install OpenShift Container Platform with the Assisted Installer and full integration on Nutanix, vSphere, and bare metal. Additionally, you can install OpenShift Container Platform with the Assisted Installer on other platforms without integration.

OpenShift Container Platform manages all aspects of the cluster, including the operating system itself. Each machine boots with a configuration that references resources hosted in the cluster that it joins. This configuration allows the cluster to manage itself as updates are applied.

If possible, use the Assisted Installer feature to avoid having to download and configure the Agent-based Installer.

###### The installation process with Agent-based infrastructure

Agent-based installation is similar to using the Assisted Installer, except that you must initially download and install the Agent-based Installer. An Agent-based installation is useful when you want the convenience of the Assisted Installer, but you need to install a cluster in a disconnected environment.

If possible, use the Agent-based installation feature to avoid having to create a provisioner machine with a bootstrap VM, and then provision and maintain the cluster infrastructure.

###### The installation process with installer-provisioned infrastructure

The default installation type uses installer-provisioned infrastructure. By default, the installation program acts as an installation wizard, prompting you for values that it cannot determine on its own and providing reasonable default values for the remaining parameters. You can also customize the installation process to support advanced infrastructure scenarios. The installation program provisions the underlying infrastructure for the cluster.

You can install either a standard cluster or a customized cluster. With a standard cluster, you provide minimum details that are required to install the cluster. With a customized cluster, you can specify more details about the platform, such as the number of machines that the control plane uses, the type of virtual machine that the cluster deploys, or the CIDR range for the Kubernetes service network.

If possible, use this feature to avoid having to provision and maintain the cluster infrastructure. In all other environments, you use the installation program to generate the assets that you require to provision your cluster infrastructure.

With installer-provisioned infrastructure clusters, OpenShift Container Platform manages all aspects of the cluster, including the operating system itself. Each machine boots with a configuration that references resources hosted in the cluster that it joins. This configuration allows the cluster to manage itself as updates are applied.

###### The installation process with user-provisioned infrastructure

You can also install OpenShift Container Platform on infrastructure that you provide. You use the installation program to generate the assets that you require to provision the cluster infrastructure, create the cluster infrastructure, and then deploy the cluster to the infrastructure that you provided.

If you do not use infrastructure that the installation program provisioned, you must manage and maintain the cluster resources yourself. The following list details some of these self-managed resources:

- The underlying infrastructure for the control plane and compute machines that make up the cluster
- Load balancers
- Cluster networking, including the DNS records and required subnets
- Storage for the cluster infrastructure and applications

If your cluster uses user-provisioned infrastructure, you have the option of adding RHEL compute machines to your cluster.

###### Installation process details

When a cluster is provisioned, each machine in the cluster requires information about the cluster. OpenShift Container Platform uses a temporary bootstrap machine during initial configuration to provide the required information to the permanent control plane. The temporary bootstrap machine boots by using an Ignition config file that describes how to create the cluster. The bootstrap machine creates the control plane machines that make up the control plane. The control plane machines then create the compute machines, which are also known as worker machines. The following figure illustrates this process:

Figure 1.2. Creating the bootstrap, control plane, and compute machines

<!-- 🖼️❌ Image not available. Please use `PdfPipelineOptions(generate_picture_images=True)` -->

Important

While planning to deploy your cluster, ensure that you are familiar with the recommended practices for performance and scalability, particularly the requirements for input/output (I/O) latency for etcd storage and the requirements for the recommended control plane node sizing. For more information, see “Recommended etcd practices” and “Control plane node sizing”.

After the cluster machines initialize, the bootstrap machine is destroyed. All clusters use the bootstrap process to initialize the cluster, but if you provision the infrastructure for your cluster, you must complete many of the steps manually.

Important

- The Ignition config files that the installation program generates contain certificates that expire after 24 hours, which are then renewed at that time. If the cluster is shut down before renewing the certificates and the cluster is later restarted after the 24 hours have elapsed, the cluster automatically recovers the expired certificates. The exception is that you must manually approve the pending node-bootstrapper certificate signing requests (CSRs) to recover kubelet certificates. See the documentation for Recovering from expired control plane certificates for more information.
- Consider using Ignition config files within 12 hours after they are generated, because the 24-hour certificate rotates from 16 to 22 hours after the cluster is installed. By using the Ignition config files within 12 hours, you can avoid installation failure if the certificate update runs during installation.

Bootstrapping a cluster involves the following steps:

1. The bootstrap machine boots and starts hosting the remote resources required for the control plane machines to boot. If you provision the infrastructure, this step requires manual intervention.
2. The bootstrap machine starts a single-node etcd cluster and a temporary Kubernetes control plane.
3. The control plane machines fetch the remote resources from the bootstrap machine and finish booting. If you provision the infrastructure, this step requires manual intervention.
4. The temporary control plane schedules the production control plane to the production control plane machines.
5. The Cluster Version Operator (CVO) comes online and installs the etcd Operator. The etcd Operator scales up etcd on all control plane nodes.
6. The temporary control plane shuts down and passes control to the production control plane.
7. The bootstrap machine injects OpenShift Container Platform components into the production control plane.
8. The installation program shuts down the bootstrap machine. If you provision the infrastructure, this step requires manual intervention.
9. The control plane sets up the compute nodes.
10. The control plane installs additional services in the form of a set of Operators.

The result of this bootstrapping process is a running OpenShift Container Platform cluster. The cluster then downloads and configures remaining components needed for the day-to-day operations, including the creation of compute machines in supported environments.

Additional resources

- Recommended etcd practices
- Control plane node sizing
- Red Hat OpenShift Network Calculator

##### 1.1.5. Verifying node state after installation

The OpenShift Container Platform installation completes when the following installation health checks are successful:

- The provisioner can access the OpenShift Container Platform web console.
- All control plane nodes are ready.
- All cluster Operators are available.

Note

After the installation completes, the specific cluster Operators responsible for the worker nodes continuously attempt to provision all worker nodes. Some time is required before all worker nodes report as READY. For installations on bare metal, wait a minimum of 60 minutes before troubleshooting a worker node. For installations on all other platforms, wait a minimum of 40 minutes before troubleshooting a worker node. A DEGRADED state for the cluster Operators responsible for the worker nodes depends on the Operators' own resources and not on the state of the nodes.

After your installation completes, you can continue to monitor the condition of the nodes in your cluster.

Prerequisites

- The installation program resolves successfully in the terminal.

Procedure

1. Show the status of all worker nodes:
						$ oc get nodesExample output
NAME                           STATUS   ROLES    AGE   VERSION
example-compute1.example.com   Ready    worker   13m   v1.21.6+bb8d50a
example-compute2.example.com   Ready    worker   13m   v1.21.6+bb8d50a
example-compute4.example.com   Ready    worker   14m   v1.21.6+bb8d50a
example-control1.example.com   Ready    master   52m   v1.21.6+bb8d50a
example-control2.example.com   Ready    master   55m   v1.21.6+bb8d50a
example-control3.example.com   Ready    master   55m   v1.21.6+bb8d50a
2. Show the phase of all worker machine nodes:
						$ oc get machines -AExample output
NAMESPACE               NAME                           PHASE         TYPE   REGION   ZONE   AGE
openshift-machine-api   example-zbbt6-master-0         Running                              95m
openshift-machine-api   example-zbbt6-master-1         Running                              95m
openshift-machine-api   example-zbbt6-master-2         Running                              95m
openshift-machine-api   example-zbbt6-worker-0-25bhp   Running                              49m
openshift-machine-api   example-zbbt6-worker-0-8b4c2   Running                              49m
openshift-machine-api   example-zbbt6-worker-0-jkbqt   Running                              49m
openshift-machine-api   example-zbbt6-worker-0-qrl5b   Running                              49m

Additional resources

- Getting the BareMetalHost resource
- Following the progress of the installation
- Validating an installation
- Agent-based Installer
- Assisted Installer for OpenShift Container Platform

###### Installation scope

The scope of the OpenShift Container Platform installation program is intentionally narrow. It is designed for simplicity and ensured success. You can complete many more configuration tasks after installation completes.

Additional resources

- See Available cluster customizations for details about OpenShift Container Platform configuration resources.

##### 1.1.6. OpenShift Local overview

OpenShift Local supports rapid application development to get started building OpenShift Container Platform clusters. OpenShift Local is designed to run on a local computer to simplify setup and testing, and to emulate the cloud development environment locally with all of the tools needed to develop container-based applications.

Regardless of the programming language you use, OpenShift Local hosts your application and brings a minimal, preconfigured Red Hat OpenShift Container Platform cluster to your local PC without the need for a server-based infrastructure.

On a hosted environment, OpenShift Local can create microservices, convert them into images, and run them in Kubernetes-hosted containers directly on your laptop or desktop running Linux, macOS, or Windows 10 or later.

For more information about OpenShift Local, see Red Hat OpenShift Local Overview.

#### 1.2. Supported platforms for OpenShift Container Platform clusters

In OpenShift Container Platform 4.18, you can install a cluster that uses installer-provisioned infrastructure on the following platforms:

- Amazon Web Services (AWS)
- Bare metal
- Google Cloud Platform (GCP)
- IBM Cloud®
- Microsoft Azure
- Microsoft Azure Stack Hub
- Nutanix
- Red Hat OpenStack Platform (RHOSP)
- Red Hat OpenStack Platform (RHOSP)
    - The latest OpenShift Container Platform release supports both the latest RHOSP long-life release and intermediate release. For complete RHOSP release compatibility, see the OpenShift Container Platform on RHOSP support matrix.
- VMware vSphere

For these clusters, all machines, including the computer that you run the installation process on, must have direct internet access to pull images for platform containers and provide telemetry data to Red Hat.

Important

After installation, the following changes are not supported:

- Mixing cloud provider platforms.
- Mixing cloud provider components. For example, using a persistent storage framework from a another platform on the platform where you installed the cluster.

In OpenShift Container Platform 4.18, you can install a cluster that uses user-provisioned infrastructure on the following platforms:

- AWS
- Azure
- Azure Stack Hub
- Bare metal
- GCP
- IBM Power®
- IBM Z® or IBM® LinuxONE
- RHOSP
- RHOSP
    - The latest OpenShift Container Platform release supports both the latest RHOSP long-life release and intermediate release. For complete RHOSP release compatibility, see the OpenShift Container Platform on RHOSP support matrix.
- VMware Cloud on AWS
- VMware vSphere

Depending on the supported cases for the platform, you can perform installations on user-provisioned infrastructure, so that you can run machines with full internet access, place your cluster behind a proxy, or perform a disconnected installation.

In a disconnected installation, you can download the images that are required to install a cluster, place them in a mirror registry, and use that data to install your cluster. While you require internet access to pull images for platform containers, with a disconnected installation on vSphere or bare metal infrastructure, your cluster machines do not require direct internet access.

The OpenShift Container Platform 4.x Tested Integrations page contains details about integration testing for different platforms.

Additional resources

- See Supported installation methods for different platforms for more information about the types of installations that are available for each supported platform.
- See Selecting a cluster installation method and preparing it for users for information about choosing an installation method and preparing the required resources.
- Red Hat OpenShift Network Calculator can help you design your cluster network during both the deployment and expansion phases. It addresses common questions related to the cluster network and provides output in a convenient JSON format.

### Chapter 2. Selecting a cluster installation method and preparing it for users

Before you install OpenShift Container Platform, decide what kind of installation process to follow and verify that you have all of the required resources to prepare the cluster for users.

#### 2.1. Selecting a cluster installation type

Before you install an OpenShift Container Platform cluster, you need to select the best installation instructions to follow. Think about your answers to the following questions to select the best option.

##### 2.1.1. Do you want to install and manage an OpenShift Container Platform cluster yourself?

If you want to install and manage OpenShift Container Platform yourself, you can install it on the following platforms:

- Amazon Web Services (AWS) on 64-bit x86 instances
- Amazon Web Services (AWS) on 64-bit ARM instances
- Microsoft Azure on 64-bit x86 instances
- Microsoft Azure on 64-bit ARM instances
- Microsoft Azure Stack Hub
- Google Cloud Platform (GCP) on 64-bit x86 instances
- Google Cloud Platform (GCP) on 64-bit ARM instances
- Red Hat OpenStack Platform (RHOSP)
- IBM Cloud®
- IBM Z® or IBM® LinuxONE with z/VM
- IBM Z® or IBM® LinuxONE with Red Hat Enterprise Linux (RHEL) KVM
- IBM Z® or IBM® LinuxONE in an LPAR
- IBM Power®
- IBM Power® Virtual Server
- Nutanix
- VMware vSphere
- Bare metal or other platform agnostic infrastructure

You can deploy an OpenShift Container Platform 4 cluster to both on-premise hardware and to cloud hosting services, but all of the machines in a cluster must be in the same data center or cloud hosting service.

If you want to use OpenShift Container Platform but you do not want to manage the cluster yourself, you can choose from several managed service options. If you want a cluster that is fully managed by Red Hat, you can use OpenShift Dedicated. You can also use OpenShift as a managed service on Azure, AWS, IBM Cloud®, or Google Cloud Platform. For more information about managed services, see the OpenShift Products page. If you install an OpenShift Container Platform cluster with a cloud virtual machine as a virtual bare metal, the corresponding cloud-based storage is not supported.

##### 2.1.2. Have you used OpenShift Container Platform 3 and want to use OpenShift Container Platform 4?

If you used OpenShift Container Platform 3 and want to try OpenShift Container Platform 4, you need to understand how different OpenShift Container Platform 4 is. OpenShift Container Platform 4 weaves the Operators that package, deploy, and manage Kubernetes applications and the operating system that the platform runs on, Red Hat Enterprise Linux CoreOS (RHCOS), together seamlessly. Instead of deploying machines and configuring their operating systems so that you can install OpenShift Container Platform on them, the RHCOS operating system is an integral part of the OpenShift Container Platform cluster. Deploying the operating system for the cluster machines is part of the installation process for OpenShift Container Platform. See Differences between OpenShift Container Platform 3 and 4.

Because you need to provision machines as part of the OpenShift Container Platform cluster installation process, you cannot upgrade an OpenShift Container Platform 3 cluster to OpenShift Container Platform 4. Instead, you must create a new OpenShift Container Platform 4 cluster and migrate your OpenShift Container Platform 3 workloads to them. For more information about migrating, see Migrating from OpenShift Container Platform 3 to 4 overview. Because you must migrate to OpenShift Container Platform 4, you can use any type of production cluster installation process to create your new cluster.

##### 2.1.3. Do you want to use existing components in your cluster?

Because the operating system is integral to OpenShift Container Platform, it is easier to let the installation program for OpenShift Container Platform stand up all of the infrastructure. These are called installer provisioned infrastructure installations. In this type of installation, you can provide some existing infrastructure to the cluster, but the installation program deploys all of the machines that your cluster initially needs.

You can deploy an installer-provisioned infrastructure cluster without specifying any customizations to the cluster or its underlying machines to AWS, Azure, Azure Stack Hub, GCP, Nutanix.

If you need to perform basic configuration for your installer-provisioned infrastructure cluster, such as the instance type for the cluster machines, you can customize an installation for AWS, Azure, GCP, Nutanix.

For installer-provisioned infrastructure installations, you can use an existing VPC in AWS, vNet in Azure, or VPC in GCP. You can also reuse part of your networking infrastructure so that your cluster in AWS, Azure, GCP can coexist with existing IP address allocations in your environment and integrate with existing MTU and VXLAN configurations. If you have existing accounts and credentials on these clouds, you can re-use them, but you might need to modify the accounts to have the required permissions to install OpenShift Container Platform clusters on them.

You can use the installer-provisioned infrastructure method to create appropriate machine instances on your hardware for vSphere, and bare metal. Additionally, for vSphere, you can also customize additional network parameters during installation.

For some installer-provisioned infrastructure installations, for example on the VMware vSphere and bare metal platforms, the external traffic that reaches the ingress virtual IP (VIP) is not balanced between the default IngressController replicas. For vSphere and bare metal installer-provisioned infrastructure installations where exceeding the baseline IngressController router performance is expected, you must configure an external load balancer. Configuring an external load balancer achieves the performance of multiple IngressController replicas. For more information about the baseline IngressController performance, see Baseline Ingress Controller (router) performance. For more information about configuring an external load balancer, see Configuring a user-managed load balancer.

If you want to reuse extensive cloud infrastructure, you can complete a user-provisioned infrastructure installation. With these installations, you manually deploy the machines that your cluster requires during the installation process. If you perform a user-provisioned infrastructure installation on AWS, Azure, Azure Stack Hub, you can use the provided templates to help you stand up all of the required components. You can also reuse a shared VPC on GCP. Otherwise, you can use the provider-agnostic installation method to deploy a cluster into other clouds.

You can also complete a user-provisioned infrastructure installation on your existing hardware. If you use RHOSP, IBM Z® or IBM® LinuxONE, IBM Z® and IBM® LinuxONE with RHEL KVM, IBM Z® and IBM® LinuxONE in an LPAR, IBM Power, or vSphere, use the specific installation instructions to deploy your cluster. If you use other supported hardware, follow the bare metal installation procedure. For some of these platforms, such as vSphere, and bare metal, you can also customize additional network parameters during installation.

##### 2.1.4. Do you need extra security for your cluster?

If you use a user-provisioned installation method, you can configure a proxy for your cluster. The instructions are included in each installation procedure.

If you want to prevent your cluster on a public cloud from exposing endpoints externally, you can deploy a private cluster with installer-provisioned infrastructure on AWS, Azure, or GCP.

If you need to install your cluster that has limited access to the internet, such as a disconnected or restricted network cluster, you can mirror the installation packages and install the cluster from them. Follow detailed instructions for user-provisioned infrastructure installations into restricted networks for AWS, GCP, IBM Z® or IBM® LinuxONE, IBM Z® or IBM® LinuxONE with RHEL KVM, IBM Z® or IBM® LinuxONE in an LPAR, IBM Power®, vSphere, or bare metal. You can also install a cluster into a restricted network using installer-provisioned infrastructure by following detailed instructions for AWS, GCP, IBM Cloud®, Nutanix, RHOSP, and vSphere.

If you need to deploy your cluster to an AWS GovCloud region, AWS China region, or Azure government region, you can configure those custom regions during an installer-provisioned infrastructure installation.

You can also configure the cluster machines to use the RHEL cryptographic libraries that have been submitted to NIST for FIPS 140-2/140-3 Validation during installation.

Important

When running Red Hat Enterprise Linux (RHEL) or Red Hat Enterprise Linux CoreOS (RHCOS) booted in FIPS mode, OpenShift Container Platform core components use the RHEL cryptographic libraries that have been submitted to NIST for FIPS 140-2/140-3 Validation on only the x86\_64, ppc64le, and s390x architectures.

#### 2.2. Preparing your cluster for users after installation

Some configuration is not required to install the cluster but recommended before your users access the cluster. You can customize the cluster itself by customizing the Operators that make up your cluster and integrate you cluster with other required systems, such as an identity provider.

For a production cluster, you must configure the following integrations:

- Persistent storage
- An identity provider
- Monitoring core OpenShift Container Platform components

#### 2.3. Preparing your cluster for workloads

Depending on your workload needs, you might need to take extra steps before you begin deploying applications. For example, after you prepare infrastructure to support your application build strategy, you might need to make provisions for low-latency workloads or to protect sensitive workloads. You can also configure monitoring for application workloads. If you plan to run Windows workloads, you must enable hybrid networking with OVN-Kubernetes during the installation process; hybrid networking cannot be enabled after your cluster is installed.

#### 2.4. Supported installation methods for different platforms

You can perform different types of installations on different platforms.

Note

Not all installation options are supported for all platforms, as shown in the following tables. A checkmark indicates that the option is supported and links to the relevant section.

|                                   | AWS (64-bit x86)   | AWS (64-bit ARM)   | Azure (64-bit x86)   | Azure (64-bit ARM)   | Azure Stack Hub   | GCP (64-bit x86)   | GCP (64-bit ARM)   | Nutanix   | RHOSP   | Bare metal (64-bit x86)   | Bare metal (64-bit ARM)   | vSphere   | IBM Cloud®   | IBM Z®   | IBM Power®   | IBM Power® Virtual Server   |
|-----------------------------------|--------------------|--------------------|----------------------|----------------------|-------------------|--------------------|--------------------|-----------|---------|---------------------------|---------------------------|-----------|--------------|----------|--------------|-----------------------------|
| Default                           | ✓                  | ✓                  | ✓                    | ✓                    | ✓                 | ✓                  | ✓                  | ✓         |         | ✓                         | ✓                         | ✓         | ✓            |          |              |                             |
| Custom                            | ✓                  | ✓                  | ✓                    | ✓                    | ✓                 | ✓                  | ✓                  | ✓         | ✓       |                           |                           | ✓         | ✓            |          |              | ✓                           |
| Network customization             | ✓                  | ✓                  | ✓                    | ✓                    | ✓                 | ✓                  | ✓                  |           |         | ✓                         | ✓                         | ✓         | ✓            |          |              |                             |
| Restricted network                | ✓                  | ✓                  | ✓                    | ✓                    |                   | ✓                  | ✓                  | ✓         | ✓       | ✓                         | ✓                         | ✓         | ✓            |          |              | ✓                           |
| Private clusters                  | ✓                  | ✓                  | ✓                    | ✓                    |                   | ✓                  | ✓                  |           |         |                           |                           |           | ✓            |          |              | ✓                           |
| Existing virtual private networks | ✓                  | ✓                  | ✓                    | ✓                    |                   | ✓                  | ✓                  |           |         |                           |                           |           | ✓            |          |              | ✓                           |
| Government regions                | ✓                  |                    | ✓                    |                      |                   |                    |                    |           |         |                           |                           |           |              |          |              |                             |
| Secret regions                    | ✓                  |                    |                      |                      |                   |                    |                    |           |         |                           |                           |           |              |          |              |                             |
| China regions                     | ✓                  |                    |                      |                      |                   |                    |                    |           |         |                           |                           |           |              |          |              |                             |

|                                              | AWS (64-bit x86)   | AWS (64-bit ARM)   | Azure (64-bit x86)   | Azure (64-bit ARM)   | Azure Stack Hub   | GCP (64-bit x86)   | GCP (64-bit ARM)   | Nutanix   | RHOSP   | Bare metal (64-bit x86)   | Bare metal (64-bit ARM)   | vSphere   | IBM Cloud®   | IBM Z®   | IBM Z® with RHEL KVM   | IBM Power®   | Platform agnostic   |
|----------------------------------------------|--------------------|--------------------|----------------------|----------------------|-------------------|--------------------|--------------------|-----------|---------|---------------------------|---------------------------|-----------|--------------|----------|------------------------|--------------|---------------------|
| Custom                                       | ✓                  | ✓                  | ✓                    | ✓                    | ✓                 | ✓                  | ✓                  |           | ✓       | ✓                         | ✓                         | ✓         |              | ✓        | ✓                      | ✓            | ✓                   |
| Network customization                        |                    |                    |                      |                      |                   |                    |                    |           |         | ✓                         | ✓                         | ✓         |              |          |                        |              |                     |
| Restricted network                           | ✓                  | ✓                  |                      |                      |                   | ✓                  | ✓                  |           |         | ✓                         | ✓                         | ✓         |              | ✓        | ✓                      | ✓            |                     |
| Shared VPC hosted outside of cluster project |                    |                    |                      |                      |                   | ✓                  | ✓                  |           |         |                           |                           |           |              |          |                        |              |                     |

### Chapter 3. Cluster capabilities

Cluster administrators can use cluster capabilities to enable or disable optional components prior to installation. Cluster administrators can enable cluster capabilities at anytime after installation.

Note

Cluster administrators cannot disable a cluster capability after it is enabled.

#### 3.1. Enabling cluster capabilities

If you are using an installation method that includes customizing your cluster by creating an install-config.yaml file, you can select which cluster capabilities you want to make available on the cluster.

Note

If you customize your cluster by enabling or disabling specific cluster capabilities, you must manually maintain your install-config.yaml file. New OpenShift Container Platform updates might declare new capability handles for existing components, or introduce new components altogether. Users who customize their install-config.yaml file should consider periodically updating their install-config.yaml file as OpenShift Container Platform is updated.

You can use the following configuration parameters to select cluster capabilities:

```
capabilities:
  baselineCapabilitySet: v4.11 1
  additionalEnabledCapabilities: 2
  - CSISnapshot
  - Console
  - Storage
```

Defines a baseline set of capabilities to install. Valid values are ,  and . If you select , all optional capabilities are disabled. The default value is , which enables all optional capabilities.

Note

v4.x refers to any value up to and including the current cluster version. For example, valid values for a OpenShift Container Platform 4.12 cluster are v4.11 and v4.12.

Defines a list of capabilities to explicitly enable. These capabilities are enabled in addition to the capabilities specified in .

Note

In this example, the default capability is set to v4.11. The additionalEnabledCapabilities field enables additional capabilities over the default v4.11 capability set.

The following table describes the baselineCapabilitySet values.

| Value    | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| vCurrent | Specify this option when you want to automatically add new, default capabilities that are introduced in new releases.                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| v4.11    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.11. By specifying v4.11, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.11 are baremetal, MachineAPI, marketplace, and openshift-samples.                                                                                                                                                                                             |
| v4.12    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.12. By specifying v4.12, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.12 are baremetal, MachineAPI, marketplace, openshift-samples, Console, Insights, Storage, and CSISnapshot.                                                                                                                                                    |
| v4.13    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.13. By specifying v4.13, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.13 are baremetal, MachineAPI, marketplace, openshift-samples, Console, Insights, Storage, CSISnapshot, and NodeTuning.                                                                                                                                        |
| v4.14    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.14. By specifying v4.14, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.14 are baremetal, MachineAPI, marketplace, openshift-samples, Console, Insights, Storage, CSISnapshot, NodeTuning, ImageRegistry, Build, and DeploymentConfig.                                                                                                |
| v4.15    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.15. By specifying v4.15, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.15 are baremetal, MachineAPI, marketplace, OperatorLifecycleManager, openshift-samples, Console, Insights, Storage, CSISnapshot, NodeTuning, ImageRegistry, Build, CloudCredential, and DeploymentConfig.                                                     |
| v4.16    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.16. By specifying v4.16, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.16 are baremetal, MachineAPI, marketplace, OperatorLifecycleManager, openshift-samples, Console, Insights, Storage, CSISnapshot, NodeTuning, ImageRegistry, Build, CloudCredential, DeploymentConfig, and CloudControllerManager.                             |
| v4.17    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.17. By specifying v4.17, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.17 are baremetal, MachineAPI, marketplace, OperatorLifecycleManager, openshift-samples, Console, Insights, Storage, CSISnapshot, NodeTuning, ImageRegistry, Build, CloudCredential, DeploymentConfig, and CloudControllerManager.                             |
| v4.18    | Specify this option when you want to enable the default capabilities for OpenShift Container Platform 4.18. By specifying v4.18, capabilities that are introduced in newer versions of OpenShift Container Platform are not enabled. The default capabilities in OpenShift Container Platform 4.18 are baremetal, MachineAPI, marketplace, OperatorLifecycleManager, OperatorLifecycleManagerV1, openshift-samples, Console, Insights, Storage, CSISnapshot, NodeTuning, ImageRegistry, Build, CloudCredential, DeploymentConfig, and CloudControllerManager. |
| None     | Specify when the other sets are too large, and you do not need any capabilities or want to fine-tune via additionalEnabledCapabilities.                                                                                                                                                                                                                                                                                                                                                                                                                       |

Additional resources

- Installing a cluster on AWS with customizations
- Installing a cluster on GCP with customizations

#### 3.2. Optional cluster capabilities in OpenShift Container Platform 4.18

Currently, cluster Operators provide the features for these optional capabilities. The following summarizes the features provided by each capability and what functionality you lose if it is disabled.

Additional resources

- Cluster Operators reference

##### 3.2.1. Bare-metal capability

###### Purpose

The Cluster Baremetal Operator provides the features for the baremetal capability.

The Cluster Baremetal Operator (CBO) deploys all the components necessary to take a bare-metal server to a fully functioning worker node ready to run OpenShift Container Platform compute nodes. The CBO ensures that the metal3 deployment, which consists of the Bare Metal Operator (BMO) and Ironic containers, runs on one of the control plane nodes within the OpenShift Container Platform cluster. The CBO also listens for OpenShift Container Platform updates to resources that it watches and takes appropriate action.

The bare-metal capability is required for deployments using installer-provisioned infrastructure. Disabling the bare-metal capability can result in unexpected problems with these deployments.

It is recommended that cluster administrators only disable the bare-metal capability during installations with user-provisioned infrastructure that do not have any BareMetalHost resources in the cluster.

Important

If the bare-metal capability is disabled, the cluster cannot provision or manage bare-metal nodes. Only disable the capability if there are no BareMetalHost resources in your deployment. The baremetal capability depends on the MachineAPI capability. If you enable the baremetal capability, you must also enable MachineAPI.

Additional resources

- Deploying installer-provisioned clusters on bare metal
- Preparing for bare metal cluster installation
- Configuration using the Bare Metal Operator

##### 3.2.2. Build capability

###### Purpose

The Build capability enables the Build API. The Build API manages the lifecycle of Build and BuildConfig objects.

Important

If you disable the Build capability, the following resources will not be available in the cluster:

- Build and BuildConfig resources
- The builder service account

Disable the Build capability only if you do not require Build and BuildConfig resources or the builder service account in the cluster.

##### 3.2.3. Cloud controller manager capability

###### Purpose

The Cloud Controller Manager Operator provides features for the CloudControllerManager capability.

Note

Currently, disabling the CloudControllerManager capability is not supported on all platforms.

You can determine if your cluster supports disabling the CloudControllerManager capability by checking values in the installation configuration (install-config.yaml) file for your cluster.

In the install-config.yaml file, locate the platform parameter.

- If the value of the platform parameter is Baremetal or None, you can disable the CloudControllerManager capability on your cluster.
- If the value of the platform parameter is External, locate the platform.external.cloudControllerManager parameter. If the value of the platform.external.cloudControllerManager parameter is None, you can disable the CloudControllerManager capability on your cluster.

Important

If these parameters contain any other values than those listed, you cannot disable the CloudControllerManager capability on your cluster.

Note

The status of this Operator is General Availability for Amazon Web Services (AWS), Google Cloud Platform (GCP), IBM Cloud®, global Microsoft Azure, Microsoft Azure Stack Hub, Nutanix, Red Hat OpenStack Platform (RHOSP), and VMware vSphere.

The Operator is available as a Technology Preview for IBM Power® Virtual Server.

The Cloud Controller Manager Operator manages and updates the cloud controller managers deployed on top of OpenShift Container Platform. The Operator is based on the Kubebuilder framework and controller-runtime libraries. It is installed via the Cluster Version Operator (CVO).

It contains the following components:

- Operator
- Cloud configuration observer

By default, the Operator exposes Prometheus metrics through the metrics service.

##### 3.2.4. Cloud credential capability

###### Purpose

The Cloud Credential Operator provides features for the CloudCredential capability.

Note

Currently, disabling the CloudCredential capability is only supported for bare-metal clusters.

The Cloud Credential Operator (CCO) manages cloud provider credentials as Kubernetes custom resource definitions (CRDs). The CCO syncs on CredentialsRequest custom resources (CRs) to allow OpenShift Container Platform components to request cloud provider credentials with the specific permissions that are required for the cluster to run.

By setting different values for the credentialsMode parameter in the install-config.yaml file, the CCO can be configured to operate in several different modes. If no mode is specified, or the credentialsMode parameter is set to an empty string (""), the CCO operates in its default mode.

Additional resources

- About the Cloud Credential Operator

##### 3.2.5. Cluster Image Registry capability

###### Purpose

The Cluster Image Registry Operator provides features for the ImageRegistry capability.

The Cluster Image Registry Operator manages a singleton instance of the OpenShift image registry. It manages all configuration of the registry, including creating storage.

On initial start up, the Operator creates a default image-registry resource instance based on the configuration detected in the cluster. This indicates what cloud storage type to use based on the cloud provider.

If insufficient information is available to define a complete image-registry resource, then an incomplete resource is defined and the Operator updates the resource status with information about what is missing.

The Cluster Image Registry Operator runs in the openshift-image-registry namespace and it also manages the registry instance in that location. All configuration and workload resources for the registry reside in that namespace.

In order to integrate the image registry into the cluster’s user authentication and authorization system, an image pull secret is generated for each service account in the cluster.

Important

If you disable the ImageRegistry capability or if you disable the integrated OpenShift image registry in the Cluster Image Registry Operator’s configuration, the image pull secret is not generated for each service account.

If you disable the ImageRegistry capability, you can reduce the overall resource footprint of OpenShift Container Platform in Telco environments. Depending on your deployment, you can disable this component if you do not need it.

###### Project

cluster-image-registry-operator

Additional resources

- Image Registry Operator in OpenShift Container Platform
- Automatically generated secrets

##### 3.2.6. Cluster storage capability

###### Purpose

The Cluster Storage Operator provides the features for the Storage capability.

The Cluster Storage Operator sets OpenShift Container Platform cluster-wide storage defaults. It ensures a default storageclass exists for OpenShift Container Platform clusters. It also installs Container Storage Interface (CSI) drivers which enable your cluster to use various storage backends.

Important

If the cluster storage capability is disabled, the cluster will not have a default storageclass or any CSI drivers. Users with administrator privileges can create a default storageclass and manually install CSI drivers if the cluster storage capability is disabled.

###### Notes

- The storage class that the Operator creates can be made non-default by editing its annotation, but this storage class cannot be deleted as long as the Operator runs.

##### 3.2.7. Console capability

###### Purpose

The Console Operator provides the features for the Console capability.

The Console Operator installs and maintains the OpenShift Container Platform web console on a cluster. The Console Operator is installed by default and automatically maintains a console.

Additional resources

- Web console overview

##### 3.2.8. CSI snapshot controller capability

###### Purpose

The Cluster CSI Snapshot Controller Operator provides the features for the CSISnapshot capability.

The Cluster CSI Snapshot Controller Operator installs and maintains the CSI Snapshot Controller. The CSI Snapshot Controller is responsible for watching the VolumeSnapshot CRD objects and manages the creation and deletion lifecycle of volume snapshots.

Additional resources

- CSI volume snapshots

##### 3.2.9. DeploymentConfig capability

###### Purpose

The DeploymentConfig capability enables and manages the DeploymentConfig API.

Important

If you disable the DeploymentConfig capability, the following resources will not be available in the cluster:

- DeploymentConfig resources
- The deployer service account

Disable the DeploymentConfig capability only if you do not require DeploymentConfig resources and the deployer service account in the cluster.

##### 3.2.10. Ingress Capability

###### Purpose

The Ingress Operator provides the features for the Ingress capability.

The Ingress Operator configures and manages the OpenShift Container Platform router.

###### Project

openshift-ingress-operator

###### CRDs

- clusteringresses.ingress.openshift.io
- clusteringresses.ingress.openshift.io
    - Scope: Namespaced
    - CR: clusteringresses
    - Validation: No

###### Configuration objects

- Cluster config
- Cluster config
    - Type Name: clusteringresses.ingress.openshift.io
    - Instance Name: default
    - View Command:
								$ oc get clusteringresses.ingress.openshift.io -n openshift-ingress-operator default -o yaml

###### Notes

The Ingress Operator sets up the router in the openshift-ingress project and creates the deployment for the router:

```
$ oc get deployment -n openshift-ingress
```

The Ingress Operator uses the clusterNetwork[].cidr from the network/cluster status to determine what mode (IPv4, IPv6, or dual stack) the managed Ingress Controller (router) should operate in. For example, if clusterNetwork contains only a v6 cidr, then the Ingress Controller operates in IPv6-only mode.

In the following example, Ingress Controllers managed by the Ingress Operator will run in IPv4-only mode because only one cluster network exists and the network is an IPv4 cidr:

```
$ oc get network/cluster -o jsonpath='{.status.clusterNetwork[*]}'
```

Example output

```
map[cidr:10.128.0.0/14 hostPrefix:23]
```

##### 3.2.11. Insights capability

###### Purpose

The Insights Operator provides the features for the Insights capability.

The Insights Operator gathers OpenShift Container Platform configuration data and sends it to Red Hat. The data is used to produce proactive insights recommendations about potential issues that a cluster might be exposed to. These insights are communicated to cluster administrators through Insights Advisor on console.redhat.com.

###### Notes

Insights Operator complements OpenShift Container Platform Telemetry.

Additional resources

- Using Insights Operator

##### 3.2.12. Machine API capability

###### Purpose

The machine-api-operator, cluster-autoscaler-operator, and cluster-control-plane-machine-set-operator Operators provide the features for the MachineAPI capability. You can disable this capability only if you install a cluster with user-provisioned infrastructure.

The Machine API capability is responsible for all machine configuration and management in the cluster. If you disable the Machine API capability during installation, you need to manage all machine-related tasks manually.

Additional resources

- Overview of machine management
- Machine API Operator
- Cluster Autoscaler Operator
- Control Plane Machine Set Operator

##### 3.2.13. Marketplace capability

###### Purpose

The Marketplace Operator provides the features for the marketplace capability.

The Marketplace Operator simplifies the process for bringing off-cluster Operators to your cluster by using a set of default Operator Lifecycle Manager (OLM) catalogs on the cluster. When the Marketplace Operator is installed, it creates the openshift-marketplace namespace. OLM ensures catalog sources installed in the openshift-marketplace namespace are available for all namespaces on the cluster.

If you disable the marketplace capability, the Marketplace Operator does not create the openshift-marketplace namespace. Catalog sources can still be configured and managed on the cluster manually, but OLM depends on the openshift-marketplace namespace in order to make catalogs available to all namespaces on the cluster. Users with elevated permissions to create namespaces prefixed with openshift-, such as system or cluster administrators, can manually create the openshift-marketplace namespace.

If you enable the marketplace capability, you can enable and disable individual catalogs by configuring the Marketplace Operator.

Additional resources

- Red Hat-provided Operator catalogs

##### 3.2.14. Node Tuning capability

###### Purpose

The Node Tuning Operator provides features for the NodeTuning capability.

The Node Tuning Operator helps you manage node-level tuning by orchestrating the TuneD daemon and achieves low latency performance by using the Performance Profile controller. The majority of high-performance applications require some level of kernel tuning. The Node Tuning Operator provides a unified management interface to users of node-level sysctls and more flexibility to add custom tuning specified by user needs.

If you disable the NodeTuning capability, some default tuning settings will not be applied to the control-plane nodes. This might limit the scalability and performance of large clusters with over 900 nodes or 900 routes.

Additional resources

- Using the Node Tuning Operator

##### 3.2.15. OpenShift samples capability

###### Purpose

The Cluster Samples Operator provides the features for the openshift-samples capability.

The Cluster Samples Operator manages the sample image streams and templates stored in the openshift namespace.

On initial start up, the Operator creates the default samples configuration resource to initiate the creation of the image streams and templates. The configuration object is a cluster scoped object with the key cluster and type configs.samples.

The image streams are the Red Hat Enterprise Linux CoreOS (RHCOS)-based OpenShift Container Platform image streams pointing to images on registry.redhat.io. Similarly, the templates are those categorized as OpenShift Container Platform templates.

If you disable the samples capability, users cannot access the image streams, samples, and templates it provides. Depending on your deployment, you might want to disable this component if you do not need it.

Additional resources

- Configuring the Cluster Samples Operator

##### 3.2.16. Operator Lifecycle Manager (OLM) Classic capability

###### Purpose

OLM (Classic) provides the features for the OperatorLifecycleManager capability.

Operator Lifecycle Manager (OLM) Classic helps users install, update, and manage the lifecycle of Kubernetes native applications (Operators) and their associated services running across their OpenShift Container Platform clusters. It is part of the Operator Framework, an open source toolkit designed to manage Operators in an effective, automated, and scalable way.

If an Operator requires any of the following APIs, then you must enable the OperatorLifecycleManager capability:

- ClusterServiceVersion
- CatalogSource
- Subscription
- InstallPlan
- OperatorGroup

Important

The marketplace capability depends on the OperatorLifecycleManager capability. You cannot disable the OperatorLifecycleManager capability and enable the marketplace capability.

Additional resources

- Operator Lifecycle Manager concepts and resources

##### 3.2.17. Operator Lifecycle Manager (OLM) v1 capability

###### Purpose

OLM v1 provides the features for the OperatorLifecycleManagerV1 capability.

Starting in OpenShift Container Platform 4.18, OLM v1 is enabled by default alongside OLM (Classic). This next-generation iteration provides an updated framework that evolves many of OLM (Classic) concepts that enable cluster administrators to extend capabilities for their users.

OLM v1 manages the lifecycle of the new ClusterExtension object, which includes Operators via the registry+v1 bundle format, and controls installation, upgrade, and role-based access control (RBAC) of extensions within a cluster.

In OpenShift Container Platform, OLM v1 is provided by the olm cluster Operator.

Note

The olm cluster Operator informs cluster administrators if there are any installed extensions blocking cluster upgrade, based on their olm.maxOpenShiftVersion properties. For more information, see "Compatibility with OpenShift Container Platform versions".

###### Components

Operator Lifecycle Manager (OLM) v1 comprises the following component projects:

###### CRDs

- clusterextension.olm.operatorframework.io
- clusterextension.olm.operatorframework.io
    - Scope: Cluster
    - CR: ClusterExtension
- clustercatalog.olm.operatorframework.io
- clustercatalog.olm.operatorframework.io
    - Scope: Cluster
    - CR: ClusterCatalog

###### Project

- operator-framework/operator-controller
- operator-framework/catalogd

Additional resources

- Extensions overview

#### 3.3. Viewing the cluster capabilities

As a cluster administrator, you can view the capabilities by using the clusterversion resource status.

Prerequisites

- You have installed the OpenShift CLI (oc).

Procedure

- To view the status of the cluster capabilities, run the following command:
					$ oc get clusterversion version -o jsonpath='{.spec.capabilities}{"\n"}{.status.capabilities}{"\n"}'Example output
{"additionalEnabledCapabilities":["openshift-samples"],"baselineCapabilitySet":"None"}
{"enabledCapabilities":["openshift-samples"],"knownCapabilities":["CSISnapshot","Console","Insights","Storage","baremetal","marketplace","openshift-samples"]}

#### 3.4. Enabling the cluster capabilities by setting baseline capability set

As a cluster administrator, you can enable cluster capabilities any time after a OpenShift Container Platform installation by setting the baselineCapabilitySet configuration parameter.

Prerequisites

- You have installed the OpenShift CLI (oc).

Procedure

- To set the baselineCapabilitySet configuration parameter, run the following command:
					$ oc patch clusterversion version --type merge -p '{"spec":{"capabilities":{"baselineCapabilitySet":"vCurrent"}}}' 11 
								For baselineCapabilitySet you can specify vCurrent, v4.18, or None.

#### 3.5. Enabling the cluster capabilities by setting additional enabled capabilities

As a cluster administrator, you can enable cluster capabilities any time after a OpenShift Container Platform installation by setting the additionalEnabledCapabilities configuration parameter.

Prerequisites

- You have installed the OpenShift CLI (oc).

Procedure

1. View the additional enabled capabilities by running the following command:
					$ oc get clusterversion version -o jsonpath='{.spec.capabilities.additionalEnabledCapabilities}{"\n"}'Example output
["openshift-samples"]
2. To set the additionalEnabledCapabilities configuration parameter, run the following command:
					$ oc patch clusterversion/version --type merge -p '{"spec":{"capabilities":{"additionalEnabledCapabilities":["openshift-samples", "marketplace"]}}}'

Important

It is not possible to disable a capability which is already enabled in a cluster. The cluster version Operator (CVO) continues to reconcile the capability which is already enabled in the cluster.

If you try to disable a capability, then CVO shows the divergent spec:

```
$ oc get clusterversion version -o jsonpath='{.status.conditions[?(@.type=="ImplicitlyEnabledCapabilities")]}{"\n"}'
```

Example output

```
{"lastTransitionTime":"2022-07-22T03:14:35Z","message":"The following capabilities could not be disabled: openshift-samples","reason":"CapabilitiesImplicitlyEnabled","status":"True","type":"ImplicitlyEnabledCapabilities"}
```

Note

During the cluster upgrades, it is possible that a given capability could be implicitly enabled. If a resource was already running on the cluster before the upgrade, then any capabilities that is part of the resource will be enabled. For example, during a cluster upgrade, a resource that is already running on the cluster has been changed to be part of the marketplace capability by the system. Even if a cluster administrator does not explicitly enabled the marketplace capability, it is implicitly enabled by the system.

### Chapter 4. Support for FIPS cryptography

You can install an OpenShift Container Platform cluster in FIPS mode.

OpenShift Container Platform is designed for FIPS. When running Red Hat Enterprise Linux (RHEL) or Red Hat Enterprise Linux CoreOS (RHCOS) booted in FIPS mode, OpenShift Container Platform core components use the RHEL cryptographic libraries that have been submitted to NIST for FIPS 140-2/140-3 Validation on only the x86\_64, ppc64le, and s390x architectures.

For more information about the NIST validation program, see Cryptographic Module Validation Program. For the latest NIST status for the individual versions of RHEL cryptographic libraries that have been submitted for validation, see Compliance Activities and Government Standards.

Important

To enable FIPS mode for your cluster, you must run the installation program from a RHEL 9 computer that is configured to operate in FIPS mode, and you must use a FIPS-capable version of the installation program. See the section titled Obtaining a FIPS-capable installation program using `oc adm extract`.

For more information about configuring FIPS mode on RHEL, see Installing the system in FIPS mode.

For the Red Hat Enterprise Linux CoreOS (RHCOS) machines in your cluster, this change is applied when the machines are deployed based on the status of an option in the install-config.yaml file, which governs the cluster options that a user can change during cluster deployment. With Red Hat Enterprise Linux (RHEL) machines, you must enable FIPS mode when you install the operating system on the machines that you plan to use as worker machines.

Because FIPS must be enabled before the operating system that your cluster uses boots for the first time, you cannot enable FIPS after you deploy a cluster.

#### 4.1. Obtaining a FIPS-capable installation program using oc adm extract

OpenShift Container Platform requires the use of a FIPS-capable installation binary to install a cluster in FIPS mode. You can obtain this binary by extracting it from the release image by using the OpenShift CLI (oc). After you have obtained the binary, you proceed with the cluster installation, replacing all instances of the openshift-install command with openshift-install-fips.

Prerequisites

- You have installed the OpenShift CLI (oc) with version 4.16 or newer.

Procedure

1. Extract the FIPS-capable binary from the installation program by running the following command:
					$ oc adm release extract --registry-config "${pullsecret\_file}" --command=openshift-install-fips --to "${extract\_dir}" ${RELEASE\_IMAGE}
						where:
					&lt;pullsecret\_file&gt;
									Specifies the name of a file that contains your pull secret.
								&lt;extract\_dir&gt;
									Specifies the directory where you want to extract the binary.
								&lt;RELEASE\_IMAGE&gt;
									Specifies the Quay.io URL of the OpenShift Container Platform release you are using. For more information on finding the release image, see Extracting the OpenShift Container Platform installation program.
2. Proceed with cluster installation, replacing all instances of the openshift-install command with openshift-install-fips.

Additional resources

- Extracting the OpenShift Container Platform installation program

#### 4.2. Obtaining a FIPS-capable installation program using the public OpenShift mirror

OpenShift Container Platform requires the use of a FIPS-capable installation binary to install a cluster in FIPS mode. You can obtain this binary by downloading it from the public OpenShift mirror. After you have obtained the binary, proceed with the cluster installation, replacing all instances of the openshift-install binary with openshift-install-fips.

Prerequisites

- You have access to the internet.

Procedure

1. Download the installation program from https://mirror.openshift.com/pub/openshift-v4/clients/ocp/latest-4.18/openshift-install-rhel9-amd64.tar.gz.
2. Extract the installation program. For example, on a computer that uses a Linux operating system, run the following command:
					$ tar -xvf openshift-install-rhel9-amd64.tar.gz
3. Proceed with cluster installation, replacing all instances of the openshift-install command with openshift-install-fips.

#### 4.3. FIPS validation in OpenShift Container Platform

OpenShift Container Platform uses certain FIPS validated or Modules In Process modules within RHEL and RHCOS for the operating system components that it uses. See RHEL core crypto components. For example, when users use SSH to connect to OpenShift Container Platform clusters and containers, those connections are properly encrypted.

OpenShift Container Platform components are written in Go and built with Red Hat’s golang compiler. When you enable FIPS mode for your cluster, all OpenShift Container Platform components that require cryptographic signing call RHEL and RHCOS cryptographic libraries.

| Attributes                                                                                                                            | Limitations                                                                                                                                                                                                                                         |
|---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FIPS support in RHEL 9 and RHCOS operating systems.                                                                                   | The FIPS implementation does not use a function that performs hash computation and signature generation or validation in a single step. This limitation will continue to be evaluated and improved in future OpenShift Container Platform releases. |
| FIPS support in CRI-O runtimes.                                                                                                       | The FIPS implementation does not use a function that performs hash computation and signature generation or validation in a single step. This limitation will continue to be evaluated and improved in future OpenShift Container Platform releases. |
| FIPS support in OpenShift Container Platform services.                                                                                | The FIPS implementation does not use a function that performs hash computation and signature generation or validation in a single step. This limitation will continue to be evaluated and improved in future OpenShift Container Platform releases. |
| FIPS validated or Modules In Process cryptographic module and algorithms that are obtained from RHEL 9 and RHCOS binaries and images. | The FIPS implementation does not use a function that performs hash computation and signature generation or validation in a single step. This limitation will continue to be evaluated and improved in future OpenShift Container Platform releases. |
| Use of FIPS compatible golang compiler.                                                                                               | TLS FIPS support is not complete but is planned for future OpenShift Container Platform releases.                                                                                                                                                   |
| FIPS support across multiple architectures.                                                                                           | FIPS is currently only supported on OpenShift Container Platform deployments using x86_64, ppc64le, and s390x architectures.                                                                                                                        |

#### 4.4. FIPS support in components that the cluster uses

Although the OpenShift Container Platform cluster itself uses FIPS validated or Modules In Process modules, ensure that the systems that support your OpenShift Container Platform cluster use FIPS validated or Modules In Process modules for cryptography.

##### 4.4.1. etcd

To ensure that the secrets that are stored in etcd use FIPS validated or Modules In Process encryption, boot the node in FIPS mode. After you install the cluster in FIPS mode, you can encrypt the etcd data by using the FIPS-approved aes cbc cryptographic algorithm.

##### 4.4.2. Storage

For local storage, use RHEL-provided disk encryption or Container Native Storage that uses RHEL-provided disk encryption. By storing all data in volumes that use RHEL-provided disk encryption and enabling FIPS mode for your cluster, both data at rest and data in motion, or network data, are protected by FIPS validated or Modules In Process encryption. You can configure your cluster to encrypt the root filesystem of each node, as described in Customizing nodes.

##### 4.4.3. Runtimes

To ensure that containers know that they are running on a host that is using FIPS validated or Modules In Process cryptography modules, use CRI-O to manage your runtimes.

#### 4.5. Installing a cluster in FIPS mode

To install a cluster in FIPS mode, follow the instructions to install a customized cluster on your preferred infrastructure. Ensure that you set fips: true in the install-config.yaml file before you deploy your cluster.

Important

To enable FIPS mode for your cluster, you must run the installation program from a RHEL computer configured to operate in FIPS mode. For more information about configuring FIPS mode on RHEL, see Installing the system in FIPS mode.

- Amazon Web Services
- Microsoft Azure
- Bare metal
- Google Cloud Platform
- IBM Cloud®
- IBM Power®
- IBM Z® and IBM® LinuxONE
- IBM Z® and IBM® LinuxONE with RHEL KVM
- IBM Z® and IBM® LinuxONE in an LPAR
- Red Hat OpenStack Platform (RHOSP)
- VMware vSphere

Note

If you are using Azure File storage, you cannot enable FIPS mode.

To apply AES CBC encryption to your etcd data store, follow the Encrypting etcd data process after you install your cluster.

If you add RHEL nodes to your cluster, ensure that you enable FIPS mode on the machines before their initial boot. See Adding RHEL compute machines to an OpenShift Container Platform cluster and Installing the system in FIPS mode.

### Legal Notice

Copyright © 2024 Red Hat, Inc.

OpenShift documentation is licensed under the Apache License 2.0 (https://www.apache.org/licenses/LICENSE-2.0).

Modified versions must remove all Red Hat trademarks.

Portions adapted from https://github.com/kubernetes-incubator/service-catalog/ with modifications by Red Hat.

Red Hat, Red Hat Enterprise Linux, the Red Hat logo, the Shadowman logo, JBoss, OpenShift, Fedora, the Infinity logo, and RHCE are trademarks of Red Hat, Inc., registered in the United States and other countries.

Linux® is the registered trademark of Linus Torvalds in the United States and other countries.

Java® is a registered trademark of Oracle and/or its affiliates.

XFS® is a trademark of Silicon Graphics International Corp. or its subsidiaries in the United States and/or other countries.

MySQL® is a registered trademark of MySQL AB in the United States, the European Union and other countries.

Node.js® is an official trademark of Joyent. Red Hat Software Collections is not formally related to or endorsed by the official Joyent Node.js open source or commercial project.

The OpenStack® Word Mark and OpenStack logo are either registered trademarks/service marks or trademarks/service marks of the OpenStack Foundation, in the United States and other countries and are used with the OpenStack Foundation’s permission. We are not affiliated with, endorsed or sponsored by the OpenStack Foundation, or the OpenStack community.

All other trademarks are the property of their respective owners.

- About OpenShift Container Platform installation
- Supported platforms for OpenShift Container Platform clusters
- Selecting a cluster installation type
- Preparing your cluster for users after installation
- Preparing your cluster for workloads
- Supported installation methods for different platforms
- Enabling cluster capabilities
- Optional cluster capabilities in OpenShift Container Platform 4.18
- Viewing the cluster capabilities
- Enabling the cluster capabilities by setting baseline capability set
- Enabling the cluster capabilities by setting additional enabled capabilities
- Obtaining a FIPS-capable installation program using oc adm extract
- Obtaining a FIPS-capable installation program using the public OpenShift mirror
- FIPS validation in OpenShift Container Platform
- FIPS support in components that the cluster uses
- Installing a cluster in FIPS mode

<!-- 🖼️❌ Image not available. Please use `PdfPipelineOptions(generate_picture_images=True)` -->

#### Learn

- Developer resources
- Cloud learning hub
- Interactive labs
- Training and certification
- Customer support
- See all documentation

#### Try, buy, &amp; sell

- Product trial center
- Red Hat Ecosystem Catalog
- Red Hat Store
- Buy online (Japan)

#### Communities

- Customer Portal Community
- Events
- How we contribute

#### About Red Hat Documentation

We help Red Hat users innovate and achieve their goals with our products and services with content they can trust. Explore our recent updates.

#### Making open source more inclusive

Red Hat is committed to replacing problematic language in our code, documentation, and web properties.

#### About Red Hat

We deliver hardened solutions that make it easier for enterprises to work across platforms and environments, from the core datacenter to the network edge.

#### Red Hat legal and privacy links

- About Red Hat
- Jobs
- Events
- Locations
- Contact Red Hat
- Red Hat Blog
- Inclusion at Red Hat
- Cool Stuff Store
- Red Hat Summit

#### Red Hat legal and privacy links

- Privacy statement
- Terms of use
- All policies and guidelines
- Digital accessibility
