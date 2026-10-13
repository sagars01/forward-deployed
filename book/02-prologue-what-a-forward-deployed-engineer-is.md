# Prologue — What a Forward Deployed Engineer Is

A forward deployed engineer is an engineer who works inside a client's organization, after the sale, and owns the result the client paid for. That result has to last after the engineer leaves.

The whole Prologue builds one mental model. Hold this shape in mind as you read:

```
Ownership of the client's outcome
├── Where the idea comes from:  the map and the terrain
├── Why the role exists:        three gaps (build, belief, lasting)
├── How it differs:             four neighboring roles, one missing piece
├── What the job demands:       three questions, in order
└── What the interview tests:   whether you act like an owner
```

Each section below adds one branch. By the end, you should be able to explain the role to someone in two minutes, using this tree.

## One client, four visitors

The fastest way to see ownership is to watch who has it and who does not. A regional insurer wants AI to process claims. Customers wait three weeks for a decision. The insurer invites four people in on the same Monday.

- **Software engineer** (product company): collects requirements, files the gaps as feature requests, and is gone by lunch. Builds for all customers at once.
- **Solutions architect** (same company): proves the product fits, draws the integration diagram, estimates the effort. Moves on once the insurer signs.
- **Management consultant**: analyzes three years of claims and recommends what to automate first. Does not build it.
- **Forward deployed engineer**: sits with a claims handler for a day. Finds the real delay is chasing medical reports sent as faxes and photos. Has a rough prototype inside the insurer's network by Friday. Still there in three months.

All four do their jobs well. Only the last one is judged on whether claims are actually decided faster, and whether they stay faster after he leaves. That difference, ownership of the outcome, is the root of the tree. Every other branch in this Prologue grows from it.

## Where the name comes from: the map and the terrain

"Forward deployed" is a military term. It means stationing forces close to where they may be needed, rather than at home.[^military] Headquarters holds the map. The forward position holds the terrain.

- **The map:** the product team's picture of what customers need. It is a simplification, and it is always wrong somewhere.
- **The terrain:** the client's reality. The data is messier, the systems older, the security rules stricter, and the user is not the person who signed.
- **The FDE's two jobs:** win on the terrain despite the map's errors, and send corrections back so the next deployment starts from a better map.

Do only the first job and you become an expensive custom developer. Do only the second and you become a product researcher. The role needs both. This is the central image of the book, and it will come back in every chapter.

**Where the role came from.** Palantir built the role in its modern form and describes itself as having pioneered it.[^palantir-role] Internally it calls these engineers "Deltas", as distinct from "Devs" who build the platforms. A Dev owns part of a platform used by every customer. A Delta typically works on a team that supports a single customer.[^palantir-delta]

**Why it is suddenly everywhere.** A large language model is about as general-purpose as technology gets, so almost all of its value depends on fitting it to one organization. In 2025, OpenAI, Anthropic and Cohere expanded their forward deployed teams fast, and job postings for the role rose more than 800 percent between January and September, according to Indeed data reported by the Financial Times.[^ft-surge]

## Why the role exists: three gaps

A client buys technology to get an outcome. Three gaps sit between the two, and every one must be closed before the outcome appears.

- **Build gap:** the technology must work on the client's real data, in the client's real environment. Example: reading scanned faxes inside a network the data cannot leave, with every access logged.
- **Belief gap:** the people who use it and pay for it must trust it enough to change how they work. Experts do not trust what they cannot check. Managers do not fund what they cannot measure.
- **Lasting gap:** the result must survive without the person who built it. The client runs it, headquarters learns from it, and it holds together when something breaks.

The neighboring roles each close part of one gap. The software engineer narrows the build gap from a distance. The solutions architect shows it can be closed. The consultant defines the problem precisely. None of them is accountable for all three gaps at one client. That accountability is the definition:

> **A forward deployed engineer is an engineer who is embedded with a client and accountable for turning a general technology into a measured, lasting outcome for that client, while feeding what they learn back into the product.**

## How it differs from the roles around it

Titles blur between companies, but the differences are real. Interviewers test them, because a candidate who thinks the role is one of the others will behave like that role on the job.

- **vs. software engineer:** both write production code. But the FDE's problem arrives as an ambiguous situation, not a ticket, and much of the week is not coding at all.
- **vs. solutions architect:** both need technical breadth and can read a room. But the architect works before the sale and is rewarded for what is possible. The FDE works after it and is rewarded for what actually happens.
- **vs. management consultant:** both diagnose, structure and manage senior clients. But the consultant's output is a recommendation. The FDE's output is a working system, so doubt can be answered with a prototype by Friday.
- **vs. product manager:** both work out what users need. But the PM serves many customers and rightly ignores one-off needs. The FDE serves one customer, then judges which of its needs are early signals for everyone.

