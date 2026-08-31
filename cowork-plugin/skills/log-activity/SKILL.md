# Log Activity

Record a recruiter activity against a candidate in Loxo.

## When to use
User says they called, emailed, left a voicemail, had a conversation, or wants to note something on a candidate.

## Steps
1. Confirm the candidate (by name or ID).
2. Ask for any missing details: activity type, date (default today), notes.
3. Call `loxo_log_activity` with candidate ID, type, date, and notes.
4. Confirm logged and show the activity summary.

## Activity Types
- Call | Email | LinkedIn Message | Voicemail | Meeting | Note | Text

## Notes
- Keep notes factual and concise.
- If candidate ID is unknown, search first.
- After logging, ask if the candidate's pipeline stage should be updated.
