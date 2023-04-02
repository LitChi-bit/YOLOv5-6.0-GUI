## YOLOv5-GUI
---
# <center>🎈YOLOv5算法(ver.6)的Qt-GUI实现<br></center>
## <center>🎈Qt-GUI implementation of the YOLOv5 algorithm (ver.6). </center>

---
>*☢ 注：是在已有基础上进行的改进，旨在增加兼容性。如有问题请 Pull requests。<br>&nbsp;&nbsp;&nbsp;&nbsp;权重文件暂时不公开，需使用官方提供的权重或自己训练的权重！！！<br>☢ Note: It is an improvement on the existing one and is intended to increase compatibility. <br>&nbsp;&nbsp;&nbsp;&nbsp;The weight file is temporarily not public, and you need to use the weights provided by the official or the weights you train!!!*<br>

✦ 基于YOLOv5的v5版本和v6版本及 ***Javacr*** 大佬的UI逻辑进行编写。<br>

✦ 提供深色和浅色两个UI。(深色版本显示不理想，最近没有时间去完善，想用也可以用，但是不建议用)<br>
&nbsp;&nbsp;&nbsp;&nbsp;Provides dark and light UI.<br>

![image](https://github.com/sakkios/YOLOv5-6.0-GUI/blob/main/demo.png) 


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

## Reference<br>

<p><a href="https://github.com/ultralytics/yolov5">ultralytics/yolov5</a><br>
<a href="https://github.com/Javacr/PyQt5-YOLOv5">Javacr/PyQt5-YOLOv5</a></p>
