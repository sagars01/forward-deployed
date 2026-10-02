# The Case — Mehra & Cole LLP

Mehra & Cole LLP did not set out to buy artificial intelligence. It set out to stop losing money on work it was good at.

By the spring the firm approached Inherent Labs, its corporate practice had lost two pitches in six months. It had written off more of its due diligence work than in any year its partners could remember, and it had come within a fortnight of a serious embarrassment on a deal it had otherwise run well. None of these events was a crisis on its own. Together they convinced the managing partner that the way the firm reviewed documents for its deals no longer worked, and that she did not fully understand why.

This part of the book tells the story of that engagement up to the morning it becomes yours. It describes the firm, the problem as the firm first described it, the problem as it turned out to be, and the agreement Inherent Labs and the firm signed to address it. It deliberately stops short of any solution. Every technical chapter that follows builds a part of that solution, and every chapter after them tests whether the firm will believe in it. You will return to the people and numbers here throughout the book, so read this the way you would read a client briefing pack before your first day on site.

## The firm

Anjali Mehra founded the firm in Mumbai in the 1990s as a four-lawyer corporate boutique. Daniel Cole, a New York-qualified lawyer who had spent a decade advising American companies investing in India, joined as a name partner in 2011 to open an office in Manhattan. Today the firm has 320 lawyers and 41 partners across Mumbai, Delhi, Bengaluru and New York.

Its largest practice is Corporate and M&A, with about 110 lawyers working on roughly sixty transactions a year. Most are mid-market deals, with enterprise values between $20 million and $300 million. Two-thirds involve private equity funds as buyers or sellers, and about two in five are cross-border deals between India and the United States. The practice is respected, profitable on paper and, as the managing partner was beginning to suspect, quietly becoming less profitable every year.

At the center of almost every one of those transactions sits a piece of work called **legal due diligence**. If you have never worked near a law firm, it is worth understanding before anything else in this book, because the entire engagement turns on it.

Before a buyer acquires a company, the buyer's lawyers review the target company's documents to find anything that should change the price, the structure of the deal or the decision to proceed at all. The seller places the documents in a virtual data room, a secure online repository, and grants the buyer's advisers access for a limited period. A mid-market data room typically holds between 3,000 and 8,000 documents: corporate records, licenses, employment agreements, litigation files, property documents and, above all, commercial contracts with customers and suppliers.

The lawyers are looking for clauses that create risk for a new owner. The most important is the **change of control** clause, which allows the other party to a contract to terminate or renegotiate it if ownership of the company changes. An acquisition is, by definition, a change of ownership, so a change of control clause in a contract with a major customer can put a large share of the target's revenue at risk on the day the deal closes. Lawyers also look for restrictions on assigning contracts, exclusivity commitments, non-compete obligations, unlimited liabilities, unusual termination rights and dozens of similar provisions.

The output is a **red-flag report**: a document listing every material issue found, where it was found, how serious it is and what the buyer should do about it. The remedy might be a price adjustment, a specific indemnity from the seller, or a condition that the seller obtain the counterparty's consent before closing. The red-flag report is what the client pays for, and it is what a private equity investment committee reads before committing hundreds of millions of dollars.

At Mehra & Cole, diligence on a mid-market deal follows a pattern that has barely changed in fifteen years. A partner leads. A senior associate runs the day-to-day work. Four to six junior associates divide the data room between them and review each document in turn, recording what they find in a shared spreadsheet the firm calls the tracker, with one row per document and a column for each type of issue. The senior associate consolidates the tracker, the partner reviews the findings that look material, and the report is drafted from the result. By the firm's own estimate, the median time from data room access to a partner-ready red-flag report is eighteen working days. Much of that time is spent at night.

## What the firm asked for

The introduction came through a private equity operating partner who had worked with both firms. Arjun Sen, the engagement partner at Inherent Labs, an applied AI company that embeds engineers inside its clients' businesses, spoke to Anjali Mehra by video on a Thursday afternoon. She did not spend long on pleasantries.

"I'll be direct," she said. "We need an AI tool for due diligence. Every firm our size is buying one, our clients ask about it in every pitch, and the one we bought two years ago is shelfware. I want something that works. How quickly can you put it in?"

"Before I answer that," Arjun said, "what would be different in a year if it worked?"

She paused for long enough that he wondered whether the connection had dropped. "We would stop losing pitches," she said. "And we would stop working for free."

He asked about the pitches. The most recent, she explained, had been for Kestrel Ridge Capital, a fund the firm had advised for eight years. Kestrel had given its latest platform acquisition to a larger firm that promised a red-flag report in five working days. Mehra & Cole had quoted three weeks. "We weren't even second," she said.

Arjun proposed a two-week paid diagnostic before any proposal: time with the people who did the work, a look at how recent deals had actually run, and a written account of the problem. Anjali was not pleased. "I asked you for a tool and you are offering me a study."

"I'm offering to make sure we build the right tool," he said. "If, after two weeks, the answer is that you need the same thing everyone else bought, I'll tell you, and you can save your money."

