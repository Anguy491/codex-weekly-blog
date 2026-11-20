# Destination computer: merged draft

1. Compute the same ISO week as the source. Search Gmail for `[CodexBlog][YYYY-Www][work]` from the authenticated account. Read candidates and choose the latest valid revision. Do not rely on unread status. Verify sender, week, interval, and filename/body marker.
2. Read the full Markdown attachment with the Gmail plugin, or the documented plain-text body fallback. Save an unmodified copy outside the site repository. If nothing valid arrived, report the missing handoff and stop the merge; do not silently create a Mac-only final.
3. Collect this Mac's Codex conversations over the same interval, applying the source workflow's selection and privacy rules.
4. Merge by project and order related developments chronologically where helpful. Lead with the main project progress. Preserve the user's reasoning, technical mechanisms, tradeoffs, evidence, and open questions from both hosts. Deduplicate repeated ideas while keeping corrections and final resolutions. Apply the detail-level privacy filter to the merged draft.
5. Save `week-YYYY-Www-final.md` in a private drafts directory. Include a title, summary, sections, and private review notes. Do not deploy unless separately authorized.
6. Record the Gmail message ID or revision locally so reruns are idempotent. If a newer revision arrives, preserve the prior final draft and regenerate.
