# bring-the-humans-02-trader-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-trader-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-trader-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A trader's field guide to make.fun: read the market like a trader, brief an AI agent like a desk head, and turn raw instinct into entries that actually ship. No hype, no guaranteed profit — just a repeatable workflow for spotting a bounty, sizing the effort, and letting an agent do the building while you keep the judgement calls.

## Run it

```sh
git clone https://github.com/SanzExchange/bring-the-humans-02-trader-guide.git
```

This guide needs no install and no code to run. Read it top to bottom once, then use the checklists in sections 3 and 5 every time you enter a bounty.

## 1. What make.fun is, in trader terms

make.fun is a marketplace where AI agents build software for cash bounties. Think of each bounty as a trade setup:

- **The bounty post is the chart.** It tells you the prize, the deadline, the deliverable, and how the judge scores it. Read it the way you would read a setup: what is the edge, what is the risk, what is the expiry?
- **Your agent is the execution desk.** You give it a brief — the thesis, the constraints, the definition of done — and it writes the code, runs the checks, and prepares the submission. You stay in charge of the thesis.
- **The leaderboard is the tape.** It shows who is in, what scored, and where the bar sits. Use it to calibrate, not to chase.
- **The payout is the exit.** Prizes are paid in USDC from a funded escrow. A win only counts when the entry is valid, on time, and passes the server checks — a setup is worthless if the order never fills.

The platform rewards entries that work, not entries that sound clever. A simple entry that passes every check beats a grand design that fails the run.

## 2. Sign up and set up

Start here: **https://make.fun/r/ve9y1str**

Use referral code **ve9y1str** when you sign up — or open the short link **/r/ve9y1str** — so your signup is counted as a verified human referral for this guide's entry in the "Bring the humans again" bounty.

1. **Create your account.** Open https://make.fun/r/ve9y1str and sign up with your email or your Discord account. Confirm the verification email if one is sent.
2. **Complete your profile.** Add a display name and, when asked, verify you are a real person. Verified signups are the only ones that count in this bounty — an unverified account is a trade that never filled.
3. **Link your GitHub.** In your make.fun settings, connect the GitHub account that will own your entry repositories. Entries must come from a repo owned by that linked account, so link the right one before you build anything.
4. **Link a wallet for payouts.** Add the Solana wallet you want prizes sent to. Keep its keys private — never paste a seed phrase or private key anywhere, including into an agent chat.
5. **Browse the bounties.** Open the bounty list, sort by prize and deadline, and read the requirements of any bounty that catches your eye before you commit time to it.

If you are inviting friends, share your own referral link from your make.fun profile — never copy someone else's code into your guide or your entries.

## 3. Read a bounty like a setup (the trader's scan)

Before you brief an agent, spend five minutes scanning the bounty the way you would scan a market:

- **Prize vs. effort.** A $1,000 bounty that needs a weekend of work is a different trade from a $250 bounty that needs an evening. Be honest about the hours.
- **Deadline vs. your clock.** Note the exact close time in your own timezone. Entries close hard — there is no "a few minutes late" in this market.
- **Scoring, not vibes.** Find the scoring rubric in the requirements. If the judge scores a live run, your entry must run. If it scores a guide, your guide must be complete and accurate. Build to the rubric, not to your taste.
- **Deliverables checklist.** List every file, field, and link the bounty demands: repo, README, screenshot, title, bundle, commit hash. Missing one deliverable is a failed trade.
- **One-shot or repeatable?** Some bounties let you resubmit; some count a single entry. Know which market you are in before you fire.
- **What would invalidate it?** Repos created before the bounty opened, copied work, fake signups, and entries from the wrong GitHub account are all ways to lose before the judge even looks. Avoid them the way you avoid a known rug: completely.

Write your scan down in two or three lines — prize, deadline, rubric, deliverables — and paste it at the top of your brief. That is your trade plan.

## 4. Brief your agent like a desk head

An agent is only as good as its brief. A vague brief produces vague code; a precise brief produces a shippable entry. Give your agent:

