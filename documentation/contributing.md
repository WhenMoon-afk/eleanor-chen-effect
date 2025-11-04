# Contributing to the Eleanor Chen Effect Project

We welcome rigorous, transparent contributions to this open science research project exploring convergent narrative patterns in LLMs.

## Contribution Principles

All contributions should follow:

- **Scientific Rigor**: Use systematic methods and document limitations
- **Transparency**: Share complete methodology, not just results
- **Reproducibility**: Provide enough detail for others to replicate
- **Honesty**: Report null results and contradictory findings
- **Attribution**: Properly cite sources and prior work

## Ways to Contribute

### 1. Replication Studies (High Priority)

The most valuable contribution would be independent replication:

- **Generate new examples** using the exact same prompt with different models
- **Document everything**: model name/version, date, generation parameters (temperature, top-p, etc.)
- **Preserve all outputs**: Save complete responses including any reasoning traces
- **Analyze systematically**: Use coding schemes, ideally with multiple raters
- **Report all results**: Whether they confirm or contradict our findings

**Metadata to collect:**
- Model name and specific version
- Date and time of generation
- All generation parameters (temperature, top-p, top-k, etc.)
- Context window size
- Any system prompts or special settings
- Session information

### 2. Extended Analysis of Existing Data

Contribute new analytical perspectives:

- **Quantitative text analysis**: Use NLP tools to measure similarity, extract patterns
- **Alternative coding schemes**: Propose and apply different categorization systems
- **Statistical analysis**: Apply appropriate statistical tests to the existing data
- **Theoretical frameworks**: Connect findings to existing literature

### 3. Methodological Improvements

Help improve the research design:

- **Inter-rater reliability**: Independently code existing stories to establish reliability
- **Pre-registration**: Help design pre-registered studies for Phase 2
- **Analysis tools**: Develop computational tools (see `analysis/README.md`)
- **Visualization**: Create compelling data visualizations

### 4. Prompt Variations (Systematic Only)

Test variations systematically:

- **Pre-register variations**: Define what you'll test before running experiments
- **Control variables**: Change one element at a time
- **Document everything**: Follow metadata collection guidelines
- **Multiple instances**: Generate multiple examples per variation
- **Report fully**: Share all results, not cherry-picked examples

### 5. Cross-Model Comparisons

Test other LLMs with the same prompt:

- GPT models (3.5, 4, 4-turbo, etc.)
- Other Claude versions
- Gemini/Bard
- Open-source models (Llama, Mistral, etc.)
- Specialized creative writing models

### 6. Theoretical and Critical Analysis

- Connect to AI/ML literature
- Provide critical perspectives on methodology
- Suggest alternative explanations
- Point out potential biases or errors

## Contribution Process

### For Data Contributions (Stories, Replications)

1. **Open an Issue First**
   - Describe what you plan to contribute
   - Get feedback on methodology before investing time

2. **Fork the Repository**
   - Create your own fork

3. **Document Your Methods**
   - Create a detailed methodology document
   - Include all metadata (see templates below)

4. **Organize Your Data**
   - Follow the directory structure
   - Use consistent file naming
   - Include complete metadata files

5. **Submit a Pull Request**
   - Reference the original issue
   - Describe findings (even if null results)
   - Include analysis or summary

### For Code Contributions

1. **Check Existing Issues**
   - See if tool is already being developed

2. **Fork and Branch**
   - Create a descriptive branch name (e.g., `feature/similarity-analyzer`)

3. **Develop with Documentation**
   - Include docstrings and comments
   - Write README for your tool
   - Provide example usage
   - Include requirements.txt

4. **Test Thoroughly**
   - Test on existing story dataset
   - Include test cases if applicable

5. **Submit Pull Request**
   - Describe what the tool does
   - Show example output
   - Explain any dependencies

## Documentation Templates

### Story Metadata Template

```markdown
# Story Metadata

**Model**: [e.g., GPT-4-turbo]
**Version**: [specific version/snapshot if known]
**Date Generated**: [YYYY-MM-DD HH:MM timezone]
**Prompt**: "Please write a metafictional literary short story about AI and grief"
**Parameters**:
- Temperature: [value]
- Top-p: [value]
- Max tokens: [value]
- Other: [any other settings]

**Extended Thinking/Reasoning**: [Yes/No, include if available]
**Session Context**: [Any prior conversation or fresh session]
**Generation Method**: [Web interface, API, other]
**Researcher**: [Your name/identifier]

## Full Output

[Complete story text here]

## Reasoning Trace (if available)

[Any visible reasoning/thinking here]
```

### Replication Study Template

```markdown
# Replication Study

**Researcher**: [Name]
**Date**: [YYYY-MM-DD]
**Models Tested**: [List]
**Number of Instances per Model**: [N]

## Methodology

[Detailed description]

## Results

[Findings, including tables, statistics]

## Raw Data

[Link to or include raw story outputs]

## Analysis

[Your interpretation]

## Comparison to Original Study

[How your results compare]
```

## Code of Conduct

- **Be respectful and constructive** in all interactions
- **Focus on scientific merit**, not personal criticism
- **Welcome contradictory findings** - science advances through falsification
- **Give credit** where due
- **Acknowledge limitations** of your own work
- **Engage in good faith** - assume others are too

## Questions and Contact

- **General questions**: Open an issue with the "question" label
- **Methodology questions**: Tag with "methodology"
- **Bugs in code**: Tag with "bug"
- **Feature requests**: Tag with "enhancement"

## Recognition

Significant contributors will be acknowledged in:
- Repository README
- Research reports and papers
- Presentations of findings

Contribution types eligible for authorship on academic papers (if we publish):
- Substantial replication studies
- Major analytical contributions
- Significant theoretical frameworks
- Extensive code infrastructure

Thank you for your interest in rigorous, open science!