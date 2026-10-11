# Prologue — What a Forward Deployed Engineer Is

A forward deployed engineer is an engineer who works inside a client's organization, after the sale, and is held responsible for the result the client paid for. Many people build software, sell it or advise on it. What sets this role apart is ownership: the engineer owns the client's outcome, in the client's environment, and the outcome has to last after the engineer has gone.

That ownership has three consequences, and almost everything in this book follows from them. The technology has to be made to work on the client's real data, inside the client's real systems and constraints, not in a demo. The people who will use it and pay for it have to trust it enough to change how they work, because a system nobody believes in produces no outcome. And the result has to survive without the engineer, so that the client can run it and the engineer's own company can learn from it. The section on why the role exists gives these three their names.

The clearest way to see what that ownership means is to put the role beside three that resemble it and lack it. A regional insurer wants to use AI to process claims. Its claims handlers are drowning, its customers wait three weeks for a decision, and its board has read that a language model can read a claim form faster than any person. The insurer invites four people to its head office on the same Monday morning.

The first is a software engineer from a company that sells a claims automation product. She asks for the insurer's requirements, notes which ones the product already meets, and files the rest as feature requests for her team back at headquarters. She will be gone by lunch. Whatever she builds next will be built for all of her company's customers at once, and this insurer will be one of them.

The second is a solutions architect from the same company. His job is to show that the product fits. He maps the insurer's systems onto the product's integration points, draws an architecture diagram, answers the security team's questions and estimates the implementation effort. If the insurer signs, he moves on to the next prospect, and an implementation team takes over.

The third is a management consultant. She interviews the head of claims, analyzes three years of claims data, and in six weeks delivers a well-structured recommendation: which claim types to automate first, what it will save, and how to reorganize the claims team around it. She does not write the system. Someone else will have to do that.

The fourth is a forward deployed engineer. He asks to sit with a claims handler for a day before anyone discusses requirements. By Wednesday he has found that the claim forms are the easy part, and that most of the delay comes from chasing medical reports that arrive as faxes and photographs. By Friday he has a rough prototype reading those reports on a laptop inside the insurer's network. He will still be there in three months, and the question he will be judged on is not whether the product fits, whether the recommendation is sound or whether the code is clean. It is whether claims are decided faster, and whether they stay faster after he leaves.

All four are skilled, and all four are doing their jobs properly. But only one of them owns the outcome at this client, in this environment, with these people, and only one will be judged on whether it lasts. The rest of this prologue explains where the role's name comes from, why the role exists, how it differs from the roles it resembles and what an interviewer is looking for in someone who can do it. The rest of the book prepares you to do it.

## Where the name comes from

"Forward deployed" is a military term. A forward deployed unit is stationed close to where the action is rather than at its home base. Headquarters has the plan, the maps and the long view. The forward position has the terrain.

That distinction is the most useful image for understanding the role, and it will come back throughout the book. Every company that builds a general-purpose technology has a headquarters: a product team with a roadmap, an architecture and a picture of what customers need. That picture is a map. Like every map, it is a simplification, and it is wrong in ways that are visible only on the ground. The client's data is messier than the map shows. Their systems are older. Their security rules are stricter. The person who signed the contract is not the person who will use the system, and the person who will use it has reasons of their own to resist it.

A forward deployed engineer works at the forward position. The job has two parts. The first is to win there: to make the technology produce a real result for this client despite everything the map got wrong. The second is to send back corrections to the map, so that headquarters learns what the ground actually looks like and the next deployment starts from a better picture. Engineers who do only the first become expensive custom developers. Engineers who do only the second become product researchers. The role requires both.

Palantir is generally credited with building the role in its modern form, embedding engineers with government and commercial customers whose problems no off-the-shelf product could solve. For years it remained unusual. Generative AI changed that. A large language model is about as general-purpose as a technology gets, which means almost all of its value depends on fitting it to a specific organization's data, workflows and people. From 2024 onwards, AI labs and applied AI companies began hiring forward deployed engineers in large numbers, because they found that the distance between an impressive model and a working deployment was where most of their customers got stuck.

## Why the role exists

Start from first principles. A client buys a technology because they want an outcome: faster claims, cheaper due diligence, fewer fraudulent transactions. Between the technology and the outcome sit three gaps, and every one of them has to be closed before the outcome appears.

The first is the **build gap**. The technology has to work on the client's actual data, inside the client's actual environment, under the client's actual constraints. A model that summarizes clean documents in a demo has to read scanned faxes, run inside a network it cannot leave, log every access and fail in ways that someone can detect. Closing this gap is engineering, and it is engineering that cannot be done from headquarters, because the problems are only visible on site.

The second is the **belief gap**. The people who must use the system, and the people who must pay for it, have to trust it enough to change how they work. Experts do not trust what they cannot check. Managers do not fund what they cannot measure. Many clients have already been disappointed by a tool that promised more than it delivered. A system that works but is not believed is not used, and a system that is not used produces no outcome.

The third is the **lasting gap**. The result has to survive without the person who created it. The client's team has to be able to run the system, the product team has to absorb what was learned, the engineer's own leadership has to understand what was promised and what was delivered, and the whole arrangement has to hold together when something breaks, as something always does.

