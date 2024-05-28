# Terminal Exercise 3: Profiles

## Objective

Edit and use profile files to customize your shell environment.

## Tasks

1. Open your Terminal application.
2. Open your profile file in a text editor (e.g., `nano` or `vi`).

   ```bash
   nano ~/.bash_profile  # or ~/.zshrc if you use zsh
   ```

3. Add the following lines to your profile file:

   ```bash
   # Custom Aliases
   alias ll='ls -la'
   alias gs='git status'

   # Custom Environment Variables
   export MY_VAR=HelloWorld
   ```

4. Save and close the file.
5. Source the profile file to apply the changes.

   ```bash
   source ~/.bash_profile  # or ~/.zshrc if you use zsh
   ```

6. Verify the changes by using the `ll` alias and printing the value of `MY_VAR`.

   ```bash
   ll
   echo $MY_VAR
   ```

Experiment with adding more aliases and environment variables to customize your Terminal experience.
