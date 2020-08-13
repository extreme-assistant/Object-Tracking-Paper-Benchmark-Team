# 2019-2020年目标跟踪资源全汇总（论文、模型代码、优秀实验室）

## 目录
[1. 顶会论文](#100)<br>
* [1.1. CVPR2020](#101)<br>
* [1.2. ECCV2020](#102)<br>
* [1.3. CVPR2019](#103)<br>
* [1.4. ICCV2019 To do list](#104)<br>
[2.benchmark](#200)<br>
[3.实验室](#300))<br>


<br><br>

<a name="100"/>

## 1.顶会论文

<br><br>

<a name="101"/>

### [CVPR2020(共33篇)](https://bbs.cvmart.net/topics/2733)<br>
参考链接：https://mp.weixin.qq.com/s/IaizDEfvRc0JrLrF--P2eA<br><br>

#### 多目标跟踪

* 1.How to Train Your Deep Multi-Object Tracker<br>
作者｜Yihong Xu, Aljosa Osep, Yutong Ban, Radu Horaud, Laura Leal-Taixe, Xavier Alameda-Pineda<br>
论文｜https://arxiv.org/abs/1906.06618<br>
代码｜https://github.com/yihongXU/deepMOT<br><br>

* 2.[Learning a Neural Solver for Multiple Object Tracking](https://arxiv.org/abs/1912.07515)<br>
作者｜Guillem Braso, Laura Leal-Taixe<br>
代码｜https://github.com/dvl-tum/mot\_neural\_solver（PyTorch）<br><br>

* 3.[GNN3DMOT: Graph Neural Network for 3D Multi-Object Tracking With 2D-3D Multi-Feature Learning](https://arxiv.org/abs/2006.07327)<br>
作者｜Xinshuo Weng, Yongxin Wang, Yunze Man, Kris M. Kitani<br>
代码｜https://github.com/xinshuoweng/GNN3DMOT（PyTorch）<br><br>

* 4.[A Unified Object Motion and Affinity Model for Online Multi-Object Tracking](https://arxiv.org/abs/2003.11291)<br>
作者 | Junbo Yin, Wenguan Wang, Qinghao Meng, Ruigang Yang, Jianbing Shen<br>
单位 | 北京理工大学；苏黎世联邦理工学院；百度；IIAI等<br>
代码 | https://github.com/yinjunbo/UMA-MOT<br><br>

* 5.[Learning Multi-Object Tracking and Segmentation From Automatic Annotations](https://arxiv.org/abs/1912.02096)<br>
作者 | Lorenzo Porzi, Markus Hofinger, Idoia Ruiz, Joan Serrat, Samuel Rota Bulo, Peter Kontschieder<br>
单位 | Mapillary Research；格拉茨技术大学等<br><br>

* 6.[SQE: a Self Quality Evaluation Metric for Parameters Optimization in Multi-Object Tracking](https://arxiv.org/abs/2004.07472)<br>
作者 | Yanru Huang, Feiyu Zhu, Zheni Zeng, Xi Qiu, Yuan Shen, Jianan Wu<br>
单位 | 清华；旷视<br><br>

* 7.[RetinaTrack: Online Single Stage Joint Detection and Tracking](https://arxiv.org/abs/2003.13870)<br>
作者 | Zhichao Lu, Vivek Rathod, Ronny Votel, Jonathan Huang<br>
单位 | 谷歌<br><br>

#### 目标跟踪与分割
* 8.[State-Aware Tracker for Real-Time Video Object Segmentation](https://arxiv.org/abs/2003.00482)<br>
作者 | Xi Chen, Zuoxin Li, Ye Yuan, Gang Yu, Jianxin Shen, Donglian Qi<br>
单位 | 浙江大学；旷视<br>
代码 | https://github.com/XavierCHEN34/State-Aware-Tracker<br><br>

* 9.[Classifying, Segmenting, and Tracking Object Instances in Video with Mask Propagation](https://arxiv.org/abs/1912.04573)<br>
作者 | Gedas Bertasius, Lorenzo Torresani<br>
单位 | Facebook AI<br>
网站 | https://gberta.github.io/maskprop/<br><br>

* 10.[Fast Template Matching and Update for Video Object Tracking and Segmentation](https://arxiv.org/abs/2004.07538)<br>
作者 | Mingjie Sun, Jimin Xiao, Eng Gee Lim, Bingfeng Zhang, Yao Zhao<br>
单位 | 西郊利物浦大学；利物浦大学；北京交通大学<br>
代码 |  https://github.com/insomnia94/FTMU<br><br>

* 11.[Video Instance Segmentation Tracking With a Modified VAE Architecture]（http://openaccess.thecvf.com/content_CVPR_2020/html/Lin_Video_Instance_Segmentation_Tracking_With_a_Modified_VAE_Architecture_CVPR_2020_paper.html）<br>
作者 | Chung-Ching Lin, Ying Hung, Rogerio Feris, Linglin He<br>
单位 | IBM Research AI；罗格斯大学<br><br>

* 12.[D3S - A Discriminative Single Shot Segmentation Tracker](http://openaccess.thecvf.com/content_CVPR_2020/html/Lukezic_D3S_-_A_Discriminative_Single_Shot_Segmentation_Tracker_CVPR_2020_paper.html)<br>
作者 | Alan Lukezic, Jiri Matas, Matej Kristan<br>
单位 | 卢布尔雅那大学等<br><br>

* 13.[MAST: A Memory-Augmented Self-Supervised Tracker](http://openaccess.thecvf.com/content_CVPR_2020/html/Lai_MAST_A_Memory-Augmented_Self-Supervised_Tracker_CVPR_2020_paper.html)<br>
作者 | Zihang Lai, Erika Lu, Weidi Xie<br>
单位 | 牛津大学<br>
代码 | https://github.com/zlai0/MAST<br><br>

#### 单目标跟踪

* 14.[SiamCAR: Siamese Fully Convolutional Classification and Regression for Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Guo_SiamCAR_Siamese_Fully_Convolutional_Classification_and_Regression_for_Visual_Tracking_CVPR_2020_paper.html)(Oral)<br>
作者 | Dongyan Guo, Jun Wang, Ying Cui, Zhenhua Wang, Shengyong Chen<br>
单位 | 浙江大学；天津大学<br>
代码 | https://github.com/ohhhyeahhh/SiamCAR<br><br>

* 15.[Siamese Box Adaptive Network for Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Siamese_Box_Adaptive_Network_for_Visual_Tracking_CVPR_2020_paper.html)<br>
作者 | Zedu Chen, Bineng Zhong, Guorong Li, Shengping Zhang, Rongrong Ji<br>
单位 | 华侨大学；国科大；哈工大；鹏城实验室；厦门大学；南理工<br>
代码 | https://github.com/hqucv/siamban<br><br>

* 16.[Deformable Siamese Attention Networks for Visual Object Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Yu_Deformable_Siamese_Attention_Networks_for_Visual_Object_Tracking_CVPR_2020_paper.html)<br>
作者 | Yuechen Yu, Yilei Xiong, Weilin Huang, Matthew R. Scott<br>
单位 | 深圳码隆科技<br><br>

* 17.[Correlation-Guided Attention for Corner Detection Based Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Du_Correlation-Guided_Attention_for_Corner_Detection_Based_Visual_Tracking_CVPR_2020_paper.html)<br>
作者 | Fei Du, Peng Liu, Wei Zhao, Xianglong Tang<br>
单位 | 哈工大<br><br>

* 18.[Siam R-CNN: Visual Tracking by Re-Detection](http://openaccess.thecvf.com/content_CVPR_2020/html/Voigtlaender_Siam_R-CNN_Visual_Tracking_by_Re-Detection_CVPR_2020_paper.html)<br>
作者 | Paul Voigtlaender, Jonathon Luiten, Philip H.S. Torr, Bastian Leibe<br>
单位 | 亚琛工业大学；牛津大学<br>
代码 | http://www.vision.rwth-aachen.de/page/siamrcnn<br><br>

* 19.[Probabilistic Regression for Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Danelljan_Probabilistic_Regression_for_Visual_Tracking_CVPR_2020_paper.html)<br>
作者 | Martin Danelljan, Luc Van Gool, Radu Timofte<br>
单位 | 苏黎世联邦理工学院<br>
代码 | https://github.com/visionml/pytracking<br><br>

* 20.[Recursive Least-Squares Estimator-Aided Online Learning for Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Gao_Recursive_Least-Squares_Estimator-Aided_Online_Learning_for_Visual_Tracking_CVPR_2020_paper.html)(Oral)<br>
作者 | Jin Gao, Weiming Hu, Yan Lu<br>
单位 | 中科院自动化所；国科大；微软<br>
代码 | https://github.com/Amgao/RLS-RTMDNet<br><br>

* 21.[ROAM: Recurrently Optimizing Tracking Model](http://openaccess.thecvf.com/content_CVPR_2020/html/Yang_ROAM_Recurrently_Optimizing_Tracking_Model_CVPR_2020_paper.html)<br>
作者 | Tianyu Yang, Pengfei Xu, Runbo Hu, Hua Chai, Antoni B. Chan<br>
单位 | 腾讯AI；香港城市大学‘；滴滴<br>
代码 | https://github.com/skyoung/ROAM<br><br>

* 22.[One-Shot Adversarial Attacks on Visual Tracking With Dual Attention](http://openaccess.thecvf.com/content_CVPR_2020/html/Chen_One-Shot_Adversarial_Attacks_on_Visual_Tracking_With_Dual_Attention_CVPR_2020_paper.html)<br>
作者 | Xuesong Chen, Xiyu Yan, Feng Zheng, Yong Jiang, Shu-Tao Xia, Yong Zhao, Rongrong Ji<br>
单位 | 北大；清华；南方科技大学；鹏城实验室；厦门大学<br><br>

* 23.[AutoTrack: Towards High-Performance Visual Tracking for UAV With Automatic Spatio-Temporal Regularization](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_AutoTrack_Towards_High-Performance_Visual_Tracking_for_UAV_With_Automatic_Spatio-Temporal_CVPR_2020_paper.html)<br>
作者 | Yiming Li, Changhong Fu, Fangqiang Ding, Ziyuan Huang, Geng Lu<br>
单位 | 同济大学；新加坡国立大学；清华<br>
代码 | https://github.com/vision4robotics/AutoTrack<br><br>

#### 长期跟踪

* 24.[High-Performance Long-Term Tracking With Meta-Updater](http://openaccess.thecvf.com/content_CVPR_2020/html/Dai_High-Performance_Long-Term_Tracking_With_Meta-Updater_CVPR_2020_paper.html)(Oral)<br>
作者 | Kenan Dai, Yunhua Zhang, Dong Wang, Jianhua Li, Huchuan Lu, Xiaoyun Yang<br>
单位 | 大连理工大学；阿姆斯特丹大学；鹏城实验室等<br>
代码 | https://github.com/Daikenan/LTMU<br><br>

#### 3D目标跟踪

* 25.[P2B: Point-to-Box Network for 3D Object Tracking in Point Clouds](http://openaccess.thecvf.com/content_CVPR_2020/html/Qi_P2B_Point-to-Box_Network_for_3D_Object_Tracking_in_Point_Clouds_CVPR_2020_paper.html)<br>
作者 | Haozhe Qi, Chen Feng, Zhiguo Cao, Feng Zhao, Yang Xiao<br>
单位 | 华中科技大学<br>
代码 | https://github.com/HaozheQi/P2B<br><br>

* 26.[Joint Spatial-Temporal Optimization for Stereo 3D Object Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Joint_Spatial-Temporal_Optimization_for_Stereo_3D_Object_Tracking_CVPR_2020_paper.html)<br>
作者 | Peiliang Li, Jieqi Shi, Shaojie Shen<br>
单位 | 香港科技大学<br><br>

* 27.[PnPNet: End-to-End Perception and Prediction With Tracking in the Loop](http://openaccess.thecvf.com/content_CVPR_2020/html/Liang_PnPNet_End-to-End_Perception_and_Prediction_With_Tracking_in_the_Loop_CVPR_2020_paper.html)<br>
作者 | Ming Liang, Bin Yang, Wenyuan Zeng, Yun Chen, Rui Hu, Sergio Casas, Raquel Urtasun<br>
单位 | Uber ATG；多伦多大学<br>

#### 细胞跟踪

* 28.[MPM: Joint Representation of Motion and Position Map for Cell Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Hayashida_MPM_Joint_Representation_of_Motion_and_Position_Map_for_Cell_CVPR_2020_paper.html)<br>
作者 | Junya Hayashida, Kazuya Nishimura, Ryoma Bise<br>
单位 | 日本九州大学<br>
代码 | https://github.com/JunyaHayashida/MPM<br><br>

#### 目标跟踪鲁棒性研究

* 29.[Cooling-Shrinking Attack: Blinding the Tracker With Imperceptible Noises](http://openaccess.thecvf.com/content_CVPR_2020/html/Yan_Cooling-Shrinking_Attack_Blinding_the_Tracker_With_Imperceptible_Noises_CVPR_2020_paper.html)<br>
作者 | Bin Yan, Dong Wang, Huchuan Lu, Xiaoyun Yang<br>
单位 | 大连理工大学；鹏城实验室等<br>
代码 | https://github.com/MasterBin-IIAU/CSA<br><br>

####   可见光与红外图像的目标跟踪

* 30.[Cross-Modal Pattern-Propagation for RGB-T Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Cross-Modal_Pattern-Propagation_for_RGB-T_Tracking_CVPR_2020_paper.html)<br>
作者 | Chaoqun Wang, Chunyan Xu, Zhen Cui, Ling Zhou, Tong Zhang, Xiaoya Zhang, Jian Yang<br>
单位 | 南京理工大学<br><br>

####  基于多谱勒雷达非视线区域的目标检测与跟踪

* 31.[Seeing Around Street Corners: Non-Line-of-Sight Detection and Tracking In-the-Wild Using Doppler Radar](http://openaccess.thecvf.com/content_CVPR_2020/html/Scheiner_Seeing_Around_Street_Corners_Non-Line-of-Sight_Detection_and_Tracking_In-the-Wild_Using_CVPR_2020_paper.html)<br>
作者 | Nicolas Scheiner, Florian Kraus, Fangyin Wei, Buu Phan, Fahim Mannan, Nils Appenrodt, Werner Ritter, Jurgen Dickmann, Klaus Dietmayer, Bernhard Sick, Felix Heide<br>
单位 | 奔驰汽车公司;普林斯顿大学;Algolux;乌尔姆大学等<br><br>

#### 3D斑马鱼跟踪数据集

* 32.[3D-ZeF: A 3D Zebrafish Tracking Benchmark Dataset](http://openaccess.thecvf.com/content_CVPR_2020/html/Pedersen_3D-ZeF_A_3D_Zebrafish_Tracking_Benchmark_Dataset_CVPR_2020_paper.html)<br>
作者 | Malte Pedersen, Joakim Bruslund Haurum, Stefan Hein Bengtson, Thomas B. Moeslund<br>
单位 | 奥尔堡大学<br>
代码 | https://bitbucket.org/aauvap/3d-zef/src/master/<br><br>
网站 | https://vap.aau.dk/3d-zef/

#### 非刚体物体跟踪

* 33.[Learning to Optimize Non-Rigid Tracking](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Learning_to_Optimize_Non-Rigid_Tracking_CVPR_2020_paper.html)<br>
作者 | Yang Li, Aljaz Bozic, Tianwei Zhang, Yanli Ji, Tatsuya Harada, Matthias Niessner<br>
单位 | 东京大学；电子科技大学；日本理化学研究所RIKEN；慕尼黑工业大学<br><br>

<br>



<br><br>

<a name="102"/>


### [ECCV2020（共26篇）](https://bbs.cvmart.net/topics/3097)


* 1.[Segment as Points for Efficient Online Multi-Object Tracking and Segmentation](https://arxiv.org/abs/2007.01550)<br>
作者｜Zhenbo Xu, Wei Zhang, Xiao Tan, Wei Yang, Huan Huang, Shilei Wen, Errui Ding, Liusheng Huang<br>
代码｜https://github.com/detectRecog/PointTrack<br><br>

* 2.[Chained-Tracker: Chaining Paired Attentive Regression Results for End-to-End Joint Multiple-Object Detection and Tracking](https://arxiv.org/abs/2007.14557)<br>
作者｜Jinlong Peng, Changan Wang, Fangbin Wan, Yang Wu, Yabiao Wang, Ying Tai, Chengjie Wang, Jilin Li, Feiyue Huang, Yanwei Fu<br><br>

* 3.Tracking objects as points<br><br>

* 4.[TAO: A Large-scale Benchmark for Tracking Any Object](https://arxiv.org/abs/2005.10356)<br>
作者｜Achal Dave, Tarasha Khurana, Pavel Tokmakov, Cordelia Schmid, Deva Ramanan<br>
代码｜https://github.com/TAO-Dataset/tao<br><br>

* 5.[Weakly-Supervised Cell Tracking via Backward-and-Forward Propagation](http://arxiv.org/abs/2007.15258)<br>
作者｜Kazuya Nishimura, Junya Hayashida, Chenyang Wang, Dai Fei Elmer Ker, Ryoma Bise<br>
代码｜https://github.com/naivete5656/WSCTBFP <br><br>

* 6.[Towards End-to-end Video-based Eye-Tracking](https://arxiv.org/abs/2007.13120)<br>
作者｜Seonwook Park, Emre Aksan, Xucong Zhang, Otmar Hilliges<br>
代码｜https://ait.ethz.ch/projects/2020/EVE<br><br>

* 7.Unsupervised Video Object Segmentation with Joint Hotspot Tracking<br>

* 8.Learning Feature Embeddings for Discriminant Model based Tracking<br>

* 9.[Guessing State Tracking for Visual Dialogue](https://arxiv.org/abs/2002.10340)<br>
作者｜Wei Pang, Xiaojie Wang<br>
代码｜https://github.com/xubuvd/guesswhat<br><br>

* 10.[TRADI: Tracking deep neural network weight distributions](https://arxiv.org/abs/1912.11316)<br>
作者｜Gianni Franchi, Andrei Bursuc, Emanuel Aldea, Severine Dubuisson, Isabelle Bloch<br><br>

* 11.Deep Learning-based Pupil Center Detection for Fast and Accurate Eye Tracking System<br>
demo｜https://www.youtube.com/watch?v=8t2FLz_ucvs<br><br>

* 12.[Robust Tracking against Adversarial Attacks](https://arxiv.org/abs/2007.09919)<br>
作者｜Shuai Jia, Chao Ma, Yibing Song, Xiaokang Yang
<br><br>

* 13.[Self-supervised Keypoint Correspondences for Multi-Person Pose Estimation and Tracking in Videos](https://arxiv.org/abs/2004.12652)<br>
作者｜Umer Rafi, Andreas Doering, Bastian Leibe, Juergen Gall<br><br>

14. CLNet: A Compact Latent Network for Fast Adjusting Siamese Tracker<br><br>

* 15.[Learning Object-aware Anchor-free Networks for Real-time Object Tracking](https://arxiv.org/pdf/2006.10721.pdf)<br>
作者｜Zhipeng Zhang，Houwen Peng，Jianlong Fu，Bing Li，Weiming Hu<br>
代码｜https://github.com/researchmm/TracKit<br><br>

* 16.Object Tracking using Spatio-Temporal Networks for Future Prediction Location<br><br>

* 17.LC-VSLAM: Real-time Tracking and Bundle Adjustment in Line-Cloud<br><br>

* 18.[Challenge-Aware RGBT Tracking](https://arxiv.org/abs/2007.13143)<br>
作者｜Chenglong Li, Lei Liu, Andong Lu, Qing Ji, Jin Tang<br><br>

* 19.PG-Net: Pixel to Global Matching Network for Visual Tracking<br><br>


* 20.[Temporal Keypoint Matching and Refinement Network for Pose Estimation and Tracking](http://web.cs.ucla.edu/~zhou.ren/ECCV2020_poseTracking.pdf)<br>
作者｜Chunluan Zhou，Zhou Ren，Gang Hua<br><br>

* 21.[Know Your Surroundings: Exploiting Scene Information for Object Tracking](https://arxiv.org/abs/2003.11014)<br>
作者｜Goutam Bhat, Martin Danelljan, Luc Van Gool, Radu Timofte<br><br>

* 22.[Simultaneous Detection and Tracking with Motion Modelling for Multiple Object Tracking](https://www.crcv.ucf.edu/wp-content/uploads/2020/07/Publications_Simultaneous-Detection-and-Tracking-with-Motion-Modelling-for-Multiple-Object-Tracking.pdf)<br>
作者｜ShiJie Sun, Naveed Akhtar, XiangYu Song, HuanSheng Song, Ajmal Mian, and Mubarak Shah<br>
代码｜https://github.com/shijieS/OmniMOTDataset<br><br>

* 23.[SPARK: Spatial-aware Online Incremental Attack Against Visual Tracking](https://arxiv.org/abs/1910.08681)<br>
作者｜Qing Guo, Xiaofei Xie, Felix Juefei-Xu, Lei Ma, Zhongguo Li, Wanli Xue, Wei Feng, Yang Liu<br><br>

* 24.[Efficient Adversarial Attacks for Visual Object Tracking](https://arxiv.org/abs/2008.00217)<br>
作者｜Siyuan Liang, Xingxing Wei, Siyuan Yao, Xiaochun Cao<br><br>

* 25.[Tracking Emerges by Looking Around Static Scenes, with Neural 3D Mapping](https://arxiv.org/abs/2008.01295)<br>
作者｜Adam W. Harley, Shrinidhi K. Lakshmikanth, Paul Schydlo, Katerina Fragkiadaki<br><br>

* 26.Stereo Event-based Particle Tracking Velocimetry for 3D Fluid Flow Reconstruction<br><br>


<br><br>

<a name="103"/>


### [CVPR2019（共19篇）](https://bbs.cvmart.net/articles/523)


参考：https://mp.weixin.qq.com/s/mfnO6brDMIYvTeDpI1pDMg<br><br>

#### 单目标跟踪

* 1.[Unsupervised Deep Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Unsupervised_Deep_Tracking_CVPR_2019_paper.html)<br>
作者｜Ning Wang, Yibing Song, Chao Ma, Wengang Zhou, Wei Liu, Houqiang Li<br>
代码｜https://github.com/594422814/UDT/<br><br>

* 2.[Tracking by Animation: Unsupervised Learning of Multi-Object Attentive Trackers](http://openaccess.thecvf.com/content_CVPR_2019/html/He_Tracking_by_Animation_Unsupervised_Learning_of_Multi-Object_Attentive_Trackers_CVPR_2019_paper.html)<br>
作者｜Zhen He, Jian Li, Daxue Liu, Hangen He, David Barber<br>
代码｜https://github.com/zhen-he/tracking-by-animation<br><br>

* 3.[Object Tracking by Reconstruction With View-Specific Discriminative Correlation Filters](http://openaccess.thecvf.com/content_CVPR_2019/html/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.html)<br>
作者｜Ugur Kart, Alan Lukezic, Matej Kristan, Joni-Kristian Kamarainen, Jiri Matas<br><br>

* 4.[Target-Aware Deep Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Target-Aware_Deep_Tracking_CVPR_2019_paper.html)<br>
作者｜Xin Li, Chao Ma, Baoyuan Wu, Zhenyu He, Ming-Hsuan Yang<br>
代码｜https://github.com/XinLi-zn/TADT<br>
代码｜https://github.com/ZikunZhou/TADT-python<br><br>

* 5.[SPM-Tracker: Series-Parallel Matching for Real-Time Visual Object Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_SPM-Tracker_Series-Parallel_Matching_for_Real-Time_Visual_Object_Tracking_CVPR_2019_paper.html)<br>
作者｜Guangting Wang, Chong Luo, Zhiwei Xiong, Wenjun Zeng<br><br>

* 6.[SiamRPN++: Evolution of Siamese Visual Tracking With Very Deep Networks](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.html)<br>
作者｜Bo Li, Wei Wu, Qiang Wang, Fangyi Zhang, Junliang Xing, Junjie Yan<br>
代码｜https://github.com/STVIR/pysot<br><br>

* 7.[Deeper and Wider Siamese Networks for Real-Time Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.html)<br>
作者｜Zhipeng Zhang, Houwen Peng<br>
代码｜https://github.com/researchmm/SiamDW<br><br>

* 8.[Graph Convolutional Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Gao_Graph_Convolutional_Tracking_CVPR_2019_paper.html)<br>
作者｜Junyu Gao, Tianzhu Zhang, Changsheng Xu<br>
代码｜https://nlpr-web.ia.ac.cn/mmc/homepage/jygao/gct_cvpr2019.html#<br><br>

* 9.[ATOM: Accurate Tracking by Overlap Maximization](http://openaccess.thecvf.com/content_CVPR_2019/html/Danelljan_ATOM_Accurate_Tracking_by_Overlap_Maximization_CVPR_2019_paper.html)<br>
作者｜Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg<br>
代码｜https://github.com/visionml/pytracking <br><br>

* 10.[Visual Tracking via Adaptive Spatially-Regularized Correlation Filters](http://openaccess.thecvf.com/content_CVPR_2019/html/Dai_Visual_Tracking_via_Adaptive_Spatially-Regularized_Correlation_Filters_CVPR_2019_paper.html)<br>
作者｜Kenan Dai, Dong Wang, Huchuan Lu, Chong Sun, Jianhua Li<br>
代码｜https://github.com/Daikenan/ASRCF<br><br>

* 11.[ROI Pooled Correlation Filters for Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Sun_ROI_Pooled_Correlation_Filters_for_Visual_Tracking_CVPR_2019_paper.html)<br>
作者｜Yuxuan Sun, Chong Sun, Dong Wang, You He, Huchuan Lu<br><br>

* 12.[Siamese Cascaded Region Proposal Networks for Real-Time Visual Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Fan_Siamese_Cascaded_Region_Proposal_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.html)<br>
作者｜Heng Fan, Haibin Ling<br><br>

#### 多目标跟踪
* 13.[Eliminating Exposure Bias and Metric Mismatch in Multiple Object Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Maksai_Eliminating_Exposure_Bias_and_Metric_Mismatch_in_Multiple_Object_Tracking_CVPR_2019_paper.html)<br>
作者｜Andrii Maksai, Pascal Fua<br><br>

* 14.[MOTS: Multi-Object Tracking and Segmentation](http://openaccess.thecvf.com/content_CVPR_2019/html/Voigtlaender_MOTS_Multi-Object_Tracking_and_Segmentation_CVPR_2019_paper.html)<br>
作者｜Paul Voigtlaender, Michael Krause, Aljosa Osep, Jonathon Luiten, Berin Balachandar Gnana Sekar, Andreas Geiger, Bastian Leibe<br>
代码｜https://www.vision.rwth-aachen.de/page/mots<br><br>

#### 跟踪与分割

* 15.[Fast Online Object Tracking and Segmentation: A Unifying Approach](http://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Fast_Online_Object_Tracking_and_Segmentation_A_Unifying_Approach_CVPR_2019_paper.html)<br>
作者｜Qiang Wang, Li Zhang, Luca Bertinetto, Weiming Hu, Philip H.S. Torr<br>
代码｜https://github.com/foolwood/SiamMask<br><br>

#### 3D目标跟踪
* 16.[Leveraging Shape Completion for 3D Siamese Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Giancola_Leveraging_Shape_Completion_for_3D_Siamese_Tracking_CVPR_2019_paper.html)<br>
作者｜Silvio Giancola, Jesus Zarzar, Bernard Ghanem<br>
代码｜https://github.com/SilvioGiancola/ShapeCompletion3DTracking<br><br>

#### 跟踪数据集
* 17.[LaSOT: A High-Quality Benchmark for Large-Scale Single Object Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Fan_LaSOT_A_High-Quality_Benchmark_for_Large-Scale_Single_Object_Tracking_CVPR_2019_paper.html)<br>
作者｜Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Hexin Bai, Yong Xu, Chunyuan Liao, Haibin Ling<br>
代码｜https://cis.temple.edu/lasot/index.html<br><br>

* 18.[Argoverse: 3D Tracking and Forecasting With Rich Maps](http://openaccess.thecvf.com/content_CVPR_2019/html/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.html)<br>
作者｜Ming-Fang Chang, John Lambert, Patsorn Sangkloy, Jagjeet Singh, Slawomir Bak, Andrew Hartnett, De Wang, Peter Carr, Simon Lucey, Deva Ramanan, James Hays<br>
代码｜https://www.argoverse.org/<br><br>

* 19.[CityFlow: A City-Scale Benchmark for Multi-Target Multi-Camera Vehicle Tracking and Re-Identification](http://openaccess.thecvf.com/content_CVPR_2019/html/Tang_CityFlow_A_City-Scale_Benchmark_for_Multi-Target_Multi-Camera_Vehicle_Tracking_and_CVPR_2019_paper.html)<br>
作者｜Zheng Tang, Milind Naphade, Ming-Yu Liu, Xiaodong Yang, Stan Birchfield, Shuo Wang, Ratnesh Kumar, David Anastasiu, Jenq-Neng Hwang<br>
代码｜https://www.aicitychallenge.org/<br><br>

<br><br>

<a name="104"/>


### [ICCV2019（共11篇）](https://bbs.cvmart.net/articles/1190)

<ul>
<li>
<p><strong>DiMP:</strong> Goutam Bhat, Martin Danelljan, Luc Van Gool, Radu Timofte.<br>
"Learning Discriminative Model Prediction for Tracking." ICCV (2019 <strong>oral</strong>).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Bhat_Learning_Discriminative_Model_Prediction_for_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]
[<a href="https://github.com/visionml/pytracking">code</a>]</p>
</li>
<li>
<p><strong>GradNet:</strong> Peixia Li, Boyu Chen, Wanli Ouyang, Dong Wang, Xiaoyun Yang, Huchuan Lu. <br>
"GradNet: Gradient-Guided Network for Visual Object Tracking." ICCV (2019 <strong>oral</strong>).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_GradNet_Gradient-Guided_Network_for_Visual_Object_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]
[<a href="https://github.com/LPXTT/GradNet-Tensorflow">code</a>]</p>
</li>
<li>
<p><strong>MLT:</strong> Janghoon Choi, Junseok Kwon, Kyoung Mu Lee. <br>
"Deep Meta Learning for Real-Time Target-Aware Visual Tracking." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Deep_Meta_Learning_for_Real-Time_Target-Aware_Visual_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]</p>
</li>
<li>
<p><strong>SPLT:</strong> Bin Yan, Haojie Zhao, Dong Wang, Huchuan Lu, Xiaoyun Yang <br>
"'Skimming-Perusal' Tracking: A Framework for Real-Time and Robust Long-Term Tracking." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]
[<a href="https://github.com/iiau-tracker/SPLT">code</a>]</p>
</li>
<li>
<p><strong>ARCF:</strong> Ziyuan Huang, Changhong Fu, Yiming Li, Fuling Lin, Peng Lu. <br>
"Learning Aberrance Repressed Correlation Filters for Real-Time UAV Tracking." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Learning_Aberrance_Repressed_Correlation_Filters_for_Real-Time_UAV_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]
[<a href="https://github.com/vision4robotics/ARCF-tracker">code</a>]</p>
</li>
<li>
<p>Lianghua Huang, Xin Zhao, Kaiqi Huang. <br>
"Bridging the Gap Between Detection and Tracking: A Unified Approach." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Bridging_the_Gap_Between_Detection_and_Tracking_A_Unified_Approach_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]</p>
</li>
<li>
<p><strong>PAT:</strong> Rey Reza Wiyatno, Anqi Xu. <br>
"Physical Adversarial Textures That Fool Visual Object Tracking." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Wiyatno_Physical_Adversarial_Textures_That_Fool_Visual_Object_Tracking_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]</p>
</li>
<li>
<p><strong>GFS-DCF:</strong> Tianyang Xu, Zhen-Hua Feng, Xiao-Jun Wu, Josef Kittler. <br>
"Joint Group Feature Selection and Discriminative Filter Learning for Robust Visual Object Tracking." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Joint_Group_Feature_Selection_and_Discriminative_Filter_Learning_for_Robust_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]
[<a href="https://github.com/XU-TIANYANG/GFS-DCF">code</a>]</p>
</li>
<li>
<p><strong>CDTB:</strong> Alan Lukežič, Ugur Kart, Jani Käpylä, Ahmed Durmush, Joni-Kristian Kämäräinen, Jiří Matas, Matej Kristan. <br></p>
<p>"CDTB: A Color and Depth Visual Object Tracking Dataset and Benchmark." ICCV (2019).
[<a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Lukezic_CDTB_A_Color_and_Depth_Visual_Object_Tracking_Dataset_and_ICCV_2019_paper.pdf" rel="nofollow">paper</a>]</p>
</li>
</ul>



<br><br>

<a name="200"/>

## 2.benchmark

首先推荐两篇综述性论文：

1. [Deep Learning for Visual Tracking: A Comprehensive Survey](https://arxiv.org/pdf/1912.00535.pdf)<br>


23页、207篇参考文献的多目标跟踪综述（2013-2019）。在OTB2013、OTB2015、VOT2018和LaSOT上对基于深度学习的最新目标跟踪方法进行了全面综述：介绍14种常用视觉跟踪数据集，超过50种历年的SOTA算法(如SiamRPN++)。<br>

![](https://github.com/extreme-assistant/Object-Tracking-Paper-Benchmark-Team/blob/master/640-76.png)


![](https://github.com/extreme-assistant/Object-Tracking-Paper-Benchmark-Team/blob/master/640-77.png)

2. [DEEP LEARNING IN VIDEO MULTI-OBJECT TRACKING: A SURVEY](https://arxiv.org/pdf/1907.12740v4.pdf)<br>



![](https://github.com/extreme-assistant/Object-Tracking-Paper-Benchmark-Team/blob/master/640-78.png)

![](https://github.com/extreme-assistant/Object-Tracking-Paper-Benchmark-Team/blob/master/640-79.png)

来源：https://github.com/foolwood/benchmark_results<br>

<ul>
<li>
<p><strong>LaSOT:</strong> Heng Fan, Liting Lin, Fan Yang, Peng Chu, Ge Deng, Sijia Yu, Hexin Bai, Yong Xu, Chunyuan Liao, Haibin Ling.
"Deep Meta Learning for Real-Time Visual Tracking based on Target-Specific Feature Space." arXiv (2018).
[<a href="https://arxiv.org/pdf/1809.07845.pdf" rel="nofollow">paper</a>]
[<a href="https://cis.temple.edu/lasot/" rel="nofollow">project</a>]</p>
</li>
<li>
<p><strong>OxUvA long-term dataset+benchmark:</strong> Jack Valmadre, Luca Bertinetto, João F. Henriques, Ran Tao, Andrea Vedaldi, Arnold Smeulders, Philip Torr, Efstratios Gavves.<br>
"Long-term Tracking in the Wild: a Benchmark." ECCV (2018).
[<a href="https://arxiv.org/pdf/1803.09502.pdf" rel="nofollow">paper</a>]
[<a href="https://oxuva.github.io/long-term-tracking-benchmark/" rel="nofollow">project</a>]</p>
</li>
<li>
<p><strong>TrackingNet:</strong> Matthias Müller, Adel Bibi, Silvio Giancola, Salman Al-Subaihi, Bernard Ghanem.<br>
"TrackingNet: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild." ECCV (2018).
[<a href="https://silviogiancola.github.io/publication/2018-03-trackingnet/details/" rel="nofollow">project</a>]
[<a href="https://arxiv.org/pdf/1803.10794.pdf" rel="nofollow">paper</a>]</p>
</li>
<li>
<p><strong>UAVDT:</strong> Dawei Du, Yuankai Qi, Hongyang Yu, Yifang Yang, Kaiwen Duan, GuoRong Li, Weigang Zhang,  Weihai; Qingming Huang, Qi Tian.<br>
"The Unmanned Aerial Vehicle Benchmark: Object Detection and Tracking." ECCV (2018).
[<a href="https://arxiv.org/pdf/1804.00518.pdf" rel="nofollow">paper</a>]</p>
  

<br><br>

<a name="300"/>



## 实验室
（以下排名不分先后，可能有遗漏，欢迎补充）


上海交通大学：[林巍峣](https://www.sohu.com/a/162408443_473283)<br>


大连理工大学：[卢湖川](http://ice.dlut.edu.cn/lu/)<br>


澳大利亚国立大学：[Hongdong Li](http://users.cecs.anu.edu.au/~hongdong/)<br>


香港理工大学：[Lei Zhang](http://www4.comp.polyu.edu.hk/~cslzhang/)<br>


中国科学院自动化研究所：[张天柱](http://nlpr-web.ia.ac.cn/mmc/homepage/tzzhang/index.html)<br>


上海交通大学：[CHAO MA](https://www.chaoma.info/)<br>


加州大学默塞德分校：[Ming-Hsuan Yang](https://faculty.ucmerced.edu/mhyang/)<br>


卢布尔雅那大学卢布尔雅那大学：[Matej Kristan](https://www.vicos.si/People/Matejk)<br>


哈佛大学：[João F. Henriques，Luca Bertinetto](https://www.robots.ox.ac.uk/~joao/) <br>


[Torr Vision Group](https://www.robots.ox.ac.uk/~tvg/people.php)<br>


苏黎世联邦理工学院：[Martin Danelljan](https://users.isy.liu.se/cvl/marda26/)<br>


商汤科技tracking组：武伟，王强，朱政<br>

腾讯 AI Lab [宋奕兵](https://ybsong00.github.io/)<br>

阿里巴巴：ET实验室<br>


