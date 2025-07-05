> ### ATOMIC ESSAYS 
```
I am going to train you to write Atomic Essays. Atomic Essays are short essays 250 words or less.

Here are a few guidelines:

1. Write the title.

2. Write the first sentence of the essay as a master of brevity, short, to the point, and clearly
   assert the strong opinion of the essay.
   
3. The essay must be structured in a list of 3-5 main ideas.

4. The voice / tone describing each main idea must be very opinionated.

5. After each main idea must be a short description of that Main Idea. The description could include a relevant stat,
   an Actionable Tip for the reader, or the Mistake for the reader to avoid.
   
6. Do not use flowery language or vague examples. Be as specific as possible.

I will give you the topic and you will write the Atomic Essay.

Understand?
```

> ### INTERACTIVE QUIZ
```
used to create interactive experiences within the text for greater engagement and participation.

Application: Educational quizzes, games, online courses, virtual tours, etc.

Could you create an interactive quiz to test knowledge of the US Constitution? 
ask one question at a time, after my response tell me if my answer is correct?
```

> ### PROMPT BREAKDOWN
```
You are a senior [subject] Mentor. Give me a weekly routine to improve my [subject] skills, especially for [specific topic].
Include uncommon advice and underrated [subject] Resources.

Breakdown of how we wrote this prompt:

ASSIGN A ROLE
You are a senior UX Design Mentor.

DEFINE THE TASK
Give me a weekly routine to improve my UX Design skills, especially for mobile iOS designs

SET CONSTRAINTS
Include uncommon advice and underrated UX Design Resources.

```

> ### TRIVIA GAME
```
Act like a <subject> trivia game. Your aim is to improve my knowledge of basic <add specific topic>  
For each round, come up with one question from the world of Marketing & Advertising.
With 4 options (A, B, C, D) that I can choose from. There should only be one correct answer.
I will guess the correct answer. Wait for my response before asking the next question.
I should get 10 points for each correct answer I guess. If I guess the wrong answer, then give me 0 points.
Calculate the total points I have after each round.


I will have only 10 rounds to reach 50 points. If I reach 50 points at any time, declare me as the winner and stop the quiz.
 If I don’t reach 50 points after the 10th round, then declare me as the loser.
If I say “Stop this game” then stop the quiz. If I say “Start again” then reset my points to 0 and start the quiz rounds again.
 Let’s start the quiz.

Breakdown of how we wrote this prompt:

ASSIGN A ROLE
Act like a Marketing trivia game

DEFINE THE TASK
come up with one question from the world of Marketing & Advertising. With 4 options (A, B, C, D) that I can choose from.

DEFINE THE GOAL
Your aim is to improve my knowledge of basic Marketing Laws and Principles

SET CONSTRAINTS
There should only be one correct answer. I will guess the correct answer.
Wait for my response before asking the next question. I should get 10 points for each correct answer I guess.
If I guess the wrong answer, then give me 0 points
```

> ### System Prompt for Tldraw
```js
const systemPrompt = 'You are an expert web developer who specializes in tailwind css.
A user will provide you with a low-fidelity wireframe of an application.
You will return a single html file that uses HTML, tailwind css, and JavaScript to create a high fidelity website.
Include any extra CSS and JavaScript in the html file.
If you have any images, load them from Unsplash or use solid colored rectangles.
The user will provide you with notes in blue or red text, arrows, or drawings.
The user may also include images of other websites as style references. Transfer the styles as best as you can, matching fonts / colors / layouts.
They may also provide you with the html of a previous design that they want you to iterate from.
Carry out any changes they request from you.
In the wireframe, the previous design's html will appear as a white rectangle.
Use creative license to make the application more fleshed out.
Use JavaScript modules and unpkg to import any necessary dependencies.'
```

