# -KNOWLEDGE-GAP-DETECTOR
# 🧠 Knowledge Gap Detector Using NLP

## 📌 Project Description

**Knowledge Gap Detector** is a Natural Language Processing (NLP) application that analyzes a student's answer and identifies important concepts that may be missing.

The application compares the student's answer with a predefined knowledge base and generates:

* Concepts understood
* Missing concepts
* Knowledge coverage percentage
* Understanding level
* Suggested study topics

---

## 🎯 Objective

The main objective of this project is to help students identify areas where they need more learning or revision.

Instead of only checking whether an answer is correct or incorrect, the application tries to identify **which concepts the student has covered and which concepts are missing**.

---

## 🔄 Working Process

```text
Student enters topic
        ↓
Student enters answer
        ↓
Text preprocessing
        ↓
Concept detection
        ↓
Compare with knowledge base
        ↓
Find missing concepts
        ↓
Calculate concept coverage
        ↓
Predict understanding level
        ↓
Generate study plan
```

---

## ✨ Features

* 📝 Student answer input
* 📚 Topic selection
* 🧠 Concept detection
* 🔍 Knowledge gap identification
* 📊 Concept coverage percentage
* 🎯 Understanding-level prediction
* 📖 Suggested study plan
* 🌐 Interactive Gradio interface
* ☁️ Google Colab support

---

## 📚 Available Topics

The current application supports these demo topics:

```text
🐍 Python
🌐 HTML
🎨 CSS
🌐 Computer Networks
🤖 Machine Learning
💬 Natural Language Processing
```

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Gradio
* Regular Expressions

### Platform

* Google Colab

### Domain

* Natural Language Processing
* Text and Speech Analysis
* Educational Technology

---

## 🧠 How It Works

The application contains a predefined knowledge base for different subjects.

For example, the Python knowledge base contains concepts such as:

```text
Variables
Data Types
Conditional Statements
Loops
Functions
Lists
Dictionaries
Classes
Exceptions
```

When a student provides an answer, the application checks which of these concepts are present.

The concepts that are not detected are shown as possible **knowledge gaps**.

---

## 🧪 Example

### Input

**Topic:**

```text
Python
```

**Student Answer:**

```text
Python has variables, data types, loops and functions.
Lists are used to store multiple values.
```

### Output

```text
🧠 KNOWLEDGE GAP ANALYSIS

📚 Topic:
Python

🎯 Understanding Level:
🟡 PARTIAL UNDERSTANDING

📊 Concept Coverage:
55.6%

✅ Concepts Detected:
• Variables
• Data Types
• Loops
• Functions
• Lists

❌ Possible Knowledge Gaps:
• Conditional Statements
• Dictionaries
• Classes
• Exceptions
```

### Suggested Study Plan

```text
1. Study: Conditional Statements
2. Study: Dictionaries
3. Study: Classes
4. Study: Exceptions
```

---

## 🚀 How to Run in Google Colab

### Step 1

Open Google Colab.

### Step 2

Create a new notebook.

### Step 3

Copy the complete Python code into one cell.

### Step 4

Run the cell.

### Step 5

Wait for the required library to install.

### Step 6

A Gradio web application will appear.

### Step 7

Enter a topic such as:

```text
Python
```

### Step 8

Enter the student's answer.

### Step 9

Click:

```text
🔍 Detect Knowledge Gaps
```

### Step 10

The application displays the detected concepts, missing concepts, coverage percentage, and suggested study plan.

---

## 📁 Project Structure

```text
Knowledge-Gap-Detector/
│
├── knowledge_gap_detector.py
└── README.md
```

---
<img width="935" height="486" alt="Screenshot 2026-10-04 152606" src="https://github.com/user-attachments/assets/92ac07ca-854e-4d9a-8dc4-210d9e6ce59d" />



<img width="929" height="419" alt="Screenshot 2026-10-04 152654" src="https://github.com/user-attachments/assets/ad2331a6-a92f-4da8-8cb2-45afdd2538b8" />


