# Answer Evaluation System
This is a simple Answer Evaluation System built using Python's Tkinter library for the user interface, difflib for similarity comparison, and Pillow for handling images. The project was developed as part of a second-year mini project.

### Table of Contents
- Project Overview
- Technologies Used
- Features
- Screenshots
## Project Overview
The Answer Evaluation System is a desktop application that allows teachers to input their answers and keywords for a question. Students can utilize Google Lens to capture handwritten answers and paste them into the application. The system then compares the student's answer with the teacher's answer using a similarity algorithm. Marks are awarded based on how closely the student's answer matches the teacher's answer and whether the provided keyword is present.

## Technologies Used
- Python: Core programming language.
- Tkinter: For building the graphical user interface (GUI).
- difflib (SequenceMatcher): For evaluating the similarity between teacher's and student's answers.
- Pillow (PIL): For handling and displaying images in the GUI.

## Features
* Teacher's Section:
Allows input of a question, correct answer, and a keyword.
* Student's Section:

Allows students to use Google Lens to capture handwritten answers and input them into the application.
## Evaluation:

Uses a similarity algorithm to compare teacher's and student's answers.
Checks for the presence of a keyword in the student's answer.
Awards marks based on similarity percentage and keyword presence.
