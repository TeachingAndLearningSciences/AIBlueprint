# AI - Education Blueprint – Behavior-Driven Testing in Software Quality


## 1. General Lecture Description

|   |         |
|-----------------------|-----------------------------------|
| **ACM Category**      | Software Engineering (SE)         |
| **Knowledge Unit**    | SE-Requirements                   |
| **Lecture Description** | The lecture introduces Behavior-Driven Testing (BDT) principles, tools, and AI-assisted test case generation for software quality assurance. |


## 2. Lecture Contents

| **Learning Objectives**      |                                                                                 | Bloom Level | 
|-----------------------------|---------------------------------------------------------------------------------|------| 
| LO1                         | Describe the principles and process of Behavior-Driven Testing.   | *(Understand)*| 
| LO2                         | Apply BDT techniques and tools to translate requirements into testable scenarios.|  *(Apply)* |
| LO3                         | Evaluate benefits and limitations of AI-generated test cases.      |*(Evaluate)*  | 


| **AI-Related LOs**      |                                                                                 | AI-Usage | Related LO |
|-----------------------------|---------------------------------------------------------------------------------|------|---|
| AI-LO1                         | Describe the principles and process of Behavior-Driven Testing. *(Understand)*   | *(Generate)* | LO2|
| AI-LO2                         | LOAI-2: Use AI to draft Gherkin feature files from user stories or requirements. | *(Generate)* | LO2|
| AI-LO3                         | Evaluate benefits and limitations of AI-generated test cases. *(Evaluate)*      | *(Generate)* | LO2|

**Topics Covered:**
<br> - Principles of BDT and its support for software quality <br> - Structure and syntax of Gherkin scenarios <br> - Test automation using BDT frameworks (e.g., Cucumber + Selenium/Java/Python) <br> - Using LLMs to generate feature files from natural language requirements <br> - Critical assessment of AI-generated test scenario


## 3. Lecture Activities


Students will engage in hands-on exercises using BDT tools and AI-assisted generation of feature files. They’ll work in small teams to translate natural language user stories into testable Gherkin scenarios manually and with AI, then automate these scenarios.

### Activities / Hands-On:
- Create basic requirements and user stories
- Manually write Gherkin scenarios from user stories (Apply)
- Generate JUnit test stubs from scenarios
- Use ChatGPT to create Given/When/Then scenarios (Generate)
- Use ChatGPT/Copilot in VS Code to generate full features (Generate)
- Analyze AI-generated scenarios for edge cases and completeness (Analyze/Evaluate)
- Execute tests using Cucumber and discuss results (Apply/Evaluate)

### Tools / Technologies:
- ChatGPT or GitHub Copilot
- Cucumber with Java/Python
- Gherkin editors (e.g., Pickles, GherkinLint)
- VS Code with BDD extensions | | 4. Assessment | Assessment Methods:
- Mini Project: Students receive user stories and produce Gherkin scenarios, automate them with BDT tools, and evaluate AI-generated content.
- Peer Review: Students critique human-written vs. AI-generated feature files.
- Reflective Quiz: Students reflect on the strengths/weaknesses of AI-generated BDT.


## 4. Assessment 

- Mini Project: Students receive user stories and produce Gherkin scenarios, automate them with BDT tools, and evaluate AI-generated content.
- Peer Review: Students critique human-written vs. AI-generated feature files.
- Reflective Quiz: Students reflect on the strengths/weaknesses of AI-generated BDT.

Constructive Alignment:
- Activities align with learning objectives
- Projects and reflections promote understanding of both BDT concepts and AI involvement

## 5. Lecture Reflection 

 Discussion Prompts:
- Can AI tools fully replace manual BDT writing?
- What risks are associated with blindly trusting AI-generated test cases?

Critical Thinking:
- Examine flawed AI-generated scenarios for incorrect assumptions
- Discuss the need for human oversight

Reflection:
- Reflect on the experience of using AI in BDT – limitations, benefits, and risks


  ## 6. Misc – Resources

  ### Documentation & Tools:
<br> - [Cucumber Docs](https://cucumber.io/docs)
- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=CucumberOpen.cucumber-official)
- [JetBrains Plugin](https://plugins.jetbrains.com/plugin/7212-cucumber-for-java)  - [Cucumber Java Skeleton GitHub](https://github.com/cucumber/cucumber-java-skeleton)
 
      

### Literature & Papers:
-  [Repo @ Leibniz Universität Hannover](https://repo.uni-hannover.de/items/0062c73d-b8bf-47d5-be1e-ebbe2ce4e0b6)
- [Exploring ChatGPT in Test Generation](https://doi.org/10.1109/QRS-C60940.2023.00013)
- [ChatGPT & Software Testing Education: Promises & Perils](https://doi.org/10.1109/ICSTW58534.2023.00078) 
