# 🧠 Quiz Game - Python Terminal  

## 📌 Overview  
This is a **command-line quiz game** built in Python as part of the **Udemy 100 Days of Code course**. The game presents **True/False** questions to the user, keeps track of their score, and provides feedback after each question.

---

## ✨ Features  
✔️ **Loads questions dynamically** from a predefined data file  
✔️ **Uses OOP principles** to separate concerns between `Question`, `QuizBrain`, and `Data`  
✔️ **Tracks the user's score** and provides immediate feedback  
✔️ **Loops until all questions are answered**  

---

## 📜 Example Gameplay  
### **🔹 Input**
Q.1: A slug's blood is green. (True/False): True You got it right! The correct answer was: True Your current score is: 1/1
### **🔹 Final Output**
You've completed the quiz Your final score was 8/12

---

## 🏗️ Project Structure  
- `main.py` - Handles the game flow and initializes the quiz.  
- `data.py` - Stores the list of questions and answers.  
- `question_model.py` - Defines the `Question` class for structuring question objects.  
- `quiz_brain.py` - Manages question progression, user input, and scoring.  

---

## ⏳ Time Taken  
⏱️ Completed as part of the **Udemy Python course**, reinforcing **OOP concepts** and **user input handling**.  

---

## 🚀 How to Run  
1️⃣ **Clone the repo**  
   ```sh
   git clone https://github.com/MattyCoding18/QuizGame.git
```
2️⃣ **Navigate to the project folder**
```sh
cd QuizGame
```
3️⃣ **Run the Python script**
```sh
python main.py
```
