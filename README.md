> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# Human occupancy recognition with multivariate ambient sensors
With advancement in sensors and Internet of Things, gathering spatiotemporal information from one's surroundings has become easier, to an extent that we can start to use sensor data to infer indoor occupancy patterns. This paper aims to identify which ambient sensor is the most dominant in recognising human presence. Four different types of off-the-shelf sensors from two manufacturers were deployed to ensure that we could collect the following data reliably: illumination, temperature, humidity, levels of carbon dioxide, pressure and sound from within one staff office. Motion, power consumption, door opening and closing data and annotations from a self-developed mobile app were also collected as ground truth. We present our methods to preprocess the data and compute the number of people in the room with different classifiers, and identify sensors with strong and weak correlations. We explain our methodology for integrating large amounts of sensor data, discuss our experiments and findings in relation to the binary occupancy of a single person office, providing a baseline for recognising human occupancy.

This repository contains resources developed within the following paper:

	Ang, I.B.A., Salim, F.D. and Hamilton, M., 2016, March. Human occupancy recognition with multivariate ambient sensors. 
	In IEEE International Conference on Pervasive Computing and Communication Workshops (PerCom Workshops), 2016 (pp. 1-6). IEEE.

You can find the [paper](https://github.com/cruiseresearchgroup/Human-occupancy-recognition-with-multivariate-ambient-sensors/blob/master/paper/ariefang2016human.pdf) in this repository. 

Alternative link: http://ieeexplore.ieee.org/document/7457116/

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:

- `code/`: Code implementation and evaluation.  
- `data/`: Preprocessed dataset used for this paper. 
- `paper/`: Formal description of the algorithm and evaluation result. 
- `presentation/`: PDF of paper presentation. 

## Possible Applications

## Citation
If you use the resources presented in this repository, please cite (using the following BibTeX entry):
```
@INPROCEEDINGS{ariefang2016human, 
author={I. B. A. Ang and F. Dilys Salim and M. Hamilton}, 
booktitle={2016 IEEE International Conference on Pervasive Computing and Communication Workshops (PerCom Workshops)}, 
title={Human occupancy recognition with multivariate ambient sensors}, 
year={2016}, 
pages={1-6}, 
keywords={Internet of Things;chemical sensors;humidity sensors;mobile computing;pattern classification;sensor fusion;spatiotemporal phenomena;temperature sensors;Internet of Things;door opening and closing data;human occupancy recognition;humidity sensors;illumination sensors;indoor occupancy patterns;mobile app;motion data;multivariate ambient sensors;off-the-shelf sensors;power consumption;pressure sensors;sound sensors;spatiotemporal information;temperature sensors;Buildings;Feature extraction;Humidity;Lighting;Power demand;Temperature sensors}, 
doi={10.1109/PERCOMW.2016.7457116}, 
ISSN={}, 
month={March},}
```
