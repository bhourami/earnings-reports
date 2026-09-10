---
name: Screen refresh
about: Rerun the mechanical earnings screen
title: "Screen refresh"
labels: request
---

Fill in the fields below. Everything else on this page is ignored.

request_type: screen_refresh
requested_by: chatgpt_review
note: 

<!--
Do NOT add a ticker. A screen refresh reruns the whole mechanical pipeline and
has no subject to aim at; an issue carrying a ticker is refused rather than
guessed at. Use the company research request template for a single name.

What this does: discovery across the calendars, then the section 5 market cap
and liquidity tests, then the report is rebuilt and published to this
repository.

What it cannot do, structurally rather than by promise: it calls no analyst,
opens no debate, seals nothing, assigns no classification and cannot reach the
ledger. The route runs one subprocess and that subprocess has no path to any of
those things, so no wording of a request can produce a judgement.

Mechanical eligibility is not a view. A name appearing in the result has only
cleared the cap and liquidity floors and has a scheduled event; whether it is
worth anything is a separate question this route cannot answer.

Limits: one refresh per pipeline run, since the work is identical however many
times it is asked for and each rerun spends provider quota. A failed rebuild
leaves the previous report published rather than replacing a working screen
with a broken one.

requested_by must be chatgpt_review or owner. Analysts may not file requests.
Fields such as classification, allocation, size_gbp, buy, sell or position are
refused outright.
-->
