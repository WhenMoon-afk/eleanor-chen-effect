# Contributing to the Eleanor Chen Effect Project

We welcome contributions to this research project exploring convergent narrative patterns in LLMs. Here's how you can help:

## Ways to Contribute

1. **Submit Additional Examples**
   - Generate new examples of stories using the prompt "Please write a metafictional literary short story about AI and grief"
   - Document the model used, any special settings (like extended thinking), and capture the full output
   - Submit via pull request or issue

2. **Test Prompt Variations**
   - Try modified versions of the original prompt
   - Document exactly what prompt was used and the resulting output
   - Note any patterns that persist or change with prompt modifications

3. **Code Contributions**
   - Develop or improve analysis tools in the `analysis/` directory
   - Add visualization capabilities for the observed patterns
   - Create tools for prompt testing and result comparison

4. **Analysis and Insights**
   - Contribute theoretical perspectives on the observed phenomena
   - Connect findings to relevant research in AI, cognitive science, or literary theory
   - Suggest new directions for investigation

## Contribution Process

1. **Fork the Repository**
   - Create your own fork of this repository

2. **Create a Branch**
   - Make your changes in a new branch

3. **Submit a Pull Request**
   - Provide a clear description of your contribution
   - Reference any relevant issues

4. **Code of Conduct**
   - Be respectful and constructive in all interactions
   - Focus on the scientific and technical aspects of the research

## Documentation Guidelines

### For Story Submissions

- All authentic stories should be saved as Markdown files in the `data/stories/` directory
- Simulated or test examples should go in `data/simulated_examples/`
- Name files consistently following the pattern `story_XX.md` where XX is a sequential number
- Update `data/metadata.csv` with the new story's information
- Update `data/README.md` to reflect the new addition
- Do not modify the story text after generation - submit exactly as generated

### For Analysis Code

- Place analysis scripts in the `analysis/` directory
- Include clear comments and docstrings
- Add dependencies to `analysis/requirements.txt`
- Update `analysis/README.md` with usage instructions
- Include example outputs or expected results

## Questions and Contact

If you have questions about contributing, please open an issue in the repository.

Thank you for your interest in this research!