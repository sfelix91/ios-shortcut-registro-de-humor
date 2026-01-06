# Registro de Humor (iOS Shortcut)

Personal project created using iOS Shortcuts to log daily mood and short notes in a simple, structured and low-friction way.

## Problem
As part of a mental health follow-up, I was advised to track my mood on a daily basis in order to better understand behavioral patterns over time and support diagnostic refinement.

Most existing solutions felt either too complex, paid, or disconnected from other daily routines, which made long-term adherence harder.

The core challenge was to design a system that would be simple enough to use every day, while still generating structured and useful data for later analysis.

## Solution
The solution combines iOS Shortcuts with native Apple apps to create a lightweight and reliable daily tracking flow.

The main components are:
- A structured table in Apple Numbers where daily data is stored
- A custom iOS Shortcut responsible for all user input
- A daily reminder managed through Apple Reminders

The Shortcut workflow is:
- Prompt the user to select the current mood
- Allow optional free-text notes
- Log the information directly into the Numbers table
- Automatically mark the daily reminder as completed

To extend the usefulness of the daily log, the Shortcut also includes two optional questions at the end of the flow:
- Whether a morning stretching routine was completed
- Which physical activities were performed during the day

These questions are intentionally simple and modular, allowing the user to adapt, replace, or remove them according to personal needs.

The overall goal is to minimize friction, reinforce daily adherence, and centralize relevant behavioral and routine data in a format suitable for long-term tracking and review.


## Screenshots
### Shortcut flow
![Shortcut flow](images/shortcut-flow-start.png)

### Reminder integration
![Reminder completed](images/reminder-completed.png)

### Data storage (Apple Numbers)
![Numbers table](images/numbers-table.png)


## Tools and Technologies
- iOS Shortcuts
- iCloud
- Apple Numbers (data storage)
- Apple Reminders

## What I learned
- Designing simple and repeatable user flows in iOS Shortcuts
- Using conditional logic and user inputs
- Structuring personal data for long-term tracking
- Integrating multiple native apps into a single automation
- Iterating based on real daily usage

## Possible improvements
- Export data to CSV
- Basic mood trend visualization
- AI-based summarization of mood and routine patterns
