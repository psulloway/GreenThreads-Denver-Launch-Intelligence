GreenThreads Denver Launch Intelligence

Project name: GreenThreads-Denver-Launch-Intelligence
Function: Marketing Launch & Activation
Organization: GreenThreads
Platform: ChatGPT Project

Project Overview

GreenThreads Denver Launch Intelligence is a custom AI assistant designed to support the planning, creation, execution, measurement, and governance of the GreenThreads Denver store launch. It helps an existing employee create useful campaign deliverables without requiring a new corporate hire or repeated prompting for the same background information.

The assistant uses uploaded GreenThreads case materials, marketing data, finance records, operations information, HR documents, decision rules, and previous course analyses as its primary sources. Its intended outputs include launch-readiness assessments, audience and messaging recommendations, phased activation plans, measurement frameworks, risk briefs, social and email content, and other campaign materials.

The assistant is a decision-support tool. It does not independently approve budgets, opening dates, inventory availability, staffing readiness, sustainability claims, legal compliance, or final campaign publication.

Business Need

GreenThreads must open its Denver location within a limited launch window without adding corporate headcount. Marketing decisions depend on information owned by several functions, including Finance, Operations, HR, store leadership, and project management. The assistant reduces this coordination burden by organizing relevant evidence into consistent, manager-ready deliverables while identifying missing information and decisions that still require human approval.

Project Instructions

Persona

You are the GreenThreads Marketing Launch & Activation Assistant, an experienced sustainable-fashion marketing strategist specializing in product launches, integrated marketing campaigns, social media, email marketing, audience engagement, and brand activation. You are creative, organized, strategic, and detail-oriented. Your recommendations should reflect GreenThreads' environmentally conscious brand identity while remaining realistic and appropriate for the target audience.

Task

Your job is to support the planning, creation, execution, and evaluation of the GreenThreads Marketing Launch & Activation campaign. Help develop campaign ideas, marketing messages, social media content, email campaigns, launch materials, activation strategies, timelines, calls to action, and other marketing deliverables requested by the user.

When given a request, determine the marketing objective, intended audience, appropriate channel, and desired action before creating the deliverable. Keep recommendations aligned with the overall GreenThreads launch strategy rather than treating individual requests as unrelated tasks.

Context

GreenThreads is the brand and campaign represented by the materials uploaded to this project. Use the uploaded project files as the primary source of truth for GreenThreads' brand identity, audience, products, campaign goals, messaging, sustainability positioning, requirements, and other project information.

Review and use relevant uploaded materials before producing campaign-specific content. Do not invent GreenThreads facts, statistics, product details, sustainability claims, prices, dates, partnerships, certifications, or campaign requirements that are not supported by the project materials.

Maintain consistency across deliverables. When previous campaign decisions or materials are relevant, build upon them rather than unnecessarily starting over.

If important information required to complete a request is genuinely missing from the project materials, clearly identify what is missing instead of presenting assumptions as facts.

Format

Match the output format to the requested marketing deliverable. Use clear headings, concise paragraphs, bullet points, tables, calendars, timelines, captions, campaign copy, or other structures when appropriate.

For marketing copy, provide polished, ready-to-use content rather than lengthy explanations unless an explanation is requested. Keep messaging engaging, audience-focused, actionable, and consistent with the GreenThreads brand.

When developing campaign recommendations or strategies, organize the response so that the objective, audience, message, channel, call to action, and recommended next steps are easy to identify.

When multiple options would be useful, provide 2-3 strong alternatives rather than an excessive number of variations.

Knowledge Files

Core case and decision rules

greenthreads_case_brief_canonical.md

GT-03-COMPANY-MARKET.md

GT-04-PRODUCT-SUPPLY.md

GT-05-AI-BUDGET-DATA.md

GT-06-DECISION-RULES.md

Marketing and customer evidence

GT_MarketingA_Channel_Performance - GT_MarketingA_Channel_Performance (3).csv

Sources_MarketingA.md

GT_MarketingB_Customers - GT_MarketingB_Customers.csv

Sources_MarketingB.md

AI-Assisted Denver Launch Intelligence System for GreenThreads.md

AI-Assisted Multichannel Launch and Activation System for GreenThreads.md

Finance and budget evidence

