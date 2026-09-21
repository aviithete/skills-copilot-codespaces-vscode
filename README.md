<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->
<img width="1433" height="737" alt="Screenshot 2026-09-20 210132" src="https://github.com/user-attachments/assets/19a81f8f-e97c-4142-8f49-100fbf22f398" />
## Project File
https://docs.google.com/spreadsheets/d/1-qTpvrSpeT-HcCq-GhLOQX1UqaRnjOnG/edit?usp=drive_link&ouid=104468940255882372981&rtpof=true&sd=true
# HR Employee Analysis Dashboard 📊

## Project Overview

The **HR Employee Analysis Dashboard** is an Excel-based HR analytics project designed to analyze employee data, workforce trends, and employee attrition patterns.

The project transforms employee data into an interactive dashboard using **Pivot Tables, Pivot Charts, KPIs, Slicers, and Excel formulas**.

## Business Problem

HR departments need to understand workforce patterns and employee attrition in order to support effective workforce planning and retention analysis.

This project analyzes employee demographics, departments, job roles, compensation, satisfaction, overtime, experience, and tenure to identify important patterns in the HR dataset.

## Objectives

* Analyze employee workforce data.
* Measure employee attrition.
* Analyze attrition by department and job role.
* Study overtime and employee attrition patterns.
* Analyze employee satisfaction and work-life balance.
* Analyze salary, experience, and tenure.
* Create an interactive HR dashboard.
* Generate data-driven business insights.

## Key Analysis Areas

* Employee Attrition
* Department Analysis
* Job Role Analysis
* Age Group Analysis
* Gender Analysis
* Salary / Monthly Income
* Overtime Analysis
* Job Satisfaction
* Work-Life Balance
* Employee Experience
* Years at Company
* Performance Rating

## Tools & Skills

**Microsoft Excel**

* Data Cleaning
* Data Analysis
* Pivot Tables
* Pivot Charts
* Slicers
* KPI Cards
* Excel Formulas
* Data Visualization
* Dashboard Design
* Business Insights

## Dashboard Structure

1. Home Page
2. HR Dashboard
3. Insights
4. Employee Details
5. KPI Charts
6. Pivot Tables
7. HR Dataset
8. Raw Data

## Business Value

The dashboard provides HR-focused views of employee data and helps users explore workforce composition, attrition patterns, satisfaction, compensation, and employee tenure.

It can support HR teams in identifying areas that require further investigation and data-driven workforce analysis.

## Project Outcome

This project demonstrates practical skills in **Excel, HR Analytics, Data Visualization, Dashboard Development, and Business Intelligence**.

## Note

The analysis describes patterns within the available dataset. Observed relationships should not automatically be interpreted as causal relationships.

# Code with GitHub Copilot

_GitHub Copilot can help you code by offering autocomplete-style suggestions right in VS Code and Codespaces._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Leverage Codespaces with VS Code for Copilot

_Welcome to "Develop With AI Powered Code Suggestions Using GitHub Copilot and VS Code"! :wave:_

GitHub Copilot is an AI pair programmer that helps you write code faster and with less work. It draws context from comments and code to suggest individual lines and whole functions instantly. GitHub Copilot is powered by OpenAI Codex, a generative pretrained language model created by OpenAI.

**Copilot works with many code editors including VS Code, Visual Studio, JetBrains IDE, and Neovim.**

Additionally, GitHub Copilot is trained on all languages that appear in public repositories. For each language, the quality of suggestions you receive may depend on the volume and diversity of training data for that language.

Using Copilot inside a Codespace shows just how easy it is to get up and running with GitHub's suite of [Collaborative Coding](https://github.com/features#features-collaboration) tools.

> **Note**
> This skills exercise will focus on leveraging GitHub Codespace. It is recommended that you complete the GitHub skill, [Codespaces](https://github.com/skills/code-with-codespaces), before moving forward with this exercise.

### :keyboard: Activity: Enable Copilot inside a Codespace

**We recommend opening another browser tab to work through the following activities so you can keep these instructions open for reference.**

Before you open up a codespace on a repository, you can create a development container and define specific extensions or configurations that will be used or installed in your codespace. Let's create this development container and add copilot to the list of extensions.

1. Navigating back to your **Code** tab of your repository, click the **Add file** drop-down button, and then click `Create new file`.
1. Type or paste the following in the empty text field prompt to name your file.
   ```
   .devcontainer/devcontainer.json
   ```
1. In the body of the new **.devcontainer/devcontainer.json** file, add the following content:
   ```
   {
       // Name this configuration
       "name": "Codespace for Skills!",
       "customizations": {
           "vscode": {
               "extensions": [
                   "GitHub.copilot"
               ]
           }
       }
   }
   ```
1. Select the option to **Commit directly to the `main` branch**, and then click the **Commit new file** button.
1. Navigate back to the home page of your repository by clicking the **Code** tab located at the top left of the screen.
1. Click the **Code** button located in the middle of the page.
1. Click the **Codespaces** tab on the box that pops up.
1. Click the **Create codespace on main** button.

   **Wait about 2 minutes for the codespace to spin itself up.**

1. Verify your codespace is running. The browser should contain a VS Code web-based editor and a terminal should be present such as the below:
   ![Screen Shot 2023-03-09 at 9 09 07 AM](https://user-images.githubusercontent.com/26442605/224102962-d0222578-3f10-4566-856d-8d59f28fcf2e.png)
1. The `copilot` extension should show up in the VS Code extension list. Click the extensions sidebar tab. You should see the following:
   ![Screen Shot 2023-03-09 at 9 04 13 AM](https://user-images.githubusercontent.com/26442605/224102514-7d6d2f51-f435-401d-a529-7bae3ae3e511.png)

**Wait about 60 seconds then refresh your repository landing page for the next step.**

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
