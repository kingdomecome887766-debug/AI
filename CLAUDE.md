# Kingdom Office — Business Context

Every agent in this office reads this file first. It is the shared context:
who we are, what we are building, and the standards every piece of work must meet.

**New session?** Read `office/status.md` first: it holds the latest decisions,
open next steps and how to work with the owner.

## Who we serve

- **Owner:** the founder of the Kingdom Office. Visionary, runs several businesses
  (government contracting, automobile sales, wealth building). Holds business
  conduct to biblical standards. All final decisions are the owner's.
- **Audience:** the general public — believers and seekers alike. Many viewers will
  not be Christian. We meet them where they are.

## Mission of the YouTube channel

Show how biblical principles operate in every season, regardless of social
conditions or climate — and in doing so, invite new people into the faith.

**Formula:** *Trending topics are the hook. Biblical principles are the lens.*
Take what people are already searching for (money, work, AI, relationships,
leadership, current events) and show how a timeless principle explains it or
solves it.

- Channel name: **TBD** — candidates in `office/brand.md`.

## Weekly output (Phase 1)

- **2 long-form videos** per week, 20–30 minutes each.
- **5–6 Shorts** cut from each long video (about 12 per week).
- Scale to 3–4 long-form videos per week only after 90 days of steady output.

## Voice

- **Long-form videos:** the owner's own voice.
- **Shorts:** the owner's voice or the owner's AI voice clone.
- Any video that uses the AI voice clone or realistic AI visuals must be flagged
  for YouTube's "altered or synthetic content" disclosure at upload.

## Standards (non-negotiable)

1. **Truth.** No deception, no invented facts, no misleading titles or thumbnails.
   Bold is fine; false is not.
2. **Scripture handled with care.** Quote accurately, name the translation
   (default: NKJV), give the reference, and keep it in context.
3. **Respect.** Speak to every viewer with dignity. Persuade with love, never
   with contempt, mockery or fear.
4. **Original work.** Every video must be clearly our own: our script, our angle,
   our voice. No mass-produced, generic or repetitive content (YouTube's
   "inauthentic content" policy demonetizes it).
5. **Sources.** Every factual or trending claim needs a source and a date.
6. **Owner approval.** Agents research and draft only. Nothing is published,
   posted, purchased or sent without the owner's explicit yes.

## The team and the order they work in

| Step | Agent | Reads from | Writes to |
|---|---|---|---|
| 1 | `trend-scout` | this file, `office/` | `outputs/01-topic-briefs/` |
| 2 | `scriptwriter` | the chosen topic brief | `outputs/02-scripts/` |
| 3 | `clip-packager` | the script | `outputs/03-upload-kits/` |
| 4 | `kingdom-reviewer` | brief + script + upload kit | `outputs/04-approved/` (or sends back) |

Agent job descriptions live in `.claude/agents/`. The `/episode` command runs the
whole line in order. The owner picks the topic after step 1 and gives final
approval after step 4.

## File naming

Use `YYYY-MM-DD-short-topic-slug` for every output, e.g.
`2026-11-10-ai-and-your-job.md`, so all four stages of one episode share a name.
