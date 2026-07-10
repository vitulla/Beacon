# Beacon Architecture

Beacon is built around one central concept:

Everything is a Card.

Cards never communicate directly with each other.

Instead, they communicate through Beacon.

-------------------------

Beacon Core

↓

Card Manager

↓

Cards

↓

AI Context

↓

Display

-------------------------

Core Responsibilities

• Boot Beacon
• Manage Cards
• Handle Navigation
• Handle Themes
• Manage Priorities
• Manage AI
• Manage Preferences

Cards never:

• Talk to each other
• Draw outside their own space
• Manage Wi-Fi
• Manage Audio
• Manage Touch

Those belong to Beacon Core.

-------------------------

Every Card is responsible for:

• Summary
• Details
• AI Context
• Refreshing its own data
• Reporting Priority

Nothing more.

-------------------------

Beacon Core decides:

Which Card is visible.

When Cards sleep.

When Cards wake.

When Cards refresh.

Which Card deserves attention.

-------------------------

Goal

A developer should be able to add a new Card without modifying Beacon Core.
