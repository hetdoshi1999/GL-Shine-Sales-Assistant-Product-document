# GL-Shine-Sales-Assistant-Product-document

---

---

## Executive Summary

Great Learning's upsell team was losing conversions — not because the product was weak, but because the way it was communicated was inconsistent. Different sales reps told different stories. New consultants rambled. Experienced ones relied too heavily on memory. The result: learners felt uncertain, refund requests climbed, and conversion rates varied wildly across the team.

Most people in the org framed this as a **training problem**. I reframed it as a **product problem** — specifically, a workflow design and communication architecture gap living inside the CRM.

I helped design and define an AI-assisted Sales Assistant module embedded directly into the SHINE CRM. The system guided reps through structured probing questions, surfaced contextual AI-generated talking points, provided rebuttal libraries, compliance guardrails, and follow-up scripts — all within the rep's existing workflow.

The result was a repeatable, scalable communication system that reduced rep variance, improved conversion consistency, and reduced refund friction across the team.

**Key outcome: ~25% increase in average conversions per team member.**

---

## Background & Business Context

Great Learning is a premium ed-tech company offering postgraduate and professional programs in Data Science, AI/ML, Cloud, and related domains — many in partnership with universities like UT Austin and Great Lakes.

Their sales model is counsellor-led: learning consultants personally engage with prospective learners over calls, WhatsApp, and email. These consultants serve a dual function — they are part advisor and part salesperson, expected to understand learner goals, pitch program value, and close enrolments.

The challenge: **this model scales poorly when left to individual skill.**

When reps handled calls independently, the quality of product communication ranged from excellent to genuinely harmful. Some reps over-promised outcomes. Others failed to address objections confidently. Many couldn't adapt their pitch when a learner worked in a niche industry or had unconventional goals.

This created a compounding problem:

- Learners who enrolled without fully understanding the product raised refund requests later
- Reps with poor objection handling lost winnable deals at the final stage
- The business couldn't scale its upsell team without scaling its quality problem simultaneously

The cost wasn't just in lost revenue. It was in **learner trust** and **brand perception** — two things that are very hard to recover in a premium ed-tech market.

---

## Problem Discovery

### What Was Actually Happening on Calls

By observing call patterns and reviewing CRM activity logs, a set of consistent failure points emerged:

**1. Inconsistent product positioning**
Different reps framed the same program in different ways. Some emphasised the UT Austin brand. Others led with placement. A few focused entirely on the curriculum. Learners comparing options received fragmented impressions of what they were buying.

**2. Weak contextualisation**
When a learner said, *"I work in healthcare IT and I'm not sure data science applies to my domain,"* most reps gave a generic response. They couldn't connect the program value to the learner's specific industry, role, or career goal in real time.

**3. Poor objection handling under pressure**
Common objections — *"the fees are too high," "I don't have enough time," "I'll check with my family"* — were handled inconsistently. Some reps caved too quickly. Others pushed too hard. Almost none had a structured approach.

**4. Compliance risk from overcommitment**
Some reps made claims that weren't accurate — implying placement guarantees, citing live faculty access that wasn't available for their program, or making fee assurances beyond their authority. This was both a legal and trust risk.

**5. New rep onboarding friction**
New learning consultants took 4–6 weeks to become conversationally confident. During that ramp period, they were often put on live calls with incomplete preparation.

### Where Drop-offs Were Happening

The sharpest drop-offs occurred in two places:

- **Post-introduction, pre-pitch** — when reps failed to ask the right probing questions and couldn't build a personalised case
- **Objection stage** — when reps lacked confident rebuttals and lost momentum

---

## Root Cause Reframing

> *"This is a training problem. We need better scripts and more coaching."*
— The default internal diagnosis
> 

That framing wasn't wrong. But it was incomplete — and it pointed toward a slow, expensive solution: more trainers, more workshops, more shadowing sessions.

