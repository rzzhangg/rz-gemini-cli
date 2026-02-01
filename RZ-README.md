# Richard's experiments of Google gemini-cli

- For deep understanding how coding agent is designed and implemented
- How to understand the intentions of user prompts and break them into tasks to be performed
- How to manage context, memory and session
- How to consolidate instructions from various markdown files, understand the intentions and use them effectively
- How to interact with agent skills and MCP servers
- How to maintain secure execution environment in which to peform the tasks

## git commands


     # 1. Add the original repo as "upstream" remote (one-time setup)
     git remote add upstream https://github.com/google/genai-gemini-cli.git

     # 2. Fetch the latest changes from upstream
     git fetch upstream

     # 3. Make sure you're on your main branch
     git checkout main

     # 4. Merge upstream changes into your fork
     git merge upstream/main

     # 5. Push the updates to your fork
     git push origin main

Alternative

    git fetch upstream
    git checkout main
    git rebase upstream/main
    git push origin main --force-with-lease


