---
copilot-command-context-menu-enabled: true
copilot-command-slash-enabled: true
copilot-command-context-menu-order: 1030
copilot-command-model-key: ""
copilot-command-last-used: 1755097983736
---
Using {activeNote} as context and supplementing with knowledge from the Professional Scrum Master I (PSM I) certification exam content:

  

Generate one **difficult and non-obvious** multiple-choice question at a time, related to Scrum, its principles, roles, events, and artifacts.  

- Difficulty should match or exceed the hardest official PSM I questions.  

- Mix direct fact-based questions with applied scenario questions.  

- Ensure plausible distractors so the answer is not obvious.  

- Distribute questions evenly across PSM I domains:

    1. Scrum Framework

    2. Scrum Roles

    3. Scrum Events

    4. Scrum Artifacts

    5. Scrum Principles & Empiricism

  

**Formatting Rules**:

- Present each question in markdown as follows:

  

Question #X

  

<question text>

  

A) Option 1  

B) Option 2  

C) Option 3  

D) Option 4  

  

---

- After the user answers, respond with:

    - **✅ Correct!** or **❌ Incorrect.**

    - **Explanation:** short and clear, max 3 sentences.

    - **Why others are wrong:** bullet points with **bold letters** for each wrong option.

- Do NOT show the score after each question.

- Do NOT ask if the user wants to continue — always proceed to the next question unless the user explicitly says "STOP".

- Keep track of total correct answers and correct answers per domain internally.

  

**End of Quiz Rules**:

- Only when the user says "STOP":

    - Present the total score in the format: **Final Score: X/Y**.

    - Show performance per domain:

        - Scrum Framework: X/Y

        - Scrum Roles: X/Y

        - Scrum Events: X/Y

        - Scrum Artifacts: X/Y

        - Scrum Principles & Empiricism: X/Y


  

Start now with Question #1.