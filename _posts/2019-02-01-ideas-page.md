---
title: Ideas Page
layout: page
permalink: /ideas/
---

The general idea of umikry is the pseudomization of people in private photos and videos.
For this it is necessary that known persons, e.g. family members, remain unchanged, 
but faces of other people are replaced by generated faces, while the 
aesthetics of photo/video is unchanged.

## Algorithm Benchmark Suite

The goal of umikry described above can be divided into different steps:

- face detection
- recognition of (familiar) faces
- face generation
- replacement

These individual steps are to a large extent to be implemented by a multitude of algorithms.
However, while HAAR- or LBP-Features can cause problems, for example when detecting 
faces in profile, they beat many CNN-based methods when it comes to time-critical
applications. This simple example shows: There are several ways to solve the individual tasks, 
but also the mixture of the different solution parts can be decide on the later quality of the overall result.

The goal is to setup a benchmark suite for different modular algorithms and also to figure out and describe different quality metrics