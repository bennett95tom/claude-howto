# 📚 Claude How-To: Everything Explained Like You're Five

## What Is This Thing?

Think of **Claude How-To** like a **giant instruction manual + playground** for Claude Code. Claude Code is a super-powered robot assistant that lives in your computer. This project teaches you how to make that robot do amazing things.

The project has **100+ ready-to-copy examples**, **3 complete plugins**, and **a learning path** that takes you from "I just installed Claude" to "I'm automating my entire workflow."

---

## The Big Picture: 10 Features You Can Learn

Claude Code has 10 main superpowers. Think of them like levels in a video game:

### 🎮 The 10 Levels (Features)

| Level | Name | What It Does | Analogy |
|-------|------|-------------|---------|
| **1** | **Slash Commands** | Quick shortcuts (type `/optimize` to fix code) | Like keyboard shortcuts in your favorite game |
| **2** | **Memory** | Claude remembers your preferences & project rules | Like saving your character's stats so you don't lose them |
| **3** | **Skills** | Teach Claude new abilities that trigger automatically | Like hiring NPCs with special powers to help you |
| **4** | **Subagents** | Send mini-Claudes to handle complex tasks | Like splitting your party into teams to solve quests |
| **5** | **MCP** | Connect Claude to Google Drive, GitHub, Slack, etc. | Like opening portals to your other tools |
| **6** | **Hooks** | Set up automatic actions before/after Claude does things | Like building traps or defense systems in your fortress |
| **7** | **Plugins** | Bundle everything above into shareable packages | Like creating a mod pack to share with other players |
| **8** | **Checkpoints** | Save your progress so you can undo mistakes | Like save points in a video game |
| **9** | **Advanced Features** | Planning mode, auto mode, voice dictation | Like unlocking cheat codes and power-ups |
| **10** | **CLI** | Use Claude from your computer's command line | Like playing the game from a secret terminal instead of the UI |

---

## How The Learning Works: Three Levels

This project is designed so **you pick your starting point** based on what you already know.

### 🟢 Level 1: Beginner (0-2 features learned)
**Time**: ~3 hours | **Goal**: Do 5 useful things with Claude

You learn:
- How to create your first slash command (30 minutes)
- How to set up memory so Claude remembers your style (45 minutes)
- How to use checkpoints to undo mistakes (45 minutes)
- How to run Claude from the terminal (30 minutes)

**By the end**: You'll have slash commands set up and Claude will know your preferences automatically.

### 🔵 Level 2: Intermediate (3-5 features learned)
**Time**: ~5 hours | **Goal**: Automate your daily workflows

You learn:
- How to create skills that auto-run when you need them (1 hour)
- How to set up hooks for automatic validation (1 hour)
- How to connect Claude to your tools via MCP (1 hour)
- How to create subagents to delegate work (1.5 hours)

**By the end**: You'll have automated workflows that handle code review, testing, docs, and more.

### 🔴 Level 3: Advanced (6-8 features learned)
**Time**: ~5 hours | **Goal**: Become a power user

You learn:
- Planning mode (how Claude thinks through complex problems)
- Advanced MCP configurations
- How to create plugins for your whole team
- How to master the CLI for scripting and CI/CD

**By the end**: You'll be orchestrating multiple agents, creating plugins others can use, and automating complex multi-step processes.

---

## The 10 Folders (What's In Each)

Each folder contains **examples, templates, and guides**. Here's what you'll find:

### 📁 01-slash-commands
**What**: Quick keyboard shortcuts for Claude

**Examples**:
- `/optimize` - finds slow parts of your code
- `/pr` - prepares pull requests
- `/commit` - writes better commit messages
- `/generate-api-docs` - makes API documentation
- `/setup-ci-cd` - sets up deployment pipelines

**How many**: 10 ready-to-use examples

**Copy them here**: `.claude/commands/`

### 📁 02-memory
**What**: Files that teach Claude about your project

**Examples**:
- `project-CLAUDE.md` - team standards (goes in your project root)
- `personal-CLAUDE.md` - your personal preferences (goes in `~/.claude/`)
- `directory-api-CLAUDE.md` - rules just for one folder

