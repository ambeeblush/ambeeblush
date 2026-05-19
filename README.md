# Hi, I'm Ambra Dondi 👋

**Image Analysis Scientist & Technologist** building automated pipelines that transform complex multi-dimensional imaging data into quantitative insights. With a PhD in Systems Medicine and 10+ years developing computational solutions, I specialize in 3D segmentation, object tracking, and spatial analysis algorithms that scale from research prototypes to production workflows. My expertise in deep learning segmentation, skeleton analysis, and colocalization metrics applies across any domain where images become data.

---

## 🔧 What I Build

| Challenge | Techniques I Apply | Tools I Use |
|-----------|-------------------|-------------|
| **Instance Segmentation** | Deep learning (Cellpose), thresholding, morphological filtering | `cellpose`, `scikit-image`, `pyclesperanto` |
| **3D Structure Analysis** | Skeletonization, graph-based path analysis, tubeness filtering | `itk`, `skan`, `scipy` |
| **Multi-Channel Registration** | Phase cross-correlation, 3D translation, downscaling | `scikit-image`, `aicsimageio` |
| **Spatial Quantification** | Region properties, colocalization (Pearson), intensity profiling | `numpy`, `pandas`, `scipy` |
| **Object Tracking** | Time-series event detection, phenotype classification | `fil_finder`, `pandas` |
| **Interactive Visualization** | 3D rendering, label overlays, quality control | `napari`, `matplotlib` |

---

## 📂 Pipeline Demos

Explore these repositories for documented, working examples of my image analysis approaches:

### Segmentation & Quantification

| Repository | Description | Core Techniques |
|------------|-------------|-----------------|
| [**3d-cell-segmentation-quantifier-demo**](https://github.com/ambeeblush/3d-cell-segmentation-quantifier-demo) | 3D instance segmentation with multi-channel intensity and colocalization metrics | `deep-learning` `3D` `colocalization` |
| [**3d-compartment-quantifier-demo**](https://github.com/ambeeblush/3d-compartment-quantifier-demo) | Quantify signal distribution across nested regions in volumetric data | `instance-segmentation` `region-analysis` `3D` |
| [**nuclear-foci-counter-demo**](https://github.com/ambeeblush/nuclear-foci-counter-demo) | Detect and count small bright spots within segmented parent objects | `spot-detection` `counting` `morphology` |
| [**nuclear-intensity-quantifier-demo**](https://github.com/ambeeblush/nuclear-intensity-quantifier-demo) | Per-object intensity measurement in 3D multi-series images | `3D` `quantification` `batch-processing` |
| [**cell-area-segmentation-demo**](https://github.com/ambeeblush/cell-area-segmentation-demo) | Automated area measurement with preprocessing and border handling | `morphometry` `thresholding` `deep-learning` |
| [**3d-cell-segmentation-demo**](https://github.com/ambeeblush/3d-cell-segmentation-demo) | 3D object segmentation with morphological filtering and touching object separation | `3D` `filtering` `connected-components` |

### Skeleton & Network Analysis

| Repository | Description | Core Techniques |
|------------|-------------|-----------------|
| [**3d-cell-skeleton-analyzer-demo**](https://github.com/ambeeblush/3d-cell-skeleton-analyzer-demo) | Extract and analyze skeletal networks with spatial relationship quantification | `skeletonization` `graph-analysis` `3D` |
| [**3d-filament-skeleton-analysis-demo**](https://github.com/ambeeblush/3d-filament-skeleton-analysis-demo) | Segment thin structures using Hessian filtering with alpha shape hulls | `hessian-filter` `skeletonization` `hull-computation` |
| [**structure-activity-quantifier-demo**](https://github.com/ambeeblush/structure-activity-quantifier-demo) | Ratio analysis of active vs total structures with skeleton morphometrics | `skeletonization` `GPU-accelerated` `ratio-analysis` |
| [**3d-cell-compartment-analyzer-demo**](https://github.com/ambeeblush/3d-cell-compartment-analyzer-demo) | Multi-compartment segmentation with internal skeleton path analysis | `3D` `skeletonization` `distance-transform` |

### Colocalization & Multi-Channel

| Repository | Description | Core Techniques |
|------------|-------------|-----------------|
| [**spot-colocalization-demo**](https://github.com/ambeeblush/spot-colocalization-demo) | Spatial correlation analysis between two spot populations within regions | `colocalization` `Pearson-correlation` `spot-analysis` |
| [**multichannel-3d-registration-demo**](https://github.com/ambeeblush/multichannel-3d-registration-demo) | Align multi-acquisition datasets using phase cross-correlation | `registration` `phase-correlation` `multi-modal` |
| [**cell-compartment-droplet-quantifier-demo**](https://github.com/ambeeblush/cell-compartment-droplet-quantifier-demo) | Quantify internal inclusions with morphological shape classification | `GPU-accelerated` `inclusion-analysis` `classification` |

### Temporal Analysis

| Repository | Description | Core Techniques |
|------------|-------------|-----------------|
| [**filament-dynamics-tracker-demo**](https://github.com/ambeeblush/filament-dynamics-tracker-demo) | Track elongated structures over time with event detection and line profiling | `tracking` `time-series` `event-detection` |

---

## 📚 Publications

| Year | Journal | Contribution |
|------|---------|--------------|
| — | — | — |

---

## 🛠 Tech Stack

```python
# Core Scientific Computing
numpy, scipy, pandas

# Image Processing & Segmentation
scikit-image, cellpose, itk, napari-simpleitk-image-processing

# GPU Acceleration
pyclesperanto-prototype, torch

# Skeleton & Graph Analysis
skan, fil_finder

# File I/O & Formats
aicsimageio, tifffile, bioformats, mrc

# Visualization
napari, matplotlib

# Specialized
alphashape, astropy
```

---

## 📫 Let's Connect

I'm always interested in collaborating on challenging image analysis problems—whether you're working with microscopy, satellite imagery, industrial inspection, materials characterization, or any domain where automated quantification matters.

- 🔬 **Looking for**: Collaborations on complex segmentation challenges, 3D analysis workflows, or algorithm development
- 💬 **Happy to discuss**: Pipeline architecture, technique selection, or adapting methods to new domains

**Reach out** via GitHub issues on any repo, or connect with me to discuss how these techniques might apply to your data.