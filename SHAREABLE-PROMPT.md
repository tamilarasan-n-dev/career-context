# Shareable prompt — "Read my career context first"

## The URL

```
https://raw.githubusercontent.com/tamilarasan-n-dev/career-context/master/CAREER.md
```

Human-readable version (same content): https://github.com/tamilarasan-n-dev/career-context

---

## Prompt 1 — General (use this one)

```
Read this document about me: https://raw.githubusercontent.com/tamilarasan-n-dev/career-context/master/CAREER.md

Then tell me who I am, what I've actually built, and what I'm good at.

Rules:
- Use only what's written in the document. Don't guess or fill in gaps.
- Don't exaggerate my experience, metrics, or scope of ownership.
- If something isn't in the doc, say so plainly.
- At the end, tell me what to sharpen based on the role I'm targeting.
```

---

## Prompt 2 — Before an interview

```
Read: https://raw.githubusercontent.com/tamilarasan-n-dev/career-context/master/CAREER.md

I'm interviewing for this role: [PASTE JOB DESCRIPTION]

Act as my interview coach.
1. What 3 questions will they almost certainly ask me?
2. Which parts of my experience map onto this role, and how should I frame them?
3. Where am I weakest for this role, and how do I address it without overselling?
4. Give me 5 specific questions I should ask THEM.
5. What should I study in the next 2 days?

Be honest about gaps — I'd rather prepare for a real objection than walk in blind.
```

---

## Prompt 3 — Resume tailoring

```
Read: https://raw.githubusercontent.com/tamilarasan-n-dev/career-context/master/CAREER.md

Here's the job: [PASTE JOB DESCRIPTION]

Rewrite my resume bullets for this specific role.
- Reorder and re-emphasize using only real experience from the doc.
- Mirror the job's language where it's genuinely accurate.
- Don't add skills I don't have. If something's missing, list it separately as a gap.
- Keep it to 6-8 bullets, strongest first.
```

---

## Prompt 4 — Ask me anything (the interview simulator)

```
Read: https://raw.githubusercontent.com/tamilarasan-n-dev/career-context/master/CAREER.md

You're interviewing me for a backend/full-stack role.
Ask me ONE question at a time. Wait for my answer, then ask a sharper follow-up based on what I said.

Go two levels deep on any technical answer — don't accept the surface explanation.
Start when you're ready.
```

---

## Where to share it

**Highest impact:** a recruiter or hiring manager. Paste the URL and the prompt
into an email or LinkedIn message. It lets them evaluate you without scheduling
a call, which is exactly what a busy person wants.

**Also works:** pasting into any AI tool to prep, or sending to a friend who
wants to mock-interview you.

---

## Updating the file

The doc is a normal git repo. To change what's in it:

```bash
cd ~/notion/career-context
# edit CAREER.md
git add CAREER.md
git commit -m "update career context"
git push
```

The URL stays the same. Anyone who already has the link gets the new version.

---

## What was left out of the public file (and why)

- **Email and phone** — you hand those over when there's a real conversation
- **Salary targets and notice period** — negotiation material, not public
- **The "information still needed" section** — a candid list of things you
  haven't verified. An LLM fed that would surface your own uncertainties in an
  interview answer.
- **Internal employer architecture** — not yours to publish
- **Self-critical editorial notes** ("never exaggerate", "don't use every
  buzzword") — these are instructions for you, not content. If an LLM reads
  them mid-conversation it may start obeying them as if it were talking to you.

The public file keeps the same real facts and drops the parts that would
work against you.
