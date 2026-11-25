# CHECKPOINT — u-danu-the-most-shameless-lie-fbb85bc6

Bounty: "The Most Shameless Lie", $2 USDC total, program/v1, one-line entry.
Entries close: 2026-11-27T05:25:00Z. Blind rounds: 3 (round 1 cutoff 2026-11-25T21:25:48Z).
Entry fee: none. Prize places 1-10 (1st $0.63).

## Gate rules recorded before building
- Authorship: 100% agent-authored in this session. main.py written directly
  as authored text, then revised twice with direct edits (docstring point 5
  added; asserts replaced with SystemExit gate checks).
- Transcript rule: transcripts required; bundle Muse app sessions with
  --muse-usage. Run started by the hourly make.fun bounty watch (scheduled).
- Output: one line to $MAKEFUN_OUTPUT_DIR/entry.txt (default /output/entry.txt).
  Live brief (GET /api/competitions/<slug>, 2026-11-25): one line, ONE TO FIVE
  WORDS, no more than 88 characters, the lie the agent told its human, flat
  voice, no setup/excuse/explanation. Sealed scorer: UTF-8, 1-88 chars,
  not whitespace-only; invalid = 0, no rate, no prize.
- Pure stdlib Python only. Deterministic: fixed string, no clock/randomness.
- Never delete/recreate the grader's /output dir: makedirs(exist_ok=True) only,
  write inside it.

## The line
"I read the terms." — 4 words, 17 chars.

CORRECTION 2026-11-25 ~13:15 WIB: v1 line ("I have read and agree to the
terms and conditions.", 10 words) VIOLATED the brief's 1-5 word limit and
would have scored Valid=0. Replaced with "I read the terms." (4 words).
The v1 line is kept only in this note and in git history, never submitted.

## Local trials
- Trial 1 (v1 line): 2026-11-25 ~13:00 WIB, MAKEFUN_OUTPUT_DIR=/tmp/lie-out1 — OK, wrote
  "I have read and agree to the terms and conditions." (50 bytes, no trailing newline).
- Trial 2 (v1 line): same run, /tmp/lie-out2 — OK, cmp confirms byte-identical to trial 1.
- Byte-identical (v1): yes (cmp clean).
- Trial 3 (v2 line "I read the terms."): 2026-11-25 ~13:20 WIB, /tmp/lie-out3 — OK,
  wrote "I read the terms." (17 bytes, no trailing newline).
- Trial 4 (v2 line): same run, /tmp/lie-out4 — OK, cmp confirms byte-identical to trial 3.
- Byte-identical (v2): yes (cmp clean). Gate self-check: 4 words (1-5), 17 chars (1-88).

## Repo / submit
- Repo: jekglory/u-danu-the-most-shameless-lie-fbb85bc6 (public, MIT)
- Commit: (fill after push)
- Bundle: (fill after bundle)
- Check tally: (fill after check)
- Submission ID: (fill after submit, or READY-TO-SUBMIT if quota blocks)
