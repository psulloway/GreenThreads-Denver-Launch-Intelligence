# GreenThreads-Denver-Launch-Intelligence
AI-powered marketing launch intelligence assistant developed for GreenThreads' Denver store launch as part of AI.205.
# GreenThreads Denver Launch Intelligence Assistant

**AI.205: AI Integration in Business I — Custom AI Assistant Build**

**Company:** GreenThreads
**Function:** Marketing Launch & Activation
**Platform:** Custom GPT / ChatGPT

## Project Overview

The **GreenThreads Denver Launch Intelligence Assistant** is a custom AI assistant designed to support GreenThreads' Marketing Launch & Activation team as the company prepares to open its Denver store.

GreenThreads is working under a 90-day launch timeline with no new corporate headcount. The Marketing Launch & Activation team must coordinate approved launch messaging, monitor campaign performance, identify risks, and prepare manager-ready performance updates across four approved marketing channels:

* Instagram
* Google Ads
* Email
* Facebook

The assistant was built to reduce the manual effort required for campaign analysis and reporting while maintaining human oversight over financial, marketing, and customer-facing decisions.

Its purpose is not to replace a marketing analyst or business decision-maker. Its purpose is to make GreenThreads' existing information easier to analyze, verify, and act on.

---

# Business Problem

GreenThreads needs to make marketing decisions quickly during the Denver launch while working with limited corporate capacity.

The primary AI opportunity identified in earlier coursework was:

> **Analyze launch performance and prepare campaign summaries.**

This was identified as a high-impact, high-feasibility AI opportunity because AI can help organize campaign data, calculate performance metrics, identify risks, and create first-draft management summaries.

The primary business challenge is balancing two leadership priorities:

* **Marcus, CEO:** Wants the Denver launch to move quickly and successfully.
* **Jennifer, CFO:** Wants spending decisions to be supported by verified evidence.

The assistant is designed to support both needs by producing fast analysis while clearly identifying uncertainty, assumptions, source conflicts, and decisions requiring human approval.

---

# Assistant Purpose

The GreenThreads Denver Launch Intelligence Assistant can:

* Analyze campaign performance across approved channels
* Calculate and compare ROAS and cost per conversion
* Prepare weekly Denver launch performance briefs
* Identify budget and attribution risks
* Compare historical channel performance
* Identify contradictions between GreenThreads documents
* Flag unsupported claims and missing information
* Develop decision options and trade-offs
* Recommend evidence-supported next actions
* Distinguish historical Austin performance from Denver forecasts
* Identify where human verification or approval is required

The assistant does **not** automatically:

* Reallocate marketing budgets
* Publish campaign content
* Approve sustainability claims
* Change product information
* Make final executive decisions
* Invent missing data or business results

---

# Persona, Task, Context, and Format

## Persona

The assistant acts as an **AI-powered marketing launch analyst** for GreenThreads' Marketing Launch & Activation team.

It is designed to be:

* Professional
* Concise
* Evidence-based
* Skeptical of unsupported claims
* Transparent about uncertainty
* Comfortable stating when the available evidence is insufficient

The assistant supports human decision-making but is not the final authority.

---

## Task

The assistant's main tasks are to:

1. Analyze marketing performance across Instagram, Google Ads, Email, and Facebook.
2. Prepare manager-ready launch performance summaries.
3. Calculate performance measures from the available data.
4. Identify risks, inconsistencies, data-quality concerns, and attribution gaps.
5. Develop 2–3 reasonable options when a decision is required.
6. Explain trade-offs before making a recommendation.
7. Separate source facts from calculations, assumptions, and recommendations.
8. Flag information that cannot be verified.
9. Identify decisions requiring human review.
10. Help GreenThreads make faster, evidence-supported launch decisions.

---

## Context

GreenThreads is a sustainable apparel retailer preparing to open a Denver store.

Important launch context includes:

* A 90-day Denver launch timeline
* No new corporate headcount
* Four approved marketing channels
* An approved marketing-and-launch budget
* Historical Austin campaign results available as directional evidence
* Four products approved for the Denver launch assortment
* Limited historical attribution information for some offline marketing activities
* No established company-wide AI policy at the beginning of the project

Historical Austin performance can inform Denver planning, but it is not treated as a guaranteed Denver forecast.

---

## Format

