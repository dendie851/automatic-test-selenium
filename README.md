# 🚀 Automation Testing with Selenium IDE

This project shows how to manage **Functional** and **Regression** testing using **Selenium IDE**. We focus on team collaboration and using **Anti-Gravity AI** to make scripts better and more stable.

## 📌 Table of Contents
1. [Core Testing Concepts](#-1-core-testing-concepts)
2. [Tools Overview: Selenium IDE](#-2-tools-overview-selenium-ide)
3. [Design & Architecture](#-3-design--architecture)
4. [Best Practice: Separation & Merger](#-4-best-practice-separation--merger)
5. [How Anti-Gravity AI Helps](#-5-how-anti-gravity-ai-helps)
6. [User Manual & Step-by-Step Guide](#-6-user-manual--step-by-step-guide)
    *   [Part A: Installation & Setup](#part-a-installation--setup)
    *   [Part B: Creating Project & Recording](#part-b-creating-project--recording)
    *   [Part C: Refactoring with Anti-Gravity AI](#part-c-refactoring-with-anti-gravity-ai)
    *   [Part D: Execution & Results](#part-d-execution--results)
    *   [Part E: Advanced Collaboration (Merger)](#part-e-advanced-collaboration-merger)
7. [Script Snippet (.side structure)](#-7-script-snippet-side-structure)
8. [Advanced WebDev Automation & Allure Reporting](#-8-advanced-webdev-automation--allure-reporting)
    *   [8.1 Professional Regression Testing Definition](#81-professional-regression-testing-definition)
    *   [8.2 Automation System Architecture](#82-automation-system-architecture)
    *   [8.3 Step-by-Step Reporting Workflow](#83-step-by-step-reporting-workflow)
    *   [8.4 WebDev Reporting Showcase](#84-webdev-reporting-showcase)

## 📚 1. Core Testing Concepts

### Functional Testing
This test checks if the software features work correctly according to the requirements. We look at the input and output without looking at the internal code.

### Regression Testing
This test checks previous features when new changes or bug fixes are added. It makes sure that new code does not break old working features.

## 🛠️ 2. Tools Overview: Selenium IDE
**Selenium IDE** is an open-source browser extension (Chrome/Firefox). It is easy to use for "Record and Playback". However, record results are often messy and need "Refactoring" to be stable and clean.

## 📐 3. Design & Architecture

### Software Testing Life Cycle (STLC)
This diagram shows the steps of testing: from Requirement Analysis to Test Closure.
![STLC Design](./design/design-software-testing-life-cycle.png)

### QA Collaboration Design
This shows how different QA members can work on different features and then merge their work into one master file.
![Collaboration Design](./design/design-colaboration-qa-selenium.png)

## 🤝 4. Best Practice: Separation & Merger
In big teams, we should:
*   **Separate**: Every QA works on their own `.side` file (e.g., `Flow-Supplier.side`).
*   **Merge**: Use a tool (like Anti-Gravity AI) to combine these files into one Master file (`Flow-All-Merger.side`) for full testing.

## 🤖 5. How Anti-Gravity AI Helps
Recording in Selenium IDE is often "flaky" (breaks easily). **Anti-Gravity AI** fixes this by:
1.  **Refactoring**: Replacing buggy `type` commands with stable `executeScript`.
2.  **Dynamic Locators**: Finding rows by text instead of fixed row numbers.
3.  **Fast Merger**: Combining different `.side` files quickly and safely.

## 📸 6. User Manual & Step-by-Step Guide

### Part A: Installation & Setup

**Step 1: Selenium IDE Overview**
Start by understanding the Selenium IDE workspace.
![Step 1](./ss/1-selinium.png)

**Step 2: Download the Extension**
Go to the official website or web store to get the extension.
![Step 2](./ss/2-selinium-dowload.png)

**Step 3: Install Plugin**
Add the extension to your browser (Chrome or Firefox).
![Step 3](./ss/3-selinium-install-plugin.png)

**Step 4: Installation Complete**
The Selenium IDE icon will appear in your browser toolbar.
![Step 4](./ss/4-selinium-install-plugin-2.png)

### Part B: Creating Project & Recording

**Step 5: Create New Project**
Open Selenium IDE and select "Create a new project".
![Step 5](./ss/5-selinium-new-project.png)

**Step 6: Name your Project**
Enter a descriptive name for your automation project.
![Step 6](./ss/6-selinium-new-project-2.png)

**Step 7: Start Recording**
Enter the Base URL of your application and click "Start Recording".
![Step 7](./ss/7-selinium-start-recording.png)

**Step 8: Perform Actions on your Page**
As you click and type on your website, Selenium records every step.
![Step 8](./ss/8-selinium-start-recording-ide-recording.png)

**Step 9: Stop Recording**
Click the stop button in the IDE once you have finished the manual flow.
![Step 9](./ss/9-selinium-start-recording-recording-stop.png)

### Part C: Refactoring with Anti-Gravity AI

**Step 10: Reviewing the raw script**
The recording result is often messy and contains unnecessary commands.
![Step 10](./ss/10-selinium-review-dan-rapihkan-value-flow-menggunakna-antigravity.png)

**Step 11: Clean script by AI**
Anti-Gravity AI refactors the script to make it professional and stable.
![Step 11](./ss/11-selinium-review-dan-rapihkan-value-flow-menggunakna-antigravity-hasil-perbaikan.png)

### Part D: Execution & Results

**Step 12: Playing the Test**
Run the test suite to verify the automation.
![Step 12](./ss/12-selinium-proses-running-png.png)

**Step 13: Identify Errors**
Failed steps will be highlighted in red with an error message.
![Step 13](./ss/13-selinium-apabila-ada-error-saat-run-akan-tampak-seperti-inipng.png)

**Step 14: Success Result**
Successful steps will be highlighted in green.
![Step 14](./ss/14-selinium-apabila-semua-succes-simbol-nya-hijau.png)

### Part E: Advanced Collaboration (Merger)

**Step 15: Separate files for teamwork**
Different QA team members work on separate `.side` files to avoid conflicts.
![Step 15](./ss/15-selinium-memisahkan-file-side-untuk-manajem-soruce-yg-dikerjakan-banyak-qa.png)

**Step 16: Other feature flows**
Example of another feature (Expedition) being managed separately.
![Step 16](./ss/16-selinium-contoh-lain-bernama-flow-ekspedisi.png)

**Step 17: Merge into one Master file**
Combine all separate flows into a single Project and Test Suite.
![Step 17](./ss/17-selinium-merger-flow-dalam-satu-file-dan-test-suite.png)

**Step 18: Configure Parallel Execution**
Enable settings for running multiple tests sequentially or in parallel suites.
![Step 18](./ss/18-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler.png)

**Step 19: Run All Tests at once**
Execute the master suite to perform full regression testing.
![Step 19](./ss/19-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler-run-all.png)

**Step 20: All Tests Passed!**
Final result showing both Supplier and Expedition flows finished successfully.
![Step 20](./ss/20-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler-run-all-result.png)

## 💻 7. Script Snippet (.side structure)
Example of optimized code from `Flow-All-Merger-Selenium.side`:

```json
{
  "name": "Flow All Merger",
  "tests": [
    {
      "name": "1. Flow Pemasok",
      "commands": [
        { "command": "open", "target": "/home/index.php", "comment": "Buka Login" },
        { "command": "executeScript", "target": "document.getElementsByName('username')[0].value='admin'", "comment": "Bypassing Bug" }
      ]
    }
  ]
}
```

---

## 📊 8. Advanced WebDev Automation & Allure Reporting

This section provides a deep dive into the professional-grade automation environment and the reporting workflow.

### 8.1 Professional Regression Testing Definition
In a professional software development environment, **Regression Testing** is an essential verification process performed after code modifications, environment updates, or system integrations. Its primary function is to confirm that existing functionalities remain intact and have not been adversely affected by recent changes. This practice is critical for maintaining software stability and preventing "functional drift" throughout the iterative development lifecycle.

### 8.2 Automation System Architecture
The following diagram illustrates the integration between the Selenium WebDriver engine, the Mocha orchestration layer, and the Allure reporting framework within our WebDev environment.

![Automation System Architecture](./design/design-Selenium-WebDev-Report.png)

### 8.3 Step-by-Step Reporting Workflow
Follow this comprehensive guide to execute tests and generate professional reports within the WebDev environment:

**Step 0: System Prerequisites**
Before proceeding, ensure you have **Node.js** and **NPM** (Node Package Manager) installed on your system.
1. Download the installer from the official [Node.js website](https://nodejs.org/).
2. Follow the installation wizard for your OS (Windows/Mac/Linux).
3. Verify installation by running `node -v` and `npm -v` in your terminal.
![Software Requirements](./ss/report/1-install-selenium-web-dev.png)

**Phase 1: Environment Initialization**
Once Node.js is ready, initialize the workspace by installing all necessary core dependencies and automation drivers via NPM.
```bash
npm install
```
![NPM Installation](./ss/report/2-install-selenium-web-dev-via-npm.png)

**Phase 2: Project Recording (Selenium IDE)**
Start by recording your initial manual flow using the Selenium IDE extension. This captures the base interactions of your application.
![Recording Flow](./ss/8-selinium-start-recording-ide-recording.png)

**Phase 3: Conversion to Professional Test Runner**
Export the recorded project from Selenium IDE into a structured **JavaScript/Mocha** format. This step moves the test from a simple recording to a scalable code base.
![Export to JS](./ss/report/3.1-convertion-fitur-export-to-javascript-mocha.png)

**Phase 4: Script Optimization (AI-Driven Refactoring)**
Optimize the exported script using **Antigravity AI**. This process replaces unstable absolute paths or flaky commands with stable `executeScript` logic and interactive Allure steps.
![AI Refactoring](./ss/report/3.2-convertion-file-flow-all-merger-selenium-side-ke-flow-all-merger-selenium-gunakan-ai-antigravity.png)

**Phase 5: Automated Execution**
Configure your `package.json` and execute the test suite via the command line interface (CLI) to trigger the automated browser sessions.
![Run Test](./ss/report/5-runing-test-menggunakan-selenium-web-dev.png)

**Phase 6: Result Persistence & Report Generation**
Captured data is processed to create a high-fidelity Allure Dashboard, providing full visibility of the testing results and screenshots.
![Report Generation](./ss/report/7-jalan-report.png)

### 8.4 WebDev Reporting Showcase
The reporting environment provides rich visualization of the testing lifecycle:

> [!IMPORTANT]
> **View Local Report**: [Open Allure Report Index](./allure-report/index.html) (Ensure you have generated the report first using `allure generate`).

*   **Interactive Steps Monitoring**: Track each of the 26 execution steps with precise timestamps.
    ![Step Monitoring](./ss/report/8-jalan-report-menampilkan-all-step-dari-setiap-flow.png)
*   **Visual Evidence Injection**: Every manual step included in the `.side` file is mapped to a screenshot in the report for undeniable verification.
    ![Visual Evidence](./ss/report/9-jalan-report-menampilkan-all-flow-sucess-dan-evidance-screenshoot.png)
*   **Portable HTML Distribution**: Export the dashboard to a standalone HTML format for easy sharing across the organization.
    ![Portable Report](./ss/report/12-report-convert-to-html-tersimpan-di-folder-allure-report-hasil-nya-bisa-dilihat-dibrowser-dan-share-ke-komputer-lain-dan-standalone.png)


