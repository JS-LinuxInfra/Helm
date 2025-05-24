# Helm
Helm functionality, configuration and maintenance.

## Scope
This project covers a series of operational Helm tasks. Each step includes screenshots, the commands used, and an explanation of the task's purpose. The focus areas include charts.

## Environment
- Kubernetes: v1.32.5
- Helm: v3.17.3
- Helm CLI
- kubectl for CLI management and troubleshooting
- Operating System: Ubuntu 24.04.2 LTS (Noble Numbat)
- YAML manifests both authored manually or provided and manipulated/updated during troubleshooting

## Tasks

### Install and start Minikube, confirming no errors, in Ubuntu.
![Step1](Images/step1.png)

### Install Helm and confirm ENVVAR.
![Step2](Images/step2.png)

### Shutdown and delete the cluster.
![Step3](Images/step3.png)

### Query artifacthub.io for consul chart.
![Step4](Images/step4.png)

### Add repo to local repos and confirm present on the control node.
![Step5](Images/step5.png)

### Add repo to local repos, confirm present on the control node, search repos for app.
![Step6](Images/step6.png)

### Start minikube, name and install app from local repo.
![Step7](Images/step7.png)

### Listed installed app(s) and uninstall.
![Step8](Images/step8.png)

### Listed local repo(s) and remove from the controlnode.
![Step9](Images/step9.png)
