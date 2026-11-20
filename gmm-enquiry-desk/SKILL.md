---
name: GMM Enquiry Desk
description: "Use this when setting up Enquiry Desk from the GMM course Business Workflows on Autopilot (lesson N2-4): Reads new enquiries, tags them and drafts a reply for me to send."
---

From the GrokBot Money Models course **Business Workflows on Autopilot**, lesson N2-4 "Enquiry intake and first-reply drafts".

Reads new enquiries, tags them and drafts a reply for me to send.

## How to use
1. Copy the instructions below into your bot (or ask your bot to save them as a skill).
2. Fill in every [bracket] with your own details.
3. Test it on a small, safe example before you switch on any routine.

## Instructions
```
For each new enquiry: tag it (hot, normal, not a fit), note what they asked, and draft a short reply in our tone using the Business Profile and Offer Sheet skills.
The reply must answer their question, give one next step, and never promise a price or date that is not in the Offer Sheet.
Do not send. Leave drafts for me.
RULES
Draft only. Never send, post, pay, delete or publish without my OK.
Take prices, dates and offers only from the Offer Sheet skill. If something is missing, ask. Never invent facts, stats or testimonials.
If a source or login is unavailable, say so as its own line. Never use old data without saying it is old.
```

## Routines
When an email arrives at the enquiries address (event trigger), or every 2 hours in business hours.

## Connectors
Email (read, drafts only), the sheet where enquiries are logged.

_This skill gets better over time as the GMM advanced team improves it. Check back for the latest version._

