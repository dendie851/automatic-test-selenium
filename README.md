# 🚀 Automation Testing with Selenium IDE & Anti-Gravity AI

This project shows how to manage **Functional** and **Regression** testing using **Selenium IDE**. We focus on team collaboration and using **Anti-Gravity AI** to make scripts better and more stable.

## 📚 1. Core Testing Concepts

### Functional Testing
This test checks if the software features work correctly according to the requirements. We look at the input and output without looking at the internal code.

### Regression Testing
This test checks previous features when new changes or bug fixes are added. It makes sure that new code does not break old working features.

## 🛠️ 2. Tools Overview: Selenium IDE
**Selenium IDE** is an open-source browser extension (Chrome/Firefox). It is easy to use for "Record and Playback". However, record results are often messy and need "Refactoring" to be stable and clean.

## 📐 3. Design & Architecture

### Software Testing Life Cycle (STLC)
![STLC Design](file:///d:/mygithub-research/qa-software/automatic-test-selenium/design/design-software-testing-life-cycle.png)
This diagram shows the steps of testing: from Requirement Analysis to Test Closure.

### QA Collaboration Design
![Collaboration Design](file:///d:/mygithub-research/qa-software/automatic-test-selenium/design/design-colaboration-qa-selenium.png)
This shows how different QA members can work on different features and then merge their work into one master file.

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
![Step 1](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/1-selinium.png)

**Step 2: Download the Extension**
Go to the official website or web store to get the extension.
![Step 2](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/2-selinium-dowload.png)

**Step 3: Install Plugin**
Add the extension to your browser (Chrome or Firefox).
![Step 3](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/3-selinium-install-plugin.png)

**Step 4: Installation Complete**
The Selenium IDE icon will appear in your browser toolbar.
![Step 4](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/4-selinium-install-plugin-2.png)

### Part B: Creating Project & Recording

**Step 5: Create New Project**
Open Selenium IDE and select "Create a new project".
![Step 5](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/5-selinium-new-project.png)

**Step 6: Name your Project**
Enter a descriptive name for your automation project.
![Step 6](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/6-selinium-new-project-2.png)

**Step 7: Start Recording**
Enter the Base URL of your application and click "Start Recording".
![Step 7](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/7-selinium-start-recording.png)

**Step 8: Perform Actions on your Page**
As you click and type on your website, Selenium records every step.
![Step 8](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/8-selinium-start-recording-ide-recording.png)

**Step 9: Stop Recording**
Click the stop button in the IDE once you have finished the manual flow.
![Step 9](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/9-selinium-start-recording-recording-stop.png)

### Part C: Refactoring with Anti-Gravity AI

**Step 10: Reviewing the raw script**
The recording result is often messy and contains unnecessary commands.
![Step 10](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/10-selinium-review-dan-rapihkan-value-flow-menggunakna-antigravity.png)

**Step 11: Clean script by AI**
Anti-Gravity AI refactors the script to make it professional and stable.
![Step 11](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/11-selinium-review-dan-rapihkan-value-flow-menggunakna-antigravity-hasil-perbaikan.png)

### Part D: Execution & Results

**Step 12: Playing the Test**
Run the test suite to verify the automation.
![Step 12](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/12-selinium-proses-running-png.png)

**Step 13: Identify Errors**
Failed steps will be highlighted in red with an error message.
![Step 13](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/13-selinium-apabila-ada-error-saat-run-akan-tampak-seperti-inipng.png)

**Step 14: Success Result**
Successful steps will be highlighted in green.
![Step 14](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/14-selinium-apabila-semua-succes-simbol-nya-hijau.png)

### Part E: Advanced Collaboration (Merger)

**Step 15: Separate files for teamwork**
Different QA team members work on separate `.side` files to avoid conflicts.
![Step 15](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/15-selinium-memisahkan-file-side-untuk-manajem-soruce-yg-dikerjakan-banyak-qa.png)

**Step 16: Other feature flows**
Example of another feature (Expedition) being managed separately.
![Step 16](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/16-selinium-contoh-lain-bernama-flow-ekspedisi.png)

**Step 17: Merge into one Master file**
Combine all separate flows into a single Project and Test Suite.
![Step 17](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/17-selinium-merger-flow-dalam-satu-file-dan-test-suite.png)

**Step 18: Configure Parallel Execution**
Enable settings for running multiple tests sequentially or in parallel suites.
![Step 18](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/18-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler.png)

**Step 19: Run All Tests at once**
Execute the master suite to perform full regression testing.
![Step 19](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/19-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler-run-all.png)

**Step 20: All Tests Passed!**
Final result showing both Supplier and Expedition flows finished successfully.
![Step 20](file:///d:/mygithub-research/qa-software/automatic-test-selenium/ss/20-selinium-merger-flow-dalam-satu-file-dan-test-suite-jalankan-secara-paraler-run-all-result.png)

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
