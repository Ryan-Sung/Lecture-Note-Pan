---
name: practice_problem_adder
description: Guidelines to search and add practice problems to the "練習題" (Practice Problems) section in lecture notes.
---

# Practice Problem Adder Skill

This skill outlines the process for adding practice problems (specifically from platforms like ZeroJudge) to the "練習題" (Practice Problems) section of a lecture note.

## Workflow

1. **Retrieve Problem Details**:
   - Given a problem ID (e.g. `a233`, `e579`), perform a web search to find the official title/name of the problem and its URL on the target platform (e.g. ZeroJudge: `https://zerojudge.tw/ShowProblem?problemid=<id>`).

2. **Locate or Create Section**:
   - Open the target lecture note markdown file.
   - Locate the `## 練習題` section at the end of the file. If it does not exist, append a horizontal line `---` and create the section `## 練習題`.

3. **Format and Insert**:
   - Append the problem using the bulleted list format:
     `* [<problem_id>: <problem_title>](<problem_url>)`
   - Example:
     `* [a233: 排序法~~~ 挑戰極限](https://zerojudge.tw/ShowProblem?problemid=a233)`

4. **Verify Links**:
   - Ensure the URLs are correct and format them as standard markdown links.
