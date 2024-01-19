# YZXJ-说明书
柚子相机说明书

什么是柚子相机?https://docs.qq.com/aio/DT3lZTUtlRExMRXJD?p=UsNljinkd84IugBZv5jON6&client_hint=0

柚子相机是一款转为数有而设计的带NPU加速的相机，具备1.3寸IPS高清屏，通过虚拟U盘快速部署NN模型，可以作为广大中小学学习人工智能的教具，也可作为人工智能学习入⻔的一款教学工具，是落实众多国家人工智能教育政策、商中《人工智能总初步》、初中《人工智能与智慧社会》的有效抓手与载体。

柚子相机是面向人工智能、物联网创新的科创教育开源项目，由YuzuMaix掌控相机项目组联合发起，致力于为全国中小学生提供一系列人工智能教育、科创教育方案。

柚子相机基于当前人工智能教育、创客教育生态，选择了矽速科技有限公司的开源硬件Maix-II（V831）和“虚谷计划”的掌控板（ESP32）作为开发路线。

柚子相机把人工智能、物联网和创客教育相结合，依靠Maix-II人工智能生态和掌控板创客教育生态，是面向人工智能的创客教育新工具。

技术路线

基于当前人工智能教育、创客教育生态，选择了矽速科技有限公司的开源硬件Maix-II(V831)和“虚谷计划”的掌握板（ESP32）作为技术开发路线。Maix-II是一块精致小巧的 AI + IOT + 音视频处理 开发板， 支持常规 Linux 开发的同时， 有特有的 AI 硬件加速 特性，配合 Sipeed 提供的易用的软件生态，快速让你的边缘 AI 应用落地。Maix-II 已经集成了大量开箱即用的功能，比如 AI 图像和物体识别，AI 语音识别，AI 人脸识别，AI 车牌识别，小车巡线， 传统OpenCV支持，常用硬件外设库等等，这些资源经过教育优化，均可以应用在人工智能教育中。掌控板由创客教育专家委员会“虚谷计划”推出， 是一款教学用开源硬件，为普及创客教育而生，在巴掌大的板子上集成了ESP32主控芯片及各种传感器和执行器，实践中经过验证是非常受欢迎教育工具。

柚子相机结合两者优势，把人工智能、物联网和创客教育相结合，依靠Maix-II人工智能生态和掌控板创客教育生态，是面向人工智能的创客教育新工具。

底板
https://m.hlcode.cn/?id=NEeNKWy

底板（背面
https://m.hlcode.cn/?id=NEeNKWi

上板
https://m.hlcode.cn/?id=NEeNKWS

上板（背面
https://m.hlcode.cn/?id=NEeNKWv


具体参数
https://m.hlcode.cn/?id=NEeNKHA


编程软件

柚子软件支持下列软件

1.mind+下载：https://mindplus.cc/

2.mpythonX下载：https://www.labplus.cn/equip-mPython

3.米思齐：https://mixly.org/


maix-ll请使用python编程

1.maixpy下载：https://pypi.org/project/maixpy3/#hisytory
（柚子相机默认已经安装）

面 向 学 生

1.学习开源硬件 (ESP32)编程、物联网，学习过程与控制，培养创新精神。 

2.学习人工智能(柚子爱)应用，学习人工智能基本知识和技能。掌握数据  采集、模型训练、部署模型、应用模型等人工智能基本理论和实践。具有人  工智能意识和使用人工智能工具的技能。

3.依靠柚子爱的生态，拓展人工智能学习，制作更有趣的作品。

面 向 教 师

1.不断更新人工智能、创客教育等先进的理念、观念，具备教育家的潜力。 

2.学习人工智能、物联网技术相关知识和技能，提升信息科技专业素养。  

3.学习人工智能、创客教育项目，指导更有技术含量的学生作品。

4.使用更低廉的价格，更简单的组织，更高水平的技术，更高质量的课程开 展创新教育。

面 向 行 业

1.提升企业推动教育市场的理念

2.基于柚子相机研发更合适的教育产品(柚子相机+企业套装),提升市场份额。 

3.和柚子相机推动青少年创新教育。

4.提升企业知名度，品牌影响力。

快 速 问 答https://docs.qq.com/aio/DT3lZTUtlRExMRXJD?p=JtALn6P230zft6huPsiYSq&client_hint=0

1、 选择柚子相机还是柚子爱?
柚子相机是柚子爱和ESP32的合体，柚子爱作为NPU相机完成人工智能 模型识别，借助ESP32掌控板生态读取柚子爱的识别结果，然后进行 逻辑控制。
柚子相机更符合中小学低门槛入门。
柚子爱更适合开发者、爱好者，灵活性更强，但同时门槛相对更高， 需要具备一定的Linux  和Python   方面的编程知识。

柚子相机：柚子爱+ESP掌控板生态https://m.hlcode.cn/?id=NEeflha

2、 柚子爱与OpenMV有什么区别?
可以这样理解：
OpenMV是个摄像头，是在MCU单片机上实现的超级阉割版OpenCV, 跑在同样被阉割micropython  上，必须依靠IDE进行代码开发。
柚子爱是个带NPU 的相机，内置100W像素摄像头，配有IPS 显示器， 带有32G存储卡，0.2T的NN加速算力跑在OpenWRT 上，通过虚拟U盘即 可进行NN模型部署，内置标准版OpenCV和Python3..8.5。


3、 柚子相机能否运行M2Dock 软件
柚子相机底层版跟柚子爱是同款芯片， M2Dock也是V831芯片，柚子爱镜像 基于M2Dock的镜像做了教学资源整理，并把镜像转换为Win32DiskImager  或balenaEtcher  可烧录的通用镜像。

# 生态来源

深圳矽速、常州思泰姆、上海智位（DF）、深圳盛思

掌控相机开源地址：https://oshwhub.com/armbian-pythoniot/yuzumaix-Hand-Cam；

掌控相机底板柚子爱开源地址：https://oshwhub.com/armbian-pythoniot/yuzumaix-v831；

柚子爱项目借鉴YuzukiIRC开源红外相机：https://oshwhub.com/GloomyGhost/yuzuki-infrared-camera；

软件、外设兼容Sipeed矽速MaixPy3：https://wiki.sipeed.com/soft/maixpy3/zh/index.html

掌控相机在匹配调试过程还得到上海智位（DF）Mind+团队、N+小方舟团队和深圳盛思技术团队支持，一并表示感谢！

项目清单https://docs.qq.com/aio/DT3lZTUtlRExMRXJD?p=E262atbxLUbLtoxaFpp3m7&client_hint=0

线上购买https://docs.qq.com/aio/DT3lZTUtlRExMRXJD?p=cb6iqr72hlqKHB2Y63bKiV&client_hint=0

常州思泰姆教育科技有限公司https://m.hlcode.cn/?id=NEeflho

授权生产：常州思泰姆教育科技有限公司

地   址：常州科教城天润科技大厦

电   话：0519-81188090

网  址：www.ardubits.com

(由柚子爱开源教育项目官方授权)
