# Video LLM Evaluation Harness

A comprehensive evaluation framework for video-based language models with proper repository structure and key components from existing research repositories.

## Repository Structure

This repository is organized into multiple branches for different components:

### Branches:
1. **main** - Core configuration and documentation
2. **dataset-integration** - Dataset loading and preprocessing modules
3. **evaluation-framework** - Evaluation metrics and benchmarking tools
4. **training-module** - Model training and fine-tuning utilities
5. **documentation** - Detailed documentation and usage examples

## Key Components

### External Modules Integrated:
1. **LongVideoBench Dataset Module** (`longvideobench/longvideobench_dataset.py`)
   - Source: `longvideobench/LongVideoBench`
   - Branch: `dataset-integration`

2. **LMM Judge Module** (`src/lmm_judge.py`)
   - Source: `VideoAutoArena/VideoAutoArena`
   - Branch: `evaluation-framework`

3. **VideoLLaMA2 Trainer Module** (`videollama2/videollama2_trainer.py`)
   - Source: `DAMO-NLP-SG/VideoLLaMA2`
   - Branch: `training-module`

### Custom Modules:
1. **Data Preprocessor** (`data_preprocessor.py`)
   - Branch: `dataset-integration`
   - Purpose: Data preprocessing utilities for video datasets

2. **Metrics Calculator** (`metrics_calculator.py`)
   - Branch: `evaluation-framework`
   - Purpose: Metrics calculation utilities for video LLM evaluation

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/nobita-0002/video-llm-evaluation-harness.git
   ```

2. Checkout the desired branch:
   ```bash
   git checkout <branch-name>
   ```

3. Install dependencies (to be added)

## Project Goals

- Provide a standardized evaluation framework for video LLMs
- Integrate best practices from existing research repositories
- Enable reproducible benchmarking across different video LLM architectures
- Facilitate comparison of model performance on video understanding tasks

## License

This project is open source and available under the MIT License.