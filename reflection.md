# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
  The game looked to be fully completed and in working order, but when playing it was found that the hints were backwards, saying to go lower when it should be higher, and the New Game button did not work at all, and the attempt counter was wrong as left side has 8 but in right side is 7.

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
|   20  |   go lower        |     Go higher   |     none               |
|Attempts| Attempts left 8  | Attempts left 7 |     None               |
|New Game| Restarts game    |   No Change     |     None               |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I used Copilot
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
The AI gave a suggestion on how to fix the number guess hint
- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count.
When giving the fix for the guess hint, the AI also wanted to add more file libraries to bring in more complex solutions to a simple fix.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
When testing the game and the bug doesn't reappear
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
When fixing the new game bug, i had to test within the game starting it then trying to start a new game, checking if the secret number resets.
- Did AI help you design or understand any tests? How?
Yes the AI helped me design some of the tests by doing it through a virtual tests

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
It is a mechanism streamlit uses to update the app whenever something changes.

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
Instead of doing long prompts for simple tasks, I could go straight to the point.
- What is one thing you would do differently next time you work with AI on a coding task?
Ask the Ai to run multiple tasks at the same time instead of simple ones, one at a time.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
It has changed how easily I have thought coding could be, but how careful I need to be as well, as the AI can accidentially make the problem worse by over thinking a simple problem.
