---
title: "ReturnOnTalent AI — how it works"
description: "How ReturnOnTalent AI works at the level a product or engineering reader needs — the run pipeline, the auditability rules, the bring-your-own-model option and the data principles — without disclosing proprietary algorithms, prompts or scoring logic."
---

# How it works

This page describes the design of ReturnOnTalent AI at the level a product or engineering reader needs to evaluate it — the pipeline, the auditability rules, the deployment options and the data principles. It deliberately does not describe the algorithms, the prompts, the scoring weights or the evaluation logic; those are proprietary and are not part of this public repository.

## The run pipeline

One workflow, from raw data to board-ready answer.

1. **Data.** Import your people data the way you already hold it — map the columns once, validate before anything runs. Nothing is pre-populated, nothing is trained on anyone else's workforce.
2. **Run.** Choose the population and the modules, see the estimated cost, then launch. Your data, your results.
3. **Attrition.** A score per employee, with risk bands and the factors behind each score. See who is at risk months before a resignation.
4. **Hidden Talent.** A nine-dimension view of performance and potential, mapped to what each person wants next. Find the talent you already paid for before you hire from outside.
5. **Sentiment.** An employee sentiment index that separates what people feel from what the environment causes — with the verbatim evidence behind every score. Listen without surveilling.
6. **Executive Report.** One consolidated, auditable summary that unites attrition, mobility and sentiment — the CHRO and the CFO read from the same page.

## Auditability: two rules, built in from the start

- **No score without proof.** Every score cites its source — the field and the evidence behind it. You can challenge a number and get an answer. That is the difference between a retention dashboard and a retention decision.
- **No score without a version.** Every output carries the model, the prompt version, the weights and the date behind it. Results stay auditable, run after run.

These two rules are the product. A retention number you cannot trace is an opinion; a retention number you can trace is a decision.

## Your model, your choice

ReturnOnTalent AI runs on the language model provider you already trust.

- **Bring your own keys.** Keep your people data where your compliance requires it, and your provider bills you directly.
- **Or let us manage the models.** We run them for you; the engine is the same either way.

Either way, your data is not used to train anyone else's model.

## Data principles

- **Nothing pre-populated.** The modules run on the workforce data you already hold.
- **Nothing trained on anyone else's people.** Your data stays your data.
- **Identifiers are pseudonymised** at ingestion, so no individual is exposed in the pipeline.
- **Compliance first.** ReturnOnTalent is designed to comply with PDPA (Singapore) and GDPR (European Union). HR governs the process.

## What is not disclosed here

The following remain proprietary to WeLinkTalent Pte Ltd and are intentionally absent from this repository:

- the machine-learning algorithms and feature engineering;
- the prompts and prompt versions;
- the scoring weights and evaluation logic;
- the internal service architecture.

## Where this fits

ReturnOnTalent AI sits alongside your HRMS — Workday, SuccessFactors and others — and adds the retention layer those systems do not cover. It is not an ATS and not a job board.

[Back to the overview](../)
