# **TriviaGame.io**

## Pseudocode

    <HTML & CSS>
* Getting the grid setup for the question with answers in a table format.
    ( My questions have the answer 4 times, I just wanted to how it would look with all the fields filled in before I went through to make all my changes.)

* Added my logo in the navbar section becuase I knew navbar by defualt          would be to stay on top.

* I used bootstrap for my grid layout functional from phone up to computer      screen sizes.

* Created my button at the bottom to submit my form.

    <JavaScript>
* On page load start the timer to answer questions.

* setup an .on(click, function) to activate when the user was done.

* Inside that function take in my const variables for correct answers,          checking questions.  Keeping a tally of correct answers, wrong              answers and questions not answered.

* Once form sent compare answers to correct ones and return on how the user did ( How many correct, How many incorrect and How many not answered).

* Once that info was viewed and they clicked ok have the form clear and start over.