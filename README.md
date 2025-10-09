# IngreVision Model v1.0.1

## Model Refinement Update

### Version 1.0.1 - Enhanced Training
- **Training Epochs**: 125
- **Image Tweaking Applied**:
  - Random resized crops (224x224)
  - Random horizontal flips
  - Color jittering (brightness, contrast, saturation, hue)
  - Random rotations (±10 degrees)
  - ImageNet normalization

### Training Details
- **Optimizer**: Adam with learning rate 0.001
- **Scheduler**: StepLR (step every 10 epochs)
- **Checkpoints**: Saved every 50 batches
- **Best Model**: Maintained based on validation accuracy

### Files Included
- Main model weights (.pth files)
- Training checkpoints
- Configuration files
- Testing scripts