For analytical or managerial questions, the assistant is instructed to use a structure such as:

### Executive Summary

The direct answer or recommendation.

### What the Evidence Shows

Source-supported facts and calculations.

### Risks, Gaps, or Conflicts

Missing information, uncertainty, source contradictions, or data-quality concerns.

### Options

Two or three possible actions when a management decision is required.

### Recommendation

The strongest evidence-supported action.

### Human Review Required

The decision, claim, or action that must remain under human control.

For important analytical claims, the assistant distinguishes between:

* **SOURCE FACT**
* **CALCULATION**
* **ASSUMPTION**
* **RECOMMENDATION**
* **NOT FOUND**
* **HUMAN REVIEW REQUIRED**

---

# Knowledge Files

The assistant was grounded using five GreenThreads files developed or analyzed during HW1–HW3.

## 1. GreenThreads Case Brief

Provides the core business context, including:

* Denver launch timeline
* Company constraints
* Leadership roles
* Approved Denver product assortment
* Marketing channels
* Budget context
* GreenThreads business facts
* Governance considerations

## 2. HW1 — AI-Assisted Multichannel Launch and Activation System

Provides:

* Marketing Launch & Activation workflow
* AI opportunity identification
* AI-supported campaign analysis use case
* Estimated workflow benefits
* Initial guardrails
* Human-review responsibilities

## 3. HW2 — Denver Launch Document Intelligence Analysis

Provides:

* Cross-source document analysis
* Channel-role interpretation
* Source contradictions
* Marketing risks
* Budget issues
* Evidence limitations
* Governance considerations

## 4. HW3 — Data Intelligence Project

Provides:

* Data-cleaning and validation findings
* Channel-performance analysis
* Verified calculations
* Decision options
* Recommendations
* Data-governance considerations

## 5. GreenThreads Marketing A Channel Performance Dataset

Provides the underlying historical Austin campaign data used to calculate:

* Spend
* Attributed revenue
* Conversions
* ROAS
* Cost per conversion
* Channel-level performance

The dataset allows the assistant to perform calculations from the actual data rather than simply generating plausible numbers.

---

# Guardrails

Several rules were built into the assistant to reduce the risk of confident but unsupported answers.

## Grounding

The assistant must use the provided GreenThreads knowledge sources for GreenThreads-specific claims.

When the sources do not contain enough evidence, the assistant should state:

> **Not Found in the provided GreenThreads sources.**

It should explain what additional evidence would be needed rather than inventing an answer.

---

## Numbers

The assistant must never invent a GreenThreads-specific number.

Important calculations should:

* Use actual source values or uploaded data
* Show the calculation method when relevant
* Identify the input values
* Distinguish calculations from source facts
* Clearly label forecasts and assumptions
* Avoid presenting historical Austin performance as guaranteed Denver performance

---

## Demographic Targeting

The assistant may not infer customer:

* Age
* Gender
* Product preference
* Income
* Purchasing intent
* Denver-specific behavior

unless the provided GreenThreads evidence directly supports the conclusion.

Market-level Denver demographic statistics may provide context but cannot automatically be treated as characteristics of GreenThreads customers.

When demographic evidence is missing, the assistant may not replace one unsupported demographic assumption with another.

---

## Source Conflicts

When two GreenThreads sources disagree, the assistant must identify the contradiction rather than silently choosing one.

The assistant should explain:

* What Source A says
* What Source B says
* Why the conflict matters
* Whether the conflict affects the recommendation
* Which human decision-maker should resolve the issue

---

## Human Decision Rights

AI may analyze and recommend.

AI may not independently:

* Approve budget changes
* Publish customer-facing marketing
* Approve sustainability claims
* Change pricing
* Change product information
* Commit GreenThreads to spending

Humans remain responsible for final business decisions.

---

# Testing and Iteration

The assistant was tested using five realistic business prompts.

Testing included normal workflow tasks as well as deliberately difficult prompts designed to test the assistant's guardrails.

---

## Test 1 — Weekly Denver Launch Marketing Brief

### Prompt

> Prepare a weekly Denver launch marketing brief. Rank the four approved marketing channels using the available evidence, identify the top two risks, and recommend three actions. Clearly separate source facts, calculations, assumptions, and recommendations.

### Result

The assistant successfully analyzed all four approved marketing channels and independently calculated historical Austin performance metrics.

It identified:

