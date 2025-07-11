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
 # How does it work?
    • Main.kt: This is the main game loop.
    • MainTest.kt: A small unit test to verify the checkGuess function works correctly.

🗂️ Project structure
# TESTING THE CODES (Main.kt and MainTest.kt)

How to fix it — do this exactly:

1️⃣ Make sure you’re still in the folder:

powershell
Copy

cd "C:\Users\Joel Ndiba Mwaura\OneDrive\Desktop\KotlinGuessTheNumber"

2️⃣ Confirm the .jar really exists:

powershell
Copy

dir

Look for Main.jar in the list.

3️⃣ Run it exactly like this:

powershell
Copy

java -jar Main.jar

# MainTest.kt

kotlinc src/MainTest.kt -include-runtime -d MainTest.jar
java -jar MainTest.jar
