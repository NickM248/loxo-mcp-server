# Outreach Prep

Prepare a candidate outreach message tailored to their profile and the open role.

## When to use
User wants to reach out to a candidate — email, LinkedIn, or phone intro script.

## Steps
1. Get the candidate brief (call candidate-brief skill or `loxo_get_candidate_brief`).
2. Get the job details if a specific role is being pitched (`loxo_get_job` or context from user).
3. Draft the outreach:
   - Subject line (email) or opener (LinkedIn/phone)
   - 2-3 sentences: why this role fits their background specifically
   - Clear call to action (15-min call, reply with interest)
   - Sign-off
4. Keep it under 150 words for email/LinkedIn. Phone scripts under 60 seconds.
5. Present the draft and ask for approval before logging.
6. On approval, offer to log the outreach via `loxo_log_activity`.

## Notes
- Passive candidate tone: consultative, not pushy.
- Reference specific experience from their profile — no generic templates.
- Velocity Staffing specialty focus: benefits, pension, actuarial, investment, HR/comp.
