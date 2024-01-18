# Web Debugging and Optimization Exercise

## Overview

This exercise is designed to improve your skills in web debugging and optimization. You will be working with an intentionally flawed web application. Your task is to identify and document the problems in the provided HTML, CSS, and JavaScript files.

## Instructions

Copy this README.md into your Devtools REPO in a new MD file called Day-5.md

### Step 1: Identify Problems

Go through the provided files (`index.html`, `style.css`, and `app.js`). Each file contains several marked problems (indicated by comments like `<!-- Problem 1: -->`, `/* Problem 5: */`, etc.). Your task is to identify what each problem is and why it is an issue.

### Step 2: Document Each Problem

In this README.md file, document each problem. Write a sentence for each problem explaining what the issue is and why it's problematic. Use the format below for your documentation:

#### Problem 1:

- Description: index.html - head: No `<meta name="viewport">` tag in head
  to "optimize your app for mobile screen sizes",
  and "prevent a 300 millisecond delay to user input"(Lighthouse report).

#### Problem 2:

- Description: No "explicit width and height on image elements to reduce layout shifts and improve CLS"
  image height set to auto rather than a value

#### Problem 3:

- Description: Using JQuery for just one line of code "Minimize third party usage"(Lighthouse)

#### Problem 4:

- Description: unnecessary style tag

#### Problem 5:

- Description: !important used unnecessarily

#### Problem 6:

- Description: unused styling classes in stylesheet

#### Problem 7:

- Description: image too large, and height not given explicit value

#### Problem 8:

- Description: unnecessary selector specificity, id selector already sufficient

#### Problem 9:

- Description: Loop running off asynchronous data, may take long to load

#### Problem 10:

- Description: Thread-blocking, unnecessarily long loop

#### Problem 11:

- Description: JQuery usage for one line of code

---

### Step 3: Propose Solutions

For each identified problem, propose a solution or an optimization strategy. Briefly describe how you would fix the issue.

#### Problem 1:

- Solution: Add `<meta name="viewport">` tag in head
  to "optimize your app for mobile screen sizes",
  and "prevent a 300 millisecond delay to user input"(Lighthouse report).

#### Problem 2:

- Solution: set image size smaller with explicit values for height and width,
  possibly with clamp css selector

#### Problem 3:

- Solution: Delete JQuery and write javascript manually

#### Problem 4:

- Solution: Remove style tag and put styles in external stylesheet 'style.css'

#### Problem 5:

- Solution: Remove !important

#### Problem 6:

- Solution: delete unused classes

#### Problem 7:

- Solution: make image smaller, and declare explicit width and height

#### Problem 8:

- Solution: get rid of unnecessary specificity, use just h2 or create and add class styles for h2

#### Problem 9:

- Solution:

#### Problem 10:

- Solution: delete unnecesessary loop

#### Problem 11:

- Solution: Instead of using JQuery, write out the Javascript manually

---

### Step 4: Reflect

After completing the exercise, write a brief reflection on what you learned from this debugging and optimization process. Discuss any new insights you gained and how you might apply these skills in future projects.

Through this assignment, I've seen the importance of best practices for performance and efficiency, and the utility
of Lighthouse, Performance, and Network tabs, to easily measure performance and detect problems in code.

## Submission

Submit this README.md file with all the problems documented and solved, along with your reflection. Ensure that your explanations are clear and concise.

---

This exercise is an opportunity to practice critical web development skills. Pay close attention to detail and think about how each issue affects the overall performance and user experience of the web application.
