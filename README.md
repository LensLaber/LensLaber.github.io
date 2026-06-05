# LensLaber

Offline-first annotation tool for computer vision datasets.

![Main Workflow](media/gifs/gif_lens.gif)

Fast, lightweight and practical annotation workflows for large computer vision datasets without relying on cloud services or high-end hardware.

---

## Why LensLaber

Many annotation workflows take place in environments where cloud access, dedicated GPUs or powerful workstations are not always available.

LensLaber was created to provide a complete offline annotation workflow that remains responsive, practical and efficient on a wide range of hardware configurations.

The goal is simple:

- Work offline
- Handle large datasets efficiently
- Reduce annotation friction
- Improve workflow speed
- Remain accessible on modest hardware

---

## Main Features

- Bounding Boxes
- Polygons
- Points
- Lines
- Fast Mode
- YOLO ONNX integration
- SAM Mobile integration
- Confidence-based false negative review
- Dataset filtering
- Dataset statistics
- Image quality control
- Project save/load system
- Dataset export
- Built-in augmentations
- Configurable shortcuts
- Adaptive cursor
- Autosave

---

## Main Workspace

![Main Workspace](media/screenshots/workspace.png)

The main workspace is designed to provide a fast and practical annotation experience with quick access to datasets, classes, tools and workflows.

---

## Large Dataset Workflow

![Large Dataset Workflow](media/screenshots/large_dataset_workflow.png)

▶ Video:
https://lenslaber.github.io/media/videos/large_dataset_workflow.mp4

LensLaber is designed to remain responsive when working with large image collections.

Features include:

- Thumbnail navigation
- Multi-selection
- Fast image switching
- Dataset organization tools

Tested with datasets containing more than 20,000 images.

---

## Fast Mode

![Fast Mode](media/gifs/fast_mode.gif)

Fast Mode allows rapid class assignment during annotation, reducing repetitive UI interactions and speeding up dataset creation.

---

## YOLO Integration

![YOLO Integration](media/gifs/yolo_detection.gif)

LensLaber supports user-provided YOLO ONNX models for automatic detection workflows.

This allows users to accelerate annotation using their own trained models.

---

## YOLO + SAM Workflow

![YOLO + SAM Workflow](media/gifs/yolo_sam_workflow.gif)

This workflow combines YOLO-based detection with SAM-assisted refinement to speed up annotation while keeping manual control.

Typical benefits include:

- Faster object initialization
- Reduced manual polygon adjustment
- Better efficiency on repetitive datasets
- Practical semi-automatic annotation workflow

---

## False Negative Review

![False Negative Workflow](media/gifs/false_negative_review.gif)

After automatic detection, LensLaber can optionally highlight low-confidence predictions for manual review.

The confidence threshold is configurable by the user.

Enabling this feature increases processing time.

---

## SAM Mobile Integration

![SAM Mobile Integration](media/gifs/sam_mobile_workflow.gif)

LensLaber currently includes SAM Mobile integration optimized for CPU-based workflows and modest hardware.

Future versions are planned to support larger SAM models through GPU/CUDA acceleration.

---

## Filtering System

![Filtering System](media/gifs/filtering_system.gif)

Filters can be combined to quickly locate images, annotations or review targets inside large datasets.

---

## Dataset Statistics

![Dataset Statistics](media/gifs/statistics.gif)

Built-in statistics provide useful information about dataset composition and annotation progress.

---

## Image Quality Control

![Image Quality Control](media/screenshots/image_quality_control.png)

Image quality tools help identify potential issues before dataset export or model training.

---

## Project System

![Project System](media/screenshots/project_system.png)

Projects can be saved and loaded using the `.lens` project format.

This preserves:

- Annotations
- Review state
- Filters
- Workflow progress

---

## Dataset Export

![Dataset Export](media/screenshots/export.png)

LensLaber supports dataset export workflows including:

- Train / Validation / Test split
- Optional image inclusion
- ZIP packaging

Built-in augmentations can also be used to prepare training datasets.

---

## Performance Philosophy

LensLaber is designed around practical workflows rather than hardware requirements.

Current versions focus on:

- CPU-friendly operation
- Lightweight AI workflows
- Offline usability

Future versions will introduce optional GPU/CUDA acceleration for users with compatible hardware.

---

## Tested Environment

Current testing includes:

- Windows 10
- Intel i5-class CPU
- 8 GB RAM

Compatibility with additional systems will continue to improve over time.

---

## Beta Status

LensLaber is currently in beta.

The beta version is functional but intentionally limited compared to future releases.

Some features may be restricted, disabled or still under development.

---

## Roadmap

Planned improvements include:

- GPU/CUDA acceleration
- Support for larger SAM models
- Additional export options
- Performance improvements
- Workflow enhancements

---

## Feedback

Feedback, bug reports and feature suggestions are welcome.

---

## Download

👉 [Download latest installer](https://github.com/LensLaber/LensLaber.github.io/releases/latest/download/LensLaber_Beta_Setup_v1.0.0.exe)

📄 [Download SHA-256 checksum](https://github.com/LensLaber/LensLaber.github.io/releases/latest/download/LensLaber_Beta_Setup_v1.0.0.exe.sha256)

---

## 🔒 Integrity Verification (SHA-256)

If you want to verify that the downloaded file is identical to the originally compiled version and has not been altered or corrupted, you can check its SHA-256 hash.

**Official Hash:**
`3a2e683374044c1f21067434e23481d30bf7ef6dfcbb938f734a49adc48ae157`

#### How to verify it on Windows:
1. Open **PowerShell** in the folder where you downloaded the installer.
2. Run the following command:
   ```powershell
   Get-FileHash .\LensLaber_Beta_Setup_v1.0.0.exe -Algorithm SHA256
   ```

---

## License

LensLaber is proprietary software.

This repository is intended for documentation, beta distribution and project updates.

© 2026 LensLaber. All rights reserved.