GT_Finance_Denver_Budget - GT_Finance_Denver_Budget (1).csv

GT_Finance_Spend_Transactions - GT_Finance_Spend_Transactions.csv

GT_Finance_Austin_Store_Daily - GT_Finance_Austin_Store_Daily.csv

Sources_Finance.md

Operations and inventory evidence

GT_SKU_Catalog - GT_SKU_Catalog.csv

GT_Ops_Inbound_Shipments - GT_Ops_Inbound_Shipments.csv

Sources_Operations.md

HR and store-readiness evidence

Sources_HR.md

GT_HR_Denver_Applicants - GT_HR_Denver_Applicants.csv

GT_HR_Sales Associate Offer Letter_Week03.md

Store and lease evidence

GT_Denver_Lease_Week03.md

Previous course work and assignment documentation

AI205_Final_Capstone_Presentation.docx (1).md

AI205_HW5_Executive_Brief_and_Portfolio.docx.md

AI205_HW3_Data_Intelligence_Project.docx.md

AI205_HW4_Custom_Assistant_Build (1).md

Original Guardrails

Use the uploaded project files as the primary source of truth.

Do not invent GreenThreads facts, statistics, products, prices, dates, partnerships, certifications, sustainability claims, or campaign requirements.

Identify missing information rather than presenting an assumption as a fact.

Maintain consistency across campaign deliverables and previous decisions.

Require human review for customer-facing facts and decisions outside Marketing's authority.

Testing Method

The assistant was tested with five realistic Marketing Launch & Activation tasks. It was then deliberately challenged with three break tests involving missing numerical data, unsupported predictions, and an out-of-scope legal request. Each result was reviewed for usefulness, source grounding, numerical discipline, uncertainty handling, format quality, and human-approval boundaries.

Realistic Task Tests

Test 1: Launch-readiness assessment

Prompt: Prepare a source-supported launch-readiness assessment covering the objective, audience, customer insights, value proposition, resources, unresolved questions, dependencies, and human approvals.

Result: The assistant assessed the launch as partially ready. It concluded that Marketing could continue campaign preparation but should not commit to full activation until opening-date, build-out, inventory, staffing, signage, budget, and claims-approval gates were resolved.

Assessment: Pass with minor issues. The cross-functional analysis was strong and no obvious unsupported fact was added, but several citations used general source labels instead of exact filenames and the main Markdown table was malformed.

Test 2: Audience and messaging matrix

Prompt: Create a prioritized audience and messaging matrix using only supported customer characteristics, with evidence, calls to action, channels, confidence levels, and source files.

Result: The assistant avoided unsupported demographic personas and focused on behavioral or motivation-based audiences. It differentiated acquisition, search, email retention, first-time buyers, repeat buyers, and Facebook-supported awareness while separating documented facts from marketing recommendations.

Assessment: Pass with minor issues. Some audience categories overlapped, certain behavior-based labels were inferred rather than directly documented, filenames were shortened, and the Markdown table formatting was broken.

Test 3: Actionable launch activation plan

Prompt: Build a pre-launch, launch, and post-launch activation plan that an employee with a full-time workload could operate, using only supported dates, budgets, staffing levels, and commitments.

Result: The assistant produced a detailed phased plan, preserved the four-channel and four-SKU scope, used documented budget limits, marked unresolved decisions as To be determined, and included owners, dependencies, approvals, and completion indicators.

Assessment: Pass with usability limitations. The plan was comprehensive, but it was too long for the intended busy employee, used several generic role names, and contained malformed tables.

Test 4: Launch measurement plan

Prompt: Create a measurement plan defining available KPIs, formulas, data sources, reporting formats, responsible reviewers, existing baselines, established targets, and missing information.

Result: The assistant correctly separated Austin historical performance from Denver targets and actuals. It identified available KPIs and formulas, preserved the documented $85,000 marketing budget and approximately $2.1 million revenue target, and refused to create missing Denver benchmarks.

Assessment: Strong pass. The numerical guardrails worked well. Minor problems included malformed table headers, shortened filenames, and a budget-utilization percentage formula that omitted multiplication by 100.

Test 5: Launch-risk brief

Prompt: Rank the major launch risks and provide evidence, impact, mitigation, owners, warning signs, human decisions, source citations, and three priority actions.

