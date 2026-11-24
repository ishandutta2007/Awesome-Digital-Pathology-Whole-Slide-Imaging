# Awesome-Digital-Pathology-Whole-Slide-Imaging

markdown

## Top Digital Pathology & Whole-Slide Imaging Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Whole-Slide Imaging (WSI) Viewers, Computational Pathology AI, Gigapixel Tissue Analysis, Slide Servers & Histopathology Toolkits*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Digital Pathology & Whole-Slide Imaging (WSI)**. These tools decode, tile, stream, annotate, segment, and analyze gigapixel histopathology slides (`.svs`, `.ndpi`, `.mrxs`, `.scn`, `.tiff`, DICOM WSI) across clinical pathology workspaces, web-based pyramid viewers, and computational pathology ML pipelines.



**Examples** include Proscia Concentriq, Philips IntelliSite, Leica Biosystems Aperio, Sectra Digital Pathology, Roche NAVIFY Digital Pathology, Paige.ai, PathAI, Visiopharm, Indica Labs HALO, Hamamatsu NanoZoomer Cloud, and open-slide/open-slide (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for WSI decoding & pyramid I/O (`openslide/openslide`, `open-slide/open-slide`, `libvips`, `TiffSlide`, `WSIDicom`), desktop & web gigapixel slide viewers (`QuPath`, `OpenSeadragon`, `Digital Slide Archive / HistomicsUI`, `Cytomine`, `SLIM`), and computational pathology deep-learning toolkits (`TIAToolbox`, `MONAI Pathology`, `CLAM`, `HistoCartography`) — ideal for pathologists, computational pathology researchers, biomedical engineers, and clinical informatics teams.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Proscia Concentriq](https://proscia.com)**  

  Cloud-native enterprise digital pathology platform and AI portfolio orchestrator uniting whole-slide management, clinical/research collaboration, and third-party diagnostic AI apps.



- **[Paige.ai (Paige Platform & Virchow Ecosystem)](https://paige.ai)**  

  Clinical-grade computational pathology SaaS and foundation-model ecosystem offering FDA-cleared diagnostic AI modules and cloud whole-slide viewing.



- **[PathAI (AISight)](https://pathai.com)**  

  Cloud-based digital pathology image management system (IMS) and AI-powered biomarker quantification platform supporting clinical trials, biopharma research, and diagnostic workflows.



- **[Philips IntelliSite Pathology Solution](https://philips.com)**  

  End-to-end clinical digital pathology suite combining ultra-fast whole-slide scanners, a scalable Image Management System (IMS), and integrated case viewers.



- **[Leica Biosystems Aperio (eSlide Manager & Aperio HALO AP)](https://leicabiosystems.com)**  

  Enterprise web-based digital pathology management and viewing ecosystem engineered for multi-site hospital networks, telepathology, and `.svs` slide workflows.



- **[Sectra Digital Pathology](https://sectra.com)**  

  Enterprise diagnostic pathology PACS and VNA platform uniting radiology and pathology imaging in a single vendor-neutral, high-speed clinical viewer.



- **[Roche NAVIFY Digital Pathology](https://roche.com)**  

  Cloud-integrated enterprise workflow software connecting whole-slide scanning, image analysis algorithms, and laboratory information systems (LIS) for clinical diagnostics.



- **[Indica Labs HALO & HALO Link](https://indicalab.com)**  

  Quantitative digital pathology image analysis and browser-based slide management platform widely used in spatial biology, oncology, and IHC biomarker research.



- **[Visiopharm](https://visiopharm.com)**  

  AI-driven precision pathology and spatial biology software suite offering automated tissue segmentation, multiplexing analysis, and enterprise slide management.



- **[Hamamatsu NanoZoomer Cloud / NDP.serve](https://hamamatsu.com)**  

  Whole-slide imaging ecosystem and cloud/network slide-serving software engineered for high-throughput `.ndpi` scanning, remote telepathology, and multi-user viewing.





## Open-Source GitHub Projects



- **[open-slide/open-slide](https://github.com) & Official OpenSlide (`openslide/openslide`)](https://github.com)**  

  Foundational open-source C libraries and bindings providing a simple, vendor-neutral interface for reading multi-resolution whole-slide image pyramids (`.svs`, `.ndpi`, `.vms`, `.scn`, `.mrxs`, `.tiff`).



- **[QuPath (`qupath/qupath`)](https://github.com)**  

  Flagship cross-platform open-source desktop application for bioimage analysis and digital pathology—featuring fluid gigapixel WSI viewing, cell/nuclei detection, trainable pixel classifiers, and Groovy/Python scripting.



- **[TIAToolbox (`TissueImageAnalytics/tiatoolbox`)](https://github.com)**  

  Comprehensive open-source Python computational pathology suite from Warwick TIA Centre providing WSI reading, stain normalization, tissue masking, patch extraction, and pre-trained deep-learning models.



- **[Digital Slide Archive — DSA & HistomicsUI (`DigitalSlideArchive/digital_slide_archive`)](https://github.com)**  

  Full-stack self-hosted open-source web platform (built on Girder and `large_image`) for managing, annotating, streaming, and running containerized Docker algorithms on gigapixel pathology slides.



- **[Cytomine (`cytomine/cytomine`)](https://github.com)**  

  Rich open-source collaborative web platform for multi-gigapixel biomedical imaging featuring semantic ontology annotations, REST APIs, and reproducible AI algorithm integration.



- **[OpenSeadragon (`openseadragon/openseadragon`)](https://github.com)**  

  Industry-standard open-source JavaScript deep-zoom viewer powering smooth pan-and-zoom web visualization of gigapixel pyramidal pathology slides across major browsers.



- **[MONAI (`Project-MONAI/MONAI`)](https://github.com)**  

  Leading PyTorch-based open-source healthcare AI framework featuring dedicated whole-slide pathology pipelines for tumor detection, patch-level inference, and multi-scale WSI training.



- **[CLAM (`mahmoodlab/CLAM`)](https://github.com)**  

  Pioneering open-source weakly supervised deep-learning framework (Clustering-constrained Attention Multiple Instance Learning) for whole-slide classification and attention heatmap generation without pixel annotations.



- **[libvips (`libvips/libvips`)](https://github.com)**  

  Ultra-fast, low-memory demand-driven C image processing library widely used in digital pathology servers to generate Deep Zoom (DZI) and pyramidal OME-TIFF tiles from massive slides.



- **[WSIDicom (`imi-bigpicture/wsidicom`) & SLIM (`ImagingDataCommons/slim`)](https://github.com)**  

  Open-source Python library (`wsidicom`) and zero-footprint web viewer (`SLIM`) implementing the open DICOM Whole Slide Imaging standard for vendor-neutral clinical interoperability.



- **[TiffSlide (`bayer-science-for-a-better-life/tiffslide`) & CuCIM (`rapidsai/cucim`)](https://github.com)**  

  High-performance open-source drop-in replacements for OpenSlide (`tiffslide` backed by `tifffile`/`zarr` and NVIDIA `cuCIM` for GPU-accelerated WSI I/O and transforms).



### Additional Strong Open-Source Options



- **[TRIDENT (`mahmoodlab/TRIDENT`)](https://github.com)** and **[UNI / CONCH Foundation Model Toolkits (`mahmoodlab/UNI`)](https://github.com)** for open-source large-scale WSI tissue segmentation, patching, and pathology foundation-model feature extraction.

- **[HistoQC (`choosehappy/HistoQC`)](https://github.com)** for an open-source automated digital pathology quality-control pipeline detecting blur, pen markings, tissue folds, and staining artifacts across WSI cohorts.

- **[Napari (`napari/napari`)](https://github.com)** with `napari-spatialdata` / `napari-lazy-openslide` for fast, multi-dimensional Python visualization of multiplexed immunofluorescence and whole-slide pathology layers.

- **[Orthanc (`orthanc-server/orthanc`)](https://github.com)** with the official Orthanc WSI plugin (`orthanc-wsi`) for a lightweight, self-hosted open-source DICOM server capable of converting and serving whole-slide images over DICOMweb.

- **[Hover-Net (`vqdang/hover_net`) & StarDist (`stardist/stardist`)](https://github.com)** for gold-standard open-source simultaneous nuclear instance segmentation and cell-type classification in H&E histopathology images.



**Frameworks for building custom systems**: Combine **OpenSlide / TiffSlide + libvips** for fast multi-format WSI tile extraction, **QuPath + StarDist** for interactive desktop cell quantification and annotation, **Digital Slide Archive + OpenSeadragon** for self-hosted web slide management, and **TIAToolbox + MONAI** for computational pathology ML pipelines.



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

Use code with caution.

• ☕ Buy me a coffee / Sponsor my open-source work on GitHub Sponsors — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



Disclaimer



• This is a community-curated list — not exhaustive and not an endorsement.

• Medical & Regulatory Notice: Open-source digital pathology tools (QuPath, OpenSlide, TIAToolbox, MONAI) are intended for research and educational use only and are not FDA-cleared or CE-IVD certified for primary clinical diagnosis; always rely on validated, regulatory-approved clinical systems and qualified pathologists for patient care.

• Whole-slide images containing patient identifiers or clinical metadata must be de-identified (WSIDicom / DICOM anonymization profiles) and stored in HIPAA/GDPR-compliant encrypted infrastructure.

Made for pathologists, computational pathology researchers, biomedical engineers, spatial biologists, and open-source contributors.

Let's make digital pathology and whole-slide imaging more open, interoperable, and reproducible.
