# ResearchTools

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

## 个性化签名
- [个性化签名](https://www.signwell.com/online-signature/)

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

## 顶会会议
- [NeurIPS](https://proceedings.neurips.cc/)

- ICML
  - ICML2022:http://proceedings.mlr.press/v162/
  - ICML2021:http://proceedings.mlr.press/v139/
  - ICML2020:http://proceedings.mlr.press/v119/
  - ICML2019:http://proceedings.mlr.press/v97/
  - ICML2018:http://proceedings.mlr.press/v80/


- [AAAI](https://aaai.org/Library/conferences-library.php)

- CVPR
  - 2022:https://openaccess.thecvf.com/CVPR2022
  - 2021:https://openaccess.thecvf.com/CVPR2021
  - 2020:https://openaccess.thecvf.com/CVPR2020
  - 2019:https://openaccess.thecvf.com/CVPR2019
  - 2018:https://openaccess.thecvf.com/CVPR2018


- IJCAI
  - 2022:https://www.ijcai.org/Proceedings/2022/
  - 2021:https://www.ijcai.org/Proceedings/2021/
  - 2020:https://www.ijcai.org/Proceedings/2020/
  - 2019:https://www.ijcai.org/Proceedings/2019/
  - 2018:https://www.ijcai.org/Proceedings/2018/
  
- ICLR
  - 2022:https://openreview.net/group?id=ICLR.cc/2022/Conference
  - 2021:https://openreview.net/group?id=ICLR.cc/2021/Conference
  - 2020:https://openreview.net/group?id=ICLR.cc/2020/Conference
  - 2019:https://openreview.net/group?id=ICLR.cc/2019/Conference
  - 2018:https://openreview.net/group?id=ICLR.cc/2018/Conference
