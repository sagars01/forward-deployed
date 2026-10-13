# The Case — Mehra & Cole LLP

Mehra & Cole LLP did not set out to buy artificial intelligence. It set out to stop losing money on work it was good at. This is the briefing pack for your first deployment: the client, the real problem, and the contract you will be held to.

```
Mehra & Cole: a diligence model that no longer pays
├── The firm:                 a mid-market M&A practice built on due diligence
├── What they asked for:      "an AI tool" (a solution, not a problem)
├── Five conversations:       trust, people, money, security, the report
├── The problem underneath:   one cause, four consequences, the constraints
├── The SOW:                  what will be done, measured and checked
├── What was promised:        one goal, four criteria, explicit limits
└── Your assignment:          the engagement becomes yours on Monday
```

Each section fills one branch. The case stops short of any solution; later chapters build it.

## The firm

By the time it approached Inherent Labs, the firm had lost two pitches in six months, written off record diligence work, and nearly been embarrassed on a deal. Together these convinced the managing partner that its document review no longer worked, and that she did not fully understand why.

- **History:** Anjali Mehra founded it in Mumbai in the 1990s as a four-lawyer corporate boutique. Daniel Cole, a New York lawyer who advised American companies investing in India, joined as name partner in 2011 to open Manhattan.
- **Size:** 320 lawyers, 41 partners; Mumbai, Delhi, Bengaluru and New York.
- **Core practice:** Corporate and M&A, about 110 lawyers, roughly sixty mid-market deals a year ($20 million to $300 million). Two-thirds involve private equity; about two in five are India–US. Respected, and quietly less profitable every year.

### What due diligence is

The engagement turns on **legal due diligence**: the buyer's lawyers review the target's documents for anything that should change the price, structure or decision to proceed.

- **The data room:** a secure online repository of the target's documents, with time-limited access. A mid-market room holds 3,000 to 8,000, mostly commercial contracts.
- **The key clause:** **change of control**, letting a counterparty terminate or renegotiate if ownership changes. With a major customer, it can put much of the revenue at risk on closing day. Also: assignment limits, exclusivity, non-competes, unlimited liabilities, unusual termination rights.
- **The output:** a **red-flag report** listing each material issue, where it was found, how serious it is and the remedy (price adjustment, indemnity, or a consent condition before closing). It is what a PE investment committee reads before committing hundreds of millions.
- **The Mehra & Cole pipeline:** a partner leads, a senior associate runs the work, and four to six juniors split the data room, logging findings in **the tracker**, a shared spreadsheet with one row per document and a column per issue type. The senior associate consolidates; the partner reviews what looks material.
- **The clock:** a median eighteen working days to a partner-ready report (firm estimate), much of it at night.

This pipeline has barely changed in fifteen years. Every problem in the case sits somewhere along it.

## What the firm asked for

The request arrived as a solution. Arjun Sen, engagement partner at Inherent Labs, an applied AI company that embeds engineers with its clients, was introduced through a PE operating partner and spoke to Anjali by video.

"I'll be direct," she said. "We need an AI tool for due diligence. Every firm our size is buying one, and the one we bought two years ago is shelfware. How quickly can you put it in?"

"Before I answer that," Arjun said, "what would be different in a year if it worked?"

After a long pause: "We would stop losing pitches. And we would stop working for free."

- **The lost pitch:** Kestrel Ridge Capital, a client for eight years, gave its latest platform acquisition to a larger firm that promised a red-flag report in five working days. Mehra & Cole had quoted three weeks. "We weren't even second."
- **The counteroffer:** a two-week paid diagnostic first. "I asked you for a tool and you are offering me a study." Arjun: "I'm offering to make sure we build the right tool." She agreed, if it took two weeks, not six.
- **The loose thread:** "There is one more reason I want this done properly, and I'd rather not discuss it on a video call. I'll tell whoever you send." Arjun underlined it.

Arjun turned "a tool" into "what would be different." Her answer names two branches of the problem, speed and economics. The diagnostic exists to find the rest.

## Five conversations

Over two weeks in Mumbai and on calls with New York, five conversations shaped everything. Each showed a different face of one problem.

### Vikram Rao: trust

