# AWS container sample projects for EKS, ECS, and App Runner

## Objective

* Compare the differences among AWS container services with the sample code from infrastructure provisioning and deployment.
* The contents will help you to choose the right service for your environment.

## Container sample project repositories

### EKS

| Repository                                                               | Time To Complete | Description          |  SonarQube  |
|--------------------------------------------------------------------------|------------------|----------------------|----------------------|
| [cdk-eks-blueprints](https://github.com/engel80/cdk-eks-blueprints)      | 30m | EKS cluster, managed node group, and add-on with EKS Blueprints. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-eks-blueprints&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-eks-blueprints) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-eks-blueprints&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-eks-blueprints) |
| [cdk-eks](https://github.com/engel80/cdk-eks)                            | 30m | EKS cluster and managed node group with CDK.        | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-eks&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-eks)  [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-eks&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-eks)    |
| [eks-eksctl](https://github.com/engel80/eks-eksctl)                      | 30m | EKS cluster and managed node group with eksctl.     |  [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_eks-eksctl&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_eks-eksctl) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_eks-eksctl&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_eks-eksctl)  |
| [eks-terraform](https://github.com/engel80/eks-terraform)                | 30m | EKS cluster and managed node group with Terraform.  |    |
| [eks-gpu-autoscaling](https://github.com/engel80/eks-gpu-autoscaling)    | 1h+ | GPU auto scaling based on Prometheus custom metric. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_eks-gpu-autoscaling&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_eks-gpu-autoscaling) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_eks-gpu-autoscaling&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_eks-gpu-autoscaling)   |
| [eks-gpu-cloudwatch](https://github.com/engel80/eks-gpu-cloudwatch)      | TBD | GPU metric CloudWatch exporter.                      |    |

### ECS

| Repository                                                     | Time To Complete  | Description          | SonarQube  |
|----------------------------------------------------------------|-------------------|----------------------|---------------------|
| [cdk-ecs-fargate](https://github.com/engel80/cdk-ecs-fargate)  | 8m  | RESTful API autoscaling with ECS Fargate and CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-fargate&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-fargate) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-fargate&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-fargate)   |
| [cdk-ecs-ec2](https://github.com/engel80/cdk-ecs-ec2)          | 15m | RESTful API autoscaling with ECS EC2 and CDK.     | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-ec2&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-ec2) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-ec2&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-ec2) |
| [cdk-ecs-gpu](https://github.com/engel80/cdk-ecs-gpu)          | 20m | Inference RESTful API autoscaling with ECS GPU EC2 and CDK.   | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-gpu&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-gpu) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_cdk-ecs-gpu&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_cdk-ecs-gpu) |

### App Runner

| Repository                    | Time To Complete  | Description          |
|-------------------------------|-------------------|----------------------|
| [cdk-apprunner](https://github.com/engel80/cdk-apprunner)  | TBD  | TBD |

## DevOps

| Repository                    | Time To Complete  | Description          |  SonarQube  |
|-------------------------------|-------------------|----------------------|---------------------|
| [jenkins-fargate-cdk](https://github.com/engel80/jenkins-fargate-cdk)  | 7m | Build a Jenkins on Fargate with CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_jenkins-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_jenkins-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_jenkins-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_jenkins-fargate-cdk) |
| [sonarqube-fargate-cdk](https://github.com/engel80/sonarqube-fargate-cdk)  | 12m | Build a continuous inspection system for code quality on Fargate with SonarQube and CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_sonarqube-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_sonarqube-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_sonarqube-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_sonarqube-fargate-cdk) |
| [jenkins-sonarqube-fargate-cdk](https://github.com/engel80/jenkins-sonarqube-fargate-cdk)  | TBD | Build Jenkins and Sonarqube on Fargate with CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=engel80_jenkins-sonarqube-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=engel80_jenkins-sonarqube-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=engel80_jenkins-sonarqube-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=engel80_jenkins-sonarqube-fargate-cdk) |


<img src="https://github.com/engel80/cdk-eks-blueprints/blob/develop/screenshots/diagram.png?raw=true">

<img src="https://github.com/engel80/cdk-ecs-fargate/blob/develop/screenshots/fargate-architecture.png?raw=true" >
