# EATSeg
EATSeg is a tool designed to help clinicians and researchers quickly and efficiently carry out epicardia adipose tissue (EAT) related researches.

## Download

Visit the [release page](https://github.com/MountainAndMorning/EATSeg/releases) to download an appropriate version.

## Installration

In Windows, you should install EATSeg by right click the **EATSegSetup.exe** installer and choose **Run as administrator**. 

## Useage

Read the [EATSeg Manual](https://github.com/MountainAndMorning/EATSeg/blob/main/EATSeg%20Manual.pdf) for the useage of EATSeg. For more help, you can connect the developer by e-mail (18207481578@163.com).

## Citation

Please cite the software by this paper:

@article{li2021automatic,
  title={Automatic quantification of epicardial adipose tissue volume},
  author={Li, Xiaogang and Sun, Yu and Xu, Lisheng and Greenwald, Stephen E and Zhang, Libo and Zhang, Rongrong and You, Hongrui and Yang, Benqiang},
  journal={Medical Physics},
  volume={48},
  number={8},
  pages={4279--4290},
  year={2021},
  publisher={Wiley Online Library}
}

# v2.0
## Improved
- Rewrite the whole software by javascript
- The stability is improved
- The name is changed to Slice.

# v0.3
## Improved
- Retrain pericardium segmentation deep learning model on  a larger dataset.
- Reduce the memory consumption when segmenting the pericardium.
- Change the database location to the app data folder. For Windows this folder is `~/AppData/Local/EATSeg`. For MacOS this folder is `~/Library/Application Support/EATSeg`.

## Fixed
- The export function can not work normally. Fixed.




