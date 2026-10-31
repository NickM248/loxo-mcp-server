# Candidate Sourcing

Search Loxo for candidates matching a role or specialty.

## When to use
User asks to find, search, or pull candidates — by name, title, specialty, company, or keyword.

## Steps
1. Call `loxo_search_candidates` with the relevant query terms.
   - Use `response_format: "summary"` for a fast overview.
   - Pass `specialty`, `title`, or keyword in the `query` field.
2. Present results as a ranked table: Name | Title | Company | Location | Last Activity.
3. If the user wants more detail on a candidate, call `loxo_get_candidate`.
4. If the user wants a full brief, trigger the candidate-brief skill.

## Notes
- Default to 20 results unless user specifies.
- Flag candidates with no recent activity (>90 days) as "cold."
- Never fabricate contact details — only surface what Loxo returns.
