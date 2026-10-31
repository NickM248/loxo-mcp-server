# Candidate Brief

Generate a full briefing pack on a candidate before a call or submission.

## When to use
User asks for a brief, summary, or "everything on" a candidate before a client call, submission, or interview.

## Steps
1. Call `loxo_get_candidate_brief` with the candidate ID — this is a composite tool that pulls profile + recent activities in one shot.
2. Structure the output:
   - **Header:** Name, Title, Company, Location, LinkedIn
   - **Contact:** Email, Phone (flag if missing)
   - **Career Summary:** Current role tenure, previous 2 roles, total experience
   - **Specialty/Skills:** From Loxo tags and profile fields
   - **Activity History:** Last 5 interactions — date, type, notes summary
   - **Status:** Current pipeline stage (if on any job)
   - **Next Step:** Recommended action based on last activity
3. Keep it to one page. Offer to expand any section.

## Notes
- If candidate ID is unknown, search first using candidate-sourcing skill.
- Flag stale data (last updated >6 months ago).
- Never invent or embellish experience — use only what Loxo returns.
