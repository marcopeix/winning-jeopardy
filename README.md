# Winning Jeopardy

This project revolves around the TV show "Jeopardy". For the analysis, a dataset containing questions and answers was used, and it can be found [here](https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/).

The dataset contains the following 7 columns:
* `Show Number` - The Jeopardy show number where the question was asked
* `Air Date` - The date the episode aired
* `Round` - The round at which the question was asked
* `Category` - The category of the question
* `Value` - The money prize for answering the question correctly
* `Question` - The question
* `Answer` - The right answer to the question

**Objective:** The objective of this project is to determine if it is possible to win Jeopardy by learning the previous questions. 

**Techniques used:**
* Pandas, regular expressions, numpy
* Scipy.stats, chi squared test
