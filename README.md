# hagent-skills

One marketplace for Hagen's Claude plugins. Each plugin lives in its own repo; this repo only lists them, so a
push to a plugin's repo is what updates it.

| Plugin | Repo | Works in |
|---|---|---|
| design-hagent | [hagenbui/design-hagent](https://github.com/hagenbui/design-hagent) | Claude Code, claude.ai, Cowork |
| storelisting-hagent | [hagenbui/storelisting-hagent](https://github.com/hagenbui/storelisting-hagent) (`plugins/storelisting-hagent`) | Claude Code, claude.ai, Cowork |
| omniroute-images | [hagenbui/omniroute-image-mcp](https://github.com/hagenbui/omniroute-image-mcp) | Claude Code on Hagen's Mac only (local SSH bridge) |

## Install

- **Claude Code:** `/plugin marketplace add hagenbui/hagent-skills`, then `/plugin install design-hagent@hagent-skills`
  (and the others). In `/plugin`, Marketplaces, turn on auto-update for hagent-skills.
- **claude.ai and Cowork (once per organization):** an Owner adds `hagenbui/hagent-skills` as a plugin marketplace in
  the organization's plugin settings and makes the plugins available. They sync from GitHub after each push.

The repos are private, so every install needs read access to them on GitHub.
