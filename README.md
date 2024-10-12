# ResearchTools

## 搭建和使用overleaf服务器
[搭建和使用overleaf服务器](https://www.tnnidm.com/build-and-use-overleaf-server/index.html)

## latex 让表格宽度与文本宽度相同
1. 原表格过宽（宽于页面）：用resizebox；
```
	\resizebox{1\linewidth}{!}{
  }
```

2. 原表格过窄（窄于页面）：不建议以上做法，原因是自动调整的结果会使得表格里的字体过大，非常不美观。对于此种情形，用tabular*，参考以下做法：
使用 tabular*， \hzise 或 \textwidth， 然后加上一些奇怪的符号。
```
		\begin{tabular}{lccc} 
```
修改为
```
		\begin{tabular*}{\hsize}{@{}@{\extracolsep{\fill}}lccc@{}} 
```

## PDF
- [在线PDF文件大小压缩](https://cdkm.com/cn/compress-pdf)


## Video
- [在线Video文件大小压缩](https://www.freeconvert.com/video-compressor)

## 表格制作
- [在线表格调试](https://www.latex-tables.com/)
- [在线表格调试2](https://www.tablesgenerator.com/)

## 图片表格转word表格
1】电子表格识别得到excel
- [电子表格识别][https://www.latex-tables.com/](https://web.baimiaoapp.com/image-to-excel)
2】Excel转Word常用方法分享
  Excel转Word常用方法分享 方法一：打开Excel表格，选择需要转到Word文档中的部分，然后“Ctrl+C”复制；
## 个性化签名
- [个性化签名](https://www.signwell.com/online-signature/)

## 电子签名
- [电子签名](https://www.diyiziti.com/qianming)

## 二维码生成工具
- [代码二维码生成](https://tool.oschina.net/qr/)

## ocr
- [图片转文字](https://www.onlineocr.net/zh_hans/)
## Video edit
- [Autocut](https://github.com/mli/autocut)

## 机器学习打标签工具
- [labelme](https://github.com/wkentaro/labelme)

## 大小写转换
- [大小写转换](https://titlecaseconverter.com/)

## 图片转Gif
- [图片转Gif](https://gif.imageonline.co/cn/)
  
## Youtube下载
- [savefrom.net](https://zh.savefrom.net/226/)
- [savieo](https://savieo.com/)
- [yout](https://yout.com/)
- [youtubemy](https://www.youtubemy.com/)
- []()

## 顶会会议
- [AI Conference Deadlines](https://aideadlin.es/?sub=ML,CV,RO,SP)
- [NeurIPS](https://proceedings.neurips.cc/)
   - 2023: https://proceedings.neurips.cc/paper_files/paper/2023
   - 2022: https://proceedings.neurips.cc/paper_files/paper/2022
   - 2021: https://proceedings.neurips.cc/paper_files/paper/2021
   - 2020: https://proceedings.neurips.cc/paper_files/paper/2020
   - 2019: https://proceedings.neurips.cc/paper_files/paper/2019
   - 2018: https://proceedings.neurips.cc/paper_files/paper/2018

- ICML
  - ICML2024:https://openreview.net/group?id=ICML.cc/2024/Conference#tab-accept-oral
  - ICML2023:
     - https://proceedings.mlr.press/v202/
     - https://openreview.net/group?id=ICML.cc/2023/Conference#tab-accept-poster
  - ICML2022:http://proceedings.mlr.press/v162/
  - ICML2021:http://proceedings.mlr.press/v139/
  - ICML2020:http://proceedings.mlr.press/v119/
  - ICML2019:http://proceedings.mlr.press/v97/
  - ICML2018:http://proceedings.mlr.press/v80/

- ICLR
  - 2024:https://openreview.net/group?id=ICLR.cc/2024/Conference
  - 2023:https://openreview.net/group?id=ICLR.cc/2023/Conference
  - 2022:https://openreview.net/group?id=ICLR.cc/2022/Conference
  - 2021:https://openreview.net/group?id=ICLR.cc/2021/Conference
  - 2020:https://openreview.net/group?id=ICLR.cc/2020/Conference
  - 2019:https://openreview.net/group?id=ICLR.cc/2019/Conference
  - 2018:https://openreview.net/group?id=ICLR.cc/2018/Conference

- [AAAI](https://aaai.org/Library/conferences-library.php)
   - 2024:https://ojs.aaai.org/index.php/AAAI/issue/view/576
   - 2023:https://ojs.aaai.org/index.php/AAAI/issue/archive
   - 2022:https://aaai.org/proceeding/aaai-36-2022/
   - 2021:https://aaai.org/proceeding/aaai-35-2021/
   - 2020:https://aaai.org/proceeding/aaai-34-2020/
   - 2019:https://aaai.org/proceeding/aaai-33-2019/
   - 2018:https://aaai.org/proceeding/aaai-32-2018/
  
- IJCAI
  - 2024:
  - 2023:https://www.ijcai.org/proceedings/2023/
  - 2022:https://www.ijcai.org/Proceedings/2022/
  - 2021:https://www.ijcai.org/Proceedings/2021/
  - 2020:https://www.ijcai.org/Proceedings/2020/
  - 2019:https://www.ijcai.org/Proceedings/2019/
  - 2018:https://www.ijcai.org/Proceedings/2018/
  

- CVPR
  - 2024:https://openaccess.thecvf.com/CVPR2024?day=all
  - 2023:https://openaccess.thecvf.com/CVPR2023?day=all
  - 2022:https://openaccess.thecvf.com/CVPR2022
  - 2021:https://openaccess.thecvf.com/CVPR2021
  - 2020:https://openaccess.thecvf.com/CVPR2020
  - 2019:https://openaccess.thecvf.com/CVPR2019
  - 2018:https://openaccess.thecvf.com/CVPR2018

- ECCV

- ICCV

  
- ICASSP
  全部ICASSP：https://ieeexplore.ieee.org/xpl/conhome/1000002/all-proceedings
  - ICASSP2024：https://ieeexplore.ieee.org/xpl/conhome/10445798/proceeding
  - ICASSP2023：https://ieeexplore.ieee.org/xpl/conhome/10094559/proceeding
  - ICASSP2022：https://ieeexplore.ieee.org/xpl/conhome/9745891/proceeding
  - ICASSP2021：https://ieeexplore.ieee.org/xpl/conhome/9413349/proceeding
  - ICASSP2020：https://ieeexplore.ieee.org/xpl/conhome/9040208/proceeding
  - ICASSP2019：https://ieeexplore.ieee.org/xpl/conhome/8671773/proceeding
  - ICASSP2018：https://ieeexplore.ieee.org/xpl/conhome/8450881/proceeding



[AirSim学习资料](https://github.com/Microsoft/AirSim/blob/main/docs/reinforcement_learning.md)
[1](https://github.com/microsoft/PromptCraft-Robotics)
[2](https://www.youtube.com/watch?v=iE5tZ6_ZYE8)
