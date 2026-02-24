# Kepler-Skills-Distiller (KSD)

A framework for scientific equation discovery that uses the "Think like a Scientist" (KeplerAgent) reasoning loop to generate procedural "Expert Skills" (SkillsBench), which are then distilled into smaller models using Pedagogically-Inspired Data Synthesis (Bloom's Mastery).

## Roadmap

- **Step 1: Project Scaffold** - Initialize the project structure with support for physical property inference and skill storage.
- **Step 2: Physical Property Inferencer** - Implement the module that takes raw data and infers underlying physical constraints (units, symmetries, conservation laws).
- **Step 3: Skill Schema Definition** - Define a structured JSON schema for "Scientific Skills" based on the SkillsBench taxonomy.
- **Step 4: Kepler Reasoning Agent** - Implement the physics-guided reasoning agent that uses inferred properties to guide scientific discovery.
- **Step 5: Expert Skill Generator** - Implement logic for the Kepler Agent to convert successful discovery trajectories into reusable "Expert Skills".
- **Step 6: Pedagogical Data Synthesizer** - Implement the synthesis engine that creates training data categorized by Bloom's Taxonomy tiers for the discovery task.
- **Step 7: Apprentice Model Scaffold** - Set up the training environment for a smaller student model (e.g., Qwen-1.5B or Llama-3-1B).
- **Step 8: Mastery Distillation Loop** - Implement the training loop that distilled the expert's scientific skills into the apprentice using the pedagogical curriculum.
- **Step 9: Equation Discovery Benchmark** - Evaluate the expert vs. distilled apprentice on symbolic regression benchmarks (e.g., Feynman benchmark).
- **Step 10: CLI & Visualization** - Create a CLI tool to run the discovery, skill generation, and distillation pipeline with progress visualization.
- **Step 11: Final Documentation & README** - Comprehensive write-up of the scientific reasoning distillation architecture.

## Installation

```bash
pip install -r requirements.txt
```

## Structure

- `src/`: Core logic (discovery, skills, distillation)
- `tests/`: Unit tests
- `data/`: Scientific datasets and synthetic samples
