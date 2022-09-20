# 复旦视觉应用算法库学习手册
> **※TIPS※**
> 写在开头：为了方式公式乱码的问题，请使用chrome浏览器并安装MathJax Plugin for Github插件。直接在chrome浏览器中进入以下网页并点击安装即可。
> 
> [网页链接](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima?utm_source=chrome-app-launcher-info-dialog)

## 学习手册目录

### [序章](./0-introductory.md)
* 人工智能与CV
* 用于CV实践的算法库系统

### [一、算法库入门](./1-fudanvia.md)
* 算法库内容结构
* 模型组件清单
* 算法库数据管理
* 模型组件开发规范

### [二、表格结构识别](./2-table-structure-recognition.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * 自顶向下的方法
  * 自底向上的方法
  * 序列生成的方法
* 相关数据集
* 论文介绍
  * WTW
  * LGPMA
  * TableStruct-Net
  * TGRNet
  * TableMaster

### [三、多目标追踪](./3-multiple-object-track.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * 算法框架
  * 多目标追踪模型简介
* 论文介绍
  * SORT和Deep SORT
  * Byte Track
  * JDE
  * FairMOT
  * CenterTrack
  * SiamMOT
* 任务实践

### [四、文本检测](./4-text-detection.md)
* 基础知识
  * 背景
  * 任务定义
  * 评价指标
  * 任务难点
* 相关内容
  * 数据集
  * 通用目标检测
* 主流算法介绍
  * 检测框回归方法
  * 语义分割方法
  * 组件链接方法
  * 轮廓点检测方法

### [五、文本识别](./5-text-recognition.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * 算法框架
  * 无分割文本识别方法模型简介
  * 字母表
* 论文介绍
  * CRNN
  * ASTER
  * SAR
* 常用数据集
  * 中文文本识别Benchmark数据集
* 任务实践
  * 算法库模型组件介绍
  * 模型组件接口调用
  * 任务范例
  * 常见问题Q&A

### [六、关键信息提取](./6-KIE.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * Graph-based
  * End-to-End
  * Grid-based
  * Token-based
* 常用数据集
  * FUNSD
  * SROIE
  * EPHOIE
* 论文介绍
  * FormNet
  * ViBERTgrid
  * MatchVIE
  * TCPN
  * EPHOIE

### [七、行人重识别](./7-person-re-identification.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 损失函数
  * 常见挑战
  * 常用方法
* 行人重识别常用数据集
  * Market1501
  * CUHK03
  * DukeMTMC-REID
  * Mars
* 论文介绍
  * MGN
  * CTL
  * BiCnet
  * TransReid
  * PFD

### [八、2D人体姿态估计](./8-pose-estimation-2d.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * 算法框架
  * 2D多人姿态估计方法模型简介
* 论文介绍
  * HRNet
  * HigherHRNet
  * CenterNet
  * DCpose
* 常用数据集
* 任务实践
  * 模型组件介绍
  * 模型组件接口调用
  * 任务范例
  * 常见问题Q&A

### [九、步态识别](./9-gait-recognition.md)
* 基础知识
  * 任务定义
  * 评价指标
  * 任务难点
  * 应用场景
* 方法论
  * 身体表示
  * 时间表示
  * 特征表示
  * 基于卷积神经网络
  * 基于循环神经网络
  * 基于图卷积网络
* 论文介绍
  * Gaitset
  * GaitGraph
  * GaitPart
  * GaitGL
  * CSTL
* 数据集

### [十、深度学习系统开发](./10-system-develop.md)
* 应用服务系统
* 系统开发相关组件
* 建立系统架构
* 深度学习中的并发
* 网络服务部署
* 开发规范
* 应用开发实战

