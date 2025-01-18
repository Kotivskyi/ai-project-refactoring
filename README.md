# ai-refactoring-suggestions
Testing AI refactoring suggestions on real-world project

Project used for analysis: [screenshot-to-code](https://github.com/abi/screenshot-to-code)


**Models Tested:**
- O1
- Gemini-2.0-flash-thinking-exp
- Claude-sonnet-3.5-sonnet-20240620
- ChatGPT-4o
- DeepThink

**Context:**
Project_summary.md (332398 tokens). Generated using [code2prompt](https://github.com/raphaelmansuy/code2prompt)


**Prompt:** 
"Here's our current code base  @project_summary.md. Can you propose improvements or a refactoring plan? Give me a bullet list of such improvements with priorities (High/Medium/Low) and a short explanation of why this improvement is needed and what has to be done for each item."


## Suggested Improvements Comparison (O1 vs Gemini)

| Improvement                                        | O1 (Priority) | Gemini-2.0-flash-thinking-exp (Priority) | Subjective Ranking |
| ------------------------------------------------- | ------------- | ---------------------------------------- | ------------- |
| Centralize Configuration Files                    | ❌            | ✅ (High)                                | (Medium) Makes sense, Configs will be easier to support in the future         |
| Improve Component Organization in Frontend        | ✅ (High)     | ✅ (High)                                | (High) Definitely worth doing, high risk of having spaghetti code              |
| Standardize Naming Conventions / Linter Rules     | ✅ (Medium)   | ✅ (Medium)                              | (High) A good linter should be able to solve it              |
| Group Backend Routes                              | ❌            | ✅ (Medium)                              | (Medium-Low) Only if we are planning to add more routes             |
| Review Utility and Helper Functions               | ✅ (Medium)   | ✅ (Low)                                 | (Medium) Worth checking if there are any duplicates. Why are there 2 places for utility functions?           |
| Consolidate Test Directories                      | ✅ (Low)      | ✅ (Low)                                 | (Medium) Definitely YES              |
| Add Consistent Error Handling                     | ✅ (High)     | ❌                                       | (Medium) Good point, especially if we are aiming for good code quality and not just a demo            |
| Improve TypeScript Strictness                     | ✅ (High)     | ❌                                       | (Low) Up to the taste of developers. TypeScript strictness is kind of painful already            |
| Extract Reusable Layout Components                | ✅ (Medium)   | ❌                                       | (Low) Sounds good, but need to take a look at what can be reused               |
| Improve Comments and Documentation                | ✅ (Low)      | ❌                                       | (Medium) It is always a trade-off between development speed and documentation, if there was a way to employ AI to do it              |
| Optimize for Performance Where Relevant           | ✅ (Low)      | ❌                                       | (Low) Only spend time on it if there is a clear bottleneck              |
| Enhance Testing Coverage                          | ✅ (Low)      | ❌                                       | (Medium) Maybe let AI do it. Never seen a developer willing to add tests when a feature is already working.              | 
