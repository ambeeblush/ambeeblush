# Hi, I'm Ambra

I'm a bioimage analyst at the Imaging Unit of IEO (European Institute of Oncology) in Milan, a biologist by training with a PhD in Systems Medicine. For almost ten years I've been turning microscopy images into numbers that scientists can build conclusions on: segmenting cells and nuclei, tracing mitochondrial and microtubule networks in 3D, measuring how signals are distributed inside the cell.

I'm a bit obsessed with 3D analysis, as cells are three-dimensional. I'm convinced that analyzing them as flat images can hide real biological differences or, worse, produce numbers that look fine but can't be trusted. So in my analysis pipelines every step is designed on the full volume. I write them in Python and run them as batch jobs on our SLURM cluster, so the same analysis scales from a single test image to an entire experiment, analyzing hundreds of cells per sample in exactly the same way.

I'm now looking for roles where these skills travel beyond biology. Images are images, whether they come from a microscope, a satellite, a pathology slide scanner or a camera on a production line: noisy signal, objects to segment, and measurements that people need to be able to trust.

<!-- PLACEHOLDER — one line on what you're looking for, if you want to be explicit,
     e.g. "Open to image analysis / computer vision roles in Milan or remote." -->



## Featured project

### [CHIMERA](https://github.com/ambeeblush/CHIMERA)

Rotating 3D movies that put raw microscopy data and analysis results side by side, generated from a YAML file and a CSV. I built it to check my own 3D skeletons and segmentations, and to show collaborators, in a slide they can press play on, that the analysis did what it was supposed to do.

<!-- PLACEHOLDER — reuse the hero GIF from the CHIMERA repo. The full raw URL makes it render here too.
     Check the branch name (main / master) once the repo is public. -->
<p align="center">
  <img src="https://raw.githubusercontent.com/ambeeblush/CHIMERA/main/docs/media/panel_mito_skeleton.gif" alt="CHIMERA: mitochondria and 3D skeleton rotating side by side" width="600">
</p>

`Python` `3D rendering` `BioIO` `pyclesperanto (GPU)` `YAML config` `SLURM`

### ✨ Coming next ✨: *POLARIS*

