# Hi, I'm Mohsin 👋

### DevOps & Cloud Engineer | AWS · Terraform · Docker · Kubernetes · GitHub Actions

I'm a DevOps Engineer with a background in **software QA, IT support and technical operations**. I enjoy building cloud infrastructure, automating deployments and investigating the problems that stand between an application and a reliable service.

My experience spans **AWS infrastructure, Infrastructure as Code, CI/CD, containers, application testing and incident investigation**. Working across support and QA has shaped how I approach engineering: understand the system, find the root cause, automate repeatable tasks and make services easier to operate.

I'm particularly interested in **cloud engineering, platform engineering, security and observability**.

## Technologies I work with

| Area | Technologies |
| --- | --- |
| **Cloud & networking** | AWS (ECS Fargate, EKS, EC2, ECR, VPC, IAM, S3, ALB, Route 53, ACM) |
| **Infrastructure as Code** | Terraform, reusable modules, remote state, workspaces |
| **Containers & orchestration** | Docker, Docker Compose, Kubernetes, Helm |
| **CI/CD & automation** | GitHub Actions, Git, OIDC, Bash, Linux |
| **Security** | IAM, security groups, Checkov, Trivy, TFLint |
| **Observability & troubleshooting** | CloudWatch, Better Stack, logs, incident investigation |
| **Testing & collaboration** | Postman, Bruno, Jira, Confluence, Agile Scrum |
| **Databases & systems** | PostgreSQL, SQL Server, Windows administration |

## Featured project

### [AWS ECS IT Tools Deployment](https://github.com/mohsinamin430/ecs-it-tools-deployment)

An end-to-end deployment of a containerised application on **Amazon ECS Fargate**, using **Terraform** for infrastructure provisioning and **GitHub Actions** for automated delivery.

- Designed AWS networking across two Availability Zones, with public and private subnets, a NAT Gateway and security groups.
- Deployed containers to ECS Fargate through an Application Load Balancer, with Route 53, ACM and HTTPS.
- Automated Docker builds, security scans, image pushes to Amazon ECR and ECS deployments using GitHub Actions.
- Used GitHub OIDC and IAM roles instead of long-lived AWS credentials.
- Integrated **TFLint, Checkov and Trivy** to catch configuration issues and vulnerabilities in deployment workflows.

**Technologies:** AWS · Terraform · ECS Fargate · Docker · GitHub Actions · ECR · ALB

## Results and improvements

- **95% smaller Docker image:** reduced image size from **556.58 MB to 30.28 MB** with multi-stage builds.
- **43% faster CI pipeline:** reduced runtime from **5m 21s to 2m 59s**.
- Built a repeatable infrastructure and deployment workflow with automated security checks.
