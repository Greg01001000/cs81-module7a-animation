### CS 81 Module 7 Assignment 7A: Code Review, by GregH, 7/20/25

#### What part of the code was most confusing and why?

I didn't understand why the animation code ran repeatedly (looped) because I didn't know setInterval() always loops until clearInterval() is called on it. I asked Microsoft Copilot why the code loops, and it explained.

#### How does the animation help visualize asynchronous behavior?
The animation waits at each frame for about half a second, but it doesn't stop the JavaScript interpreter (the browser) from doing other things. The JavaScript program could even do other things while waiting for each interval to finish.

#### What did you change or improve, and what effect did it have?

I added a countdown which displays below the animation. I don't think it had any other effect.