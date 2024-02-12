![Kubernetes Pods](https://github.com/yeshwanthlm/100DaysOfK8s/assets/66474973/97a8ec25-c72e-4a77-b252-f1519eb7fb32)

In this video we will be learing the following:

1. What is a pod
2. How to create pods (both via the CLI and with YAML)
3. How to access documentation related to a pod specification 
4. How to execute a command in a running pod 
5. Pod restart policies (the default value and available options)
6. The difference between Declarative and Imperative approaches when using kubectl
7. How pods make use of the network namespace for a shared IP address
8. How pods are able to communicate without the use of NAT or other complicated network setups
9. Running multiple containers in a pod
10. Accessing logs from a particular container when running multiple containers in a pod
11. Accessing logs from a terminated container in a pod when running multiple containers
12. What is a sidecar and how it could be implemented


Imperative Commands (create, replace or delete)

In Kubernetes, imperative commands are a way to interact with the cluster by directly instructing it to perform specific operations. These commands focus on the desired outcome rather than the underlying
configuration files or declarative state. When using imperative commands, you provide explicit instructions to create, replace, or delete.

While imperative commands can be convenient, they may result in configuration drift if not carefully managed, as the desired state is not
explicitly defined and tracked.


Declarative Approach (apply)

In Kubernetes, declarative commands are a preferred approach for managing the cluster's state and resources. With declarative commands, you define the desired state of your Kubernetes objects using YAML or JSON configuration.

Rather than specifying individual operations, you provide a complete representation of the desired state of your resources. When applying these files, Kubernetes compares the desired state with the current state of the cluster and automatically performs the necessary operations to reconcile any differences.


--------------------------
Follow our tutorials here: https://www.youtube.com/@amonkincloud/videos \
Follow my personal blog here:https://dev.to/yeshwanthlm/ \
Follow us on Instagram: https://www.instagram.com/amonkincloud/ \
For queries write to us at: amonkincloud@gmail.com 
