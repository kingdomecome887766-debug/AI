# Office Status — Handoff Notes

Read this at the start of every new session. Update it at the end of each one.

_Last updated: 2026-11-07_

## Working with the owner

- The owner is new to coding and learning as we build. Explain every file,
  agent and command in plain English before creating or running it, define
  technical words, and keep explanations short and practical.
- The owner often uses voice-to-text. If a word seems off, read for intent and
  confirm anything important.
- Act like a strategist: find gaps, give one clear recommendation, avoid long
  surveys of options.

## Decisions made

- **Priority:** the YouTube channel comes first. Business agents (government
  contracting, auto sales, wealth, $10k/month revenue) come later, using the same
  pattern.
- **Channel:** one channel. Christian-based but open to the general public.
  Formula: trending topics are the hook, biblical principles are the lens.
- **Output:** 2 long-form videos (20–30 min) + about 12 Shorts per week.
- **Voice:** the owner's voice on long-form; the owner's AI voice clone allowed
  on Shorts (with the YouTube synthetic-content disclosure).
- **Format:** mostly faceless; voiceover or on camera when needed.
- **Budget:** start lean (about $0/month) with free tools such as DaVinci
  Resolve, Canva, Pexels and the YouTube Audio Library. Upgrade only from earnings.

## Built so far

- `CLAUDE.md`, `office/brand.md`, 4 agents in `.claude/agents/`, the
  `/episode` command and the `outputs/` trays. See `README.md`.

## Open next steps

1. **Pick the channel name** from the 14 candidates in `office/brand.md`, then
   check its availability on YouTube.
2. **Run the first `/episode`** as a test, then tune the agents from the result.
3. Later: add the business agents; move the office onto local hardware (Phase 2);
   add voice control (Phase 3).

## Hardware (summary; the full inventory lives in the separate network-planning session)

| Role | Machine |
|---|---|
| Command center + main AI engine | Ryzen 7 9700X desktop, 128 GB RAM, RTX 5070 12 GB, 5.46 TB (name TBD) |
| YouTube studio | DESKTOP-I5KI0DB: i7-12700F, 32 GB DDR5, RTX 4060 8 GB |
| Second AI node / backup render | DESKTOP-TT5NV6R: i5-13400F, 64 GB, RTX 4060 Ti 8 GB, 2.73 TB (RAM runs at 2133 MT/s; check XMP later) |
| Mobile command station | HP Laptop 17t-cn300: i7-1355U, 32 GB, 932 GB |
| Storage and backups | Dell PowerEdge tower with iDRAC6 (exact model TBD) |
| Nodes | OptiPlex 3010 (32 GB), OptiPlex (8 GB), Dell Inspiron (16 GB), Latitude E6510, Latitude E5530, HP EliteBook convertible, Lenovo ThinkPad (model TBD) |
| Network | Cox gateway (phone/E911) → TP-Link ER605 → Grandstream GWN7721; TL-SG105 |

## Security to-dos (owner)

- Several machines have passwords or one shared PIN written on labels or sticky
  notes. Change each one, store the new ones in KeePassXC, and remove the labels.
- Change the PowerEdge iDRAC default login.
- Never paste real passwords into an AI chat.
