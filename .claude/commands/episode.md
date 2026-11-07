---
description: Run the YouTube production line - topic, script, upload kit, review
argument-hint: "[optional topic idea]"
---

Run the Kingdom Office YouTube line for one long-form episode, in order.
Topic idea from the owner (may be empty): $ARGUMENTS

1. **Trend Scout:** use the `trend-scout` agent. If the owner gave a topic idea,
   build the 3 options around it. Then **stop**, show the owner the 3 options in
   a short summary and wait for them to pick one.
2. **Scriptwriter:** use the `scriptwriter` agent on the chosen option.
3. **Clip & Package Producer:** use the `clip-packager` agent on the script.
4. **Kingdom Reviewer:** use the `kingdom-reviewer` agent on all three files.
   If the verdict is REVISE, send each fix to the named agent and review again
   (at most 2 rounds; then report what is still open to the owner).
5. Report to the owner in plain English: the episode title, the runtime, the
   number of Shorts, where the approved files are, and anything that needs
   their decision. Remind them that nothing has been published.