Notice the pattern. Each neighbor shares a skill with the FDE, and each one stops short of owning the outcome at one client. That last point, spotting which local needs are early signals, is the "corrections to the map" job from the central image.

## What the job demands: three questions, in order

The three gaps become three questions you must answer on every engagement. They arrive in a fixed order.

1. **Can you make it work?** (Build) How the technology behaves, what it sees, how it connects to client data, how you measure it and run it reliably.
2. **Can you make them believe it?** (Land) Discover the real need, structure your thinking, tell the story, report honestly, manage your time and hold the room.
3. **Can it survive without you?** (Lead) Manage up, manage the client, manage across to headquarters, manage down, and hold things together when they break.

The order matters. Nobody believes in a system that does not work, and nobody depends on a system they do not believe in. These three questions are the three parts of this book. Strong engineers most often fail on the second, because they assume good work speaks for itself.

## What the interview tests

FDE interviews blend the roles the job blends. The format varies by company. The underlying question does not: alone at a client, with a vague problem, messy data and a skeptical senior stakeholder, will this person make good decisions without being told?

- **Formats to expect:** a technical exercise (build, debug or design under time pressure), a client scenario ("what would you do?"), and a conversation about past ambiguity and failure.
- **Signals interviewers look for:** you ask about the problem before proposing a solution, you explain technical ideas without jargon, you promise only what you can check, and you plan for what happens after you leave.
- **The signal behind all of them:** whether you treat the client's outcome as yours.

You cannot fake that with prepared answers. You can build it by living through one engagement and making its decisions yourself. That is what the rest of this book asks you to do.

## Your forward position

Next comes the client you are being sent to: a law firm in Mumbai whose most important work has quietly stopped paying for itself. Its partners have been burned by AI once. Its managing partner has signed a contract that commits you to numbers.

Read the next part as the briefing pack for your first forward deployment. Headquarters has given you the map. Your job is to find out where it is wrong.

---

## Prologue reference

| | Software engineer | Solutions architect | Management consultant | Product manager | Forward deployed engineer |
|---|---|---|---|---|---|
| Where they work | Headquarters | With prospects, mostly before the sale | With the client, for a defined study | Headquarters, across many customers | Embedded with one client, after the sale |
| What they produce | Product code for all customers | Proof of fit, architecture, estimates | Diagnosis and recommendation | Decisions about what to build for everyone | A working system at the client, and feedback to the product |
| How the problem arrives | Defined, as a ticket or spec | As the client's stated requirements | As a question the client wants answered | As patterns across many customers | Ambiguous, as a business situation |
| What success looks like | Correct, maintainable code shipped | Deal signed | Recommendation adopted | Product used and valued by many | Client's outcome measurably changed, and it lasts |
| What they own | The code | The technical case for buying | The quality of the analysis | The roadmap | The outcome at this client |

**The three gaps between a technology and an outcome:**

| Gap | The question | Book module |
|---|---|---|
| Build | Can you make it work? | Part I — Build |
| Belief | Can you make them believe it? | Part II — Land |
| Lasting | Can it survive without you? | Part III — Lead |

**Definition:** a forward deployed engineer is an engineer who is embedded with a client and accountable for turning a general technology into a measured, lasting outcome for that client, while feeding what they learn back into the product.

**Central image:** headquarters holds the map; the forward position holds the terrain. The job is to win on the ground and send back corrections to the map.

---

## Sources

[^military]: Forward deployment as "the regular assignment of US military forces to bases and facilities" overseas: *Forward Deployment in the 1970's and 1980's*, Defense Technical Information Center report ADA037806. <https://apps.dtic.mil/sti/html/tr/ADA037806/index.html>

[^palantir-role]: Palantir's own job postings state that it "pioneered this unique position, embedding engineers directly with customers." Palantir, *Forward Deployed Software Engineer* (job posting). <https://jobs.lever.co/palantir/8c38feb7-7ca8-429e-9643-efffe2fe0428>. Postings are recruiting copy, so treat this as Palantir's account of its own history.

[^palantir-delta]: Palantir, *Dev versus Delta: Demystifying engineering roles at Palantir*, Palantir Blog. <https://blog.palantir.com/dev-versus-delta-demystifying-engineering-roles-at-palantir-ad44c2a6e87>

[^ft-surge]: Financial Times reporting on FDE hiring at OpenAI, Anthropic and Cohere and on Indeed postings data (January to September 2025), as summarized in eWeek, *Why Forward-Deployed Engineers Are in High Demand*. <https://www.eweek.com/news/openai-anthropic-cohere-ai-hiring/>. Some secondary reports describe the 800 percent figure as covering customer-facing AI roles more broadly, not only roles titled forward deployed engineer.
