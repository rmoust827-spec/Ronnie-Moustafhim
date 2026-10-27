# Ronnie-Moustafhim

## Trader skills

`.claude/skills/` holds the 11 skills from
[Jakeschincariol/trader-skill](https://github.com/Jakeschincariol/trader-skill)
(commit `5189e79`, MIT, see `.claude/skills/TRADER-SKILL-LICENSE`), installed
project-local so Claude Code in this repo gets them as plain slash commands:

`/trader-copycat`, `/trader-news`, `/trader-budget`, `/trader-pelosi`,
`/trader-analyst`, `/trader-screener`, `/trader-risk`, `/trader-broker`,
`/trader-tax`, `/trader-alerts`, `/trader-rebalance`.

The tools are standard-library Python 3.8+. SEC requires a contact string: set
`SEC_USER_AGENT="Your Name you@example.com"` or put `sec_user_agent` in
`trader/config.json`. Skills write their state to a `trader/` folder here.

Not financial advice. Paper trading is the default, and nothing places an order
without an explicit yes. See the upstream README for the full workflow.

To update: re-copy `trader-*/` from a fresh clone of the upstream repo.
