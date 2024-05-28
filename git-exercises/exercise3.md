# Git Exercise 3: Branching and Merging

## Objective

Learn to create branches and merge them back into the main branch.

## Tasks

1. Open your Terminal application and navigate to your repository.
2. Create a new branch named `feature-branch`.

   ```bash
   git branch feature-branch-<username>
   ```

3. Switch to the `feature-branch-<username>`.

   ```bash
   git checkout feature-branch-<username>
   ```

4. Create a new file named `feature.txt` and add some content.

   ```bash
   echo "This is a new feature" > feature.txt
   ```

5. Add `feature.txt` to the staging area and commit the change.

   ```bash
   git add feature.txt
   git commit -m "Add feature.txt"
   ```

6. Push branch to origin (GitHub)

   ```bash
   git push --set-upstream origin feature-branch-<username>
   ```

7. Create PR on GitHub by navigating to the URL printed from the `git push...` command

You have now learned how to work with branches and create a PR to merge changes back to the `main` branch!
