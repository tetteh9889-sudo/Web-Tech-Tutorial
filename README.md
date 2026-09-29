# HTML Lab Assignment: User Registration Form

## Objective
In this assignment, you will learn how to build a structured **User Registration Form** using semantic HTML form elements, input validation attributes, and appropriate form controls.

---

## Instructions
1. Clone this repository or click **"Use this template"** to create your own repository.
2. Open `index.html` in your code editor (e.g., VS Code).
3. Read through the starter code provided in `index.html`.
4. Identify and fix any HTML structural or attribute bugs present in the starter code (pay close attention to form label accessibility).
5. Complete the tasks listed below to finish the form.
6. Commit and push your changes to GitHub before the deadline.

---

## Starter Code Overview
The provided starter code sets up a basic registration form containing:
- Text inputs for **Name**, **Email**, and **Password**
- Radio buttons for selecting **Gender**
- Checkboxes for selecting **Interests**
- A **Submit** button

---

## Questions & Tasks

### Task 1: Fix Accessibility Bugs (Labels & Attributes)
Review the starter code in `index.html` and fix the following issues:
1. **Radio Buttons:** Correct the `for` attributes on the `<label>` tags for the Male and Female radio buttons so clicking the label text selects the corresponding radio button.
2. **Checkboxes:** Correct the `for` attributes on the `<label>` tags for the Sports, Music, and Reading checkboxes so they properly link to their matching `id` attributes.

---

### Task 2: Enhance Form Controls & Validation
Add or modify attributes in `index.html` to complete the following requirements:
1. **Country Selection:** Add a `<select>` dropdown field named `country` after the Interests section with options for at least three countries (e.g., Ghana, Nigeria, Kenya).
2. **Age Input:** Add a number input field (`type="number"`) for **Age** that restricts values between **18** and **100**.
3. **Terms & Conditions:** Add a single checkbox at the bottom that requires users to check **"I agree to the Terms and Conditions"** before submitting the form.

---

### Task 3: Conceptual Questions
Answer the following questions by typing your responses below each question:

1. **What is the purpose of the `name` attribute on input elements, and why is it essential when a form is submitted?**
   > *Your answer here:*

2. **Why must all radio buttons in a group share the same `name` attribute?**
   > *Your answer here:*

3. **What is the functional difference between the `id` attribute and the `name` attribute in an HTML `<input>` tag?**
   > *Your answer here:*

---

## How to Submit
1. Save your changes to `index.html` and `README.md`.
2. Commit your work:
   ```bash
   git add .
   git commit -m "Completed registration form assignment"
   git push origin main