**How many**: 6 templates for different scopes

**How it works**: Claude automatically reads these when you talk to it. It's like leaving sticky notes all over your project.

### 📁 03-skills
**What**: Teach Claude to do complex things automatically

**Example skills**:
- **code-review**: Analyzes code for security, performance, quality
- **brand-voice**: Makes sure all your writing sounds like your brand
- **blog-draft**: Helps you write blog posts
- **doc-generator**: Creates documentation from code
- **refactor**: Automatically improves your code structure

**How many**: 6 complete skills with templates and scripts

**Includes**: Python scripts, checking logic, templates for output

### 📁 04-subagents
**What**: Hire specialized Claude agents to handle specific jobs

**Specialists**:
- **code-reviewer**: Reviews pull requests
- **data-scientist**: Analyzes data and creates charts
- **debugger**: Finds and fixes bugs
- **documentation-writer**: Writes clear docs
- **clean-code-reviewer**: Makes code beautiful

**How many**: 6 pre-built agents ready to hire

**How it works**: Send them a problem, they work on it, you get the answer back.

### 📁 05-mcp
**What**: Connect Claude to your other tools (GitHub, Google Drive, Slack, etc.)

**What you learn**:
- How to configure GitHub MCP
- How to connect your database
- How to access Google Drive
- How to read Slack channels

**Configuration files**: JSON configs for each tool

**How many**: 8+ integrations with examples

### 📁 06-hooks
**What**: Automatic actions that trigger before or after Claude does something

**Examples**:
- Before Claude reviews code → check that tests exist
- After Claude generates docs → validate the format
- Before Claude commits → format the code
- After Claude writes → spell-check

**How many**: 8 example hooks

**Includes**: JavaScript code that runs automatically

### 📁 07-plugins
**What**: Bundle slash commands, skills, hooks, and MCP together as a complete solution

**3 Complete Plugins**:

1. **PR Review Plugin**
   - Agents that check security, tests, and performance
   - Commands: `/review-pr`, `/check-security`, `/check-tests`
   - Use when: Someone opens a pull request

2. **Documentation Plugin**
   - Agents that write docs, generate examples, create API references
   - Commands: `/generate-api-docs`, `/generate-readme`, `/sync-docs`
   - Use when: You need documentation

3. **DevOps Plugin**
   - Agents that handle deployments, incidents, and rollbacks
   - Commands: `/deploy`, `/incident`, `/rollback`, `/status`
   - Use when: You're managing infrastructure

**How many**: 3 complete, production-ready plugins

**What's included**: Agents, commands, hooks, MCP configs

### 📁 08-checkpoints
**What**: Save points in your work so you can undo mistakes

**How it works**: Before you try something risky, create a checkpoint. If it breaks, go back.

**Includes**: Setup guide and best practices

### 📁 09-advanced-features
**What**: The powerful stuff once you've learned the basics

**Features**:
- **Planning Mode**: Claude thinks through complex problems step by step
- **Auto Mode**: Claude runs commands automatically
- **Channels**: Organize your work by topic
- **Voice Dictation**: Talk to Claude instead of typing
- **Permissions**: Control who can do what

**Includes**: Examples and use cases

### 📁 10-cli
**What**: Use Claude from your computer's terminal (command line)

**Examples**:
- `claude -p` - print mode (for scripts)
- `claude "do this thing"` - run a one-off command
- `claude --model claude-opus-4` - pick which Claude brain to use
- Piping output: `cat file.js | claude /optimize`

**Includes**: Setup guide and common patterns

---

## How To Actually Use This

### Step 1: Take The Self-Assessment Quiz

Open `LEARNING-ROADMAP.md` and answer these questions honestly:

- [ ] I can start Claude Code and have a conversation
- [ ] I've edited a CLAUDE.md file
- [ ] I've used 3+ slash commands
- [ ] I've created a custom slash command
- [ ] I've configured MCP
- [ ] I've set up hooks
- [ ] I've created subagents
- [ ] I've used print mode

**Count your checkmarks**:
- 0-2 checks → Start at **Level 1** (3 hours)
- 3-5 checks → Start at **Level 2** (5 hours)
- 6-8 checks → Start at **Level 3** (5 hours)

