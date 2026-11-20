# Codex Weekly Blog

A two-computer Codex skill for turning selected conversations into a private weekly blog draft. Windows prepares a sanitized Markdown handoff and sends it through the Gmail plugin. Mac retrieves it, adds its own notes, and produces a final draft. Publishing is a separate choice.

## Install

Clone this repository on each computer and install the entire folder as `codex-weekly-blog` in your Codex skills directory (normally `~/.codex/skills/`). On Windows, `%USERPROFILE%\.codex\skills\codex-weekly-blog` is the typical location. Connect the Gmail plugin to the same account on both computers.

See [setup](references/setup.md) for the two Friday automations and initial mail test. Generated notes belong in private local directories and are excluded from this repository.

## Limits

The skill needs each local Codex app running when its scheduled task fires. It can only read conversations accessible to that host. Gmail attachment support may vary by plugin installation; the documented plain-text body fallback keeps the handoff usable. Do not use the workflow to transfer employer or client material without authorization.

## License

MIT.
