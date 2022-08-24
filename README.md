# FL-Datasets-for-HAR

This repo includes four new real-world human activity recognition (HAR) datasets collected under federated learning settings, which first appear at the MobiSys 2021 paper: <a href="https://dl.acm.org/doi/10.1145/3458864.3467681"> ClusterFL: A Similarity-Aware Federated Learning System for Human Activity Recognition </a>.

The first dataset is a large-scale dataset collected using an Android App in a crowdsourcing manner. The other three are collected in indoor environments.


# Download

  The four datasets are publicly available in the current repository. Each dataset is accompanied by a Python file "data_pre.py" for preprocessing and loading each node's data separately in federated learning. The data and processing file are compressed to a ".zip" file for each dataset. Please click the following links for more detail descriptions and downloading each dataset.
  
  
### [HARBox Dataset: Daily Activities Recognition using Smartphones](https://github.com/xmouyang/FL-Datasets-for-HAR/tree/main/datasets/HARBox)


### [UWB Dataset: Human Movement Detection using Ultra Wide Band Modules](https://github.com/xmouyang/FL-Datasets-for-HAR/tree/main/datasets/UWB)


### [IMU Dataset: Walking Activity Recognition using Inertial Measurement Unit Modules](https://github.com/xmouyang/FL-Datasets-for-HAR/tree/main/datasets/IMU)


### [Depth Dataset: Gesture Recognition using Depth Camera](https://github.com/xmouyang/FL-Datasets-for-HAR/tree/main/datasets/Depth)



# Citation
The datasets of this project are made available for non-commercial, academic research only. If you would like to use the datasets of this project, please cite the following papers:
```
@inproceedings{ouyang2021clusterfl,
  title={ClusterFL: a similarity-aware federated learning system for human activity recognition},
  author={Ouyang, Xiaomin and Xie, Zhiyuan and Zhou, Jiayu and Huang, Jianwei and Xing, Guoliang},
  booktitle={Proceedings of the 19th Annual International Conference on Mobile Systems, Applications, and Services},
  pages={54--66},
  year={2021}
}
```
```
@article{ouyang2022clusterfl,
  title={ClusterFL: a clustering-based federated learning system for human activity recognition}},
  author={Ouyang, Xiaomin and Xie, Zhiyuan and Zhou, Jiayu and Xing, Guoliang and Huang, Jianwei},
  journal={ACM Transactions on Sensor Networks (TOSN)},
  year={2022}
}
```
