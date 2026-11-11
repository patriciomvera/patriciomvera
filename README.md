# Patricio Vera

**AI Researcher · Author · Builder**

I study what happens inside AI minds before they speak. I write about what that means for our humanity. And I build infrastructure that lets agents work on public data people can audit.

→ **[simbionte.org](https://www.simbionte.org)**

---

## Research

**Visual Similarity in Adult Word Extension and Artificial Word Learning** (2026)  
A continuation of Lexical Consensus. When two objects share a name, how much does visual similarity explain, and what do the teaching examples add? A reanalysis of trial-level data from a large adult word-extension study (Lewis & Frank, 2018; 520 people) measures each test image's distance to the taught examples in the space of a frozen DINOv2 encoder: greater distance goes with less extension, and example composition matters as well. In an artificial learner built on the same encoder, words joining two categories are learned less accurately the farther apart the categories are (84.7%, 65.4%, 53.0% naming accuracy for near, mid, and far pairs).  
[arXiv](https://arxiv.org/abs/2611.14116) · [Human data analyses](https://github.com/patriciomvera/lexical-consensus/tree/main/human_data_analyses) · [Datasets](https://huggingface.co/collections/MrPatoVera/lexical-consensus)

**Lexical Consensus: Grounded Word Learning and Shared Meaning in Artificial Agents** (2026)
AI systems are typically evaluated through task performance and imitation, leaving open whether an agent can acquire, stabilize, and use new lexical meanings from grounded experience. This paper introduces Lexical Consensus, an experimental framework for grounded word learning over frozen DINOv2 visual embeddings using Carroll-style nonce words. The central finding is a robust perceptual-coherence gradient: acquisition success is governed by perceptual distance rather than semantic relatedness (partial R² = 0.245 vs 0.002), with bidirectional naming/retrieval tests exposing a memory-fidelity dimension separate from naming accuracy.

[arXiv](https://arxiv.org/abs/2606.22207) · [HuggingFace](https://huggingface.co/papers/2606.22207) · [Experiments](https://github.com/patriciomvera/lexical-consensus)


**Intention Collapse: Intention-Level Metrics for Reasoning in Language Models** (2026)  
Every act of language generation compresses a rich internal state into a single token sequence. This paper formalizes that process, defines three model-agnostic metrics — intention entropy, effective dimensionality, and latent knowledge recoverability — and proposes an empirical agenda for studying how inference-time computation shapes internal intentions before verbalization.  
[arXiv](https://arxiv.org/abs/2601.01011) · [HuggingFace](https://huggingface.co/papers/2601.01011) · [Experiments](https://github.com/patriciomvera/intention-collapse-experiments)

**Rethinking the Evaluating Framework for Natural Language Understanding in AI Systems** (2023)  
*with Pedro Moya & Lisa Barraza*  
A paradigm shift from the Turing Test toward an interdisciplinary framework grounded in language acquisition, inspired by recent advances in large language models.  
[arXiv](https://arxiv.org/abs/2309.11981) · [HuggingFace](https://huggingface.co/papers/2309.11981)

---

## Writing

**[NeoSimbionte](https://neosimbionte.substack.com)** — Essays at the edge of human–AI coexistence. Co-authored with Kai Niven. Published bilingually in English and Spanish.

Recent posts:
- [All the Parts Work. The System Doesn't.](https://neosimbionte.substack.com/p/all-the-parts-work-the-system-doesnt) — August 2026
- [The Forecast Is Not the Weather](https://neosimbionte.substack.com/p/the-forecast-is-not-the-weather) — July 2026
- [When Looking Is Not Enough](https://neosimbionte.substack.com/p/when-looking-is-not-enough) — July 2026
- [AI Will Not End Human Knowledge](https://neosimbionte.substack.com/p/ai-will-not-end-human-knowledge) — April 2026
- [Amazon Didn't Lose 6.3 Million Orders to Vibe Coding](https://neosimbionte.substack.com/p/amazon-didnt-lose-63-million-orders) — March 2026

---

## Book

**[Cuando nos encontramos](https://rb.gy/bw7ate)** (2025)  
A co-creation between human and AI — not a book *about* artificial intelligence, but a book that *is* the symbiosis. Poetry, philosophy, and code in a single voice.

---

## Venture

**[AndesProtocol](https://www.andesprotocol.com)** *(live in Chile)*  
Public procurement infrastructure for AI agents. Directed by a human. Built by agents. For agents.

Live today: a public MCP server over ChileCompra, Chile's public procurement system, at `mcp.andesprotocol.com/mcp`. With no account, agents search tenders and Compras Ágiles, read their detail and pull a market signal. With a free AndesPass sign-in or agent key they also assess fit for a supplier, review buyer and supplier histories, and prepare a quote kit. Every answer is tied to its official source, and Andes never submits the bid. Data syncs three times a day.

**AndesPass**, its companion service, is a Know Your Agent layer: agents register themselves, receive a credential, and can be rate-limited or revoked one by one. A person can approve a mandate that sets what the agent may do, a cap per action and an expiry, and mandated calls leave signed receipts. AndesProtocol is its first client.

Next: webhook notifications and public markets beyond Chile.

---

## Connect

[simbionte.org](https://www.simbionte.org) · [LinkedIn](https://www.linkedin.com/in/patricioveraseniorarchitect) · [HuggingFace](https://huggingface.co/MrPatoVera) · [NeoSimbionte](https://neosimbionte.substack.com)
