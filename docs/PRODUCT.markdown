Product Documentation
=====================

This part of documentation covers product definition, this should can explain various features of Arlin. As we're making an actual app that potentially could be used and very useful by a lot of people, we're putting this beyond just a project; a product. This relates to <https://github.com/gunadarma-academy/asde-michi/issues/14>.

As mentioned in the beginning, Arlin (Arah lalu lintas) is a community-driven transportation helper for anyone in the city/town. Arlin is designed as a question-answer forum that is simple and clear. Since there's a similar app or platform our there, like Haaash and Stack Overflow, we should learn from them first.

Features
--------

### Basically Important

(Relate to <https://github.com/gunadarma-academy/asde-michi/issues/9>)

1. New visitor can set their username simply when landing in the app. The app have a _set username_ box and its log in button in the homepage. Then the visitor become a user. Later on, we will implement a proper sign up system with social sign in or even email.
   - The visitor is able to CREATE a user with username.
   - The user is able to READ their own username.
   - The visitor/user is able to READ other user's username.
2. The visitor/user who has a username, can post a question by clicking the _Post a Question_ button, type their question's title and description in the question box, and then click _Submit_.
   - The user is able to CREATE a question with its title and description.
   - The user is able to READ their own question.
   - (if possible) The user is able to UPDATE their own question.
   - (if possible) The user is able to DELETE their own question.
3. The visitor/user who has a username, can see a list of questions.
   - The visitor/user is able to READ a list of questions.
4. The visitor/user who has a username, can answer a question below the question frame by either:
   - The user is able to CREATE an answer to a desired question.
     - Clicking the _Answer_ button, type the answer, and then click _Submit_.
     - (or might even) Just type the answer in the answer box, then just hit _Enter_.
   - The visitor/user is able to READ some answers to a desired question.

### Must Have

1. The user with their corresponding question should be able to accept answers with a _Verify_ button should they actually prove the reliabity of the answer firsthand. 
2. Every user should be able to either upvote or downvote each of the answer from a question if they have their own experience on it, or if they believe the answer is correct. The vote would either make the user who anwers gain credibility among the users.
3. (Optional) Every user should be able to make a list of Favorite questions so that they can find them quickly without having to bookmark or manually search for them. 
4. (Optional) Every user should have their own profile with sets of other features such as:
   - The user should be able to see lists of their own questions.
   - The user should be able to see lists of their own answers.
   - The user should be able to see lists of their favorite questions.
   - The user should be able to see the voting statistics.
   - The user should be able to modify their profile information.

Success Criteria
----------------

### User Acceptance Testing

The overall results from the user acceptance test that obtained from the online questionnaire are shown in the table below.

![data-analysis-uat](https://cloud.githubusercontent.com/assets/17141470/14813423/cffe8b00-0bcb-11e6-9106-b88ff0527880.png)

The result are: 
- 19.5% for the very agree answer (scale 5),
- 53.9% for the agree answer (scale 4),
- 18.9% for the neutral answer (scale 3),
- 6.4% for the disagree answer  (scale 2), and
- 1.3% for the very disagree answer (scale 1)

After we combine the percentage, the result are shown in the table below.

![data-result](https://cloud.githubusercontent.com/assets/17141470/14813422/cffdf0a0-0bcb-11e6-8ea5-3f7ec7076d1c.png)

The average percentages for all questions are
- 74.15% for the good variable (scale 4 + scale 5),
- 18.18% for the neutral variable (scale 3), and 
- 7.67% for the not-good variable (scale 1 + scale 2)

Based on the UAT result, with the successful percentage **74.15%**, it can be concluded that Arlin website has been acceptance by the user, in terms of **user interface**, **content**, **ease of use**, and **usability**. We have decided the minimum percentage target for this test, which was **70%**. However, despite the accomplishment has been obtained, Arlin website must still be developed.
