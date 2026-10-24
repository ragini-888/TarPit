# TarPit ("Kamla Aunty")

> We turn every scam attempt into evidence, and make scammers pay in time.

## Problem
Digital-arrest and KYC scams target many people in India, especially the elderly. Existing tools only warn victims after the damage is done, scammers pay no cost for failed attempts, and victims are left with little usable evidence.

## Our Idea
A user forwards a scam message to our Telegram bot. An AI persona ("Kamla Aunty"), a confused and chatty victim, keeps the scammer busy and steers the conversation so they reveal UPI IDs, phone numbers and links. TarPit then links identifiers shared across chats to expose scam rings and generates a pre-filled complaint PDF for the user to file at cybercrime.gov.in / helpline 1930.

## Planned Features
- [ ] Telegram bot with goal-driven AI persona
- [ ] Scam-stage tracking
- [ ] UPI / phone / URL extraction
- [ ] Scam-ring linking graph
- [ ] Live dashboard
- [ ] Complaint PDF generator
- [ ] Scammer simulator for demos

## Tech Stack
Python, Telegram Bot API, LLM API, SQLite, NetworkX, Streamlit, ReportLab

## Safety and Ethics
- The persona never shares real personal data, sends money or clicks links
- It never threatens or hacks back; it only records what scammers volunteer
- Victim data is masked before storage
- Nothing is auto-submitted; the user files the report themselves
- This is a support tool, not legal advice

## Team
Team The Last Commit: Ragini Gupta and Jahnavi Khurana

## Status
Work in progress, built for Collosal - A Pitch
