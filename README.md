# AWS container sample projects for EKS, ECS, and App Runner

## Objective

* Compare the differences among AWS container services with the sample code from infrastructure provisioning and deployment.
* The contents will help you to choose the right service for your environment.

## Container sample project repositories

### EKS

| Repository                                                               | Time To Complete | Description          |
|--------------------------------------------------------------------------|------------------|----------------------|
| [cdk-eks-blueprints](https://github.com/engel80/cdk-eks-blueprints)      | 30m | EKS cluster, managed node group, and add-on with EKS Blueprints. |
| [cdk-eks](https://github.com/engel80/cdk-eks)                            | 30m | EKS cluster and managed node group with CDK.        |
| [eks-eksctl](https://github.com/engel80/eks-eksctl)                      | 30m | EKS cluster and managed node group with eksctl.     |
| [eks-terraform](https://github.com/engel80/eks-terraform)                | 30m | EKS cluster and managed node group with Terraform.  |
| [eks-gpu-autoscaling](https://github.com/engel80/eks-gpu-autoscaling)    | 1h+ | GPU auto scaling based on Prometheus custom metric. |
| [eks-gpu-cloudwatch](https://github.com/engel80/eks-gpu-cloudwatch)      | TBD | GPU metric CloudWatch exporter.                      |

### ECS

| Repository                                                     | Time To Complete  | Description          |
|----------------------------------------------------------------|-------------------|----------------------|
| [cdk-ecs-fargate](https://github.com/engel80/cdk-ecs-fargate)  | 8m  | RESTful API autoscaling with ECS Fargate and CDK. |
| [cdk-ecs-ec2](https://github.com/engel80/cdk-ecs-ec2)          | 15m | RESTful API autoscaling with ECS EC2 and CDK.     |
| [cdk-ecs-gpu](https://github.com/engel80/cdk-ecs-gpu)          | 20m | Inference RESTful API autoscaling with ECS GPU EC2 and CDK.   |

### App Runner

| Repository                    | Time To Complete  | Description          |
|-------------------------------|-------------------|----------------------|
| [cdk-apprunner](https://github.com/engel80/cdk-apprunner)  | TBD  | TBD |

## DevOps

| Repository                    | Time To Complete  | Description          |
|-------------------------------|-------------------|----------------------|
| [sonarqube-fargate-cdk](https://github.com/engel80/sonarqube-fargate-cdk)  | 12m | Build a continuous inspection system for code quality on Fargate with SonarQube and CDK. |
| [jenkins-fargate-cdk](https://github.com/engel80/jenkins-fargate-cdk)  | TBD | Build a Jenkins on Fargate with CDK. |

