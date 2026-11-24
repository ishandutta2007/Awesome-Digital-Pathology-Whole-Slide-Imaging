# Awesome-Digital-Pathology-Whole-Slide-Imaging

## Top Digital Pathology & Whole-Slide Imaging Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Whole-Slide Imaging (WSI) Viewers, Computational Pathology AI, Gigapixel Tissue Analysis, Slide Servers & Histopathology Toolkits*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Digital Pathology & Whole-Slide Imaging (WSI)**. These tools decode, tile, stream, annotate, segment, and analyze gigapixel histopathology slides (`.svs`, `.ndpi`, `.mrxs`, `.scn`, `.tiff`, DICOM WSI) across clinical pathology workspaces, web-based pyramid viewers, and computational pathology ML pipelines.

**Examples** include Roche NAVIFY Digital Pathology, Leica Biosystems Aperio, Philips IntelliSite, Sectra Digital Pathology, Hamamatsu NanoZoomer Cloud, PathAI, Paige.ai, Proscia Concentriq, Indica Labs HALO, and Visiopharm.

**Open-source emphasis**: This section features active projects for WSI decoding & pyramid I/O (`libvips`, `OpenSlide`, `TiffSlide`, `WSIDicom`), desktop & web gigapixel slide viewers (`OpenSeadragon`, `QuPath`, `Digital Slide Archive / HistomicsUI`, `SLIM`, `Cytomine`), and computational pathology deep-learning toolkits (`MONAI`, `CLAM`, `StarDist`, `UNI`, `HoVer-Net`, `Prov-GigaPath`, `TIAToolbox`, `histolab`, `HistoQC`, `HistoCartography`, `deep-histopath`, `marugoto`).

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global digital pathology market is valued at approximately **$1.3 billion to $1.6 billion** (projected to reach $2.86B–$5.75B by the early 2030s at an estimated CAGR of 12.5%–18.5%). The sector exhibits a **hybrid, moderately concentrated structure**: the foundational hardware and clinical slide scanner segment is highly concentrated among legacy conglomerates (Danaher/Leica, Roche, Philips, Hamamatsu commanding nearly 50% of revenue), whereas the cloud IMS, AI biomarker quantification, and algorithmic software segments remain **fragmented** with active M&A consolidation driven by biopharma partnerships and diagnostic AI acquisitions.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing | Free Tier / Trial Limit | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Roche NAVIFY Digital Pathology](https://roche.com)** | ~$282B Market Cap / ~$75B Revenue | Commercial clinical deployment starting from ~$45,000/year (LIS & scanner interface modules) | 30-day guided institutional trial (requires clinical site onboarding & demo dataset) | Enterprise cloud-integrated workflow software uniting high-throughput slide scanning, NAVIFY algorithm suite, and hospital LIS for clinical diagnostics. |
| **[Leica Biosystems Aperio (eSlide Manager & Aperio HALO AP)](https://leicabiosystems.com)** | Parent Danaher ~$162B Market Cap (Leica ~$1B Revenue) | Enterprise server tier starting from ~$30,000/year (multi-seat clinical license) | 30-day institutional trial for Aperio eSlide Manager (up to 25 test slides with full viewer features) | Enterprise web-based slide management, viewing, and telepathology ecosystem engineered for multi-site health systems and `.svs` slide workflows. |
| **[Philips IntelliSite Pathology Solution](https://philips.com)** | ~$27B Market Cap / ~$20B Revenue | Enterprise hospital deployment starting from ~$50,000/year (Image Management System tier) | 60-day structured hospital pilot evaluation program (limited to 5 clinician seats & preloaded study sets) | End-to-end clinical digital pathology suite combining ultra-fast whole-slide scanners, scalable IMS, and FDA-cleared diagnostic case viewers. |
| **[Sectra Digital Pathology](https://sectra.com)** | ~$5.5B Market Cap / ~$360M Revenue | Subscription starting from ~$35,000/year (PACS integration & diagnostic pathology workstation) | 30-day clinical sandbox trial (includes demo PACS connection and 50 anonymized whole-slide studies) | Enterprise diagnostic pathology PACS and VNA platform uniting radiology and pathology imaging in a single vendor-neutral clinical viewer. |
| **[Hamamatsu NanoZoomer Cloud / NDP.serve](https://hamamatsu.com)** | ~$3.5B Market Cap / ~$1.4B Revenue | Software server license starting from ~$15,000/year (NDP.serve base streaming server) | 30-day trial license for NDP.view / NDP.serve (limited to local server hosting & 10 concurrent slide connections) | Whole-slide imaging ecosystem and cloud/network slide-serving software engineered for high-throughput `.ndpi` scanning, telepathology, and multi-user viewing. |
| **[PathAI (AISight)](https://pathai.com)** | ~$1.05B Valuation (Acquired by Roche) / ~$50M Revenue | Enterprise biopharma / clinical lab tier starting from ~$25,000/year (AISight IMS subscription) | 14-day interactive web sandbox demo (includes 10 sample breast/prostate whole-slide sessions) | Cloud-based digital pathology IMS and AI-powered biomarker quantification platform supporting clinical trials, biopharma research, and diagnostic workflows. |
| **[Paige.ai (Paige Platform & Virchow Ecosystem)](https://paige.ai)** | ~$239M Total VC Funding / ~$25M Revenue | Clinical AI diagnostic module tier starting from ~$20,000/year (per-lab diagnostic subscription) | 14-day cloud evaluation trial for Paige Platform (includes 20 AI-assisted prostate/breast diagnostic slide analyses) | Clinical-grade computational pathology SaaS and foundation-model ecosystem offering FDA-cleared diagnostic AI modules and cloud whole-slide viewing. |
| **[Proscia Concentriq](https://proscia.com)** | ~$240M Acquisition (Agilent) / ~$18M TTM Revenue | Enterprise laboratory tier starting from ~$18,000/year (Concentriq AP / LS base cloud subscription) | 30-day guided evaluation sandbox (limited to 3 concurrent user accounts and 100 hosted test slides) | Cloud-native enterprise digital pathology platform and AI orchestrator uniting whole-slide management, clinical collaboration, and diagnostic AI apps. |
| **[Indica Labs HALO & HALO Link](https://indicalab.com)** | ~$20M Revenue / Private Enterprise | Academic/lab desktop license starting from ~$10,000/seat/year (HALO base quantitative analysis) | 14-day full-feature trial license (single workstation, includes core tissue segmentation & cell analysis modules) | Quantitative digital pathology image analysis and browser-based slide management platform widely used in spatial biology, oncology, and IHC research. |
| **[Visiopharm](https://visiopharm.com)** | ~$15M Revenue (Acquired by Grundium) | Research analysis APP tier starting from ~$12,000/seat/year (modular AI tissue analysis package) | 14-day evaluation license (single user, access to 2 standard oncology biomarker APPs on local slides) | AI-driven precision pathology and spatial biology software suite offering automated tissue segmentation, multiplexing analysis, and enterprise slide management. |

## Open-Source GitHub Projects

Curated open-source libraries, web viewers, slide servers, and computational pathology toolkits sorted by GitHub stars:

- **[libvips](https://github.com/libvips/libvips)** [![GitHub stars](https://img.shields.io/github/stars/libvips/libvips?style=social&color=white)](https://github.com/libvips/libvips/stargazers)  
  Ultra-fast, low-memory demand-driven C image processing library widely used in digital pathology servers to generate Deep Zoom (DZI) and pyramidal OME-TIFF tiles from massive slides.

- **[MONAI](https://github.com/Project-MONAI/MONAI)** [![GitHub stars](https://img.shields.io/github/Project-MONAI/MONAI?style=social&color=white)](https://github.com/Project-MONAI/MONAI/stargazers)  
  Leading PyTorch-based open-source healthcare AI framework featuring dedicated whole-slide pathology pipelines for tumor detection, patch-level inference, and multi-scale WSI training.

- **[OpenSeadragon](https://github.com/openseadragon/openseadragon)** [![GitHub stars](https://img.shields.io/github/stars/openseadragon/openseadragon?style=social&color=white)](https://github.com/openseadragon/openseadragon/stargazers)  
  Industry-standard open-source JavaScript deep-zoom viewer powering smooth pan-and-zoom web visualization of gigapixel pyramidal pathology slides across major browsers.

- **[napari](https://github.com/napari/napari)** [![GitHub stars](https://img.shields.io/github/stars/napari/napari?style=social&color=white)](https://github.com/napari/napari/stargazers)  
  Fast, interactive multi-dimensional bioimage viewer in Python with `napari-lazy-openslide` and `napari-spatialdata` plugins for exploring multi-gigapixel histopathology and multiplexed tissue layers.

- **[CLAM](https://github.com/mahmoodlab/CLAM)** [![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/CLAM?style=social&color=white)](https://github.com/mahmoodlab/CLAM/stargazers)  
  Pioneering open-source weakly supervised deep-learning framework (Clustering-constrained Attention Multiple Instance Learning) for whole-slide classification and attention heatmap generation without pixel annotations.

- **[QuPath](https://github.com/qupath/qupath)** [![GitHub stars](https://img.shields.io/github/stars/qupath/qupath?style=social&color=white)](https://github.com/qupath/qupath/stargazers)  
  Flagship cross-platform open-source desktop application for bioimage analysis and digital pathology—featuring fluid gigapixel WSI viewing, cell/nuclei detection, trainable pixel classifiers, and Groovy/Python scripting.

- **[StarDist](https://github.com/stardist/stardist)** [![GitHub stars](https://img.shields.io/github/stars/stardist/stardist?style=social&color=white)](https://github.com/stardist/stardist/stargazers)  
  Deep-learning tool for 2D/3D star-convex object detection and instance segmentation widely integrated with QuPath for high-density nuclei detection in H&E and fluorescence pathology.

- **[UNI](https://github.com/mahmoodlab/UNI)** [![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/UNI?style=social&color=white)](https://github.com/mahmoodlab/UNI/stargazers)  
  General-purpose self-supervised pathology foundation model pre-trained on 100M+ gigapixel histopathology patches for transfer learning and diagnostic classification across 30+ disease tasks.

- **[HoVer-Net](https://github.com/vqdang/hover_net)** [![GitHub stars](https://img.shields.io/github/stars/vqdang/hover_net?style=social&color=white)](https://github.com/vqdang/hover_net/stargazers)  
  Simultaneous nuclear instance segmentation and cell-type classification (lymphocytes, epithelial, stromal) in histology images using horizontal and vertical distance maps.

- **[TRIDENT](https://github.com/mahmoodlab/TRIDENT)** [![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/TRIDENT?style=social&color=white)](https://github.com/mahmoodlab/TRIDENT/stargazers)  
  Open-source multi-scale computational pathology toolkit for automated whole-slide tissue segmentation, artifact rejection, and scalable patch extraction.

- **[Prov-GigaPath](https://github.com/prov-gigapath/prov-gigapath)** [![GitHub stars](https://img.shields.io/github/stars/prov-gigapath/prov-gigapath?style=social&color=white)](https://github.com/prov-gigapath/prov-gigapath/stargazers)  
  Whole-slide pathology foundation model pre-trained on 1.3 billion pathology tiles from 170,000+ WSIs developed by Providence and Microsoft Research for slide-level representation learning.

- **[TIAToolbox](https://github.com/TissueImageAnalytics/tiatoolbox)** [![GitHub stars](https://img.shields.io/github/stars/TissueImageAnalytics/tiatoolbox?style=social&color=white)](https://github.com/TissueImageAnalytics/tiatoolbox/stargazers)  
  Comprehensive open-source Python computational pathology suite from Warwick TIA Centre providing WSI reading, stain normalization, tissue masking, patch extraction, and pre-trained deep-learning models.

- **[OpenSlide](https://github.com/openslide/openslide)** [![GitHub stars](https://img.shields.io/github/stars/openslide/openslide?style=social&color=white)](https://github.com/openslide/openslide/stargazers)  
  Foundational open-source C library and bindings providing a simple, vendor-neutral interface for reading multi-resolution whole-slide image pyramids (`.svs`, `.ndpi`, `.vms`, `.scn`, `.mrxs`, `.tiff`).

- **[histolab](https://github.com/histolab/histolab)** [![GitHub stars](https://img.shields.io/github/stars/histolab/histolab?style=social&color=white)](https://github.com/histolab/histolab/stargazers)  
  Python library for digital pathology image preprocessing, whole-slide tissue extraction, artifact filtering, and reproducible slide tiling pipelines.

- **[HistoQC](https://github.com/choosehappy/HistoQC)** [![GitHub stars](https://img.shields.io/github/stars/choosehappy/HistoQC?style=social&color=white)](https://github.com/choosehappy/HistoQC/stargazers)  
  Open-source automated digital pathology quality-control pipeline detecting blur, pen markings, tissue folds, and staining artifacts across large WSI cohorts.

- **[HistoCartography](https://github.com/BiomedSciAI/histocartography)** [![GitHub stars](https://img.shields.io/github/stars/BiomedSciAI/histocartography?style=social&color=white)](https://github.com/BiomedSciAI/histocartography/stargazers)  
  Standardized Python framework with preprocessing, machine learning, and explainability tools for graph-based spatial analytics and cellular topology in computational pathology.

- **[deep-histopath](https://github.com/CODAIT/deep-histopath)** [![GitHub stars](https://img.shields.io/github/stars/CODAIT/deep-histopath?style=social&color=white)](https://github.com/CODAIT/deep-histopath/stargazers)  
  Deep learning pipeline and reference models for histopathologic lymph node metastasis classification on gigapixel pathology slides.

- **[SLIM](https://github.com/ImagingDataCommons/slim)** [![GitHub stars](https://img.shields.io/github/stars/ImagingDataCommons/slim?style=social&color=white)](https://github.com/ImagingDataCommons/slim/stargazers)  
  Interoperable, zero-footprint web viewer for DICOM Whole Slide Imaging (WSI) with support for microcopy image annotations, heatmaps, and DICOMweb retrieval.

- **[Patch-GCN](https://github.com/mahmoodlab/Patch-GCN)** [![GitHub stars](https://img.shields.io/github/stars/mahmoodlab/Patch-GCN?style=social&color=white)](https://github.com/mahmoodlab/Patch-GCN/stargazers)  
  Context-aware survival prediction using patch-based Graph Convolutional Networks that model both topological and phenotypic heterogeneity in whole-slide images.

- **[Digital Slide Archive (DSA) & HistomicsUI](https://github.com/DigitalSlideArchive/digital_slide_archive)** [![GitHub stars](https://img.shields.io/github/stars/DigitalSlideArchive/digital_slide_archive?style=social&color=white)](https://github.com/DigitalSlideArchive/digital_slide_archive/stargazers)  
  Full-stack self-hosted open-source web platform for managing, annotating, streaming, and running containerized Docker algorithms on gigapixel pathology slides.

- **[pathology-whole-slide-data](https://github.com/DIAGNijmegen/pathology-whole-slide-data)** [![GitHub stars](https://img.shields.io/github/stars/DIAGNijmegen/pathology-whole-slide-data?style=social&color=white)](https://github.com/DIAGNijmegen/pathology-whole-slide-data/stargazers)  
  Python package for working with whole-slide data featuring a fast batch iterator and patch extraction utilities for training deep learning models.

- **[marugoto](https://github.com/KatherLab/marugoto)** [![GitHub stars](https://img.shields.io/github/stars/KatherLab/marugoto?style=social&color=white)](https://github.com/KatherLab/marugoto/stargazers)  
  Open-source deep-learning toolbox for weakly supervised biomarker prediction, survival analysis, and molecular profiling from histology slides.

- **[TiffSlide](https://github.com/Bayer-Group/tiffslide)** [![GitHub stars](https://img.shields.io/github/stars/Bayer-Group/tiffslide?style=social&color=white)](https://github.com/Bayer-Group/tiffslide/stargazers)  
  Cloud-native, `tifffile`-based drop-in replacement for OpenSlide Python, supporting remote whole-slide image reading and caching from cloud object stores.

- **[WSIDicom](https://github.com/imi-bigpicture/wsidicom)** [![GitHub stars](https://img.shields.io/github/stars/imi-bigpicture/wsidicom?style=social&color=white)](https://github.com/imi-bigpicture/wsidicom/stargazers)  
  Open-source Python library for reading, tiling, and converting whole-slide images according to the DICOM WSI standard for clinical archive integration.

- **[Cytomine](https://github.com/cytomine/cytomine)** [![GitHub stars](https://img.shields.io/github/stars/cytomine/cytomine?style=social&color=white)](https://github.com/cytomine/cytomine/stargazers)  
  Rich open-source collaborative web platform for multi-gigapixel biomedical imaging featuring semantic ontology annotations, REST APIs, and reproducible AI algorithm integration.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ Buy me a coffee / Sponsor my open-source work on GitHub Sponsors — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

## Disclaimer

- This is a community-curated list — not exhaustive and not an endorsement.
- Medical & Regulatory Notice: Open-source digital pathology tools (QuPath, OpenSlide, TIAToolbox, MONAI) are intended for research and educational use only and are not FDA-cleared or CE-IVD certified for primary clinical diagnosis; always rely on validated, regulatory-approved clinical systems and qualified pathologists for patient care.
- Whole-slide images containing patient identifiers or clinical metadata must be de-identified (WSIDicom / DICOM anonymization profiles) and stored in HIPAA/GDPR-compliant encrypted infrastructure.

Made for pathologists, computational pathology researchers, biomedical engineers, spatial biologists, and open-source contributors.  
Let's make digital pathology and whole-slide imaging more open, interoperable, and reproducible.
