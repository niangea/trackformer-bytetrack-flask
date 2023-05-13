# TrackFormer-bytetarck-flask

所需参数已经默认设置完毕
默认的帧路径位于snakeborad目录下
默认打开bytetrack
直接运行track即可，不需输入参数

2023/5/13
----------------------------------------
（1）增加了mask_track.py以及mask_byte_track.py，可以在MOTS数据集上对两个方法进行图像切割
（2）正在进行gui.py,基于flask的可视化

----------------------------------------
主要问题
（1）使用MOTS数据集进行可视化的时候需要修改nun_class为1




```
@InProceedings{meinhardt2021trackformer,
    title={TrackFormer: Multi-Object Tracking with Transformers},
    author={Tim Meinhardt and Alexander Kirillov and Laura Leal-Taixe and Christoph Feichtenhofer},
    year={2022},
    month = {June},
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
}
```
