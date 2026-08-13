# Madhesh Vivekanandan

**Software engineer who builds things.**

Not a frontend developer. Not a backend developer. Not a Java developer.
Just an engineer who can move across the stack, reason about systems, debug unfamiliar
problems, and hold a solid mental model of how software actually works.

Languages and frameworks are tools I pick up when the problem asks for them — not
identities I carry around. I work AI-assisted by default: I use LLMs and coding agents
the way an engineer uses a compiler or a debugger, as leverage on top of judgment,
never as a substitute for understanding the code I ship.

---

## How I work

**I start from the system, not the syntax.**
Before writing code I want to know where the data comes from, what the failure modes are,
what's actually slow, and which constraint the design has to respect. The implementation
language is a detail that follows.

**I'm comfortable being unfamiliar.**
Dropped into a codebase I've never seen, in a language I don't use daily, I can read my way
to the part that matters, form a hypothesis, and prove it right or wrong. Debugging is a
first-class skill, not a chore between features.

**I move across boundaries.**
API design, data modelling, retrieval and inference layers, glue scripts, the UI when the UI
is what's blocking — I go where the work is instead of stopping at a job title.

**I build with AI, deliberately.**
Agentic workflows, RAG systems, LLM-backed services — both as things I build and as the way
I build. I know where models are genuinely useful, where they quietly lie, and how to put
verification around them so a system stays trustworthy.

**I care that it survives contact with reality.**
Tested, observable, boring to operate. Software that works once on my machine isn't finished.

---

## Where I've worked in the system

Described by the problem, not the language — the tools in parentheses are just what those
particular jobs happened to be built with.

**Retrieval and inference layers** — turning a pile of documents into something a model can
answer from: chunking, embeddings, vector stores, ranking, and the guardrails that keep an
answer honest. *(Python, embedding models, Qdrant)*

**Service and API layers** — designing the contract, then the orchestration behind it:
request shaping, downstream calls, error semantics, keeping latency predictable.
*(FastAPI, REST, GraphQL)*

**Data modelling and persistence** — schema design, relational vs. graph vs. vector depending
on the questions being asked, and migrations that don't break what's live.
*(PostgreSQL, MySQL, Neo4j, SQLAlchemy)*

**Model-facing plumbing** — prompts, tool calls, agent loops, evaluation and tracking, plus
the fallbacks for when a model does something unexpected. *(LLM APIs, Hugging Face, Ollama, MLflow)*

**Interfaces, when the interface is the blocker** — enough frontend to make the thing usable
and see whether the design actually holds up in someone's hands. *(JavaScript)*

**Running and verifying it** — containers, environment setup, scripting away repetition,
tests that catch real regressions rather than pad a number. *(Docker, Linux, Shell, pytest)*

None of this is a boundary. Give me a domain I haven't touched and the tooling is the easy
part — this list looked different a year ago and will look different next year.

---

## Selected work

Each of these exists because a problem needed solving, and each one pushed me into
something I hadn't done before.

**[RAG-Based Document Question Answering](https://github.com/Madheshvivekanandan/RAG-Based-Document-Question-Answering-System)**
Ingestion, embedding storage, and retrieval wired into a service that answers questions
with context instead of guesses. Where I learned how much of RAG quality lives in the
unglamorous parts: chunking, ranking, and knowing when to say "I don't know."

**[LLM-Powered Conversational Assistant](https://github.com/Madheshvivekanandan/LLM-Powered-Conversational-Assistant)**
End to end — prompt design, orchestration layer, and the interface on top. Full-stack by
necessity rather than by label.

**[voice_ai](https://github.com/Madheshvivekanandan/voice_ai)**
Voice as an interface to a model. Latency, turn-taking, and the gap between a demo that
impresses and an interaction that feels natural.

**[website_to_dataset](https://github.com/Madheshvivekanandan/website_to_dataset)**
A tool built for myself: turn messy web content into structured data worth training or
querying against. Most useful software starts as someone's own bottleneck.

**[Path Optimisation (TSP)](https://github.com/Madheshvivekanandan/Path-Optimisation--TSP-)**
Classic optimisation, implemented rather than read about. Algorithms stop being abstract
once you have to make one converge.

**[Sequence Recall](https://github.com/Madheshvivekanandan/Sequence-Recall)**
An interactive build about state, timing, and feedback loops — the small-scale version of
problems that reappear at scale.

---

## Currently working on

Getting better at the hard parts: agentic systems that stay reliable past the demo,
retrieval that degrades gracefully, and using AI tooling to raise the ceiling on what one
engineer can build and still fully understand.

---

## Get in touch

Good conversations: systems design, applied AI, debugging war stories, anything that needs
building.

[LinkedIn](https://www.linkedin.com/in/madhesh-vivekanandan/) ·
[madheshvivekanandan@gmail.com](mailto:madheshvivekanandan@gmail.com)
