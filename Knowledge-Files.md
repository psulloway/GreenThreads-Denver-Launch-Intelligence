# GreenThreads Denver Launch Intelligence Assistant — Knowledge Files

## Purpose

The GreenThreads Denver Launch Intelligence Assistant is grounded in five GreenThreads files from the earlier AI.205 assignments.

These files provide the assistant with company context, workflow analysis, document findings, data findings, and the underlying historical marketing-performance data needed to support evidence-based recommendations.

The knowledge set was intentionally limited to materials relevant to GreenThreads' **Marketing Launch & Activation** function and the Denver store launch.

---

# Knowledge File 1 — GreenThreads Case Brief

**File:** GreenThreads Case Brief
**Role:** Core company and Denver launch source

## What It Provides

The Case Brief establishes the primary facts and constraints of the GreenThreads engagement, including:

* GreenThreads is opening its Denver store under a 90-day timeline
* No new corporate headcount is available
* The Denver opening budget totals $450,000
* Marketing and launch has an $85,000 allocation
* GreenThreads uses four marketing channels:

  * Instagram
  * Google Ads
  * Email
  * Facebook
* Denver launches with four approved products:

  * Classic Tee
  * Active Shorts
  * Bamboo Joggers
  * EcoFleece Hoodie
* Four additional GreenThreads products are catalog-only and are not approved for the Denver launch
* Marcus, CEO, prioritizes speed and successful expansion
* Jennifer, CFO, prioritizes verification and financial discipline
* GreenThreads does not have an established AI policy

## Why It Is Included

This file acts as the assistant's primary source for fixed GreenThreads facts, company constraints, leadership context, product scope, launch timing, and governance considerations.

The assistant is instructed not to modify GreenThreads fixed facts unless a newer approved source explicitly supersedes them.

---

# Knowledge File 2 — HW1: AI-Assisted Multichannel Launch and Activation System

**File:** AI-Assisted Multichannel Launch and Activation System for GreenThreads
**Role:** Workflow and AI opportunity source

## What It Provides

HW1 defines the Marketing Launch & Activation function and its responsibilities.

It documents work such as:

* Coordinating launch messaging
* Creating channel-specific campaign content
* Monitoring campaign activity
* Reviewing customer response
* Tracking channel performance
* Preparing weekly launch updates
* Reporting campaign results

HW1 also identifies several AI opportunities.

A key opportunity used in the Custom GPT design is:

> **Analyze how the launch is performing and prepare campaign summaries.**

This opportunity was identified as high impact and high feasibility.

HW1 estimated that AI-assisted analysis and reporting could reduce the manual effort required to prepare weekly campaign updates while preserving human verification.

## Why It Is Included

This file connects the assistant directly to a real GreenThreads workflow rather than making it a general-purpose marketing chatbot.

It establishes:

* What work the assistant is designed to support
* Where AI adds value
* What should remain under human control
* Initial marketing-specific AI guardrails

---

# Knowledge File 3 — HW2: Denver Launch Document Intelligence Analysis

**File:** AI-Assisted Denver Launch Intelligence System for GreenThreads
**Role:** Cross-source document analysis and business-rule source

## What It Provides

HW2 synthesizes GreenThreads launch documents and identifies decision-relevant findings across multiple sources.

Important findings include:

* Instagram produced the strongest historical short-term acquisition performance
* Google Ads performed strongly for high-intent conversion capture
* Email serves an important nurture and retention role
* Facebook may support retargeting, event communication, and local reach
* Different channel metrics should not automatically be treated as interchangeable
* Austin performance is directional evidence rather than a guaranteed Denver forecast

HW2 also identifies important risks and contradictions.

Examples include:

### Inventory Budget Conflict

The Denver budget contains a $29,300 line labeled:

> **Opening buy – catalog SKUs**

However, the Case Brief states that the four catalog-only products are not part of the Denver launch and should not be planned around, budgeted for, or marketed.

This conflict requires human clarification.

### Unsupported Demographic Targeting

The available customer evidence does not contain GreenThreads customer age or gender fields sufficient to support demographic targeting recommendations.

### Offline Attribution Gap

Historical ROI or attribution evidence is not available for:

* Denver launch event
* Local partnerships

These activities should not be assigned invented revenue or ROI figures.

## Why It Is Included

This file gives the assistant cross-source business context and helps it identify:

* Contradictions
* Missing evidence
* Unsupported assumptions
* Attribution gaps
* Business risks
* Decisions requiring human review

It also reinforces the distinction between source facts, calculations, assumptions, and recommendations.

---

# Knowledge File 4 — HW3: Data Intelligence Project

**File:** GreenThreads HW3 Data Intelligence Project
**Role:** Data analysis, verification, and recommendation source

## What It Provides

HW3 applies data cleaning, validation, analysis, and verification to GreenThreads' marketing information.

The project emphasizes an important AI principle:

> AI should perform calculations from the actual data rather than simply generating numbers that sound plausible.

HW3 supports the assistant with:

* Data-cleaning methods
* Validation procedures
* Channel comparisons
* Performance calculations
* Decision options
* Trade-off analysis
* Recommendations
* Human-verification requirements
* Governance considerations

