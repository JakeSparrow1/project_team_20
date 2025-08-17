# HOW TO ADD YOUR CS EMAIL TO GIT CONFIG

---

Follow these steps carefully on your Windows machine.

1. Open Command Prompt (cmd) or Git Bash.

   - Press `Win + R`, type `cmd`, and hit Enter.

2. Clone the project repository:

   ```
   git clone https://github.com/JakeSparrow1/project_team_20.git
   ```

3. Move into the project folder:

   ```
   cd project_team_20
   ```

4. Set your Git username (use your full name or first name):

   ```
   git config user.name "Your Full Name"
   ```

   Example:

   ```
   git config user.name "Taonga Kalizinje"
   ```

5. Set your Git email (use your CS email address):

   ```
   git config user.email "your_cs_email@cs.unza.zm"
   ```

   Example:

   ```
   git config user.email "taonga123@cs.unza.zm"
   ```

6. Verify that your details were saved:

   ```
   git config user.name
   git config user.email
   ```

   The output should show your name and CS email.

---

## NOTES:

- Do NOT run `git init` inside the project folder (it is already a Git repository).
- If you make a mistake with your email, you can reset it with:
  ```
  git config user.email "correct_email@cs.unza.zm"
  ```
- Always pull before pushing in new work:
  ```
  git pull origin main
  ```
