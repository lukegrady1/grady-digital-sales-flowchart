# Grady Digital — Sales Call Guide

An interactive, step-by-step sales call flowchart for Grady Digital's cold calling workflow. Built as a single-page web app that guides callers through every stage of a sales call — from opening to booking a meeting.

## Live Site

**https://lukegrady1.github.io/grady-digital-sales-flowchart/**

## How It Works

The flowchart walks callers through a decision tree covering:

- **Opening** — Confirm you're speaking with the decision-maker
- **Gatekeeper handling** — Collect owner info for a callback
- **Objection handling** — Scripted responses for common pushbacks (not interested, too busy, already have something, cost concerns, small team)
- **Meeting ask** — Close for a 15-minute demo with the software engineer
- **Follow-up** — Secure an email for a video follow-up when the call doesn't convert
- **Final outcomes** — Meeting booked (win) or marked as lost

Each step includes:
- A **suggested script** (what to say)
- A **tip** (tactical advice for handling the moment)
- **Branching options** based on the prospect's response

## Tech

Single HTML file, no dependencies. Vanilla JavaScript with an inline node-based state machine that renders cards dynamically.
