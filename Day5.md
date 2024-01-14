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

- Description:

#### Problem 4:

- Description: unnecessary style tag

#### Problem 5:

- Description: No previous styling needing !important to overwrite

#### Problem 6:

- Description: unused styling classes in stylesheet

#### Problem 7:

- Description: unnecessary selector specificity, id selector already sufficient

#### Problem 8:

- Description: unnecessary selector specificity, id selector already sufficient

---

### Step 3: Propose Solutions

For each identified problem, propose a solution or an optimization strategy. Briefly describe how you would fix the issue.

#### Problem 1:

- Solution: Add `<meta name="viewport">` tag in head
  to "optimize your app for mobile screen sizes",
  and "prevent a 300 millisecond delay to user input"(Lighthouse report).

#### Problem 2:

- Solution: set image height and width with explicit values,
  possibly with clamp css selector

#### Problem 3:

- Solution:

#### Problem 4:

- Solution: Remove style tag and put styles in external stylesheet 'style.css'

#### Problem 5:

- Solution: Remove !important

#### Problem 6:

- Solution: delete unused classes

#### Problem 7:

- Solution: simply use the # and id name

#### Problem 7:

- Solution: simply use the # and id name

#### Problem 8:

- Solution:

#### Problem 9:

- Solution:

#### Problem 10:

- Solution:

#### Problem 11:

- Solution:

---

### Step 4: Reflect

After completing the exercise, write a brief reflection on what you learned from this debugging and optimization process. Discuss any new insights you gained and how you might apply these skills in future projects.

## Submission

Submit this README.md file with all the problems documented and solved, along with your reflection. Ensure that your explanations are clear and concise.

---

This exercise is an opportunity to practice critical web development skills. Pay close attention to detail and think about how each issue affects the overall performance and user experience of the web application.
