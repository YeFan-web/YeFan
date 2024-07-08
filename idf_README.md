细粒度猫狗识别
====
环境
-----
```
numpy==1.24.4
opencv_python==4.10.0.84
Pillow==10.4.0
torch==2.2.0
torchvision==0.17.0
```
推理单张图片
-------
在inference_one_pic.py中把cls_img_path,idf_img_path_1,idf_img_path_2改成对应图片路径
```python
pyhon inference_one_pic.py
```
批量推理图片
-------
1.在prepare_cls_img.py中把需要分类的文件夹路径输入root_dir
```python
python prepare_cls_img.py
```
2.在prepare_identification_img.py中把需要识别的图片的文件夹路径分别输入root_dir1,root_dir2 
```python
python prepare_identification_img.py
```
2.执行inference.py
```python
python inference.py
```
使用交互界面推理图片
-------
```python
python interface.py
```
