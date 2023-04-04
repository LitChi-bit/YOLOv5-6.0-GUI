## YOLOv5-GUI
---
# <center>🎈YOLOv5算法(ver.6)的Qt-GUI实现<br></center>
## <center>🎈Qt-GUI implementation of the YOLOv5 algorithm (ver.6). </center>

---
>*☢ 注：是在已有基础上进行的改进，旨在增加兼容性。如有问题请 Pull requests。<br>&nbsp;&nbsp;&nbsp;&nbsp;权重文件暂时不公开，需使用官方提供的权重或自己训练的权重！！！<br>☢ Note: It is an improvement on the existing one and is intended to increase compatibility. <br>&nbsp;&nbsp;&nbsp;&nbsp;The weight file is temporarily not public, and you need to use the weights provided by the official or the weights you train!!!*<br>

✦ 基于YOLOv5的v5版本和v6版本及 ***Javacr*** 大佬的UI逻辑进行编写。<br>

✦ 提供深色和浅色两个UI。(深色版本显示不理想，最近没有时间去完善，想用也可以用，但是不建议用)<br>
&nbsp;&nbsp;&nbsp;&nbsp;Provides dark and light UI.<br>

![image](https://github.com/LitChi-bit/YOLOv5-6.0-GUI/blob/main/demo.png) 


## Installation and use
<p>0.Fetching projects from git</p>

```bash
git clone https://github.com/sakkios/YOLOv5-6.0-GUI.git
```

<p>1.Installation environment</p>

```bash
pip install -r requirements.txt
```

<p>2.Launching applications</p>

```bash
python run.py
```

## Attention

<p>GUI默认为浅色模式，你也可以通过下述方法将程序界面调整为深色模式。<br>
The GUI defaults to light mode, and you can also adjust the program interface to dark mode by using the above methods.</p>

```bash
#open python file: run.py

import main_ui_light

##Modify the code to -->

import main_ui_dark
```

### 下载预训练权重<br>Pretrained Checkpoints

| Model                                                                                           | size<br><sup>(pixels) | mAP<sup>val<br>50-95 | mAP<sup>val<br>50 | Speed<br><sup>CPU b1<br>(ms) | Speed<br><sup>V100 b1<br>(ms) | Speed<br><sup>V100 b32<br>(ms) | params<br><sup>(M) | FLOPs<br><sup>@640 (B) |
| ----------------------------------------------------------------------------------------------- | --------------------- | -------------------- | ----------------- | ---------------------------- | ----------------------------- | ------------------------------ | ------------------ | ---------------------- |
| [YOLOv5n](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5n.pt)              | 640                   | 28.0                 | 45.7              | **45**                       | **6.3**                       | **0.6**                        | **1.9**            | **4.5**                |
| [YOLOv5s](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5s.pt)              | 640                   | 37.4                 | 56.8              | 98                           | 6.4                           | 0.9                            | 7.2                | 16.5                   |
| [YOLOv5m](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5m.pt)              | 640                   | 45.4                 | 64.1              | 224                          | 8.2                           | 1.7                            | 21.2               | 49.0                   |
| [YOLOv5l](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5l.pt)              | 640                   | 49.0                 | 67.3              | 430                          | 10.1                          | 2.7                            | 46.5               | 109.1                  |
| [YOLOv5x](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5x.pt)              | 640                   | 50.7                 | 68.9              | 766                          | 12.1                          | 4.8                            | 86.7               | 205.7                  |
|                                                                                                 |                       |                      |                   |                              |                               |                                |                    |                        |
| [YOLOv5n6](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5n6.pt)            | 1280                  | 36.0                 | 54.4              | 153                          | 8.1                           | 2.1                            | 3.2                | 4.6                    |
| [YOLOv5s6](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5s6.pt)            | 1280                  | 44.8                 | 63.7              | 385                          | 8.2                           | 3.6                            | 12.6               | 16.8                   |
| [YOLOv5m6](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5m6.pt)            | 1280                  | 51.3                 | 69.3              | 887                          | 11.1                          | 6.8                            | 35.7               | 50.0                   |
| [YOLOv5l6](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5l6.pt)            | 1280                  | 53.7                 | 71.3              | 1784                         | 15.8                          | 10.5                           | 76.8               | 111.4                  |
| [YOLOv5x6](https://github.com/ultralytics/yolov5/releases/download/v7.0/yolov5x6.pt)<br>+ [TTA] | 1280<br>1536          | 55.0<br>**55.8**     | 72.7<br>**72.7**  | 3136<br>-                    | 26.2<br>-                     | 19.4<br>-                      | 140.7<br>-         | 209.8<br>-             |





## Reference<br>

<p><a href="https://github.com/ultralytics/yolov5">ultralytics/yolov5</a><br>
<a href="https://github.com/Javacr/PyQt5-YOLOv5">Javacr/PyQt5-YOLOv5</a></p>