She agreed on condition that the diagnostic took two weeks and not six. Near the end of the call she added something he wrote down and underlined. "There is one more reason I want this done properly," she said, "and I'd rather not discuss it on a video call. I'll tell whoever you send."

## Five conversations

Arjun spent the next two weeks in the firm's Mumbai office and on early-morning calls with New York. Five of his conversations shaped everything that followed.

The first was with Vikram Rao, head of the Corporate and M&A practice and a partner for twenty-two years. Vikram's concern was not speed. It was trust.

"The tracker comes to me with eight hundred rows," he said. "Six hundred of them say 'no issue'. I don't trust those six hundred, so I re-read the contracts that matter myself, which means I am doing a junior associate's job at one in the morning."

He told Arjun about a deal the previous year. The firm had acted for a fund buying a logistics software company. The target's largest customer accounted for eighteen percent of its revenue, and the master services agreement with that customer had been reviewed and marked clean. What nobody on the deal team had found was a 2021 amendment letter, filed in a different folder of the data room, that gave the customer the right to terminate on a change of control. The buyer's commercial team discovered it during customer calls two weeks before signing. The deal survived with a price adjustment and a special indemnity, but the fund's general counsel called Anjali personally.

"We didn't lose the client," Vikram said. "We lost the benefit of the doubt."

He made a second point that Arjun came to think of as the most important thing anyone said in the diagnostic. "Materiality depends on the deal. A non-compete is a footnote for a strategic buyer and a red flag for a fund planning a roll-up in the same sector. That judgment lives in my head and in the heads of maybe four other partners. It does not live in the checklist, and it does not reach the juniors until I'm reading their work at the end."

The second conversation was with Priya Nair, a seventh-year senior associate who had run the day-to-day work on more diligence exercises than anyone else in the firm. Her concern was people and process.

"On every deal I get four or five juniors, and half of them have never done a diligence," she said. "I spend the first three days teaching them what a change of control clause looks like. By the time they're good, they leave." Attrition among associates in their second to fourth years was running at about a third a year, most of them leaving for in-house roles.

She described the data rooms themselves as a large part of the problem. Contracts arrived as scanned PDFs with file names like scan_0041.pdf. Amendments were filed separately from the agreements they amended. The same agreement appeared in three versions with no indication of which was signed. State-level registrations and land records arrived in Hindi and Marathi. "Half my team's time isn't legal analysis," she said. "It's finding things."

She was equally blunt about the tool the firm had bought two years earlier. "It highlighted every clause that mentioned assignment. Two hundred highlights a contract. The juniors stopped opening it within a month, and the partners never trusted it in the first place."

The third conversation was with Sunita Kulkarni, the firm's chief operating officer, and it was the one that explained why Anjali had said the firm was working for free. Three years earlier, most private equity clients had paid for diligence by the hour. Now about seventy percent of the firm's private equity diligence mandates carried a fixed fee or a cap. The firm's realization on diligence work, the share of recorded time it actually billed and collected, had fallen from eighty-nine percent to sixty-eight percent over the same period.

"On a mandate capped at $120,000, we routinely record $170,000 of time," she said. "The difference is written off, and it comes out of the partners' pockets." Diligence now accounted for about thirty percent of the practice's hours and was its least profitable work. The firm could not simply do less of it. "Diligence is how we get the rest of the deal," she said. "The share purchase agreement, the negotiation, the closing. Those are profitable. If we stop doing diligence, we stop getting the deals."

The fourth conversation was with Rohan Desai, the chief information officer, who spoke mostly about what could not happen. Data rooms belonged to the target company and were shared under strict confidentiality agreements. Some clients prohibited uploading their documents to any external tool. Some Indian clients required their data to stay in India. Access within the firm had to respect the ethical walls that kept deal teams separated where there was a potential conflict, and every access to a client document had to be logged.

"If any vendor's model trains on a client's data room, we are finished," he said. "I need that in writing, and I need to be able to prove it to a client's auditor." He was also tired. "The last vendor took four months to clear our security review, for something nobody ended up using. I'm not doing that again."

The fifth conversation, by video from New York, was with Daniel Cole. American clients were now asking about AI use in their requests for proposals, and the American Bar Association's 2024 formal opinion on generative AI had made the professional obligations explicit: lawyers had to understand the tools they used, protect client confidentiality when using them, and bill fairly for work a tool had made faster.

"Our clients will want us to use AI, and they will want the savings," Daniel said. "The real question is whether we keep any of them." He had one more requirement. "Whatever you build has to end in a report that a New York general counsel will sign off on. Not a spreadsheet. Not a dashboard. A report."

Arjun noticed what was missing from his notes as clearly as what was in them. He had not sat with any of the junior associates who did the first-pass review, and he had not spoken to anyone on the client side who read the red-flag reports. He recorded both as open questions.

## The problem underneath

At the end of the second week Arjun sent Anjali a six-page memo. Its first page did something she had not expected: it declined to recommend a tool.

The memo argued that "we need an AI tool" was a solution, and that the firm had not yet agreed on the problem it was solving. The problem, as the conversations described it, was the firm's diligence model itself. That model converted associate hours into a red-flag report. For fifteen years it had worked because clients paid for the hours and accepted the timeline. Clients now capped the price and compressed the timeline, and the model had no way to produce the same report with fewer hours. Worse, the judgment that decided what mattered on a given deal was held by a handful of partners and applied only at the end, after the hours had already been spent.

