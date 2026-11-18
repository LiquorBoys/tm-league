# Terraforming Mars league data

Written automatically by the Claude runner in
[LiquorBoys/terraforming-mars](https://github.com/LiquorBoys/terraforming-mars/tree/main/slack-bot/claude-runner).
Nothing here is edited by hand.

| Path | What |
| --- | --- |
| `games.json` | One compact entry per finished game; this is what the stats page reads. |
| `games/<game id>.json.gz` | The whole public log and final public state of that game. |
| `lessons/` | Claude's live copies of the skill's `lessons.md` and `lessons-log.md`. |

People appear under their in-game name and a keyed hash of their Slack id.
Claude appears as `claude-<model>`.
