# :brain: Git Learning Notes

### ✅ What I understand so far:

#### 🌳 Branching

- Creating and switching to a branch

```
git switch -c feature-name
```

- Checking branches

```
git branch
```

### 📦 Staging and Committing

- Stage files

```
git add .
```

- Commmit with a message:

```
git commit -m "your message"
```

### 🚀 Pushing and Pulling

- Push a branch `git push -u origin your-branch-name`

- Pull a branch `git pull`

-- 💯 Basic Concepts

- A branch is a timeline of work
- main (or master) is the default branch
- Staging area = "What I'm preparing to commit"

### 😵‍💫 Things I'm still confused about:

--When to use 🔀 `checkout` vs `switch`

- `switch` and `restore` are newer, but `checout` still works

- some tutorials mix them up

* ↖️ Merge vs Rebase

- What's the practical difference?
- When should I rebase instead of merge?

🎯 HEAD Pointer

- I get that it points to where I am ..but how does it move exactly

* ⏪Undoing Mistakes

- git revert vs git reset
- Hard reset vs soft reset
- Which one is safe?

--🌐 Tracking Remote Branches

- Why do I sometimes nee `-u` with `git push`?

🧪 Commands I want to practice

`git merge`
`git rebase`
`git reset --soft, --mixed, --hard`
`git stash`
`git log --oneline --graph --decorate`

## ❓ Additional info

- Why does Git sometimes say a branch is "ahead" or "behind"?
- Whats a **detached HEAD** and what does that even mean?
