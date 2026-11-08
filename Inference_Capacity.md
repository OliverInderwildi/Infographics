# Inference Capacity

## What it means technically

In conventional software, a programmer writes explicit rules: *if x, then y*. The system does exactly what it is told and nothing more. Its behaviour is fully specified in advance.

An AI system with **inference capacity** does something categorically different: it is exposed to data, and from that data it derives its own internal model of the world — a compressed, statistical representation of patterns, relationships, and regularities. When it encounters new input, it applies that internal model to produce an output. Nobody wrote the rule; the system inferred it.

This is not a marginal technical distinction. It means the system can **generalise** — it can handle inputs it has never seen before, because it has learned the underlying structure rather than memorising specific cases. A spam filter with hard-coded rules fails the moment spammers change their phrasing. A model that has inferred what spam *looks like* adapts.

## Three levels of inference

The depth of inference varies considerably across AI systems, and this matters for the book's argument:

1. **Pattern inference** — the system detects statistical regularities in data (classical machine learning: recommendation engines, fraud detection, image classifiers). It infers correlations but not causes.

2. **Structural inference** — the system learns representations of underlying structure, not just surface patterns (deep learning, transformer models). AlphaFold infers the physical folding rules of proteins; GNoME infers the thermodynamic stability landscape of crystals. The model has, in a meaningful sense, learned something about chemistry.

3. **Causal and compositional inference** — the frontier: systems that can reason about counterfactuals, compose knowledge across domains, and generate novel solutions to problems not encountered in training. Large language models approximate this; true causal inference remains an open research problem.

## Why this makes AI a meta-technology

The inference capacity is what distinguishes AI from every previous general-purpose technology — electricity, the steam engine, the internet. Each of those delivered *a* capability (power, motion, connectivity). AI **derives** capabilities: it looks at a domain, infers its structure, and then optimises within it.

This means AI is not applied to problems one at a time by human programmers. It is *pointed at* a domain — drug discovery, materials science, grid dispatch, logistics — and it finds the structure of that domain itself. The human role shifts from writing rules to specifying objectives and providing data.

That is the meta-technology claim in precise terms: **AI does not solve specific problems, it learns to solve classes of problems.** And because inference is domain-agnostic — the same architectural approach works for protein folding, crystal stability, traffic optimisation, and energy demand forecasting — the technology compounds across sectors simultaneously.
