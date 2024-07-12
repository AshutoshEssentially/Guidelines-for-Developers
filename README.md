# Guidelines While Working On a Project

1. **Use correct production code from the beginning**
   - ORM to use DB
   - Correct folder structure and logical separation
   - Environment variable access method
   - Database structure
   - Use descriptive variable names
   - Create logs

2. **The first thing in the project is to implement the main, implement logs, and then implement the required functionalities.**

3. **As soon as the functionalities are completed, run and test it.**
   - Get it reviewed by someone else
   - Only then push it to the central repository

4. **As soon as the code is pushed, ask other team members to immediately take a pull and continue their work.**

5. **Before starting any code, make sure you have the input and output requirements confirmed:**
   - Document it **ON PAPER**
   - Get it reviewed by your assignee

6. **Create a DAG structure ON PAPER to determine dependent and independent tasks for every project.**

7. **Use interfaces to accommodate dependency injection.**

8. **ChatGPT often does not have the full context of the code you are asking for.**
   - The code given might not fully satisfy your requirement but the logic may be correct
   - Hence, try to avoid copy-pasting and prefer to write the code yourself

9. **Only add comments wherever required.**
   - Before pushing, make sure you remove all the unused, wrong, and commented code

10. **Every function should have comments describing the input, the functionality, and the output.**
