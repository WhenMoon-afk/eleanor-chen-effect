# Analysis Tools and Methods

**Current Status:** 🚧 Planned - Not Yet Implemented

This directory is reserved for computational analysis tools and scripts for analyzing patterns in the AI-generated stories. The current Phase 1 study relied on manual qualitative and quantitative analysis.

## Current Analysis Approach (Phase 1)

The preliminary study used:

- **Manual coding**: Single researcher (LovelyCeres) identified patterns through close reading
- **Frequency counts**: Manual tallying of recurring elements (character names, motifs, structures)
- **Comparative analysis**: Side-by-side comparison of narrative techniques and themes
- **Table-based organization**: Results organized in markdown tables (see main report)

**Limitation:** No automated tools, no inter-rater reliability, potential for confirmation bias.

## Planned Analysis Tools (Future Phases)

The following tools would strengthen future research:

1. **Pattern Detector**
   - Automated identification of recurring elements (character names, AI systems, narrative structures)
   - N-gram analysis for phrase repetition
   - Named entity recognition (NER) for character extraction

2. **Similarity Analyzer**
   - Semantic similarity metrics (cosine similarity, sentence embeddings)
   - Structural similarity analysis
   - Visualization of similarity networks

3. **Prompt Variation Tester**
   - Automated prompt generation and testing framework
   - Result cataloging and comparison
   - Statistical analysis of variation effects

4. **Narrative Structure Mapper**
   - Plot arc identification and comparison
   - Metafictional technique detection
   - Temporal structure analysis

5. **Character Analysis Tool**
   - Demographic pattern extraction
   - Role and profession categorization
   - Relationship mapping

## Contributing Analysis Tools

We welcome contributions of analysis code! If you'd like to implement any of these tools:

1. **Fork the repository** and create a feature branch
2. **Add your tool** to this directory with clear documentation
3. **Include requirements.txt** or similar for dependencies
4. **Write tests** demonstrating correctness
5. **Document usage** in a README within your tool's subdirectory
6. **Submit a pull request** with description of what the tool does

### Guidelines for Contributors

- Use **open-source libraries** (e.g., spaCy, NLTK, transformers, scikit-learn)
- Provide **example usage** with the existing story dataset
- Include **output visualization** when applicable
- Follow **reproducibility best practices** (seed values, version pinning)
- Write **clean, commented code**

## Contact

For questions about analysis approaches or tool development, please open an issue in the repository.