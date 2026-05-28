# EA AI Workflow Tools
**Built by Paola Moore | Executive Assistant & AI Workflow Consultant**

A portfolio of AI-powered workflow tools designed for Executive Assistants 
supporting C-suite executives. These tools were built using Claude (Anthropic), 
Google Calendar API, and Gmail API — and are actively used to support a 
simulated executive environment.



## What's Here

This repository showcases the *architecture and outcomes* of each tool. 
Full implementation files are available upon request.



### Travel Conflict Auditor
Scans an executive's Gmail inbox for travel confirmations (flights, hotels, 
car service) and cross-references them against Google Calendar to flag:
- Scheduling conflicts
- Tight layover windows
- Hotel check-in/out mismatches
- Missing ground transportation gaps

**Output:** A conflict summary email drafted to the executive + a structured 
Google Doc report.

**Relevant to:** Complex travel coordination, attention to detail, 
proactive problem-solving.



### Calendar Coordinator
A multi-mode calendar management tool that operates across two executive 
calendars simultaneously. Modes include:
- Real-time conflict detection
- Board meeting reminders
- Weekly Friday briefings
- Daily evening briefings

**Relevant to:** Complex scheduling, reactive and proactive calendar management, 
cross-functional coordination.



### Email Triage Engine
Reads unread Gmail messages, categorizes by urgency and type, drafts 
responses for routine items, and surfaces emails requiring personal attention.

**Relevant to:** High-volume inbox management, communication prioritization, 
executive support at scale.



## Approach & Philosophy

These tools were built with responsible AI practices in mind:
- Each tool includes a human review step before any action is taken
- Outputs are drafted, not auto-sent — the executive remains in control
- Built for accuracy, not speed: conflict detection prioritizes false positives 
  over missed issues

## Tech Stack
- Claude (Anthropic) — reasoning and drafting
- Google Calendar API — scheduling data
- Gmail API — email retrieval and draft creation
- Google Drive API — report generation
- Co:Work — external automation scheduling



*Connect on www.linkedin.com/in/paola-m-0335713a
