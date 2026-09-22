# Session Overview – Day 3: DevOps Fundamentals

## What is DevOps?

**DevOps** is a streamlined approach that bridges **Development, Testing, and IT Operations** to make the **Software Development Life Cycle (SDLC)** faster, more reliable, and higher quality through **automation and collaboration**.

---

## Core Problem

In traditional software delivery:

- Development (Dev), Quality Assurance (QA), and Operations (Ops) teams often work in **silos**.
- This can lead to:
  - Miscommunication
  - Blame games
  - Delays
  - Manual errors
  - Slow software releases

### DevOps Solution

DevOps brings teams together and:

- Automates repetitive/manual tasks
- Improves communication and collaboration
- Keeps Dev, QA, and Ops teams aligned
- Speeds up the SDLC
- Improves software quality and release reliability

---

## DevOps Toolchain

| Category | Tools | Purpose |
|---|---|---|
| **Planning** | Jira, Confluence | Jira for tickets; Confluence for documentation |
| **Coding** | Visual Studio Code | Universal code editor / IDE |
| **Code Management** | Git, GitHub | Source-code version control and collaboration |
| **Build Tool (Java)** | Maven | Builds and manages Java projects and dependencies |
| **Artifact Management** | Nexus | Stores and manages build artifacts |
| **Test Automation** | Selenium, JMeter | Selenium for UI/browser testing; JMeter for performance testing |
| **CI/CD** | Jenkins, GitLab | Continuous Integration and Continuous Delivery/Deployment |
| **Containerization** | Docker | Creates and runs container images/containers |
| **Container Orchestration** | Kubernetes | Manages and orchestrates containers |
| **Infrastructure Provisioning** | Terraform | Automates infrastructure creation and provisioning |
| **Configuration/Operations Automation** | Ansible | Automates configuration and operational tasks |
| **Monitoring** | Prometheus, Grafana, CloudWatch, Splunk, Datadog | Monitoring, visualization, AWS monitoring, logging, and observability |

### Tool Usage Notes

- **Java projects → Maven**
- **CI/CD → Jenkins**
- **Containers → Docker**
- **Container orchestration → Kubernetes**
- **Infrastructure as Code → Terraform**
- **Configuration automation → Ansible**
- **Kubernetes monitoring → Prometheus + Grafana**
- **AWS monitoring → CloudWatch**
- **Logging → Splunk**
- **Observability/monitoring → Datadog**

> **Note:** Jenkins was highlighted in the session as a widely used CI/CD tool, with GitLab also commonly used for CI/CD.

---

## Interview Q&A Tips

### 1. How would you define DevOps?

**Suggested answer:**

> DevOps is a combination of practices, collaboration, and automation that bridges Development and Operations teams. It helps automate the software delivery lifecycle, reduce miscommunication, improve quality, and deliver applications faster and more reliably.

### 2. Why is DevOps required?

DevOps helps organizations:

- Reduce manual work
- Minimize human errors
- Improve collaboration between teams
- Automate software delivery
- Reduce release time
- Improve reliability and quality
- Enable faster and more frequent releases

### 3. What is the relationship between DevOps and SDLC?

DevOps improves and automates different stages of the **Software Development Life Cycle (SDLC)**, from planning and coding through building, testing, releasing, deployment, and monitoring.

### 4. Which tool is used for Java builds?

**Maven** is commonly used for building Java applications and managing dependencies.

### 5. Which tool is commonly used for CI/CD?

**Jenkins** is one of the widely used tools for implementing CI/CD pipelines.

### 6. What is the difference between Docker and Kubernetes?

- **Docker** is used to create, package, and run applications in containers.
- **Kubernetes** is used to orchestrate and manage containers at scale.

### 7. Why is communication important in DevOps interviews?

DevOps involves continuous collaboration between multiple teams. Therefore, being able to clearly explain concepts, communicate problems, and describe solutions is critical.

---

## GitHub Profile & Daily Practice

A strong GitHub profile can demonstrate consistent learning and practical work.

Recommended practice:

- Create or maintain a GitHub repository for DevOps learning.
- Upload session notes regularly.
- Commit code and configuration files as you practice.
- Maintain a consistent contribution history.
- Add meaningful README files explaining projects.

> **Important:** GitHub activity can demonstrate consistency and practical engagement, but it should complement actual hands-on skills and project experience.

---

## Day 3 Action Items

- [ ] Fork the challenge repository on GitHub.
- [ ] Upload today's session notes to your GitHub repository.
- [ ] Download and install Visual Studio Code.
- [ ] Create a dedicated DevOps learning repository if you don't already have one.
- [ ] Make your first meaningful Git commit.
- [ ] Practice explaining **"What is DevOps?"** in your own words.
- [ ] Review the purpose of each tool in the DevOps toolchain.

---

## Quick Revision

**DevOps = Collaboration + Automation + Continuous Delivery + Improved Quality**

### Remember the Toolchain

**Plan → Code → Build → Artifact → Test → CI/CD → Containerize → Orchestrate → Provision → Configure → Monitor**

**Jira/Confluence → Git/GitHub → Maven → Nexus → Selenium/JMeter → Jenkins/GitLab → Docker → Kubernetes → Terraform → Ansible → Prometheus/Grafana/CloudWatch/Splunk/Datadog**

---

## Key Interview Statement

> **DevOps bridges Development and Operations through collaboration and automation, helping organizations reduce manual effort and miscommunication while delivering software faster, more reliably, and with better quality.**
