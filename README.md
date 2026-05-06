# Module 2 – Thinking Like A Programmer
## Component 4: Programming & HTML Basics — Summative Assessment

> **Occupational Certificate: Software Development**
> This assessment is aligned with the QCTO requirements and is focused on preparing the student for the EISA exam.

---

| | |
|---|---|
| **Student Name** |Pfarelo Judith Monyeleote |
| **Student/ID Number** |9501030956088 |
| **Date** | 5 May 2026 |
| **Assessor** | |
| **Assessor Date** | |
| **Signature** | |

---

## ⚠️ Important

- You have **2 hours and 30 minutes** to complete this assessment.
- You are **NOT allowed to use AI or Google**. If we suspect that you have used AI or external help, you will be considered **not competent** for this assessment.

---

## Scenario

You are employed as a junior web developer at a software company. Your manager has asked you to finish a basic webpage that will be used to display student assessment results. Another developer started the project but left the HTML incomplete and wrote incorrect pseudocode for the result-checking logic.

**You are required to:**
- Complete the website using HTML
- Correct the logical errors in the provided pseudocode

---

## Section A: HTML Development — [56 Marks]

In the VS Code terminal, clone the following repository using HTTPS or SSH:

```
tpc-student-system/
├── index.html
├── css/
│   └── style.css
└── images/
    └── logo.png
```

The file `index.html` is incomplete.

### Question 1: In VS Code, complete the HTML structure (56 marks)

**1. Format the structure in `index.html` by:** *(10 Marks)*

- a. Add a closing tag to the `head` element. *(2 Marks)*
- b. Complete the charset value in the head meta tag. *(2 Marks)*
- c. Add a closing tag to the `body` element. *(2 Marks)*
- d. Add a closing tag to the `h1` element in the body. *(2 Marks)*
- e. Add a closing tag to the `html` element. *(2 Marks)*

**2.** Add the page title in the `head` element. *(5 Marks)*

**3.** In the `<head>` section, add the title: `Student Results Portal` *(4 Marks)*

**4.** In the `header` element of the body, add: *(10 Marks)*
- a. A main heading: `Student Results Portal` *(5 Marks)*
- b. Attach the image `logo.png` in the `img` element of the header element. *(5 Marks)*

**5.** Create the main content section. Using a semantic `<main>` tag, add the following: *(16 Marks)*
- a. A paragraph explaining that the page shows student result information. *(4 Marks)*
- b. A subheading: `Assessment Result` *(4 Marks)*
- c. A paragraph showing an example student name.
- d. A paragraph showing an example score. *(4 Marks)*
- e. A paragraph showing an example result such as `Pass` or `Fail`. *(4 Marks)*

**6.** Create the footer section. Using a semantic `<footer>` tag, add a simple footer message such as: `TPC Student System` *(5 Marks)*

**7.** Link assets correctly: *(10 Marks)*
- a. Link the stylesheet correctly to `css/style.css` *(5 Marks)*
- b. Link the image correctly to `images/logo.png` *(5 Marks)*

**8.** In the VS Code terminal, submit your work by pushing the repository to the `main` branch, then paste the link in your answer block.

---

## Section B: Pseudocode Debugging — [30 Marks]

The pseudocode below is meant to determine whether a student has passed or failed based on their assessment mark.

### Given Incorrect Pseudocode

```
START
INPUT studentName
INPUT
IF score  
   OUTPUT "Student Name: " + studentName
   OUTPUT "Result: Pass"
ELSE
   OUTPUT "Student Name: " + studentName
   OUTPUT "Result: Fail"
START
OUTPUT "Thank you for using the portal"
END
```

### Question 1 *(5 Marks)*

In the VS Code terminal, create a `fixed.txt` file in the cloned repository. *(5 Marks)*

### Question 2: Rewrite the pseudocode correctly in `fixed.txt` *(25 Marks)*

Rewrite the pseudocode so that:

- a. The pseudocode correctly checks whether the student passed or failed. *(5 Marks)*
- b. The pseudocode outputs the student name. *(5 Marks)*
- c. The pseudocode outputs the student result. *(5 Marks)*
- d. The pseudocode ends correctly. *(5 Marks)*
- e. The pseudocode has the correct structure. *(5 Marks)*
