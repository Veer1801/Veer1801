<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Veer Patel — AI, machine learning, and research. Start with a question. Follow it deeper." src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="#research-spotlight">Research</a> &nbsp; / &nbsp;
  <a href="#follow-a-thread">Follow a thread</a> &nbsp; / &nbsp;
  <a href="#lets-connect">Connect</a>
</p>

## Hi, I'm Veer.

I'm a developer focused on **AI, machine learning, and research**. I'm curious about how models represent information, reason about relationships, and arrive at decisions we can understand.

My public research explores **computer vision, adaptive tokenization, and graph-based reasoning**. I like questions that lead from an intuition to a mathematical formulation—and then to an experiment that could prove it wrong.

> Understand the assumptions. Ask a better question. Let the evidence lead.

## Research spotlight

### [DAG-ViT · Vision Transformers with Adaptive Graph Reasoning](https://github.com/Veer1801/DAG-ViT)

**What if a vision model could learn which image regions matter—and how they relate?**

DAG-ViT is my theoretical proposal for combining adaptive token selection with directed acyclic graph reasoning in a vision transformer.

- **The idea:** move beyond a fixed patch grid to explore selective, relational image representations.
- **The formulation:** bring together soft attention, graph neural networks, transformers, and an acyclicity constraint.
- **The stage:** mathematical formulation and research paper. Implementation and empirical validation remain next steps.

[Explore the repository →](https://github.com/Veer1801/DAG-ViT) &nbsp; · &nbsp; [Read the paper →](https://github.com/Veer1801/DAG-ViT/blob/main/DAG_VIT_PAPER.pdf)

<details>
<summary><b>Look inside the idea</b></summary>

The proposal connects three questions:

1. **What should the model attend to?** Adaptive tokenization uses soft attention to select relevant image information.
2. **How should those tokens interact?** A directed graph represents dependencies between tokens, alongside transformer and graph-based reasoning.
3. **How can the graph stay acyclic?** A differentiable DAG constraint is part of the proposed formulation.

Medical and satellite imagery are potential application areas discussed in the project. Establishing usefulness would require implementation, suitable baselines, and experiments.

</details>

## Follow a thread

Research starts with curiosity. Open a question below.

<details>
<summary><b>01 / Can a model see less and understand more?</b></summary>

I'm interested in the tradeoff between selecting fewer image tokens and preserving the information needed for a task. Fewer tokens alone are not enough: the important question is what happens to accuracy, computation, and robustness.

**An experiment I'd like to run:** compare adaptive token selection with a fixed patch grid under the same compute budget.

</details>

<details>
<summary><b>02 / When does structure help a model reason?</b></summary>

Graphs offer a way to represent relationships explicitly. I'm curious about when that structure adds useful information, how it interacts with attention, and when its extra complexity is justified.

**A question worth testing:** does learned graph structure improve performance over attention alone, and which connections actually matter?

</details>

<details>
<summary><b>03 / What would change my mind?</b></summary>

A promising idea should survive a fair comparison. My research mindset is to make assumptions explicit, start with a clear baseline, and ask what evidence would challenge the original intuition.

**The loop I aim for:** question → read → formulate → implement → evaluate → revise.

I value clear limitations and useful negative results as part of that process.

</details>

## Let's connect

Interested in computer vision, graph learning, or a thoughtful discussion about an ML idea? I'd be glad to connect.

[Email me](mailto:veerpatel1801@gmail.com) &nbsp; · &nbsp; [Explore my repositories](https://github.com/Veer1801?tab=repositories)

<sub>Always curious. Always willing to revise an assumption.</sub>
