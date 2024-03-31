# project-VM-Jenkins-Sonarqube-Nexus-Slack

This is a VM project with Jenkins pipeline, Quality Gate by Sonarqube, repository by Nexus and job notification by Slack


This is a README.md for Jenkins integration with SonarQube as quality gate, Nexus OSS as artifacts repository and real-time notification via Slack channel.

The project is based on AWS for assignment3 but I am using Vagrant with VMs with local HP laptop.

Here is the topology of VM with its specific functional description and access information with same provisioning parameters used for AWS except the static ip address:
1. Jenkins VM is hosted with ubuntu2004 whose ip: "172.16.11.5" port:8080
2. Nexus VM is hosted with centos/7 whose ip: "172.16.11.2" port:8081
3. SonarQube VM is hosted with /ubuntu2004 whose ip: "172.16.11.3" port 80

The following files and directories provide the essential provisional instructions.
1. Vagrant file is definition for the Oracle Virutalbox Manager
2. The setup directory provides the required bash shell scripts for installing and starting jenkins, sonar and nexus services.
3. The jenkins directory provides the essential provisioning instructions with pipeline code.
4. The nexus directory provides the essential provisioning instructions with sample logs.
5. The sonar directory provides the essential provisioning instructions with sample logs.
6. The slack directory provides the essential provisioning instructions with sample logs.

