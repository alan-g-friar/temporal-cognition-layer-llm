[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19006506.svg)](https://doi.org/10.5281/zenodo.19006506)

# ChronoContext
## A Temporal Cognition Layer for Large Language Models

**Author:** Alan Friar  
**Organization:** EnBra Group  
**Version:** 1.1  
**Date:** 2026-03-15  

This repository contains the canonical, timestamped publication of the paper:

> *ChronoContext: A Temporal Cognition Layer for Large Language Models*

The paper examines a structural limitation in current Large Language Model (LLM) systems: the absence of an explicit representation of real-world time progression. While LLMs can interpret temporal language within prompts, they do not maintain persistent awareness of elapsed time between events or across conversations.

ChronoContext introduces a conceptual architecture for a lightweight temporal cognition layer that augments LLM interactions with chronological awareness. The system detects events, maintains structured timelines, computes temporal relationships, and injects temporal context into prompts before they are processed by an LLM.

A key component of the ChronoContext model is cross-session temporal continuity, enabling event anchors and timelines to persist across multiple conversational sessions. This allows LLM-assisted systems to reason about processes that evolve over days, weeks, or longer periods rather than within a single isolated conversation.

Version **1.1** includes documentation of a prototype middleware demonstration validating the architectural feasibility of the ChronoContext temporal cognition model.

## Contents

- `chronocontext.md` — canonical markdown version  
- `chronocontext.pdf` — publication-ready PDF  
- `chronocontext_prototype_run.md` — documented prototype execution  
- `chronocontext_temporal_reasoning_experiment.md` — temporal reasoning experiment  

## Citation

If referencing this work, please cite as:

Friar, A. (2026). *ChronoContext: A Temporal Cognition Layer for Large Language Models*.  
GitHub repository: https://github.com/alan-g-friar/temporal-cognition-layer-llm  
Version 1.1

## Status

This repository represents **version 1.1** of the ChronoContext paper.  
Future revisions, if any, will be versioned explicitly and committed separately.
