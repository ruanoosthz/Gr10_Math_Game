# 60 Second Scatter

## Task - 1a

I want to design an educational game where the user can test and improve their mathematical skills by completing various multiplication sums.

The sums will be generated randomly, and the user will then have to enter the correct answer to achieve a better score. If the user gets an answer wrong, the score will decrease, and this will determine how well the user performs. The user will only have 60 seconds to answer the questions.

**What will appear on the GUI while it is being used?**

- The instructions will be provided on the first 'tabsheet'.
- The user will be able to choose an avatar from several options on the second 'tabsheet'.
- A screen where the game will be played is on the last 'tabsheet'.
- While the user plays the game, their score and how much time they have left will be displayed.
- An end screen that shows how the user performed by showing how many questions the user answered correctly and how many questions the user answered incorrectly, as well as what achievement they obtained.
<img width="686" height="817" alt="image" src="https://github.com/user-attachments/assets/989e8280-2514-4539-b048-f0236f33e4ad" />


## Task - 1b

| As a (User) | I want to (play an educational maths game) | So that I can (improve at doing quick calculations). |
|-------------|---------------------------------------------|-------------------------------------------------------|
| User        | play an educational maths game              | improve at doing quick calculations.                  |

---


## Acceptance Test

- The system will ask the user which avatar they want to be.
- The system will use the avatar to show whether the question was answered correctly or incorrectly.
- The system will start a timer.
- The system will randomly generate a multiplication sum.
- The system will check the answer.
- The system will display the user's time and score during and after the game has finished.

---


## Input, Processing, Output (IPO)

### Input Validation and Output Formatting

| Input Validation | Output Formatting |
|------------------|--------------------|
| 1 – The program will not let the game start without the user having chosen an avatar | 1 – `Avatar.Visible` |
| 3 – Answer must be a string or integer depending on the question | 2 – `inputbox('Question + IntToStr(nr)' + '<Question>' + ' ');` |

### IPO Table

| Input | Processing | Output |
|-------|------------|--------|
| 1. User chooses avatar. | Set 'avatar' as the symbol the user has chosen. | Display avatar on the game screen. |
| 2. User presses 'Lock In' button. | Randomly generate a question and format it according to an input box. | The question is displayed on the screen via an input box. |
| 3. User answers the question by entering the answer into the input box. | The answer is checked to see if it is correct. | Display score in the 'score' area. |

---

*Can you achieve the top performance?*

~ Ruan Oosthuizen
