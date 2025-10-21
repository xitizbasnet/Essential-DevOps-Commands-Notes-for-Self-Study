## 🧬 Git Commands

```bash
51. git init                                 # Initialize a git repository
52. git clone repo_url                       # Clone a repository
53. git status                               # Show changes
54. git add .                                # Stage all changes
55. git commit -m "msg"                      # Commit changes
56. git push origin branch                   # Push changes
57. git pull origin branch                   # Pull latest changes
58. git checkout branch                      # Switch branch
59. git branch -a                            # List all branches
60. git merge branch                         # Merge branch into current branch
61. git log --oneline                        # Show commit history
62. git diff                                 # Show changes
63. git stash                                # Stash changes
64. git stash pop                            # Apply stashed changes
65. git reset --hard HEAD~1                  # Reset last commit
66. git revert commit_id                     # Revert commit
67. git tag -a v1.0 -m "Version 1.0"         # Create tag
68. git push --tags                          # Push tags
69. git rm file                              # Remove a file from git
70. git clean -fd                            # Remove untracked files
71. git config --global user.name "Your Name"  # Set global username
72. git config --global user.email "you@example.com"  # Set global email
73. git show commit_id                       # Show commit details
74. git blame file.txt                       # Show changes by line
75. git remote -v                            # Show remote repositories
76. git remote add origin URL                # Add remote repo
77. git rebase branch                        # Rebase branch
78. git cherry-pick commit_id                # Pick specific commit
79. git fetch                                # Fetch remote changes
80. git log --graph                          # Show graphical commit log
81. git branch -d branch_name                # Delete branch
82. git pull --rebase                        # Rebase while pulling
83. git push --force                         # Force push changes
84. git reflog                               # Show reflog
85. git diff HEAD~1                          # Show last commit changes
86. git apply patch.diff                     # Apply patch
87. git reset --soft HEAD~1                  # Soft reset
88. git archive --format=tar.gz HEAD > archive.tar.gz  # Archive repo
89. git grep "search_term"                   # Search for text
90. git bisect start                         # Start binary search
91. git ls-files                             # List tracked files
92. git update-index --assume-unchanged file # Ignore file temporarily
93. git push origin --delete branch_name     # Delete remote branch
94. git pull --all                           # Fetch all branches
95. git submodule add URL path               # Add a submodule
96. git submodule update --init --recursive  # Update submodules
97. git commit --amend -m "Updated commit message"  # Amend commit
98. git fetch --prune                        # Remove deleted remote branches
99. git push --mirror destination_url        # Mirror repository
100. git worktree add ../branch_name branch_name  # Work with multiple branches
```


