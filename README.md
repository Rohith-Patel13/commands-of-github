# Git-commands

# Create an empty local repository
```sh
git init 
```

# Add to stage area
```sh
git add -A 
```

# Save changes to local repository
```sh
git commit -m “commit message” 
```

# Display a list of commits in your local repository
```sh
git log
```

# Establishes a connection between your local repository and a remote repository hosted on a server, such as GitHub, GitLab, or Bitbucket.
```sh
git remote add origin <repository-url>
```

# Used in Git to rename the current branch to "main"
```sh
git branch -M main 
```

# Push your local repository changes to remote repository
```sh
git push -u origin main 
```

# Enter Username and  Password i.e PAT


# After changing any file in local repository continuation commands:
```sh
git add changed_content_file_name
```
```sh
git commit -m “changed_content_file_name  commit message”
```
```sh
git push -u origin main
```

# Provides a summary of what is happening in the repository
```sh
git status
```

# Pull latest commits from a remote repository to your local repository
```sh
git pull origin main
```

# For removing origin
```sh
git remote rm origin 
```

# For removing ./git folder
```sh
rm -rf .git 
```


# Creating a branch in github and make PR:
1) clone the main branch
2) ```sh
   git checkout -b <new_branch_name>
   ```

