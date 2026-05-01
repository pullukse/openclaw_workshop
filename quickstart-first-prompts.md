# Quickstart First Prompts

## Purpose

This file gives students a short list of the best first prompts to run after setting up KiloClaw and uploading their starter context files.

The goal is to:
- verify the agent understands them
- verify key integrations work
- create early wins fast

These are not advanced prompts.
They are confidence-building prompts.

---

## Best first prompts after onboarding

### 1. Check whether the agent understands the user
**Prompt:**

```text
What should you know about me, how I work, and what I care about based on the files I gave you?
```

### What this tests
- `USER.md`
- `SOUL.md`
- `MEMORY.md`
- overall context quality

### Good result
The answer should sound specific, accurate, and aligned with the uploaded files.

---

### 2. Check whether the agent understands its role
**Prompt:**

```text
How should you behave in this workspace?
```

### What this tests
- `AGENTS.md`
- `SOUL.md`
- behavior rules

### Good result
The answer should reflect the workspace rules, tone, and boundaries clearly.

---

### 3. Check whether local setup notes are usable
**Prompt:**

```text
What tools, services, accounts, or environment details do you know about in this setup?
```

### What this tests
- `TOOLS.md`
- operational awareness

### Good result
The answer should reference local URLs, tools, bot accounts, or environment notes that were added.

---

### 4. Test Google integration with a safe read action
**Prompt:**

```text
Show today’s calendar events.
```

### What this tests
- Google Account integration
- GOG access
- basic calendar functionality

### Good result
The agent can read from the connected Google account successfully.

---

### 5. Test Gmail integration with a safe read action
**Prompt:**

```text
Check your Gmail inbox for unread messages.
```

### What this tests
- Gmail access
- Google auth success

### Good result
The agent can read inbox information without confusion.

---

### 6. Test Drive integration
**Prompt:**

```text
List recent files in your Google Drive.
```

### What this tests
- Drive access
- Google integration depth

### Good result
The agent can access recent Drive files from the connected bot account.

---

### 7. Test whether priorities are reflected correctly
**Prompt:**

```text
Based on what you know about me, what do you think my most important priorities are right now?
```

### What this tests
- context interpretation
- whether uploaded files are shaping decisions well

### Good result
The answer should sound grounded and relevant, not generic.

---

### 8. Test a simple high-value workflow
**Prompt:**

```text
Give me a concise morning brief for today using what you know and any connected tools that help.
```

### What this tests
- context use
- tool use
- synthesis ability
- usefulness of the starter pack overall

### Good result
The answer should feel like the beginning of a useful assistant, not a generic chatbot.

---

## Good second-round prompts

After the first validation pass, students can try:

### Google and workflow prompts
- “Draft an email to myself summarizing today’s top priorities.”
- “Find any meetings today that need prep.”
- “Search Drive for onboarding documents.”

### Agent-context prompts
- “What kind of help should you proactively give me?”
- “What recurring workflows do you think I should automate?”
- “What would be a good first custom skill for me?”

### GitHub prompts if connected
- “What GitHub capabilities do you have in this setup?”
- “Help me think through a simple backup workflow for my important files.”

---

## What bad results usually mean

If these prompts go badly, it usually points to one of these problems:

- the starter files are too vague
- the files were not uploaded or applied correctly
- the Google integration is not actually working
- the agent has too little real context
- expectations are ahead of the current setup

---

## Best instructor guidance

Students should not judge the system by one fancy prompt.
They should judge it by whether the first practical prompts work cleanly.

That is the real signal that onboarding worked.

---

## Final takeaway

Good first prompts should:
- validate context
- validate integrations
- create fast useful wins
- reveal setup problems early

That is why these prompts matter.
