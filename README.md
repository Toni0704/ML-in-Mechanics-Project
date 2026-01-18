# ML in Mechanics Project

This project applies machine learning techniques to solve mechanics-related problems, incorporating neural networks to model complex physical phenomena.

## Documentation

- **Project Report**: See [report.pdf](APL405_Project%20(1).pdf) for the detailed technical report
- **Presentation**: See [405ppt_final.pptx](405ppt_final.pptx) for the project overview and key findings
- **Additional References**: [deeponet_crack.pdf](deeponet_crack.pdf) provides background on DeepONet architectures

## Project Structure

- `code.ipynb` - Main implementation notebook with model training and evaluation
- `input/` - Input data for the models
- `output/` - Trained models and prediction results
  - `checkpoints/` - Model checkpoints from each training epoch
  - `predictions/` - Model prediction outputs
  - Model files: `image_sequence_model_final.pth`, `image_sequence_model.pth`

## Getting Started

1. Review the [project presentation](405ppt_final.pptx) for an overview
2. Read the [full report](APL405_Project%20(1).pdf) for detailed methodology and results
3. Run `code.ipynb` to train and evaluate models

## Key Files

- **Model**: Trained sequence-to-sequence models saved in `output/`
- **Checkpoints**: Epoch-wise model snapshots in `output/checkpoints/`
