# System Architecture

## Data Sources

The agent reads information from:

- Gmail messages received during the review period
- Google Calendar events scheduled for the current day

## Processing

The agent processes the information in four stages:

1. Retrieve recent emails and calendar events
2. Classify messages by importance
3. Extract deadlines and action items
4. Generate and deliver the morning brief

## Data Flow

```text
Gmail
  |
  v
Recent email retrieval
  |
  v
Email summarization and priority classification
  |
  +----------------------+
  |                      |
  v                      v
Deadlines          Response-required emails

Google Calendar
  |
  v
Today's events
  |
  +----------------------+
                         |
                         v
                  Morning brief
                         |
                         v
                    Email delivery
