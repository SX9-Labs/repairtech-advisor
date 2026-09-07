# RepairTech Advisor

A skill for **your** Claude or Grok. Paste a RepairTech diagnosis or inspection and get a
plain-language read — what it means, what is urgent, what to ask before you approve.

RepairTech Automotive · Kissimmee, FL · [autorepair-tech.net](https://autorepair-tech.net) ·
(407) 348-3400

This is not the bay tech GPT. It does not talk to shop systems.

**Visibility:** private until we flip it. The `.net` Git chip still points here so GTM
can count clicks. Tech-to-tech / Mech Tech / UTI courseware is a later lane — not in
this repo yet.

## Install

### Claude Code / Cowork

```bash
npx skills add SX9-Labs/repairtech-advisor
```

Or clone into your Claude skills folder:

```bash
git clone https://github.com/SX9-Labs/repairtech-advisor.git ~/.claude/skills/repairtech-advisor
```

If your Claude loader wants `SKILL.md` at the folder root:

```bash
git clone https://github.com/SX9-Labs/repairtech-advisor.git /tmp/repairtech-advisor
cp -R /tmp/repairtech-advisor/skills/repairtech-advisor ~/.claude/skills/
```

### Grok

```bash
grok plugin marketplace add SX9-Labs/repairtech-advisor
grok plugin install repairtech-advisor --trust
```

Or install the plugin straight from the repo:

```bash
grok plugin install SX9-Labs/repairtech-advisor --trust
```

Then `/repairtech-advisor` or start a session with the `repairtech-advisor` agent.

### Pi

```bash
pi install git:github.com/SX9-Labs/repairtech-advisor
```

Pi loads the skill and the `prompts/repairtech-advisor.md` template.

## What is in the box

| Piece | For |
|-------|-----|
| `skills/repairtech-advisor` | Claude, Grok, Pi — report explainer |
| `agents/repairtech-advisor.md` | Grok / Claude session agent |
| `prompts/repairtech-advisor.md` | Pi prompt template |
| `references/florida-open-tips.md` | Heat, oil, tires, rain — not a diagnosis |
| `references/maintenance-schedule.md` | Severe-service *picture*; owner's manual wins |

## ChatGPT

Same assistant, Store GPT (your ChatGPT):

https://chatgpt.com/g/g-6a4af900387881918270c5eac541825d-repairtech-automotive

## License

MIT. Shop records stay the inspection, estimate, and invoice.
