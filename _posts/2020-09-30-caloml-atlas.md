---
layout: post
title: "Research Project: Calorimeter Particle Reconstruction for High-Energy Nuclear Collisions"
---

### Improving High-Energy Particle Detectors with Machine Learning

Microseconds after the big bang, the universe existed in a state called the quark-gluon plasma (QGP). To experimentally study its properties, the QGP is recreated in high-energy nuclear collisions at the LHC, and the particles produced from the QGP are reconstructed from their energy deposition in the ATLAS calorimeter. This requires both classifying the particles and calibrating their deposited energy. The objective of this project is to improve the reconstruction by using machine learning techniques, where the energy depositions of clusters of cells, formed by ATLAS topo-clustering methods, are treated as three-dimensional images when inputted to neural networks. This approach significantly improves the calibration of deposited energies when cross-validating while training, and models trained on idealized data predict the calibrated energies of particles in more complex data sets well. Additionally, implementation of a data generator using uproot allows the program to load input data into memory as needed while training or predicting, significantly reducing the amount of memory used. The data generator also allows for use of multi-processing to speed up training and evaluating. This work illustrates that using machine learning methods for both classification and calibration has the potential to significantly improve particle reconstruction.

I worked on this research project at Lawrence Livermore National Laboratory (LLNL) under Aaron Angerami from June 2020 to August 2020. At the end of my internship, I presented the results of my research at the Summer SLAM! ([abstract](/research/SULI_SLAM_Abstract_w_IM.pdf) and [presentation](/research/SULI_SLAM_presentation_w_IM.pdf)). I also wrote a [research report](/research/SULI_Report_w_IM.pdf) to culminate my internship.
