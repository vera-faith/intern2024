# LLM Deliverable Week 3

## Install Kubernetes

The first step in getting onboarded to Nautilus involved setting up Kubernetes on my local machine. Kubernetes, often abbreviated as K8s, is an open-source platform designed to automate deploying, scaling, and operating application containers. It provides a framework to run distributed systems resiliently. Before diving into Nautilus, ensuring that Kubernetes was installed correctly was essential.

## Downloaded the Nautilus config
* Has the server information and connection settings/configurations

After setting up Kubernetes, the next step was to download the Nautilus configuration file. This file contains crucial information such as server details, connection settings, and other necessary configurations to connect to the Nautilus cluster.

## Got added to the gilpin-lab namespace

Namespaces in Kubernetes provide a mechanism to isolate groups of resources within a single cluster. Being part of this namespace allowed me to interact with resources and manage deployments specific to the gilpin-lab projects.

* Downloaded the sample .yaml files to create pods and deployments

With access to the gilpin-lab namespace, I downloaded sample `.yaml` files, which are used to create Kubernetes objects like Pods and Deployments. These files provided a template to understand the structure and components required to define and manage Kubernetes resources.

## Learned about Nautilus

Nautilus is an advanced platform designed for managing and deploying containerized applications in an efficient manner. It integrates with Kubernetes, providing capabilities for resource management, monitoring, and deployment automation. Nautilus aims to simplify the complexities involved in orchestrating containers, making it easier for developers to deploy and manage applications at scale.

## Tested and updated the sample .yaml files

Testing and updating the sample `.yaml` files was a critical learning phase. I renamed files and reorganized their locations to fit the project structure better. This exercise helped me understand the anatomy of `.yaml` files and how they are used to define the desired state of Kubernetes resources.


## Learned about pods
1. create, get, describe, delete

2. Exec to get to the pod terminal and execute Linux commands inside the pods

3. Creating and running test-pod-faith .yaml through Kubernetes

Pods are the smallest Kubernetes objects. A Pod represents a single instance of a running process in your cluster and can contain one or more containers. Understanding Pods was essential as they form the building blocks of Kubernetes applications. Additionally, I learned to exec into the Pod's terminal and execute Linux commands inside the container, which is useful for debugging and management.


## Learned about deployments
1. Create, get, describe, delete
2. Exec to get to the deployment terminal and execute Linux commands inside the deploy
3. Creating and running testdep-faith .yaml through Kubernetes

Deployments in Kubernetes provide declarative updates to applications. A Deployment controller ensures that the specified number of Pods are running and available at all times. Learning about Deployments was crucial for managing application lifecycle and ensuring high availability. Just like with Pods, I learned to exec into the Deployment terminal to execute commands within the running containers.

## Conclusion

Getting onboarded to Nautilus and learning the basics of Kubernetes was a transformative experience. From setting up Kubernetes, configuring access to the Nautilus cluster, and understanding namespaces to managing Pods and Deployments, each step was integral in building a strong foundation for working with containerized applications. The hands-on experience with `.yaml` files and Kubernetes commands provided practical knowledge essential for my role in the gilpin-lab.

