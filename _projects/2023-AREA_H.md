---
title: "AREA-H: Accelerating Robotics and Embedding Autonomy in Horticulture"
collection: projects
type: "Principal Investigator at LU"
permalink: /projects/2023-AREA-H
funder: "Innovate UK"
date: 2023-09-01
enddate: 2026-8-31
value: "£423k/£1.48m"
ID: "10073332"
---

{% include base_path %}

This project is part of UK government's recent initiatives to boost sustainable farming with robotics and automation. More background information please see [this link](https://www.gov.uk/government/news/125m-for-robotics-and-automation-to-boost-sustainable-farming). 

![image](/images/AreaH_logo.png)

Co-Investigators at Loughborough University: 
* [Dr Matthew Coombes](https://www.lboro.ac.uk/departments/aae/staff/matthew-coombes/)
* [Prof William Whittow](https://www.lboro.ac.uk/departments/meme/staff/william-whittow/)
* [Prof Lisa Jackson](https://www.lboro.ac.uk/departments/aae/staff/lisa-jackson/)

---

## Research in AREA-H at Loughborough

At Loughborough, our work in AREA-H focuses on **localisation, place recognition, and mapping for horticultural robots operating in commercial polytunnel environments**. These environments are particularly challenging for autonomy because they combine long repetitive crop rows, strong perceptual aliasing, dynamic foliage, seasonal appearance variation, reflections from plastic tunnel covers, and often unreliable GNSS.

Our research therefore looks at how to make robotic perception and localisation more robust in these realistic agricultural conditions. This includes work on:

- **multi-sensor and landmark-assited localisation and mapping** in polytunnels,
- **3D LiDAR-based place recognition** for repetitive horticultural environments,
- **cross-season robustness** under crop growth and appearance change,
- **benchmarking and dataset development** for evaluating SLAM and localisation methods in protected horticulture.

<div style="margin: 1.5rem 0; text-align: center;">
  <img src="{{ base_path }}/images/projects/area-h/hortimulti_overview.png" alt="HortiMulti overview in commercial horticultural polytunnels" style="max-width: 100%; border-radius: 6px;">
  <p style="font-size: 0.9em; color: #666; margin-top: 0.5rem;">
    Multi-sensor data collection and localisation/mapping research in commercial horticultural polytunnels.
  </p>
</div>

## Platforms and sensing

Our recent experiments use Antobot's Assist robotic platforms equipped with **3D LiDARs, RGB cameras, IMU, GNSS and wheel odometry**. In the AREA-H work, the sensing setup is enhanced by careful calibration and time synchronisation, enabling the study of visual, LiDAR and multi-sensor SLAM in realistic commercial conditions.

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1.5rem 0;">
  <div style="flex: 1 1 320px; min-width: 280px;">
    <img src="{{ base_path }}/images/projects/area-h/sensor_setup.png" alt="Sensor setup for horticultural robot platform" style="width: 100%; border-radius: 6px;">
  </div>
  <div style="flex: 1 1 320px; min-width: 280px;">
    <img src=""{{ base_path }}/images/AREA_H/areah_platform.png"" alt="Robot platform operating in a polytunnel" style="width: 100%; border-radius: 6px;">
  </div>
</div>

## Recent outputs

### HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels

A recent output from the project is **HortiMulti**, a multi-sensor, cross-season dataset designed to support research on localisation and mapping in commercial strawberry and raspberry polytunnels. The dataset provides time-synchronised raw data, calibration files, reference trajectories and baseline benchmarks for **visual, LiDAR and multi-sensor SLAM**, and highlights the limitations of current methods in these environments.

<div style="margin: 1rem 0 1.25rem 0;">
  <a href="https://arxiv.org/abs/2603.20150" target="_blank" style="display:inline-block; padding:0.35rem 0.7rem; margin-right:0.5rem; border:1px solid #2c7be5; border-radius:999px; text-decoration:none;">Paper</a>
  <a href="https://github.com/shuoyuanxu/HortiMulti" target="_blank" style="display:inline-block; padding:0.35rem 0.7rem; margin-right:0.5rem; border:1px solid #28a745; border-radius:999px; text-decoration:none;">Dataset / GitHub</a>
</div>

### PointNetPGAP-SLC: 3D LiDAR-Based Place Recognition for Mobile Robots in Horticulture

Another recent output is our work on **3D LiDAR-based place recognition for horticultural robots**, addressing the ambiguity caused by highly repetitive crop-row structures. This work develops a place-recognition approach tailored to horticultural environments and demonstrates improved retrieval performance, particularly in ambiguous segments where neighbouring rows can appear very similar.

<div style="margin: 1rem 0 1.25rem 0;">
  <a href="https://ieeexplore.ieee.org/abstract/document/10706020" target="_blank" style="display:inline-block; padding:0.35rem 0.7rem; margin-right:0.5rem; border:1px solid #2c7be5; border-radius:999px; text-decoration:none;">Paper</a>
  <a href="https://github.com/Cybonic/PointNetPGAP-SLC" target="_blank" style="display:inline-block; padding:0.35rem 0.7rem; margin-right:0.5rem; border:1px solid #6f42c1; border-radius:999px; text-decoration:none;">Code</a>
</div>

## SLAM and localisation in action

The videos below illustrate our recent localisation and mapping work in horticultural environments.

<div style="display: flex; flex-wrap: wrap; gap: 1rem; margin: 1.5rem 0;">
  <div style="flex: 1 1 360px; min-width: 300px;">
    <video controls playsinline style="width: 100%; border-radius: 6px;">
      <source src="{{ base_path }}/images/projects/area-h/hortimulti_slam_demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 0.9em; color: #666; margin-top: 0.5rem;">
      Example of multi-sensor localisation and mapping in a commercial polytunnel.
    </p>
  </div>

  <div style="flex: 1 1 360px; min-width: 300px;">
    <video controls playsinline style="width: 100%; border-radius: 6px;">
      <source src="{{ base_path }}/images/projects/area-h/place_recognition_demo.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="font-size: 0.9em; color: #666; margin-top: 0.5rem;">
      Example illustrating horticultural place recognition / localisation behaviour.
    </p>
  </div>
</div>

## Outlook

Through AREA-H, we are building the perception, localisation and mapping capabilities needed for dependable autonomy in horticultural environments. These capabilities are important for future robotic systems that must navigate safely and robustly while supporting real agricultural tasks such as inspection, treatment and crop management in commercial polytunnels.

