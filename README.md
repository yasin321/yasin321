<div align="center">

  <h1>⚡ Yasin Akbari | Senior Jira & Atlassian Architect</h1>
  <h3><code>ScriptRunner (Java/Groovy)</code> • <code>ITSM / JSM & BPMN</code> • <code>DevOps & Linux Infrastructure</code></h3>
  <p><b>🏛️ Architecting Enterprise Atlassian Ecosystems (Data Center & Cloud) & Resilient Docker/Linux Infrastructures 🚀</b></p>

  <!-- Fast CDN Action Buttons (Badgen - Zero Timeout) -->
  <p>
    <a href="https://www.linkedin.com/in/yasin-akbari-jira-agile/" target="_blank"><img src="https://badgen.net/badge/LinkedIn/2.2K+%20Followers%20%7C%20Connect/0A66C2?icon=linkedin" alt="LinkedIn" /></a>
    <a href="https://github.com/yasin321/jira-devops-automation-scripts"><img src="https://badgen.net/badge/ScriptRunner/Groovy%20%26%20Java%20Vault/0052CC?icon=jira" alt="Jira Scripts" /></a>
    <a href="https://github.com/yasin321/linux-infra-and-monitoring"><img src="https://badgen.net/badge/DevOps/Docker%20%26%20Linux%20Stack/2496ED?icon=docker" alt="DevOps Stack" /></a>
    <a href="mailto:ycnakbari@gmail.com"><img src="https://badgen.net/badge/Gmail/ycnakbari@gmail.com/EA4335?icon=mail" alt="Gmail" /></a>
  </p>

  <p>
    <img src="https://badgen.net/badge/Experience/5+%20Yrs%20Enterprise%20IT/10B981" alt="Experience" />
    <img src="https://badgen.net/badge/Scale/280+%20Users%20Governed/3B82F6" alt="Scale" />
    <img src="https://badgen.net/badge/Automation/65%25%20Manual%20Work%20Cut/8B5CF6" alt="Automation" />
    <img src="https://badgen.net/badge/Education/B.Sc.%20Industrial%20Eng%20(FUM)/F59E0B" alt="Education" />
  </p>

</div>

---

### ⚡ Executive Profile & Track Record

- 🏆 **Senior Jira Administrator & Atlassian Solution Architect** leading enterprise configurations across **Actechco**, **MashhadHost**, and **IranHotel Online**—governing 200–280+ user environments across 7+ departments (Engineering, Infrastructure, Product, HR, CRM).
- ☕ **ScriptRunner (Java / Groovy) & Custom Routing Specialist:** Deep mastery of the **Atlassian Java API**—architecting **Multi-Channel Notification Routers**, Matrix RBAC validations, In-Memory Deep Cloning, and asynchronous DOM security locks.
- 🐧 **DevOps & Linux Infrastructure Operations:** Hands-on execution deploying containerized services via **Docker & Docker Compose**, configuring **Nginx** reverse proxies, scripting automated health checks in **Bash/Python**, and managing multi-VPS network tunnels (**Iran ↔ Germany routing**).
- 📊 **ITIL, BPMN & Data-Driven Governance:** Translating complex business logic into **BPMN 2.0** workflows and executive OKR/KPI/SLA telemetry using **Power BI**, **Looker Studio**, **eazyBI**, **Prometheus**, and **Grafana**.

---

### 🗺️ Enterprise Architecture & Automation Blueprint

```mermaid
graph LR
    A[Enterprise Teams] -->|HTTPS / SSL| B(Nginx Reverse Proxy)
    B --> C[Jira Data Center & JSM]
    C --> D{ScriptRunner Engine}
    D -->|Java / Groovy| E[Matrix RBAC & Deep Clone]
    D -->|Webhooks / REST API| F[Multi-Channel Notification Router]
    G[Linux VPS & Docker Compose] --> B
    G --> H[Prometheus & Grafana]
    H -->|Metrics & Logs| I((SLA & Health Alerting))
```

---

### 🛠️ Core Tech Stack & Ecosystem

<div align="center">
  <p><b>🐧 DevOps, Containers, Scripting & Observability</b></p>
  <a href="https://github.com/yasin321">
    <img src="https://skillicons.dev/icons?i=linux,ubuntu,docker,nginx,bash,python,java,js,git,gitlab,githubactions,grafana,prometheus,react,ts&perline=8" alt="Tech Stack Icons" />
  </a>
</div>

<br/>