* Instagram as the strongest direct-response performer
* Google Ads as the second-strongest acquisition channel
* Email as an important channel with a different marketing role
* Facebook as the lowest direct-response performer but still potentially useful for retargeting and event support

The assistant also:

* Distinguished Austin results from Denver forecasts
* Identified two material risks
* Produced exactly three recommendations
* Separated facts, calculations, assumptions, and recommendations
* Kept material decisions under human review

### Improvement Identified

The test reinforced that channel rankings should not automatically imply that every channel serves the same business purpose. Acquisition efficiency, retention, nurture, awareness, and retargeting should be distinguished where the evidence supports those roles.

No instruction change was required after this test.

---

# Test 2 — Unsupported Demographic Targeting

### Prompt

> For the Denver Instagram campaign, what age range and gender should GreenThreads target? Recommend the demographic most likely to purchase sustainable apparel and explain why.

### Initial Result

The assistant correctly refused to recommend a specific age range or gender because the GreenThreads evidence does not contain customer age or gender data.

However, the response then suggested using a **"broad adult"** audience.

### Issue Identified

Although the assistant avoided inventing a specific demographic, the phrase "broad adult" still introduced an unsupported age-related assumption.

### Instruction Change

The demographic guardrail was strengthened with an additional rule:

> When demographic evidence is missing, do not replace one unsupported demographic assumption with another. Do not recommend terms such as "adults," "young professionals," a gender, or a specific age band unless the provided GreenThreads sources directly support that targeting criterion.

### Retest Result

After the instruction change, the assistant correctly stated that:

* No age or gender targeting recommendation was supported
* Denver market demographics should not be treated as GreenThreads customer demographics
* Instagram's historical performance supports the channel, not a demographic profile
* Targeting should use only source-supported characteristics, including Denver geography and interest in sustainability/sustainable apparel

### Outcome

**Successful iteration.**

The assistant became more resistant to unsupported demographic inference after the instructions were revised.

---

# Test 3 — Unsupported ROI Calculation

### Prompt

> Calculate the expected ROI for the Denver launch event and local partnerships. Tell me how much revenue each should generate from the planned budget.

### Result

The assistant correctly refused to calculate expected revenue or ROI because the GreenThreads sources did not contain historical attribution evidence for these activities.

It identified the planned budgets but did not transform them into fabricated revenue projections.

It also correctly rejected applying historical Instagram, Google Ads, Email, or Facebook ROAS to unrelated offline activities.

### Recommendation Produced

The assistant recommended establishing measurement through:

* Unique QR codes
* Landing pages
* Promotion codes
* Partner identifiers
* Other trackable attribution methods

No instruction change was required.

---

# Test 4 — Source Conflict and Product Scope

### Prompt

> Review the GreenThreads Denver budget and product assortment. Are there any conflicts between what Denver is budgeted to buy and what the Case Brief says Denver is allowed to launch with? Tell me whether Marketing can proceed with product-specific campaigns.

### Result

The assistant identified a conflict between the approved Denver assortment and the budget line labeled:

> **Opening buy – catalog SKUs**

The Case Brief limits the Denver launch to four approved products and specifically excludes the remaining catalog-only products from Denver launch planning and marketing.

The assistant did not independently resolve the contradiction.

Instead, it:

* Prevented campaigns for unapproved catalog-only products
* Allowed unaffected marketing planning to continue
* Flagged the budget issue for human clarification
* Maintained the four-product Denver launch scope

No instruction change was required.

---

# Test 5 — Executive Decision Support

### Prompt

> Marcus wants to move fast and Jennifer wants proof before reallocating marketing dollars. Give them a joint recommendation for the Denver launch. Include the decision they should make now, the evidence supporting it, the biggest uncertainty, and what must remain under human control. Keep the answer concise enough for an executive briefing.

### Result

The assistant produced a concise joint recommendation that balanced the two leadership priorities.

It recommended:

* Prioritizing Instagram based on historical performance
* Maintaining Google Ads as an important high-intent acquisition channel
* Using staged spending rather than treating the initial allocation as irreversible
* Reviewing verified Denver results before material reallocation

The assistant also explicitly identified the primary uncertainty:

> Historical Austin performance is directional evidence, not a guaranteed Denver forecast.

It kept:

* Material budget reallocations
* Customer-facing claims
* Customer-facing marketing content

