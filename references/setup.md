# Setup on both computers

Clone this repository, then copy the `codex-weekly-blog` directory to the local Codex skills folder, usually `~/.codex/skills/codex-weekly-blog`. Keep the Git clone separate so pulling updates cannot conflict with generated drafts. A directory symlink is another option.

Connect the Gmail plugin to the same personal Gmail account on both Codex installations. Test attachment sending on Windows and reading on Mac with a harmless Markdown note before scheduling. Plugin availability and local attachment support can vary by host; the source workflow has a plain-text body fallback.

Create two local automations in the respective Codex desktop apps. Use the Automations UI or ask Codex to create them. They need the local host available. Schedule in `Asia/Shanghai`:

- Windows, Friday 17:00: `Use $codex-weekly-blog as the source computer. Summarize this week's local Codex conversations into a privacy-filtered Markdown handoff, then send it to me through the Gmail plugin. Follow references/source.md. Do not publish.`
- Mac, Friday 17:30: `Use $codex-weekly-blog as the destination computer. Retrieve this week's work handoff from Gmail, add this Mac's Codex notes, and produce a final Markdown draft. Follow references/destination.md. Do not publish.`

If one machine misses its run, rerun that host's task manually. Check both runs for the first two weeks before trusting unattended delivery. Keep drafts and downloaded mail outside public Git repositories. Suggested location: `~/Documents/CodexBlogInbox/` on Mac and an equivalent private user directory on Windows.
