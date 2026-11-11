# Hi, I'm Rungroj (Ball)

**AWS Certified Solutions Architect – Associate · Building toward Cloud Engineering & DevOps**

I'm an engineering graduate based in Bangkok, Thailand, building containerized and serverless applications on AWS. My background in full-stack development helps me connect application behavior with the infrastructure that runs it.

I use Terraform to define infrastructure, GitHub Actions to automate deployments, and CloudWatch to understand how my systems behave. I'm interested in reliable, secure cloud systems and the trade-offs behind their design.

**Open to junior Cloud Engineer and DevOps opportunities.**

[Portfolio](https://rungroj.dev) · [Email](mailto:rungrojr.ball@gmail.com)

## Featured projects

### [Movie Ticketing System](https://github.com/Imperator7/Movie-ticketing)

A full-stack booking application with an AWS architecture defined in Terraform.

- **Application:** Next.js, NestJS, PostgreSQL and Docker; transactional seat locking and verified payment webhooks.
- **Infrastructure:** ECS Fargate behind an ALB, RDS PostgreSQL, and an S3 / CloudFront web tier.
- **Operations:** ECS target-tracking auto scaling, CloudWatch alarms with SNS notifications, and GitHub Actions deployments using AWS OIDC.
- **Security and cost:** private database subnets, separate migration and runtime database roles, Fargate Spot, and Bash / AWS CLI shutdown scripts.

*The hosted demo is paused during an AWS account migration. The repository includes instructions for running the application locally.*

### [Portfolio & Serverless Contact API](https://github.com/Imperator7/portfolio-next)

[rungroj.dev](https://rungroj.dev) combines a Next.js frontend on Vercel with a Terraform-provisioned AWS backend.

- API Gateway → Lambda → DynamoDB handles contact submissions.
- DynamoDB Streams → a separate Lambda → SES sends email notifications independently of the API response.
- Cloudflare Turnstile, API throttling, Secrets Manager, and least-privilege IAM protect the contact flow.
- Terraform uses remote state in S3 with locking.

### [Todo List](https://github.com/Imperator7/todolist-frontend)

A React and TypeScript application with TanStack Query, Zod, and MSW. Implements optimistic updates with rollback, input validation, and loading and error states.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Cloud | AWS ECS Fargate, ECR, ALB, RDS, VPC, IAM, S3, Lambda, API Gateway, DynamoDB, SES |
| Infrastructure & delivery | Terraform, Docker, GitHub Actions, AWS OIDC, AWS CLI |
| Operations & security | CloudWatch, SNS, Secrets Manager, SSM Parameter Store, Linux, Bash |
| Development | TypeScript, Node.js, React, Next.js, NestJS, Python, SQL, PostgreSQL |

## Currently developing

- Cloud operations skills while preparing for AWS Certified CloudOps Engineer – Associate.
- Linux administration and troubleshooting.
- SRE fundamentals: SLIs, SLOs, error budgets, monitoring, and incident response, with the goal of applying them to my projects.

## Background

- **AWS Certified Solutions Architect – Associate (SAA-C03)**
- **B.Eng. in Civil Engineering**, Chulalongkorn University
- **TOEIC 965/990**

I'm looking for a team where I can contribute, learn from experienced engineers, and grow through operating real systems.
