# Awesome-3D-Scene-Reconstruction-Computer-Vision

## Top 3D Scene Reconstruction & Computer Vision Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Photogrammetry, Structure-from-Motion (SfM), Multi-View Stereo (MVS), Neural Radiance Fields (NeRF/3DGS) & Foundation 3D Reconstruction*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Scene Reconstruction & Computer Vision**. These tools reconstruct metric 3D scenes, dense point clouds, textured meshes, and real-time radiance fields from uncalibrated photographs, video streams, or LiDAR sensors.



**Examples** include Luma AI, Polycam, Scaniverse, KIRI Engine, RealityCapture (Capturing Reality), Agisoft Metashape, Matterport, Artec Cloud, Nerfstudio, and apekshik/anyscene (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for Structure-from-Motion (SfM), Multi-View Stereo (MVS), feed-forward visual geometry foundation models (`VGGT`, `DUSt3R`, `MASt3R`), 3D Gaussian Splatting, and real-time dense SLAM — ideal for computer vision engineers, VFX artists, digital twin builders, and robotics researchers building transparent pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global 3D reconstruction and computer vision spatial mapping sector is valued at approximately $1.6B–$1.9B (projected to reach over $3.2B by the early 2030s at an 11–17% CAGR). The market is moderately to highly fragmented across vertical niches (BIM/digital twins, aerial drone surveying, industrial metrology, gaming, and consumer spatial AI) rather than a winner-take-all monopoly, characterized by competing active sensor and passive neural vision paradigms (SfM/MVS, NeRF, and 3D Gaussian Splatting) alongside frequent targeted acquisitions by larger infrastructure and gaming giants.

## SaaS/Hosted Platforms

| Company / Platform | Company Scale (Valuation / Revenue) | Description | Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Epic Games RealityCapture](https://capturingreality.com)** | **$22.5B Valuation** (~$5B+ annual revenue) | Industry-standard photogrammetry & laser-scanning reconstruction software producing ultra-high-resolution textured 3D meshes and ortho-projections. | Free for revenue <$1M/yr; **$1,250/seat/year** for enterprise (or $1,850/yr Unreal bundle) | **Free forever** for all individuals, students, educators, and businesses with gross annual revenue under $1,000,000 USD (full features). |
| **[Niantic Scaniverse](https://scaniverse.com)** | **$3.5B Unit Valuation** (historic $9B valuation, ~$650M–$700M peak revenue) | Mobile spatial capture app offering fast on-device 3D Gaussian Splatting, LiDAR scanning, and cloud rendering for geospatial world mapping. | Paid cloud plans start at **$20/month** (Plus, or $200/yr) up to $50/mo (Pro) | **Free forever** for unlimited on-device captures, Gaussian splat processing, and mesh exports (SPZ, FBX, PLY); includes 20,000 free monthly cloud credits. |
| **[Luma AI](https://lumalabs.ai)** | **$4.0B Valuation** (~$900M Series C, tens of millions ARR) | Cloud AI 3D capture and radiance field platform converting mobile video into photorealistic 3D Gaussian Splats, textured meshes, and interactive WebGL scenes. | Paid subscription plans start at **$30/month** (Plus, or $25/mo billed annually) | **Free forever** basic tier with limited daily regeneration credits (~30 video/capture generations, non-commercial/watermarked). |
| **[Matterport](https://matterport.com)** | **$1.6B Valuation / Mkt Cap** (Nasdaq: MTTR, ~$170M annual revenue) | Enterprise spatial data and digital twin SaaS transforming 360 cameras, LiDAR scanners, and smartphones into navigable 3D virtual tours and BIM files. | Paid self-serve plans start at **$108/month** (Professional tier, or $90/mo billed annually) | **Free forever** plan limited to 1 active space/digital twin at a time, 1 user, smartphone/360-camera capture only (no Matterport Pro cameras). |
| **[DroneDeploy](https://dronedeploy.com)** | **$845M Acquisition Valuation** (Acquired by Procore; ~$78M annual revenue) | Enterprise drone reality capture and site intelligence platform automating aerial and 360-camera 3D reconstruction for construction and surveying. | Paid self-serve plans start at **$159/month** (Ag-Lite, billed annually) or $329/mo (Individual) | **14-day free trial** with full platform exploration, flight planning, and 2D/3D map generation capabilities (no credit card required). |
| **[Pix4Dcloud](https://pix4d.com)** | **$25M Valuation** (~$14M–$30M annual revenue) | Cloud photogrammetry and drone mapping SaaS converting aerial/terrestrial imagery into measurable 3D meshes, point clouds, and CAD overlays. | Paid plans start at **$129/month** (Pix4Dcloud Starter, or $107.50/mo billed annually); Pro at $449/mo | **15-day free trial** with full PIX4Dcloud Pro features, including an allocation of 40 processing credits (~200 images at 20 MP; trial data expires after 30 days). |
| **[Artec Cloud](https://artec3d.com)** | **$25M–$30M Annual Revenue** (Privately held, backed by European Investment Bank) | Cloud 3D scan processing, point-cloud registration, mesh reconstruction, and collaborative browser inspection for precision industrial 3D scanners. | Paid storage tiers start at **$70/month** (200 GB, or $59/mo billed annually) | **Free forever** entry plan providing 5 GB of cloud storage for viewing, commenting, and project backup. |
| **[Polycam](https://poly.cam)** | **$6.5M Annual Revenue** (Venture-backed Series A) | Cross-platform mobile and web 3D scanning suite supporting cloud photogrammetry, LiDAR capture, 3D Gaussian Splatting, and browser-native sharing. | Paid plans start at **$30/month** (Polycam Basic, or ~$150/year billed annually); Business from $25/seat/mo | **Free forever** plan for basic mobile capture and viewing; advanced CAD/BIM/point-cloud exports and unlimited splat processing require paid tiers. |
| **[Agisoft Metashape Cloud](https://agisoft.com)** | **$3M–$4M Annual Revenue** (Privately held / bootstrapped) | Cloud photogrammetric processing pipeline and storage backend for Metashape Professional producing dense point clouds and georeferenced DEMs. | Commercial storage starts at **$10/month** for 100 GB (plus pay-per-use processing at $4.25/compute hour) | **Free plan** providing 50 GB cloud storage and 20 compute hours per month renewed monthly (available for trial, Metashape Pro trial, and educational users). |
| **[KIRI Engine](https://kiriengine.app)** | **Bootstrap / Seed Stage** (<$3M estimated revenue) | Cloud 3D scanning and Gaussian Splatting app offering photo-to-3D reconstruction, featureless object scanning, quad-retopology, and Blender integration. | Pro subscription starts at **$79.99/year** (~$6.66/month equivalent) or $17.99 month-to-month | **Free forever** plan with unlimited free exports (OBJ, FBX, STL, GLB/GLTF, USDZ) and unlimited LiDAR scans, capped at 150 photos (2 GB) per photogrammetry scan. |





## Open-Source GitHub Projects



- **[apekshik/anyscene](https://github.com)**  

  Open-source (`MIT`) feed-forward monocular 3D scene reconstruction pipeline combining `Depth Anything V2` with `MASt3R` dense camera/geometry matching to reconstruct colored point clouds (`PLY`, `GLB`) from arbitrary images or videos with optional `COLMAP` export.



- **[COLMAP](https://github.com)**  

  Industry-standard open-source (`BSD-3-Clause`) general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with both graphical and headless CLI interfaces.



- **[GLOMAP](https://github.com)**  

  ECCV 2024 open-source (`BSD-3-Clause`) global Structure-from-Motion mapper tightly integrated with COLMAP that recovers camera poses orders of magnitude faster than incremental SfM.



- **[AliceVision Meshroom](https://github.com)**  

  Full-featured open-source (`MPL-2.0`) node-based photogrammetry software built on the AliceVision computer vision framework for end-to-end photo-to-textured-mesh reconstruction.



- **[OpenMVG (Open Multiple View Geometry)](https://github.com)**  

  Modular open-source (`MPL-2.0`) C++ computer vision library for feature extraction, robust epipolar geometry, global/incremental SfM, and camera calibration.



- **[OpenMVS (Open Multi-View Stereo)](https://github.com)**  

  Open-source (`AGPL-3.0`) multi-view stereo reconstruction library that takes SfM camera poses and produces dense point clouds, watertight surface meshes, and high-res textures.



- **[VGGT (Visual Geometry Grounded Transformer)](https://github.com)**  

  CVPR 2025 Best Paper open-source (`MIT`) feed-forward Transformer from Meta AI that directly infers camera parameters, depth maps, point maps, and 3D tracks from one to hundreds of views in seconds.



- **[DUSt3R & MASt3R (`naver/dust3r`)](https://github.com)**  

  Open-source dense 3D reconstruction frameworks from NAVER Labs Europe capable of recovering calibrated 3D pointmaps and pixel-level correspondences from uncalibrated image pairs without prior intrinsics.



- **[Nerfstudio](https://github.com)**  

  Modular open-source (`Apache-2.0`) PyTorch framework unifying 3D Gaussian Splatting (`splatfacto`), NeRFs (`nerfacto`), COLMAP/GLOMAP pose estimation, and a real-time web viewer.



- **[OpenDroneMap (ODM & WebODM)](https://github.com)**  

  Production-grade open-source (`AGPL-3.0`) aerial and terrestrial photogrammetry toolkit generating georeferenced 3D textured meshes, point clouds, and orthophotos via CLI or web UI.



- **[RTAB-Map](https://github.com)**  

  Cross-platform open-source (`BSD-3-Clause`) RGB-D, Stereo, and LiDAR graph-based SLAM system for real-time 3D indoor/outdoor scene mapping and loop closure.



- **[Gaussian Splatting (`graphdeco-inria/gaussian-splatting`)](https://github.com)**  

  Reference SIGGRAPH 2023 open-source CUDA implementation for real-time photorealistic 3D scene reconstruction and radiance field rendering from calibrated photographs.



- **[2D Gaussian Splatting (`hbb1/2d-gaussian-splatting`)](https://github.com)**  

  SIGGRAPH 2024 open-source (`MIT`) surface reconstruction method using 2D oriented planar disks to extract clean, geometrically accurate triangle meshes from radiance fields.



- **[Instant-NGP (`NVlabs/instant-ngp`)](https://github.com)**  

  NVIDIA open-source multiresolution hash-encoding framework for ultra-fast neural radiance field (`NeRF`) and signed distance function (`SDF`) 3D scene reconstruction.



- **[Open3D (`isl-org/Open3D`)](https://github.com)**  

  Modern open-source (`MIT`) C++ and Python library providing RGB-D odometry, TSDF volumetric integration, multi-way registration, and Poisson/Ball-Pivoting mesh reconstruction.



### Additional Strong Open-Source Options



- **[Depth Anything V2](https://github.com)** and **[Depth Pro (Apple)](https://github.com)** for sharp, metric monocular depth estimation used in single-image and video 3D scene lifting.

- **[Map-Anything (`facebookresearch/map-anything`)](https://github.com)** and **[SpaTracker / VGGT-SLAM](https://github.com)** for universal feed-forward metric 3D reconstruction across diverse camera geometries.

- **[MonoGS (`muskie82/MonoGS`)](https://github.com)** and **[SplaTAM (`spla-tam/SplaTAM`)](https://github.com)** for real-time 3D Gaussian Splatting monocular and RGB-D SLAM scene reconstruction.

- **[NeuS2 (`19reborn/NeuS2`)](https://github.com)** and **[BakedSDF](https://github.com)** for fast neural implicit surface reconstruction and real-time mesh extraction.

- **[CloudCompare](https://github.com)** and **[MeshLab](https://github.com)** for post-reconstruction point-cloud alignment, cleanup, decimation, and texture baking.



**Frameworks for building custom systems**: Combine **GLOMAP / COLMAP** or **VGGT / MASt3R** (for camera pose & pointmap estimation) with **OpenMVS** (for textured meshes) or **Nerfstudio (`gsplat`)** (for photorealistic 3DGS) and **Open3D / CloudCompare** for end-to-end open-source 3D scene reconstruction pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Photogrammetry (`COLMAP`, `Meshroom`, `OpenMVS`) and neural reconstruction (`Nerfstudio`, `VGGT`, `MASt3R`) pipelines benefit substantially from NVIDIA CUDA GPUs, sufficient RAM/VRAM, and sharp, well-overlapping input imagery.
