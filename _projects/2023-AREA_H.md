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

## Research focus

Within AREA-H, our research at Loughborough is focused on **robot localisation and mapping for horticultural field robots operating in polytunnel environments**. These environments are particularly challenging for autonomy because they combine long repetitive crop rows, strong perceptual aliasing, dynamic foliage, seasonal appearance variation, reflections from plastic tunnel covers, and often unreliable GNSS. Our aim is to develop robust perception and SLAM solutions that enable dependable navigation and mapping for agricultural robots in real commercial settings. :contentReference[oaicite:0]{index=0}

More broadly, the work brings together **multi-sensor perception, 3D LiDAR-based place recognition, localisation, mapping, and cross-season robustness** for horticultural robotics. We are interested not only in building accurate maps, but also in understanding how current methods fail in horticultural environments and how they can be improved for deployment in practice. This includes both **dataset and benchmarking work** and **algorithm development for localisation and place recognition**. :contentReference[oaicite:1]{index=1}

## Platforms and sensing

Our recent work has used field robotic platforms equipped with **3D LiDAR, RGB cameras, IMU, GNSS and wheel odometry**, with the specific sensor setup varying across experiments. In the recent HortiMulti work, the sensor suite includes **two 3D LiDARs, four RGB cameras, an IMU, GNSS and wheel odometry**. The associated dataset was collected in commercial strawberry and raspberry polytunnels across an entire growing season to capture realistic operational challenges for SLAM and localisation. :contentReference[oaicite:2]{index=2}

Our related horticultural localisation research has also used **Clearpath mobile robot platforms** in orchard, greenhouse and polytunnel environments. The HORTO-3DLM project page describes sequences collected on **Clearpath Husky** and **Clearpath Jackal** robots with 3D LiDAR and GNSS/localisation systems, including strawberry polytunnel data recorded in the UK. :contentReference[oaicite:3]{index=3}

## What we are doing in AREA-H

Some of the main strands of our current work include:

- **Localisation and mapping in GNSS-challenged polytunnels**, where standard outdoor navigation assumptions do not hold. :contentReference[oaicite:4]{index=4}
- **Cross-season and appearance-robust perception**, so that robots can continue to localise despite crop growth, foliage changes and environmental variation. :contentReference[oaicite:5]{index=5}
- **3D LiDAR-based place recognition and segment-level consistency methods** for reliable localisation in horticultural environments. :contentReference[oaicite:6]{index=6}
- **Benchmarking and dataset release**, providing representative real-world resources for developing and evaluating robotics algorithms in protected horticulture. :contentReference[oaicite:7]{index=7}

## Recent outputs

### HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels

We recently released **HortiMulti**, a multi-sensor, cross-season dataset for localisation and mapping in commercial strawberry and raspberry polytunnels. The dataset provides time-synchronised raw measurements, calibration files, reference trajectories, and baseline benchmarks for **visual, LiDAR and multi-sensor SLAM**. The paper highlights that current state-of-the-art methods remain inadequate for reliable deployment in these environments, underlining the need for horticulture-specific localisation and mapping solutions. :contentReference[oaicite:8]{index=8}

- **Paper:** [HortiMulti: A Multi-Sensor Dataset for Localisation and Mapping in Horticultural Polytunnels](https://arxiv.org/abs/2603.20150)
- **Project / dataset page:** [HortiMulti GitHub repository](https://github.com/shuoyuanxu/HortiMulti)

### PointNetPGAP-SLC: A 3D LiDAR-Based Place Recognition Approach With Segment-Level Consistency Training for Mobile Robots in Horticulture

Another recent output is our work on **3D LiDAR-based place recognition for mobile robots in horticulture**, published in *IEEE Robotics and Automation Letters*. This work addresses place recognition in horticultural environments using a segment-level consistency training strategy, reflecting our broader interest in robust long-term localisation under structured yet highly repetitive agricultural conditions. The HORTO-3DLM repository lists the paper as: **“PointNetPGAP-SLC: A 3D LiDAR-Based Place Recognition Approach With Segment-Level Consistency Training for Mobile Robots in Horticulture”**, *IEEE Robotics and Automation Letters*, 2024. :contentReference[oaicite:9]{index=9}

- **Paper:** [IEEE Xplore entry](https://ieeexplore.ieee.org/abstract/document/10706020)

## Media

The HortiMulti repository also includes example images and videos that illustrate the sensing setup, trajectories and SLAM-related data collection in horticultural polytunnels. These would work well on this page to show the research in action and to make the project more visually engaging. :contentReference[oaicite:10]{index=10}

