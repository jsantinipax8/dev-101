# Git Exercise 2: Cloning and Pushing to GitHub

## Objective

Learn to clone a repository and push changes to GitHub.

## Tasks

1. Fork this repository on GitHub to create your own copy.
2. Clone your forked repository to your local machine.

   ```bash
   git clone https://github.com/your-username/dev-101.git
   cd intro-to-terminal-and-git
   ```

3. Create a new file named `myfile.txt` and add some content.

   ```bash
   echo "Hello, GitHub!" > myfile.txt
   ```

4. Add `myfile.txt` to the staging area.

   ```bash
   git add myfile.txt
   ```

5. Commit the change with a message.

   ```bash
   git commit -m "Add myfile.txt"
   ```

6. Push the change to your GitHub repository.

   ```bash
   git push origin main
   ```

You have now successfully pushed changes to your GitHub repository!
