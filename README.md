<!--
PROFILE README SETUP
1) Create a PUBLIC repository named exactly your GitHub username.
   For you: MK-MAN0JKUMAR/MK-MAN0JKUMAR
2) Add this file as README.md
3) Replace placeholders marked with: REPLACE_ME

REPLACE THESE VALUES
- GitHub username: MK-MAN0JKUMAR   (already set below)
- LinkedIn URL:   REPLACE_ME_LINKEDIN_URL
- Email address:  REPLACE_ME_EMAIL

NOTES
- Keep pinned repos on your profile aligned with the "Featured Engineering Work" section.
- This README is intentionally recruiter-first: clean, technical, fast to scan.
-->

# Manoj Kumar
**Automation Test Engineer transitioning toward SDET**  
3.6+ years in software testing (Automation + Manual) | Framework Engineering | UI + API + CI/CD readiness

---

## Professional Summary
I build and evolve automation frameworks with a focus on **architecture**, **stability**, and **scalability**. My work emphasizes maintainable design (POM/service layers), strong diagnostics (logs/screenshots/reports), and execution models that fit **local development**, **regression**, and **CI pipelines**.

---

## Automation Engineering Focus
**What I optimize for in real-world automation:**
- Framework structure that supports fast onboarding and consistent patterns
- Flakiness control: synchronization strategy, deterministic assertions, actionable failure evidence
- CI-friendly execution: tagged suites, configurable environments, and report artifacts
- Clear separation of concerns (tests vs. page/service layers vs. utilities)

**Framework capabilities (implemented across projects):**
- Hybrid automation framework patterns
- Page Object Model (POM)
- Logging + screenshot capture
- Allure / Extent reporting
- TestNG execution model
- Data Driven Testing (DDT) (JSON/Excel where applicable)
- Parallel execution patterns (where supported by the framework design)
- Database validation utilities (MySQL checks where applicable)

---

## Technical Skills

### Automation / Test Stack
- **Selenium WebDriver**, **TestNG**, **Cucumber BDD**, **Maven**
- **Postman** (API testing)
- **JMeter** (performance testing)
- **MySQL** validation and data verification

### Programming
- **Java**, **SQL**

### Reporting & Evidence
- **Allure Reports**
- **Extent Reports**
- Logging + screenshots + artifacts for CI triage

---

## Current Learning Roadmap
- **API Automation with Rest-Assured** (enterprise patterns, reusable clients, schema validations)
- **CI/CD pipelines** using **GitHub Actions** and **Jenkins** (gates, artifacts, test stages)

## Forward Roadmap (Planned)
- Playwright with TypeScript
- AI-assisted testing (controlled usage and reviewable test design)
- LLM-based test data generation and AI debugging tools
- Self-healing automation (pragmatic application)
- AI agents for test workflows (triage, execution orchestration, coverage insights)
- CI/CD + AI integration; MCP Playwright ecosystem

---

## Featured Engineering Work
<!--
UI TIP (IMPORTANT): Pin these same repositories on your GitHub profile.
Go to your profile -> "Customize your pins" -> pick 3–6 flagship repos.
-->

### 1) Production-grade API Automation Framework
**Repo:** `restassured-enterprise-framework`  
**Stack:** Java, Rest-Assured, TestNG, Maven  
**What it demonstrates:** senior-style API framework structure, reusability, maintainability, and CI readiness  
- Request/response abstractions and reusable utilities
- Config-driven environment handling
- Reporting + logging suitable for pipelines

### 2) Enterprise UI Automation Framework (CI/CD-ready)
**Repo:** `frameworkforge-sdet`  
**Stack:** Java, Selenium, TestNG, Maven  
**What it demonstrates:** maintainable POM design and execution profiles (local/regression/CI)  
- Clean test structure and reusable page layers
- Execution profile strategy for predictable runs
- CI-friendly organization for scheduled and gated runs

### 3) AI-assisted Playwright Automation Framework
**Repo:** `mcp_playwright_automation`  
**Stack:** JavaScript, Playwright, MCP, Copilot-assisted workflows  
**What it demonstrates:** modern E2E design and controlled AI usage for stability and maintainability  
- Scalable E2E suite structure
- Controlled AI usage patterns (review gates, consistent structure)
- Stability improvements and repeatable execution

