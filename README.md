## **How to Submit Your Solution?**

1. **Clone this repository:**
   - Clone the project repository to your local machine using the following command:
     ```bash
     git clone <repository-url>
     ```

2. **Create a new branch:**
   - Create a new branch with the name of the task followed by your name:
     ```bash
     git checkout -b task-1-<your-name>
     ```

3. **Create a directory for your task:**
   - Inside the `tasks` directory, create a new folder named after the task followed by your name:
     ```
     tasks/
       └── 1-task/
           └── <your-name>/
     ```
   - Add your solution files to this directory.

4. **Commit your changes:**
   ![git-commit-message-cheatsheet](https://github.com/user-attachments/assets/20f9bbe3-5f51-49b6-bbdb-b62bdbeec7e7)

   - Ensure that your commit messages are **descriptive** and follow the format below:
     ```
     <type>: <short description>
     ```
   - **Types of commits**:
     - `feat`: For adding a new feature.
     - `fix`: For fixing bugs.
     - `refactor`: For refactoring existing code.
     - `docs`: For changes related to documentation.
     - `style`: For styling changes that don’t impact the code logic.
     - `test`: For adding or improving tests.
     - `chore`: For changes to build processes or auxiliary tools.

   - **Examples of commit messages**:
     - `feat: implement a new feature`
     - `fix: remove a bug in form validation`
     - `refactor: improve login function`
     - `docs: add contribution guidelines`
     - `style: change the color of submit button`
     - `test: add tests for user login`
     - `chore: add ESLint configuration`

6. **Push your changes:**
   - Push your branch to the repository:
     ```bash
     git push origin task-1-<your-name>
     ```

7. **Create a Pull Request (PR):**
   - Go to the repository on GitHub and create a **pull request** (PR) from your branch.
   - The **title** of the PR should follow this format:
     ```
     [Task <task-number>]: <Task description>
     ```

   - **Examples of PR titles**:
     - `[Task 1]: Implement Holy Grail layout using CSS`
     - `[Task 2]: Implement Mortgage Calculator using React`

---