### Step 2: Follow Your Path

#### 🟢 Level 1 (Beginner)
Start here if you're new:

1. Read: `01-slash-commands/README.md` (30 min)
   - Copy one slash command to `.claude/commands/`
   - Try using it

2. Read: `02-memory/README.md` (45 min)
   - Copy `project-CLAUDE.md` to your project root
   - Add your team standards

3. Read: `08-checkpoints/README.md` (45 min)
   - Learn how to save and restore work

4. Read: `10-cli/README.md` (30 min)
   - Learn how to use Claude from terminal

**After Level 1**: You'll have slash commands, Claude will remember your preferences, and you can undo mistakes.

#### 🔵 Level 2 (Intermediate)
Start here if you know basic stuff:

1. Read: `03-skills/README.md` (1 hour)
   - Copy a skill to `.claude/skills/`
   - Customize it for your needs

2. Read: `06-hooks/README.md` (1 hour)
   - Copy a hook to `.claude/hooks/`
   - Set up automatic validation

3. Read: `05-mcp/README.md` (1 hour)
   - Pick a tool (GitHub, Google Drive, etc.)
   - Configure the connection

4. Read: `04-subagents/README.md` (1.5 hours)
   - Create a subagent file
   - Delegate a task to it

**After Level 2**: You'll have automated workflows running. Code review, docs, testing all happen automatically.

#### 🔴 Level 3 (Advanced)
Start here if you're already using Claude daily:

1. Read: `09-advanced-features/README.md` (2-3 hours)
   - Learn Planning Mode
   - Learn Auto Mode
   - Set up voice dictation

2. Read: `07-plugins/README.md` (2 hours)
   - Pick a plugin (PR Review, Documentation, or DevOps)
   - Customize it
   - Share with your team

3. Read: `10-cli/README.md` advanced section (1 hour)
   - Learn scripting patterns
   - Set up CI/CD automation

**After Level 3**: You're orchestrating multiple agents, creating team plugins, and automating complex processes.

### Step 3: Copy Examples Into Your Project

Everything is ready to copy. For example:

```bash
# Level 1: Copy a slash command
cp 01-slash-commands/optimize.md ~/.claude/commands/

# Level 2: Copy a skill
cp -r 03-skills/code-review/ ~/.claude/skills/

# Level 2: Set up memory
cp 02-memory/project-CLAUDE.md ./CLAUDE.md

# Level 3: Use a complete plugin
cp -r 07-plugins/pr-review/ my-pr-plugin/
```

### Step 4: Test It Works

For each thing you copy, try using it:

```bash
# Test a slash command
claude /optimize my-file.js

# Test memory (Claude should know your rules)
claude "what are our coding standards?"

# Test a skill
# (Skills auto-run when Claude detects their use case)

# Test a subagent
claude "I'm assigning this code review to @code-reviewer"
```

---

## Real-World Workflows You Can Build

Once you understand the 10 features, you can combine them into powerful workflows:

### Workflow 1: Automated Code Review
**Tools**: Slash command `/review-pr` → Subagent (code-reviewer) → Hook (check tests) → MCP (GitHub)

What happens:
1. You type `/review-pr`
2. Subagent reads your pull request
3. Hook checks that tests exist
4. Results post back to GitHub
5. Slack notifies the team

Time to build: 2 hours

### Workflow 2: Self-Documenting Code
**Tools**: Skill (doc-generator) → Hook (validate markdown) → MCP (GitHub) → Subagent (example-generator)

What happens:
1. You commit code with a comment: `// TODO: document this`
2. Skill auto-runs when Claude sees the comment
3. Claude generates docs
4. Hook checks the format is right
5. Docs automatically push to GitHub

Time to build: 1.5 hours

### Workflow 3: Incident Response Pipeline
**Tools**: Plugin (devops-automation) → Subagents (alert-analyzer, incident-commander) → MCP (Slack, PagerDuty) → Hooks (validation)

What happens:
1. Alert comes in
2. Claude analyzes it
3. Determines severity
4. Pages the right team
5. Creates incident in system
6. Posts updates to Slack
7. Tracks resolution