The memo traced four consequences to that single cause. The economics had deteriorated, because capped fees met unchanged effort and the difference was written off. The firm had lost speed, because eighteen working days could not compete with a promise of five. Reliability suffered, because inexperienced associates searching disorganized data rooms missed issues, as the amendment letter on the logistics deal had shown, and partners compensated by re-reviewing at night. And the firm's knowledge was leaving with its people, because every associate who learned to do diligence well and then left took that skill with them.

It also set out the constraints any answer would have to respect: client confidentiality, data residency for some clients, ethical walls, a complete audit trail, a security review that would not take four months, and a professional culture that had already rejected one tool and would not give a second the benefit of the doubt.

The memo condensed all of this into one sentence, which Anjali later said was the first time she had seen her own problem written down:

> Mehra & Cole cannot deliver a partner-quality red-flag report within the time and fee its private equity clients now demand, because first-pass review depends on inexperienced associates searching disorganized data rooms, and the judgment about what matters is applied only at the end, by a few partners.

Anjali read it twice and called Arjun. "Fine," she said. "Now tell me what you'll actually commit to."

## Writing the statement of work

A **statement of work**, usually shortened to SOW, is the contract that defines an engagement: what will be done, in what phases, by whom, by when, at what cost, and how everyone will know whether it succeeded. Engineers sometimes treat it as paperwork for the commercial team. A forward deployed engineer cannot afford to. The SOW is the document the client will hold you to, and on a difficult day it is the only thing that settles an argument about what was promised.

The Mehra & Cole SOW took three weeks to agree, mostly because each of the five people Arjun had interviewed wanted something different from it.

Anjali wanted the five-day turnaround that had won Kestrel's mandate written in as a promise. Arjun refused. "I won't put a number in the SOW that neither of us can check today," he said. "I'll put the measurement in the SOW and let the numbers decide." Vikram insisted that any measure of quality be judged against what partners had actually flagged on real deals, not against a vendor's benchmark. Sunita wanted associate hours measured, because hours were what she wrote off. Rohan attached a security schedule and made the start of any live work conditional on it. Daniel asked that the final report remain entirely the work of the firm's lawyers.

The agreed SOW ran to eleven pages. Its core read as follows:

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

## What was promised, and what was not

Above the SOW sat a single business goal that every member of the steering committee signed: to deliver a partner-ready red-flag report on a mid-market deal in seven working days instead of the current eighteen, with no loss in the capture of material issues, within the fee caps private equity clients now set. The pilot was not expected to achieve that goal in twelve weeks. It was expected to show, with evidence, whether the goal was reachable.

The SOW defined that evidence in four success criteria:

1. On the twelve closed deals, surface at least 95 percent of the issues that the reviewing partner classified as critical in the final report, with every finding linked to the clause it relies on.
2. On the two pilot deals, reduce associate first-pass hours per hundred contracts by at least 40 percent against the baseline.
3. On the two pilot deals, have the deal teams use the system for first-pass review of at least 80 percent of in-scope contracts.
4. Pass the firm's security review before any live client data is processed.

The SOW was equally explicit about what was not promised. It did not promise to remove partner review, to draft the red-flag report, to reduce the number of associates or to make no errors. Every finding the system produced would be checked by a lawyer before it reached a client.

Anjali pushed back once more at the final review. "You are promising me less than the firm that beat us."

"I'm promising you something you can check," Arjun said. "They promised five days. In six months, ask Kestrel what they got."

It was Vikram who settled it. "I'd rather sign this than the other thing," he said. Anjali signed the following morning.

## Your assignment

You are a forward deployed engineer at Inherent Labs, and on the Friday after the SOW was signed, Arjun called to tell you the engagement was yours.

The assignment was straightforward to state. You would be embedded in the Mumbai office four days a week for twelve weeks. You would be accountable for delivering the pilot against the SOW: the baseline, the build, the supervised pilot and the evidence for the decision gate. Priya Nair would be your day-to-day counterpart. You would report to Arjun, and you would present to the steering committee every two weeks.

Arjun sent you the briefing pack that evening: the diagnostic memo, the signed SOW, his notes from the five conversations and a short list of open questions. The list was more useful than anything else in the pack. Nobody had yet sat with the junior associates who did the first-pass review. Nobody had seen how a private equity client actually read a red-flag report. The eighteen-day median and the hours behind it were the firm's own estimates, not measurements. And at the bottom, underlined twice, was the reason Anjali had refused to give over video.

"The SOW tells you what we promised," Arjun said. "It doesn't tell you how. That part is yours." He paused. "Anjali wants to see you at nine on Monday. She said there's something she wants to tell you in person."

The engagement now had a problem, a promise and an owner. What it did not yet have was anyone on the Inherent Labs side who had sat across from the managing partner and explained, at the level of mechanism, what the technology she was buying actually does and why it fails. On Monday morning, that would be the first thing she asked for.

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
