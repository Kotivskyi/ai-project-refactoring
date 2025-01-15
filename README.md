# ai-project-refactoring
Testing AI refactoring suggestions on realworld project

Project used for analysis: [screenshot-to-code](https://github.com/abi/screenshot-to-code)

Project_summary.md (332398 tokens), is generated using[code2prompt](https://github.com/raphaelmansuy/code2prompt)


Prompt Used: 
"Here's our current code base  @project_summary.md. Can you propose improvements or a refactoring plan? Give me bullet list of such improvments with priorities (High/Medium/Low) and short explanation why this improvment needed and what has to be done for each item"


## Suggested Improvments Comparison

| Improvment                                        | O1 (Priority) | Gemini-2.0-flash-thinking-exp (Priority) | Subjective Human Ranking |
| ------------------------------------------------- | ------------- | ---------------------------------------- | ------------- |
| Centralize Configuration Files                    | ❌            | ✅ (High)                                | (Medium) Make sence, Configs will be easier to support in the future         |
| Improve Component Organization in Frontend        | ✅ (High)     | ✅ (High)                                | (High) Definetly worth doing high risk of having spaghettic code              |
| Standardize Naming Conventions / Linter Rules                    | ✅ (Medium)             | ✅ (Medium)                              | (High) Good linter should be able to solve it              |
| Group Backend Routes                              | ❌            | ✅ (Medium)                              | (Medium-Low) Only If we are planning to add more routes             |
| Review Utility and Helper Functions               | ✅ (Medium)   | ✅ (Low)                                 | (Medium) Worth to check if there are any duplicates. Why the are 2 places for utility functions ?           |
| Consolidate Test Directories                      | ✅ (Low)      | ✅ (Low)                                 | (Medium) Definitely YES              |
| Add Consistent Error Handling                     | ✅ (High)     | ❌                                       | (Medium) Good Point especially if we are aiming for good code quality and not just a demo            |
| Improve TypeScript Strictness                     | ✅ (High)     | ❌                                       | (Low) Up to taste of developers. Typescript strictnes is kinda painfull already            |
| Extract Reusable Layout Components                | ✅ (Medium)   | ❌                                       | (Low) sounds good, but need to take a look what can be reused               |
| Improve Comments and Documentation                | ✅ (Low)      | ❌                                       | (Medium) It is always trade of between development speed and documentation, if there was way to employ AI to do it              |
| Optimize for Performance Where Relevant           | ✅ (Low)      | ❌                                       | (Low) Only spend time on it if there is clear bottleneck              |
| Enhance Testing Coverage                          | ✅ (Low)      | ❌                                       | (Medium) Maybe let AI do it. Never seen developer willing to add tests when feature is already working.              | 