Time to build: 3 hours

---

## File Organization Reference

Here's how Claude Code expects files to be organized:

```
your-project/
├── .claude/                          # Claude config folder
│   ├── settings.json                 # Your settings
│   ├── CLAUDE.md                     # Project memory
│   ├── commands/                     # Slash commands
│   │   ├── optimize.md
│   │   ├── pr.md
│   │   └── commit.md
│   ├── skills/                       # Skills
│   │   ├── code-review/
│   │   └── doc-generator/
│   ├── agents/                       # Subagents
│   │   ├── code-reviewer.md
│   │   └── debugger.md
│   ├── hooks/                        # Hooks
│   │   ├── pre-review.js
│   │   └── post-commit.js
│   └── plugins/                      # Plugins
│       ├── pr-review/
│       ├── documentation/
│       └── devops-automation/
├── CLAUDE.md                         # Project standards (also here)
└── README.md                         # Your project readme
```

---

## Pro Tips

### Tip 1: Start Small
Don't try to set up everything at once. Pick ONE slash command. Get comfortable. Then add another.

### Tip 2: Test Each Thing
After copying something, test it before moving on. Make sure it works before the next thing.

### Tip 3: Use Memory Effectively
Your `CLAUDE.md` files are the foundation. Good memory = Claude does things right. Bad memory = Claude guesses.

### Tip 4: Hooks Are Safety Nets
Use hooks to prevent mistakes, not to add features. Example: "Before committing, check for console.log statements."

### Tip 5: Plugins Are for Sharing
If you build something awesome, turn it into a plugin so your team can use it too.

### Tip 6: Read The READMEs
Each folder has a detailed README. They explain not just what, but *why*. The why helps you understand when to use things.

---

## Troubleshooting

**Q: I copied a slash command but it's not showing up**
- Check it's in `.claude/commands/` not `commands/`
- Restart Claude Code
- Make sure the filename matches (e.g., `optimize.md` not `Optimize.md`)

**Q: Claude doesn't remember my rules**
- Make sure your `CLAUDE.md` is in the right place
- For projects: Put it in your project root
- For personal: Put it in `~/.claude/CLAUDE.md`
- Claude reads these automatically at startup

**Q: A skill isn't triggering**
- Check the skill's README to see when it auto-runs
- Some skills only trigger on certain keywords
- You might need to explicitly call them first

**Q: My subagent isn't getting assigned**
- Use the `@agent-name` syntax to assign
- Make sure the agent file is in `.claude/agents/`
- Check the agent's requirements in its definition file

---

## What You Can Do After Learning Everything

**By the end of Level 1** (3 hours):
- Create custom slash commands for your team's workflows
- Claude remembers your coding standards
- You can undo mistakes with checkpoints

**By the end of Level 2** (8 hours total):
- Automate code reviews (runs every pull request)
- Auto-generate documentation (runs when you commit code with TODOs)
- Validate all your work (tests, formatting, security)
- Run complex analysis with specialized agents

**By the end of Level 3** (13 hours total):
- Lead a team using unified Claude workflows
- Create plugins that your whole team uses
- Automate deployments, incident response, and monitoring
- Orchestrate multiple agents working together on complex problems
- Use Claude from scripts and CI/CD pipelines

---

## Next Steps

1. **Pick your level** (based on self-assessment)
2. **Read the Learning Roadmap** (`LEARNING-ROADMAP.md`)
3. **Start with the first module** for your level
4. **Copy ONE example** into your project
5. **Test it** to make sure it works
6. **Move to the next module**

The whole project is designed so you **learn by doing, not just reading**.

---

## Where To Get Help

Each folder has:
- `README.md` - Detailed explanation
- Example files - Copy-paste ready
- Screenshots - Visual guides
- Comments in code - Explaining what's happening

Also check:
- `QUICK_REFERENCE.md` - One-page cheat sheet
- `CATALOG.md` - Complete list of everything
- `FAQ` section in each README

---

**Happy learning! 🚀**

You're about to unlock 90% of Claude Code's power that most people never use. Start with Level 1, follow the path, and you'll be amazed at what you can automate.
