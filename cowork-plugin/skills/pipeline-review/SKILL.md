# Pipeline Review

Review the candidate pipeline for a job opening.

## When to use
User asks about a job's pipeline, who is in what stage, or overall search status.

## Steps
1. Call `loxo_get_job_pipeline` with the job ID.
2. Group candidates by pipeline stage.
3. For each stage, show: Candidate Name | Days in Stage | Last Activity.
4. Flag stalled candidates (no activity >7 days in active stages).
5. Summarize: total in pipeline, stage breakdown, next recommended actions.

## Notes
- If user doesn't know the job ID, call `loxo_search_jobs` first.
- Highlight any candidates ready to advance.
- Keep the summary under one screen — offer to drill into a stage on request.
