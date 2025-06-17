# Homework 1

## 🎯 Your Mission
A junior developer made a mess. Fix it using proper Git practices!

## 📁 Current State
- All changes dumped in one commit
- Useless commit messages ("fix", "update")
- Mixed features, bugs, and random comments
- No atomic commits

## ✅ Tasks

### 1. Split the Mess
Use `git add -p` to create atomic commits:
- [ ] Basic addition function
- [ ] Subtraction function (with bug)
- [ ] Bug fix for subtraction
- [ ] Division function
- [ ] Remove trash comments
- [ ] Add TODO for multiplication

### 2. Write Proper Commit Messages
Follow conventional commits:
```
feat: add basic addition function
fix: correct subtraction logic
refactor: remove unnecessary comments
```

### 3. Clean History
Use `git rebase -i` to:
- Reorder commits logically
- Squash related changes
- Edit commit messages

## 📋 Deliverables
1. Fork this repo
2. Fix the history
3. Submit PR with:
   - Clean, atomic commits
   - Meaningful messages
   - Logical commit order

## 🎓 Success Criteria
- Each commit does ONE thing
- `git log --oneline` tells a story
- Any commit can be reverted safely
- New developer understands project evolution

## 💡 Hint
Start fresh: `git reset --soft HEAD~1` to uncommit everything!
