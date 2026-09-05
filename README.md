<div align="center">

![Himabindu Vallapaneni - DevSecOps Engineer](security-banner.png)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himabindu-v-12ba84282)
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore_Projects-0B7285?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HimabinduVallapaneni?tab=repositories)
[![Profile Views](https://komarev.com/ghpvc/?username=HimabinduVallapaneni&label=Profile+Views&color=2563EB&style=for-the-badge)](https://github.com/HimabinduVallapaneni)

### 🔐 Secure Delivery &nbsp;•&nbsp; ☁️ Cloud Native &nbsp;•&nbsp; ⚙️ Automated &nbsp;•&nbsp; 📊 Observable

</div>

---

## 👩‍💻 About Me

I am a **DevSecOps Engineer with 6+ years of experience** building secure, repeatable software-delivery platforms across AWS and Azure using CI/CD automation, Python, Terraform, Docker, Kubernetes, and policy-driven security controls.

My focus is integrating security into everyday engineering workflows—from source code and open-source dependencies to infrastructure as code, container images, Kubernetes workloads, cloud environments, and production deployments.

I build reusable security controls that help engineering teams detect credible risks earlier, understand remediation requirements, and deliver software without unnecessary friction.

> ### 💡 Engineering Principle
>
> **Security should provide early, actionable feedback and enable safer software delivery—not become an unexplained final gate.**

<div align="center">

| ⚙️ SECURE CI/CD | ☁️ CLOUD SECURITY | 🛡️ SECURITY AUTOMATION | 📊 RELIABILITY |
|:---:|:---:|:---:|:---:|
| Jenkins · GitHub Actions | AWS · Azure · GCP | Python · Bash · PowerShell | Monitoring · Alerting |
| GitLab · Azure DevOps | IAM · KMS · Secrets | Policy as Code | Incident Response |
| SAST · SCA · DAST | Kubernetes · Containers | Vulnerability Workflows | Root-Cause Analysis |
| Risk-Based Gates | Terraform · Helm | Evidence Automation | Recovery Validation |

</div>

---

## 🛡️ Featured Project #1

<table>
<tr>
<td width="68%" valign="top">

### 🔐 SecureHub — Application Security & DevSecOps Platform

An end-to-end **Application Security and DevSecOps project** designed to demonstrate how security controls can be integrated throughout the software-development lifecycle instead of being applied only before production.

SecureHub is being built as a practical application with a **FastAPI backend and modern frontend**, while security controls are progressively integrated across source-code management, pull requests, CI/CD, containerization, infrastructure, and deployment.

**Application architecture**

- ✅ FastAPI backend application
- ✅ REST API architecture
- ✅ Modular backend structure
- ✅ Frontend and backend separation
- ✅ Git-based development workflow
- ✅ Feature and DevOps branch development with pull-request integration

**Application Security & DevSecOps controls**

- ✅ Repository-wide secret scanning with Gitleaks
- ✅ Automated security scanning through GitHub Actions
- ✅ Pull-request security validation
- 🚧 Static Application Security Testing (SAST)
- 🚧 Software Composition Analysis (SCA)
- 🚧 Dependency vulnerability management
- 🚧 Container-image security scanning
- 🚧 Infrastructure-as-Code security scanning
- 🚧 Security gates for high-risk findings
- 🚧 Vulnerability triage and remediation workflows

**Security engineering goals**

- 🔐 Detect exposed credentials and secrets before merge
- 🛡️ Identify vulnerable application code and dependencies
- 🔍 Provide developers with early security feedback
- ⚙️ Automate repeatable security checks through CI/CD
- 📊 Centralize security findings and remediation visibility
- 🚀 Build security into the SDLC rather than treating it as a final release gate

**Current phase**

- 🚧 Expanding repository-wide security controls
- 🚧 Building additional AppSec scanning stages
- 🚧 Integrating vulnerability management workflows
- 🚧 Preparing container and deployment security controls

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-0B7285?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HimabinduVallapaneni/SecureHub)
[![DevOps Works](https://img.shields.io/badge/SECURITY_WORKFLOWS-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/HimabinduVallapaneni/SecureHub/tree/devops)

</td>

<td width="32%" valign="top" align="center">

### Security Flow

```text
┌───────────────┐
│   DEVELOPER   │
│     CODE      │
└───────┬───────┘
        ▼
┌───────────────┐
│ SECRET SCAN   │
│   GITLEAKS    │
└───────┬───────┘
        ▼
┌───────────────┐
│     PULL      │
│    REQUEST    │
└───────┬───────┘
        ▼
┌───────────────┐
│ SAST + SCA    │
│   SECURITY    │
└───────┬───────┘
        ▼
┌───────────────┐
│ CI/CD SECURITY│
│     GATES     │
└───────┬───────┘
        ▼
┌───────────────┐
│   CONTAINER   │
│   SECURITY    │
└───────┬───────┘
        ▼
┌───────────────┐
│    SECURE     │
│  DEPLOYMENT   │
└───────────────┘
```

**Shift Left · Automated**<br>
**Detect · Remediate · Secure**

</td>
</tr>
</table>

---
## ☁️ Featured Project #2

<table>
<tr>
<td width="68%" valign="top">

### ☁️ [AWS Infrastructure Architecture with CloudFormation](https://github.com/HimabinduVallapaneni/AWS_Architectures_CloudFormation)

A hands-on **AWS Infrastructure-as-Code project** demonstrating the progressive design and automated provisioning of AWS compute, networking, security, and scaling components using **AWS CloudFormation and YAML**.

The project moves from basic EC2 provisioning toward complete network architectures and scalable compute infrastructure.

**Infrastructure as Code**

- ✅ AWS infrastructure defined using CloudFormation YAML templates
- ✅ Repeatable infrastructure provisioning through CloudFormation stacks
- ✅ Parameterized infrastructure configuration
- ✅ AWS resource references and dependency management
- ✅ Reusable infrastructure templates

**EC2 automation**

- ✅ EC2 instance provisioning through CloudFormation
- ✅ Amazon Linux EC2 configuration
- ✅ Dynamic AMI retrieval using AWS Systems Manager Parameter Store
- ✅ Configurable instance types and networking
- ✅ Automated resource tagging

**AWS networking architecture**

- ✅ Custom Amazon VPC
- ✅ Subnet creation and CIDR configuration
- ✅ Internet Gateway provisioning and VPC attachment
- ✅ Route-table creation
- ✅ Default internet routing
- ✅ Subnet-to-route-table association

**Network security**

- ✅ Network ACL creation
- ✅ HTTP inbound NACL rules
- ✅ SSH inbound NACL rules
- ✅ Outbound network rules
- ✅ Security Group configuration
- ✅ Security Group association with EC2 workloads

**High availability & scaling**

- ✅ EC2 Launch Template configuration
- ✅ Auto Scaling Group provisioning
- ✅ Minimum, maximum, and desired instance capacity
- ✅ EC2 health-check configuration
- ✅ Integration with existing subnet and Security Group resources

**Architecture progression**

The repository demonstrates infrastructure development incrementally:

`EC2 → VPC → Subnet → Internet Gateway → Routing → NACL → Security Groups → EC2 → Launch Template → Auto Scaling`

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://github.com/HimabinduVallapaneni/AWS_Architectures_CloudFormation)
[![CloudFormation Templates](https://img.shields.io/badge/CLOUDFORMATION_TEMPLATES-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](https://github.com/HimabinduVallapaneni/AWS_Architectures_CloudFormation/tree/AWS_CF_Architectures)

</td>

<td width="32%" valign="top" align="center">

### AWS Architecture

```text
┌───────────────┐
│ CLOUDFORMATION│
│     YAML      │
└───────┬───────┘
        ▼
┌───────────────┐
│      VPC      │
└───────┬───────┘
        ▼
┌───────────────┐
│    SUBNET     │
└───────┬───────┘
        ▼
┌───────────────┐
│ INTERNET GW   │
│  + ROUTING    │
└───────┬───────┘
        ▼
┌───────────────┐
│  NACL + SG    │
│   SECURITY    │
└───────┬───────┘
        ▼
┌───────────────┐
│ EC2 LAUNCH    │
│   TEMPLATE    │
└───────┬───────┘
        ▼
┌───────────────┐
│ AUTO SCALING  │
│     GROUP     │
└───────────────┘
```

**Infrastructure as Code**<br>
**Network · Security · Compute · Scale**

</td>
</tr>
</table>

---

## 🚀 Featured Project3

<table>
<tr>
<td width="68%" valign="top">

### 🔐 [DevSecOps CI/CD Pipeline for a TypeScript Application](https://github.com/HimabinduVallapaneni/Typescript_CICD)

A practical **DevSecOps and GitOps delivery project** built around a responsive Tic-Tac-Toe application developed with **React, TypeScript, Vite, npm, and Tailwind CSS**.

The project demonstrates how application testing, static analysis, container security, image publishing, and Kubernetes deployment configuration can be integrated into an automated GitHub Actions workflow.

**Application capabilities**

- ✅ Interactive Tic-Tac-Toe game built with React and TypeScript
- ✅ Score tracking for X, O, and draws
- ✅ Game history with timestamps
- ✅ Winning-combination highlighting
- ✅ Game and statistics reset functionality
- ✅ Responsive user interface built with Tailwind CSS

**CI and security workflow**

- ✅ GitHub Actions workflow triggered by pushes and pull requests to `main`
- ✅ Node.js 20 environment with reproducible dependency installation using `npm ci`
- ✅ Unit testing of application game logic using Vitest
- ✅ Static code analysis and code-quality validation using ESLint
- ✅ Production application build using Vite
- ✅ Build-artifact creation and transfer between pipeline jobs
- ✅ Multi-stage Docker build using Node.js and Nginx
- ✅ Trivy scanning for critical and high-severity OS and library vulnerabilities
- ✅ Security gate preventing vulnerable images from being published
- ✅ Container-image publishing to GitHub Container Registry
- ✅ Immutable container-image tagging using the Git commit SHA
- ✅ Automatic Kubernetes deployment-manifest image update
- ✅ Automated commit of the updated manifest to GitHub

**Kubernetes deployment configuration**

- ✅ Kubernetes Deployment configured with three application replicas
- ✅ CPU and memory requests and limits
- ✅ Readiness and liveness health probes
- ✅ Internal application exposure through a ClusterIP Service
- ✅ External routing configuration through Kubernetes Ingress
- ✅ GitHub Container Registry image-pull secret integration
- ✅ Git-managed Kubernetes manifests supporting a GitOps delivery model

**Next phase**

- 🚧 Provision a Kubernetes cluster on AWS infrastructure
- 🚧 Install and configure Argo CD in the Kubernetes cluster
- 🚧 Connect Argo CD to the GitHub Kubernetes manifests
- 🚧 Automatically synchronize approved manifest changes
- 🚧 Add deployment health, synchronization, and rollback validation

[![View Project](https://img.shields.io/badge/VIEW_PROJECT-0B7285?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HimabinduVallapaneni/Typescript_CICD)
[![CI/CD Workflow](https://img.shields.io/badge/VIEW_CI%2FCD_WORKFLOW-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/HimabinduVallapaneni/Typescript_CICD/blob/main/.github/workflows/ci-cd.yml)

</td>
<td width="32%" valign="top" align="center">

### Delivery Flow

```text
┌───────────────┐
│  PUSH OR PR   │
└───────┬───────┘
        ▼
┌───────────────┐
│ TEST + LINT   │
└───────┬───────┘
        ▼
┌───────────────┐
│  VITE BUILD   │
└───────┬───────┘
        ▼
┌───────────────┐
│ DOCKER BUILD  │
└───────┬───────┘
        ▼
┌───────────────┐
│ TRIVY SCAN    │
└───────┬───────┘
        ▼
┌───────────────┐
│  PUSH TO GHCR │
└───────┬───────┘
        ▼
┌───────────────┐
│ UPDATE K8S    │
│   MANIFEST    │
└───────┬───────┘
        ▼
┌───────────────┐
│ ARGO CD       │
│ NEXT PHASE    │
└───────┬───────┘
        ▼
┌───────────────┐
│ KUBERNETES    │
│    ON AWS     │
└───────────────┘
```

**Automated · Testable**<br>
**Secure · GitOps-Ready**

</td>
</tr>
</table>

---
