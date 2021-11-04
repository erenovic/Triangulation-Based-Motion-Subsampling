# Triangulation-Based-Motion-Subsampling
An unofficial encoder implementation of "A Triangulation-Based Backward Adaptive Motion Field Subsampling Scheme"

- [X] Encoder implementation
- [ ] Decoder implementation

A backward adaptive motion subsampling scheme to reduce the number of motion vectors to be coded. 

For further specifications of the scheme, please refer to the paper:
```
@INPROCEEDINGS{9287064,
  author={Brand, Fabian and Seiler, Jürgen and Alshina, Elena and Kaup, André},
  booktitle={2020 IEEE 22nd International Workshop on Multimedia Signal Processing (MMSP)}, 
  title={A Triangulation-Based Backward Adaptive Motion Field Subsampling Scheme}, 
  year={2020},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/MMSP48831.2020.9287064}}
```

For the motion estimation, [Spynet (2017)](https://github.com/anuragranj/spynet) model is utilized:
```
@inproceedings{spynet2017,
    author = {Ranjan, Anurag and Black, Michael J.},
    title = {Optical Flow Estimation using a Spatial Pyramid Network},
    booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
    year = {2017}}
```
