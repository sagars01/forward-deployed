# How to Read This Book

This book has one purpose: to help you get hired as a forward deployed AI engineer. Everything in it, from the first explanation of how a language model predicts text to the last chapter on handling a deployment that has gone wrong, is here because it will be tested, directly or indirectly, when you sit across from someone deciding whether to put you in front of their clients.

That purpose shapes how the book is written and how it should be read. This page explains both: what the book is trying to do, how it is organized, and how to get the most from it.

## The intention

Most technical books are organized around concepts. A chapter on retrieval explains retrieval. A chapter on evaluation explains evaluation. Each explanation is clear, and by the end of the chapter you understand the idea. Then you close the book and discover that understanding an idea is not the same as knowing when to use it.

Forward deployed interviews are built to expose exactly that gap. The role exists because clients have messy, specific problems that no product solves out of the box, and the engineer's job is to work out which ideas apply to this client, this data, these people and these constraints. So the interview rarely asks you to define a concept. It hands you a situation and watches what you do with it.

You might be given a client who wants to automate a process nobody has fully described, and asked how you would start. You might be asked why a system that worked in a demo is failing on the client's real documents, or how you would know whether a model is good enough to put in front of a skeptical expert. You might be asked what you would say to a senior client who has just been embarrassed by an AI tool, or how you would handle an executive who wants a promise you cannot make. None of these questions has a definition as its answer. Each one tests whether you can recognize which concept the situation calls for, apply it under real constraints, and explain your reasoning to someone who does not share your vocabulary.

A candidate who has learned concepts in isolation tends to answer these questions with a lecture. A candidate who has learned them in context answers like someone who has been in the room. This book is written to make you the second candidate.

## One client, start to finish

To do that, the book teaches every concept inside a single client engagement that runs from the first page to the last.

Mehra & Cole LLP is a mid-size law firm with offices in Mumbai, Delhi, Bengaluru and New York. Its corporate practice is losing money and pitches on legal due diligence, the document review that precedes every acquisition, and its managing partner has hired Inherent Labs to help. You are the forward deployed engineer Inherent Labs sends. The engagement has a signed statement of work, a steering committee, a twelve-week timeline, a security review, skeptical partners, overworked associates, disorganized data rooms and a business goal every stakeholder has signed. It is fictional, but every element of it is drawn from the way real engagements run.

The case is not an illustration added to the end of each chapter. It is the reason each chapter exists. You learn how a language model produces text because, on your first morning, the managing partner asks why a chatbot invented case law for one of her associates, and you need an answer she will believe. You learn retrieval because the most important clause in a deal turns out to be hidden in an amendment letter filed in the wrong folder. You learn evaluation because the statement of work commits you to a number, and you have to prove you hit it. You learn to manage a client because the client keeps asking for things the statement of work does not cover.

In every chapter the situation comes first and the concept follows. That is the order in which concepts arrive in a real engagement, and it is the order in which they arrive in an interview. Nobody will tell you which chapter a question belongs to. You will have to recognize it from the situation, and the book is designed to train that recognition.

A law firm was chosen deliberately. It is a hard place to deploy AI. The documents are long, inconsistent and sometimes in several languages. A missed clause can cost millions. The users are experts who will not trust what they cannot check, and many have already been burned. The data is confidential, subject to residency rules and protected by ethical walls. And the economics are real: the system has to change how many hours a report takes, not just impress anyone in a demo. Almost every problem a forward deployed engineer meets, in any industry, appears somewhere in this engagement. If you can reason through Mehra & Cole, you can reason through the hospital, bank or logistics company in your interview.

## How the book is organized

The book opens with two short pieces before the first chapter. The Prologue explains what a forward deployed engineer is and how the role differs from a software engineer, a solutions architect and a consultant. The Case then sets out the Mehra & Cole engagement up to the morning it becomes yours: the firm, the problem, the five stakeholder conversations, the statement of work and your assignment. It ends with a reference section summarizing the people, numbers, phases and meeting cadence, which you will return to throughout.

The chapters that follow are grouped into three modules. Each module answers one of the three questions every forward deployed engineer must answer, in the order the engagement raises them.

The first module, Build, asks whether you can make the system work. It begins with how language models actually behave (Chapter 1), then moves to deciding what the model sees (Chapter 2), retrieving the right material from the client's own data (Chapter 3), letting the model act through tools (Chapter 4), measuring whether it is right (Chapter 5) and running it inside the client's environment (Chapter 6). It closes with a capstone in which you build a working prototype in a week (Chapter 7), and the client is unmoved.

The second module, Land, asks whether you can make the client believe in it. It opens by working out why the prototype failed to persuade: discovering the real problem (Chapter 8), structuring your thinking (Chapter 9), telling the story of the work (Chapter 10), reporting it in writing (Chapter 11), organizing yourself across competing demands (Chapter 12) and carrying yourself in the room (Chapter 13). It ends with the client trusting you, which means people now depend on you.

The third module, Lead, asks whether the work can last beyond you. It covers managing upward to your own leadership (Chapter 14), managing the client (Chapter 15), managing across to the product team back at headquarters (Chapter 16), managing anyone who works for you (Chapter 17) and holding everything together when a deployment breaks (Chapter 18).

The Epilogue brings the engagement to its decision gate and maps each module to the parts of the interview that test it.

Every chapter follows the same shape. It opens where the previous chapter left the engagement. It introduces one central image or analogy that makes the idea intuitive. It explains the idea from first principles, then returns to Mehra & Cole to show what you actually say or do. It closes with the problem the next chapter has to solve. The technical chapters end with Further reading: the primary papers and documentation behind each idea, with a note on what to read first.

Each concept is explained once, in the chapter that needs it first. Later chapters build on it by name without explaining it again. This keeps the book short, but it means the chapters depend on each other.

## How to read it

Read the book in order. The engagement is continuous, and so is the argument. A chapter that seems to start abruptly is picking up a thread the previous one left open.

Start with the Case, and read it the way you would read a briefing pack before your first day at a new client: learn the people, the problem, the promises and the open questions. When a later chapter mentions Vikram's materiality judgment or the amendment letter on the logistics deal, you should know what it means without looking it up. If you do need to look it up, use the reference section at the end of the Case.

As you read each chapter, do what you would do on the engagement. When the opening scene presents a situation, stop before the explanation begins and decide what you would do or say. When the chapter reaches its answer, compare it with yours. The distance between the two is the most useful thing the book can show you, because it is the same distance an interviewer is looking for.

Read the papers listed at the end of the technical chapters, at least the parts each note recommends. Interviewers for these roles are often engineers who know the primary sources, and nothing establishes credibility faster than knowing where an idea came from and what its authors actually showed.

The modules are not equally technical, and readers often want to skip the part they think they already know. Resist that. Engineers tend to underrate the second and third modules, and those are where many strong technical candidates fail, because the interview treats your judgment with clients and colleagues as seriously as your code.

By the end of the book you should be able to walk into an interview, hear a messy client scenario and recognize it. Not because you have memorized an answer, but because you have already lived a version of it: twelve weeks at a law firm in Mumbai, from the first morning to the decision gate.
