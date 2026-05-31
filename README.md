# AI Meeting Assistant using n8n

## Project Overview

AI Meeting Assistant is an intelligent workflow built using n8n that automatically processes meeting notes, extracts action items, generates summaries, stores records in Notion, creates reminders in Google Calendar, and sends summary emails through Gmail.

## Problem Statement

Teams often struggle to track meeting discussions, action items, deadlines, and follow-ups after meetings.

This project automates the entire process and ensures that important decisions and tasks are never missed.

---

## Features

✅ AI-powered meeting summarization

✅ Action Item Extraction

✅ Key Decision Identification

✅ Sentiment Analysis

✅ Gmail Summary Delivery

✅ Notion Documentation

✅ Google Calendar Reminder Creation

✅ Automated Workflow using n8n

---

## Workflow Architecture

Webhook
↓
Groq LLM
↓
JSON Parser
↓
Notion Integration
↓
Google Calendar Integration
↓
Gmail Integration

---

## Technologies Used

- n8n
- Groq API
- Gmail API
- Google Calendar API
- Notion API
- JavaScript

---

## Sample Output

Summary:
The team reviewed project progress and assigned tasks.

Key Decisions:
- React selected for frontend
- Node.js selected for backend

Action Items:
- Rahul → Complete frontend by Monday
- Arjun → Prepare PPT by Friday

Sentiment:
Positive

---

## Future Improvements

- Automatic audio meeting transcription
- Zoom integration
- Google Meet integration
- Multi-user notifications
- Dashboard analytics

---

## Author

Devesh Changalasetty
