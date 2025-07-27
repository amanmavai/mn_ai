```sh
# plan mode
shift + tab (twice) 

# file paths
use @ to refer to files / folders in the current project

# claude code usage report
bunx ccusage
```

# subagents
use subagents to explore multiple paths in parallel (e.g. when you have multiple ideas for a solution)


# things you could ask claude code
- what did I do last week?

# playwright mcp
- Implement the ui shown in the attached image, by using playwright MCP to screenshot the app, until it looks like the image (paste image here), allow auto accepts
- playwright mcp can also check for browser logs and errors

# Leverage Tests 
- Write tests for Claude to auto-verify functionality; prompt Claude to write ad-hoc tests if needed.

# context
- Despite large context windows, Claude's response quality can degrade with conversation length.
- After finishing a task, it's recommended to clear the existing context using `/clear`
- The `/compact` command can be used to summarize long conversations, retaining key decisions and code changes in a more concise format. 
- You can revert to a previous point in the conversation by pressing the **double escape** key and selecting a message

# version control
- Adding pre-commit checks (e.g., compile checks, linters, unit tests) using tools like Husky [15:10] can ensure high code quality and automated feedback for Claude.

# utility features
- ! for running bash commands and including their output in context 
- Keywords like `think`, `think hard`, `think harder`, and `ultra think` to trigger different levels of thinking budgets for Claude's models (use sparingly due to quota consumption).
- Ctrl + Dash to undo typing in the terminal 

# commands
Utilizing Commands for Specific Tasks (code-review etc). For specific tasks requiring additional context without polluting the root claude.md file, you can create custom commands in the commands folder. These commands can accept arguments and include outputs of bash commands

# subagents
could you research what you would recommend for this, perhaps you could split these into 3 separate issues and tackle them in parallel using subagents so I don't have to wait too long. 