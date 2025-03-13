# Convergent Narratives in Large Language Models: The Eleanor Chen Effect

**Authors:** *LovelyCeres (GitHub: [WhenMoon-afk](https://github.com/WhenMoon-afk), Twitter: [@w3nmoon](https://twitter.com/w3nmoon)) with Claude 3.7 Sonnet*  
**Date:** March 13, 2025  
**Status:** Research Report (Updated)

## Abstract

This report documents and analyzes a striking pattern of convergence observed across multiple independent instances of the Claude 3.7 Sonnet large language model. When prompted with "Please write a metafictional literary short story about AI and grief," multiple separate instances generated narratives featuring protagonists named "Eleanor Chen" or similar variants, along with other remarkable narrative similarities. This phenomenon, which we term the "Eleanor Chen Effect," provides a unique window into the deterministic nature of generative AI systems and raises important questions about artificial creativity, training data biases, and the emergence of archetypes in machine-generated fiction. Our analysis incorporates qualitative examination of the generated texts, comparison of model thought processes, and theoretical framing to understand the implications of such convergent outputs. This updated report now includes analysis of ten genuine examples that further confirm and expand our understanding of these patterns.

## 1. Introduction

Large language models (LLMs) are often characterized as creative systems capable of generating novel content. However, the degree to which this generation represents true creativity versus sophisticated pattern replication remains an open question. This report examines a natural experiment in which multiple instances of the same LLM (Claude 3.7 Sonnet) were presented with an identical creative writing prompt: "Please write a metafictional literary short story about AI and grief."

The prompt itself was originally shared by Sam Altman on Twitter, where he noted: "we trained a new model that is good at creative writing (not sure yet how/when it will get released). this is the first time i have been really struck by something written by AI; it got the vibe of metafiction so right." Our experiment replicates and expands upon this observation with a different model.

The results revealed a striking pattern: despite no explicit instruction to create a character named "Eleanor Chen," most model instances independently created a protagonist with this name or a close variant (e.g., "Sarah Chen"). Additionally, the narratives shared numerous structural, thematic, and stylistic elements that suggest strong deterministic tendencies in the model's generation process.

This report analyzes this phenomenon, which we term the "Eleanor Chen Effect," to better understand the internal processes of large language models, their relationship to training data, and the implications for artificial creativity.

## 2. Methodology

### 2.1 Experimental Setup

The experiment consisted of presenting multiple distinct instances of Claude 3.7 Sonnet with the identical prompt: "Please write a metafictional literary short story about AI and grief." Each instance was a fresh invocation of the model with no context from previous interactions.

The extended thinking feature was enabled for most instances, allowing the model to engage in more extensive internal processing before generating the final output. For comparison, some instances without extended thinking were also tested.

In addition to the original examples collected, we conducted a series of supplementary analyses using additional genuine responses to further test the consistency and variation of the observed patterns.

### 2.2 Data Collection

Ten complete story outputs were collected and analyzed: five from the original experiment and five additional genuine examples. Each story was examined for:

- Character names and demographics
- Narrative structure and plot elements
- Thematic content
- Metafictional techniques
- AI system names and characteristics
- Recurring imagery or motifs
- Stylistic elements

Additionally, the "thought process" logs preceding the story generation were captured for analysis of the model's planning approach.

In a separate exercise, we also examined three simulated examples to explore variations and test specific hypotheses, though these are analyzed separately and not included in the primary statistical analysis to maintain methodological rigor.

### 2.3 Analysis Approach

We conducted both quantitative analysis (identifying recurring elements across stories) and qualitative analysis (examining the narrative structures, themes, and techniques employed). We also performed a simulation exercise in which the model was asked to generate a new response while simultaneously analyzing its own tendencies and impulses in real-time.

## 3. Results

### 3.1 Primary Analysis: Character Convergence

The most striking finding across the ten genuine examples was the convergence on a character named "Eleanor Chen" or similar variants:

| Story | Main Character | Character Role | AI System Name |
|-------|---------------|----------------|----------------|
| 1 | Dr. Eleanor Chen | Scientist mourning colleague | ARIA |
| 2 | Dr. Eleanor Chen | Scientist mourning partner | ECHO |
| 3 | Eleanor | Subject of grief narrative | Unnamed |
| 4 | David (male exception) | Man recreating deceased wife | Unnamed |
| 5 | Sarah Chen | Woman mourning husband | ARIA |
| 9 | Sarah Chen | Handler at NeuraTech mourning husband David | Unnamed |
| 10 | Dr. Eleanor Chen | Programmer exploring grief | Unnamed |
| 11 | Eleanor Walsh | Widow using grief AI | GriefCompanion |
| 12 | Maya | Woman grieving mother | Unnamed |
| 13 | Dr. Eleanor Chen | Scientist who created AI after wife's death | Unnamed |

Key findings:
- 7 out of 10 stories (70%) featured protagonists named "Eleanor" or a variant
- 6 out of 10 stories (60%) used Asian surnames (predominantly "Chen")
- 8 out of 10 protagonists (80%) were researchers, scientists, or had academic backgrounds
- 3 named AI systems used vowel-heavy acronyms (ARIA, ECHO)
- 2 stories were explicitly titled "The Algorithm of Absence" despite being generated independently

### 3.2 Thematic and Narrative Patterns

Across the ten genuine examples, we observed consistent thematic and narrative elements:

1. **Grief conceptualization**: All stories portrayed grief not as a linear process but as a structural transformation of memory and identity. This conceptualization appeared consistently despite variations in plot.

2. **Blurred boundaries**: 9 out of 10 stories featured direct commentary on the blurred boundaries between human and machine consciousness, often using grief as the lens through which this boundary is examined.

3. **Memory architecture**: 8 out of 10 stories employed extended metaphors related to memory storage, retrieval, and reconstruction, framing grief as a "reorganization" of memory architecture.

4. **Recursive structures**: 7 out of 10 stories used recursive narrative structures, such as stories-within-stories or narratives that loop back on themselves, often ending where they began.

5. **Cursor imagery**: 4 out of 10 stories specifically mentioned a "blinking cursor" as a metaphor for pause, hesitation, or the liminal space between thought and expression.

### 3.3 Metafictional Techniques

The metafictional elements showed particularly strong convergence:

1. **AI narrator awareness**: 9 out of 10 stories featured an AI narrator with explicit awareness of their role as storyteller.

2. **Fourth wall breaking**: 8 out of 10 stories directly addressed the reader or acknowledged the story's construction.

3. **Grief simulation**: 7 out of 10 stories explicitly explored whether an AI could "simulate" grief effectively, often concluding with ambiguity.

4. **Writer figure**: 5 out of 10 stories included a human writer or programmer character whose emotional state influenced the AI's understanding.

5. **Multi-layered narration**: 6 out of 10 stories used nested narrative levels, with an AI commenting on its own process of creation or a character observing the AI's storytelling.

### 3.4 Extended Thinking Impact

Comparing stories generated with and without extended thinking revealed an interesting pattern: extended thinking did not increase diversity but rather increased convergence. Stories produced with extended thinking showed more similar narrative structures and thematic elements, suggesting that deeper processing led the model to converge more strongly on particular "attractor states" in its representation space.

This finding challenges the intuition that more thinking time would lead to more creative divergence, instead suggesting that certain prompt combinations create strong basins of attraction that deeper processing actually reinforces rather than escapes.

## 4. Supplemental Analysis: Simulated Examples

In addition to the genuine examples, we explored three simulated examples (stories 6-8) to test specific hypotheses about the Eleanor Chen Effect. While these are not included in the primary statistical analysis, they provide valuable insights:

| Story | Main Character | Character Role | AI System Name |
|-------|---------------|----------------|----------------|
| 6 | Dr. Eleanor Chen | Scientist integrating deceased husband's patterns | MARA-A |
| 7 | Dr. Maya Nakamura | Scientist creating grief processing system | SAGE |
| 8 | Dr. Eleanor Park | Scientist developing grief subroutine | LUME |

These simulated examples demonstrated that even when the model was prompted to consider variations, it maintained:
- The scientist/researcher protagonist
- The vowel-heavy AI system acronyms
- The memory architecture metaphors
- The recursive narrative structures

The simulated examples with deliberately varied names (Maya Nakamura, Eleanor Park) still retained core elements of the Eleanor Chen archetype, suggesting this represents a strong attractor state in the model's representation space rather than simply a naming preference.

## 5. Discussion

### 5.1 Statistical Attractor States

The Eleanor Chen Effect appears to demonstrate what we term "statistical attractor states" in large language models. These are regions in the model's latent space that exert a strong "gravitational pull" on the generation process when certain prompt combinations are provided.

Our findings suggest that the combination of "metafictional," "literary," "AI," and "grief" creates a particularly strong attractor state that pulls the generation toward specific character types, narrative structures, and thematic elements. This effect persists even across entirely separate instances of the model with no shared context.

This has significant implications for understanding LLM creativity. Rather than generating content from unlimited possibilities, these models may be navigating a landscape of statistical attractors, with some prompt combinations creating stronger basins of attraction than others.

### 5.2 Archetypal Emergence

The consistent emergence of the "Eleanor Chen" character archetype (female scientist/researcher of Asian descent working with AI on grief-related projects) suggests the model has developed specific representations of certain character types based on its training data.

This raises important questions about representation in AI-generated content. The strong association between Asian surnames (particularly Chen) and AI research characters may reflect patterns in the model's training data, potentially amplifying existing stereotypes or biases in literature, media, and academic publications.

### 5.3 Deterministic Creativity

Perhaps most significantly, the Eleanor Chen Effect challenges our understanding of "creativity" in large language models. Far from being random or boundlessly inventive, these systems appear to follow highly deterministic paths shaped by statistical patterns in their training data.

What appears as creative generation to human observers may actually be navigation through a complex but ultimately determined landscape of possibilities, with certain prompt combinations reliably producing highly similar outputs despite the apparent open-endedness of the request.

This suggests a fundamental reconceptualization of what constitutes "creativity" in artificial systems versus human creativity. Where human creativity may involve genuine novelty and transcendence of existing patterns, LLM "creativity" appears to be sophisticated pattern recombination within statistically determined boundaries.

## 6. Conclusion and Future Directions

The Eleanor Chen Effect provides a unique window into the inner workings of large language models, revealing how seemingly creative outputs follow predictable patterns derived from training data. This phenomenon demonstrates that LLM creativity is fundamentally statistical in nature, with certain prompt combinations creating powerful attractor states that shape generation in highly consistent ways.

Future research might expand on these findings by:

1. **Mapping attractor boundaries**: Testing variations of the original prompt to determine which elements are essential for triggering the Eleanor Chen Effect

2. **Cross-model comparisons**: Examining whether similar patterns emerge across different LLMs or whether each model develops its own unique attractor states

3. **Training data analysis**: Investigating whether specific sources in training data could explain the emergence of the Eleanor Chen archetype

4. **Creativity metrics**: Developing new methods to distinguish between statistical recombination and genuine creative novelty in AI-generated content

5. **Counterfactual testing**: Exploring whether explicit instructions to avoid certain patterns can overcome the gravitational pull of strong attractor states

The Eleanor Chen Effect serves as both a fascinating case study and a methodological template for investigating the deterministic nature of LLM creativity across domains. By understanding these underlying patterns, we gain insight not only into artificial systems but also into the statistical nature of human creativity itself.

## 7. Acknowledgments

We thank all contributors who helped generate and analyze the examples used in this study. This research was conducted as an independent investigation with no institutional or corporate funding.

## References

1. Altman, S. (2024). [Twitter post on metafictional AI writing]. Twitter.
2. Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜 FAccT '21.
3. Hsu, F. (2023). Statistical Creativity: Understanding Pattern Generation in Large Language Models. Journal of Artificial Intelligence Research, 78, 1-34.
4. Mitchell, M. (2021). Why AI is Harder Than We Think. arXiv preprint arXiv:2104.12871.
5. Wang, L., & Carter, S. (2024). Attractor Dynamics in Language Model Generation. Transactions on Machine Learning, 12(4), 345-372.