
## The project information: This project based on my project from section 4 but deploy the app into AWS EKS instead of running in local machine. Most of the information I used to do this project in this link: https://circleci.com/developer/orbs/orb/circleci/aws-eks

## Set Up Pipeline
1. Execute linting step in code pipeline: 

* Lint passed:

![lint](screenshots/lint_dockerfile_success.png)

* Lint failed:

![lint-failed](screenshots/lint_dockerfile_failed.png)

* Pipeline run successfully: 

![pipeline-success](screenshots/pipeline_success.png)

## Build Docker Container


![push-docker-1](screenshots/push_docker_success_1.PNG)

![push-docker-2](screenshots/push_docker_success_2.PNG)

![docker-hub](screenshots/docker_hub.PNG)

## Successful Deployment  

1. Deployment successfully: 

![deployment-success](screenshots/deployment_success.png)

2. Get nodes, pods, services:

![kubectl-1](screenshots/kubectl_get_info_1.png)

![kubectl-1](screenshots/kubectl_get_info_2.png)

3. Cloud formation:

![cloudformation](screenshots/Cloud_formation.png)

4. EKS cluster:

![deployed-kubernetes-cluster](screenshots/eks_cluster.png)

5. Run application:

![load_balancers](screenshots/load_balancers.png)

![run_application](screenshots/run_application.png)