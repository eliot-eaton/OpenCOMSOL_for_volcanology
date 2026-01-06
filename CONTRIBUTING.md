# Contributing to OpenCOMSOL for Volcanology

Thank you for your interest in contributing to this repository! This guide will help you share your COMSOL models, ideas, and improvements with the volcanology community.

## 📋 Table of Contents

- [Types of Contributions](#types-of-contributions)
- [Before You Contribute](#before-you-contribute)
- [Submission Guidelines](#submission-guidelines)
- [Model Documentation Requirements](#model-documentation-requirements)
- [Code of Conduct](#code-of-conduct)

## Types of Contributions

### 1. Published Models
Submit complete, peer-reviewed models associated with published research.

**Requirements:**
- Model must be associated with a published scientific paper
- Complete documentation and validation results
- All input files and parameters included
- Clear citation information

**Submission location:** `/published_models/`

### 2. Unfinished/unpublished Models
Share work-in-progress models for feedback and collaboration. This would be a great location for models that may not have been published or finished during a research project but are valuable to the members of the commmunity. 

**Requirements:**
- Description of current development stage
- Known issues and limitations documented
- Clear goals for completion
- Contact information for collaboration

**Submission location:** `/unfinished_models/`

### 3. Model Ideas
Propose concepts for future COMSOL models.

**Requirements:**
- Clear description of the research question
- Relevant physics modules identified
- Scientific motivation explained
- Optional: Literature references

**Submission location:** `/model_ideas/`

## Before You Contribute

1. **Search existing models**: Check if similar models already exist
2. **Review guidelines**: Read the README in the target directory
3. **Prepare documentation**: Gather all necessary files and information
4. **Check licensing**: Ensure you have rights to share the model
5. **Test your model**: Verify that model files work correctly

## Submission Guidelines

### Step 1: Prepare Your Contribution

#### For Published/Unfinished Models:

Create a directory structure:
```
your_model_name/
├── README.md              # Required: Model description
├── your_model.mph         # Required: COMSOL model file(s)
├── parameters/            # Recommended: Parameter files
│   ├── default_params.txt
│   └── sensitivity_params.txt
├── results/               # Recommended: Example results
│   ├── figures/
│   └── data/
├── documentation/         # Optional: Additional docs
│   ├── theory.pdf
│   └── validation.pdf
└── scripts/               # Optional: Pre/post-processing scripts
```

#### For Model Ideas:

Create a markdown file:
```
your_idea_name.md
```

### Step 2: Create Your README.md

Every model submission must include a README.md with:

```markdown
# Model Name

## Overview
Brief description of the model and its purpose.

## Citation
[Required for published models]
Author(s). (Year). Title. Journal, Volume(Issue), pages. DOI

## Physics Modules Used
- Heat Transfer
- Structural Mechanics
- Fluid Flow
- [etc.]

## Model Description
Detailed description of:
- Governing equations
- Geometry and mesh
- Boundary conditions
- Material properties
- Solution approach

## Parameters
Key parameters and their default values.

## Results
Description of expected outputs and validation.

## COMSOL Version
- COMSOL Version: X.X
- Required Modules: [list]
- Operating System: [if relevant]

## Usage Instructions
Step-by-step guide to run the model.

## Known Limitations
Any limitations or assumptions.

## Contact
Your name and email (if you wish to be contacted).

## License
Specify the license for your model (if different from repository default).
```

### Step 3: Submit Your Contribution

#### Option A: Pull Request (Recommended)

1. Fork the repository
2. Create a new branch: `git checkout -b add-model-name`
3. Add your files to the appropriate directory
4. Commit your changes: `git commit -m "Add [model name]"`
5. Push to your fork: `git push origin add-model-name`
6. Open a Pull Request with:
   - Clear title describing your contribution
   - Description of the model and its significance
   - Any special notes for reviewers

#### Option B: Issue Submission

If you're not familiar with Git:
1. Open a new Issue
2. Use the title: "Model Submission: [Model Name]"
3. Provide a download link to your files (e.g., Zenodo, institutional repository)
4. Include all required documentation in the issue description

### Step 4: Review Process

1. Maintainers will review your submission
2. You may be asked for clarifications or modifications
3. Once approved, your contribution will be merged
4. You'll be acknowledged as a contributor

## Model Documentation Requirements

### Minimum Requirements

✅ **Must Have:**
- Model name and brief description
- COMSOL version and required modules
- Basic usage instructions
- Contact information or attribution

✅ **For Published Models:**
- Full citation with DOI
- Validation results
- Complete parameter documentation

✅ **For Unfinished Models:**
- Current status and goals
- Known issues
- Collaboration preferences

### Best Practices

🌟 **Recommended:**
- Include example results or figures
- Provide parameter files separately
- Add validation data when available
- Include mesh convergence information
- Document computational requirements (RAM, CPU time)
- Add preprocessing/postprocessing scripts
- Include theoretical background or references

## File Size Considerations

- Keep individual files under 100 MB when possible
- For large result files, consider:
  - Hosting on external platforms (Zenodo, Figshare, etc.)
  - Providing download links in the README
  - Including only representative results

## Naming Conventions

### Directory Names
Use lowercase with underscores:
- ✅ `magma_chamber_deformation_2024`
- ❌ `MagmaChamberDeformation2024`

### File Names
Use descriptive, lowercase names:
- ✅ `conduit_flow_model.mph`
- ✅ `default_parameters.txt`
- ❌ `model1.mph`

## Code of Conduct

### Our Standards

- **Respectful**: Treat all community members with respect
- **Constructive**: Provide helpful, constructive feedback
- **Ethical**: Share only work you have rights to distribute
- **Accurate**: Document models honestly and thoroughly
- **Collaborative**: Be open to questions and improvements

### Unacceptable Behavior

- Harassment or discriminatory language
- Sharing proprietary or confidential information without permission
- Plagiarism or failing to properly cite sources
- Deliberately sharing incorrect or misleading information

## Questions?

- Open an issue with the label "question"
- Start a discussion in GitHub Discussions
- Contact the repository maintainers

## Attribution

All contributors will be acknowledged. Significant contributions may be highlighted in the repository's documentation.

Thank you for contributing to the advancement of volcanology research! 🌋
