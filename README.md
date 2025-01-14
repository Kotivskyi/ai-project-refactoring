# ai-project-refactoring
Testing AI refactoring suggestions on realworld project

Code2Prompt: https://github.com/raphaelmansuy/code2prompt

Repo Used for analysis: https://github.com/abi/screenshot-to-code

Project_summary.md Tokens: 332398

Prompt: 
"Here’s our current code base. Can you propose improvements or a refactoring plan?"

## Ranking of Responses

| Model                         | Score | Subjective Feedback                                                                                                | AI Feedback |
| ----------------------------- | ----- | ----------------------------------------------------------------------------------------------------------------- | ----------- |
| Gemini-2.0-flash-thinking-exp | Best  | Meaningful refactoring suggestions. It feels like it has a good understanding of the codebase. I would definitely consider implementing some of them.| Offers strong architectural vision with clear separation of concerns between frontend and backend, focusing on system design patterns and scalability considerations. |
| O1                            | 2nd   | I kinda like Gemini response more.  Some suggestions are meaningful but others are not. Anyweay it better higlights Documentation problem and found missing CI/CD.                                                            | Excels in providing a comprehensive DevOps-oriented roadmap with clear, actionable steps for implementation, making it ideal for teams looking to improve both code quality and deployment processes. |
| GPT-4o                        | 3rd   | Kinda makes sense, but feels like a list of general suggestions                                                    | Provides accessible high-level overview of improvement areas but lacks specific implementation details, making it better suited for initial planning rather than execution. |
| Claude-sonnet-3.5             | 4th   | Tries to write code straight away, but what I really want is bigger picture overview                                                      | Delivers practical, code-first approach with concrete TypeScript examples and type safety improvements, though narrower in scope compared to infrastructure considerations. |