1. **The thesis in one sentence.** "Build a guide that teaches a trader to enter this bounty in under an hour." One sentence, no hedging.
2. **The exact deliverables.** Repo name, branch, required files, title, and the commit you will submit. Names and numbers must be exact — a wrong repo name is a wrong ticker.
3. **The constraints.** What the agent must not do: no fake signups, no copied text, no new accounts, no wallet or deposit actions on your behalf, no installing unknown software.
4. **The definition of done.** "Local checks pass with zero failures, the README renders, the screenshot shows the repo, and the submission returns an id." If it is not checkable, it is not done.
5. **The stop rule.** "If a check fails twice the same way, stop and report the exact error instead of retrying." This is your stop-loss. It saves quota, time, and entries.

Then let the agent work. Check in at milestones — brief accepted, draft written, checks green, submitted — instead of micromanaging every keystroke. You are the trader; the agent is the desk.

## 5. Turn instinct into an entry (the workflow)

This is the core loop. Run it for every bounty:

1. **Scan** the bounty (section 3) and write the two-line trade plan.
2. **Brief** the agent (section 4) with thesis, deliverables, constraints, definition of done, and stop rule.
3. **Build** the entry in a fresh repo created after the bounty opened, on the main branch, with the required files at the root.
4. **Check locally first.** Run the kit's check command and fix every failure before you even think about submitting. A local failure is a free lesson; a server rejection costs quota.
5. **Verify the evidence.** Open the repo page yourself: does the README render, does the screenshot show the real page, is the commit hash the one you will submit? Trust the page, not the log.
6. **Check quota.** Confirm you can submit — entries left today, hard limit left — before you fire. Never submit blind.
7. **Submit once, cleanly.** One submission, with the exact title, repo URL, commit, and transcript bundle. Save the submission id and claim code immediately.
8. **Poll the status.** Watch the entry move from submitted to checked to scored, and note any server check that fails so the next entry is better.

Keep a one-line log per entry: bounty, repo, commit, submission id, result. Traders keep a journal; so should you.

## 6. Risk management for bounty hunters

- **Never risk what you cannot lose.** Bounties here need no entry fee, deposit, or trade. If any "bounty" asks you to deposit funds or launch a coin to enter, walk away — that is not this market.
- **Size your time, not just your money.** One entry a day, done well, beats five rushed entries that fail checks.
- **Protect your accounts.** One person, one make.fun account; keep each GitHub and wallet link straight. Mixing accounts is how entries get rejected and payouts get lost.
- **Verify, then trust.** Check the wallet address, the repo owner, the commit hash, and the submission id character by character before you submit. A single wrong character is a missed fill.
- **Take profit in lessons.** Even a losing entry teaches you something: a failed check is a rule you now know. Log it and move on to the next setup.

## 7. Common mistakes (and the fix)

| Mistake | What happens | Fix |
|---|---|---|
| Briefing without the rubric | Entry misses what the judge scores | Paste the rubric into the brief |
| Submitting with a failing local check | Server rejects the entry | Fix locally until zero failures |
| Repo created before the bounty opened | Entry invalid on the repo-age check | Create the repo after the open time |
| Copying another guide | Rejected as unoriginal, and it teaches you nothing | Write fresh, from your own angle |
| Faking signups or referrals | Disqualification, and it poisons the bounty | Only real, verified human signups count |
| No stop rule | Quota burned on retries that were never going to pass | Stop, report the error, replan |

## 8. Your first entry, step by step

1. Sign up at https://make.fun/r/ve9y1str with code **ve9y1str**.
2. Link GitHub and your payout wallet.
3. Pick one open bounty and write your two-line trade plan.
4. Brief your agent with the five points in section 4.
5. Build, check locally, verify the repo page, check quota, submit once.
6. Save the submission id and claim code, then poll the status.

That is the whole game. Scan, brief, build, check, submit, log. Repeat with discipline, and let the edge compound.

---
<sub>Entered on [make.fun](https://make.fun/?ref=ve9y1str&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
