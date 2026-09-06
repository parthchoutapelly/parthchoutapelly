# Parth Choutapelly

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=FF9900&center=true&vCenter=true&width=750&lines=Cloud+%2F+AWS+enthusiast;Building+serverless+systems+on+AWS;Currently+shipping%3A+Leave+Management+%2B+VEYRA+Document+Vault)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parth-choutapelly-38686828b/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:parth.choutapelly@gmail.com)

I build and break things on AWS — currently deep in serverless architecture, IAM, and cloud-native app design.

---

### `$ git status`

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=parthchoutapelly&show_icons=true&theme=dark&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=parthchoutapelly&layout=compact&theme=dark&hide_border=true)

---

### `$ cat featured-projects.md`

#### 🏢 Smart Leave & Absence Management

A serverless leave-management platform implementing employee → manager → HR approval workflows.

**Architecture**
- AWS Lambda
- Amazon DynamoDB
- AWS Step Functions
- Amazon API Gateway
- Amazon Cognito
- Amazon SNS
- Amazon SES
- Amazon S3

**Highlights**
- Multi-stage approval workflow
- Conditional HR approval
- Signed approval/rejection actions
- Automatic leave-balance updates after final approval
- Role-based dashboards
- Email and notification workflows
- End-to-end workflow validation

---

#### 🗄️ VEYRA — Employee Document Vault

A centralized employee document-management platform with role-based access and secure document handling.

**Architecture**
- Amazon S3
- Amazon DynamoDB
- AWS Lambda
- Amazon API Gateway
- Amazon Cognito

**Highlights**
- Employee / Manager / HR Admin roles
- Secure pre-signed document URLs
- Document upload and retrieval
- Soft-delete functionality
- Audit logging
- Role-based authorization
- Serverless architecture

---

### `$ cat architecture.md`

```text
                    ┌───────────────┐
                    │    Cognito    │
                    │ Authentication│
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ API Gateway   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │    Lambda     │
                    │ Business Logic│
                    └───┬───────┬───┘
                        │       │
              ┌─────────┘       └─────────┐
              ▼                           ▼
       ┌─────────────┐             ┌─────────────┐
       │  DynamoDB   │             │     S3      │
       │ Application │             │  Documents  │
       │    Data     │             │   / Assets  │
       └─────────────┘             └─────────────┘
                        │
                        ▼
                ┌───────────────┐
                │ Step Functions│
                │   Workflows   │
                └───────────────┘
```

---

### `$ ls certifications/`

🏅 **AWS Partner: Cloud Economics Essentials**
🏅 **AWS Partner: Agentic AI Essentials**
<!-- Add future AWS certifications here -->

---

### `$ cat stack.txt`

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?style=for-the-badge&logo=amazoncognito&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazonapigateway&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![SNS](https://img.shields.io/badge/SNS-FF4F8B?style=for-the-badge&logo=amazonsns&logoColor=white)
![SES](https://img.shields.io/badge/SES-FF9900?style=for-the-badge&logo=amazonses&logoColor=white)

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

### `$ cat learning.log`

Currently exploring:
- ☁️ AWS Solutions Architecture
- 🔐 IAM & cloud security
- 🏗️ Serverless architecture
- ⚡ Event-driven systems
- 🗄️ DynamoDB data modeling
- 🔄 Step Functions workflow design
- 🤖 Agentic AI & Amazon Bedrock
- 💻 Data Structures & Algorithms
- 🧠 OOP / DBMS / OS / Computer Networks

---

### `$ cat philosophy.txt`

```text
Build → Deploy → Break → Debug → Improve
☁️ Prefer cloud-native architectures
🔐 Design with security in mind
📦 Keep systems modular
📊 Understand the data before designing the database
🚀 Ship working systems, not just tutorials
```

---

### `$ watch github_activity`

![GitHub Contribution Snake](https://raw.githubusercontent.com/parthchoutapelly/parthchoutapelly/output/github-contribution-grid-snake.svg)

---

*$ echo "provisioning the next thing..."*
