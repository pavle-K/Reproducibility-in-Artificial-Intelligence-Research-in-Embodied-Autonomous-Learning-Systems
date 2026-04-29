# Reproducibility in AI Research in Embodied and Multi-Agent Autonomous Learning Systems: Voyager Case Study

**Authors:** Pavle Kerkez (Bee Labs), Chris Piatt (Eden Network)

## Overview

This paper investigates reproducibility challenges in embodied and multi-agent AI systems, using Voyager — an autonomous LLM-powered agent that navigates Minecraft's technology tree — as a case study.

## Key Findings

- Early-game achievements were consistently reproducible across runs, while advanced achievements showed substantial variability and environmental dependence
- The inference module exhibited complete reproducibility failure: 0/9 successful task completions versus the originally reported 100% success rate
- Identified key reproducibility barriers: environmental variability, inter-agent communication issues, input ambiguity, and skill library overfitting
- Proposed modifications improved tool achievement rates from 33.3% to 83.3% and inference module success from 0% to 22%

## Why It Matters

Reproducibility is a foundational requirement for trustworthy AI research. Embodied and multi-agent systems present unique challenges because their behavior depends on dynamic environments and complex inter-agent interactions — not just model outputs in isolation. This work argues that reproducibility in this domain requires evaluating behavioral consistency across learning trajectories, not just final performance metrics.
