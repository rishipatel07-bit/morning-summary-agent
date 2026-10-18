# Morning Brief AI

Morning Brief AI is a personal productivity agent that summarizes important emails, identifies deadlines and action items, checks the user's calendar, and delivers a personalized morning brief.

## Problem

Students and professionals often spend unnecessary time searching through emails and calendars to determine what needs attention each day.

I built this agent to automatically organize that information into one concise daily summary.

## Features

- Reviews emails received since the previous morning
- Identifies important messages
- Extracts deadlines and action items
- Separates messages requiring a response from informational messages
- Reviews the day's calendar events
- Includes event times, locations, and preparation notes
- Sends the completed brief every morning at 7:00 AM Pacific

## Workflow

```text
Gmail + Google Calendar
          |
          v
     Agent workflow
          |
          v
Email classification and summarization
          |
          v
Deadlines, action items, and calendar events
          |
          v
Personalized morning brief
          |
          v
Email delivery
