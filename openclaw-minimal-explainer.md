# Minimal `openclaw.json5` Explainer

## Purpose

This companion note explains the minimal config example.

The goal is not to show every possible setting.
The goal is to help students understand the smallest practical config shape.

---

## What this example includes

### `gateway`
Controls how OpenClaw runs locally.

### `agents.defaults.workspace`
Tells OpenClaw where the main workspace lives.

### `agents.defaults.model.primary`
Sets the default model for the agent.

### `session.dmScope`
Controls how direct-message session continuity works.

### `channels.discord`
Shows a very simple example of enabling a Discord connection with an environment variable token.

---

## Why this example matters

Students are often overwhelmed by large real-world config files.
A minimal example helps them see the skeleton first:
- gateway
- agent defaults
- session behavior
- one channel

That makes the larger config easier to understand later.

---

## Teaching note

This is a learning example, not a full production setup.
A real config may also include:
- auth
- memory
- hooks
- skills config
- plugins config
- model provider config
- more channels
