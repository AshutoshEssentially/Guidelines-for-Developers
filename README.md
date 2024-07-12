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

5. **Do not blindly copy even your code**
  - There are instances where 2 different functions have similar logic but slightly different implementations.
  - At such time we are tempted to copy the code from the previously implemented function and paste it to create the second function.
  - In such cases, we tend to miss small details which later turn into a bug that takes an hour to debug.
  - So every time we copy any code, we should be extremely careful.

7. **Before starting any code, make sure you have the input and output requirements confirmed:**
   - Document it **ON PAPER**
   - Get it reviewed by your assignee

8. **Create a DAG structure ON PAPER to determine dependent and independent tasks for every project.**

9. **Use interfaces to accommodate dependency injection.**

10. **ChatGPT often does not have the full context of the code you are asking for.**
   - The code given might not fully satisfy your requirement but the logic may be correct
   - Hence, try to avoid copy-pasting and prefer to write the code yourself

11. **Only add comments wherever required.**
   - Before pushing, make sure you remove all the unused, wrong, and commented code

11. **Every function should have comments describing the input, the functionality, and the output.**