- **Role:** head of Corporate and M&A; partner for twenty-two years.
- **Concern:** "The tracker comes to me with eight hundred rows. Six hundred of them say 'no issue'. I don't trust those six hundred," so he re-reads key contracts himself at one in the morning.
- **The logistics deal:** the target's largest customer (eighteen percent of revenue) had its master services agreement marked clean. A 2021 amendment letter in another folder gave it a change-of-control termination right. The buyer's commercial team found it two weeks before signing. A price adjustment and special indemnity saved the deal, but the fund's general counsel called Anjali. "We didn't lose the client. We lost the benefit of the doubt."
- **Materiality:** "Materiality depends on the deal. A non-compete is a footnote for a strategic buyer and a red flag for a fund planning a roll-up in the same sector. That judgment lives in my head and in the heads of maybe four other partners. It does not reach the juniors until I'm reading their work at the end." Arjun thought this the most important thing anyone said.

### Priya Nair: people and process

- **Role:** seventh-year senior associate; has run more diligence than anyone else.
- **Juniors:** half of each team is new to diligence. "I spend the first three days teaching them what a change of control clause looks like. By the time they're good, they leave." About a third of second- to fourth-years leave yearly.
- **Data rooms:** scans named scan_0041.pdf, amendments filed apart from their agreements, one agreement in three versions with no sign of which was signed, land records in Hindi and Marathi. "Half my team's time isn't legal analysis. It's finding things."
- **The old tool:** two hundred highlights a contract. "The juniors stopped opening it within a month, and the partners never trusted it in the first place."

### Sunita Kulkarni: money

- **Role:** chief operating officer.
- **Fee shift:** about seventy percent of PE diligence mandates are now capped or fixed fee; three years ago most were hourly.
- **Realization** (recorded time actually billed and collected): down from eighty-nine to sixty-eight percent. "On a mandate capped at $120,000, we routinely record $170,000 of time. The difference is written off."
- **No exit:** diligence is about thirty percent of practice hours and the least profitable, but "if we stop doing diligence, we stop getting the deals."

### Rohan Desai: what cannot happen

- **Role:** chief information officer.
- **Constraints:** confidentiality agreements on every data room; some clients forbid external tools; some Indian clients require data to stay in India; ethical walls between deal teams; every access logged.
- **Red line:** "If any vendor's model trains on a client's data room, we are finished. I need that in writing, and I need to be able to prove it to a client's auditor."
- **Fatigue:** the last vendor's security review took four months, "for something nobody ended up using."

### Daniel Cole: the report

- **Role:** name partner, New York.
- **Context:** US clients now ask about AI in requests for proposals. The American Bar Association's 2024 formal opinion on generative AI requires lawyers to understand their tools, protect confidentiality when using them, and bill fairly for work a tool made faster.[^aba-512]
- **Tension:** "Our clients will want us to use AI, and they will want the savings. The real question is whether we keep any of them."
- **Requirement:** a report a New York general counsel will sign off on. "Not a spreadsheet. Not a dashboard. A report."

### What the five add up to

Laid on the pipeline, the concerns connect. Priya's juniors lose time at the front; Vikram's judgment arrives only at the end. Sunita pays for the gap in write-offs. Rohan sets the walls, and Daniel defines what must come out.

Two gaps remained: nobody had sat with a junior doing first-pass review, or met a client who reads the reports.

## The problem underneath

Arjun's six-page memo declined to recommend a tool. "We need an AI tool" was a solution; nobody had agreed on the problem.

- **The cause:** the diligence model converts associate hours into a report. Clients now cap price and time, and the model cannot do the same with fewer hours. Judgment about what matters arrives only at the end, after the hours are spent.
- **Economics:** capped fees meet unchanged effort; the difference is written off.
- **Speed:** eighteen days cannot compete with five.
- **Reliability:** juniors in disorganized data rooms miss issues (the amendment letter), so partners re-review at night.
- **Knowledge loss:** every associate who learns diligence and leaves takes the skill along.
- **Constraints:** Rohan's list, a security review well under four months, and a culture that already rejected one tool.

Anjali later said this sentence was the first time she had seen her own problem written down:

> Mehra & Cole cannot deliver a partner-quality red-flag report within the time and fee its private equity clients now demand, because first-pass review depends on inexperienced associates searching disorganized data rooms, and the judgment about what matters is applied only at the end, by a few partners.

