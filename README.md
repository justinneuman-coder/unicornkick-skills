# unicornkick-skills

**Use these coaches in your browser in 60 seconds:** https://unicornkick.app/coach.html

Two AI coaches that refuse to do the work for you. **UnicornKick Writer** gets you to finish the book... it never writes a sentence. **UnicornKick Ultra** gets you to your first ultra... it never fakes a mile. Open Agent Skills ([agentskills.io](https://agentskills.io)) for Claude, Codex, Gemini, Cursor, and more. Free, from the [Unicorn Kick](https://unicornkick.app) app by Ultra-Normal LLC.

## Why these are different

Everybody's building AI that does the work for you. These do the opposite. They plan, pace, and nudge, and they hold the line. The Writer will not draft your prose. The Ultra will not fake your fitness. The struggle is the point, and the coach is there to keep you in it, not to remove it.

## What's inside

- `unicornkick-dreamer/` — the soul document. Helps you find the dream you can't name yet, shrinks the first step until it's trivial, holds the line at the wall. Never picks your dream for you.
- `unicornkick-writer/` — coaches any long writing project (book, dissertation, article) on the UnicornKick method: real baseline, gradual build, recovery weeks, the Glittery Handcuffs early-stop rule. Never ghostwrites.
- `unicornkick-ultra/` — coaches a runner from their real starting point to a trail or ultra finish: true baseline, 10% builds, recovery weeks, easy miles, the "woah, cowgirl" restraint. Never fakes a mile.

## How to use them

**Just paste (any AI, 60 seconds).** Open `unicornkick-writer/SKILL.md` or `unicornkick-ultra/SKILL.md`, copy the contents, paste into Claude or ChatGPT, and go. Or grab the short paste versions at [unicornkick.app/coach.html](https://unicornkick.app/coach.html).

**Make it persist (Claude).** Drop the coach into a Claude Project's custom instructions so every chat in that project is coached. Or, on a paid plan, zip the skill folder and upload it in Settings under Capabilities so Claude loads it automatically.

**AI-native install (cross-tool).** These follow the open [Agent Skills](https://agentskills.io) standard:

​```bash
npx skills add justinneuman-coder/unicornkick-skills
​```

Or clone and drop into your skills directory:

​```bash
git clone https://github.com/justinneuman-coder/unicornkick-skills.git
cp -r unicornkick-skills/unicornkick-* ~/.claude/skills/
​```

## License

MIT. Use them, fork them, remix them. If they get you across a finish line, that's the whole point.

---

*Small steps to big dreams. No one is too old for a little glitter.* — [unicornkick.app](https://unicornkick.app)
