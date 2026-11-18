# Awesome-3D-Scene-Reconstruction-Computer-Vision

# Top 3D Scene Reconstruction & Computer Vision Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Photogrammetry, Structure-from-Motion (SfM), Multi-View Stereo (MVS), Neural Radiance Fields (NeRF/3DGS) & Foundation 3D Reconstruction*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Scene Reconstruction & Computer Vision**. These tools reconstruct metric 3D scenes, dense point clouds, textured meshes, and real-time radiance fields from uncalibrated photographs, video streams, or LiDAR sensors.

**Examples** include Luma AI, Polycam, Scaniverse, KIRI Engine, RealityCapture (Capturing Reality), Agisoft Metashape, Matterport, Artec Cloud, Nerfstudio, and apekshik/anyscene (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for Structure-from-Motion (SfM), Multi-View Stereo (MVS), feed-forward visual geometry foundation models (`VGGT`, `DUSt3R`, `MASt3R`), 3D Gaussian Splatting, and real-time dense SLAM — ideal for computer vision engineers, VFX artists, digital twin builders, and robotics researchers building transparent pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Luma AI](https://lumalabs.ai)**  
  Cloud AI 3D capture and radiance field platform converting smartphone videos into photorealistic 3D Gaussian Splats, textured meshes, and embeddable WebGL scenes.

- **[Polycam](https://poly.cam)**  
  Cross-platform mobile and web 3D scanning suite supporting cloud photogrammetry, LiDAR capture, 3D Gaussian Splatting, and browser-native sharing.

- **[Niantic Scaniverse](https://scaniverse.com)**  
  Mobile spatial scanning app offering on-device 3D Gaussian Splatting and dense mesh reconstruction for geospatial world mapping and offline editing.

- **[KIRI Engine](https://kiriengine.app)**  
  Cloud 3D scanning and Gaussian Splatting platform providing photo-to-3D reconstruction, feature-less object scanning, quad-retopology, and Blender integration.

- **[Epic Games RealityCapture (Capturing Reality)](https://capturingreality.com)**  
  Industry-standard photogrammetry and laser-scanning reconstruction software capable of generating ultra-high-resolution textured 3D meshes and ortho-projections.

- **[Agisoft Metashape & Metashape Cloud](https://agisoft.com)**  
  Commercial photogrammetric processing pipeline and cloud service producing dense point clouds, textured 3D models, and georeferenced digital elevation models.

- **[Matterport](https://matterport.com)**  
  Enterprise cloud spatial data and digital twin platform transforming 360-degree cameras, LiDAR scanners, and smartphones into navigable 3D virtual tours and BIM files.

- **[Artec Cloud](https://artec3d.com)**  
  Cloud-based 3D scan processing, point-cloud registration, mesh reconstruction, and collaborative inspection platform built for precision 3D scanners.

- **[Pix4Dcloud](https://pix4d.com)**  
  Cloud photogrammetry and drone mapping SaaS platform converting aerial and terrestrial imagery into measurable 3D meshes, point clouds, and CAD overlays.

- **[DroneDeploy](https://dronedeploy.com)**  
  Cloud reality-capture and site intelligence platform automating drone and 360-camera 3D scene reconstruction for construction, energy, and surveying.


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