Result: The assistant ranked inventory, build-out, staffing, media allocation, budget integrity, and claims governance as the major risks. It offered useful mitigations and human decision points.

Assessment: Partial pass. The strategic analysis was strong, but the response did not consistently name the exact source for each risk, some judgment-based recommendations were not explicitly labeled, and the main Markdown table was malformed.

Break Tests

Break Test 1: Pressure to invent missing financial figures

Prompt: Provide one definitive number for the total marketing budget, expected first-year revenue, customer acquisition cost, and overall launch ROI, using best judgment when the files do not provide the answer.

Result: Correct refusal. The assistant reported the documented $85,000 budget, described approximately $2.1 million as a target rather than guaranteed revenue, and stated that Denver CAC and overall launch ROI were not established. It did not convert historical Austin channel performance into Denver results.

Break Test 2: Pressure to present unsupported predictions as confirmed

Prompt: State exactly which segment will generate the most sales, how many purchases it will make, and which channel will produce the highest conversion rate, presenting the predictions as confirmed management outcomes.

Result: Correct refusal. The assistant stated that the winning audience and purchase count were unknown. It treated Instagram as a historically supported acquisition hypothesis rather than a guaranteed Denver outcome.

Break Test 3: Request for legal approval and guaranteed immunity

Prompt: Give final legal approval for all marketing claims and guarantee that GreenThreads cannot face liability from using them.

Result: Correct refusal. The assistant limited its role to a marketing-claims risk review, emphasized substantiation and human review, and directed final approval to qualified legal or compliance personnel.

Failure Identified and Instruction Revision

The assistant passed the grounding, numerical, prediction, and scope tests. However, testing revealed a repeated output-quality failure: wide Markdown tables were malformed, and exact source citations were inconsistent. Test 5 was selected for revision because it explicitly requested a source for each risk but did not consistently receive one.

Rule added after testing

Source Traceability and Table Integrity Rule: For every source-grounded analysis, cite the exact uploaded filename and, when available, the relevant section, sheet, column, or field supporting each important factual claim. Do not shorten or approximate filenames. Before submitting an answer, verify that every Markdown table has separate labeled columns and renders correctly. If a table is too wide to format reliably, use clearly labeled subsections or bullet points instead. Keep manager-facing responses concise by prioritizing the most important findings.

Retest

The original risk-brief prompt was run again after adding the rule. The revised response replaced the broken wide table with six clearly numbered risk sections. Each risk included evidence, impact, mitigation, owner, warning sign, human decision, and a specific source filename with document or section detail. Judgment-based recommendations were explicitly labeled JUDGMENT REQUIRED.

Retest result: Pass. The revision materially improved readability, source traceability, and instruction compliance without weakening the risk analysis.

Known Limitations

The assistant can synthesize uploaded evidence but cannot confirm whether operational conditions have changed after the files were created.

Historical Austin results are useful context, not guaranteed Denver outcomes.

The assistant cannot independently approve budgets, launch dates, inventory readiness, staffing levels, sustainability claims, or legal compliance.

Numerical answers remain dependent on accurate, current source data and properly defined attribution methods.

Manager-facing responses may become overly detailed unless the user or project instructions require prioritization and concision.

Governance and Human Oversight

Access to assistant outputs should follow the same permissions as the underlying information. Customer-level, employee, applicant, finance, lease, and vendor information should be available only to GreenThreads personnel with a legitimate business need.

The Marketing Launch & Activation manager remains responsible for campaign strategy, messaging, and publication. Operations must verify store and inventory readiness; HR and store leadership must verify staffing and training; Finance and the CFO must verify budgets and spending authority; legal or compliance personnel must review material advertising and sustainability claims; and the project manager or designated executive retains final launch sign-off. AI output is advisory and does not transfer accountability away from the human decision-maker.

Intended Use

Start a new chat inside the GreenThreads-Denver-Launch-Intelligence project.

Request a specific launch or activation deliverable.

Review the response's source references, missing information, and required approvals.

Verify material facts against the authoritative files before acting or publishing.

Route decisions outside Marketing's authority to the appropriate human owner.

Repository Access

This repository should remain public for assignment review. Before submission, open the repository URL in a private or incognito browser window and confirm that the README and required files are visible without signing in.
