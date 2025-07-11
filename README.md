# Kotlin Guess The Number 🎮

A simple **Guess The Number** game written in **Kotlin**, plus a tiny unit test to check the core logic.

---

## 📌 What does it do?

- The program randomly picks a number between **1 and 100**.
- The player keeps guessing until they get it right.
- After each guess, the game tells the player if their guess is **Too low**, **Too high**, or **Correct!**

---

## 🧩 How does it work?

- **Main.kt:** This is the main game loop.
- **MainTest.kt:** A small unit test to verify the `checkGuess` function works correctly.

---

## 🗂️ Project structure


---

## ⚙️ How to run the game

1️⃣ **Open terminal / PowerShell**

2️⃣ Navigate to the project folder:

```bash

cd "C:\Users\Joel Ndiba Mwaura\OneDrive\Desktop\KotlinGuessTheNumber"
Compile the game:

kotlinc src/main/kotlin/Main.kt -include-runtime -d Main.jar

4️⃣ Run the game:

java -jar Main.jar

🧪 How to run the test

```bash

kotlinc src/MainTest.kt -include-runtime -d MainTest.jar
java -jar MainTest.jar