It also reinforces the difference between:

* Historical evidence
* Calculations
* Planning assumptions
* Recommendations

## Why It Is Included

This file gives the assistant the analytical reasoning developed during HW3 and helps ensure that recommendations are connected to verified data rather than unsupported assertions.

It also provides the methodology behind the analysis so the assistant can explain how conclusions were reached.

---

# Knowledge File 5 — GreenThreads Marketing A Channel Performance

**File:** GT_MarketingA_Channel_Performance
**Role:** Underlying historical marketing-performance dataset

## What It Provides

This dataset contains historical Austin campaign performance across GreenThreads' four approved marketing channels:

* Instagram
* Google Ads
* Email
* Facebook

The file contains 30 days of performance for each of the four channels.

This provides **120 channel-day observations**.

The dataset allows calculations using actual historical GreenThreads data, including:

* Spend
* Attributed revenue
* Conversions
* ROAS
* Cost per conversion
* Channel comparisons

Historical analysis produced approximately:

| Channel    | Historical ROAS | Cost per Conversion |
| ---------- | --------------: | ------------------: |
| Instagram  |           6.20x |              $14.99 |
| Google Ads |           5.10x |              $18.69 |
| Email      |           4.00x |              $24.46 |
| Facebook   |           3.00x |              $31.13 |

Across the four channels, the analyzed Austin data contained approximately:

* **$80,000.01 in spend**
* **$400,800.05 in attributed revenue**
* **4,260 conversions**

These historical figures are used as planning evidence.

They are **not guaranteed Denver results**.

## Why It Is Included

This is the most important quantitative grounding file for the assistant.

Instead of asking the AI to recall or invent campaign numbers, the dataset allows the assistant to calculate performance using the underlying data.

This directly reduces the risk of a **confident wrong number**.

---

# Knowledge Selection Strategy

The knowledge files were selected because together they cover five distinct needs:

| Knowledge Need                        | Source                          |
| ------------------------------------- | ------------------------------- |
| Company facts and launch constraints  | GreenThreads Case Brief         |
| Workflow and AI opportunity           | HW1                             |
| Cross-document findings and conflicts | HW2                             |
| Data analysis and verification method | HW3                             |
| Underlying marketing data             | Marketing A Channel Performance |

Together, the files allow the assistant to move from:

> **Business context → workflow → document evidence → data analysis → recommendation**

This creates a more grounded assistant than relying on a single summary document.

---

# Source Priority and Conflict Handling

The assistant does not assume that every uploaded file is equally authoritative for every question.

In general:

### Fixed GreenThreads Facts

Use the **GreenThreads Case Brief** for confirmed company facts and launch constraints.

### Workflow Design

Use **HW1** for the Marketing Launch & Activation workflow and identified AI opportunities.

### Cross-Source Findings

Use **HW2** for documented contradictions, evidence gaps, and synthesized business findings.

### Analytical Method

Use **HW3** for data-validation methods, analytical findings, options, recommendations, and verification procedures.

### Numerical Calculations

Use the **Marketing A Channel Performance dataset** whenever the underlying data are available for calculation.

If two sources conflict, the assistant is instructed to flag the conflict rather than silently selecting one.

---

# Historical Evidence vs. Denver Forecasts

The Marketing A dataset contains historical results from Austin.

These results may be used to:

* Establish an initial channel hierarchy
* Identify potential strengths and weaknesses
* Build planning assumptions
* Design Denver measurement priorities

They may not be used to claim that Denver will automatically achieve the same results.

The assistant is instructed to distinguish between:

**Historical evidence:**
What occurred in Austin.

**Assumption:**
A planning choice made before Denver-specific evidence exists.

**Forecast:**
An estimate of what may occur.

**Actual Denver result:**
Performance measured after Denver activity begins.

These categories must not be treated as interchangeable.

---

# Privacy and Governance Considerations

The knowledge set was intentionally designed to minimize unnecessary exposure of sensitive data.

The assistant uses the Marketing A channel-performance dataset because it contains campaign-level performance data necessary for the analysis.

Customer-level information should be handled more cautiously.

Where possible, GreenThreads should prefer:

* Aggregated customer findings
* De-identified information
* Minimum necessary data
* Company-approved AI environments

Personally identifiable information and unnecessary customer-level records should not be uploaded to public or unapproved AI systems.

---

# Knowledge Limitations

The uploaded knowledge files do not answer every possible GreenThreads question.

Important gaps include:

* Denver-specific campaign results do not yet exist in the historical source set
* Customer age and gender are not supported for targeting recommendations
* Historical launch-event ROI is not available
* Historical local-partnership ROI is not available
* Some source documents contain contradictions or ambiguous fields
* Austin performance cannot guarantee Denver performance

When evidence is unavailable, the assistant is instructed to identify the limitation rather than manufacture an answer.

---

# Knowledge Governance Principle

The assistant's knowledge is useful only when its source boundaries remain visible.

The operating rule is:

> **Use the GreenThreads evidence that exists. Identify the evidence that does not exist. Never hide the difference.**

This principle allows the Custom GPT to accelerate analysis while keeping human judgment, verification, and decision rights intact.
