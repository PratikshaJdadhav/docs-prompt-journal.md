# SupportDesk Prompt Journal

> Starter journal for Day 3 — 23 October 2026.
> Update each entry after you use the prompt and review the actual response. The checks below are not claimed to have been run unless explicitly stated.

## Entry 1 — Understand tokens and context windows

- Date: 23 October 2026
- Goal: Understand basic LLM terms in beginner-friendly language.
- Prompt used: “Explain tokens and context windows in simple English. Give a short definition and explain why relevant project details should be included in a prompt.”
- Summary of AI response: A token is a small unit of text processed by a language model. A context window is the amount of information the model can consider at one time.
- What I changed or rejected: I kept the explanations short and beginner-friendly.
- Why I changed it: Short definitions are easier to revise and explain in my own words.
- How I checked the result: Not independently verified yet. Review the Day 3 learning notes and explain both terms without reading.
- What I learned: Tokens are not exactly the same as words, and the assistant may not have every earlier project detail available in a long conversation.
- Follow-up question or unresolved assumption: How does the context window affect a very long conversation?

## Entry 2 — Learn the 6-box prompt framework

- Date: 23 October 2026
- Goal: Learn the six parts of a structured prompt.
- Prompt used: “Explain the 6-box prompt framework in English, using simple definitions.”
- Summary of AI response: The six boxes are Context, Goal, Constraints/Guardrails, Examples, Output Format, and Checks.
- What I changed or rejected: I used one-line definitions for each box rather than a long explanation.
- Why I changed it: A concise list is easier to remember and apply to future prompts.
- How I checked the result: Compared the names and descriptions with the Day 3 assignment document. Confirm this review before marking it complete.
- What I learned: A strong prompt explains the task, limits, expected answer, and how the result should be checked.
- Follow-up question or unresolved assumption: Which boxes are essential for a simple request versus a complex coding task?

## Entry 3 — Rewrite the SupportDesk explanation prompt

- Date: 23 October 2026
- Goal: Make “Explain SupportDesk” suitable for a new intern without inventing project details.
- Prompt used: “I am a new intern learning about SupportDesk. Explain what it does, who uses it, and its main features using only the supplied PRD. Do not invent missing details. Identify unclear information and return a beginner-friendly structured summary.”
- Summary of AI response: The improved prompt specifies the audience, source of truth, missing-information handling, and structured output.
- What I changed or rejected: I replaced the broad request with a PRD-based task and asked the assistant to identify gaps.
- Why I changed it: The original prompt did not say what SupportDesk information to use or how to handle missing facts.
- How I checked the result: The actual PRD was not included in this exercise, so the product facts have not been verified. Supply the approved PRD before using this prompt for a factual summary.
- What I learned: The assistant should not fill gaps in project requirements with guesses.
- Follow-up question or unresolved assumption: Which sections of the approved PRD define users and product features?

## Entry 4 — Ask for a prompt critique

- Date: 23 October 2026
- Goal: Check whether a prompt is specific, bounded, and verifiable.
- Prompt used: “Review this prompt against the six boxes: Context, Goal, Constraints/Guardrails, Examples, Output Format, and Checks. Identify missing information and suggest focused improvements without inventing requirements.”
- Summary of AI response: This prompt asks for a structured critique and explicitly requires the reviewer to identify missing boxes.
- What I changed or rejected: I added a named checklist and asked for missing information to be called out.
- Why I changed it: “Make this prompt better” does not define what a good prompt should contain.
- How I checked the result: Not yet tested on a separate prompt. Apply it to one of the five weak prompts and record the actual findings.
- What I learned: A review is more useful when the evaluation criteria are explicit.
- Follow-up question or unresolved assumption: Should every prompt include examples, or only when an example would clarify the expected result?

## Entry 5 — Request assumptions and verification steps

- Date: 23 October 2026
- Goal: Avoid accepting a confident-sounding AI answer without checking it.
- Prompt used: “Review your answer and list assumptions, unsupported claims, edge cases, and verification steps. Distinguish checks that are suggested from checks that have actually been completed. Do not claim that tests passed unless they were run.”
- Summary of AI response: The prompt directs the assistant to expose uncertainty and separate proposed verification from completed verification.
- What I changed or rejected: I explicitly added a requirement to distinguish suggested checks from tests actually run.
- Why I changed it: A test checklist is not evidence that tests passed.
- How I checked the result: No code tests were run as part of this prompt-writing exercise. For future coding work, follow the steps and record actual results.
- What I learned: AI output is a suggestion until checked against requirements, reliable documentation, or test results.
- Follow-up question or unresolved assumption: Which checks can be done from the supplied files, and which require running the application?

## Review checklist

- [ ] I used these prompts and updated each entry to match the actual AI response.
- [ ] I recorded any changes or rejected suggestions and why.
- [ ] I verified claims against approved project material where available.
- [ ] I did not claim tests passed unless I actually ran them.
- [ ] I did not include passwords, API keys, `.env` values, customer data, or confidential code.
