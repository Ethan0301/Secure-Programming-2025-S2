## Secure Overlay Chat

A decentralized peer-to-peer chat system that follows the class protocol. Includes at least two ethical backdoors for review and a clean version for the final submission.

## Project Info
- **Course:** Advanced Secure Programming
- **Assignment:** Advanced Secure Overlay Chat
- **Deadline (final reflective + clean code):** 26 Oct 2025, 23:59
- **Group:** Group X (replace)
- **Members:** Name A (GitHub: xxx), Name B (GitHub: xxx), Name C (GitHub: xxx)

## One-line Summary
Build a decentralized overlay chat that works with the class protocol, add ≥2 ethical backdoors, and take part in peer review and a friendly hackathon.

## Objectives (simple)
- Build a P2P overlay chat that works with the class protocol.
- No central server; the system keeps working if some nodes fail.
- Support: online user list, private chat, group broadcast, and point-to-point file transfer.
- Use secure coding: authentication, encryption, integrity checks, and session management.
- Add ≥2 ethical backdoors inside the chat system (for classmates to find only).
- Do manual and automated code reviews and write a reflection.

## Deliverables
- **Week 9 (06 Oct 2025):** Submit backdoored implementation + README.
- **Week 10 (by 19 Oct 2025):** Review three other groups and submit feedback.
- **Week 11 (by 26 Oct 2025 23:59):** Submit reflective essay (≤2000 words) + clean (no-backdoor) code + appendices (PoC, screenshots, logs).
- **Week 12:** Join the ethical hackathon and show proof-of-concept attacks in a VM.

## Features (simple)
- **Online members:** show users who are connected now.
- **Private message:** send a message to one user.
- **Group broadcast:** send a message to all users.
- **P2P file transfer:** send a file directly to another user.
- **Sessions & routing:** create/keep sessions and route messages in the overlay.
- **Basic protections:** sign/verify messages, encrypt in transit, and protect against replay.
