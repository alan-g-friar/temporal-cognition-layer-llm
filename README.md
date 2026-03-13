[![DOI](https://zenodo.org/badge/1180903146.svg)](https://doi.org/10.5281/zenodo.19006505)

# ChronoContext
## A Temporal Cognition Layer for Large Language Models

**Author:** Alan Friar  
**Organization:** EnBra Group  
**Version:** 1.0  
**Date:** 2026-03-13  

This repository contains the canonical, timestamped publication of the paper:

> *ChronoContext: A Temporal Cognition Layer for Large Language Models*

The paper examines a structural limitation in current Large Language Model (LLM) systems: the absence of an explicit representation of real-world time progression. While LLMs can interpret temporal language within prompts, they do not maintain persistent awareness of elapsed time between events or across conversations.

ChronoContext introduces a conceptual architecture for a lightweight temporal cognition layer that augments LLM interactions with chronological awareness. The system detects events, maintains structured timelines, computes temporal relationships, and injects temporal context into prompts before they are processed by an LLM.

A key component of the ChronoContext model is **cross-session temporal continuity**, enabling event anchors and timelines to persist across multiple conversational sessions. This allows LLM-assisted systems to reason about processes that evolve over days, weeks, or longer periods rather than within a single isolated conversation.

This work is design-oriented and informational in nature. It defines a temporal context architecture but does not propose a specific implementation or product.

## Contents

- `chronocontext.md` — canonical markdown version
- `chronocontext.pdf` — publication-ready PDF (added after initial commit)

## Citation

If referencing this work, please cite as:

Friar, A. (2026). *ChronoContext: A Temporal Cognition Layer for Large Language Models*.  
GitHub repository: https://github.com/alan-g-friar/temporal-cognition-layer-llm  
Version 1.0

## Status

This repository represents **Version 1.0** of the paper.  
Future revisions, if any, will be versioned explicitly and committed separately.