The training-first approach also treats knowledge as something that lives in a rep's head. But **knowledge that lives only in a person's head doesn't scale.** It walks out the door when they do.

I reframed the problem this way:

**The root cause isn't rep skill variance. It's a missing contextual guidance layer inside the workflow.**

More specifically:

| Default Framing | Reframed Diagnosis |
| --- | --- |
| Reps aren't trained well enough | The workflow provides no real-time guidance |
| Reps don't know the product | Product knowledge isn't surfaced at the moment of need |
| Reps handle objections poorly | There's no structured rebuttal system available mid-call |
| Inconsistent messaging | No communication guardrails are embedded in the tool |
| Compliance risk from overcommitment | No in-CRM "don'ts" reference during live conversations |

The solution, therefore, wasn't to run more training sessions. It was to **build a better workflow** — one where the right information surfaces at the right moment, inside the tool reps were already using.

This is a product thinking shift: from *"change the people"* to *"change the system."*

---

## Product Thinking Framework

### Users, Goals & Constraints

| Dimension | Detail |
| --- | --- |
| **Primary User** | Sales Reps using SHINE CRM |
| **Secondary User** | Team Leads / Sales Managers reviewing quality |
| **End Beneficiary** | Learners — who receive better-quality counselling |
| **User Goal** | Close enrolments confidently and accurately |
| **Business Goal** | Increase conversion rates, reduce refund requests, reduce compliance risk |
| **Core Constraint** | Cannot disrupt active call flow — guidance must be non-intrusive and fast to access |
| **Key Risk** | Over-engineered tool that reps ignore in favour of their old habits |
| **Core Assumption** | Reps will use the tool if it's embedded in their existing CRM workflow and reduces cognitive load |

### Design Principles

- **Contextual over generic** — AI answers should vary by industry, role, and experience level, not be one-size-fits-all
- **Accessible without interruption** — information should be one tab or one click away
- **Guardrails over punishment** — better to restrict bad claims at the source than to coach after the fact
- **Progressive disclosure** — don't overwhelm reps; surface detail only when it's needed

---

## User Personas

### Persona 1 — Rahul, Experienced Consultant (3+ years)

Rahul has strong instincts but often freestyles his pitch. He's excellent with mid-funnel learners but struggles when conversations go outside his comfort zone — niche industries, unconventional goals. He doesn't use scripts. He relies on memory, which sometimes fails him on compliance details.

**Pain point:** "I know what to say, I just don't always remember the exact boundaries — especially for programs I don't cover often."

---

### Persona 2 — Divya, New Learning Consultant (2 months in)

Divya is sharp but under-confident. She freezes when learners push back on fees or timelines. She asks good probing questions but can't connect answers to program value in real time.

**Pain point:** "I know I should personalise the pitch, but I don't always know how to link what the learner says to why this program is right for them."

---

### Persona 3 — Arjun, Mid-Senior Rep (1.5 years)

Arjun is consistent but formulaic. He follows a loose script but doesn't adapt it well. His conversions are average. He's never actively misled a learner but has missed upsell opportunities because he didn't have the right language ready.

**Pain point:** "I know the product. I just need better ways to explain it for different kinds of people."

---

### Persona 4 — Priya, Career Switcher (Learner)

Priya is a marketing manager with 8 years of experience considering a move into data analytics. She's motivated but skeptical. She's comparing Great Learning with two other providers. She has specific questions about how the program applies to her non-technical background.

**Pain point:** "I need to understand what this program does *for someone like me* — not a generic pitch."

---

## Existing Workflow Problems

Before the Sales Assistant was introduced, a rep's call workflow looked like this:

1. Open lead in CRM → basic contact info visible
2. Call learner with no structured framework
3. Pitch from memory using loosely recalled talking points
4. Handle objections based on personal experience
5. Follow up manually with no guided template
6. Occasional compliance breach from over-promising

**Specific problems embedded in that workflow:**