### 4) Hybrid Framework (Selenium + Cucumber + TestNG)
**Repo:** `AutoHive_Framework`  
**Stack:** Java, Selenium, Cucumber, TestNG  
**What it demonstrates:** hybrid framework capabilities (DDT, evidence capture, reporting)  
- DDT with JSON/Excel (where applicable)
- Screenshot capture + logging + reporting
- Parallel execution patterns (Driver Factory approach)

---

## Portfolio Architecture (Reference Diagrams)

### CI/CD Pipeline (Reference)
```mermaid
flowchart LR
  A[Commit / Pull Request] --> B[CI Trigger]
  B --> C[Build (Maven)]
  C --> D[Smoke Suite]
  D --> E[Regression Suite (UI/API)]
  E --> F[Reports: Allure / Extent]
  F --> G[Artifacts: logs/screenshots]
  G --> H[Quality Gate: pass/fail + thresholds]
  H -->|Pass| I[Merge / Release]
  H -->|Fail| J[Notify + Triage]
```

### Automation Framework Architecture (Reference)
```mermaid
flowchart TB
  RUN[Test Runner: TestNG/Cucumber] --> SUITES[Suites / Tags / Profiles]
  SUITES --> TESTS[Test Cases]
  TESTS --> POM[Page Objects]
  TESTS --> API[API Layer]
  TESTS --> DB[DB Utilities]
  TESTS --> DATA[Test Data (JSON/Excel)]
  POM --> DRV[Driver Factory / Browser Config]
  API --> HTTP[HTTP Clients (Rest-Assured / helpers)]
  DRV --> CFG[Config & Environment Mgmt]
  HTTP --> CFG
  DB --> CFG
  TESTS --> OBS[Observability]
  OBS --> LOG[Logs]
  OBS --> SS[Screenshots]
  OBS --> REP[Allure / Extent Reports]
```

---

## GitHub Statistics Dashboard
<!--
Widgets below are the only "visuals" intentionally used.
Clean, professional, and commonly accepted by engineering managers.
If any widget fails to load, remove `theme=...` or switch themes.
-->

### Overview
[![GitHub Readme Stats](https://github-readme-stats.vercel.app/api?username=MK-MAN0JKUMAR&show_icons=true&hide_title=true&include_all_commits=true&count_private=true&rank_icon=github&theme=default)](https://github.com/MK-MAN0JKUMAR)

### Streak
[![GitHub Streak](https://streak-stats.demolab.com?user=MK-MAN0JKUMAR&theme=default)](https://github.com/MK-MAN0JKUMAR)

### Top Languages
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=MK-MAN0JKUMAR&layout=compact&theme=default)](https://github.com/MK-MAN0JKUMAR)

### Activity Graph
[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=MK-MAN0JKUMAR&theme=github-compact)](https://github.com/MK-MAN0JKUMAR)

---

## Contribution Graph
GitHub’s contribution graph is visible on my profile. I optimize for **meaningful changes**: framework improvements, documentation, CI integration, stability fixes, and repeatable execution patterns.

---

## Contact
<!-- Replace placeholders with your real details -->
- **LinkedIn:** REPLACE_ME_LINKEDIN_URL
- **Email:** REPLACE_ME_EMAIL

---

<!--
PROFILE IMPROVEMENT CHECKLIST (Do this after adding the README)

PINNED REPOS (critical for recruiters)
- Pin 3–6 repos: restassured-enterprise-framework, frameworkforge-sdet, mcp_playwright_automation, AutoHive_Framework (+ 1 optional)

REPO READMEs (make each repo recruiter-proof)
For each featured repo, add:
1) "Problem -> Solution -> Architecture" (5–8 lines)
2) Tech stack and folder structure
3) How to run locally (mvn commands / node commands)
4) How to run in CI (GitHub Actions workflow)
5) Sample report screenshot (Allure/Extent)
6) Test design conventions (naming, tagging, retries policy, flaky test policy)

CI/CD (high leverage)
- Add GitHub Actions workflows to at least your top 2 repos:
  - Build + run smoke
  - Upload reports as artifacts
  - Optional: scheduled nightly regression

DOCUMENTATION (signals seniority)
- Add an /docs folder to flagship repos with:
  - framework-architecture.md
  - execution-profiles.md
  - reporting-and-artifacts.md

QUALITY SIGNALS
- Add consistent formatting, clean commits, and small PR-style changes even on personal repos.
-->
