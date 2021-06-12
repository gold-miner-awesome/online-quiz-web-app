# Online Quiz Exam Web App

This project is for online exam with quizzes by using PHP/MySQL, HTML, CSS, Bootstrap v3.3.7, Responsive, JQuery and plugins, and Drag & Drop.

## Overview

- Quiz Type: timed and untimed
- Question Type: SEQ(Ranking), MR(Selection), MC(Ratings)
- Quiz Kind: Ranking, Selection, Ratings, Minimock(combined with Ranking, Selection and Ratings, less than 50 questions), Mock(More than 50 questions)

## Features:

### [Admin](http://quiz-app.groundforcetrucking.com/admin "Demo admin link")

- Log In

![](screenshots/screenshot_admin_login.png "admin login")
![](screenshots/screenshot_admin.png "admin main page")

- Import quizzes & questions from excel file

![](screenshots/screenshot_admin_import.png "admin import quizzes and questions")

- Manage quiz and question

![](screenshots/screenshot_admin_quiz_list.png "admin quiz list")
![](screenshots/screenshot_admin_quiz_edit.png "admin quiz edit")
![](screenshots/screenshot_admin_question_list.png "admin question list")
![](screenshots/screenshot_admin_question_edit.png "admin questions edit")

- Evaluation Setting
![](screenshots/screenshot_admin_eval.png "admin evaluation")

### [Student](http://quiz-app.groundforcetrucking.com/ "Demo student link")

- Select quiz exam(Ranking, Selection, Ratings, Minimock, Mock)
- Load exam from saved
- Auto-save exam
- Drag & Drop(SEQ questions) and Multi-select(MR question), and Chice(MC question)
- Timeout exam(only timed quiz exam)
- Choose any question in progress exam
- Check answer in progress exam(only Ranking, Selection, Ratings quiz exam)
- Submit all answers and Evaluate exam
- Review your answers after evaluation