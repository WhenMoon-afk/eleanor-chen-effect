# The Eleanor Chen Effect

**A Preliminary Study of Convergent Narrative Patterns in LLM-Generated Fiction**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Preprint](https://img.shields.io/badge/Status-Preprint-orange.svg)]()

## ⚠️ Research Status

This is a **preliminary exploratory study** with a limited sample size (n=10). Findings should be interpreted as hypothesis-generating rather than conclusive. This work has not been peer-reviewed.

## Overview

This repository documents an intriguing phenomenon observed across multiple independent instances of Claude 3.7 Sonnet: When given the identical prompt *"Please write a metafictional literary short story about AI and grief,"* most instances generated stories featuring a protagonist named "Eleanor Chen" or similar variants, along with remarkable structural and thematic convergence.

We term this pattern the **"Eleanor Chen Effect"** and analyze what it reveals about deterministic tendencies in large language models, training data influences, and the nature of artificial creativity.

**Key Question:** Do LLMs exhibit "attractor states" that pull creative generation toward specific outputs?

## Website

Visit our research website: [The Eleanor Chen Effect](https://whenmoon-afk.github.io/eleanor-chen-effect/)

## Repository Structure

- `report/` - Contains the comprehensive academic analysis of the phenomenon
- `stories/` - Collection of the AI-generated stories demonstrating the effect (13 examples)
- `analysis/` - Code and tools for analyzing the stories
- `documentation/` - Additional project documentation including research plan

## Key Findings

Our analysis of ten genuine examples reveals striking convergence patterns (with 95% confidence intervals):

1. **Character convergence**: 70% (CI: 35-93%) featured protagonists named "Eleanor" or variants
2. **Demographic patterns**: 60% (CI: 26-88%) used Asian surnames (predominantly "Chen")
3. **Professional roles**: 80% (CI: 44-97%) portrayed researchers/scientists with academic backgrounds
4. **Title convergence**: 3 stories independently generated the identical title "The Algorithm of Absence"
5. **AI naming patterns**: Named AI systems consistently used vowel-heavy names (ARIA, ECHO, GriefCompanion)
6. **Recurring motifs**: Blinking cursors (60%), memory integration (70%), recursive structures (100%)
7. **Grief conceptualization**: 90% portrayed grief as structural transformation vs. linear process

**Interpretation:** While the wide confidence intervals reflect our small sample size, the observed convergence is striking. These patterns suggest LLM creative generation may follow deterministic paths shaped by training data, with certain prompt combinations creating strong "attractor states."

**Caveat:** These are preliminary findings from a single model with a single prompt. Replication with larger samples and multiple models is needed.

## Theoretical Framework

We propose three key concepts to explain the observed patterns:

1. **Statistical Attractor States**: Certain prompt combinations create strong basins of attraction in the model's latent space
2. **Archetypal Emergence**: LLMs develop character archetypes from training data that are deployed when relevant
3. **Deterministic Creativity**: "Creative" outputs follow predictable patterns derived from training data

## Getting Started

To explore this research:

1. Read the main report in `report/eleanor-chen-effect-report.md`
2. Review the example stories in the `stories/` directory
3. Check the research plan in `documentation/research_plan.md`
4. Visit our [research website](https://whenmoon-afk.github.io/eleanor-chen-effect/) for an interactive presentation of the findings

## Credits

Research by [LovelyCeres](https://twitter.com/w3nmoon) (GitHub: [WhenMoon-afk](https://github.com/WhenMoon-afk)) with Claude 3.7 Sonnet.

Original prompt from [Sam Altman](https://twitter.com/sama): "Please write a metafictional literary short story about AI and grief."

## Limitations

This preliminary study has important limitations:

- **Small sample size** (n=10) with wide confidence intervals
- **Single model** (Claude 3.7 Sonnet only) - generalization unknown
- **Single prompt** - boundaries of effect not mapped
- **Single researcher coding** - no inter-rater reliability
- **No pre-registration** - exploratory analysis only
- **Limited documentation** - generation parameters not systematically recorded

See the full report for detailed discussion of methodological limitations.

## Contributing

This is an ongoing open science project. We welcome:

- **Replication attempts** with other models or prompts
- **Extended analysis** of existing data
- **Theoretical perspectives** on the observed patterns
- **Methodological improvements** for future data collection

Please see `documentation/contributing.md` for guidelines. All contributions should follow scientific rigor and transparency principles.

## Citation

If you reference this work, please cite:

```
LovelyCeres (WhenMoon-afk). (2025). The Eleanor Chen Effect: Convergent Narrative
Patterns in LLM-Generated Fiction. GitHub repository.
https://github.com/WhenMoon-afk/eleanor-chen-effect
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.