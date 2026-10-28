# Preston Keable

**Operations and risk leader building decision-support tools with AI coding agents.**

My work spans risk programs at Amazon and global supply chain leadership.

I build software with Claude Code and Codex, combining my operations experience with AI-assisted development. I take responsibility for framing the problems, directing implementation, and evaluating whether the results meet the requirements.

## Selected work

### [Velum](https://github.com/pkkeable/Velum)

Velum demonstrates a local workflow from reusable identity through individual request review, simulated execution, dated history and encrypted backup and recovery. The preview uses fictional data and a local fake provider, making the behavior inspectable without claiming live removals.

I set the product direction, privacy boundaries, acceptance criteria and release decisions, using Claude Code and Codex for implementation, testing and review.

Start with the [case study](https://github.com/pkkeable/Velum/blob/v0.5.2/docs/CASE_STUDY.md), try the [fictional demo](https://github.com/pkkeable/Velum/tree/v0.5.2#try-the-fictional-demo), or inspect the [release and acceptance evidence](https://github.com/pkkeable/Velum/releases/tag/v0.5.2).

### [YourSet Insights](https://github.com/pkkeable/yourset-insights-demo)

A decision-support dashboard for interpreting conflicting health and training signals. It connects observations to an assessment, records the user's decision, and preserves the original evidence for later review. The public demonstration uses synthetic data.

Start with the [walkthrough](https://github.com/pkkeable/yourset-insights-demo#a-short-walkthrough), then explore the [engineering findings](https://github.com/pkkeable/yourset-insights-demo/blob/main/ENGINEERING.md) and [tested capabilities and limits](https://github.com/pkkeable/yourset-insights-demo/blob/main/docs/CAPABILITIES.md).

### [YourSet](https://www.yourset.fit/demo/case-study)

A strength-training app that replans a session when the time available changes. A deterministic engine decides what to trim, skip or pair, and every change says why. The source is private; the public demo runs the real engine on a fictional lifter's session.

I defined the problem, the rules the engine follows and the acceptance criteria, and decided what shipped. AI coding agents wrote most of the code.

Start with the [case study](https://www.yourset.fit/demo/case-study), then [try the demo](https://www.yourset.fit/demo).

## How I approach the work

I make assumptions explicit, distinguish missing evidence from negative evidence, and require verification of how a system behaves when inputs are incomplete or a workflow fails. For features that use AI, I define what it can propose, how those proposals are checked, and where a person retains the decision.
