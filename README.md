# 3DSMCOS: 3D Model-Based Synthetic Data Pipeline for Camouflaged Object Segmentation
3DSMCOS is a research project and codebase for generating high-quality synthetic training data and annotations to improve military camouflaged object detection and segmentation. This repository accompanies the paper "3DSMCOS: A 3D Model-Based Synthetic Data Pipeline for Military Camouflaged Object Segmentation with Distractor-Augmented Realism." The project aims to tackle the challenges of detecting well-camouflaged military targets by creating synthetic images with pixel-level labels and automating the labeling of real data. By addressing data scarcity, class imbalance, and the need for precise masks, 3DSMCOS helps vision models better spot camouflaged personnel and equipment in cluttered scenes.

# Military-Camouflaged-Object-Segmentation-Dataset
- Download the military camouflage dataset with pixel-level segmentation labels at: [MHCD-Seg](https://drive.google.com/file/d/1NK8nxM626adBSGXAaUstaQpnGTIltQae)

- Here is the augmented dataset, which also includes segmentation labels, generated using BlenderProc: [BlenderProc-Segment-Dataset](https://drive.google.com/file/d/1LLLMFZNZB44neZr9mrV15wlncBDe7vay)

## <a name="CitingMHCDSeg"></a>Citing MHCD-Seg
If you find our dataset helpful for your research, please consider citing the following BibTeX entry.
```BibTeX
@misc{truong2025_3dsmcos,
  title     = {3DSMCOS: A 3D Model-Based Synthetic Data Pipeline for Military Camouflaged Object Segmentation with Distractor-Augmented Realism},
  author    = {Thi-Thu-Hang Truong and Trung-Kien Tran and Ngoc-Bach Hoang and Trong-Dat Nguyen and Thi-Hai-Hong Phan and Chi-Thanh Nguyen},
  note      = {To appear in the 2025 International Conference on Multimedia Analysis and Pattern Recognition (MAPR)},
  year      = {2025},
  month     = {August}
}
```

## Acknowledgement

Many thanks to these excellent opensource projects 
* [MHCD2022](https://github.com/liumaozhen-lmz/Military-Camouflage-MHCD2022)
* [BlenderProc](https://github.com/DLR-RM/BlenderProc)
