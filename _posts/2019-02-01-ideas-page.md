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

## Ship it to everyone

Another vision of umikry is that everyone can use it in their project.
While Python can be used for rapid development and testing of algorithms, we see umikry strongly in web-, app- and desktop-applications, which are mostly written in JavaScript, Java, C++, C#, Swift, etc. 
Currently we are trying to reimplement all algorithms in C++ and then create an interface to the individual
language (e.g. Java via JNI or Python via pybind11), since many languages allow C++ modules. However we need
here not just assistance in the C++ implementation, but perhaps also in the overall architecture,
because there may just smarter ways to reach our goal.