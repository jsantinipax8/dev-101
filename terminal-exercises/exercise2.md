# Terminal Exercise 2: Environment Variables and Aliases

## Objective

Understand and use environment variables and aliases.

## Tasks

1. Open your Terminal application.
2. Print the value of the `HOME` environment variable.

   ```bash
   echo $HOME
   ```

3. Set a new environment variable named `MY_VAR` with the value `HelloWorld`.

   ```bash
   export MY_VAR=HelloWorld
   ```

4. Print the value of `MY_VAR`.

   ```bash
   echo $MY_VAR
   ```

5. Create an alias named `ll` that lists directory contents in long format.

   ```bash
   alias ll='ls -la'
   ```

6. Use the `ll` alias to list the contents of the current directory.

   ```bash
   ll
   ```

To make the alias permanent, add it to your profile file (`~/.bash_profile` or `~/.zshrc`).
