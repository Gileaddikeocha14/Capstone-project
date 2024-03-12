explanation of the capstone project:

The project is divided into three sections
section one: This section focus on the Code.The code is all about deploying applications on kubernetes.
These includes ingress-rule,micro-service,prometheus and grafana.
 Ingress-Rule: A Kubernetes ingress is an API object used to manage external user access to services running in a Kubernetes cluster. It provides routing rules, defined within the ingress resource, which you can use to configure access to your clusters and ngress Rules govern traffic originating from external connections coming into the pod.

Prometheus and Grafana: These are two of the most popular open-source monitoring tools for Kubernetes.
Using Helm: This is an easy way to send any application container to Kubernetes. Helm is the official package manager for Kubernetes. With Helm, we make installing, sending, and managing Kubernetes applications easier.
Prometheus collects and stores metric data as time-series data, while Grafana is an analytics and visualization web application that can ingest data from various sources and display it in customizable charts

Micro-Service: One of the primary advantages of microservices is the ability to independently scale individual components. In this project, we use Kubernetes services to expose microservices within the cluster. Each service gets a stable IP address and DNS name, making it easier for microservices to communicate with each other.

Nginx-Controller:  is production‑grade Ingress controller (daemon) that runs alongside NGINX Open Source or NGINX Plus instances in a Kubernetes environment. This was deployed to enable tighter security and traffic control among Kubernetes services.

Section Two: 
This section Focuses attention on what each eks directories is all about,features, and directories.
eks: Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service that makes it easy for you to run Kubernetes on AWS and on-premises. eks was use in this project for automating deployment, scaling, and management of containerized applications.
The feactures and directories includes,Bastion hosts,eks files, vpc varialbes,i am roles,node-group,terraform.tfvars etc.

Section three: How to run the script:
The eks cluster runs first,before the capstone project,the root should always be present and key pair also to be present on aws account before running the command.
cluster-jenkins, installer and jenkinsfiles.
Cluster-jenkins: In this capstone project,cluster-jenkins is connected to Source Code Management (SCM) Git repository. The repository then host the Jenkinsfile and other application files. Jenkins uses the files in the GitHub repository to deploy the applications to the Kubernetes cluster.
Installer.sh help to set the environment to install.eg terraform,helm aws cli etc.

