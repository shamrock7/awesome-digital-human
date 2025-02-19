# 数字人 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
<!-- # <p align=center>`awesome digital human`</p> -->
<!-- [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
![visitors](https://visitor-badge.glitch.me/badge?style=flat-square&page_id=weihaox/awesome-clothed-human)  -->

> 关于人体着装的精选资源集合：全身重建、头部重建、数字人相关项目等。 

## 贡献

欢迎提供反馈与贡献！如果你认为某些内容有遗漏或者有任何建议（论文、实现方案及其他资源），请在 [PR](https://github.com/shamrock7/awesome-digital-human/pulls)上提PR 。你可以手动编辑项目内容，或者使用脚本按照下面提供的 Markdown 格式生成内容。

```Markdown
**这里是论文名称。**<br>
*[作者1](homepage), 作者2, 作者3。*<br>
会议或期刊发表年份。 [[PDF](link)] [[项目](link)] [[代码](link)] [[数据](link)]
```

<details><summary>目录</summary><p>
	
- [行业 Demo 或产品](#industry-demo-or-product)
- [3D 人体虚拟形象生成与动画制作](#3d-human-avatar-generation-and-animation)
- [（基于 2D 图像集合的）3D 可动画头部虚拟形象](#3d-head-animatable-avatar--from-2d-image-collections-)
- [(着装) 人体运动生成](#-clothed--human-motion-generation)
- [人体着装数字化](#clothed-human-digitalization)
- [布料建模、布料悬垂模拟、布料仿真以及穿衣](#cloth-modelling--draping--simulation--and-dressing)
- [人体图像与视频生成](#human-image-and-video-generation)
- [基于图像的虚拟试穿](#image-based-virtual-try-on)
- [人体重塑](#human-body-reshaping)
- [服装设计](#garment-design)
- [时尚风格影响因素](#fashion-style-influences)
- [团队与人员](#team-and-people)
- [数据集](#dataset)
- [应用](#applications)

</p></details><p></p>

## 行业 Demo 或产品 <a name='industry-demo-or-product'></a>

Highavenue: 将自己变成一个 3D 模型。


## 3D/4D 人体动画生成与制作 <a name='3d-human-avatar-generation-and-animation'></a>

**DressRecon：基于单目视频的自由形态 4D 人体重建**<br>
*Jeff Tan, Donglai Xiang, Shubham Tulsiani, Deva Ramanan, Gengshan Yang.*<br>
arxiv 2024.  [[PDF](https://arxiv.org/abs/2409.20563)] [[项目](https://jefftan969.github.io/dressrecon/)] [[代码](https://github.com/jefftan969/dressrecon)]

**Disco4D：基于单张图像的解耦 4D 人体生成与动画**<br>
*Hui En Pang, Shuai Liu, Zhongang Cai, Lei Yang, Tianwei Zhang, Ziwei Liu.*<br>
arxiv 2024.  [[PDF](https://arxiv.org/abs/2409.17280)] [[项目](https://disco-4d.github.io/)]

**RodinHD：利用扩散模型实现高保真 3D 虚拟形象生成**<br>
*Bowen Zhang, Yiji Cheng, Chunyu Wang, Ting Zhang, Jiaolong Yang, Yansong Tang, Feng Zhao, Dong Chen, Baining Guo.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.06938)] [[项目](https://rodinhd.github.io)] [[代码]()]

**可动画高斯模型：学习基于姿态的高斯映射以实现高保真人体虚拟形象建模**<br>
*Zhe Li, Zerong Zheng, Lizhen Wang, Yebin Liu..*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.16096)] [[项目](https://animatable-gaussians.github.io)] [[代码](https://github.com/lizhe00/AnimatableGaussians)]

**HumanNorm：学习正态扩散模型以生成高质量逼真的 3D 人体**<br>
*Xin Huang, Ruizhi Shao, Qi Zhang, Hongwen Zhang, Ying Feng, Yebin Liu, Qing Wang..*<br> 
CVPR 2024. [[PDF]()] [[项目](https://humannorm.github.io/)]

**RAM - 虚拟化身：通过单目视频实现具备全身控制的实时逼真虚拟化身**<br>
*Xiang Deng, Zerong Zheng, Yuxiang Zhang, Jingxiang Sun, Chao Xu, XiaoDong Yang, Lizhen Wang, Yebin Liu.*<br> 
CVPR 2024. [[PDF](https://cloud.tsinghua.edu.cn/f/6b7a88c3b4ac43b0b506/?dl=1)] [[项目](https://github.com/Xiang-Deng00/RAM-Avatar/)] [[代码](https://github.com/Xiang-Deng00/RAM-Avatar)]

**TexVocab：基于纹理词汇条件的人体虚拟化身**<br>
*Yuxiao Liu, Zhe Li, Yebin Liu, Haoqian Wang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.00524)] [[项目](https://texvocab.github.io/)]

**HumanGaussian：基于高斯溅射的文本驱动 3D 人体生成**<br>
*Xian Liu, Xiaohang Zhan, Jiaxiang Tang, Ying Shan, Gang Zeng, Dahua Lin, Xihui Liu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17061)] [[项目](https://alvinliu0.github.io/projects/HumanGaussian)]

**DreamAvatar：基于扩散模型的文本与形状引导的 3D 人体虚拟形象生成**<br>
*[Yukang Cao](https://yukangcao.github.io/), [Yan-Pei Cao](https://yanpei.me/), [Kai Han](https://www.kaihan.org/), [Ying Shan](https://scholar.google.com/citations?user=4oXBp9UAAAAJ&hl=zh-CN), [Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong/).*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2304.00916)] [[项目](https://yukangcao.github.io/DreamAvatar/)] [[代码](https://yukangcao.github.io/DreamAvatar/)]

**SCULPT：基于形状条件的非成对学习，用于生成依赖姿态的着装及带纹理人体网格**<br>
*Soubhik Sanyal, Partha Ghosh, Jinlong Yang, Michael J. Black, Justus Thies, Timo Bolkart.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2308.10638)] [[项目](https://huangyangyi.github.io/tech/)]

**3DGS - 虚拟化身：通过可变形 3D 高斯溅射实现可动画虚拟化身**<br>
*Zhiyin Qian, Shaofei Wang, Marko Mihajlovic, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.09228)] [[项目](https://neuralbodies.github.io/3DGS-Avatar/)]

**基于解耦潜在扩散的情感语音驱动 3D 人体动画**<br>
*Kiran Chhatre, Radek Daněček, Nikos Athanasiou, Giorgio Becherini, Christopher Peters, Michael J. Black, Timo Bolkart.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.04466)]

**GauHuman：基于单目人体视频的关节式高斯溅射技术**<br>
*Shoukang Hu, Ziwei Liu.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02973v1)] [[项目](https://skhu101.github.io/GauHuman/)] [[代码](https://github.com/skhu101/GauHuman)]

**FlashAvatar：以 300 FPS 实现高保真数字虚拟化身渲染**<br>
*Jun Xiang, Xuan Gao, Yudong Guo, Juyong Zhang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02214v1)] [[项目](https://ustc3dv.github.io/FlashAvatar/)]

**PEGASUS：具备可组合属性的个性化生成式 3D 虚拟化身**<br>
*[Hyunsoo Cha](https://research.hyunsoocha.com/), [Byungjun Kim](https://bjkim95.github.io/), [Hanbyul Joo](https://jhugestar.github.io/).*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2402.10636)] [[项目](https://snuvclab.github.io/pegasus/)] [[代码](https://github.com/snuvclab/pegasus)]

**TADA：从文本到可动数字虚拟化身**<br>
*[Tingting Liao](https://github.com/TingtingLiao), [Hongwei Yi](https://xyyhw.top/), [Yuliang Xiu](http://xiuyuliang.cn/), [Jiaxiang Tang](https://me.kiui.moe/), [Yangyi Huang](https://github.com/huangyangyi/), [Justus Thies](https://justusthies.github.io/), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
3DV 2024. [[PDF](https://arxiv.org)] [[项目](https://tada.is.tue.mpg.de/)] [[代码](https://github.com/TingtingLiao/TADA)]

**基于分层表面体的高效 3D 关节式人体生成**<br>
*Yinghao Xu, Wang Yifan, Alexander W. Bergman, Menglei Chai, Bolei Zhou, Gordon Wetzstein.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2307.05462)] [[项目](https://www.computationalimaging.org/publications/lsv/)]

**TECA：文本引导的组合式 3D 虚拟形象生成与编辑**<br>
*[Hao Zhang](https://haozhang990127.github.io/), [Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Peter Kulits](https://kulits.github.io/), [Yandong Wen](https://is.mpg.de/person/ydwen), [Justus Thies](https://justusthies.github.io/), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2309.07125)] [[项目](https://yfeng95.github.io/teca/)]

**FLARE：可动画与可重光照网格虚拟化身的快速学习**<br>
*Shrisha Bharadwaj, Yufeng Zheng, Otmar Hilliges, Michael J. Black, Victoria Fernandez-Abrevaya.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2310.17519)]

**基于一致纹理参数化的单次成像隐式可变形人脸**<br>
*Connor Z. Lin, Koki Nagano, Jan Kautz, Eric R. Chan, Umar Iqbal, Leonidas Guibas, Gordon Wetzstein, Sameh Khamis.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.03043)] [[项目](https://research.nvidia.com/labs/toronto-ai/ssif/)] [[代码]()]

**DELIFFAS：用于快速虚拟化身合成的可变形光场**<br>
*Youngjoong Kwon, Lingjie Liu, Henry Fuchs, Marc Habermann, Christian Theobalt.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2310.11449)]

**PrimDiffusion：用于 3D 人体生成的体素基元扩散**<br>
*Zhaoxi Chen, Fangzhou Hong, Haiyi Mei, Guangcong Wang, Lei Yang, Ziwei Liu.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2312.04559)] [[项目](https://frozenburning.github.io/projects/primdiffusion/)] [[代码](https://github.com/FrozenBurning/PrimDiffusion)]

**XAGen：3D 具表现力的人体虚拟形象生成**<br>
*Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Jiashi Feng, Mike Zheng Shou.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2311.13574)] [[项目](https://showlab.github.io/xagen/)] [[代码](https://github.com/magic-research/xagen)]

**DreamHuman：基于文本的可动 3D 虚拟化身**<br>
*[Nikos Kolotouros](https://www.nikoskolot.com/), [Thiemo Alldieck](https://research.google/people/107250/), [Andrei Zanfir](https://scholar.google.com/citations?user=8lmzWycAAAAJ&hl=en&oi=ao), [Eduard Gabriel Bazavan](https://research.google/people/107659/), [Mihai Fieraru](https://mihaifieraru.github.io/), [Cristian Sminchisescu](https://research.google/people/CristianSminchisescu/).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.09329)] [[项目](https://dream-human.github.io/)] [[头像图库](https://dream-human.github.io/avatar_gallery.html)]

**DINAR：用于一次性生成人体虚拟化身的神经纹理扩散修复技术
**<br>
*David Svitov, Dmitrii Gudkov, Renat Bashirov, Victor Lempitsky.*<br> 
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.09375)] [[代码](https://github.com/SamsungLabs/DINAR)]

**AvatarCraft：通过参数化形状与姿态控制将文本转化为神经人体虚拟形象**<br>
*[Ruixiang Jiang](https://j-rx.com/), [Can Wang](https://cassiepython.github.io/), [Jingbo Zhang](https://eckertzhang.github.io/), [Menglei Chai](https://mlchai.com/), [Mingming He](https://mingminghe.com/), [Dongdong Chen](https://www.dongdongchen.bid/), [Jing Liao](https://liaojing.github.io/html/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17606)] [[项目](https://avatar-craft.github.io/)] [[代码](https://github.com/songrise/avatarcraft)] [[数据](https://drive.google.com/drive/folders/1m97mmoAtDes0mBwkS4q2VNBivXSmRkOK)]

**StyleAvatar3D：利用图像 - 文本扩散模型实现高保真 3D 虚拟化身生成**<br>
*Chi Zhang, Yiwen Chen, Yijun Fu, Zhenglin Zhou, Gang YU, Billzb Wang, Bin Fu, Tao Chen, Guosheng Lin, Chunhua Shen.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.19012)] [[项目](https://x-zhangyang.github.io/2023_Get3DHuman/)] [[代码](https://github.com/icoz69/StyleAvatar3D)]

**Get3DHuman：运用像素对齐重建先验将 StyleGAN - Human 提升为 3D 生成模型**<br>
*Zhangyang Xiong, Di Kang, Derong Jin, Weikai Chen, Linchao Bao, Xiaoguang Han.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[代码](https://github.com/X-zhangyang/Get3DHuman/)]

**GETAvatar：用于可动画人体虚拟形象的生成式带纹理网格**<br>
*Xuanmeng Zhang, Jianfeng Zhang, Rohan Chacko, Hongyi Xu, Guoxian Song, Yi Yang, Jiashi Feng.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2310.02714)] [[项目](https://getavatar.github.io/)]

**AG3D：从二维图像集合中学习生成三维虚拟化身**<br>
*[Zijian Dong](https://ait.ethz.ch/people/zijian/), [Xu Chen](https://ait.ethz.ch/people/xu/), [Jinlong Yang](https://is.mpg.de/~jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges), [Andreas Geiger](http://www.cvlibs.net/).*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2305.02312)] [[项目](https://zj-dong.github.io/AG3D/)] [[代码](https://github.com/zj-dong/AG3D)]

**学习局部可编辑的虚拟人**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io/), [Lixin Xue](https://lxxue.github.io/), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2023. [[PDF](https://files.ait.ethz.ch/projects/custom-humans/paper.pdf)] [[项目](https://custom-humans.github.io/)] [[代码](https://github.com/custom-humans/editable-humans)]

**人物神经辐射场（PersonNeRF）：基于照片集的个性化重建**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi/), Pratul P. Srinivasan, Brian Curless, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.01162)] [[项目](https://grail.cs.washington.edu/projects/personnerf/)] [[代码]()]

**用于形状引导的 3D 形状与纹理生成的潜隐神经辐射场（Latent-NeRF）**<br>
*Gal Metzer, Elad Richardson, Or Patashnik, Raja Giryes, Daniel Cohen-Or.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2211.07600)]  [[代码](https://github.com/eladrich/latent-nerf)]

**EVA3D：从二维图像集合生成组合式 3D 人体模型**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), [Zhaoxi Chen](https://frozenburning.github.io/), [Yushi Lan](https://github.com/NIRVANALAN), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ&hl=zh-CN), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2210.04888)] [[项目](https://hongfz16.github.io/projects/EVA3D.html)] [[代码]()]

**CLIP-Actor：用于人体网格动画的文本驱动推荐与风格化**<br>
*Kim Youwang, Kim Ji-Yeon, Tae-Hyun Oh.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.03550)] [[项目](https://clip-actor.github.io/)] [[代码](https://github.com/postech-ami/CLIP-Actor)]

**AvatarCLIP：零样本下文本驱动的 3D 虚拟化身生成与动画制作**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), Mingyuan Zhang, Liang Pan, Zhongang Cai, Lei Yang, Ziwei Liu.*<br>
SIGGRAPH (TOG) 2022. [[PDF](https://arxiv.org/abs/2205.08535)] [[项目](https://hongfz16.github.io/projects/AvatarCLIP.html)] [[代码](https://github.com/hongfz16/AvatarCLIP)] 

**WildAvatar：用于 3D 虚拟化身创建的网络规模野外视频数据集**<br>
*Zihao Huang, ShouKang Hu, Guangcong Wang, Tianqi Liu, Yuhang Zang, Zhiguo Cao, Wei Li, Ziwei Liu.*<br> 
arXiv 2024. [[PDF](https://arxiv.org/abs/2407.02165)] [[项目](https://wildavatar.github.io/)]

**可驱动的 3D 高斯虚拟化身**<br>
*Wojciech Zielonka, Timur Bagautdinov, Shunsuke Saito, Michael Zollhöfer, Justus Thies, Javier Romero.*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2311.08581)] [[项目](https://zielon.github.io/d3ga/)]

**MagicAvatar：多模态虚拟化身生成与动画制作**<br>
*Jianfeng Zhang, Hanshu Yan, Zhongcong Xu, Jiashi Feng, Jun Hao Liew.*<br> 
arXiv 2023. [[PDF](http://arxiv.org/abs/2308.14748)] [[项目](https://magic-avatar.github.io/)] [[代码](https://github.com/magic-research/magic-avatar)]

**DELTA：利用混合 3D 表征学习解耦虚拟化身**<br>
*[Yao Feng](https://scholar.google.com/citations?user=wNQQhSIAAAAJ&hl=en&oi=ao), [Weiyang Liu](https://wyliu.com/), [Timo Bolkart](https://sites.google.com/site/bolkartt/), [Jinlong Yang](https://is.mpg.de/~jyang), [Marc Pollefeys](https://people.inf.ethz.ch/pomarc/), [Michael J. Black](https://ps.is.mpg.de/person/black).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2309.06441)] [[项目](https://yfeng95.github.io/delta/)] [[代码](https://github.com/yfeng95/DELTA)]

**AvatarBooth：高质量可定制的 3D 人体虚拟形象生成**<br>
*[Yifei Zeng](https://github.com/zeng-yifei), [Yuanxun Lu](https://github.com/YuanxunLu), [Xinya Ji](https://github.com/jixinya), [Yao Yao](https://yoyo000.github.io/), [Hao Zhu](http://zhuhao.cc/), [Xun Cao](https://cite.nju.edu.cn/People/Faculty/20190621/i5054.html).*<br> 
arXiv 2023. [[PDF](https://arxiv.org/abs/2306.09864)] [[项目](https://zeng-yifei.github.io/avatarbooth_page/)] [[代码](https://github.com/zeng-yifei/AvatarBooth)]

## （基于 2D 图像集合的）3D 可动画头部虚拟形象 <a name='3d-head-animatable-avatar--from-2d-image-collections-'></a>

**PAV：从非结构化视频集合中生成个性化头部虚拟形象**<br>
*Akin Caliskan, Berkay Kicanaoglu, Hyeongwoo Kim.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.21047)] [[项目](https://akincaliskan3d.github.io/PAV/)] 

**高斯头部虚拟化身：基于动态高斯模型的超高保真头部虚拟化身**<br>
*Yuelang Xu, Benwang Chen, Zhe Li, Hongwen Zhang, Lizhen Wang, Zerong Zheng, Yebin Liu.*<br>
CVPR 2024. [[PDF](https://arxiv.org/abs/2312.03029)] [[项目](https://yuelangx.github.io/gaussianheadavatar/)] 

**HeadArtist：基于自分数蒸馏的文本驱动 3D 头部生成**<br>
*Hongyu Liu, Xuan Wang, Ziyu Wan, Yujun Shen, Yibing Song, Jing Liao, Qifeng Chen.*<br> 
SIGGRAPH 2024. [[PDF](http://arxiv.org/abs/2312.07539)] [[项目](https://kumapowerliu.github.io/HeadArtist)]

**GAN-Avatar：基于生成对抗网络的可控个性化人类头部虚拟化身**<br>
*Berna Kabadayi, Wojciech Zielonka, Bharat Lal Bhatnagar, Gerard Pons-Moll, Justus Thies.*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2311.13655)] [[项目](https://ganavatar.github.io/)] 

**NeRFEditor：用于全 3D 场景编辑的可微风格分解**<br>
*[Chunyi Sun](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Yanbin Liu](https://chuny1.github.io/NeRFEditor/nerfeditor.html), [Junlin Han](https://junlinhan.github.io/), [Stephen Gould](https://chuny1.github.io/NeRFEditor/nerfeditor.html).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2212.03848)] [[项目](https://chuny1.github.io/NeRFEditor/nerfeditor.html)]

**AlbedoGAN：迈向逼真的生成式 3D 人脸模型**<br>
*[Aashish Rai](https://aashishrai3799.github.io/), [Hiresh Gupta](https://hireshgupta1997.github.io/), Ayush Pandey, Francisco Vicente Carrasco, Shingo Jason Takagi, Amaury Aubel, Daeil Kim, [Aayush Prakash](https://aayushp.github.io/), [Fernando de la Torre](https://www.cs.cmu.edu/~ftorre/).*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2304.12483)] [[项目](https://aashishrai3799.github.io/Towards-Realistic-Generative-3D-Face-Models/)] [[代码](https://lnkd.in/gVz8Hzn3)]

**AvatarStudio：文本驱动的 3D 动态人类头部虚拟化身编辑**<br>
*Mohit Mendiratta. Xingang Pan, Mohamed Elgharib, Kartik Teotia, Mallikarjun B R, Ayush Tewari, Vladislav Golyanik, Adam Kortylewski, Christian Theobalt.*<br> 
TOG 2024. [[PDF](http://arxiv.org/abs/2306.00547)] [[项目](https://vcai.mpi-inf.mpg.de/projects/AvatarStudio/)]

**HQ3DAvatar：高质量可控 3D 头部虚拟化身**<br>
*[Kartik Teotia](https://www.linkedin.com/in/kartik-teotia/?originalSubdomain=de), Mallikarjun B R, Xingang Pan, Hyeongwoo Kim, Pablo Garrido, Mohamed Elgharib, Christian Theobalt.*<br>
TOG 20234. [[PDF](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar/)] [[项目](https://vcai.mpi-inf.mpg.de/projects/HQ3DAvatar/)] [[代码]()]

**CLIPFace：基于文本引导的纹理 3D 可变形模型编辑**<br>
*[Shivangi Aneja](https://niessnerlab.org/members/shivangi_aneja/profile.html), [Justus Thies](https://is.mpg.de/~jthies), [Angela Dai](https://www.professoren.tum.de/en/dai-angela), [Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html).*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2212.01406)] [[项目](https://shivangi-aneja.github.io/projects/clipface/)] [[代码](https://github.com/shivangi-aneja/ClipFace)]

**DreamFace：文本引导下的可动画 3D 人脸渐进式生成**<br>
*Longwen Zhang, Qiwei Qiu, Hongyang Lin, Qixuan Zhang, Cheng Shi, Wei Yang, Ye Shi, Sibei Yang, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2304.03117)] [[项目](https://sites.google.com/view/dreamface)] [[Demo](https://hyperhuman.deemos.com/)] [[HuggingFace](https://huggingface.co/spaces/DEEMOSTECH/ChatAvatar)]

**StyleAvatar：从单个视频生成实时逼真的神经肖像虚拟化身**<br>
*Lizhen Wang, Xiaochen Zhao, Jingxiang Sun, Yuxiang Zhang, Hongwen Zhang, Tao Yu✝, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.00942)]

**LatentAvatar：学习用于表情丰富的神经头部虚拟化身的潜在表情代码**<br>
*Yuelang Xu, Hongwen Zhang, Lizhen Wang, Xiaochen Zhao, Han Huang, Guojun Qi, Yebin Liu.*<br>
SIGGRAPH 2023. [[PDF](https://arxiv.org/abs/2305.01190)], [[项目](https://www.liuyebin.com/latentavatar/)],[[代码](https://github.com/YuelangX/LatentAvatar)]

**NeRSemble：人头的多视图辐射场重建**<br>
*[Tobias Kirschstein](https://tobias-kirschstein.github.io/), [Shenhan Qian](https://shenhanqian.com/), [Simon Giebenhain](https://simongiebenhain.github.io/), Tim Walter, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.03027)] [[项目](https://tobias-kirschstein.github.io/nersemble/)] [[Video](https://youtu.be/a-OAWqBzldU)]

**GOHA：可泛化的一次性神经头部虚拟化身**<br>
*[Xueting Li](https://sunshineatnoon.github.io/), [Shalini De Mello](https://research.nvidia.com/person/shalini-de-mello), [Sifei Liu](https://www.sifeiliu.net/), [Koki Nagano](https://luminohope.org/), [Umar Iqbal](https://research.nvidia.com/person/umar-iqbal), [Jan Kautz](https://jankautz.com/).*<br> 
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2306.08768)] [[项目](https://research.nvidia.com/labs/lpr/one-shot-avatar)]

**GANHead：迈向生成式可动画神经头部虚拟化身**<br>
*[Sijing Wu](https://wsj-sjtu.github.io), [Yichao Yan](https://daodaofr.github.io/), Yunhao Li, Yuhao Cheng, Wenhan Zhu, Ke Gao, Xiaobo Li, [Guangtao Zhai](https://scholar.google.com/citations?user=E6zbSYgAAAAJ&hl=en&oi=ao).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03950)] [[项目](https://wsj-sjtu.github.io/GANHead/)]

**FitMe：深度逼真的 3D 可变形模型虚拟化身**<br>
*[Alexandros Lattas](https://alexlattas.com/), [Stylianos Moschoglou](https://moschoglou.com/), [Stylianos Ploumpis](https://www.ploumpis.com/), [Baris Gecer](https://barisgecer.github.io/), [Jiankang Deng](https://jiankangdeng.github.io/), [Stefanos Zafeiriou](https://www.imperial.ac.uk/people/s.zafeiriou).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.09641)] [[项目](https://alexlattas.com/fitme)]

**Next3D：用于 3D 感知头部虚拟化身的生成式神经纹理光栅化**<br>
*[Jingxiang Sun](https://mrtornado24.github.io/), [Xuan Wang](https://xuanwangvc.github.io/), [Lizhen Wang](https://lizhenwangt.github.io/), [Xiaoyu Li](https://xiaoyu258.github.io/), [Yong Zhang](https://yzhang2016.github.io/yongnorriszhang.github.io/), [Hongwen Zhang](https://hongwenzhang.github.io/), [Yebin Liu](http://www.liuyebin.com/).*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/pdf/2211.11208.pdf)] [[项目](https://mrtornado24.github.io/Next3D/)] [[代码](https://github.com/MrTornado24/Next3D)]

**BlendFields：少样本示例驱动的面部建模**<br>
*Kacper Kania, Stephan J. Garbin, Andrea Tagliasacchi, Virginia Estellers, Kwang Moo Yi, Julien Valentin, Tomasz Trzciński, Marek Kowalski.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2305.07514)] [[项目](https://blendfields.github.io/)]

**OTAvatar：具有可控三平面渲染的一次性说话人脸虚拟化身**<br>
*Zhiyuan Ma, Xiangyu Zhu, Guojun Qi, Zhen Lei, Lei Zhang.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2303.14662)] [[代码](https://github.com/theEricMa/OTAvatar)] [[Demo](https://youtu.be/qpIoMYFr7Aw)]

**PanoHead：360° 下几何感知的 3D 全头合成**<br>
*Sizhe An, Hongyi Xu, Yichun Shi, Guoxian Song, Umit Ogras, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.13071) [[项目](https://sizhean.github.io/panohead)]

**用于可动画人类虚拟化身的高效网格神经场**<br>
*Xiaoke Huang, Yiji Cheng, Yansong Tang, Xiu Li, Jie Zhou, Jiwen Lu .*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.12965)] [[项目](https://xk-huang.github.io/ema/)]

**Rodin：一种使用扩散塑造 3D 数字虚拟化身的生成模型**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[项目](https://3d-avatar-diffusion.microsoft.com/)]

**OmniAvatar：几何引导的可控 3D 头部合成**<br>
*Hongyi Xu, Guoxian Song, Zihang Jiang, Jianfeng Zhang, Yichun Shi, Jing Liu, Wanchun Ma, Jiashi Feng, Linjie Luo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.15539)]

**PointAvatar：从视频中生成基于可变形点的头部虚拟化身**<br>
*Yufeng Zheng, Wang Yifan, Gordon Wetzstein, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.08377)] [[项目](https://zhengyuf.github.io/PointAvatar/)] [[代码](https://github.com/zhengyuf/pointavatar)]

**MEGANE：可变形眼镜与虚拟化身网络**<br>
*Junxuan Li, Shunsuke Saito, Tomas Simon, Stephen Lombardi, Hongdong Li, Jason Saragih.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.04868)] [[项目](https://junxuan-li.github.io/megane/)] 

**从单目视频重建个性化语义面部神经辐射场模型**<br>
*Xuan Gao, ChengLai Zhong, Jun Xiang, Yang Hong, Yudong Guo, Juyong Zhang.*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2210.06108)] [[项目](https://ustc3dv.github.io/NeRFBlendShape/)] [[代码](https://github.com/USTC3DV/NeRFBlendShape-code)]

**H3D - Net：少样本高保真 3D 头部重建**<br>
*Eduard Ramon, Gil Triginer, Janna Escur, Albert Pumarola, Jaime Garcia, Xavier Giro-i-Nieto, Francesc Moreno-Noguer.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2107.12512)] [[项目](https://crisalixsa.github.io/h3d-net/)] [[H3DS Dataset](https://docs.google.com/forms/d/e/1FAIpQLScbs-m-Me85KeMqJ2WnCwvToeSRIHC8sJckhxX3eknQu8ItRQ/viewform)]

**AvatarMe++：基于逼真渲染感知生成对抗网络的面部形状和双向反射分布函数推断**<br>
*[Alexandros Lattas](https://www.imperial.ac.uk/people/a.lattas), [Stylianos Moschoglou](https://www.doc.ic.ac.uk/~sm3515/), [Stylianos Ploumpis](https://www.imperial.ac.uk/people/s.ploumpis), [Baris Gecer](http://barisgecer.github.io), [Abhijeet Ghosh](https://www.doc.ic.ac.uk/~ghosh/), [Stefanos Zafeiriou](https://wp.doc.ic.ac.uk/szafeiri/).*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2112.05957)]  [[代码](https://github.com/lattas/AvatarMe)]

**AvatarMe：“野外” 逼真可渲染的 3D 面部重建**<br>
*Alexandros Lattas, Stylianos Moschoglou, Baris Gecer, Stylianos Ploumpis, Vasileios Triantafyllou, Abhijeet Ghosh, Stefanos Zafeiriou.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.13845)]  [[代码](https://github.com/lattas/AvatarMe)]

## （着装）人体运动生成 <a name='-clothed--human-motion-generation'></a>

**ReLoo：从野外单目视频重建穿着宽松服装的人体**<br>
*Chen Guo, Tianjian Jiang, Manuel Kaufmann, Chengwei Zheng, Julien Valentin, Jie Song, Otmar Hilliges.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2409.15269)] [[项目](https://moygcc.github.io/ReLoo/)]

**TLControl：用于人体运动合成的轨迹与语言控制**<br>
*Weilin Wan, Zhiyang Dou, Taku Komura, Wenping Wang, Dinesh Jayaraman, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](http://arxiv.org/abs/2311.17135)] [[项目](https://tlcontrol.weilinwl.com/)]

**CoMo：通过语言引导的姿态代码编辑实现可控运动生成**<br>
*Yiming Huang, Weilin Wan, Yue Yang, Chris Callison-Burch, Mark Yatskar, Lingjie Liu.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2403.13900)] [[项目](https://yh2371.github.io/como/)]

**Total Selfie：生成全身自拍图像**<br>
*Bowei Chen, Brian Curless, Ira Kemelmacher-Shlizerman, Steve Seitz.*<br> 
CVPR 2024 (Highlight). [[PDF](http://arxiv.org/abs/2308.14740)] [[项目](https://homes.cs.washington.edu/~boweiche/project_page/totalselfie/)]

**OmniControl：在任何时间控制任何关节以生成人体运动**<br>
*Yiming Xie, Varun Jampani, Lei Zhong, Deqing Sun, Huaizu Jiang.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08580)] [[项目](https://neu-vi.github.io/omnicontrol/)]

**MotionDiffuse：使用扩散模型的文本驱动人体运动生成**<br>
*[Mingyuan Zhang](https://mingyuan-zhang.github.io/), [Zhongang Cai](https://caizhongang.github.io/), [Liang Pan](https://github.com/paul007pl), [Fangzhou Hong](https://hongfz16.github.io/), [Xinying Guo](https://gxyes.github.io/), [Lei Yang](https://yanglei.me/), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
TPAMI 2024. [[PDF](https://arxiv.org/abs/2208.15001)] [[项目](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] [[代码](https://github.com/mingyuan-zhang/MotionDiffuse)]

**TMR：使用对比 3D 人体运动合成的文本到运动检索**<br>
*Mathis Petrovich, Michael J. Black and Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.00976)] [[项目](https://mathis.petrovich.fr/tmr/index.html)] [[代码](https://github.com/Mathux/TMR)]

**SINC：用于同时动作生成的 3D 人体运动空间组合**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2304.10417)] [[项目](https://sinc.is.tue.mpg.de/)] [[代码](https://github.com/athn-nik/sinc)]

**HumanRF：用于运动中人体的高保真神经辐射场**<br>
*[Mustafa Işık](https://www.mustafaisik.net/), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[项目](http://www.synthesiaresearch.github.io/humanrf)] [[代码](https://github.com/synthesiaresearch/humanrf)] [[数据](http://www.actors-hq.com/)]

**GestureDiffuCLIP：结合 CLIP 潜在空间的手势扩散模型**<br>
*[Tenglong Ao](https://aubrey-ao.github.io/), Zeyi Zhang, [Libin Liu](https://libliu.info/).*<br>
SIGGRAPH 2023 (期刊论文板块). [[PDF](https://arxiv.org/abs/2303.14613)] [[项目](https://pku-mocca.github.io/GestureDiffuCLIP-Page/)] [[代码]()]

**MDM：人体运动扩散模型**<br>
*Guy Tevet, Sigal Raab, Brian Gordon, Yonatan Shafir, Daniel Cohen-Or, Amit H. Bermano.*<br>
ICLR 2023. [[PDF](https://arxiv.org/abs/2209.14916)] [[项目](https://guytevet.github.io/mdm-page/)] [[代码](https://github.com/GuyTevet/motion-diffusion-model)]

**MoFusion：一个基于去噪扩散的运动合成框架**<br>
*[Rishabh Dabral](https://www.cse.iitb.ac.in/~rdabral/), [Muhammad Hamza Mughal](https://m-hamza-mughal.github.io/), [Vladislav Golyanik](https://people.mpi-inf.mpg.de/~golyanik/), [Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.04495)] [[项目](https://vcai.mpi-inf.mpg.de/projects/MoFusion/)] 

**MotionCLIP：将人体运动生成引入 CLIP 空间**<br>
*Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-Or.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.08063)] [[项目](https://guytevet.github.io/motionclip-page/)] [[代码](https://github.com/GuyTevet/MotionCLIP)]

**TEMOS：从文本描述生成多样的人体运动**<br>
*[Mathis Petrovich](https://mathis.petrovich.fr/), Michael J. Black, Gül Varol.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.14109)] [[项目](https://mathis.petrovich.fr/temos/)] [[代码](https://github.com/Mathux/TEMOS)]

**TEACH：3D 人体的时间动作合成**<br>
*Nikos Athanasiou, Mathis Petrovich, Michael J. Black, Gül Varol.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.04066)] [[项目](https://teach.is.tue.mpg.de/)] [[代码](https://github.com/athn-nik/teach)]

## 人体着装数字化 <a name='clothed-human-digitalization'></a>

[Project Splinter](https://project-splinter.github.io/): Human Digitalization with Implicit Representation.

**PuzzleAvatar：从个人相册组装 3D 虚拟化身**<br>
*Yuliang Xiu, Yufei Ye, Zhen Liu, Dimitrios Tzionas, Michael J. Black.*<br>
SIGGRAPH Asia (TOG) 2024. [[PDF](https://arxiv.org/abs/2405.14869)]

**iHuman：从单目视频生成即时可动画数字人体**<br> 
*Pramish Paudel, Anubhav Khanal, Ajad Chhatkuli, Danda Pani Paudel, Jyoti Tandukar.*<br> 
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.11174)]

**HiLo：利用参数模型的高频和低频信息进行详细且稳健的 3D 着装人体重建**<br>
*Yifan Yang, Dong Liu, Shuhai Zhang, Zeshuai Deng, Zixiong Huang, Mingkui Tan.*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2404.04876)] [[Github](https://github.com/YifYang993/HiLo)]

**IntrinsicAvatar：通过显式光线追踪从单目视频对动态人体进行基于物理的逆渲染**<br>
*Shaofei Wang, Božidar Antić, Andreas Geiger, Siyu Tang.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.05210)] [[项目](https://neuralbodies.github.io/IntrinsicAvatar)]

**GaussianAvatar：通过可动画 3D 高斯从单个视频实现逼真的人体虚拟化身建模**<br>
*Liangxiao Hu, Hongwen Zhang, Yuxiang Zhang, Boyao Zhou, Boning Liu, Shengping Zhang, Liqiang Nie.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2312.02134)] [[项目](https://huliangxiao.github.io/GaussianAvatar)] [[Github](https://github.com/aipixel/GaussianAvatar)]

**SiTH：使用图像条件扩散的单视图纹理人体重建**<br>
*[Hsuan-I Ho](https://azuxmioy.github.io/), [Jie Song](https://ait.ethz.ch/people/song), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br> 
CVPR 2024. [[PDF](https://arxiv.org/abs/2311.15855)] [[项目](https://sith-diffusion.github.io/)]

**从单目图像恢复 3D 人体网格：一项综述**<br>
*[Yating Tian](https://github.com/tinatiansjz), [Hongwen Zhang](https://github.com/HongwenZhang), [Yebin Liu](https://www.liuyebin.com/), [Limin Wang](https://wanglimin.github.io/).*<br>
TPAMI 2023. [[PDF](https://arxiv.org/abs/2203.01923)] [[项目](https://github.com/tinatiansjz/hmr-survey)] [[数据集](https://github.com/tinatiansjz/hmr-survey#datasets)] [[Benchmarks](https://github.com/tinatiansjz/hmr-survey#benchmarks)]

**具有镜像感知的神经人体**<br>
*Daniel Ajisafe, James Tang, Shih-Yang Su, Bastian Wandt, Helge Rhodin.*<br> 
3DV 2024. [[PDF](https://arxiv.org/abs/2311.09221)] [[项目](https://danielajisafe.github.io/mirror-aware-neural-humans/)]

**TeCH：文本引导的逼真着装人体重建**<br>
*[Yangyi Huang](https://huangyangyi.github.io/), [Hongwei Yi](https://xyyhw.top/), [Yuliang Xiu](https://xiuyuliang.cn/), [Tingting Liao](https://github.com/tingtingliao), [Jiaxiang Tang](https://me.kiui.moe/), [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/), [Justus Thies](http://justusthies.github.io/).*<br>
3DV 2024. [[PDF](https://arxiv.org/abs/2308.08545)] [[项目](https://huangyangyi.github.io/TeCH/)]

**基于形状引导扩散的单图像 3D 人体数字化**<br>
*Badour AlBahar, Shunsuke Saito, Hung-Yu Tseng, Changil Kim, Johannes Kopf, Jia-Bin Huang.*<br>
SIGGRAPH Asia 2023. [[PDF](https://arxiv.org/abs/2208.15001)] [[项目](https://human-sgd.github.io/)]

**用于着装虚拟化身重建的全局相关 3D 解耦变换器**<br>
*Zechuan Zhang, Li Sun, Zongxin Yang, Ling Chen, Yi Yang.*<br>
NeurIPS 2023. [[PDF](https://arxiv.org/abs/2309.13524)]

**ISP：具有隐式缝纫图案的多层服装褶皱模拟**<br>
*Ren Li, Benoît Guillard, Pascal Fua.*<br> 
NeurIPS 2023. [[PDF](http://arxiv.org/abs/2305.14100)]

**NCHO：用于人体和物体的神经 3D 合成的无监督学习**<br>
*[Taeksoo Kim](https://taeksuu.github.io/), [Shunsuke Saito](https://shunsukesaito.github.io/), [Hanbyul Joo](https://jhugestar.github.io/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2305.14345)] [[项目](https://taeksuu.github.io/ncho/)]

**Chupa：使用 2D 扩散概率模型从蒙皮形状先验雕刻 3D 着装人体**<br>
*[Byungjun Kim](https://bjkim95.github.io/), Patrick Kwon, Kwangho Lee, Myunggi Lee, Sookwan Han, Daesik Kim, Hanbyul Joo.*<br>
ICCV 2023 (Oral). [[PDF](https://arxiv.org/abs/2305.11870)] [[项目](https://snuvclab.github.io/chupa)]

**SHERF：从单张图像生成可泛化的人体神经辐射场**<br>
*[Shoukang Hu](https://skhu101.github.io/), [Fangzhou Hong](https://hongfz16.github.io/), [Liang Pan](https://scholar.google.com/citations?user=lSDISOcAAAAJ), Haiyi Mei, [Lei Yang](https://scholar.google.com.hk/citations?user=jZH2IPYAAAAJ&hl=en), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.12791)] [[项目](https://skhu101.github.io/SHERF/)] [[代码](https://github.com/skhu101/SHERF)]

**SynBody：用于 3D 人体感知和建模的具有分层人体模型的合成数据集**<br>
*Zhitao Yang, Zhongang Cai, Haiyi Mei, Shuai Liu, Zhaoxi Chen, Weiye Xiao, Yukun Wei, Zhongfei Qing, Chen Wei, Bo Dai, Wayne Wu, Chen Qian, Dahua Lin, Ziwei Liu, Lei Yang.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2303.17368)] [[项目](https://maoxie.github.io/SynBody/)]

**用于 3D 人体网格重建的单目视频循环测试时自适应**<br>
*Hyeongjin Nam, Daniel Sungho Jung, Yeonguk Oh, Kyoung Mu Lee.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2308.06554)]

**HumanRF：用于运动中人体的高保真神经辐射场**<br>
*[Mustafa Işık](https://www.mustafaisik.net/), Martin Rünz, Markos Georgopoulos, Taras Khakhulin, Jonathan Starck, Lourdes Agapito, Matthias Nießner.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.06356)] [[项目](http://www.synthesiaresearch.github.io/humanrf)] [[代码](https://github.com/synthesiaresearch/humanrf)] [[数据](http://www.actors-hq.com/)]

**AvatarReX：实时表情丰富的全身虚拟化身**<br>
*Zerong Zheng, Xiaochen Zhao, Hongwen Zhang, Boning Liu, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2305.04789)] [[项目](https://liuyebin.com/AvatarRex/)]

**PoseVocab：学习用于人体虚拟化身建模的关节结构化姿态嵌入**<br>
*Zhe Li, Zerong Zheng, Yuxiao Liu, Boyao Zhou, Yebin Liu.*<br>
SIGGRAPH 2023 [[PDF](https://arxiv.org/abs/2304.13006)] [[项目](https://lizhe00.github.io/projects/posevocab)]

**从单张图像进行高保真着装虚拟化身重建**<br>
*Tingting Liao, Xiaomei Zhang, Yuliang Xiu, Hongwei Yi, Xudong Liu, Guo-Jun Qi, Yong Zhang, Xuan Wang, Xiangyu Zhu, Zhen Lei.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.03903)] [[代码](https://github.com/TingtingLiao/CAR)]

**SeSDF：用于隐式 3D 着装人体重建的自演化有符号距离场**<br>
*[Yukang Cao](https://yukangcao.github.io/), [Kai Han](https://www.kaihan.org/), [Kenneth Kwan-Yee K. Wong](https://i.cs.hku.hk/~kykwong/).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.00359)] [[项目](https://yukangcao.github.io/SeSDF/)] [[代码](https://yukangcao.github.io/)]

**用于重建可重光照和可动画虚拟化身的结构化 3D 特征**<br>
*Enric Corona, Mihai Zanfir, Thiemo Alldieck, Eduard Gabriel Bazavan, Andrei Zanfir, Cristian Sminchisescu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06820)] [[项目](https://enriccorona.github.io/s3f/)]

**从视频重建可动画类别**<br>
*[Gengshan Yang](https://gengshan-y.github.io/), [Chaoyang Wang](https://mightychaos.github.io/), [N Dinesh Reddy](https://dineshreddy91.github.io/), [Deva Ramanan](http://www.cs.cmu.edu/~deva/).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.06351)] [[项目](https://gengshan-y.github.io/rac-www/)] [[代码](https://github.com/gengshan-y/rac)]

**将体视频表示为动态多层感知器映射**<br>
*Sida Peng, Yunzhi Yan, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2304.06717.pdf)] [[项目](https://zju3dv.github.io/mlp_maps)] [[代码](https://github.com/zju3dv/mlp_maps)]

**在数分钟内学习动态人体的神经体表示**<br>
*[Chen Geng](https://chen-geng.com/), Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://chen-geng.com/files/instant_nvr.pdf)] [[项目](https://zju3dv.github.io/instant_nvr/)] [[代码](https://github.com/zju3dv/instant-nvr/)]

**CloSET：通过显式模板分解在连续表面上对着装人体进行建模**<br>
*[Hongwen Zhang](https://hongwenzhang.github.io/), [Siyou Lin](https://jsnln.github.io/), [Ruizhi Shao](https://dsaurus.github.io/saurus), [Yuxiang Zhang](https://zhangyux15.github.io/), [Zerong Zheng](https://zhengzerong.github.io/), [Han Huang](http://www.liuyebin.com/closet/#), [Yandong Guo](http://www.liuyebin.com/closet/#), [Yebin Liu](https://liuyebin.com/).*<br>
CVPR 2023. [[PDF](http://www.liuyebin.com/closet/assets/CloSET_CVPR2023.pdf)] [[项目](http://www.liuyebin.com/closet/)]

**MonoHuman：从单目视频生成可动画人体神经场**<br>
*Zhengming Yu, Wei Cheng, Xian Liu, Wayne Wu, Kwan-Yee Lin.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2304.02001)] [[项目](https://yzmblog.github.io/projects/MonoHuman/)]

**FlexNeRF：从稀疏视图对运动人体进行逼真的自由视点渲染**<br>
*Vinoj Jayasundara, Amit Agrawal, Nicolas Heron, Abhinav Shrivastava, Larry S. Davis.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.14368)]

**从单个 2K 分辨率图像进行高保真 3D 人体数字化**<br>
*Sang-Hun Han, Min-Gyu Park, Ju Hong Yoon, Ju-Mi Kang, Young-Jae Park, Hae-Gon Jeon.*<br>
CVPR 2023 (Highlight). [[PDF](https://arxiv.org/abs/2303.15108)] [[代码](https://github.com/SangHunHan92/2K2K)]

**在数分钟内学习动态人体的神经体表示**<br>
*Chen Geng, Sida Peng, Zhen Xu, Hujun Bao, Xiaowei Zhou.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.12237)] [[项目](https://zju3dv.github.io/instant_nvr/)] 

**Vid2Avatar：通过自监督场景分解从野外视频进行 3D 虚拟化身重建**<br>
*Chen Guo, Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2302.11566)] [[项目](https://moygcc.github.io/vid2avatar/)]

**Rodin：一种使用扩散塑造 3D 数字虚拟化身的生成模型**<br>
*Tengfei Wang, Bo Zhang, Ting Zhang, Shuyang Gu, Jianmin Bao, Tadas Baltrusaitis, Jingjing Shen, Dong Chen, Fang Wen, Qifeng Chen, Baining Guo.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.06135)] [[项目](https://3d-avatar-diffusion.microsoft.com/)]

**ECON：从法线获得显式着装人体**<br>
*Yuliang Xiu, Jinlong Yang, Xu Cao, Dimitrios Tzionas, Michael J. Black.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/)] [[项目](https://xiuyuliang.cn/econ)] [[代码](https://github.com/YuliangXiu/ECON)]

**X-Avatar：表情丰富的人类虚拟化身**<br>
*[Kaiyue Shen](https://skype-line.github.io/), Chen Guo, Manuel Kaufmann, Juan Jose Zarate, Julien Valentin, Jie Song, Otmar Hilliges.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2303.04805)] [[项目](https://skype-line.github.io/projects/X-Avatar/)] [[代码](https://github.com/Skype-line/X-Avatar)]

**InstantAvatar：在 60 秒内从单目视频学习虚拟化身**<br>
*Tianjian Jiang, Xu Chen, Jie Song, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2212.10550)] [[项目](https://tijiang13.github.io/InstantAvatar/)] [[代码](https://github.com/tijiang13/InstantAvatar)]

**学习可见性场以进行详细的 3D 人体重建和重光照**<br>
*Ruichen Zheng, Peng Li, Haoqian Wang, Tao Yu.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.11900)]

**HumanGen：使用显式先验生成人体辐射场**<br>
*Suyi Jiang, Haoran Jiang, Ziyu Wang, Haimin Luo, Wenzheng Chen, Lan Xu.*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.05321)]

**SHARP：对穿着宽松服装的人进行形状感知重建**<br>
*Sai Sagar Jinka, Rohan Chacko, Astitva Srivastava, Avinash Sharma, P.J. Narayanan.*<br>
IJCV 2023. [[PDF](https://arxiv.org/abs/2106.04778)]

**用于人体重建的几何感知双尺度 PIFu 表示**<br>
*Zheng Dong, Ke Xu, Ziheng Duan, Hujun Bao, Weiwei Xu, Rynson W.H. Lau.*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2112.02082)]

**TotalSelfScan：从面部、手部和身体的自拍照视频学习全身虚拟化身**<br>
*[Junting Dong](https://jtdong.com/), [Qi Fang](https://raypine.github.io/), Yudong Guo, Sida Peng, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
NeurIPS 2022. [[PDF](https://openreview.net/pdf?id=lgj33-O1Ely)] [[项目](https://zju3dv.github.io/TotalSelfScan/)] [[数据](http://jtdong.com/)]

**FOF：学习用于单目实时人体重建的傅里叶占有率场**<br>
*[Qiao Feng](https://fengq1a0.github.io/), [Yebin Liu](http://www.liuyebin.com/), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai/), [Jingyu Yang](http://seea.tju.edu.cn/info/1015/1608.htm), [Kun Li](http://cic.tju.edu.cn/faculty/likun/).*<br>
NeurIPS 2022. [[PDF](https://arxiv.org/abs/2206.02194)] [[项目](https://cic.tju.edu.cn/faculty/likun/projects/FOF/index.html)] [[代码](https://github.com/fengq1a0/FOF)]

**对穿着具有挑战性服装的人体进行基于神经点的形状建模**
Yihao Zhi, Shenhan Qian, Xinhao Yan, Shenghua Gao
3DV 2022. [[PDF](https://arxiv.org/abs/2208.14851)] [[代码](https://github.com/zyhbili/Dual-Space-NeRF)]

**对穿着具有挑战性服装的人体进行基于神经点的形状建模**<br>
*Qianli Ma, Jinlong Yang, Michael J. Black, Siyu Tang.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2209.06814)]

**HVTR：用于人体虚拟化身的混合体 - 纹理渲染**<br>
*Tao Hu, Tao Yu, Zerong Zheng, He Zhang, Yebin Liu, Matthias Zwicker.*<br>
3DV 2022. [[PDF](https://arxiv.org/abs/2112.10203)] [[项目](https://www.cs.umd.edu/~taohu/hvtr/)]

**通过神经动画网格进行人体性能建模与渲染**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io/), Yuheng Jiang, Kaixin Yao, Jiakai Zhang, Liao Wang, Haizhao Dai, Yuhui Zhong, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/abs/2209.08468)] [[项目](https://zhaofuq.github.io/NeuralAM/)]

**FloRen：通过使用稀疏 RGB 相机的外观流实现实时高质量人体性能渲染**<br>
*Ruizhi Shao, Liliang Chen, Zerong Zheng, Hongwen Zhang, Yuxiang Zhang, Han Huang, Yandong Guo, Yebin Liu.*<br>
SIGGRAPH Asia 2022. [[PDF](https://dl.acm.org/doi/abs/10.1145/3550469.3555409)] 

**用于单视图 RGB - D 人体重建的占有率平面**<br>
*Xiaoming Zhao, Yuan-Ting Hu, Zhongzheng Ren, Alexander G. Schwing.*<br>
AAAI 2023. [[PDF](https://arxiv.org/abs/2208.02817)] [[代码](https://github.com/Xiaoming-Zhao/oplanes)]

**HuMMan：用于通用传感与建模的多模态 4D 人体数据集**<br>
*[Zhongang Cai](https://caizhongang.github.io/), [Daxuan Ren](https://kimren227.github.io/), [Ailing Zeng](https://ailingzeng.site/), [Zhengyu Lin](https://www.linkedin.com/in/zhengyu-lin-a908aba8/), [Tao Yu](https://ytrock.com/), [Wenjia Wang](https://scholar.google.com/citations?user=cVWmlYQAAAAJ&hl), Xiangyu Fan, Yang Gao, Yifan Yu, Liang Pan, Fangzhou Hong, Mingyuan Zhang, Chen Change Loy, Lei Yang, Ziwei Liu.*<br>
ECCV 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.13686)] [[项目](https://caizhongang.github.io/projects/HuMMan/)]

**高效几何感知神经关节表示的无监督学习**<br>
*Atsuhiro Noguchi, Xiao Sun, Stephen Lin, Tatsuya Harada.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.08839)] [[项目](https://nogu-atsu.github.io/ENARF-GAN/)] [[代码](https://github.com/nogu-atsu/ENARF-GAN)]

**NeuMan：从单个视频生成神经人体辐射场**<br>
*Wei Jiang, Kwang Moo Yi, Golnoosh Samei, Oncel Tuzel, Anurag Ranjan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2203.10157)] [[代码](https://github.com/apple/ml-neuman)]

**ARAH：铰接式人体有符号距离场的可动画体渲染**<br>
*[Shaofei Wang](https://taconite.github.io/), [Katja Schwarz](https://katjaschwarz.github.io/), [Andreas Geiger](http://www.cvlibs.net/), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2210.10036)] [[项目](https://neuralbodies.github.io/arah/)] [[代码](https://github.com/taconite/arah-release)]

**DiffuStereo：通过基于扩散的稀疏相机立体视觉实现高质量人体重建**<br>
*Ruizhi Shao, Zerong Zheng, Hongwen Zhang, Jingxiang Sun, Yebin Liu.*<br>
ECCV (Oral) 2022. [[PDF](https://arxiv.org/abs/2207.08000)] [[代码](https://github.com/DSaurus/DiffuStereo)]

**LoRD：用于高保真动态人体建模的局部 4D 隐式表示**<br>
*Boyan Jiang, Xinlin Ren, Mingsong Dou, Xiangyang Xue, Yanwei Fu, Yinda Zhang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08622)] [[代码](https://boyanjiang.github.io/LoRD/)]

**从单目视频对可动画 3D 人体进行神经捕捉**<br>
*Gusi Te, Xiu Li, Xiao Li, Jinglu Wang, Wei Hu, Yan Lu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.08728)]

**他们在电视节目中重建 3D 人体与环境的那一次**<br>
*Georgios Pavlakos, Ethan Weber, Matthew Tancik, Angjoo Kanazawa.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.14279)] [[项目](http://ethanweber.me/sitcoms3D/)]

**UNIF：用于着装人体重建与动画的联合神经隐式函数**<br>
*Shenhan Qian, Jiale Xu, Ziwei Liu, Liqian Ma, Shenghua Gao.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09835)]

**野外 3D 着装人体重建**<br>
*Gyeongsik Moon, Hyeongjin Nam, Takaaki Shiratori, Kyoung Mu Lee.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.10053)] [[项目](https://github.com/hygenie1228/ClothWild_RELEASE/blob/main)]

**NDF：用于动态人体建模的神经可变形场**<br>
*Ruiqi Zhang, Jie Chen.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09193)]

**铰接式人体有符号距离场的可动画体渲染**<br>
*[Shaofei Wang](https://taconite.github.io/), [Katja Schwarz](https://katjaschwarz.github.io/), [Andreas Geiger](http://www.cvlibs.net/), [Siyu Tang](https://vlg.inf.ethz.ch/team/Prof-Dr-Siyu-Tang.html).*<br>
ECCV 2022. [[PDF](https://drive.google.com/file/d/10yCrdOadwKNiDQBni23_W03ZwVafkfCJ/view)] [[项目](https://neuralbodies.github.io/arah/)] [[项目](https://github.com/taconite/arah-release)]

**学习用于基于点的着装人体建模的隐式模板**<br>
*Siyou Lin, Hongwen Zhang, Zerong Zheng, Ruizhi Shao, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.06955)] [[项目](https://jsnln.github.io/fite)] [[项目](https://github.com/jsnln/fite)]

**DANBO：通过图神经网络实现解耦的铰接式神经人体表示**<br>
*[Shih-Yang Su](https://lemonatsu.github.io/), [Timur Bagautdinov](https://scholar.google.ch/citations?user=oLi7xJ0AAAAJ&hl=en), and [Helge Rhodin](http://helge.rhodin.de/).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2205.01666)] [[项目](https://lemonatsu.github.io/danbo/)] [[代码](https://github.com/LemonATsu/DANBO-pytorch)]

**用于可泛化且高效的神经人体渲染的几何引导渐进式神经辐射场**<br>
*Mingfei Chen, Jianfeng Zhang, Xiangyu Xu, Lijuan Liu, Jiashi Feng, Shuicheng Yan.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2112.04312)]

**AvatarCap：基于可动画虚拟化身条件的单目人体体捕捉**<br>
*Zhe Li, Zerong Zheng, Hongwen Zhang, Chaonan Ji, Yebin Liu.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.02031)] [[项目](http://www.liuyebin.com/avatarcap/avatarcap.html)]

**通过手机扫描获得逼真的体虚拟化身**<br>
*[Chen Cao](https://sites.google.com/site/zjucaochen/home), Tomas Simon, Jin Kyu Kim, Gabe Schwartz, Michael Zollhoefer, Shunsuke Saito, Stephen Lombardi, Shih-en Wei, Danielle Belko, Shoou-i Yu, Yaser Sheikh, Jason Saragih.*<br>
SIGGRAPH 2022. [[PDF](https://drive.google.com/file/d/1i4NJKAggS82wqMamCJ1OHRGgViuyoY6R/view?usp=sharing)] [[项目](https://zollhoefer.com/papers/arXiv22_InstantAvatars/page.html)]

**HumanNeRF：从稀疏输入高效生成人体辐射场**<br>
*[Fuqiang Zhao](https://zhaofuq.github.io/), Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2112.02789.pdf)] [[项目](https://zhaofuq.github.io/humannerf/)] 

**穿着服装的人体的逼真单目 3D 重建**<br>
*[Thiemo Alldieck](https://scholar.google.com/citations?user=tJlD24EAAAAJ), [Mihai Zanfir](https://scholar.google.com/citations?user=af68sKkAAAAJ), [Cristian Sminchisescu](https://scholar.google.com/citations?user=LHTI1W8AAAAJ).*<br>
CVPR 2022. [[PDF](https://phorhum.github.io/static/assets/alldieck2022phorhum.pdf)] [[项目](https://phorhum.github.io/)]

**HumanNeRF：从单目视频对运动中的人进行自由视点渲染**<br>
*[Chung-Yi Weng](https://homes.cs.washington.edu/~chungyi/), Brian Curless, Pratul Srinivasan,Jonathan T. Barron, Ira Kemelmacher-Shlizerman.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04127)] [[项目](https://grail.cs.washington.edu/projects/humannerf/)]

**H4D：通过学习神经组合表示进行人体 4D 建模**<br>
*Boyan Jiang, Yinda Zhang, Xingkui Wei, Xiangyang Xue, Yanwei Fu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01247)]

**OcclusionFusion：用于实时动态 3D 重建的遮挡感知运动估计**<br>
*[Wenbin Lin](https://wenbin-lin.github.io/), Chengwei Zheng, Jun-Hai Yong, Feng Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/pdf/2203.07977.pdf)] [[项目](https://wenbin-lin.github.io/OcclusionFusion/)]

**PINA：从单个 RGB - D 视频序列学习个性化隐式神经虚拟化身**<br>
*Zijian Dong, Chen Guo, Jie Song, Xu Chen, Andreas Geiger, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.01754)] [[项目](https://zj-dong.github.io/pina/)]

**SelfRecon：从单目视频自我重建你的数字虚拟化身**<br>
*[Boyi Jiang](https://scholar.google.com/citations?user=lTlZV8wAAAAJ&hl=zh-CN), Yang Hong, Hujun Bao, Juyong Zhang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.12792)] [[项目](https://jby1993.github.io/SelfRecon/)]

**用于实时动态辐射场渲染的傅里叶全八叉树**<br>
*Liao Wang, Jiakai Zhang, Xinhang Liu, Fuqiang Zhao, Yanshun Zhang, Yingliang Zhang, Minye Wu, Lan Xu, Jingyi Yu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.08614)]

**NeuralHOFusion：人体 - 物体交互下的神经体渲染**<br>
*Yuheng Jiang, Suyi Jiang, Guoxing Sun, Zhuo Su, Kaiwen Guo, Minye Wu, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2202.12825)] [[项目](https://nowheretrix.github.io/neuralfusion/)]

**JIFF：用于高质量单视图着装人体重建的联合对齐隐式人脸函数**<br>
*[Yukang Cao](https://github.com/yukangcao), [Guanying Chen](https://guanyingc.github.io/), [Kai Han](http://www.hankai.org/), [Wenqi Yang](https://github.com/ywq), [Kwan-Yee K. Wong](http://i.cs.hku.hk/~kykwong/).*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.10549)] [[项目](https://yukangcao.github.io/JIFF)]

**从单个 RGB 相机获得高保真人体虚拟化身**<br>
*Hao Zhao, [Jinsong Zhang](https://zhangjinso.github.io/), [Yu-Kun Lai](https://users.cs.cf.ac.uk/Yukun.Lai/), [Zerong Zheng](https://zhengzerong.github.io/), Yingdi Xie, [Yebin Liu](http://www.liuyebin.com/), [Kun Li](http://cic.tju.edu.cn/faculty/likun/).*<br>
CVPR 2022. [[PDF](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/assets/main.pdf)] [[项目](http://cic.tju.edu.cn/faculty/likun/projects/HF-Avatar/index.html)] [[项目](https://github.com/hzhao1997/HF-Avatar)] [[数据](https://drive.google.com/file/d/1qh1dj5ZoUBst_02UJY7IWstQMhb8L5IA/view?usp=sharing)]

**ICON：从法线获得隐式着装人体**<br>
*[Yuliang Xiu](https://ps.is.tuebingen.mpg.de/person/yxiu), [Jinlong Yang](https://ps.is.tuebingen.mpg.de/person/jyang), [Dimitrios Tzionas](https://ps.is.mpg.de/~dtzionas), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.09127)] [[代码](https://github.com/YuliangXiu/ICON)]

**DoubleField：连接神经表面与辐射场以实现高保真人体渲染**<br>
*Ruizhi Shao, Hongwen Zhang, He Zhang, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[项目](http://www.liuyebin.com/dbfield/dbfield.html)]

**用于人体虚拟化身建模的结构化局部辐射场**<br>
*[Zerong Zheng](https://zhengzerong.github.io/), Han Huang, Tao Yu, Hongwen Zhang, Yandong Guo, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.14478)] [[项目](https://liuyebin.com/slrf/slrf.html)] [[代码](https://zhengzerong.github.io/)]

**DoubleField：连接神经表面与辐射场以实现高保真人体重建与渲染**<br>
*Ruizhi Shao, [Hongwen Zhang](https://hongwenzhang.github.io/), He Zhang, Mingjia Chen, Yanpei Cao, Tao Yu, Yebin Liu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2106.03798)] [[项目](http://www.liuyebin.com/dbfield/dbfield.html)]

**I M Avatar：从视频中生成隐式可变形头部虚拟化身**<br>
*Yufeng Zheng, Victoria Fernández Abrevaya, Xu Chen, Marcel C. Bühler, Michael J. Black, Otmar Hilliges.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07471)]

**用于可控 3D 人体合成的表面对齐神经辐射场**<br>
*Tianhan Xu, Yasuhiro Fujita, Eiichi Matsumoto.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.01683)]

**单目 RGB 视频生成神经头部虚拟化身**<br>
*[Philip-William Grassal](https://hci.iwr.uni-heidelberg.de/vislearn/people), [Malte Prinzler](https://de.linkedin.com/in/malte-prinzler), [Titus Leistner](https://titus-leistner.de/pages/about-me.html), [Carsten Rother](https://hci.iwr.uni-heidelberg.de/vislearn/people/carsten-rother/), [Matthias Nießner](https://www.niessnerlab.org/members/matthias_niessner/profile.html), [Justus Thies](https://justusthies.github.io/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.01554)] [[项目](https://philgras.github.io/neural_head_avatars/neural_head_avatars.html)]

**gDNA：迈向生成式详细神经虚拟化身**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu/), [Tianjian Jiang](https://ait.ethz.ch/people/zhengyuf/), [Jie Song](https://ait.ethz.ch/people/song/), [Jinlong Yang](https://is.mpg.de/person/jyang), [Michael J. Black](https://ps.is.mpg.de/~black), [Andreas Geiger](http://www.cvlibs.net/), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2201.04123)] [[项目](https://ait.ethz.ch/projects/2022/gdna/downloads/)] [[代码](https://github.com/xuchen-ethz/gdna)]

**HumanNeRF：从稀疏输入生成可泛化的神经人体辐射场**<br>
*Fuqiang Zhao, Wei Yang, Jiakai Zhang, Pei Lin, Yingliang Zhang, Jingyi Yu, Lan Xu.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.02789)] [[项目](https://zhaofuq.github.io/humannerf/)]

**PERGAMO：从单目视频生成个性化 3D 服装**<br>
*Andrés Casado-Elvira, Marc Comino Trinidad, Dan Casas.*<br>
CFG 2022. [[PDF](https://arxiv.org/abs/2210.15040)] [[项目](http://mslab.es/projects/PERGAMO/)]

**用于可动画全身虚拟化身的显式服装建模**<br>
*Donglai Xiang, Fabian Andres Prada, Timur Bagautdinov, Weipeng Xu, Yuan Dong, He Wen, Jessica Hodgins, Chenglei Wu.*<br>
SIGGRAPH Asia 2021. [[PDF](https://arxiv.org/abs/2106.14879)]

**驱动信号感知的全身虚拟化身**<br>
*Timur Bagautdinov, Chenglei Wu, Tomas Simon, Fabian Prada, Takaaki Shiratori, Shih-En Wei, Weipeng Xu, Yaser Sheikh, Jason Saragih.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.10441)]

**从 RGB - D 自拍创建高保真 3D 数字化人头**<br>
*Xiangkai Lin, Yajing Chen, Linchao Bao, Haoxian Zhang, Sheng Wang, Xuefei Zhe, Xinwei Jiang, Jue Wang, Dong Yu, Zhengyou Zhang.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2010.05562)] [[代码](https://github.com/tencent-ailab/hifi3dface)] [[项目](https://github.com/tencent-ailab/hifi3dface_projpage)]

**实时深度动态角色**<br>
*Marc Habermann, Lingjie Liu, Weipeng Xu, Michael Zollhoefer, Gerard Pons-Moll, Christian Theobalt.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.01794)] [[项目](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-ddc/)]

**利用神经混合形状学习骨骼关节运动**<br>
*Peizhuo Li, Kfir Aberman, Rana Hanocka, Libin Liu, Olga Sorkine-Hornung, Baoquan Chen.*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2105.02451)] [[视频](https://youtu.be/antc20EFh6k)] [[项目](https://peizhuoli.github.io/neural-blend-shapes/)]

**从单张图像中精细恢复虚拟化身**<br>
*Hao Zhu, Xinxin Zuo, Haotian Yang, Sen Wang, Xun Cao, Ruigang Yang.*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2108.02931)]

**RSC - 网络：从低分辨率图像和视频获取 3D 人体姿态、形状和纹理**<br>
*Xiangyu Xu, Hao Chen, Francesc Moreno-Noguer, Laszlo A. Jeni, Fernando De la Torre.*<br>
TPAMI 2021. [[PDF](https://arxiv.org/abs/2103.06498)] [[代码](https://github.com/xuxy09/RSC-Net)] [[项目](https://sites.google.com/view/xiangyuxu/3d_eccv20)]

**深入探究 DeepCap**<br>
*[Marc Habermann](http://people.mpi-inf.mpg.de/~mhaberma/), [Weipeng Xu](http://people.mpi-inf.mpg.de/~wxu/), [Michael Zollhoefer](https://zollhoefer.com/), [Gerard Pons-Moll](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/people/gerard-pons-moll/), [Christian Theobalt](http://www.mpi-inf.mpg.de/~theobalt/).*<br>
TPAMI 2021. [[PDF](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-tpami-deeperdeepcap/data/paper.pdf)] [[代码](https://people.mpi-inf.mpg.de/~mhaberma/projects/2021-tpami-deeperdeepcap/)] [[数据](https://gvv-assets.mpi-inf.mpg.de/)]

**从稀疏视角学习着装人体的隐式 3D 表示**<br>
*Pierre Zins, Yuanlu Xu, Edmond Boyer, Stefanie Wuhrer, Tony Tung.*<br>
3DV 2021. [[PDF](https://arxiv.org/abs/2104.08013)]

**PIXIE：通过适度协作回归生成表情丰富的人体**<br>
*Yao Feng, Vasileios Choutas, Timo Bolkart, Dimitrios Tzionas, Michael J. Black.*<br>
3DV 2021. [[PDF](https://arxiv.org/pdf/2105.05301.pdf)] [[项目](https://pixie.is.tue.mpg.de/)] 

**A - NeRF：用于学习人体形状、外观和姿态的铰接式神经辐射场**<br>
*[Shih-Yang Su](https://lemonatsu.github.io/), [Frank Yu](https://yu-frank.github.io/), [Michael Zollhoefer](https://zollhoefer.com/), [Helge Rhodin](http://helge.rhodin.de/).*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2102.06199)] [[项目](https://lemonatsu.github.io/ANeRF-Surface-free-Pose-Refinement/)]

**从视频中进行与类别无关的动态物体重建**<br>
*[Zhongzheng Ren](https://jason718.github.io), [Xiaoming Zhao](https://xiaoming-zhao.com/index.php), [Alexander G. Schwing](http://www.alexander-schwing.de/).*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2112.02091)] [[项目](https://jason718.github.io/redo)]

**神经人体表演者：学习用于人体动作渲染的可泛化辐射场**<br>
*Youngjoong Kwon, Dahun Kim, Duygu Ceylan, Henry Fuchs.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2109.07448)]

**MetaAvatar：从少量深度图像学习可动画的着装人体模型**<br>
*[Shaofei Wang](https://taconite.github.io/), Marko Mihajlovic, Qianli Ma, Andreas Geiger, Siyu Tang.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2106.11944)] [[项目](https://neuralbodies.github.io/metavatar/)] [[代码](https://github.com/taconite/MetaAvatar-release)]

**Garment4D：从点云序列进行服装重建**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), Liang Pan, Zhongang Cai, Ziwei Liu.*<br>
NeurIPS 2021. [[PDF](https://openreview.net/pdf?id=aF60hOEwHP)] [[项目](https://hongfz16.github.io/projects/Garment4D.html)] [[代码](https://github.com/hongfz16/Garment4D)]

**学习用于单视图服装重建的具有梯度方向对齐的锚定无符号距离函数**<br>
*Fang Zhao, Wenhao Wang, Shengcai Liao, Ling Shao.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.08478)] [[代码](https://github.com/zhaofang0627/AnchorUDF)]

**用于着装人体的动态表面函数网络**<br>
*Andrei Burov, Matthias Nießner, Justus Thies.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2104.03978)] [[视频](https://youtu.be/4wbSi9Sqdm4)] [[代码](https://github.com/andreiburov/DSFN)]

**THUNDR：基于 Transformer 且使用标记的 3D 人体重建**<br>
*Mihai Zanfir, Andrei Zanfir, Eduard Gabriel Bazavan, William T. Freeman, Rahul Sukthankar, Cristian Sminchisescu.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2106.09336)]

**神经铰接式辐射场**<br>
*Atsuhiro Noguchi, Xiao Sun, Stephen Lin, Tatsuya Harada.*<br>
ICCV 2021. [[PDF](http://arxiv.org/abs/2104.03110)]

**使用 Transformer 从单张图像进行 3D 人体纹理估计**<br>
*Xiangyu Xu, Chen Change Loy.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Xu_3D_Human_Texture_Estimation_From_a_Single_Image_With_Transformers_ICCV_2021_paper.html)]

**ARCH++：重新审视适用于动画的着装人体重建**<br>
*Tong He, Yuanlu Xu, Shunsuke Saito, Stefano Soatto, Tony Tung.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/He_ARCH_Animation-Ready_Clothed_Human_Reconstruction_Revisited_ICCV_2021_paper.html)]

**DeePSD：用于 3D 服装动画的自动深度蒙皮和姿态空间变形**<br>
*Hugo Bertiche, Meysam Madadi, Emilio Tylson, Sergio Escalera.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Bertiche_DeePSD_Automatic_Deep_Skinning_and_Pose_Space_Deformation_for_3D_ICCV_2021_paper.html)]

**EgoRenderer：从以自我为中心的相机图像渲染人体虚拟化身**<br>
*Tao Hu, Kripasindhu Sarkar, Lingjie Liu, Matthias Zwicker, Christian Theobalt.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Hu_EgoRenderer_Rendering_Human_Avatars_From_Egocentric_Camera_Images_ICCV_2021_paper.html)]

**SNARF：用于非刚性神经隐式形状动画的可微正向蒙皮**<br>
*[Xu Chen](https://ait.ethz.ch/people/xu/), [Yufeng Zheng](https://ait.ethz.ch/people/zhengyuf/), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/), [Andreas Geiger](http://www.cvlibs.net/).*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2104.03953)] [[项目](https://xuchen-ethz.github.io/snarf/) [[代码](https://github.com/xuchen-ethz/snarf)]

**Neural - GIF：用于穿着服装的人动画的神经广义隐式函数**<br>
*[Garvita Tiwari](https://virtualhumans.mpi-inf.mpg.de/people/Tiwari.html), Nikolaos Sarafianos, [Tony Tung](https://sites.google.com/site/tony2ng/), Gerard Pons-Moll.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.08807)] [[项目](https://virtualhumans.mpi-inf.mpg.de/neuralgif/)]

**点在穿着服装的人体建模中的作用**<br>
*[Qianli Ma](https://qianlim.github.io/), Jinlong Yang, Siyu Tang, Michael J. Black.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2109.01137)] [[项目](https://qianlim.github.io/POP)] [[代码](https://github.com/qianlim/POP)]

**使用可微语义渲染从图像学习回归人体**<br>
*[Sai Kumar Dwivedi](https://ps.is.tuebingen.mpg.de/person/sdwivedi), [Nikos Athanasiou](https://ps.is.tuebingen.mpg.de/employees/nathanasiou), [Muhammed Kocabas](https://ps.is.tuebingen.mpg.de/person/mkocabas), [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2110.03480)] [[项目](https://dsr.is.tue.mpg.de/)]

**imGHUM：3D 人体形状和铰接姿态的隐式生成模型**<br>
*Thiemo Alldieck, Hongyi Xu, Cristian Sminchisescu.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.10842)] 

**DeepMultiCap：使用稀疏多视图相机进行多角色动作捕捉**<br>
*[Yang Zheng](https://y-zheng18.github.io/zy.github.io/), Ruizhi Shao, [Yuxiang Zhang](https://zhangyux15.github.io/), [Zerong Zheng](https://zhengzerong.github.io/), [Tao Yu](https://ytrock.com/), [Yebin Liu](http://www.liuyebin.com/student.html).*<br>
ICCV 2021. [[PDF](http://www.liuyebin.com/dmc/assets/main.pdf)] [[项目](http://www.liuyebin.com/dmc/dmc.html)]

**用于人体建模的可动画神经辐射场**<br>
*[Sida Peng](https://pengsida.net/), Junting Dong, Qianqian Wang, Shangzhan Zhang, Qing Shuai, Hujun Bao, Xiaowei Zhou.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2105.02872)] [[项目](https://zju3dv.github.io/animatable_nerf/)] [[代码](https://github.com/zju3dv/animatable_nerf)]

**用于动态人体建模的可动画神经辐射场**<br>
*Sida Peng, Junting Dong, Qianqian Wang, Shangzhan Zhang, Qing Shuai, Xiaowei Zhou, Hujun Bao.*<br>
ICCV 2021. [[PDF](https://arxiv.org/pdf/2203.08133.pdf)] [[项目](https://zju3dv.github.io/animatable_nerf/)]

**Function4D：从非常稀疏的消费级 RGBD 传感器进行实时人体体捕捉**<br>
*Tao Yu, Zerong Zheng, Kaiwen Guo, Pengpeng Liu, Qionghai Dai, Yebin Liu.*<br>
CVPR 2021 (oral). [[PDF](http://www.liuyebin.com/Function4D/assets/Function4D.pdf)] [[项目](http://www.liuyebin.com/Function4D/Function4D.html)] [[THuman2.0 Dataset](https://github.com/ytrock/THuman2.0-Dataset)]

**POSEFusion：用于单视图人体体捕捉的姿态引导选择性融合**<br>
*[Zhe Li](https://lizhe00.github.io/), Tao Yu, Zerong Zheng, Kaiwen Guo, Yebin Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.15331)] [[项目](http://www.liuyebin.com/posefusion/posefusion.html)]

**SCANimate：蒙皮着装虚拟化身网络的弱监督学习**<br>
*Shunsuke Saito, Jinlong Yang, Qianli Ma, Michael J. Black.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.03313)] [[代码](https://www.cs.cmu.edu/~aayushb/SST/)]

**使用 StyleGAN 和感知细化进行归一化虚拟化身合成**<br>
*Huiwen Luo, Koki Nagano, Han-Wei Kung, [Qingguo Xu](https://qingguo-xu.com/), Zejian Wang, Lingyu Wei, Liwen Hu, Hao Li.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2106.11423)]

**DeepSurfels：学习在线外观融合**<br>
*Marko Mihajlovic, Silvan Weder, Marc Pollefeys, Martin R. Oswald.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.14240)] [[项目](https://onlinereconstruction.github.io/DeepSurfels)] [[代码](https://github.com/onlinereconstruction/deep_surfels)]

**用于 3D 人体的高分辨率可编辑纹理的半监督合成**<br>
*Bindita Chaudhuri, Nikolaos Sarafianos, Linda Shapiro, Tony Tung.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2103.17266)]

**StereoPIFu：通过立体视觉实现深度感知的着装人体数字化**<br>
*Yang Hong, [Juyong Zhang](http://staff.ustc.edu.cn/~juyong/), Boyi Jiang, [Yudong Guo](https://yudongguo.github.io/), Ligang Liu, Hujun Bao.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.05289)] [[项目](https://crishy1995.github.io/StereoPIFuProject/)] [[代码](https://github.com/CrisHY1995/StereoPIFu_Code)]

**LASR：从单目视频学习铰接形状重建**<br>
*Gengshan Yang, Deqing Sun, Varun Jampani, Daniel Vlasic, Forrester Cole, Huiwen Chang, Deva Ramanan, William T. Freeman, Ce Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2105.02976)] [[项目](https://lasr-google.github.io/)]

**从单张图像进行多人隐式重建**<br>
*Armin Mustafa, Akin Caliskan, Lourdes Agapito, Adrian Hilton.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.09283)]

**StylePeople：全身人体虚拟化身的生成模型**<br>
*Artur Grigorev, Karim Iskakov, Anastasia Ianina, Renat Bashirov, Ilya Zakharkin, Alexander Vakhitov, Victor Lempitsky.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.08363)]

**SCALE：使用铰接局部元素的表面编解码器对着装人体进行建模**<br>
*Qianli Ma, Shunsuke Saito, Jinlong Yang, Siyu Tang, Michael J. Black.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.07660)] [[项目](https://qianlim.github.io/SCALE)]

**用于 3D 人体的高分辨率可编辑纹理的半监督合成**<br>
*Bindita Chaudhuri, Nikolaos Sarafianos, Linda Shapiro, Tony Tung.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.17266)]

**具有部件间相关性的单目实时全身捕捉**<br>
*[Yuxiao Zhou](https://calciferzh.github.io/), [Marc Habermann](https://people.mpi-inf.mpg.de/~mhaberma/), Ikhsanul Habibie, Ayush Tewari, [Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/), [Feng Xu](http://xufeng.site/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.06087)]

**SMPLicit：用于着装人体的拓扑感知生成模型**<br>
*Enric Corona, Albert Pumarola, Guillem Alenyà, Gerard Pons-Moll, Francesc Moreno-Noguer.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.06871)] [[项目](http://www.iri.upc.edu/people/ecorona/smplicit/)]

**3D 角色二次运动的深度模拟器**<br>
*Mianlun Zheng, Yi Zhou, Duygu Ceylan, Jernej Barbic.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.01261)]

**PVA：像素对齐的体虚拟化身**<br>
*Amit Raj, Michael Zollhoefer, Tomas Simon, Jason Saragih, Shunsuke Saito, James Hays, Stephen Lombardi.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.02697)] [[项目](https://volumetric-avatars.github.io/)]

**ANR：用于虚拟化身的铰接式神经渲染**<br>
*Amit Raj, Julian Tanke, James Hays, Minh Vo, Carsten Stoll, Christoph Lassner.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2012.12890)] [[项目](https://anr-avatars.github.io/)]

**SMPLpix：从 3D 人体模型生成神经虚拟化身**<br>
*Sergey Prokudin, Michael J. Black, Javier Romero.*<br>
WACV 2021. [[PDF](https://arxiv.org/abs/2008.06872)] [[代码](https://github.com/sergeyprokudin/smplpix)]

**用于单目人体网格恢复的合成训练**<br>
*Yu Sun, Qian Bao, Wu Liu, Wenpeng Gao, Yili Fu, Chuang Gan, Tao Mei.*<br>
BMVC 2020. [[PDF](https://arxiv.org/abs/2010.14036)]

**从智能手机视频生成逼真的虚拟人**<br>
*Stephan Wenninger, Jascha Achenbach, Andrea Bartl, Marc Erich Latoschik, [Mario Botsch](https://ls7-gv.cs.tu-dortmund.de/).*<br>
ACM VRST 2020 (最佳论文奖). [[PDF](https://ls7-gv.cs.tu-dortmund.de/downloads/publications/2020/vrst20.pdf)] [[Video](https://ls7-gv.cs.tu-dortmund.de/downloads/publications/2020/vrst20.mp4)] [[Talk](https://youtu.be/Mm318gs_fb8)]

**LoopReg：用于 3D 人体网格配准的隐式表面对应关系、姿态和形状的自监督学习**<br>
*Bharat Lal Bhatnagar, Cristian Sminchisescu, Christian Theobalt, Gerard Pons-Moll.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2010.12447)] [[代码](https://github.com/bharat-b7/LoopReg)]

**3D Multi-bodies: 将合理的 3D 人体模型集拟合到模糊图像数据**<br>
*Benjamin Biggs, Sébastien Ehrhadt, Hanbyul Joo, Benjamin Graham, Andrea Vedaldi, David Novotny.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2011.00980)]

**HPBTT：通过跨视图一致性从单张图像到 3D 人体的基于人体解析的纹理转移**<br>
*Fang Zhao, Shengcai Liao, Kaihao Zhang, Ling Shao.*<br>
NeurIPS 2020. [[PDF](https://papers.nips.cc/paper/2020/file/a516a87cfcaef229b342c437fe2b95f7-Paper.pdf)] [[代码](https://github.com/zhaofang0627/HPBTT)]

**Neural3D：通过上下文感知对应学习实现轻量级神经肖像扫描**<br>
*Xin Suo, Minye  Wu, Yanshun  Zhang, Yanshun Zhang, Yingliang  Zhang, Yingliang Zhang, Lan  Xu, Qiang  Hu, Jingyi  Yu.*<br>
ACM MM 2020. [[PDF](https://dl.acm.org/doi/abs/10.1145/3394171.3413734)]

**3DBooSTeR：3D 人体形状和纹理恢复**<br>
*Alexandre Saint, Anis Kacem, Kseniya Cherenkova, Djamila Aouada.*<br>
ECCV 2020 Workshop. [[PDF](https://arxiv.org/abs/2010.12670)]

**BCNet：从单张图像学习人体和服装形状**<br>
*Boyi Jiang, Juyong Zhang, Yang Hong, Jinhao Luo, Ligang Liu, Hujun Bao.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2004.00214)]

**MonoPort：单目实时体动作捕捉**<br>
*Ruilong Li, Yuliang Xiu, Shunsuke Saito, Zeng Huang, Kyle Olszewski, Hao Li.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13988)] [[代码](https://github.com/Project-Splinter/MonoPort)]

**通过自监督学习从单张低分辨率图像获取 3D 人体形状和姿态**<br>
*Xiangyu Xu, Hao Chen, Francesc Moreno-Noguer, Laszlo A. Jeni, Fernando De la Torre.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13666)] [[项目](https://sites.google.com/view/xiangyuxu/3d_eccv20)]

**BLSM：人体网格的骨骼级蒙皮模型**<br>
*Haoyang Wang, Riza Alp Güler, Iasonas Kokkinos, George Papandreou, Stefanos Zafeiriou.*<br>
ECCV 2020. [[pdf](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500001.pdf)] [[补充](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500001-supp.zip)]

**STAR：稀疏训练的铰接式人体回归器**<br>
*Ahmed A. A. Osman, Timo Bolkart, Michael J. Black.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.08535)] [[项目](http://star.is.tue.mpg.de/)]

**I2L - MeshNet：用于从单张 RGB 图像精确估计 3D 人体姿态和网格的图像到体素预测网络**<br>
*Gyeongsik Moon, Kyoung Mu Lee.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.03713)] [[代码](https://github.com/mks0601/I2L-MeshNet_RELEASE)]

**基于外观一致性驱动的自监督人体网格恢复**<br>
*Jogendra Nath Kundu, Mugalodi Rakesh, Varun Jampani, Rahul Mysore Venkatesh, R. Venkatesh Babu.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.01341)]

**TexMesh：从 RGB - D 视频重建详细的人体纹理和几何形状**<br>
*Tiancheng Zhi, Christoph Lassner, Tony Tung, Carsten Stoll, Srinivasa G. Narasimhan, Minh Vo.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2008.00158)]

**NormalGAN：从单张 RGB - D 图像学习详细的 3D 人体**<br>
*Lizhen Wang, Xiaochen Zhao, Tao Yu, Songtao Wang, [Yebin Liu](http://liuyebin.com/).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.15340)] [[项目](http://www.liuyebin.com/NormalGan/normalgan.html)]

**重建 NBA 球员**<br>
*[Luyang Zhu](https://homes.cs.washington.edu/~lyzhu/), [Konstantinos Rematas](http://www.krematas.com/), [Brian Curless](https://homes.cs.washington.edu/~curless/), [Steve Seitz](https://homes.cs.washington.edu/~seitz/), [Ira Kemelmacher-Shlizerman](https://sites.google.com/view/irakemelmacher/home).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.13303)] [[代码](https://github.com/luyangzhu/NBA-Players)] [[项目](http://grail.cs.washington.edu/projects/nba_players/)]

**RobustFusion：使用 RGBD 相机基于数据驱动视觉线索的人体体捕捉**<br>
*Zhuo Su, [Xu Lan](https://www.xu-lan.com/), Zerong Zheng, Tao Yu, Yebin Liu, Lu Fang.*<br>
ECCV 2020. [[PDF](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490239.pdf)]

**IPNet：结合隐式函数学习和参数模型进行 3D 人体重建**<br>
*Bharat Lal Bhatnagar, Cristian Sminchisescu, Christian Theobalt, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11432)] [[项目](http://virtualhumans.mpi-inf.mpg.de/ipnet)] [[代码](https://github.com/bharat-b7/IPNet)]

**神经铰接形状近似**<br>
*Boyang Deng, JP Lewis, Timothy Jeruzalski, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html), Geoffrey Hinton, Mohammad Norouzi, Andrea Tagliasacchi.*<br>
ECCV 2020. [[PDF](http://virtualhumans.mpi-inf.mpg.de/papers/NASA20/NASA.pdf)]

**SIZER：一个用于解析 3D 服装和学习尺寸敏感型 3D 服装的数据集与模型**<br>
*Garvita Tiwari, Bharat Lal Bhatnagar, Tony Tung, [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/publications.html).*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11610)] [[数据](https://nextcloud.mpi-klsb.mpg.de/index.php/s/nx6wK6BJFZCTF8C)] [[代码](https://github.com/garvita-tiwari/sizer)] [[项目](https://virtualhumans.mpi-inf.mpg.de/sizer/)]

**TailorNet：根据人体姿态、形状和服装风格预测 3D 服装**<br>
*Chaitanya Patel, Zhouyingcheng Liao, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.04583)] [[代码](https://github.com/chaitanya100100/TailorNet)] [[项目](https://virtualhumans.mpi-inf.mpg.de/tailornet/)] [[数据](https://github.com/zycliao/TailorNet_dataset)]

**Geo - PIFu：用于单视图人体重建的几何与像素对齐隐式函数**<br>
*Tong He, John Collomosse, Hailin Jin, Stefano Soatto.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.08072)] [[代码](https://github.com/simpleig/Geo-PIFu)]

**从单目视频进行自监督人体深度估计**<br>
*Feitong Tan, Hao Zhu, Zhaopeng Cui, Siyu Zhu, Marc Pollefeys, Ping Tan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2005.03358)]

**ARCH：可动画的着装人体重建**<br>
*Zeng Huang, Yuanlu Xu, Christoph Lassner, Hao Li, Tony Tung.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.04572)]

**pix2surf：学习将纹理从服装图像转移到 3D 人体**<br>
*[Aymen Mir](https://virtualhumans.mpi-inf.mpg.de/people/Mir.html), Thiemo Alldieck, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.02050)] [[代码](https://github.com/aymenmir1/pix2surf)]

**PIFuHD：用于高分辨率 3D 人体数字化的多层像素对齐隐式函数**<br>
*[Shunsuke Saito](http://www-scf.usc.edu/~saitos/), [Tomas Simon](https://scholar.google.com/citations?user=7aabHgsAAAAJ), [Jason Saragih](https://scholar.google.com/citations?hl=en&user=ss-IvjMAAAAJ), [Hanbyul Joo](https://jhugestar.github.io/).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.00452)] [[项目](https://shunsukesaito.github.io/PIFuHD)] [[代码](https://github.com/facebookresearch/pifuhd)]

**DeepCap：使用弱监督的单目人体动作捕捉**<br>
*Marc Habermann, Weipeng Xu, Michael Zollhoefer, erard Pons-Moll, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-deepcap/data/paper.pdf)] [[项目](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-deepcap/)]

**EventCap：使用事件相机对高速人体运动进行单目 3D 捕捉**<br>
*Lan XU, Weipeng Xu, Vladislav Golyanik, Marc Habermann, Lu Fang, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-eventcap/data/paper.pdf)] [[项目](https://gvv.mpi-inf.mpg.de/projects/2020-cvpr-eventcap/)]

**DeepDeform：利用半监督数据学习非刚性 RGB - D 重建**<br>
*Aljaž Božič, Michael Zollhöfer, Christian Theobalt, Matthias Nießner.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1912.04302)] [[项目](https://pure.mpg.de/pubman/faces/ViewItemOverviewPage.jsp?itemId=item_3187203)] [[代码](https://github.com/AljazBozic/DeepDeform)] [[DeepDeform Benchmark](http://kaldir.vc.in.tum.de/deepdeform_benchmark)]

**特征空间中用于 3D 形状重建与补全的隐式函数**<br>
*Julian Chibane, [Thiemo Alldieck](https://graphics.tu-bs.de/people/alldieck), Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/chibane20ifnet/chibane20ifnet.pdf)]

**DeepCap：使用弱监督的单目人体动作捕捉**<br>
*Marc Habermann, Weipeng Xu, Michael and Zollhoefer, Gerard Pons-Moll, Christian Theobalt.*<br>
CVPR 2020. [[PDF](https://virtualhumans.mpi-inf.mpg.de/)]

**TetraTSDF：利用四面体外壳从单张图像进行 3D 人体重建**<br>
*Hayato Onizuka, Zehra Hayirci, Diego Thomas, Akihiro Sugimoto, Hideaki Uchiyama, Rin-ichiro Taniguchi.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.10534)] [[代码](https://github.com/diegothomas/TetraTSDF)]

**用于改进着装人体单图像 3D 重建的多视图一致性损失**<br>
*Akin Caliskan, Adrian Hilton.*<br>
ACCV 2020. [[PDF](https://arxiv.org/abs/2009.14162)] [[代码](https://github.com/akcalakcal/Multi_View_Consistent_Single_Image_3D_Human_Reconstruction)]

**PaMIR：用于基于图像的人体重建的参数模型条件隐式表示**<br>
*Zerong Zheng, Tao Yu, Yebin Liu, Qionghai Dai.*<br>
TPAMI 2020. [[PDF](http://www.liuyebin.com/pamir/assets/revised_paper.pdf)] [[项目](http://www.liuyebin.com/pamir/pamir.html)]

**MulayCap：使用单目摄像机进行多层人体动作捕捉**<br>
*Zhaoqi Su, Weilin Wan, [Tao Yu](https://ytrock.com/), [Lingjie Liu](https://lingjie0206.github.io/), Lu Fang, Wenping Wang and Yebin Liu.*<br>
TVCG 2020. [[PDF](http://www.liuyebin.com/MulayCap/MulayCap_files/MulayCap.pdf)] [[项目](http://www.liuyebin.com/MulayCap/MulayCap.html)]

**基于深度层次神经网络的解耦人体嵌入**<br>
*Boyi Jiang, Juyong Zhang, Jianfei Cai, Jianmin Zheng.*<br>
TVCG 2020. [[PDF](https://arxiv.org/abs/1905.05622)]

**SparseFusion：从稀疏 RGBD 图像进行动态人体虚拟化身建模**<br>
*Xinxin Zuo, Sen Wang, Jiangbin Zheng, Weiwei Yu, Minglun Gong, Ruigang Yang, Li Cheng.*<br>
TMM 2020. [[PDF](https://arxiv.org/abs/2006.03630)]

**UnstructuredFusion：使用商用 RGBD 相机进行实时 4D 几何和纹理重建**<br>
*Lan Xu, Zhuo Su, Lei Han, Tao Yu, Yebin Liu, Lu Fang.*<br>
TPAMI 2019. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8708933)]

**PIFu：用于高分辨率着装人体数字化的像素对齐隐式函数**<br>
*Shunsuke Saito, Zeng Huang, Ryota Natsume, Shigeo Morishima, Angjoo Kanazawa, Hao Li.*<br>
ICCV 2019. [[PDF](https://arxiv.org/pdf/1905.05172.pdf)] [[项目](shunsukesaito.github.io/PIFu)] [[代码](https://github.com/shunsukesaito/PIFu)]

**Multi - Garment Net：从图像学习为 3D 人物着装**<br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, Gerard Pons-Moll.*<br>
ICCV 2019. [[代码](https://github.com/bharat-b7/MultiGarmentNetwork)] [[PDF](https://virtualhumans.mpi-inf.mpg.de/papers/bhatnagar2019mgn/bhatnagar2019mgn.pdf)]

**学习从单个 RGB 相机重建着装人体**<br>
*Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll.* <br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1903.05885)] [[代码](https://github.com/thmoa/octopus)]

**用于从单张图像进行详细人体深度估计的神经网络**<br>
*Sicong Tang, Feitong Tan, Kelvin Cheng, Zhaoyang Li, Siyu Zhu, Ping Tan.* <br>
ICCV 2019. [[PDF](http://openaccess.thecvf.com/content_ICCV_2019/papers/Tang_A_Neural_Network_for_Detailed_Human_Depth_Estimation_From_a_ICCV_2019_paper.pdf)]

**纹理姿态（TexturePose）：利用纹理一致性监督人体网格估计** <br>
*[Georgios Pavlakos](https://www.seas.upenn.edu/~pavlakos/), [Nikos Kolotouros](https://www.seas.upenn.edu/~nkolot/), [Kostas Daniilidis](http://www.cis.upenn.edu/~kostas/).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1910.11322)] [[项目](https://www.seas.upenn.edu/~pavlakos/projects/texturepose/)] [[代码](https://github.com/geopavlakos/TexturePose)]

**3D人体：着装人体的几何建模** <br>
*Albert Pumarola, Jordi Sanchez, Gary P. T. Choi, Alberto Sanfeliu, Francesc Moreno-Noguer.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.04571)] [[3DPeople-Dataset](https://github.com/albertpumarola/3DPeople-Dataset)]

**DeepHuman：从单张图像进行 3D 人体重建**<br>
*Zerong Zheng, Tao Yu, Yixuan Wei, Qionghai Dai, Yebin Liu.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1904.04571)] [[项目](http://www.liuyebin.com/deephuman/deephuman.html)]

**Tex2Shape：从单张图像获取详细的全身人体几何形状**<br>
*Thiemo Alldieck, Gerard Pons-Moll, Christian Theobalt, Marcus Magnor.* <br>
CVPR 2019. [[PDF](https://arxiv.org/abs/1903.06473)] [[代码](https://github.com/thmoa/tex2shape)]

**SimulCap：结合布料模拟的单视图人体动作捕捉**<br>
*Tao Yu, Zerong Zheng, Yuan Zhong, Jianhui Zhao, Qionghai Dai, Gerard Pons-moll, Yebin Liu.*<br>
CVPR 2019. [[PDF](http://www.liuyebin.com/simulcap/assets/SimulCap.pdf)] [[项目](http://www.liuyebin.com/simulcap/simulcap.html)]

**SiCloPe：基于轮廓的着装人体 ** <br>
*Ryota Natsume, [Shunsuke Saito](http://www-scf.usc.edu/~saitos/), Zeng Huang, Weikai Chen, Chongyang Ma, Hao Li, Shigeo Morishima.* <br>
CVPR 2019. [[PDF](http://openaccess.thecvf.com/content_CVPR_2019/papers/Natsume_SiCloPe_Silhouette-Based_Clothed_People_CVPR_2019_paper.pdf)]

**带纹理的神经虚拟化身**<br>
*Aliaksandra Shysheya, Egor Zakharov, Kara-Ali Aliev, Renat Bashirov, Egor Burkov, Karim Iskakov, Aleksei Ivakhnenko, Yury Malkov, Igor Pasechnik, Dmitry Ulyanov, Alexander Vakhitov, Victor Lempitsky.*<br>
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1905.08776)] [[项目](https://saic-violet.github.io/texturedavatar/)]

**MonoClothCap：迈向从单目 RGB 视频进行时间连贯的服装捕捉**<br>
*[Donglai Xiang](https://xiangdonglai.github.io/), Fabian Prada, Chenglei Wu, Jessica Hodgins.*<br>
3DV 2020 (最佳论文荣誉提名，口头报告). [[PDF](https://arxiv.org/abs/2009.10711)]

**从单张图像获取着装人体的 360 度纹理** <br>
*Verica Lazova, Eldar Insafutdinov, Gerard Pons-Moll.* <br>
3DV 2019. [[PDF](https://arxiv.org/pdf/1908.07117.pdf)] [[项目](http://virtualhumans.mpi-inf.mpg.de/360tex/)] 

**从单目视频生成精细的人体虚拟化身**  <br>
*Thiemo Alldieck, Marcus Magnor, Weipeng Xu, Christian Theobalt, Gerard Pons-Moll.* <br>
3DV 2018. [[PDF](https://arxiv.org/abs/1808.01338)] [[代码](https://github.com/thmoa/semantic_human_texture_stitching)]

**BodyFusion：使用单个深度相机实时捕捉人体运动和表面几何形状**<br>
*[Tao Yu](https://ytrock.com/), [Kaiwen Guo](http://www.guokaiwen.com/), [Feng Xu](http://feng-xu.com/), Yuan Dong, Zhaoqi Su, Jianhui Zhao, Jianguo Li, Qionghai Dai, Yebin Liu.*<br>
ICCV 2017. [[PDF](http://liuyebin.com/bodyfusion/bodyfusion_files/BdyFu_ICC7.pdf)] [[项目]()]

## 布料建模、布料悬垂模拟、布料仿真以及穿衣 <a name='cloth-modelling--draping--simulation--and-dressing'></a>

**4D - DRESS：一个带有语义标注的真实世界人体服装 4D 数据集**<br>
*[Wenbo Wang](https://wenbwa.github.io), [Hsuan-I Ho](https://ait.ethz.ch/people/hohs), [Chen Guo](https://ait.ethz.ch/people/cheguo), [Boxiang Rong](https://ribosome-rbx.github.io), [Artur Grigorev](https://ait.ethz.ch/people/agrigorev), [Jie Song](https://ait.ethz.ch/people/song), [Juan Jose Zarate](https://ait.ethz.ch/people/jzarate), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges).*<br>
CVPR 2024 (Highlight). [[PDF](https://arxiv.org/abs/2404.18630)] [[项目](https://eth-ait.github.io/4d-dress/)] [[数据](https://4d-dress.ait.ethz.ch/)] [[代码](https://github.com/eth-ait/4d-dress)]

**生成式多分辨率金字塔和法线条件 3D 布料褶皱模拟**<br>
*Hunor Laczkó, Meysam Madadi, Sergio Escalera, Jordi Gonzalez.*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2311.02700)]

**迈向多层 3D 服装动画**<br>
*Yidi Shao, Chen Change Loy, Bo Dai.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2305.10418.pdf)] [[项目](https://mmlab-ntu.github.io/project/layersnet/index.html)]

**REC - MV：从单目视频重建 3D 动态布料**<br>
*[Lingteng Qiu](https://lingtengqiu.github.io/), [Guanying Chen](https://guanyingc.github.io/), Jiapeng Zhou, [Mutian Xu](https://mutianxu.github.io/), Junle Wang, [Xiaoguang Han](https://mypage.cuhk.edu.cn/academics/hanxiaoguang/).*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2305.14236)] [[项目](https://lingtengqiu.github.io/2023/REC-MV/)] [[代码](https://github.com/GAP-LAB-CUHK-SZ/REC-MV)]

**HOOD：用于服装动力学广义建模的层次图**<br>
*[Artur Grigorev](https://dolorousrtur.github.io/), [Bernhard Thomaszewski](https://n.ethz.ch/~bthomasz/index.html), [Michael J. Black](https://ps.is.mpg.de/~black), [Otmar Hilliges](https://ait.ethz.ch/people/hilliges/).*<br> 
CVPR 2023. [[PDF](https://arxiv.org/abs/2212.07242)] [[项目](https://dolorousrtur.github.io/hood/)] [[代码](https://github.com/Dolorousrtur/HOOD)]

**薄壳模型的深度变形细节合成**<br>
*Lan Chen, Lin Gao, Jie Yang, Shibiao Xu, Juntao Ye, Xiaopeng Zhang, Yu-Kun Lai.*<br>
CGF 2023. [[PDF](https://arxiv.org/abs/2102.11541)]

**运动引导的深度动态 3D 服装**<br>
*[Meng Zhang](https://mengzephyr.com/), [Duygu Ceylan](https://research.adobe.com/person/duygu-ceylan/), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/).*<br>
SIGGRAPH Asia 2022. [[PDF](https://arxiv.org/pdf/2209.11449.pdf)] [[项目](http://geometry.cs.ucl.ac.uk/projects/2022/MotionDeepGarment/)]

**使用骨骼驱动运动网络预测宽松服装变形**<br>
*Xiaoyu Pan, Jiaming Mai, Xinwei Jiang, Dongxue Tang, Jingxiang Li, Tianjia Shao, Kun Zhou, Xiaogang Jin, Dinesh Manocha.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.01355)] [[代码](https://github.com/non-void/VirtualBones)]

**DiffCloth：具有干摩擦接触的可微布料模拟**<br>
*[Yifei Li](https://people.csail.mit.edu/liyifei/), [Tao Du](https://people.csail.mit.edu/taodu/), [Kui Wu](https://people.csail.mit.edu/kuiwu/), [Jie Xu](http://people.csail.mit.edu/jiex/), [Wojciech Matusik](https://cdfg.csail.mit.edu/wojciech).*<br>
TOG 2022. [[PDF](https://arxiv.org/abs/2106.05306)] [[项目](https://people.csail.mit.edu/liyifei/publication/diffcloth-differentiable-cloth-simulator/)] [[代码](https://github.com/omegaiota/DiffCloth)]

**DIG：在人体上虚拟披挂隐式服装**<br>
*Ren Li, Benoît Guillard, Edoardo Remelli, Pascal Fua.*<br>
ACCV 2022. [[PDF](https://arxiv.org/abs/2209.10845)]

**SNUG：自监督神经动态服装**<br>
*Igor Santesteban, Miguel A. Otaduy, Dan Casas.*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2204.02219)] [[项目](http://mslab.es/projects/SNUG/)] [[代码](https://github.com/isantesteban/snug)]

**从显式到隐式的配准：从单张图像迈向高保真服装网格重建**<br>
*Heming Zhu, Lingteng Qiu, Yuda Qiu, Xiaoguang Han.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15007)] [[项目](https://kv2000.github.io/2022/03/28/reef/)]

**通过生成式 3D 服装模型进行自监督碰撞处理以实现虚拟试穿**<br>
*Igor Santesteban, Nils Thuerey, Miguel A. Otaduy, Dan Casas.*<br>
CVPR 2021. [[PDF](http://arxiv.org/abs/2105.06462)]

**动态神经服装**<br>
*[Meng Zhang](https://mengzephyr.com/), [Duygu Ceylan](http://www.duygu-ceylan.com/), [Tuanfeng Wang](http://geometry.cs.ucl.ac.uk/tuanfeng/), [Niloy J. Mitra](http://www0.cs.ucl.ac.uk/staff/n.mitra/).*<br>
TOG 2021. [[PDF](https://arxiv.org/)] [[项目](http://geometry.cs.ucl.ac.uk/projects/2021/DynamicNeuralGarments/)] [[代码](https://github.com/MengZephyr/DynamicNeuralGarments)]

**PBNS：用于无监督服装姿态空间变形的基于物理的神经模拟**<br>
*Hugo Bertiche, Meysam Madadi, Sergio Escalera.*<br>
SIGGRAPH Asia 2021. [[PDF](https://arxiv.org/abs/2012.11310)] [[项目](https://hbertiche.github.io/PBNS/)] [[代码](https://github.com/hbertiche/PBNS)]

**任何服装的深度细节增强**<br>
*Meng Zhang, Tuanfeng Wang, Duygu Ceylan, Niloy J. Mitra.*<br>
Eurographics 2021. [[PDF](https://arxiv.org/pdf/2008.04367.pdf)]

**用于单目人体动作捕捉的基于深度物理感知的布料变形推断**<br>
*Yue Li, Marc Habermann, Bernhard Thomaszewski, Stelian Coros, Thabo Beeler, Christian Theobalt.*<br>
3DV 2021. [[PDF](https://arxiv.org/abs/2011.12866)]

**神经非刚性跟踪**<br>
*Aljaž Božič, Pablo Palafox, Michael Zollhöfer, Angela Dai, Justus Thies, Matthias Nießner.*<br>
NeurIPS 2020. [[PDF](https://arxiv.org/abs/2006.13240)]

**SIZER：一个用于解析 3D 服装和学习尺寸敏感型 3D 服装的数据集与模型**<br>
*Garvita Tiwari, Bharat Lal Bhatnagar, Tony Tung, Gerard Pons-Moll.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.11610)]

**基于生成对抗网络（GAN）使用缝纫图案图像生成服装**<br>
*Yu Shen, Junbang Liang, Ming C. Lin.*<br>
ECCV 2020. [[PDF](http://cs.umd.edu/~liangjb/docs/ICCV2019.pdf)] [[项目](https://gamma.umd.edu/researchdirections/virtualtryon/garmentgeneration)] [[代码](https://github.com/williamljb/HumanMultiView)]

**Deep Fashion3D：一个用于从单张图像进行 3D 服装重建的数据集和基准**<br>
*Heming Zhu, Yu Cao, Hang Jin, Weikai Chen, Dong Du, Zhangye Wang, Shuguang Cui, Xiaoguang Han.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2003.12753)] [[项目](https://kv2000.github.io/2020/03/25/deepFashion3DRevisited/)]

**GarNet++：通过曲率损失改进快速准确的静态 3D 布料褶皱模拟**<br>
*Erhan Gundogdu, Victor Constantin, Shaifali Parashar, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/2007.10867)]

**均质化纱线级布料**<br>
*[Georg Sperl](https://pub.ist.ac.at/~gsperl/), Rahul Narain, Chris Wojtan.*<br>
SIGGRAPH (TOG) 2020. [[PDF](http://pub.ist.ac.at/group_wojtan/projects/2020_Sperl_HYLC/2020_HYLC_paper.pdf)] [[项目](http://visualcomputing.ist.ac.at/publications/2020/HYLC/)] [[Data & Code](http://pub.ist.ac.at/group_wojtan/projects/2020_Sperl_HYLC/2020_HYLC_data_code.zip)]

**CLOTH3D：着装的 3D 人体**<br>
*Hugo Bertiche, Meysam Madadi, Sergio Escalera.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/1912.02792)]

**CAPE：学习为 3D 人物穿着生成式服装**<br>
*[Qianli Ma](https://ps.is.tue.mpg.de/person/qma), Jinlong Yang, Anurag Ranjan, Sergi Pujades, Gerard Pons-Moll, Siyu Tang, [Michael J. Black](https://ps.is.tuebingen.mpg.de/person/black).*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.13615v2)] 	[[项目](http://ps.is.mpg.de/publications/cape-cvpr-20)]

**学习为 3D 人物穿着生成式服装**<br>
*Qianli Ma, Jinlong Yang, Anurag Ranjan, Sergi Pujades, Gerard Pons-Moll, Siyu Tang, Michael J. Black.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1907.13615)]

**虚拟裁缝：根据人体姿态、形状和服装风格预测 3D 服装**<br>
*Chaitanya Patel, Zhouyingcheng Liao, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.04583)]

**学习将纹理从服装图像转移到 3D 人体**<br>
*Aymen Mir, Thiemo Alldieck, Gerard Pons-Moll.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.02050)] [[代码](https://github.com/aymenmir1/pix2surf)]

**GarNet：用于快速准确 3D 布料褶皱模拟的双流网络**<br>
*[Erhan Gundogdu](https://egundogdu.github.io/), Victor Constantin, Amrollah Seifoddini, Minh Dang, Mathieu Salzmann, Pascal Fua.*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1811.10983)] [[补充材料](https://www.epfl.ch/labs/cvlab/wp-content/uploads/2019/04/GarNet_supplementary.pdf)] [[项目](https://cvlab.epfl.ch/research/garment-simulation/garnet/)] [[数据集](https://drive.switch.ch/index.php/s/7mAk9SoZ7J4uokt)]

**Multi - Garment Net：从图像学习为 3D 人物着装**<br>
*Bharat Lal Bhatnagar, Garvita Tiwari, Christian Theobalt, [Gerard Pons-Moll](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/people/gerard-pons-moll/)(REAL VIRTUAL HUMANS, MPII).*<br>
ICCV 2019. [[PDF](https://arxiv.org/abs/1908.06903)]

**DRAPE：为任何人着装**<br>
*Peng Guan, Loretta Reiss, David A. Hirshberg, Alexander Weiss, Michael J. Black.*<br>
TOG 2012. [[PDF](https://dl.acm.org/citation.cfm?doid=2185520.2185531)] [[项目](https://ps.is.tue.mpg.de/research_projects/drape-dressing-any-person)]

## 人体图像和视频生成 <a name='human-image-and-video-generation'></a>

**用于高效 3D 人体生成的高斯壳映射**<br>
*Rameen Abdal, Wang Yifan, Zifan Shi, Yinghao Xu, Ryan Po, Zhengfei Kuang, Qifeng Chen, Dit-Yan Yeung, Gordon Wetzstein.*<br> 
CVPR 2024. [[PDF](http://arxiv.org/abs/2311.17857)] [[项目](https://rameenabdal.github.io/GaussianShellMaps/)]

**HyperHuman：通过潜在结构扩散生成超逼真人体**<br>
*Xian Liu, Jian Ren, Aliaksandr Siarohin, Ivan Skorokhodov, Yanyu Li, Dahua Lin, Xihui Liu, Ziwei Liu, Sergey Tulyakov.*<br> 
ICLR 2024. [[PDF](http://arxiv.org/abs/2310.08579)] [[项目](https://snap-research.github.io/HyperHuman/)]

**VeRi3D：用于 3D 可控人体图像合成的基于生成式顶点的辐射场**<br>
*Xinya Chen, Jiaxin Huang, Yanrui Bin, Lu Yu, Yiyi Liao.*<br> 
ICCV 2023. [[PDF](http://arxiv.org/abs/2309.04800)]

**UnitedHuman：利用多源数据进行高分辨率人体生成**<br>
*Jianglin Fu, Shikai Li, Yuming Jiang, Kwan-Yee Lin, Wayne Wu, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2309.14335)] [[项目](https://unitedhuman.github.io/)] [[Github](https://github.com/UnitedHuman/UnitedHuman)] 

**Text2Performer：文本驱动的人体视频生成**<br>
*Yuming Jiang, Shuai Yang, Tong Liang Koh, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
ICCV 2023. [[PDF](https://arxiv.org/pdf/2304.08483.pdf)] [[项目](https://yumingj.github.io/projects/Text2Performer.html)] [[代码](https://github.com/yumingj/Text2Performer)]

**从 2D 图像集合进行文本引导的 3D 人体生成**<br>
*Tsu-Jui Fu, Wenhan Xiong, Yixin Nie, Jingyu Liu, Barlas Oğuz, William Yang Wang.*<br> 
EMNLP 2023 (Findings). [[PDF](http://arxiv.org/abs/2305.14312)] [[项目](https://text-3dh.github.io/)]

**用于可控人物图像合成的基于交叉注意力的风格分布**<br>
*Xinyue Zhou, Mingyu Yin, Xinyuan Chen, Li Sun, Changxin Gao, Qingli Li.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2208.00712)] 

**StyleGAN - Human：以数据为中心的人体生成探索**<br>
*Jianglin Fu, Shikai Li, [Yuming Jiang](https://yumingj.github.io/), [Kwan-Yee Lin](https://kwanyeelin.github.io/), [Chen Qian](https://scholar.google.com/citations?user=AerkT0YAAAAJ&hl=zh-CN), [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/), [Wayne Wu](https://dblp.org/pid/50/8731.html), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2204.11823)] [[代码](https://youtu.be/nIrb9hwsdcI)] [[项目](https://stylegan-human.github.io/)] [[Colab Demo](https://colab.research.google.com/drive/1sgxoDM55iM07FS54vz9ALg1XckiYA2On)] [[Hugging Face Demo](https://huggingface.co/spaces/hysts/StyleGAN-Human)]

**Text2Human：文本驱动的可控人体图像生成**<br>
*Yuming Jiang, Shuai Yang, Haonan Qiu, Wayne Wu, Chen Change Loy, Ziwei Liu.*<br>
SIGGRAPH 2022. [[PDF](https://arxiv.org/abs/2205.15996)] [[代码](https://github.com/yumingj/Text2Human)] [[项目](https://yumingj.github.io/projects/Text2Human.html)] 

**用于人物图像生成的自监督相关性挖掘网络**<br>
*Zijian Wang, Xingqun Qi, Kun Yuan, Muyi Sun.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_Self-Supervised_Correlation_Mining_Network_for_Person_Image_Generation_CVPR_2022_paper.html)] 

**BodyGAN：通用可控神经人体生成**<br>
*Chaojie Yang, Hanhui Li, Shengjie Wu, Shengkai Zhang, Haonan Yan, Nianhong Jiao, Jie Tang, Runnan Zhou, Xiaodan Liang, Tianxiang Zheng.*<br>
CVPR 2022. [[PDF](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_BodyGAN_General-Purpose_Controllable_Neural_Human_Body_Generation_CVPR_2022_paper.html)] 

**用于全身图像生成的 InsetGAN**<br>
*[Anna Frühstück](https://afruehstueck.github.io/), [Krishna Kumar Singh](http://krsingh.cs.ucdavis.edu/), [Eli Shechtman](https://research.adobe.com/person/eli-shechtman/), [Niloy J. Mitra](https://research.adobe.com/person/niloy-mitra/), [Peter Wonka](http://peterwonka.net/), [Jingwan Lu](https://research.adobe.com/person/jingwan-lu/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)] [[项目](http://afruehstueck.github.io/insetgan)]

**用于可控人物图像合成的神经纹理提取与分布**<br>
*Yurui Ren, Xiaoqing Fan, Ge Li, Shan Liu, Thomas H. Li.*<br>
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2203.10496)] [[代码](https://github.com/RenYurui/Neural-Texture-Extraction-Distribution)]

**用于可控人物图像合成的神经纹理提取与分布**<br>
*Pengze Zhang, Lingxiao Yang, Jianhuang Lai, Xiaohua Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.02910)]

**用于人物图像合成的结构变换纹理增强网络**<br>
*Munan Xu, Yuanqi Chen, Shan Liu, Thomas H. Li, Ge Li.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Xu_Structure-Transformed_Texture-Enhanced_Network_for_Person_Image_Synthesis_ICCV_2021_paper.html)]

**PISE：使用解耦生成对抗网络进行人物图像合成与编辑**<br>
*[Jinsong Zhang](https://zhangjinso.github.io/), [Kun Li](http://cic.tju.edu.cn/faculty/likun/), [Yu-Kun Lai](http://users.cs.cf.ac.uk/Yukun.Lai/), [Jingyu Yang](http://tju.iirlab.org/).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.04023)] [[项目](http://cic.tju.edu.cn/faculty/likun/projects/PISE/)] [[代码](https://github.com/Zhangjinso/PISE)]

**用于人物图像生成的 XingGAN**<br>
*[Hao Tang](http://disi.unitn.it/~hao.tang/), Song Bai, Li Zhang, Philip H. S. Torr, Nicu Sebe.*<br>
ECCV 2020.  [[代码](https://github.com/Ha0Tang/XingGAN)]

**用于人物图像生成的渐进式姿态注意力转移**<br> 
*Zhen Zhu, Tengteng Huang, Baoguang Shi, Miao Yu, Bofei Wang, Xiang Bai.*<br> 
CVPR 2019 (oral). [[PDF](https://arxiv.org/abs/1904.03349)] [[代码](https://github.com/tengteng95/Pose-Transfer.git)]

**使用外观感知姿态风格化器生成人物图像**<br>
*Siyu Huang, Haoyi Xiong, Zhi-Qi Cheng, Qingzhong Wang, Xingran Zhou, Bihan Wen, Jun Huan, Dejing Dou.*<br>
IJCAI 2020. [[PDF](https://arxiv.org/abs/2007.09077)] [[代码](https://github.com/siyuhuang/PoseStylizer)]

## 基于图像的虚拟试穿 <a name='image-based-virtual-try-on'></a>

[[Awesome Virtual Try-on (VTON)](https://github.com/minar09/awesome-virtual-try-on)]

**FashionTex：基于文本和纹理的可控虚拟试穿**<br>
*Anran Lin, Nanxuan Zhao, Shuliang Ning, Yuda Qiu, Baoyuan Wang, Xiaoguang Han.*<br> 
SIGGRAPH 2023. [[PDF](http://arxiv.org/abs/2305.04451)]

**TryOnDiffusion：两个 U - Net 的故事**<br>
*[Luyang Zhu](https://homes.cs.washington.edu/~lyzhu/), [Dawei Yang](http://www-personal.umich.edu/~ydawei/), [Tyler Zhu](https://research.google/people/TylerZhu/), [Fitsum Reda](https://fitsumreda.github.io/), [William Chan](http://williamchan.ca/), [Chitwan Saharia](https://scholar.google.co.in/citations?user=JApued4AAAAJ&hl=en), [Mohammad Norouzi](https://norouzi.github.io/), [Ira Kemelmacher-Shlizerman](https://www.irakemelmacher.com/).*<br>
CVPR 2023. [[PDF](https://arxiv.org/abs/2306.08276)] [[项目](https://tryondiffusion.github.io/)]

**在处理错位和遮挡条件下的高分辨率虚拟试穿**<br>
*Sangyun Lee, Gyojung Gu, Sunghyun Park, Seunghwan Choi, Jaegul Choo.*<br>
ECCV 2022. [[PDF](https://arxiv.org/pdf/2206.14180.pdf)] [[项目](https://koo616.github.io/HR-VITON/)] [[代码](https://github.com/sangyun884/HR-VITON)]

**通过可变形注意力流实现单阶段虚拟试穿**<br>
*Shuai Bai, Huiling Zhou, Zhikang Li, Chang Zhou, Hongxia Yang.*<br>
ECCV 2022. [[PDF](https://arxiv.org/abs/2207.09161)]

**MGN：用于无解析器虚拟试穿的区域掩码引导网络**<br>
*Chao Lin, Zhao Li, Sheng Zhou, Shichang Hu, Jialun Zhang, Linhao Luo, Jiarun Zhang, Longtao Huang, Yuan He.*<br>
IJCAI 2022. [[PDF](https://arxiv.org/abs/2204.11258)]

**ClothFormer：在所有模块中处理视频虚拟试穿**<br> 
*Jianbin Jiang, Tan Wang, He Yan, Junhui Liu.*<br> 
CVPR 2022 (oral). [[PDF](https://arxiv.org/abs/2204.07154)] [[项目](https://arxiv.org/abs/2204.12151)]

**基于风格的全局外观流用于虚拟试穿**<br>
*Sen He, Yi-Zhe Song, Tao Xiang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2204.01046)] 

**通过观看舞蹈视频实现野外着装**<br>
*Xin Dong, Fuwei Zhao, Zhenyu Xie, Xijin Zhang, Daniel K. Du, Min Zheng, Xiang Long, Xiaodan Liang, Jianchao Yang.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.15320)] [[项目](https://awesome-wflow.github.io/)]

**CIT：用于虚拟试穿的布料交互 Transformer**<br>
*[Bin Ren](https://scholar.google.com/citations?user=Md9maLYAAAAJ&hl=en), Hao Tang, Fanyang Meng, Runwei Ding, Ling Shao, Philip H.S. Torr, Nicu Sebe.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2104.05519)] [[代码](https://github.com/Amazingren/CIT)]

**弱监督高保真服装模型生成**<br>
*Ruili Feng, Cheng Ma, Chengji Shen, Xin Gao, Zhenjiang Liu, Xiaobo Li, Kairi Ou, Zhengjun Zha.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2112.07200)]

**WAS - VTON：用于虚拟试穿网络的变形架构搜索**<br>
*Zhenyu Xie, Xujie Zhang, Fuwei Zhao, Haoye Dong, Michael C. Kampffmeyer, Haonan Yan, Xiaodan Liang.*<br>
ACM MM 2021. [[PDF](https://arxiv.org/abs/2108.00386)] 

**通过补丁路由空间自适应生成对抗网络实现可扩展的无配对虚拟试穿**<br>
*Zhenyu Xie, Zaiyu Huang, Fuwei Zhao, Haoye Dong, Michael Kampffmeyer, Xiaodan Liang.*<br>
NeurIPS 2021. [[PDF](https://arxiv.org/abs/2111.10544)] [[代码](https://github.com/xiezhy6/PASTA-GAN)]

**ZFlow：基于门控外观流且带有 3D 先验的虚拟试穿**<br>
*Ayush Chopra, Rishabh Jain, Mayur Hemani, Balaji Krishnamurthy.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2109.07001)]

**有序着装：用于姿态转移、虚拟试穿及服装编辑的循环式人物图像生成**<br>
*Aiyu Cui, Daniel McKee, Svetlana Lazebnik.**<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Cui_Dressing_in_Order_Recurrent_Person_Image_Generation_for_Pose_Transfer_ICCV_2021_paper.html)]

**FashionMirror：具有顺序模板姿态的协同注意力特征重映射虚拟试穿**<br>
*Chieh-Yun Chen, Ling Lo, Pin-Jui Huang, Hong-Han Shuai, Wen-Huang Cheng.*<br>
ICCV 2021. [[PDF](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_FashionMirror_Co-Attention_Feature-Remapping_Virtual_Try-On_With_Sequential_Template_Poses_ICCV_2021_paper.html)]

**M3D - VTON：从单目到 3D 的虚拟试穿网络**<br>
*Fuwei Zhao, Zhenyu Xie, Michael Kampffmeyer, Haoye Dong, Songfang Han, Tianxiang Zheng, Tao Zhang, Xiaodan Liang.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2108.05126)]

**内衣模型的形状可控虚拟试穿**<br>
*Xin Gao, Zhenjiang Liu, Zunlei Feng, Chengji Shen, Kairi Ou, Haihong Tang, Mingli Song.*<br>
ACM MM 2021. [[PDF](https://arxiv.org/abs/2107.13156)]

**TryOnGAN：通过分层插值实现人体感知的试穿**<br>
*[Kathleen M Lewis](https://katiemlewis.github.io/), [Srivatsan Varadharajan](https://www.linkedin.com/in/srivatsan-varadharajan-9a570818), [Ira Kemelmacher-Shlizerman](https://www.irakemelmacher.com/).*<br>
TOG 2021. [[PDF](https://arxiv.org/abs/2101.02285)] [[项目](https://tryongan.github.io/tryongan/)] [[Demo](https://tryongan.github.io/tryongan/demo_rewrite.html)]

**VOGUE：通过 StyleGAN 插值优化实现试穿**<br>
*[Kathleen M Lewis](https://katiemlewis.github.io/), [Srivatsan Varadharajan](https://www.linkedin.com/in/srivatsan-varadharajan-9a570818), [Ira Kemelmacher-Shlizerman](https://sites.google.com/view/irakemelmacher/home).*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2101.02285)] [[项目](https://vogue-try-on.github.io/)] [[代码](https://github.com/Charmve/VOGUE-Try-On)]

**有序着装：用于姿态转移、虚拟试穿和服装编辑的循环人物图像生成**<br>
*Aiyu Cui, Daniel McKee, Svetlana Lazebnik.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2104.07021)] [[代码](https://github.com/cuiaiyu/dressing-in-order)]

**注重细节以实现准确逼真的服装可视化**<br>
*Kedan Li, Min Jin Chong, Jeffrey Zhang, Jingen Liu.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2106.06593)] [[Demo](https://revery.ai/demo.html)]

**VITON - HD：通过错位感知归一化实现高分辨率虚拟试穿**<br>
*Seunghwan Choi, Sunghyun Park, Minsoo Lee, Jaegul Choo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.16874)]

**VITON - HD：通过错位感知归一化实现高分辨率虚拟试穿**<br>
*Kripasindhu Sarkar, Lingjie Liu, Vladislav Golyanik, Christian Theobalt.*<br>
CVPR 2021. [[PDF](https://arxiv.org/pdf/2103.06902.pdf)] [[项目](http://gvv.mpi-inf.mpg.de/projects/HumanGAN/)]

**DCTON：用于高度逼真虚拟试穿的解耦循环一致性**<br>
*Chongjian Ge, Yibing Song, Yuying Ge, Han Yang, Wei Liu, and Ping Luo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.09479)] [[代码](https://github.com/ChongjianGE/DCTON)]

**PF - AFN：通过提炼外观流实现无解析器虚拟试穿**<br>
*Yuying Ge, Yibing Song, Ruimao Zhang, Chongjian Ge, Wei Liu, Ping Luo.*<br>
CVPR 2021. [[PDF](https://arxiv.org/abs/2103.04559)] [[代码](https://github.com/geyuying/PF-AFN)] 

**通过语义引导优化实现无模板试穿图像合成**<br>
*Chien-Lung Chou, Chieh-Yun Chen, Chia-Wei Hsieh, Hong-Han Shuai, Jiaying Liu, Wen-Huang Cheng.*<br>
TNNLS 2021. [[PDF](https://arxiv.org/abs/2102.03503)]

**通过语义解析变换实现无配对人物图像生成**<br>
*Sijie Song, Wei Zhang, Jiaying Liuv, Zongming Guo, Tao Mei.*<br>
TPAMI 2020. [[PDF](https://arxiv.org/abs/1912.06324)] [[CVPR 2019](https://arxiv.org/abs/1904.03379)] [[TPAMI 2020](https://ieeexplore.ieee.org/document/9085915/authors#authors)] [[代码](https://github.com/JDAI-CV/Down-to-the-Last-Detail-Virtual-Try-on-with-Detail-Carving)]

**无需掩码时不掩码：无解析器虚拟试穿**<br>
*Thibaut Issenhuth, Jérémie Mary, Clément Calauzènes.*<br>
ECCV 2020. [[PDF](https://arxiv.org/abs/2007.02721)]

**用于参数化虚拟试穿的全卷积图神经网络**<br>
*Raquel Vidaurre, Igor Santesteban, Elena Garces, Dan Casas.*<br>
ACM MM 2020. [[PDF](https://arxiv.org/abs/2009.04592)] [[项目](http://mslab.es/projects/FullyConvolutionalGraphVirtualTryOn)]

**通过自适应生成保留图像内容迈向逼真虚拟试穿**<br>
*Han Yang, Ruimao Zhang, Xiaobao Guo, Wei Liu, Wangmeng Zuo, Ping Luo.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2003.05863)] [[代码](https://github.com/switchablenorms/DeepFashion_Try_On)]

**PSGAN：用于可定制妆容转移的姿态和表情鲁棒空间感知生成对抗网络**<br>
*Wentao Jiang, Si Liu, Chen Gao, Jie Cao, Ran He, Jiashi Feng, Shuicheng Yan.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/1909.06956)]

**GarmentGAN：逼真的对抗式时尚转移**<br>
*Amir Hossein Raffiee, Michael Sollami.*<br>
ICPR 2020. [[PDF](https://arxiv.org/abs/2003.01894)]

**SieveNet：一个用于稳健基于图像虚拟试穿的统一框架**<br>
*Surgan Jandial, Ayush Chopra, Kumar Ayush, Mayur Hemani, Abhijeet Kumar, Balaji Krishnamurthy.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2001.06265)] [[代码](https://github.com/levindabhi/SieveNet)]

**TailorGAN：制作用户定义的时尚设计**<br>
*Lele Chen, Justin Tian, Guo Li, Cheng-Haw Wu, Erh-Kan King, Kuan-Ting Chen, Shao-Hang Hsieh.*<br>
WACV 2020. [[PDF](https://arxiv.org/abs/2001.06427)] [[代码](https://github.com/gli-27/TailorGAN)]

**ClothFlow：用于着装人物生成的基于流的模型**<br>
*Xintong Han, Xiaojun Hu, Weilin Huang, Matthew R. Scott.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/html/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.html)]

**VTNFP：一个保留人体和服装特征的基于图像的虚拟试穿网络**<br>
*Ruiyun Yu, Xiaoqi Wang, Xiaohui Xie.*<br>
ICCV 2019. [[PDF](https://openaccess.thecvf.com/content_ICCV_2019/html/Yu_VTNFP_An_Image-Based_Virtual_Try-On_Network_With_Body_and_Clothing_ICCV_2019_paper.html)]

**迈向保留特征的基于图像的虚拟试穿网络**<br>
*Bochao Wang, Huabin Zheng, Xiaodan Liang, Yimin Chen, Liang Lin, Meng Yang.*<br>
ECCV 2018. [[PDF](https://arxiv.org/abs/1807.07688)]

## 人体重塑 <a name='human-body-reshaping'></a>

**用于人体重塑的结构感知流生成**<br>
*[Jianqiang Ren](https://github.com/JianqiangRen), Yuan Yao, Biwen Lei, Miaomiao Cui, Xuansong Xie.*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.04670)] [[代码](https://github.com/JianqiangRen/FlowBasedBodyReshaping)]

**人体实时重塑**<br>
*Michal Richter, Kiran Varanasi, Nils Hasler, Christian Theobalt.*<br>
International Conference on 3D Imaging, Modeling, Processing, Visualization & Transmission, 2012. [[PDF](https://vcai.mpi-inf.mpg.de/files/3DimPVT/human_reshape.pdf)]

**MovieReshape：视频中人体的跟踪与重塑**<br>
*Arjun Jain, Thorsten Thormählen, Hans-Peter Seidel, Christian Theobalt.*<br>
SIGGRAPH Asia 2010. [[PDF](http://www.mpi-inf.mpg.de/resources/MovieReshape/MovieReshape.pdf)] [[项目](https://resources.mpi-inf.mpg.de/MovieReshape/)]

**图像中人体的参数化重塑**<br>
*Shizhe Zhou, Hongbo Fu,  Ligang Liu, Daniel Cohen-Or, Xiaoguang Han.*<br>
SIGGRAPH 2010. [[PDF](https://dl.acm.org/doi/10.1145/1833349.1778863)]

### 场景上下文感知的人体生成

**将人置于合适位置：基于场景感知的人体插入**<br>
*Sumith Kulal, Tim Brooks, Alex Aiken, Jiajun Wu, Jimei Yang, Jingwan Lu, Alexei A. Efros, Krishna Kumar Singh.*<br> 
CVPR 2023. [[PDF](http://arxiv.org/abs/2304.14406)] [[项目](https://sumith1896.github.io/affordance-insertion/)]

**在无人场景中生成 3D 人物**<br>
*Yan Zhang, Mohamed Hassan, Heiko Neumann, Michael J. Black, Siyu Tang.*<br> 
CVPR 2020. [[PDF](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhang_Generating_3D_People_in_Scenes_Without_People_CVPR_2020_paper.html)] [[代码](https://github.com/yz-cnsdqz/PSI-release)]

### 人体网格恢复

**GLAMR：基于动态相机的全局遮挡感知人体网格恢复**<br>
*[Ye Yuan](https://www.ye-yuan.com/), [Umar Iqbal](http://www.umariqbal.info/), [Pavlo Molchanov](https://research.nvidia.com/person/pavlo-molchanov/), [Kris Kitani](http://www.cs.cmu.edu/~kkitani/), [Jan Kautz](https://jankautz.com/).*<br>
CVPR 2022 (Oral). [[PDF](https://arxiv.org/abs/2112.01524)] [[项目](https://nvlabs.github.io/GLAMR)] [[代码](https://github.com/NVlabs/GLAMR)]

**Shapy：使用度量和语义属性进行准确的 3D 人体形状回归**<br>
*Vasileios Choutas, Lea Muller, Chun-Hao P. Huang, Siyu Tang, Dimitrios Tzionas, Michael J. Black.*<br> 
CVPR 2022. [[PDF](http://arxiv.org/abs/2206.07036)] [[项目](https://shapy.is.tue.mpg.de/)] [[代码](https://github.com/muelea/shapy)]

**PoseScript：从自然语言生成 3D 人体姿态**<br>
*Ginger Delmas, Philippe Weinzaepfel, Thomas Lucas, Francesc Moreno-Noguer, Grégory Rogez.*<br> 
ECCV 2022. [[PDF](http://arxiv.org/abs/2210.11795)] [[代码](https://github.com/naver/posescript)]

### 以人为中心的感知

**用于以人体为中心感知的通用多模态预训练**<br>
*[Fangzhou Hong](https://hongfz16.github.io/), [Liang Pan](), [Zhongang Cai](), [Ziwei Liu](https://liuziwei7.github.io/).*<br>
CVPR 2022. [[PDF](https://arxiv.org/abs/2203.13815)] [[代码](https://github.com/hongfz16/HCMoCo)] [[项目](https://hongfz16.github.io/projects/HCMoCo.html;)]

### 挑战赛与研讨会
- KDD（国际知识发现和数据挖掘大会）时尚领域研讨会 [[2019]](https://kddfashion2019.mybluemix.net/) [[2018]](https://kddfashion2018.mybluemix.net/) [[2017]](https://kddfashion2017.mybluemix.net/) [[2016]](http://kddfashion2016.mybluemix.net/)
- 时尚、艺术与设计领域的计算机视觉研讨会 [[CVPR 2020]](https://sites.google.com/view/cvcreative2020) [[ICCV 2019]](https://sites.google.com/view/cvcreative/home) [[ECCV 2018]](https://sites.google.com/view/eccvfashion/) [[ICCV 2017]](https://sites.google.com/zalando.de/cvf-iccv2017/home?authuser=0)
- NeurIPS（神经信息处理系统大会）《机器学习助力创意与设计》研讨会 [[2019]](https://neurips2019creativity.github.io/) [[2018]](https://nips2018creativity.github.io/) [[2017]](https://nips2017creativity.github.io/)
- SIGIR（国际计算机学会信息检索大会）电子商务研讨会 [[2019]](https://sigir-ecom.github.io/index.html) [[2018]](https://sigir-ecom.github.io/ecom2018/index.html) [[2017]](http://sigir-ecom.weebly.com/) 
- CVPR（计算机视觉与模式识别会议）《深度学习用于内容创作》教程  [[2019]](https://nvlabs.github.io/dl-for-content-creation/)
- iMaterialist 时尚挑战赛 [[CVPR 2019]](https://sites.google.com/view/fgvc6/competitions/imat-fashion-2019)
- iDesigner挑战赛 [[CVPR 2019]](https://sites.google.com/view/fgvc6/competitions/idesigner-2019)
- 时尚生成挑战赛 [[ICCV 2019, ECCV 2018]](https://fashion-gen.com/)
- 京东 AI 时尚挑战赛 [[ChinaMM 2018]](https://fashion-challenge.github.io/)
- 阿里巴巴时尚 AI 全球挑战赛 [[Tianchi]](http://fashionai.alibaba.com/)
- 时尚与纺织领域 AI 会议 [[AIFT 2018]](https://www.polyu.edu.hk/itc/aift2018/)
- 时尚 IQ 挑战赛 [[CVPR 2020]](https://sites.google.com/view/cvcreative2020/fashion-iq?authuser=0) [[ICCV 2019]](https://sites.google.com/view/lingir/fashion-iq)
- 深度时尚 2 挑战赛 [[CVPR 2020]](https://sites.google.com/view/cvcreative2020/deepfashion2?authuser=0) [[ICCV 2019]](https://sites.google.com/view/cvcreative/deepfashion2)

### 数据集
- WildAvatar (2024). [[Website]](https://arxiv.org/pdf/2407.02165)
- Fashionpedia. [[Website]](https://fashionpedia.github.io/home/index.html)
- DeepFashion2 Dataset. [[Website]](<https://github.com/switchablenorms/DeepFashion2>)
- DeepFashion Dataset. [[Website]](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html)
- FashionGen. [[Website]](https://fashion-gen.com/)
- FashionAI. [[Tianchi]](http://fashionai.alibaba.com/datasets/?spm=a2c22.11190735.991137.8.501b6d83ilPJsX)
- TaobaoClothMatch. [[Tianchi]](TaobaoClothMatch)
- Fashion-MNIST. [[Fashion-MNIST]](https://github.com/zalandoresearch/fashion-mnist)
- Fashion IQ. [[Website]](https://www.spacewu.com/posts/fashion-iq/)
- NTURGBD-Parsing-4K Dataset. [[Website](https://github.com/hongfz16/HCMoCo)]

## 时装设计 <a id='garment-design'></a>

**用于人体运动的弹性可控 4D 针织服装**<br>
*[Zishun Liu](https://github.com/zishun), Xingjian Han, Yuchen Zhang, Xiangjia Chen, Yukun Lai, Eugeni L. Doubrovski, Emily Whiting, Charlie C.L. Wang.*<br>
TOG 2021. [[PDF](https://1drv.ms/b/s!AsZuzkRqeoh6gsUNhZKQ0bRp-BDaJQ?e=XIegdJ)] [[项目](https://zishun.github.io/projects/Knitting4D/)]

**基于生成对抗网络的服装设计**<br>
*Chenxi Yuan, Mohsen Moghaddam.*<br>
KDD workshop on AdvML 2020. [[PDF](https://arxiv.org/abs/2007.10947)] 

## <a name='fashion-style-influences'></a>时尚风格影响因素

**从巴黎到柏林：探寻全球时尚风格的相互影响**<br>
*Ziad Al-Halah, Kristen Grauman.*<br>
CVPR 2020. [[PDF](https://arxiv.org/abs/2004.01316)]

**从文化到服饰：探寻一个世纪时尚影像背后的世界大事**<br>
*Wei-Lin Hsiao, Kristen Grauman.*<br>
ICCV 2021. [[PDF](https://arxiv.org/abs/2102.01690)]

## 团队与成员<a name='team-and-people'></a>

- [真是虚拟人](http://virtualhumans.mpi-inf.mpg.de/), **马克斯·普朗克信息学研究所**, by [Gerard Pons-Moll](http://virtualhumans.mpi-inf.mpg.de/people/pons-moll.html).
- [感知系统，图宾根校区](http://ps.is.tuebingen.mpg.de/), **马克斯·普朗克智能系统研究所**, by [Michael Black](http://ps.is.tuebingen.mpg.de/person/black).
- [视觉计算实验室b](https://niessnerlab.org/opening.html), **慕尼黑工业大学 (TUM)**, [Prof. Dr. Matthias Nießner](https://niessnerlab.org/members/matthias_niessner/profile.html) 及其[团队](https://niessnerlab.org/team.html).
- [宽带网络与数字媒体实验室](http://www.liuyebin.com/student.html), 自动化系, **清华大学**, [Yebin Liu](http://www.liuyebin.com/).
- [视觉与图形实验室](https://ict.usc.edu/), **南加州大学**,  [Hao Li](http://hao-li.com/Hao_Li/Hao_Li_-_publications.html).

## 数据集<a name='dataset'></a>

- `SMPL`。要下载 [SMPL-X](https://smpl-x.is.tue.mpg.de/)、[SMPL+H](http://mano.is.tue.mpg.de/) 以及 SMPL（[男性、女性](http://smpl.is.tue.mpg.de/)、[中性模型](http://smplify.is.tue.mpg.de/)），请访问该项目网站并注册，以获得下载权限。[代码](https://github.com/vchoutas/smplx#loading-smpl-x-smplh-and-smpl)

- `清华人体数据集（THUmanDataset）`。[THUman](https://github.com/ZhengZerong/DeepHuman/tree/master/THUmanDataset) 是一个三维真实人体模型数据集，包含约7000个模型。

- `AGORA`。AGORA 于 2021 年 CVPR（计算机视觉与模式识别会议）的一篇[论文](https://openaccess.thecvf.com/content/CVPR2021/papers/Patel_AGORA_Avatars_in_Geography_Optimized_for_Regression_Analysis_CVPR_2021_paper.pdf)中提出，由 4240 次扫描构成，涵盖 350 多个不同个体，所有扫描都匹配了 SMPL-X 模型。

## 应用<a name="applications"></a>

### 健身训练

**AIFit：用于健身训练的自动三维人体可解释反馈模型。**<br>
*Mihai Fieraru, Mihai Zanfir, Silviu-Cristian Pirlea, Vlad Olaru, Cristian Sminchisescu.*<br>
CVPR 2021. [[PDF](https://openaccess.thecvf.com/content/CVPR2021/papers/Fieraru_AIFit_Automatic_3D_Human-Interpretable_Feedback_Models_for_Fitness_Training_CVPR_2021_paper.pdf)] [[项目](http://vision.imar.ro/fit3d/)]