**Cognitive overload mid-call** — reps were expected to simultaneously listen to the learner, recall product knowledge, adapt their pitch, and manage objections without any in-tool support.

**No probing framework** — most reps invented their own question structure. This meant they collected inconsistent information and couldn't build a reliable learner profile mid-call.

**No rebuttal structure** — objection handling was entirely intuitive. There was no shared library of tested responses to common objections like "the fee is too high" or "I'm not sure I have time."

**No compliance layer** — reps making restricted claims (placement guarantees, assured salary growth) had no in-CRM reference to check themselves against.

**Weak follow-up** — post-call follow-up lacked consistency. Different reps sent completely different messages, with no standardised opening or CTA.

---

## Solution Design

The core insight was this: **good sales communication is a knowledge + context + structure problem.** All three components can be systematised.

The solution was the **SHINE Sales Assistant** — a dedicated CRM module that gave reps guided, AI-assisted support across four distinct workflow phases.

### Module 1 — Probing Questions Framework

Before pitching anything, reps need a clear picture of the learner. The Sales Assistant presented a structured 8-question probing framework, collapsible for reference during a live call:

1. Introduction (scripted opener with rep name, company, and program context)
2. Work experience in years
3. Educational background
4. Company's industry
5. Job responsibilities
6. Motivation for enrolling
7. Whether they know someone who has done a similar course
8. Financial affordability check

Each question was expandable — when a rep clicked on "Introduction," they saw a fully scripted opener.

This eliminated the blank-screen moment at the start of a call and standardised the first impression across every rep.

### Module 2 — Contextual AI Answer Engine

This was the core intelligence layer of the system. After a rep inputted the learner's industry and job function using dropdown filters, the AI Answer panel generated contextual talking points specific to that learner's profile.

For example, for a learner with **12–15 years of experience in IT**, the system surfaced answers to questions like:

- *"How can a learner with 12–15 years of work experience benefit from learning Data Science?"*
- *"How can a learner with this experience leverage their past experience after becoming a data scientist?"*

The AI-generated answers emphasised domain-specific value: how their existing expertise in IT could be combined with data skills to solve complex business problems, lead data teams, and remain competitive in a rapidly changing market.

This gave reps precise, personalised talking points without requiring them to recall or construct them independently — reducing cognitive load and dramatically improving pitch relevance.

The system indicated answer availability ("AI Answers 2/2"), so reps knew when contextualised content was ready to use.

### Module 3 — Follow-Ups, Ice Breakers & Rebuttal Library

The second major tab of the Sales Assistant contained structured follow-up and objection handling support, organised into three sections:

**Follow-up Opening Pitch** — a scripted follow-up opener referencing the prior conversation, ensuring continuity and professionalism across calls.

**Ice Breakers** — context-setting openers based on whether the learner had a peer who'd done a similar course at GL, at a competitor, or had no peer reference at all. This gave reps a natural, non-pushy entry point for reconnecting.

**Rebuttals** — a categorised objection handling library covering the most common blockers:

- *Not opening up / Hesitating*
- *No time to dedicate / Have projects / Professionally busy*
- *Fees is high*
- *Deadline concern*

Each rebuttal was collapsible and expandable on demand. Reps could quickly access the right response framework without disrupting call flow.

### Module 4 — Compliance Guardrails ("Don'ts")

A dedicated compliance section listed restricted claims reps were explicitly not permitted to make during calls:

- Masters programs cannot be described as completable in an accelerated timeline
- "Placement assistance" must not be used — only "career assistance" is permitted
- No placement guarantees
- No assured percentage growth claims
- Live sessions from UT Austin faculty are not available for all programs
- Programs are not UGC or AICTE approved
- Program managers are not available on demand — they have a defined TAT
- PM team is not available 24/7
- No carrier fairs offered
- No internal installment plans

This transformed compliance from a training topic into an **embedded guardrail** — always visible, always accessible, impossible to overlook during a live call.

