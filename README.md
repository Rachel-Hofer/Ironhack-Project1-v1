Technologies Used:
 - HTML5
 - CSS3
 - JavaScript
 - JQuery
 - Bootstrap

Instructions:
 - This game is a trivia game with the added competitive twist of making the setting a job interview
 - The “Interview” is specifically for Web Developers, offering 3 different "positions" (difficulty levels)
    1.  Two highly-qualified candidates will go head to head in an intense round of interview questions asked by the company's CEO
    2.  Each Candidate will be asked 10 questions
    3.  Correct answers = +1 point
    4.  Candidates will alternate turns, regardless of a correct/incorrect answer
    5.  The interview will come to an end after both candidates answer their 10 questions
    6.  The Candidate with the most points will receive a job offer


Challanges:
 - CHALLANGE: Trying to move through the questions while having specific actions happen after each question-
    TRIED:
    1.  for loop - didn’t work
    2.  Prompts - didn’t work
* SOLUTION: creating an increaseQuestion method with a variable for nextIndex

 - CHALLANGE: Alternating player turns and having the points counter recognize each player-
    TRIED:
    1.  Two separate question arrays - didn’t work
* SOLUTION: creating a nested if/else statement, alternating true/false per player after each submission


Future Add-Ons:
 - Responsive Web-Design
 - Add Mid-Level and Senior-Level Questions
 - Add a timer, 10 seconds to answer each question
 - Add a feature to “steal” candidate’s question if answered incorrectly or time limit exceeds with no answer
 - Add a tie-breaker rule, sudden death questions
 - Improve certain UX aspects


Instructor Feedback:
    Successes:
        1. Met all criteria necessary for Game
            -   Winner/Loser
            -   2 Players
            -   Deployed
            -   Can play the full game all the way through
        2. Good balance between design and functionality focus
        3. Good "game plan"/organization of the process
    
    Areas of Opportunity:
        1.  Organize your JS better:
            -   Don't write so much code inside of the logic, instead create functions OR methods/classes for what you want the logic to do, to make logic shorter/more organized/easier to read.
    
    Brainstorming Ideas for Project 2:

    Closet App:
        "store" photos of ever item of clothing in your digital closet
        use it to pick out outfits
        use it to manage your clothing "inventory"
        use it to track when you wear what
        