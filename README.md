# Hi, I'm Ambra Dondi 👋

**Image Analysis Scientist & Technologist** with 10+ years building automated pipelines that transform raw imaging data into quantitative insights. My expertise spans deep learning segmentation, 3D morphological analysis, and multi-channel signal quantification—techniques that translate across microscopy, satellite imagery, materials science, and industrial inspection. I architect reproducible Python workflows that scale from single images to high-throughput batch processing.

---

## 🔧 What I Build

| Technique | Tools & Methods |
|-----------|-----------------|
| **Instance Segmentation** | Cellpose, deep learning models, watershed, connected components |
| **3D Morphological Analysis** | Skeletonization (ITK), distance transforms, region properties |
| **Signal Quantification** | Colocalization metrics, intensity profiling, Pearson correlation |
| **Image Registration** | Phase cross-correlation, multi-modal alignment, temporal registration |
| **Network Analysis** | Graph-based skeleton parsing (skan), filament detection, path tracing |
| **GPU-Accelerated Processing** | pyclesperanto, CUDA-enabled batch workflows |

---

## 📂 Pipeline Demos

| Repository | Description | Core Techniques |
|------------|-------------|-----------------|
| [3d-cell-segmentation-quantifier-demo](https://github.com/ambeeblush/3d-cell-segmentation-quantifier-demo) | Segments 3D objects and quantifies multi-channel colocalization | `deep-learning` `3D-morphology` `colocalization` |
| [3d-compartment-quantifier-demo](https://github.com/ambeeblush/3d-compartment-quantifier-demo) | Measures signal distribution across nested regions in 3D volumes | `instance-segmentation` `region-analysis` `correlation` |
| [nuclear-foci-counter-demo](https://github.com/ambeeblush/nuclear-foci-counter-demo) | Detects and counts small bright spots within segmented regions | `spot-detection` `intensity-quantification` `morphology` |
| [nuclear-intensity-quantifier-demo](https://github.com/ambeeblush/nuclear-intensity-quantifier-demo) | Quantifies signal intensity within automatically segmented 3D objects | `3D-processing` `deep-learning` `batch-analysis` |
| [cell-area-segmentation-demo](https://github.com/ambeeblush/cell-area-segmentation-demo) | Segments objects and measures area distributions with morphological filtering | `thresholding` `region-properties` `quality-control` |
| [structure-activity-quantifier-demo](https://github.com/ambeeblush/structure-activity-quantifier-demo) | Quantifies active vs. total structure ratios with skeleton analysis | `skeletonization` `graph-analysis` `GPU-accelerated` |
| [3d-cell-skeleton-analyzer-demo](https://github.com/ambeeblush/3d-cell-skeleton-analyzer-demo) | Extracts skeletal networks from 3D volumes and quantifies spatial relationships | `tubeness-filter` `3D-thinning` `network-analysis` |
| [3d-filament-skeleton-analysis-demo](https://github.com/ambeeblush/3d-filament-skeleton-analysis-demo) | Segments thin filamentous structures and computes morphological statistics | `hessian-filter` `alpha-shapes` `graph-analysis` |
| [cell-compartment-droplet-quantifier-demo](https://github.com/ambeeblush/cell-compartment-droplet-quantifier-demo) | Segments compartments and quantifies internal inclusions with shape classification | `deep-learning` `morphology` `multi-channel` |
| [multichannel-3d-registration-demo](https://github.com/ambeeblush/multichannel-3d-registration-demo) | Aligns multi-acquisition images using phase correlation for fusion analysis | `registration` `cross-correlation` `temporal-alignment` |
| [spot-colocalization-demo](https://github.com/ambeeblush/spot-colocalization-demo) | Quantifies spatial colocalization between different spot signals | `colocalization` `pearson-correlation` `segmentation` |
| [3d-cell-compartment-analyzer-demo](https://github.com/ambeeblush/3d-cell-compartment-analyzer-demo) | Comprehensive 3D compartment segmentation with skeleton and intensity analysis | `ITK` `skan` `distance-transform` |
| [filament-dynamics-tracker-demo](https://github.com/ambeeblush/filament-dynamics-tracker-demo) | Tracks elongated structures over time and detects transition events | `time-series` `FilFinder` `event-detection` |
| [3d-cell-segmentation-demo](https://github.com/ambeeblush/3d-cell-segmentation-demo) | Robust 3D segmentation with morphological filtering and object separation | `cellpose` `connected-components` `anisotropic-3D` |

---

## 📚 Publications

| Year | Journal | Contribution |
|------|---------|--------------|
| — | — | *Coming soon* |

---

## 🛠 Tech Stack

```python
# Core Scientific Computing
numpy, pandas, scipy, scikit-image

# Deep Learning & Segmentation
cellpose, torch

# 3D Image Processing
aicsimageio, itk, napari, napari-simpleitk-image-processing

# GPU Acceleration
pyclesperanto-prototype

# Network & Skeleton Analysis
skan, fil_finder, alphashape

# Visualization & I/O
matplotlib, napari, tifffile, bioformats
```

---

## 📫 Let's Connect

I'm always interested in collaborating on challenging image analysis problems—whether you're working with satellite data, industrial inspection, medical imaging, or materials characterization. The algorithms are transferable; the insights are universal.

- 🏛 **Current Role:** European Institute of Oncology (IEO), Milan
- 🎓 **Background:** PhD in Systems Medicine
- 💬 **Open to:** Consulting, collaborations, and interesting problems

*If you're building image analysis pipelines or looking for expertise in automated quantification workflows, let's talk.*