3D quantification of mitochondrial redistribution around functionalized beads, the analysis behind [Eli et al., *Nature Communications* 2025](https://doi.org/10.1038/s41467-025-65775-z). I'm turning the original script into a clean, documented package.



## Why most of my code isn't public (yet)

In academic research, analysis code usually goes out together with the paper it was written for, and several of the projects I've worked on are still unpublished. The full pipelines will be released as their papers come out. In the meantime, have a look to the publications where my analyses ended up.



## Publications including my analyses

- Chiesa A., Poli V., [...], **Dondi A.**, [...], Campaner S. (2026). *Functional genomic screens uncover FERMT2 as a critical regulator of YAP/TAZ-driven tumorigenicity.* Cell Death & Differentiation 33(9):1907–1922. [doi:10.1038/s41418-026-01694-w](https://doi.org/10.1038/s41418-026-01694-w)

- Massari L.F., Finardi A., Visintin C., Calabrese E., **Dondi A.**, Visintin R. (2026). *Safeguarding genome integrity: Polo-like kinase Cdc5 and phosphatase Cdc14 orchestrate Topoisomerase II-mediated catenane resolution in mitosis.* Nucleic Acids Research 54(2):gkaf1509. [doi:10.1093/nar/gkaf1509](https://doi.org/10.1093/nar/gkaf1509)
  <br>Quantification of Top2 abundance and distribution in expanded nuclear regions (Fig. 6F–G).

- Eli S., Rauso G., [...], **Dondi A.**, [...], Mapelli M. (2025). *Localized Wnt-signaling promotes asymmetric NuMA-dependent oriented divisions and unequal apportioning of mitochondria.* Nature Communications 16:10690. [doi:10.1038/s41467-025-65775-z](https://doi.org/10.1038/s41467-025-65775-z)
  <br>3D analysis of mitochondrial enrichment as a function of the position of Wnt-coated beads (POLARIS, ✨ *coming soon* ✨).

- Mulè P., Fernandez-Perez D., [...], **Dondi A.**, [...], Pasini D. (2024). *WNT oncogenic transcription requires MYC suppression of lysosomal activity and EPCAM stabilization in gastric tumors.* Gastroenterology 167(5):903–918. [doi:10.1053/j.gastro.2024.06.029](https://doi.org/10.1053/j.gastro.2024.06.029)

<!--Full list on [ORCID](https://orcid.org/0000-0001-7594-2105).-->




<!--## Technique demos

Small, self-contained examples of the building blocks I use in larger pipelines.

**3D segmentation and quantification**
- [3d-cell-segmentation-demo](https://github.com/ambeeblush/3d-cell-segmentation-demo): Cellpose segmentation of anisotropic 3D stacks, with morphological filtering and separation of touching objects
- [3d-cell-segmentation-quantifier-demo](https://github.com/ambeeblush/3d-cell-segmentation-quantifier-demo): 3D segmentation followed by multi-channel colocalization
- [nuclear-intensity-quantifier-demo](https://github.com/ambeeblush/nuclear-intensity-quantifier-demo): signal intensity inside automatically segmented 3D objects, in batch
- [3d-compartment-quantifier-demo](https://github.com/ambeeblush/3d-compartment-quantifier-demo): signal distribution across nested regions in 3D volumes
- [3d-cell-compartment-analyzer-demo](https://github.com/ambeeblush/3d-cell-compartment-analyzer-demo): compartment segmentation combined with skeleton and intensity analysis
- [cell-compartment-droplet-quantifier-demo](https://github.com/ambeeblush/cell-compartment-droplet-quantifier-demo): inclusions inside segmented compartments, with shape classification
- [cell-area-segmentation-demo](https://github.com/ambeeblush/cell-area-segmentation-demo): segmentation and area distributions, with morphological filtering and quality control

**Skeletons and networks**
- [3d-cell-skeleton-analyzer-demo](https://github.com/ambeeblush/3d-cell-skeleton-analyzer-demo): tubeness filter and 3D thinning to extract networks and measure spatial relationships
- [3d-filament-skeleton-analysis-demo](https://github.com/ambeeblush/3d-filament-skeleton-analysis-demo): thin filaments with Hessian filtering, alpha shapes and graph statistics
- [structure-activity-quantifier-demo](https://github.com/ambeeblush/structure-activity-quantifier-demo): active vs. total structure ratios from skeletons, GPU-accelerated
- [filament-dynamics-tracker-demo](https://github.com/ambeeblush/filament-dynamics-tracker-demo): tracking elongated structures over time and detecting transition events

**Spots and colocalization**
- [nuclear-foci-counter-demo](https://github.com/ambeeblush/nuclear-foci-counter-demo): counting small bright spots inside segmented regions
- [spot-colocalization-demo](https://github.com/ambeeblush/spot-colocalization-demo): spatial colocalization between two spot signals

**Registration**
- [multichannel-3d-registration-demo](https://github.com/ambeeblush/multichannel-3d-registration-demo): aligning multiple acquisitions with phase cross-correlation-->




## Tools I use most

**Segmentation and deep learning:** Cellpose, PyTorch, scikit-image<br>
**3D processing:** ITK, pyclesperanto (GPU), SciPy<br>
**Skeletons and network analysis:** skan, FilFinder<br>
**Data analysis and statistics:** pandas, SciPy (scipy.stats), statsmodels<br>
**Plotting:** matplotlib, seaborn<br>
**I/O and visualization:** BioIO, napari<br>
**Engineering:** NumPy, YAML / Pydantic configs, conda / mamba, SLURM, Git



## Teaching

I teach microscopy and image analysis to PhD students of [SEMM](https://semm.it/) (European School of Molecular Medicine) and to Master's students of [Master's Program in Biomedical Omics](https://www.unimi.it/en/education/master-programme/biomedical-omics-bo). 

I'm currently responsible for these modules:

- **Optimizing live-cell imaging settings**, in the [Light Microscopy](https://semm.it/course-light-microscopy/) course
- **Introduction to the ImageJ macro language**, in the [Image Analysis I](https://semm.it/image-analysis-i/) course
- **Cell segmentation with Cellpose in Python**, in the [Image Analysis II](https://semm.it/image-analysis-ii/) course
- **Microscopy and image analysis for digital pathology** practical laboratory activity, in the [Master's programme in Biomedical Omics](https://www.unimi.it/en/education/master-programme/biomedical-omics-bo) at the University of Milan


## Contact

[LinkedIn](https://www.linkedin.com/in/ambra-dondi) · [ORCID](https://orcid.org/0000-0001-7594-2105) · [Email](mailto:ambra.dondi@hotmail.com)
