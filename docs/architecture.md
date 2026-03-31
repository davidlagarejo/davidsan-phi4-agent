# Architecture Notes

`DavidSan` is published here as the public foundation of a larger privacy-first AI system.

## High-Level Components

- an input layer for intentionally selected user context
- a fine-tuned `Phi-4` reasoning layer
- a prompt and reformulation layer for narrative clarity and positioning
- a validation layer to reduce overexposure of sensitive information
- an execution layer supported by `n8n` workflows
- a dashboard layer for priorities, rationale, and next actions

## Fine-Tuned Model Intent

The fine-tuned `Phi-4` component is intended to prioritize proactive understanding of the user by:

- asking direct follow-up questions
- reading relevant files for grounded context
- identifying missing information
- supporting prioritization instead of only reactive answers

## Dashboard Intent

The dashboard is meant to keep the system centered on high-priority execution.

Rather than acting as a passive UI, it is designed to make priorities, fit, rationale, references, and next steps visible in one place.

The timeline is a key mechanism because it keeps attention anchored on what matters most, exposes sequencing and deadline pressure, and helps prevent important work from being displaced by noise.

## Core Principle

The system should help represent the user and move work forward without requiring exposure of identity, memory, or sensitive personal data.

## Status

This document describes the intended architecture of the public repository, not the full private implementation.