Each of the other roles in the opening scene closes part of one gap. The software engineer improves the technology for everyone, which narrows the build gap from a distance. The solutions architect shows that the gap can be closed, which is a step toward belief. The consultant defines the problem and the outcome precisely, which is the foundation of belief and part of what makes a result last. None of them is accountable for closing all three gaps at a single client. The forward deployed engineer is.

That accountability is the definition. **A forward deployed engineer is an engineer who is embedded with a client and accountable for turning a general technology into a measured, lasting outcome for that client, while feeding what they learn back into the product.** Everything else about the role follows from it.

## How it differs from the roles around it

The boundaries between these roles are blurred in practice, and titles vary between companies. The differences are still real, and interviewers will test whether you understand them, because a candidate who thinks the role is just one of the others will behave like that role on the job.

**Compared with a software engineer**, a forward deployed engineer writes production code, often a great deal of it, but the problem does not arrive as a ticket. A software engineer is usually given a defined problem and judged on whether the solution is correct, maintainable and shipped. A forward deployed engineer is usually given an ambiguous situation and judged on whether the client's outcome changed. That means deciding what to build, which is often harder than building it, and accepting code that is good enough for this client this month rather than ideal for every client next year. It also means spending a large part of the week not writing code at all: interviewing users, negotiating access to data, presenting to a steering committee, writing status notes. Engineers who find that part of the work a distraction tend not to last in the role.

**Compared with a solutions architect or sales engineer**, a forward deployed engineer stays. A solutions architect works mostly before the sale. The aim is to show that the product can meet the client's needs and to design how it will fit, and success is usually measured by the deal being signed. A forward deployed engineer works mostly after the sale, when the promises have been made and someone has to keep them. The two roles need many of the same skills, including technical breadth, clear explanation and the ability to read a room, but they face different incentives. A solutions architect is rewarded for showing what is possible. A forward deployed engineer is rewarded for what actually happens, which makes them the person who has to say, early and unpopularly, which promises cannot be kept.

**Compared with a management consultant**, a forward deployed engineer builds. Good consultants and good forward deployed engineers share a great deal: both diagnose before they prescribe, both structure messy problems, both manage senior clients and both are judged on the client's results. The difference is where their work ends. A consultant's main output is usually a recommendation, and its value depends on someone else implementing it. A forward deployed engineer's main output is a working system, and the recommendation is the reason for building it. This gives the forward deployed engineer an advantage consultants rarely have: when the client doubts that something is possible, the answer can be a prototype by Friday rather than an argument.

**Compared with a product manager**, a forward deployed engineer serves one client deeply rather than many clients broadly. Both are responsible for working out what users actually need. But a product manager has to decide what is worth building for everyone and is right to ignore needs that only one customer has. A forward deployed engineer has to meet the needs of this customer, including the unusual ones, and then work out which of those needs are truly unusual and which are early signs of something every customer will soon need. That judgment is the substance of the second part of the job, the corrections to the map, and it is one of the most valuable things a forward deployed engineer gives the company that employs them.

## What the job demands

The three gaps translate directly into three questions every forward deployed engineer must answer on every engagement, and they arrive in this order.

The first is **can you make it work?** This is the technical core: understanding how the technology actually behaves, deciding what it sees, connecting it to the client's data and systems, measuring whether it is right and running it reliably in an environment you do not control. A candidate who cannot answer this question will not be hired, however good they are with clients.

The second is **can you make them believe it?** A working system is necessary but not sufficient. You have to discover what the client actually needs, which is often different from what they asked for. You have to structure your thinking so that others can follow it, tell the story of the work, report it honestly in writing, manage your own time across competing demands and carry yourself in a room full of senior people who are not sure they need you. Many technically strong candidates fail here, because they assume good work speaks for itself. It does not.

The third is **can it survive without you?** Once the client trusts you, people depend on you, and dependence is a risk as well as a reward. You have to manage your own leadership, manage the client, manage across to the product team at headquarters, manage anyone who works for you and hold everything together when something goes wrong. An engagement that collapses the week the engineer leaves has failed, however good the demo was.

These three questions are the three modules of this book: Build, Land and Lead. The order matters. Nobody believes in a system that does not work, and nobody depends on a system they do not believe in.

## What the interview is looking for

Because the role combines several others, the interview usually does too. Expect some mix of a technical exercise, in which you build, debug or design something under time pressure; a scenario, in which you are handed a messy client situation and asked what you would do; and a conversation about how you have handled people, ambiguity and failure in the past. Details vary from company to company, but the underlying question does not: when this person is alone at a client, with an ambiguous problem, imperfect data and a skeptical senior stakeholder, will they make good decisions without being told what to do?

Interviewers look for the signs of someone who has been in that position. They notice whether you ask about the problem before proposing a solution, whether you can explain a technical idea to someone who does not share your vocabulary, whether you promise only what you can check and whether you think about what happens after you leave. They notice, above all, whether you treat the client's outcome as your responsibility or as someone else's.

You cannot fake that perspective with prepared answers. You can, however, build it, by working through an engagement from start to finish and making its decisions yourself. That is what the rest of this book asks you to do.

## The forward position

The next part of the book describes the client you are about to be sent to: a law firm in Mumbai whose most important work has quietly stopped paying for itself, whose partners have been embarrassed by AI once already and whose managing partner has signed a statement of work that commits you to numbers. You will arrive after the contract is signed and before anyone knows how to keep it.

Read it as the briefing pack for your first forward deployment. Headquarters has given you the map. It is your job to find out where it is wrong.

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