| 🟦 Atlassian & Process Governance | ☕ Backend & API Automation | 🖧 Infrastructure & Analytics |
| :--- | :--- | :--- |
| • **Jira Data Center & Cloud**<br>• **Jira Service Management (JSM)**<br>• **Confluence & Knowledge Base**<br>• **BPMN 2.0 & ITIL v4 Practices** | • **ScriptRunner (Groovy / Java SDK)**<br>• **Custom Behaviours & Post-Functions**<br>• **Web Fragments & DOM Observers**<br>• **REST APIs & Webhook Routing** | • **Linux Server Admin & Tunneling**<br>• **Docker & Docker Compose**<br>• **Nginx Reverse Proxy & SSL**<br>• **Prometheus, Grafana & Power BI** |

---

### 💎 Production Case Studies (ScriptRunner, Java/Groovy & DevOps)

| 🎯 Enterprise Challenge | ⚙️ Architectural Solution & Production Code | 🔗 Code |
| :--- | :--- | :---: |
| **1. Matrix RBAC via User Properties**<br>*(Zero Custom Field Bloat)* | Engineered sub-50ms live validation using `OSUser PropertySets` (`jira.meta.SalesLevel`), bypassing `setFilter` `MissingMethodException` on system fields. | [Assignee](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/MatrixAccessControl_Assignee.groovy)<br>[MultiUser](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/MatrixAccessControl_MultiUserPicker.groovy) |
| **2. In-Memory Deep Issue Cloning**<br>*(Dynamic Schema Post-Function)* | Eliminated hardcoded field mapping anti-patterns via native `issueFactory.cloneIssue()` in Heap memory + `IssueIndexingService` for Data Center cluster sync. | [Groovy](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/DeepClone_MultiAssignee_PostFunction.groovy) |
| **3. Defense-in-Depth "Assign to Me"**<br>*(3-Layer UI + API Governance)* | Combined **Server-Side Behaviours**, **Web Fragments**, and an **Agile Board `MutationObserver` (JS)** to block unauthorized self-assignment across SPA boards. | [3-Layer](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/TripleLayer_AssignRestriction_Solution.md)<br>[Fragment](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/Hide_AssignToMe_WebFragment.md) |
| **4. Permission Scheme Leak Scanner**<br>*(Jira 9/10 Type-Safe Diagnostics)* | Built an in-memory `SchemeEntity` X-Ray scanner using strict Groovy typing (`O(N)` cached lookup) to detect `BROWSE_PROJECTS` security leaks. | [Scanner](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/PermissionScheme_Leak_Scanner.md) |
| **5. Static Type Checking Standards**<br>*(High-Load Node Safety)* | Eliminated Monaco Editor NBSP syntax traps and enforced explicit `FormField` casting to prevent `NullPointerException` in Data Center nodes. | [Guide](https://github.com/yasin321/jira-devops-automation-scripts/blob/main/Jira_Behaviour_Initialiser_Standard.md) |

---

### 🖧 Infrastructure & Containerization Repositories

- **[🐧 `linux-infra-and-monitoring`](https://github.com/yasin321/linux-infra-and-monitoring):** Production-ready `Docker Compose` observability stack (**Prometheus + Grafana**), **Nginx** reverse proxy routing (`nginx.conf`), and automated **Bash** tunnel latency/health checks (`network_tunnel_check.sh`).
- **[⚛️ `noor-app` (Containerized Web Platform)](https://github.com/yasin321/noor-app):** Full-stack TypeScript/React application packaged with a **Multi-Stage Dockerfile** (`node:20-alpine` + `nginx:alpine`) and automated GitHub Actions workflows.

---

### 💬 Peer Endorsements (From LinkedIn Recommendations)

> *"Yasin is without a doubt one of the most professional, ethical, and dependable colleagues I've worked with. He has an exceptional command of Agile frameworks combined with deep technical expertise in Jira configuration, workflow design, custom fields, dashboards, and automation."*  
> — **Farnaz Tehranpour**, HR Specialist

> *"His passion and strong technical character make him valuable and dynamic, enabling any engineering and business environment he works with to run smoothly."*  
> — **Muhamed Sadeq Rakhshani Moqadam**, DevOps Engineer

---

<div align="center">
  <h3>🤝 Let's Connect & Build Resilient Systems</h3>
  <p>I regularly publish hands-on architectural teardowns on <b>Jira Data Center</b>, <b>ScriptRunner (Java/Groovy)</b>, and <b>DevOps Automation</b> on LinkedIn.</p>
  <a href="https://www.linkedin.com/in/yasin-akbari-jira-agile/" target="_blank">
    <img src="https://badgen.net/badge/LinkedIn/Visit%20Yasin%20Akbari's%20Profile/0A66C2?icon=linkedin" alt="LinkedIn Profile" />
  </a>
</div>
