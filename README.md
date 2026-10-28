# EX-02: Cross-Platform Prompting – Evaluating Diverse Prompt Engineering Techniques in AI-Powered Code Generation

## Name:GOLLA MOULIDHAR
## Reg No:212223240042

---

# AIM

To evaluate and compare the effectiveness of different prompting techniques (Basic Prompt, Role Prompt, Context Prompt, Constraint Prompt, and Output Format Prompt) across AI platforms such as ChatGPT, Gemini, Claude AI, and Microsoft Copilot for the task of code generation.

---

# Scenario

You are a software developer creating a **Student Management System** using Python. The objective is to generate clean, readable, and efficient code for performing student record management. Different prompting techniques are used to determine which AI platform provides the best programming assistance.

The evaluation is based on:

- Accuracy
- Code Quality
- Readability
- Speed
- User Experience

---

# Algorithm

## Step 1: Select the Application

Choose a programming task.

**Selected Task:** Student Management System in Python

The program should:

- Add student details
- Display student records
- Search student details
- Update student information
- Delete student records

---

## Step 2: Choose AI Platforms

The following AI tools were selected:

- ChatGPT
- Google Gemini
- Claude AI
- Microsoft Copilot

---

## Step 3: Prepare Prompting Techniques

### A. Basic Prompt

The AI is directly asked to generate the code.

**Prompt:**

> Write a Python program for a Student Management System.

---

### B. Role Prompt

The AI is assigned a role.

**Prompt:**

> Act as an experienced Python developer and create a Student Management System using Python with proper comments.

---

### C. Context Prompt

Additional background information is provided.

**Prompt:**

> The Student Management System is designed for first-year engineering students. It should allow users to add, search, update, delete, and display student records using Python.

---

### D. Constraint Prompt

Specific requirements are given.

**Prompt:**

> Generate the Python code using functions only. Keep the program under 100 lines, use simple variable names, and avoid external libraries.

---

### E. Output Format Prompt

The required output format is specified.

**Prompt:**

> Generate the solution with the following sections:
> - Program Title
> - Python Code
> - Sample Input
> - Sample Output
> - Explanation

---

## Step 4: Generate Responses

The same programming task was given to each AI platform using different prompting techniques.

The generated programs were collected and compared.

---

## Step 5: Organize Results

The generated outputs were evaluated based on:

- Accuracy
- Code Quality
- Readability
- Speed
- User Experience

---

# Result

## ChatGPT + Basic Prompt

### Prompt Used

> Write a Python program for a Student Management System.

### Observation

Generated a complete menu-driven program with proper logic and easy-to-understand code.

### Evaluation

- Accuracy: Excellent
- Code Quality: Excellent
- Readability: Excellent
- Speed: Very Fast
- User Experience: Excellent

---

## Gemini + Context Prompt

### Prompt Used

> The Student Management System is designed for first-year engineering students. Generate a Python program with add, search, update, delete, and display operations.

### Observation

Produced a well-structured solution with detailed implementation and good explanations.

### Evaluation

- Accuracy: Very High
- Code Quality: Very Good
- Readability: Good
- Speed: Fast
- User Experience: Very Good

---

## Claude AI + Constraint Prompt

### Prompt Used

> Generate the Python code using functions only. Keep the program under 100 lines and avoid external libraries.

### Observation

Produced optimized, modular, and clean code while following all constraints.

### Evaluation

- Accuracy: Excellent
- Code Quality: Excellent
- Readability: Very Good
- Speed: Moderate
- User Experience: Excellent

---

## Microsoft Copilot + Role Prompt

### Prompt Used

> Act as an experienced Python developer and create a Student Management System with proper comments.

### Observation

Generated beginner-friendly code with clear comments and good documentation.

### Evaluation

- Accuracy: Good
- Code Quality: Good
- Readability: Excellent
- Speed: Fast
- User Experience: Good

---

# Comparison Table

| Platform | Prompting Technique | Accuracy | Code Quality | Readability | Speed | User Experience |
|----------|---------------------|----------|--------------|-------------|-------|-----------------|
| ChatGPT | Basic Prompt | Excellent | Excellent | Excellent | Very Fast | Excellent |
| Gemini | Context Prompt | Very High | Very Good | Good | Fast | Very Good |
| Claude AI | Constraint Prompt | Excellent | Excellent | Very Good | Moderate | Excellent |
| Microsoft Copilot | Role Prompt | Good | Good | Excellent | Fast | Good |

---

# Final Result

The experiment demonstrated that different prompting techniques significantly influence the quality of AI-generated code.

- **ChatGPT + Basic Prompt** generated the most balanced and beginner-friendly solution with excellent readability and speed.
- **Gemini + Context Prompt** produced well-structured code with detailed explanations.
- **Claude AI + Constraint Prompt** generated the most optimized and modular code while strictly following the given constraints.
- **Microsoft Copilot + Role Prompt** created well-commented code suitable for beginners.

Overall, **ChatGPT with the Basic Prompt** was identified as the most suitable combination for educational programming tasks because it produced accurate, readable, and fast results.
