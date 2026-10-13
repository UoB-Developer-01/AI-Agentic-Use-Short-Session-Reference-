
# 🤖 Session Supplementary Quick Reference

# 1- Useful, but Optional Installations

- Visual Studio Code: https://code.visualstudio.com/  
- Git: https://git-scm.com/  

# 2- Install Your AI Agent of Choice

## Claude Code (Requires A Paid Subscription)

1. First you need to subscribe online https://claude.com/pricing
2. Install Claude Code CLI

```
# Windows (CMD admin):
>curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd

# Windows (Powershell. Does not seem to work reliably):
irm https://claude.ai/install.ps1 | iex
```
3. Start using from windows terminal

- `claude` start terminal user interface (TUI)  
- `claude --enable-auto-mode` claude decides whether to ask for permissions
- `claude --dangerously-skip-permissions` bypasses request for approvals  

Note: If you prefer a graphical user interface over using the commnad line, you can download https://claude.com/product/claude-code

## OpenCode (Can be Used for Free)

1. install Node.js: https://nodejs.org/en  
1. install OpenCode https://opencode.ai/ `npm install -g @opencode/cli`
3. Start using from windows terminal `opencode`

# 3- Common CLI-Based AI Agent Commands

- `/clear` clear context window and start a new conversation. (it is good to do this often, but before doing you may sometimes want to ask claude to summarize progress and next steps in memory or some files)
- `/context` show context window token utilization
- `/status` claude settings, information, and remaining/cnosumed tokens % 
- `/model` switch between models

# 4- Markdown File Format Example

```
# Heading 1
## Heading 2
## Heading 3

Regular text example

- list item 1
- list item 2
- list item 3

- [x] list item 1
- [ ] list item 2
- [ ] list item 3
```

# Heading 1
## Heading 2
## Heading 3

Regular text example

This project tracks progress.

- list item 1
- list item 2
- list item 3

- [ ] list item 1
- [ ] list item 2
- [ ] list item 3

# 

# 5 - Prompting and Prompt Engineering 

**Prompts** are the instructions and input you give to an AI generative model.

-	Top and best
-	Score and rank
-	Include justifications
-	Compare across dimensions
-	Breakdown assess
-	Assess content and creator
-	Reference Card
-	ToC 
-	Additional Tips and Recommendations 

Example: 
> Top 30 desserts compared and scored across the most important dimensions

**Prompt engineering** is the process of crafting specific, effective instructions (prompts) to guide a generative AI model in producing desired outputs.

-	Persona, task, context, and format
-	Give References (sketches, images, urls, etc.)
-	Prompt generation 
-	Prompt reverse engineering

!!! Learn the name of things – and the concepts behind them (e.g. gardening, photogrphy, etc.)