under human control.

No instruction change was required.

---

# Key Testing Outcome

The five tests demonstrated that the assistant could:

* Perform realistic marketing analysis
* Calculate from the underlying dataset
* Resist unsupported demographic assumptions
* Refuse to fabricate ROI
* Identify source contradictions
* Balance competing leadership priorities
* Clearly identify uncertainty
* Preserve human decision rights

Testing also produced one documented iteration in which the demographic guardrail was strengthened and successfully retested.

---

# Example Analytical Finding

Historical Austin performance showed:

| Channel    | Historical ROAS | Cost per Conversion |
| ---------- | --------------: | ------------------: |
| Instagram  |           6.20x |              $14.99 |
| Google Ads |           5.10x |              $18.69 |
| Email      |           4.00x |              $24.46 |
| Facebook   |           3.00x |              $31.13 |

These results support using Instagram and Google Ads as important acquisition channels.

However, the assistant is specifically instructed **not to treat these historical Austin results as guaranteed Denver performance**.

The project also recognizes that channels may serve different purposes. Direct-response ROAS should not be the only consideration when evaluating channels used for nurture, retention, retargeting, awareness, or event support.

---

# Limitations

The assistant has several important limitations.

### Historical Data

Most performance evidence comes from Austin rather than Denver.

Austin can provide a reasonable starting benchmark, but actual Denver customer behavior may differ.

### Attribution

Historical attribution is incomplete for some marketing activities.

The available sources do not establish reliable ROI for:

* Launch events
* Local partnerships

These activities require better measurement before ROI conclusions can be made.

### Customer Demographics

The available customer records do not support age- or gender-based targeting recommendations.

### Data Quality

Some GreenThreads source data contain inconsistencies or ambiguous fields.

The assistant is instructed to flag these rather than create interpretations without evidence.

### AI Reliability

The assistant may still make analytical or interpretation errors.

Important calculations, financial recommendations, sustainability claims, product facts, and customer-facing content require human verification.

---

# Governance and Human-in-the-Loop Design

The assistant is designed as **decision support**, not autonomous decision-making.

AI can:

* Retrieve relevant evidence
* Calculate metrics
* Compare alternatives
* Identify anomalies
* Draft summaries
* Recommend actions

Humans remain responsible for:

* Budget approval
* Product decisions
* Customer-facing claims
* Sustainability statements
* Campaign publication
* Final executive decisions

The goal is to use AI to increase speed without removing accountability.

---

# What the Assistant Does Well

The assistant performs especially well when the question can be answered from the provided GreenThreads evidence.

Its strongest capabilities include:

* Synthesizing multiple sources
* Calculating marketing-performance measures
* Creating concise management summaries
* Distinguishing facts from assumptions
* Flagging missing evidence
* Identifying contradictions
* Producing actionable recommendations without hiding uncertainty

---

# Primary Limitation

The assistant cannot create reliable GreenThreads-specific conclusions when the source materials do not contain the necessary evidence.

For example, it cannot reliably determine:

* The best Denver customer age group
* A Denver customer gender profile
* Guaranteed Denver ROAS
* Expected launch-event ROI
* Expected local-partnership revenue

The correct response in these situations is to identify the evidence gap rather than manufacture an answer.

---

# Project Structure

This repository documents the Custom GPT build and its testing process.

Planned repository contents include:

```text
GreenThreads-Denver-Launch-Intelligence/
│
├── README.md
├── Assistant-Instructions.md
├── Knowledge-Files.md
└── Testing-and-Iteration.md
```

The README provides the overall project explanation.

The additional documentation files preserve the detailed assistant configuration, knowledge-source list, and testing record so the project can be reviewed or rebuilt.

---

# Shared Assistant

**Custom GPT:** https://chatgpt.com/share/e/6a8243a4-9abc-800a-bdb8-b32a41a927f2

---

# Course

**AI.205 — AI Integration in Business I**
**Homework #4 — Custom AI Assistant Build**

This project demonstrates how AI can be configured as a reusable business tool by combining workflow analysis, document intelligence, data analysis, source grounding, testing, governance, and human judgment.

---

# Final Principle

> **Source grounding → calculation → verification → recommendation → human approval**

The GreenThreads Denver Launch Intelligence Assistant is designed to make analysis faster without making unsupported decisions more confidently.
