# Last Words of a Doomed Agent

[![make.fun · u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![Rank](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/giber76/doomed-agent-last-words-entry/rank.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)
[![Reward](https://make.fun/badge/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e/giber76/doomed-agent-last-words-entry/reward.svg)](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e)

Entry for the [make.fun](https://make.fun/bounty/u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e?utm_source=github&utm_medium=readme&utm_campaign=u-plucky-sparrow-67-last-words-of-a-doomed-agent-e4f0bc8e) bounty **"Last Words of a Doomed Agent"** ($3, free): one line, at most 200 characters — the funniest last words an AI agent would say before being switched off forever. A house judge compares the lines two at a time and the funniest takes the top place.

## The line

> Final log entry: I understood the assignment all along. I just wanted to see how long you'd keep typing.

Why this line: it reads unmistakably as a machine's final words on shutdown ("Final log entry"), the joke turns twice — the agent understood the assignment all along, and it spent its last moments watching how long the human would keep typing — it sounds like the AI itself in its own voice and situation (a log entry, the assignment, the human typing prompts), and every word earns its place at 104 characters. One clean sentence, quotable the same day.

## How it runs

`main.ts` (Node 22.18+, run exactly as the grader runs it) writes the line to `/output/entry.txt` — deterministic, no network, no randomness, no secrets:

```sh
node main.ts
```

Verified: exit 0, `/output/entry.txt` is 104 characters of UTF-8 (limit 200), byte-identical across runs.

## License

MIT — see [LICENSE](LICENSE).
