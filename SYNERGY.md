# Synergy

> An aggregator for AI agents: the right domain-specific agent for the job, or a mix of several, so users spend less and get better output.

---

## 1. Overview

**Synergy** is a platform for selecting the best domain-specific AI agent for the task at hand. It works as an **aggregator**, comparable to a swap aggregator or "jumper" in crypto, but for AI agents instead of tokens. Where a crypto aggregator routes a swap through the best path, Synergy routes a user's task to the best agent, or combination of agents, to complete it.

Synergy is **crypto-centric**, and its authentication and user experience reflect that (see [Section 6](#6-authentication-and-onboarding)).

---

## 2. The Problem

People routinely use LLMs and AI agents for the wrong use cases. Two examples:

- **Using the wrong tool for the domain.** Some people use Meta AI for coding, even though it is not the best fit for that kind of work.
- **Paying for a poorly matched agent.** Some people use a paid agent that is not technically dense enough for their specific purpose.

### Consequences

1. **They spend more.** They pay for tools or usage that do not fit the job.
2. **They do not get what they want.** The output is weaker than a domain-appropriate agent would have produced.

In short, users lose both money and quality because nothing helps them match a task to the agent best suited for it.

---

## 3. The Solution

Synergy is the place where users **effectively select the best domain-specific agent for the job at hand**.

### 3.1 Core idea: an aggregator for agents

- It works like a **crypto swap aggregator (a "jumper"), but for agents**.
- The user brings a task. Synergy determines which domain-specific agent is best suited to it.
- Instead of the user guessing which LLM or agent to use, Synergy makes that decision for them.

### 3.2 Mixing agents

Synergy **can also combine several AI agents** to produce the best possible output. A task does not have to be handled by a single agent. Where it helps, Synergy blends the strengths of multiple agents into one result.

### 3.3 Benefits

| Benefit | Description |
|---|---|
| **Saves tokens** | Tasks go to the agent that fits them, so tokens are not wasted on mismatched or over-powered models. |
| **Saves money** | Users stop overpaying for the wrong agent or for capabilities they do not need. |
| **Better output** | A domain-specific agent, or a mix of agents, yields results closer to what the user wants. |

---

## 4. Tiers and Monetization

Synergy will have **various tiers**. The exact structure is **to be discussed later with Claude IDE during implementation**.

### 4.1 Free tier

- The free tier is intended to **do tons of heavy lifting**.
- It should do **very much, and sufficient, work** on most LLM free tiers.
- For the majority of users and tasks, the free tier should be enough to get real value.

### 4.2 Paid tiers

- For **more complex projects**, a **paywall** comes into consideration.
- The details of where the paywall sits and what the paid tiers contain are **not yet decided** and will be worked out during implementation.

---

## 5. Product Positioning Summary

- **What it is:** an agent aggregator and router, with the ability to mix agents.
- **Who it is for:** people who use AI agents and LLMs and currently pick the wrong one for their use case.
- **What it delivers:** the best domain-specific agent (or combination) per task, with lower token usage and lower cost.
- **How it makes money:** tiered access, with a generous free tier and a paywall for more complex projects.
- **Where it lives:** a crypto-centric product.

---

## 6. Authentication and Onboarding

Because the project is crypto-centric, users should be able to sign in in two ways:

1. **Connecting their wallet.**
2. **Using their Gmail account.**

**Privy** should work for this, handling both wallet connection and email/Google sign-in.

---

## 7. Open Items (to be decided during implementation)

These are items the original brief explicitly leaves for later:

- **Tier definitions:** the exact tiers, their limits, and pricing, to be discussed with Claude IDE during implementation.
- **Paywall placement:** where "more complex projects" cross from the free tier into paid.

---

## 8. Scope of This Document

This document records the idea as described so far. The brief states: *"this should be all for now."* It will be extended as the project moves into implementation.
