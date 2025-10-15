# 🧠 CS50 Trivia
This project is a simple interactive quiz built for **Harvard’s CS50x Problem Set 8: Trivia**. It uses HTML, CSS, and JavaScript to test users’ knowledge and provide instant feedback. The app includes multiple-choice and free-response questions, demonstrating basic DOM manipulation and event handling in JavaScript. <br>

Example:
![image alt](https://cs50.harvard.edu/x/psets/8/trivia/questions.png)

## Overview
The game presents two trivia challenges: one multiple-choice question and one free-response question. When users select or type an answer, the page reacts instantly by changing colors and displaying “Correct” or “Incorrect” messages.

## Files
- **index.html** – Contains the structure, content, and JavaScript logic for the quiz.
- **styles.css** – Defines layout, color, fonts, and hover effects.

## How It Works
When a user clicks a button on the multiple-choice question (“What is the capital of The USA?”), the `checkCapital()` function checks if the clicked option equals “Washington D.C.”. If correct, the button background turns green and displays “Correct.” Otherwise, it turns red and displays “Incorrect.”  
For the free-response question (“What would Superman do?”), the `checkSuper()` function verifies if the input text equals “fly.” If correct, the background becomes green with the word “Correct”; otherwise, red with “Incorrect.”

## Key Concepts
- DOM manipulation using `document.getElementById()` and `innerText`
- Conditional logic with if/else statements
- Event handling with `onclick` attributes
- CSS transitions and hover effects for better UX
- Input validation using JavaScript

## Example Interaction
**Multiple Choice:**  
Q: What is the capital of The USA?  
A: Washington D.C. → ✅ Correct!  
**Free Response:**  
Q: What would Superman do?  
A: fly → ✅ Correct!

## How to Run
1. Clone or download this repository.  
2. Open `index.html` in your browser.  
No server or setup required — it runs locally.

## Styling
The UI uses a clean blue theme (`#477bff`) with white backgrounds and the **Montserrat** Google Font for a modern, minimal design. Buttons and input fields have hover and transition effects that highlight interactivity.

## Author
**Cayden Garrett**  
Built as part of CS50x 2025 — Problem Set 8: Trivia  
[CS50 Website](https://cs50.harvard.edu/x)

## License
This project is intended for educational use under CS50’s Academic Honesty policy. You’re free to experiment and modify it for personal learning.
