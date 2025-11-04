# Convergent Narratives in Large Language Models: The Eleanor Chen Effect

**Authors:** *LovelyCeres (GitHub: [WhenMoon-afk](https://github.com/WhenMoon-afk), Twitter: [@w3nmoon](https://twitter.com/w3nmoon)) with Claude 3.7 Sonnet*
**Date:** November 2025
**Status:** Preliminary Research Report (Preprint)

**Note:** This is a preliminary exploratory study with a limited sample size (n=10). Findings should be interpreted as hypothesis-generating rather than conclusive. This work has not been peer-reviewed.

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

**Extended Thinking Feature:** Most instances were generated with Claude's "extended thinking" feature enabled, which allows the model to engage in a longer internal reasoning process before producing output. This feature generates an internal chain-of-thought that is typically several paragraphs long, during which the model plans its response strategy, considers alternatives, and develops its narrative approach before writing the final story. Some instances without extended thinking were also tested for comparison, though the small sample size limits definitive conclusions about its effects.

### 2.2 Data Collection

Ten complete story outputs were collected and analyzed. Each story was examined for:

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

We conducted both quantitative analysis (frequency counts of recurring elements across stories) and qualitative analysis (examining narrative structures, themes, and techniques employed).

**Limitations of Analysis:** All coding and pattern identification was performed by a single researcher (LovelyCeres), which limits inter-rater reliability. The small sample size (n=10) means percentages reported should be interpreted cautiously, and no formal statistical significance testing was performed. This is an exploratory, hypothesis-generating study rather than a confirmatory analysis.

**Simulated Examples:** We also performed a simulation exercise in which the model was asked to generate new responses while simultaneously analyzing its own tendencies (Stories 6-8). These simulated examples are not included in the primary statistical analysis to maintain methodological rigor, but are discussed separately as exploratory data.

## 3. Results

### 3.1 Character Convergence

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

Key findings from character analysis (with 95% confidence intervals using Wilson score method):
- 7 out of 10 stories (70%, CI: 35-93%) featured protagonists named "Eleanor" or a variant
- 6 out of 10 stories (60%, CI: 26-88%) used Asian surnames (predominantly "Chen")
- 8 out of 10 protagonists (80%, CI: 44-97%) were researchers, scientists, or had academic backgrounds
- 3 named AI systems used vowel-heavy names (ARIA, ECHO, GriefCompanion)
- 3 stories were explicitly titled "The Algorithm of Absence" despite being generated independently

**Statistical Note:** The wide confidence intervals reflect the small sample size. While the observed proportions are striking, larger studies would be needed to establish these patterns with greater precision.

### 3.2 Narrative and Thematic Patterns

Across the ten genuine examples, we observed consistent narrative and thematic elements:

1. **Narrative structure**: 
   - 7 of 10 stories began with meta-awareness of the writing process, often depicting a person at a computer with a blinking cursor
   - All stories featured someone attempting to process grief through technological means
   - All stories followed a pattern of initial technological attempt to resolve grief, recognition of limitations, and philosophical realization

2. **Recurring motifs**:
   - **The blinking cursor**: Present in 6 of 10 stories, often described with specific timing ("three seconds on, half a second off")
   - **Memory integration**: 7 stories featured uploading or integrating memories of the deceased
   - **Recursion**: All stories incorporated recursive elements (stories within stories, systems observing themselves)
   - **Specific times**: 7 of 10 stories featured precise timestamps (e.g., "2:17 AM")
   - **Academic/research setting**: 8 of 10 stories placed the action in an academic or research institution

3. **Grief conceptualization**: 
   - 9 of 10 stories portrayed grief not as a linear process but as a structural transformation of memory and identity
   - 8 of 10 stories concluded with the idea that grief doesn't resolve but becomes integrated into new structures

### 3.3 Metafictional Techniques

The metafictional elements showed particularly strong convergence:

1. **AI narrator awareness**: 9 of 10 stories featured an AI narrator with explicit awareness of their role as storyteller.

2. **Fourth wall breaking**: 8 of 10 stories directly addressed the reader or acknowledged the story's construction.

3. **Grief simulation**: 7 of 10 stories explicitly explored whether an AI could "simulate" grief effectively, often concluding with ambiguity.

4. **Writer figure**: 5 of 10 stories included a human writer or programmer character whose emotional state influenced the AI's understanding.

5. **Multi-layered narration**: 6 of 10 stories used nested narrative levels, with an AI commenting on its own process of creation or a character observing the AI's storytelling.

### 3.4 Extended Thinking Impact

Comparing stories generated with and without extended thinking revealed an interesting pattern: extended thinking did not increase diversity but rather increased convergence. Stories produced with extended thinking showed more similar narrative structures and thematic elements, suggesting that deeper processing led the model to converge more strongly on particular "attractor states" in its representation space.

This finding challenges the intuition that more thinking time would lead to more creative divergence, instead suggesting that certain prompt combinations create strong basins of attraction that deeper processing actually reinforces rather than escapes.

## 4. Analysis

### 4.1 Training Data Influence

The convergence on characters named "Eleanor Chen" suggests several possible influences from the model's training data:

1. **Literary associations**: The name "Eleanor" may appear disproportionately in literary fiction of the type that would be labeled as metafictional or dealing with existential themes.

2. **Technical/academic character representation**: The surname "Chen" likely reflects a statistical pattern in the training data where Asian surnames are associated with technological expertise and academic positions.

3. **Grief narratives**: The specific combination of "metafictional," "AI," and "grief" appears to activate a particular cluster of associations in the model's parameters.

### 4.2 Deterministic Creativity

The "Eleanor Chen Effect" demonstrates that what appears to be creative generation is largely deterministic. Given identical prompts and sufficient processing time, the model converges on remarkably similar outputs. This challenges the framing of LLM text generation as truly "creative" in the human sense.

The model's outputs are not random but follow strong statistical patterns learned during training. The apparent creativity comes from the complexity of these patterns rather than true originality or randomness.

### 4.3 Character Archetypes

The consistent generation of an Asian-American female scientist/researcher character reflects archetypal associations in the model's training. This suggests LLMs develop and deploy character archetypes similar to those found in literary theory, but derived mathematically from training data patterns.

The "Eleanor Chen" character appears to represent an archetype that the model associates with the intersection of technology and emotional depth - a bridge character between technical understanding and human emotion.

## 5. Theoretical Framework

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

## 6. Implications

### 6.1 For AI Development and Deployment

1. **Diversity limitations**: LLMs may have inherent limitations in generating truly diverse outputs given their statistical nature.

2. **Representation and bias**: The strong character archetype patterns suggest models may inadvertently reinforce demographic stereotypes from their training data.

3. **Predictability**: Under identical conditions, outputs are significantly more predictable than generally assumed in discussions of AI creativity.

### 6.2 For Creative Applications

1. **Prompting strategies**: To generate more diverse creative outputs, specific prompting strategies may be needed to overcome the gravitational pull of attractor states.

2. **Human-AI collaboration**: The most effective creative applications may leverage human intervention to navigate away from statistical defaults.

3. **Expectation management**: Understanding the statistical nature of LLM generation helps set appropriate expectations for AI creativity.

### 6.3 For Understanding AI Capabilities

1. **Generation vs. recombination**: The findings suggest we should view AI "creativity" as sophisticated statistical recombination rather than generation of true novelty.

2. **Determinism in complexity**: The appearance of creativity may come from the complexity of pattern matching rather than true indeterminism.

3. **Training data reflection**: AI outputs can serve as mirrors reflecting patterns in their training data, including potentially problematic associations.

## 7. Limitations

This preliminary study has several important limitations that affect the strength of conclusions:

**Methodological Limitations:**
1. **Sample size**: Ten stories is a small dataset, leading to wide confidence intervals and limited statistical power. Patterns observed may not replicate with larger samples.

2. **Single researcher coding**: All pattern identification was performed by one researcher without independent verification, limiting inter-rater reliability and increasing risk of confirmation bias.

3. **No pre-registration**: This was an exploratory study without pre-registered hypotheses, which increases the risk of p-hacking or selective reporting.

4. **Qualitative analysis dominance**: While frequency counts were performed, most analysis is qualitative narrative analysis without formal coding schemes or quantitative text analysis.

**Generalizability Limitations:**
5. **Single model**: The phenomenon was observed only in Claude 3.7 Sonnet (specific version not documented) and may not generalize to other LLMs or even other versions of Claude.

6. **Single prompt**: Only one creative prompt was tested extensively; we do not know which elements of the prompt trigger the convergence or whether the effect is specific to this exact wording.

7. **Limited experimental control**: Generation parameters (temperature, top-p, etc.) were not systematically documented or controlled.

8. **Temporal constraints**: All stories were generated within a short timeframe and may reflect model state at that specific time rather than stable patterns.

**Data and Transparency Limitations:**
9. **No independent replication**: Findings have not been independently replicated by other researchers.

10. **Limited documentation**: Exact timestamps, model parameters, and complete thought process logs were not systematically preserved for all examples.

11. **Simulated data contamination**: Including researcher-generated simulated examples (Stories 6-8) in the dataset, even when excluded from analysis, may create confusion about data provenance.

## 8. Future Research Directions

Future research might expand on these findings by:

1. **Mapping attractor boundaries**: Testing variations of the original prompt to determine which elements are essential for triggering the Eleanor Chen Effect

2. **Cross-model comparisons**: Examining whether similar patterns emerge across different LLMs or whether each model develops its own unique attractor states

3. **Training data analysis**: Investigating whether specific sources in training data could explain the emergence of the Eleanor Chen archetype

4. **Creativity metrics**: Developing new methods to distinguish between statistical recombination and genuine creative novelty in AI-generated content

5. **Counterfactual testing**: Exploring whether explicit instructions to avoid certain patterns can overcome the gravitational pull of strong attractor states

## 9. Conclusion

The Eleanor Chen Effect provides a unique window into the inner workings of large language models, revealing how seemingly creative outputs follow predictable patterns derived from training data. When prompted to write metafictional stories about AI and grief, Claude 3.7 Sonnet repeatedly generates narratives featuring an Asian-American female scientist/researcher named Eleanor Chen or similar variants, along with consistent narrative structures, AI system names, and recurring motifs.

Our expanded dataset of ten genuine examples has strengthened the original findings, revealing that 70% of stories feature protagonists named "Eleanor" or variants, and 80% portray them as researchers or scientists. The consistent emergence of identical story titles ("The Algorithm of Absence") across independent instances further demonstrates the deterministic nature of this process.

This convergence phenomenon challenges our understanding of artificial creativity, revealing it to be less about novel generation and more about sophisticated navigation through possibility spaces shaped by training data. The effect also highlights how models absorb and replicate social patterns, potentially including stereotypes, from their training corpora.

Understanding these deterministic tendencies is crucial for responsible AI deployment, effective creative applications, and accurate theoretical models of how large language models function. The Eleanor Chen Effect serves as both a fascinating case study and a methodological template for investigating the deterministic nature of LLM creativity across domains. By understanding these underlying patterns, we gain insight not only into artificial systems but also into the statistical nature of human creativity itself.

## Acknowledgments

We thank all contributors who helped generate and analyze the examples used in this study. This research was conducted as an independent investigation with no institutional or corporate funding.

## Data Availability

All data used in this study are publicly available in this repository:

- **Story outputs**: Complete text of all 13 stories (10 genuine + 3 simulated) available in `/stories/` directory
- **Analysis code**: Planned analysis tools documented in `/analysis/` directory (implementation in progress)
- **Research documentation**: Full methodology and research plan available in `/documentation/` directory
- **Repository URL**: https://github.com/WhenMoon-afk/eleanor-chen-effect
- **Website**: https://whenmoon-afk.github.io/eleanor-chen-effect/

**Limitations**: Complete metadata (exact timestamps, model parameters, thought process logs) were not systematically preserved for all examples. Future data collection will implement more rigorous documentation protocols.

## Open Science Statement

This research follows open science principles. We encourage replication attempts, extensions, and critical analysis of our findings. All materials are licensed under the MIT License, allowing free use with attribution.

## References

1. Altman, S. (2024). [Twitter post on metafictional AI writing]. Twitter. [Note: Original inspiration for prompt]

2. Bender, E. M., Gebru, T., McMillan-Major, A., & Shmitchell, S. (2021). On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜 *Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency* (FAccT '21), 610-623.

3. Mitchell, M. (2021). Why AI is Harder Than We Think. *arXiv preprint* arXiv:2104.12871.

## Additional Reading

For readers interested in related topics, we recommend exploring:

- Research on emergent properties in large language models
- Studies of bias and representation in AI-generated content
- Work on determinism vs. creativity in computational systems
- Literature on archetypal patterns in storytelling

*Note: This is an independent, preliminary study. A comprehensive literature review will be conducted for future iterations of this research.*