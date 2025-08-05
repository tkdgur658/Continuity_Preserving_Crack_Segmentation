# Crack Segmentation Project

Continuity-Preserving Crack Segmentation via a Multi-Scale Bypass Network.

## Project Structure

```
├── config.py              # Configuration settings
├── utils.py               # Utility functions
├── data_processing.py     # Data loading and preprocessing
├── losses.py              # Loss functions and metrics
├── training.py            # Training and validation functions
├── experiment.py          # Main experiment script
├── models/                # Model definitions
└── output/                # Experiment results
```

## Usage

### Basic Execution

```bash
python experiment.py
```

### Configuration

Edit `config.py` to customize:

- **Models**: Change `model_names` list
- **Dataset**: Modify `Dataset_root` path
- **Training**: Adjust `epochs`, `batch_size`, `lr`
- **Hardware**: Set `devices` for GPU selection

### Output

Results are saved in `output/` directory with:
- Training/validation losses
- Test metrics (IoU, Dice, Precision, Recall)
- Model checkpoints
- Performance summaries

## Requirements
- Python 3.8.12
See `requirements.txt` for further dependencies. 
