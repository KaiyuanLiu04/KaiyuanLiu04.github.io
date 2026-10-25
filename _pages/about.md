---
permalink: /
title: "Biography"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

# Kaiyuan Liu
B.S./M.S. Student, Paul G. Allen School of Computer Science & Engineering, University of Washington

I am a student in the combined B.S./M.S. program in Computer Science at the University of Washington, where I am fortunate to be mentored by [Natasha Jaques](https://natashajaques.ai/) and [Luke Zettlemoyer](https://www.cs.washington.edu/people/faculty/luke-zettlemoyer/). I also work closely with [Alex Dimakis](https://people.eecs.berkeley.edu/~alexdimakis/) at UC Berkeley. In Summer 2026, I was a research intern at Microsoft AI, working with Asli Celikyilmaz on self-improvement.

## Research Interests
My research centers on **continual learning**: how can AI systems keep accumulating knowledge and improving over very long horizons, rather than stopping at what they learned during training?

In the near term, I approach this question through **multi-agent systems**. This bet rests on two observations:

1. **Much of human intelligence is social.** If we view human intelligence as a whole, a large share of our knowledge creation is built on social intelligence. Communication and collaboration between individuals have done far more to advance what we know than any single mind working alone.
2. **Models, unlike brains, are trivially duplicable.** A model can be copied as many times as compute allows. In the spirit of [The Bitter Lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html), general methods that turn more computation into more capability tend to win, and many interacting copies of a model are a natural way to do exactly that.

Concretely, I work on two questions:

1. **Scaling strategies on long-horizon tasks.** How do models, whether a single agent or an agent swarm, spend their compute on very long-horizon tasks? How can we use that understanding to make them perform better, and ultimately to achieve better continual learning? My representative work, [When Agents Slow Down](https://arxiv.org/abs/2609.15309), studies how LLM agents allocate test-time compute as they revise solutions, use tools, explore alternatives, and decide when to stop, through an Elo-per-token lens.
2. **Emergent behavior and communication in multi-agent systems.** What behaviors and communication structures emerge on their own when models interact? How can we interpret a multi-agent system as a whole, beyond interpreting a single model? I am also excited about the bridge in both directions: using what we know about human societies to understand agents, and using agents to better understand society. My work on [LLM agents as human simulators in climate social dilemmas](https://openreview.net/forum?id=wTgTyIgRv3) is an early step in this direction.

## Latest News
* **[Oct 2026]** [FrontierCS 2: A Benchmark for Computer Science R&D](https://arxiv.org/abs/2610.29932) is now on arXiv.
* **[Sep 2026]** Three papers accepted to **NeurIPS 2026**: [FrontierSmith](https://arxiv.org/abs/2605.14445) (**Spotlight**), [Harbor](https://arxiv.org/abs/2609.04298), and [Agents' Last Exam](https://arxiv.org/abs/2606.05405).
* **[Sep 2026]** [EmbodiedSWE: Coding Agents for Long Horizon Dexterous Robotics](https://arxiv.org/abs/2609.27308) is now on arXiv.
* **[Sep 2026]** New first-author preprint on arXiv: [When Agents Slow Down: Understanding LLM Agents' Test-Time Strategies via Elo-per-token Analysis](https://arxiv.org/abs/2609.15309).
* **[Sep 2026]** [Harbor Adapters and Harbor-Index](https://arxiv.org/abs/2609.04298) is now on arXiv.
* **[Jun 2026]** I received the **Best Senior Thesis Award** from the Paul G. Allen School.
* **[Jun 2026]** [Agents' Last Exam](https://arxiv.org/abs/2606.05405) is now on arXiv.
* **[Jun 2026]** I started as a Research Intern at **Microsoft AI**, advised by Asli Celikyilmaz.
* **[May 2026]** **FrontierCS** has been accepted to **ICML 2026**.
* **[May 2026]** Two new preprints on arXiv: [OpenDeepThink](https://arxiv.org/abs/2605.15177) and [FrontierSmith](https://arxiv.org/abs/2605.14445).
* **[Mar 2026]** Our paper on LLM agents in climate social dilemmas was accepted as an **Oral** at the ICLR 2026 MALGAI Workshop.
* **[Jan 2026]** **AutoCode** has been accepted to **ICLR 2026**.
* **[Jan 2026]** I am honored to have received an **Honorable Mention** for the **CRA Undergraduate Research Award**.
* **[Dec 2025]** I presented LiveCodeBench Pro in San Diego at **NeurIPS 2025**.
* **[Nov 2025]** I received a **Tinker Research Grant** from Thinking Machines Lab.

---

## Background
My research journey has spanned **Theoretical Computer Science**, **Machine Learning Systems**, and **Computational Neuroscience**. While I no longer work directly on brain-inspired computation, it has profoundly shaped my research intuition.

I am also proud of my background in **Competitive Programming**, where I had the honor of representing my team in the **ICPC World Finals**.

*(Fun Fact: My Erdos number is 3!)*
