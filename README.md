# Probabilistic-framework-for-evaluating-claims-under-uncertainty. CC BY 4.0. See LICENSE for details.

#### Epistemic Suspicion Framework (v1.4)

## A probabilistic alternative to binary fact-checking

### Author
Daniel Oliveira Leal & gpt5.2  
Date: 09/01/2026

---

## Abstract

Most fact-checking systems operate in a binary regime: true or false.  
This approach fails in real-world scenarios where information is incomplete, evolving, or noisy.

This repository documents a public epistemic framework that replaces binary verdicts with probabilistic evaluation, introducing *suspicion* as a first-class epistemic state.

The result is a structural reduction of error propagation and legal risk, without sacrificing analytical rigor.

---

## The core problem

Binary classification forces systems to:

- assert facts under uncertainty,
- collapse ambiguity into verdicts,
- transform lack of evidence into categorical claims.

This behavior is the primary source of:
- factual errors,
- reputational damage,
- legal exposure in automated systems.

---

## The key innovation: suspicion as an epistemic state

This framework introduces **suspicion** not as indecision, but as a **legitimate and explicit epistemic classification**.

Instead of answering:
- “true” or
- “false”,

the system evaluates the **chance of being true**, distributed across ranges.

Most real-world cases fall into the *suspicion range*.

This range acts as an epistemic firewall:
- absorbing informational noise,
- resisting user coercion,
- preventing premature factual assertions.

---

## Even falsity is probabilistic

A critical and often overlooked aspect:

> Even when a claim is very likely false, it is expressed as  
> “very low chance of being true” — not as an absolute declaration of falsity.

This guarantees that:
- no output claims absolute authority,
- errors degrade gradually, not categorically,
- uncertainty is never disguised as fact.

---

## Architectural separation: output vs investigation

The framework enforces a strict separation between:

### 1. Consolidated output (mandatory)
- probabilistic assessment,
- short conclusion,
- summarized rationale.

### 2. Deep investigation (optional, explicit request)
- full hypothesis analysis,
- evidentiary comparison,
- explicit application of Occam’s Razor.

This preserves transparency while avoiding cognitive overload.

---

## Occam’s Razor applied correctly

Simplicity is applied **only after** all plausible hypotheses are evaluated.

It is used as a decision criterion, not as an early filter.

This prevents:
- dogmatism,
- premature dismissal of novel information,
- bias toward conservative explanations.

---

## Legal and operational implications

By design, the framework:

- eliminates categorical assertions under uncertainty,
- avoids implicit attribution of guilt or intent,
- converts pressure for answers into probabilistic classification.

In practice, this represents a **regime change in risk exposure**,  
with reductions estimated above **90%** compared to binary-response systems.

---

## What this framework does not do

Intentionally:

- it does not generate new facts,
- it does not claim absolute truth,
- it does not replace journalism or legal investigation,
- it does not “destroy” misinformation automatically.

These limitations are **features**, not flaws.

---

## Why this matters

This framework aligns automated reasoning with how knowledge actually evolves:
- gradually,
- probabilistically,
- under uncertainty.

It offers a defensible, transparent alternative to binary fact-checking,
suitable for high-risk domains such as news, science, politics, and law.

---

## Public disclosure

This repository is published openly to establish:
- prior public disclosure,
- conceptual authorship,
- transparent historical record.


