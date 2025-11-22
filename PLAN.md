# Plan for Repository & Activity #14

## Repository (GitHub) Plan
- Keep this repository public so that the instructor can see my work.
- Use the **main** branch for stable, completed work.
- Create additional branches (for example, `editing-activity14`) when I want to
  experiment or make changes to the Activity #14 files.
- Write clear commit messages that describe what changed and why.
- Open pull requests to review and merge changes from a branch back into `main`.
- Use Issues to record bugs, ideas, or to-do items related to Activity #14.
- Make sure both the QMD file and the PDF for Activity #14 are stored in this
  repository and kept up to date.

## Activity #14 Plan

1. **YAML header**
   - Create a valid YAML header with:
     - A meaningful title for the document.
     - My name.
     - The date.
     - The output format (PDF).
   - Check that the YAML renders correctly when knitting.

2. **Overall document structure**
   - Organize the QMD into clear sections with appropriate headings.
   - Make sure the headings match the required topics so the instructor can
     quickly see where each part of the assignment is completed.

3. **Section: Armed Forces data wrangling revisit (Activities #08 and #10)**
   - Re-use and clean up the data-wrangling code from Activity #08 (especially
     the code from Question 5).
   - Fix any problems so the code can run on another person’s computer without
     modification.
   - Use the processed data and the structure from Activity #10 to create a
     frequency table for a *small subset* of soldiers.
   - Explain briefly what the table shows.

4. **Section: Baby name popularity (Activity #13)**
   - Revisit the ideas from Activity #13.
   - Clearly explain why I chose the specific names that appear in my graphs or
     tables (for example, personal reasons, interesting patterns, or trends).
   - Include at least one summary or visualization of baby-name popularity.

5. **Section: Plotting a mathematical function (Activity #04 – box problem)**
   - Reuse the function for the volume of the box from Activity #04.
   - Create a plot of **box volume vs. cut-out side length**.
   - Use **ggplot2** and `stat_function()` to produce the plot, as required.
   - Label axes clearly and write a short interpretation of what the graph shows.

6. **Section: What I have learned so far**
   - Reflect on what I believe I have learned and “mastered” so far in this
     course.
   - Write a short, honest paragraph (or more) summarizing my current
     understanding and skills.

7. **Code appendix**
   - At the end of the QMD, create a section called **“Code Appendix”**.
   - Move full code chunks into this appendix so that the main body focuses on
     explanations, tables, and graphs.
   - Keep the code well formatted and clearly separated into logical parts.

8. **Final checks and submission**
   - Read through the whole document and fix grammar, spelling, and formatting
     issues.
   - Knit the QMD to create a PDF.
   - Upload the PDF to Canvas in the correct submission area.
   - Commit and push the final QMD and PDF to this GitHub repository with a
     clear commit message.
