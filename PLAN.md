# Plan Document for Repository & Activity #14

This document describes my plans for both (1) the GitHub repository and  
(2) the Activity #14 project. Each part is written in terms of Goals, Needs, and Steps.

---

## Part 1 – Plan for the GitHub Repository

### Goals
- Keep a clear, public record of my work for Activities #14 and #15.
- Practice basic version control skills: branches, commits, issues, and pull requests.
- Maintain an organized repo so the instructor can easily find the QMD, PDF, README, and this plan.

### Needs
- A public GitHub repository that belongs to my STAT 184 account.
- A `main` branch plus at least one additional branch (for example, `editing-activity14`).
- A README file that explains the project and data.
- This plan document (`PLAN.md`).
- At least two Issues to track future work or improvements.

### Steps
1. Create a public repository for Activity #14 on GitHub.
2. Add the Activity #14 QMD file and PDF to the repo.
3. Create and maintain a `README.md` file describing the project, data sources, plan, and structure.
4. Create this `PLAN.md` file and keep it updated if the project changes.
5. Create an additional branch (e.g., `editing-activity14`) for editing the README or QMD.
6. Make changes on the new branch, commit with clear messages, and open a pull request.
7. Merge the pull request into `main` after reviewing the changes.
8. Create at least two Issues to记录 ideas, bugs, or improvements for the repo.
9. Periodically check that all files are up to date and that the repo remains organized.

---

## Part 2 – Plan for the Activity #14 Project

### Goals
- Produce a complete Activity #14 QMD that satisfies all assignment requirements.
- Show that I can combine several earlier activities (08, 10, 13, 04) into one well-structured report.
- Create a final PDF that is clear, reproducible, and ready to submit on Canvas.

### Needs
- A QMD file with a correct YAML header (title, name, date, output format).
- Clean and working R code for:
  - Armed forces data wrangling (from Activities #08 and #10).
  - Baby-name popularity analysis (from Activity #13).
  - The box-volume function and plot (from Activity #04).
- A section where I reflect on what I have learned so far.
- A “Code Appendix” section that contains full code chunks.
- Enough time to review, knit to PDF, and fix any errors.

### Steps
1. **Set up the QMD**
   - Create a YAML header with an appropriate title, my name, date, and PDF output.
   - Add clear headings for each required section.

2. **Armed forces data wrangling (Activities #08 and #10)**
   - Bring in the data-wrangling code from Activity #08 (especially Question 5).
   - Fix any problems so the code can run on another computer without changes.
   - Use the structure from Activity #10 to build a frequency table for a small subset of soldiers.
   - Briefly explain what the table shows.

3. **Baby-name popularity (Activity #13)**
   - Load the baby-name dataset used in class (from the R package provided in STAT 184).
   - Create at least one summary or visualization of name popularity.
   - Explain why I chose the specific names and what interesting patterns I see.

4. **Box-volume function and plot (Activity #04)**
   - Reuse the volume function from the “box problem”.
   - Use `ggplot2` and `stat_function()` to plot volume vs. cut-out side length.
   - Label the axes and write a short interpretation of the graph.

5. **Reflection section**
   - Write a short section that describes what I think I have learned or mastered so far in this course.
   - Connect this reflection to the code and plots in the document where possible.

6. **Code Appendix**
   - Create a section named “Code Appendix”.
   - Move full code chunks into this section so that the main body focuses on explanation and results.
   - Keep the code well formatted and commented.

7. **Final checks and submission**
   - Read through the entire QMD to fix spelling, grammar, and formatting issues.
   - Knit the QMD to produce a PDF.
   - Upload the final PDF to Canvas.
   - Commit and push the final QMD and PDF to this GitHub repository.