---

## Detailed Userflow

<img width="1648" height="811" alt="image234234" src="https://github.com/user-attachments/assets/3ec0dca4-7f78-4973-a8ad-05166f3ba04f" />


---

---

## Guardrails & Compliance Architecture

The compliance module wasn't an afterthought — it was a deliberate product decision. The "Don'ts of AIML" section (and equivalents for other programs) represented an embedded communication control layer.

**What it covered:**

| Restricted Category | Why It Matters |
| --- | --- |
| Placement guarantees | Legal liability and learner trust risk |
| Accelerated program timelines | False expectations leading to refund requests |
| UGC / AICTE approval claims | Factually incorrect, potential regulatory issue |
| Live sessions from specific faculty | Program-dependent; can't be overgeneralised |
| Percentage salary growth assurance | Unsubstantiable and potentially deceptive |
| 24/7 support availability | Operationally inaccurate; creates false expectations |
| Internal installment plans | Financial compliance issue |

**Design decision:** rather than hiding the Don'ts in a separate knowledge base, they were surfaced inside the same CRM panel the rep was already using. This reduced the chance of a compliance breach to near-zero for reps who were actively using the tool.

---

## Metrics & Impact

### Before vs. After

| Metric | Before | After |
| --- | --- | --- |
| Average conversions per consultant | Baseline | ~25% increase |
| Rep-to-rep conversion variance | High (dependent on individual skill) | Reduced significantly |
| Refund request rate | Elevated | Decreased |
| Customer complaints | Recurring | Reduced |
| New rep ramp-up time | 4–6 weeks to confidence | Shorter via guided framework |
| Compliance breach risk | Present | Mitigated by embedded guardrails |
| Pitch personalisation quality | Low–Medium | Consistently Higher |

### Operational Impact

- Onboarding new reps became faster — the tool functioned as a guided training environment, not just a sales aid
- Team leads could standardise quality expectations by pointing to the Sales Assistant as the baseline workflow
- The system created a reusable, scalable communication architecture that didn't depend on any individual rep's tenure or skill level

### Qualitative Outcomes

- Reps reported feeling more confident on calls, particularly when handling objections
- Learners received more consistent, contextualised explanations of program value
- The "introduction" scripting created a uniformly professional first impression across all calls

---

## PM Skills Demonstrated

| Skill | How It Was Applied |
| --- | --- |
| **Product Thinking** | Reframed a training problem as a workflow design problem; treated communication quality as a product surface |
| **User Research** | Observed rep behaviour, identified pain points at multiple stages of the call lifecycle |
| **Workflow Optimisation** | Redesigned the end-to-end call workflow from a blank-slate CRM tab into a structured, AI-guided experience |
| **AI-Assisted UX** | Designed contextual AI answer surfacing based on learner profile inputs — not static, not generic |
| **Information Architecture** | Organised complex content (scripts, rebuttals, AI answers, compliance) into navigable, tab-based sections with collapsible design |
| **Scalable Systems Thinking** | Built a communication system that works for a 5-person team and a 50-person team with equal reliability |
| **Cross-functional Collaboration** | Worked across sales operations, product, and compliance to align on guardrails and content |
| **Metrics-driven Decision Making** | Tied design decisions to conversion impact, refund reduction, and compliance risk |
| **Process Design** | Defined the 7-step call framework and 8-question probing structure as repeatable operational artifacts |
| **Compliance by Design** | Embedded communication restrictions directly into the tool rather than relying on training recall |

---

## My Contribution

---

### 1. Problem Identification — Spotting the Drop-off Pattern

While working closely with the upsell workflow, I identified a recurring pattern: learners were dropping off not because of lack of interest, but because product value was being communicated inconsistently across reps. Some conversations created clarity and confidence, while others left learners uncertain — resulting in lower conversions, refund requests, and customer complaints.

