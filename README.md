# Content Marketing Playbook

An agent skill that writes social content the way a good strategist would. Hooks, re-hooks, story scripts, 100 content formats, captions and CTAs, all built on one simple funnel:

**Attention > Interest > Trust > Action**

Works with Claude, Codex, and any AI that can read a markdown file.

## What it does

Ask for a reel, a LinkedIn post, a carousel or a month of ideas. The skill makes the AI:

- ask who it is for and what they should do next
- write 3 to 5 hooks before the body
- use a proven story or format template
- add a re-hook where attention drops
- end with one clear CTA
- run a quality check (no filler words, no em dashes, no invented facts)

## What is inside

| File | What it holds |
|---|---|
| `SKILL.md` | Core rules, workflow, hook levels, angle system, checklist |
| `references/hooks-library.md` | 107 hook structures by category |
| `references/re-hooks.md` | Lines that hold attention mid-piece |
| `references/story-templates.md` | 10 storytelling formats with fill-in flows |
| `references/formats-library.md` | 100 formats: advice, easy, opinion, relatable, storytelling |
| `references/playbook-notes.md` | Funnel and reel hook groups |
| `ALL-IN-ONE.md` | Everything above in a single file |
| `AGENTS.md` | Pointer for tools that read AGENTS.md |

## Install

**Claude (app):** download `content-marketing-playbook.skill` from Releases, then Settings > Skills > upload.

**Claude Code:**
```bash
git clone https://github.com/irslanilyas/content-marketing-playbook ~/.claude/skills/content-marketing-playbook
```

**Codex:**
```bash
# one repo
git clone https://github.com/irslanilyas/content-marketing-playbook .agents/skills/content-marketing-playbook
# all repos
git clone https://github.com/irslanilyas/content-marketing-playbook ~/.agents/skills/content-marketing-playbook
```
Then use `$content-marketing-playbook` or just describe the task.

**ChatGPT, Gemini, Cursor, others:** paste `ALL-IN-ONE.md` into the chat, a custom GPT, a Gem, or a rules file.

## Example prompts

- "Write 5 hooks for a reel about why freelancers lose clients after the first call."
- "Turn this client story into a LinkedIn post."
- "Give me 10 content ideas for a SaaS design agency using the angle system."

## Make it yours

Generic playbooks give generic posts. Add your own files next to `SKILL.md`:

`your-best-posts.md`, `your-stories.md`, `audience-language.md`, `your-opinions.md`, `good-vs-bad.md`, `never-write.md`

The skill reads them first and copies your voice over any template.

## License

MIT. Use it, change it, share it.
