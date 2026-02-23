# 📘 Probability Project – Expectation Decider

## 📌 Project Title
**Expectation Decider Using Probability & Bayes’ Theorem**

---

## 🎯 Objective

This project analyzes student performance using fundamental probability concepts.  
It applies statistical reasoning to understand how factors like attendance and group discussion influence final exam results.

The project covers:

- Empirical Probability  
- Joint Probability  
- Conditional Probability  
- Independence of Events  
- Bayes’ Theorem  

---

## 📊 Dataset Description

The dataset represents student academic performance and includes the following variables:

- `study_hours` – Number of study hours per week  
- `attendance` – Attendance percentage  
- `group_discussion` – Participation in group discussion (Yes/No)  
- `previous_test_score` – Previous internal test marks  
- `final_exam_pass` – Final exam result (Pass/Fail)  

The dataset is generated using Python for analysis purposes.

---

## 🧮 Concepts Implemented

### 1️⃣ Empirical Probability

Empirical probability is calculated using actual observed data.

Formula:

P(A) = (Number of favorable outcomes) / (Total number of outcomes)

Example:
Probability that a randomly selected student participated in group discussion.

---

### 2️⃣ Joint Probability

Joint probability measures the probability of two events occurring together.

Formula:

P(A ∩ B)

Example:
Probability that a student:
- Participated in group discussion  
AND  
- Passed the final exam  

---

### 3️⃣ Conditional Probability

Conditional probability calculates the probability of an event given that another event has already occurred.

Formula:

P(A | B) = P(A ∩ B) / P(B)

Example:
Probability that a student passed given that they participated in discussion:

P(Pass | Discussion)

---

### 4️⃣ Independence of Events

Two events are independent if:

P(A ∩ B) = P(A) × P(B)

If knowing one event changes the probability of another event, the events are dependent.

In this project, participation and passing are found to be dependent events.

---

### 5️⃣ Bayes’ Theorem

Bayes’ theorem is used to reverse conditional probability.

Formula:

P(A | B) = (P(B | A) × P(A)) / P(B)

Example:
Probability that a student passed given that they had high attendance:

P(Pass | High Attendance)

This helps determine how attendance influences exam success.

---

## 📈 Key Observations

- Higher attendance increases the probability of passing.
- Students participating in group discussions have a higher success rate.
- Attendance and final results are dependent events.
- Bayes’ theorem confirms that high attendance significantly increases pass probability.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Basic Probability Mathematics

---

## 📚 Theoretical Questions

Some theoretical explanations are written separately in the notebook and include:

- Definitions of probability concepts
- Interpretation of results
- Difference between independent and dependent events
- Explanation of Bayes’ theorem in simple terms

---

## 🚀 How to Run the Project

1. Open the notebook in Jupyter Notebook or VS Code.
2. Run all cells sequentially.
3. Observe calculated probabilities and interpretations.

---

## 🎓 Learning Outcomes

After completing this project, you will understand:

- How to compute empirical, joint, and conditional probabilities.
- The difference between theoretical and empirical probability.
- How to test independence of events.
- How to apply Bayes’ theorem in real-world scenarios.
- How probability can be used to analyze academic performance.

---

## 📌 Conclusion

This project demonstrates how probability theory can be applied to real-world datasets to make meaningful decisions.  
Using statistical reasoning, we conclude that attendance and participation positively influence exam performance.

---
