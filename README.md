# AI-Assisted Investment Research Workflows

An exploration of how reusable research instructions can make AI-assisted portfolio analysis more structured and easier to review.

**Author:** Xavier Chen  
**Status:** Markdown research workflow and worked examples. This is not a deployed multi-agent platform, autonomous investment system, or installable software package.

## Project description

The project starts with a portfolio-review prompt and introduces a reusable `portfolio-council` instruction file. It includes examples of a review without the skill and with the skill, making the change in research structure visible to readers.

The goal is to move beyond one-off prompting toward explicit questions, consistent analytical steps, and outputs that a human can challenge and verify.

## Contents

| Resource | Purpose |
| --- | --- |
| [Portfolio-council skill](1.0%20Skill%3A%20portfolio-council.md) | Reusable instructions for an investment/portfolio review |
| [Example without the skill](1.1%20Example%20without%20skill%3A%20Does%2060_40%20fit%20your%20profile_.md) | Baseline example |
| [Example with the skill](1.2%20Example%20with%20skill%3A%2060-40%20portfolio%20review.md) | A worked example using the structured instructions |

The examples illustrate a workflow. They are not a controlled benchmark or proof that one approach produces more accurate investment conclusions.

## Tech stack

Markdown instruction files and saved AI-assisted research examples. No model API integration, dependency manifest, or executable application is currently included.

## Installation

No installation is needed to read the files on GitHub. A local copy is optional:

```bash
git clone https://github.com/Xiaowen-CHEN-Learner/From-prompt-to-AI-system.git
cd From-prompt-to-AI-system
```

Some existing filenames contain colons, which can cause checkout problems on Windows. Browser-based reading avoids that issue; cross-platform filename cleanup is a planned improvement.

## Usage

1. Read the skill file and both examples to understand the existing workflow.
2. For a new experiment, provide the same research question, assumptions, and permitted source material to a compatible AI interface.
3. Compare a baseline response with one that uses the skill instructions.
4. Review the outputs for source traceability, numerical consistency, missing assumptions, unsupported claims, and decision relevance.
5. Record the model, settings where available, experiment date, and human corrections before sharing the result.

Do not provide account credentials, confidential client information, or proprietary employer materials to an external AI service.

## Evaluation and limitations

A polished answer is not evidence of correctness. Independently check cited sources, calculations, data dates, and the interpretation of risk. Different models, settings, or input materials may produce different results.

Future evaluation should use a defined rubric, comparable inputs, repeated trials where appropriate, and examples of failure—not just a selected successful output.

## Roadmap

- Organize future material under `skills/`, `examples/`, and `evaluation/` using cross-platform filenames.
- Add a reproducible evaluation rubric and a log of corrections.
- Make input requirements, source boundaries, and the human review stage explicit.
- Document any executable implementation separately when one exists.

## Contributing and contact

Feedback on research design, verification, and documentation is welcome through GitHub issues.

[Xavier Chen on LinkedIn](https://www.linkedin.com/in/xiaowen-chen/) · [GitHub portfolio](https://github.com/Xiaowen-CHEN-Learner)

## License

No project-wide license is currently included. Third-party material retains its applicable rights.

---

Educational research only. AI-generated outputs require human verification. Not investment advice.