Every conversation reappears as a consequence or constraint, traced to one cause. Anjali read it twice and called Arjun. "Fine. Now tell me what you'll actually commit to."

## Writing the statement of work

A **statement of work** (SOW) defines an engagement: what, in what phases, by whom, by when, at what cost, and how everyone will know it succeeded. It is what the client will hold you to, and on a bad day the only thing that settles what was promised.

It took three weeks to agree; each stakeholder wanted something different.

- **Anjali:** wanted Kestrel's five days written in. Arjun refused: "I won't put a number in the SOW that neither of us can check today. I'll put the measurement in the SOW and let the numbers decide."
- **Vikram:** judge quality against what partners actually flagged on real deals, not a vendor benchmark.
- **Sunita:** measure associate hours, because hours are what she writes off.
- **Rohan:** a security schedule, with live work conditional on it.
- **Daniel:** the final report stays entirely the work of the firm's lawyers.

The SOW ran to eleven pages. Its core:

> **Statement of Work No. 1: AI-Assisted Due Diligence Pilot**
>
> **Objective.** Establish whether AI-assisted first-pass review can materially reduce the time and associate effort needed to produce a partner-ready red-flag report, without reducing the capture of material issues.
>
> **Scope.** Corporate and M&A practice, Mumbai and New York offices. Commercial contracts in target data rooms. Out of scope: litigation and regulatory analysis, drafting of the final red-flag report, and integration with billing systems.
>
> **Phases.** (1) Baseline, weeks 1–2: measure time, associate hours and issues found on twelve closed deals. (2) Build, weeks 3–8. (3) Supervised pilot, weeks 9–12: two live deals, with every output reviewed by the deal team. (4) Decision gate, week 12: steering committee decides whether to scale, extend or stop.
>
> **Client dependencies.** Access, with client consent, to the data rooms, trackers and final reports of twelve closed deals; two hours a week from a named partner; one day a week from a senior associate; completion of security review within fifteen business days.
>
> **Data and security.** All client data processed in a firm-approved environment within India. No client data used to train any model. Every document access logged. Access mirrors deal-team membership and existing ethical walls.
>
> **Governance.** Steering committee every two weeks: Anjali Mehra, Vikram Rao, Sunita Kulkarni, Rohan Desai and Arjun Sen, with the Inherent Labs engineer presenting. Day-to-day counterpart: Priya Nair.
>
> **Commercial terms.** Fixed fee for phases 1–3. Any scale-up priced under a separate SOW.

Every demand is visible in the text: Vikram's twelve closed deals, Sunita's hours, Rohan's security clause, Daniel's exclusion of report drafting. Only Anjali's five days became a measurement instead of a promise.

## What was promised, and what was not

Above the SOW sits one business goal, signed by the steering committee. The pilot only has to show, with evidence, whether it is reachable.

- **Business goal:** a partner-ready red-flag report on a mid-market deal in seven working days instead of eighteen, with no loss in capture of material issues, within PE fee caps.
- **Success criteria:**
  1. On the twelve closed deals, surface at least 95 percent of the issues the reviewing partner classified as critical, each linked to the clause it relies on.
  2. On the two pilot deals, cut associate first-pass hours per hundred contracts by at least 40 percent against baseline.
  3. On the two pilot deals, deal teams use the system for first-pass review of at least 80 percent of in-scope contracts.
  4. Pass the firm's security review before any live client data is processed.
- **Not promised:** removing partner review, drafting the report, fewer associates, zero errors. A lawyer checks every finding before it reaches a client.

"You are promising me less than the firm that beat us," Anjali said at the final review.

"I'm promising you something you can check," Arjun said. "They promised five days. In six months, ask Kestrel what they got."

Vikram settled it: "I'd rather sign this than the other thing." Anjali signed the next morning. The criteria map onto the problem: capture for reliability, hours for economics, adoption for a firm that shelved its last tool, security for Rohan.

## Your assignment

You are a forward deployed engineer at Inherent Labs. On the Friday after signing, Arjun told you the engagement was yours.

- **The role:** embedded in Mumbai four days a week for twelve weeks, accountable for the pilot against the SOW.
- **Your people:** Priya day to day; you report to Arjun and present to the steering committee fortnightly.
- **The pack:** the memo, the SOW, Arjun's notes and a list of open questions (see the reference below), the most useful thing in it. At the bottom, underlined twice: the reason Anjali would give only in person.

