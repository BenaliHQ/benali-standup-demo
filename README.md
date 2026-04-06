# Benali Standup Demo

Practice repo for learning the GitHub workflow with Claude Code.

## What we're doing

Everyone adds their favorite candy bar to `team.md` — using branches, commits, and pull requests.

## Steps

1. **Clone the repo**
   ```
   gh repo clone BenaliHQ/benali-standup-demo
   cd benali-standup-demo
   ```

2. **Create your branch**
   ```
   git checkout -b add-[your-name]-candy
   ```

3. **Edit `team.md`** — add your candy bar next to your name (only your row)

4. **Commit**
   ```
   git add team.md
   git commit -m "Add [your name]'s favorite candy bar"
   ```

5. **Push and create a PR**
   ```
   git push -u origin add-[your-name]-candy
   gh pr create --title "Add [your name]'s candy bar"
   ```

6. **Wait for review** — Khalil will review and merge

## Rules

- Only edit your own row
- Write a clear commit message
- Never commit secrets or API keys
- Use Claude Code — just tell it what you want in plain English
