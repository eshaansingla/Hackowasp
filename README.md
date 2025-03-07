
## Motivation
The cost of healthcare has been on the rise in this day and age, and your health has been the most valuable asset you own. Eating healthy and having a good sleep schedule is effective for preventing illness, but as people get busier, it has become more difficult to maintain your health. That is why it is essential for people to take dietary supplements. But how do people know what the best supplements are for them? They can ask a doctor, but the doctor might miss some information and excluding procedures or tests.

## What it does
Vital uses users' personal physical information including their age, gender, allergies, and a text input where they write how they specifically want to improve their health. After entering those information, the users' information will be used to generate a list of the top recommended dietary supplement to take. This will help users save time, money, and confusion from spending time searching for which supplements to buy. The user will be able to enter new information to get supplement recommendations for different reasons and conditions.

## How we built it
We built Vital using the MERN stack, and sentiment analysis models for our ML. After the user enters their personal information, those data are used to generate recommendations. To give examples, if there are users filling out the form for a child under 6 years old who's allergic to peanuts, our model will avoid any supplements that are pills and contain peanuts. For the free response, if the use inputs "I want to have better skin", then our model will assess that sentence and recommend supplements that are useful for the skin.
