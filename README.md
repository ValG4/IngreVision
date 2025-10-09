# IngreVision Model v1.0.1

## Model Refinement Update

### Version 1.0.1 - Enhanced Training
- **Training Epochs**: 125
- **Classes**: 11 ingredients
- **Last Updated**: 2025-10-09 01:32:13

### Image Augmentation Applied:
- Random resized crops (224x224)
- Random horizontal flips
- Color jittering (brightness, contrast, saturation, hue)
- Random rotations (±10 degrees)
- ImageNet normalization

### Training Details
- **Optimizer**: Adam with learning rate 0.001
- **Scheduler**: StepLR (step every 10 epochs)
- **Batch Size**: 16
- **Checkpoints**: Saved every 50 batches + best model
- **Validation**: After every epoch

### Files Included
- `IngreVision_V1.pth` - Main model weights
- `IngreVision_V1_best.pth` - Best validation accuracy
- `IngreVision_V1_final.pth` - Final training epoch
- `class_names.json` - Class labels
- `metadata.json` - Model configuration
- `training_logs/` - Training history and metrics

### Performance
- Model trained for 125 epochs with comprehensive augmentation
- Regular validation and best model selection
- Enhanced generalization through image transformations
