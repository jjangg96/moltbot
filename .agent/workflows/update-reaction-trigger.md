---
description: Update main from upstream and merge it into feat/discord-reaction-trigger
---

// turbo-all
1. Update main branch from upstream:
   ```bash
   git checkout main
   git pull upstream main --no-rebase
   git push origin main
   ```

2. Merge main into reaction trigger branch:
   ```bash
   git checkout feat/discord-reaction-trigger
   git merge main
   ```

3. Push the updated branch:
   ```bash
   git push origin feat/discord-reaction-trigger
   ```
