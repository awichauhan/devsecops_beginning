# BASIC TERMINOLOGIES OF CI/CD

Here’s a list of basic CI/CD and DevOps terminologies to get you started:
---

### **General Concepts**
1. **DevOps**: A cultural and technical movement focused on collaboration between development and operations teams to deliver high-quality software quickly.
2. **CI/CD**: Continuous Integration (CI) and Continuous Delivery/Deployment (CD), methodologies for automating software development and delivery.
3. **Pipeline**: A set of automated steps that code goes through from development to deployment.
4. **Version Control**: A system (e.g., Git) to manage and track changes to code.

---

### **Continuous Integration (CI)**
1. **Build**: The process of compiling source code into an executable format.
2. **Unit Testing**: Testing individual components or functions of the software.
3. **Integration Testing**: Testing the interaction between different software modules.
4. **Code Coverage**: A measure of how much of the code is tested during the CI process.

---

### **Continuous Delivery/Deployment (CD)**
1. **Delivery**: The process of preparing software to be deployed to production at any time.
2. **Deployment**: Releasing the software to production or end-users.
3. **Rollout**: Gradual deployment of new software versions to users.
4. **Rollback**: Reverting to a previous software version if issues are detected.

---

### **Automation Tools**
1. **Jenkins**: A popular CI/CD automation server.
2. **GitHub Actions**: CI/CD workflows integrated with GitHub repositories.
3. **Docker**: A tool for creating and managing containers.
4. **Kubernetes (K8s)**: A system for automating container deployment, scaling, and management.
5. **Ansible/Puppet/Chef**: Configuration management tools for infrastructure automation.

---

### **Monitoring and Observability**
1. **Logs**: Detailed records of events within the application or system.
2. **Metrics**: Quantifiable measures (e.g., CPU usage, response times) used to monitor system health.
3. **Alerting**: Notifications triggered when predefined thresholds are crossed.
4. **APM (Application Performance Monitoring)**: Tools like New Relic or Datadog used to monitor application performance.

---

### **Testing and Quality Assurance**
1. **Static Code Analysis**: Examining code without executing it to find bugs (e.g., SonarQube).
2. **Dynamic Testing**: Testing software during runtime to identify issues.
3. **Regression Testing**: Ensuring new changes don’t break existing functionality.

---

### **Infrastructure**
1. **Infrastructure as Code (IaC)**: Managing infrastructure through code (e.g., Terraform, CloudFormation).
2. **CI/CD Runner/Agent**: A machine or service that executes CI/CD tasks.
3. **Artifact**: A file or collection of files resulting from a build process (e.g., JAR, Docker image).

---

### **Source Control and Collaboration**
1. **Repository**: A storage location for code (e.g., GitHub, GitLab).
2. **Branching**: Creating separate copies of the codebase for development or testing.
3. **Merge Request/Pull Request (PR)**: A proposal to merge code changes into the main branch.

---

### **Advanced Concepts**
1. **Blue-Green Deployment**: Running two production environments to minimize downtime.
2. **Canary Release**: Releasing updates to a small user base before full deployment.
3. **Chaos Engineering**: Testing system resilience by introducing failures.
4. **Service Mesh**: A dedicated infrastructure layer for service-to-service communication in microservices.

---

# TOOLS FOR DEVSECOPS:

## DEVELOPMENT PHASE:

Tools: 

1. Git Secrets
2. Security plugins (IntelliJ)
3. trufflehog

## SECURITY PHASE:

Tools:
1. Sonarqube: code quality
2. Fortify, veracode, checkmarx: SAST security tools
3. Owasp ZAP, Webinspect, Veracode, DAST, Acunefix : DAST tools
4. Bridgecrew, Synk: Infrastructure as Code security tools
5. Aqua, Qualys, Prismacloud: Container security

## OPERATIONS PHASE:

Tools:

1.  Jenkins, AWS, GCP cloudbuild, Azure Devops, Github actions, Gitlab: Build pipeline tools
2. AQUA, Bridgecrew: CSPM tools
3. AQUA, AWS Native registry scanning: Container registry scanning tools
4. Chef Inspect, Nessus: Infrastructure scanning tool
5. AWS security hub, azure defender: Cloud security tools


# DEVSECOPS IN AZURE

1. Azure source code repos (private repos)
2. azure-pipeline.yml file
3. azure pipelines
4. build artifacts