"The SOW tells you what we promised," Arjun said. "It doesn't tell you how. That part is yours." He paused. "Anjali wants to see you at nine on Monday. She said there's something she wants to tell you in person."

The engagement has a problem, a promise and an owner. Nobody at Inherent Labs has yet explained to the managing partner, at the level of mechanism, what the technology she is buying actually does and why it fails. On Monday morning, that will be the first thing she asks for.

---

## Case reference

This reference condenses everything above for readers returning to the case from later chapters. Where it adds operating detail, such as meeting days, that detail was agreed at signing and is consistent with the SOW.

### Key stakeholders

| Person | Role | What they care about | In their words |
|---|---|---|---|
| Anjali Mehra | Managing partner, Mehra & Cole. Sponsor and final signatory. | Winning back pitches, stopping write-offs, avoiding another embarrassment | "We would stop losing pitches. And we would stop working for free." |
| Vikram Rao | Head of Corporate and M&A. The named partner on the pilot. | Trust in first-pass findings; materiality judgment | "We didn't lose the client. We lost the benefit of the doubt." |
| Priya Nair | Senior associate (7th year). The FDE's day-to-day counterpart. | Training churn, messy data rooms, a tool juniors will actually open | "Half my team's time isn't legal analysis. It's finding things." |
| Sunita Kulkarni | Chief operating officer | Realization, write-offs, associate hours | "If we stop doing diligence, we stop getting the deals." |
| Rohan Desai | Chief information officer | Confidentiality, data residency, audit trail, a fast security review | "If any vendor's model trains on a client's data room, we are finished." |
| Daniel Cole | Name partner, New York | US client expectations, professional obligations, a signable report | "Not a spreadsheet. Not a dashboard. A report." |
| Arjun Sen | Engagement partner, Inherent Labs. The FDE's manager. | Promising only what can be checked | "I'll put the measurement in the SOW and let the numbers decide." |
| You | Forward deployed engineer, Inherent Labs | Delivering the pilot against the SOW | — |

Off stage: Kestrel Ridge Capital, the PE client lost to a rival firm that promised a five-day red-flag report.

### The problem as agreed

**Problem statement:** Mehra & Cole cannot deliver a partner-quality red-flag report within the time and fee its private equity clients now demand, because first-pass review depends on inexperienced associates searching disorganized data rooms, and the judgment about what matters is applied only at the end, by a few partners.

| Consequence | Evidence from the diagnostic |
|---|---|
| Economics | About 70% of PE diligence mandates are capped. Realization fell from 89% to 68%. A typical $120,000 cap carries $170,000 of recorded time. |
| Speed | 18 working days (firm estimate) against a rival's 5-day promise. Kestrel pitch lost. |
| Reliability | Logistics deal near-miss: change-of-control right in a 2021 amendment letter filed apart from the master agreement. Partners re-review "clean" rows at night. |
| Knowledge loss | About a third of 2nd–4th year associates leave each year. Materiality judgment sits with about five partners. |

**Constraints any answer must respect:** client confidentiality; India data residency for some clients; no training on client data; ethical walls; full access logging; a security review of no more than fifteen business days; a culture that has already rejected one tool.

### How the engagement unfolded

| Stage | What happened | Output |
|---|---|---|
| 1. Introduction | Referral through a PE operating partner. Anjali asks Arjun for "an AI tool for due diligence." | Agreement to a two-week paid diagnostic |
| 2. Diagnostic (2 weeks) | Arjun interviews Vikram, Priya, Sunita, Rohan and Daniel. | Interview notes and open questions |
| 3. Problem memo | Reframes "AI tool" as a symptom; names the diligence model as the problem. | Six-page memo and problem statement |
| 4. SOW negotiation (3 weeks) | Each stakeholder shapes the terms. Arjun refuses to promise five days. | Signed SOW No. 1 and agreed business goal |
| 5. Assignment | The FDE is staffed and receives the briefing pack. | Monday 9am meeting with Anjali (Chapter 1) |

### SOW in brief

**Business goal (signed by the steering committee):** a partner-ready red-flag report on a mid-market deal in 7 working days instead of 18, with no loss in the capture of material issues, within the fee caps PE clients now set. The pilot must show whether this is reachable; it is not expected to achieve it in twelve weeks.