I mapped these issues to specific stages in the upsell journey, particularly during value articulation and objection handling, and documented the problem as a workflow-level communication gap rather than an individual performance issue.

**The PM thinking here:** I treated inconsistency as a systems problem — a sign that the communication workflow itself lacked structure and support.

---

### 2. Root Cause Reframing — From Training Problem to Product Problem

The initial assumption inside the organisation was that the issue could be solved through more training, call shadowing, and coaching sessions. I challenged that framing.

I reframed the root cause as a **product communication and positioning gap within the CRM itself**. Reps were expected to deliver high-quality, contextual conversations without any built-in guidance, structured communication flow, or compliance safeguards inside the tool they used every day.

This reframing shifted the solution from “train reps harder” to “design a scalable communication system” — enabling consistency through workflow design rather than relying entirely on individual rep capability.

---

### 3. Workflow Design — Defining the AI-Assisted Communication System

Once the problem was reframed, I moved into workflow design and requirement definition for an AI-assisted communication layer integrated into the CRM.

I defined:

- A **7-step call framework** to standardise upsell conversations from discovery to objection handling and closing
- A **structured learner input model** where reps entered details such as role, industry, experience, and career goals to generate contextualised talking points
- The **AI-assisted pitch support flow** that surfaced relevant, pitch-ready messaging tailored to the learner profile
- The **rebuttal and objection-handling libraries** categorised by common concerns such as fees, time commitment, hesitation, and urgency
- The **follow-up communication structure** to improve consistency beyond the live call
- The **compliance guardrails and restricted claims framework** embedded directly into the workflow to reduce trust and legal risk at scale

I collaborated closely with the product team to translate these workflow requirements into the CRM experience — helping define what information should appear, at which stage of the conversation, and how reps should interact with it in real time.

---

### 4. Adoption & Standardisation — Driving the Rollout

Designing the workflow was only part of the challenge. The larger challenge was driving adoption across the sales team and making the process operationally repeatable.

I positioned the AI-assisted Sales Assistant not as a replacement for rep skill, but as a system that improved pitch relevance, reduced inconsistency, and accelerated ramp-up for newer team members. I worked with team leads to establish the workflow as the standard baseline for upsell communication across the team — replacing ad-hoc pitching approaches with a more structured process.

This standardisation helped improve communication consistency at scale while contributing to stronger conversion performance, reduced refund requests, and a more reliable customer experience overall.

---

### 5. Measuring the Impact

I tracked the outcomes across four dimensions:

| Outcome | Result |
| --- | --- |
| Conversion rate per rep | ~25% increase |
| Refund requests | Reduced |
| Customer complaints | Reduced |
| Communication consistency | Standardised across the team |

Beyond the numbers, the more durable outcome was organisational: the team now had a repeatable communication process that didn't depend on any individual's tenure, memory, or mood. That's the kind of impact that compounds.

---

## Screenshots

<img width="1151" height="736" alt="image7337838" src="https://github.com/user-attachments/assets/290ddbcc-d489-402a-8b31-3f0b5797131e" />
<img width="1149" height="739" alt="image89767" src="https://github.com/user-attachments/assets/7e3c82a7-6c25-41ca-b1d0-12260bbe61fe" />

## Key Takeaways

The core insight this project reinforced is one that applies broadly to product thinking:

> **When a human process produces variable outcomes, the fix is rarely more training. It's better system design.**
> 

Reps weren't failing because they didn't care or weren't trying. They were failing because the tool gave them no structure to work within, no contextual intelligence to draw on, and no guardrails to keep them compliant. The moment the system provided those things — embedded in the workflow they were already using — the quality of communication improved structurally, not just individually.

This is what separates a product-minded approach from a people-management one: it creates outcomes that persist regardless of which rep is on the call, what mood they're in, or how long they've been at the company.

A well-designed system doesn't just help the best reps perform better. It raises the floor for everyone.

---

*Case study written for portfolio purposes. All data is based on real workflow contribution.*
