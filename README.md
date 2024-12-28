- Name : SUJAL MALLIKARJUN SHRIGAN
- Company : CODTECH IT SOLUTIONS
- ID : CT08EFW
- Domain :  C PROGRAMMING
- Duration :  DECEMBER TO JANUARY 2025
- Mentor : NEELA SANTHOSH KUMAR

![QUIZ GAME](https://github.com/user-attachments/assets/49aaee25-3773-4634-9959-375a6c45441d)
Overview of the Code :
The provided code is a simple C-based quiz game that presents a series of questions to the user, collects their responses, and evaluates their answers. At the end of the quiz, the user receives feedback on their performance.

Key Features of the Code :
 1. Questions and Options Initialization:
   - The questions, multiple-choice options, and correct answers are pre-defined in arrays.
   - Each question has four options, labeled A, B, C, and D.

 2. Interactive Gameplay:
   - The game displays each question along with its options.
   - The user inputs their choice, which is validated and compared with the correct answer.

 3. Score Calculation:
   - The code tracks the user's score by incrementing it for each correct answer.
   - Feedback is given for each answer (correct or wrong).
 
 4. Final Feedback:
   - After all questions are answered, the user's score is displayed.
   - A final message provides performance-based feedback (Excellent, Good, or Needs Improvement).

Key Activities in the Code:

 1. Initialization:
   - Define the total number of questions (totalQuestions).
   - Create arrays to store the questions, their options, and the correct answers.

 2. Question Display and User Interaction:
   - Use a loop to iterate through the list of questions.
   - Call the displayQuestion function to display the question and its options.

 3. User Input Handling:
   - Prompt the user to input their answer.
   - Convert the answer to uppercase using toupper() for case-insensitive matching.
   - Compare the input with the correct answer and update the score.

  4. Feedback for Each Answer:
    - Provide feedback for each question immediately after the user responds.
    - Display whether the answer was correct or incorrect, and reveal the correct answer for incorrect attempts.

  5. Final Score and Feedback:
    - Display the total score at the end of the quiz.
    - Provide feedback based on the score:
      A) All correct: "Excellent!"
      B) More than half correct: "Good job!"
      C) Less than half: "Improvement needed."

  6. Function for Question Display:
    - The displayQuestion function prints the question and its corresponding options.
    - It ensures the questions are presented in a readable format.
