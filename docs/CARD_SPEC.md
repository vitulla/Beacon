# Card Specification

## Purpose

A Card is the fundamental building block of Beacon.

Every piece of information presented by Beacon is contained within a Card.

Regardless of its function, every Card should behave consistently.

---

# Philosophy

A Card should answer one question at a glance.

If the user wants more information, they tap.

If they want an explanation, they ask AI.

---

# Every Card Must Provide

## Name

Human readable name.

Example:
Weather

---

## Icon

Simple recognizable icon.

---

## Summary

The primary information.

Must be understood in under three seconds.

---

## Details

Additional information shown after tapping.

---

## AI Context

Structured information automatically provided to the AI.

The user should never need to explain what they're looking at.

---

## Priority

Every Card reports a priority score.

0–100

Higher priority Cards appear first.

---

## Refresh Interval

Each Card decides how often it needs new information.

Examples:

Flight
2 seconds

Weather
10 minutes

Clock
1 second

---

## Status

Active

Sleeping

Offline

Updating

---

# Interaction

Idle

↓

Summary

↓

Tap

↓

Details

↓

Hold Button

↓

AI

↓

Return to previous Card

---

# Design Rules

Every Card should:

• be glanceable

• avoid clutter

• use consistent spacing

• use consistent typography

• respect the circular display

• never surprise the user

---

# Success

A user should understand a Card in under three seconds.

If they stay longer, they should discover something interesting.