| Phase | Weeks | Purpose | Exit condition |
|---|---|---|---|
| 1. Baseline | 1–2 | Measure time, associate hours and issues found on 12 closed deals | Measured baseline replaces the firm's estimates |
| 2. Build | 3–8 | Build the AI-assisted first-pass review | Security review passed; ready for supervised use |
| 3. Supervised pilot | 9–12 | Two live deals, every output reviewed by the deal team | Evidence against the four success criteria |
| 4. Decision gate | 12 | Steering committee decides | Scale, extend or stop |

**Success criteria:** (1) at least 95% of partner-classified critical issues surfaced on the 12 closed deals, each linked to its source clause; (2) at least 40% fewer associate first-pass hours per 100 contracts on the pilot deals; (3) the system used for at least 80% of in-scope contracts on the pilot deals; (4) security review passed before any live client data is processed.

**In scope:** Corporate and M&A, Mumbai and New York; commercial contracts in target data rooms. **Out of scope:** litigation and regulatory analysis; drafting the red-flag report; billing integration.

**Not promised:** removing partner review, drafting the report, reducing headcount, zero errors. Every finding is checked by a lawyer before it reaches a client.

**Client dependencies:** consented access to 12 closed deals (data rooms, trackers, final reports); 2 hours a week from Vikram; 1 day a week from Priya; security review within 15 business days.

**Commercial terms:** fixed fee for phases 1–3; scale-up under a separate SOW.

### Operating cadence and meeting practices

| Rhythm | Who | Purpose |
|---|---|---|
| On site Monday to Thursday, Mumbai | FDE | Embedded with the deal teams; Friday remote |
| Monday morning, weekly | FDE and Priya | Plan the week; agree which documents, deals and associates are involved |
| Weekly, 2 hours | FDE and Vikram | Partner review of findings and materiality judgments |
| Friday, weekly | FDE to Anjali and Arjun | Written status note against the SOW phases and criteria |
| Friday, weekly | FDE and Arjun | Internal check-in at Inherent Labs |
| Every two weeks, 60 minutes | Steering committee: Anjali, Vikram, Sunita, Rohan, Arjun; Daniel by video; FDE presents | Progress against success criteria, risks, decisions needed |
| Weeks 1–3 | FDE and Rohan | Security review against the SOW's data and security schedule |

**Meeting practices:** steering committee pre-reads go out 24 hours in advance. Every claim about performance is backed by a measured number, not an estimate. The FDE keeps a running decision and action log for the steering committee. Steering meetings are scheduled for the Mumbai evening so that Daniel can join from the New York morning.

### Key numbers

| Item | Value |
|---|---|
| Firm | 320 lawyers, 41 partners; Mumbai, Delhi, Bengaluru, New York |
| Corporate and M&A practice | About 110 lawyers, about 60 deals a year, $20M–$300M enterprise value, two-thirds PE, two in five India–US |
| Typical data room | 3,000–8,000 documents |
| Typical diligence team | 1 partner, 1 senior associate, 4–6 juniors |
| Time to partner-ready report | 18 working days median (estimate, not yet measured) |
| Diligence share of practice hours | About 30% |

### Open questions the FDE inherits

1. Nobody has sat with the junior associates who do first-pass review.
2. Nobody has seen how a PE client actually reads a red-flag report.
3. The 18-day median and associate hours are estimates, not measurements.
4. Anjali's reason for wanting this done properly, which she would give only in person.

---

## Sources

[^aba-512]: American Bar Association Standing Committee on Ethics and Professional Responsibility, *Formal Opinion 512: Generative Artificial Intelligence Tools*, July 29, 2024. It addresses competence, confidentiality, communication, supervision, candor to the tribunal and reasonable fees when lawyers use generative AI. Copy of the opinion hosted by the Minnesota Lawyers Professional Responsibility Board: <https://lprb.mncourts.gov/Pages/Formal%20Opinion%20512%20-%20Generative%20Artificial%20Intelligence%20Tools.pdf>. Summary: National Law Review, *American Bar Association Issues Formal Opinion on Use of Generative AI Tools*, <https://natlawreview.com/article/american-bar-association-issues-formal-opinion-use-generative-ai-tools>.
