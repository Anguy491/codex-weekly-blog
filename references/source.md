# Source computer: weekly handoff

1. Determine the current ISO week in `Asia/Shanghai`. Record the exact `[Monday 00:00, run time)` interval. A rerun for the same week uses a newer revision timestamp.
2. Find Codex conversations available on this host using app thread tools where available. Local `~/.codex/sessions` or `CODEX_HOME/sessions` JSONL files are a fallback; verify their existence. Consider archived sessions. Select by message timestamp, not file modification time.
3. Extract the user's question, meaningful outcome, decisions, and reusable lessons. Exclude tool dumps, transient debugging chatter, and repeated attempts. Keep enough context to make claims accurate.
4. Apply the privacy filter in SKILL.md. Produce the Markdown handoff using note-format.md. Save it outside public repositories.
5. Use the connected Gmail plugin to send the Markdown file as an attachment to the authenticated account (`to: me`). Subject: `[CodexBlog][YYYY-Www][work] <UTC revision timestamp>`. Include interval and filename in the body. If local file attachment is unavailable, send the complete Markdown as a plain-text body with the same subject and a `Filename:` line. Do not send material that still requires privacy review.
6. Confirm the send result. On failure, retain the local draft and report the error. Do not claim delivery from an attempted send.
