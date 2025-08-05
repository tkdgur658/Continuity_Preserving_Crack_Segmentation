# Micro Video Recommendation System

This repository contains a micro video recommendation system implementation with configurable training and inference modes.

## Project Structure

```
├── main.py              # Main execution script
├── utils.py             # Utility functions
├── models/              # Model implementations
├── output/              # Output directory for results
├── graphs/              # Graph data directory
└── README.md           # This file
```

## Quick Start

### Prerequisites

- Python 3.11
- PyTorch
- NumPy
- Pandas
- tqdm

### Running Experiments

#### Training Mode
```bash
python main.py
```

#### Inference Mode
Run:
```bash
python main.py
```

## Output Structure

Results are saved in the `output/` directory with the following structure:
```
output/
└── output_YYYYMMDD_HHMMSS/
    ├── model_dataset_split_ratio_iter/
    │   └── timestamp_model_dataset_split_ratio_iter.pt
    └── Micro_Video_Recommendation_YYYYMMDD_HHMMSS.csv
```
