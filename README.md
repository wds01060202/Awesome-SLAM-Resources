# Awesome-SLAM-Resources
SLAM顶会论文、实验室、公司收集

* [SfM 相关文献](https://github.com/AwesomeKings/Awesome-SLAM-Resources/blob/master/README.md)
  * [增量式SfM]()
  * [全局式SfM]()
* [稠密重建(Multiple View Stereo)相关文献](https://github.com/AwesomeKings/Awesome-SLAM-Resources/blob/master/README.md)
* [SLAM公司推荐](https://github.com/AwesomeKings/Awesome-SLAM-Resources/blob/master/README.md)
  * [自动驾驶]()
  * [仓储机器人]()
  * [服务型机器人]()
  * [无人机]()
  * [增强现实]()
  * [芯片相机]()
* [SLAM常用数据集](https://github.com/AwesomeKings/Awesome-SLAM-Resources/blob/master/README.md)
* [SLAM开源数据集汇总（中文版）]()

# SfM 相关文献
## 增量式SfM：
1.	N. Snavely, et al. Modeling the World from Internet Photo Collections. IJCV 2007.
2.	P. Moulon, et al. Adaptive Structure from Motion with a contrario model estimation. ACCV 2012.
3.	C. Wu. Towards linear-time incremental structure from motion. 3DV 2013.
4.	J. Schonberger, et al. Structure-from-Motion Revisited. CVPR 2016.
5.	H. Cui, et al. Batched Incremental Structure-from-Motion. 3DV 2017.
6.	H. Cui, et al. Progressive Large-Scale Structure-from-Motion with Orthogonal MSTs. 3DV 2018.
## 全局式SfM：
1.	N. Jiang, et al. A Global Linear Method for Camera Pose Registration. ICCV 2013.
2.	M. Moulon, et al. Global Fusion of Relative Motions for Robust, Accurate and Scalable structure from motion. ICCV 2013.
3.	K. Wilson, et al. Robust Global Translations with 1DSfM. ECCV 2014.
4.	O. Ozyesil, et al. Robust Camera Location Estimation by Convex Programming. CVPR 2015 .
5.	C. Sweeney, et al. Optimizing the Viewing Graph for Structure-from-Motion. ICCV 2015.
6.	T. Goldstein, et al. Shapefit and Shapekick for Robust, Scalable Structure from Motion. ECCV 2016.
7.	S. Zhu, et al. Very Large-Scale Global SfM by Distributed Motion Averaging. CVPR 2018.
## 混合式SfM：
1.	H. Cui, et al. HSfM: Hybrid Structure-from-Motion. CVPR 2017.
2.	S. Zhu, et al. Parallel Structure from Motion from Local Increment to Global Averaging. arXiv:1702.08601.

# 稠密重建(Multiple View Stereo)相关文献
1.	G. Vogiatzis, et. al. Multiview stereo via volumetric graph-cuts and occlusion robust photo-consistency. IEEE T-PAMI, 2007.
2.	S.N. Sinha, et. al. Multi-view stereo via graph cuts on the dual of an adaptive tetrahedral mesh. ICCV 2007.
3.	D. Gallup, et. al. Real-Time Plane-sweeping Stereo with Multiple Sweeping Directions. CVPR 2007.
4.	Y. Furukawa and Jean Ponce. Accurate, dense, and robust Multiview stereopsis.. IEEE T-PAMI, 2010.
5.	H. Vu, et. al. High accuracy and visibilityconsistent dense multiview stereo. IEEE T-PAMI , 2012.
6.	M. Bleyer, et. al. Patchmatch stereostereo matching with slanted support windows. BMVC, 2011.
7.	S. Shen. Accurate multiple view 3d reconstruction using patch-based stereo for large-scale scenes. IEEE T-IP, 2013.
8.	S. Galliani, et. al. Massively parallel multiview stereopsis by surface normal diffusion. ICCV, 2015.
9.	J. L. Schonberger, et. al. Pixelwise view selection for unstructured multi-view stereo. ECCV, 2016.
10.	Q. Xu and W. Tao. Multi-Scale Geometric Consistency Guided Multi-View Stereo. CVPR, 2019
11.	P-H. Huang, et. al. DeepMVS: Learning Multi-view Stereopsis, CVPR 2018. (CNN Based)
12.	Y. Yao, et al. MVSNet: Depth Inference for Unstructured Multi-view Stereo, ECCV 2018. (CNN Based)
13.	Y. Yao, et al. Recurrent MVSNet for High-resolution Multi-view Stereo Depth Inference, CVPR 2019. (CNN Based)



# SLAM公司推荐

作者：张磊涛
##
## 一  自动/辅助驾驶：

### 1.百度：

主要产品：自动驾驶软件

百度智能汽车开启未来之路。基于SD地图、ADAS地图、高精地图、人工智能、大数据， 向国内外车企提供自动驾驶系统解决方案和HMI人机交互平台；与车企、Tier1厂商、芯片厂商以及服务提供商等共同打造智慧汽车新生态自动驾驶软件服务自动驾驶软件服务，是面向汽车企业提供包括感知、自定位和决策在内的应用级自动驾驶辅助软件服务。
Apollo(阿波罗)是一个开放的、完整的、安全的平台，将帮助汽车行业及自动驾驶领域的合作伙伴结合车辆和硬件系统，快速搭建一套属于自己的自动驾驶系统Road Hackers是百度自动驾驶开放平台，提供海量中国路情驾驶数据的开放、基于深度学习的自动驾驶算法的演示和自动驾驶算法Benchmark评比。

### 2.地平线 ：

主要产品：智能驾驶解决方案

基于自研计算平台的智能驾驶解决方案。面向智能驾驶，目前地平线已形成由 Matrix 自动驾驶计算平台、ADAS、DMS、AR HUD、Face ID 等构建的智能驾驶产品矩阵，地平线可针对客户不同需求提供针对 L2、L3、L4 等不同级别自动驾驶的解决方案。目前，地平线也是中国唯一一家在全球四大汽车市场都同顶级汽车 Tier1s 和 OEMs 建立合作关系的 AI 科技创业公司。

多级别 ，地平线将 Matrix 自动驾驶计算平台等核心硬件与地平线智能驾驶软件平台深度耦合，可提供面向智能驾驶的多级别视觉环境感知方案。高性能，支持对复杂场景进行细粒度、结构化的语义感知，高度可扩展、模块化的三维语义环境重建。低延时，基于边缘人工智能计算，可在本地端实现高效计算与数据处理。高精度基于深度学习的环境感知，目标检测、识别与运动预测，用结构化的深度神经网络进行高效和全面的计算。
### 3.图森未来：

主要产品：无人驾驶卡车

有效感知距离长达1000米，在高速路上，1000米有效感知距离确保卡车有35秒的反应时间，帮助系统进行更安全更高效的驾驶任务，感知系统能够在多种天气条件下进行正确识别商业化无人驾驶运输服务的开展，使得图森未来通过L4级别（SAE）无人驾驶解决方案持续获得主营收入。在美国，图森未来无人驾驶卡车日均完成3-5次货物运输，服务十三位终端货主客户，将开通一条由亚利桑那州至德克萨斯州的全新运输线路，在今年将无人驾驶卡车车队规模扩充到50台。

### 4.腾讯：

主要产品：智能驾驶解决方案

腾讯自动驾驶业务中心充分发挥腾讯在高精度地图方向的能力积累，整合公司在车联网，大数据、云平台，深度学习、多源信息融合感知与定位、高精度地图生产与运用等多方面的技术优势，以“-个核心， 两个产品和三个平台”为着力点，构建领先的集自动驾驶产品研发，测试以及评测验证于一身的开发平台，提供完整的自动驾驶技术解决方案和开放的平台支持能力，做“软件与服务提供商”，通过“数字化接口和工具箱"为行业提供包容、创新和可持续的智慧解决方案。


### 5.四维图新：
主要产品：自动驾驶系统解决方案

自动驾驶地图。自动驾驶不可或缺的一环，在自动驾驶车感知、定位、规划决策中扮演重要角色
高精度定位。基于实时动态差分RTK技术，以厘米级精度精准定位自动驾驶车。
智能地平线。地图实现车辆控制，全面提升ADAS功能与能力的软硬件解决方案
智能感知。Smart Collector，高精度、低成本、自带算法的智能感知系统


### 6.驭势科技：

主要产品：U-Drivetm智能驾驶系统

为用户提供全方位、可升级的智能驾驶系统。AI算法基于领先视觉能力的多为感知识别，厘米级融合定位，规划控制。车规级硬件，集成AI算法的智能驾驶控制器，兼容摄像头，激光雷达，毫米波雷达等多种传感器。云端智能服务，基于安全的云端数据通信技术，提供车辆远程监控，驾驶以及编队调度，车路协同等无人运营服务，自动驾驶仿真模拟服务。


### 7.纵目科技：

主要产品：ADAS高级驾驶员辅助系统

ADAS高级驾驶员辅助系统，通过传感器和摄像头感知车辆周围的环境及车辆，给驾驶员提供可靠的报警及提示信息，让行驶变得更加安全。在产品设计过程中，采用了专业的车载产品设计过程，抗震强，干扰小，功耗低，耐高温，防冲击。定制鱼眼镜头，覆盖车身周围360无盲区。摄像头体积小巧，车载适用摄像头模具，方便设配安装，与车型完美匹配，方便调试安装。

### 8.滴滴：

主要产品：智能驾驶

智能驾驶会大幅提升安全性和出行效率，为现有司机服务提供有力补充。车路协同、车车协同的智慧交通将改变车辆的出行方式。滴滴正在积极布局高级别智能驾驶以及V2X技术研发，滴滴平台上每天产生大量数据，为训练智能驾驶算法打造了得天独厚的基础。目前滴滴在中美两地拥有研发中心和测试车队，并将持续加大对智能驾驶的投入。

### 9.momenta：

主要产品：环境感知、高精度地图和驾驶决策

环境感知。道路在黑暗、逆光、恶劣天气和缺乏清晰的车道线的情况下，做到高性能地识别多个车道、交通标志和信号、可行驶区域。

行人。通过检测行人和识别人体特征点，可做到理解行人姿势和行为意图，同时也可准确估计行人与汽车的距离。

车辆。路面上的每一辆车都可还原其3D边界框，鲁棒地检测车的方向，精确地估算距离，并在高精度地图上进行实时定位。


数据驱动的驾驶决策。类似于建立一个拥有1000亿公里驾驶经验的智能司机。众包路测让我们获得高精度语义地图中的海量驾驶轨迹。通过对驾驶轨迹的学习，算法可以根据当前环境感知和高精度地图信息，做出驾驶决策规划。因此可以利用数据而不是规则，解决算法在罕见路况失灵的问题。

### 10.纽劢科技：

主要产品：自动驾驶解决方案

运用多传感器融合（摄像头、激光雷达、毫米波雷达、超声波雷达和GPS/IMU）打造的完整自动驾驶解决方案，具备反应速度快、定制水平化高和可扩展性强等突出特点，可以实现L3/L4级别自动驾驶。

基于深度学习、以视觉为主的感知系统，应用最尖端的图像信号处理（ISP）技术和计算机视觉科技进行目标识别与检测，利用高度优化的深度神经网络，实现全天候、多路况、各种复杂天气下的精确环境感知。

### 11.飞步科技：

主要产品：无人驾驶货运卡车  汽车AI芯片  ADAS高级辅助驾驶

无人驾驶货运卡车.飞步提供L2-L4自动驾驶货运卡车的整体解决方案，将人工智能技术应用于货运卡车，使货运驾驶更安全、更便捷、效率更高。
汽车AI芯片。基于飞步自身AI技术，本着高性能、低功耗、低成本宗旨，研发出完全自主知识产权的中国“芯”，为快速迈入AI时代，提供“硬”支持。

ADAS高级辅助驾驶。车道偏离预警、前向碰撞预警、疲劳驾驶预警，飞步ADAS安装在驾驶室内，由前向和驾驶室内的摄像头来识别前方路况及驾驶行为情况，辅助驾驶员前向碰撞和车道偏离预警；同时可监测驾驶员的疲劳程度和驾驶规范。
### 12.极目智能：

主要产品：ADAS驾驶辅助解决方案

作为一家专业ADAS驾驶辅助解决方案供应商，极目智能拥有自主研发的专业计算机视觉技术，能准确识别车辆、车道线、行人、交通标志等道路信息，帮助驾驶员感知周边驾驶环境，提醒潜在碰撞危险，减少碰撞事故，同时致力于为自动驾驶的普及提供核心技术及服务。

### 13. 虹软

主要产品：ADAS驾驶辅助系统

功能：通过前向摄像头，ADAS视觉子系统可以实时识别前方车辆、行人和车道线， 检测本车与前车或行人之间的距离、方位及相对速度，以及本车在车道中的位置，并由此做出预警判定,从而为安全驾驶提供辅助作用。


## 二  仓储机器人：

### 1.京东：

主要产品：无人车

无人车立足于打造京东智能物流体系中的智能运载装备，以自动驾驶核心技术为基础，根据不同场景的用户需求，研发并生产多种系列多种型号的自动驾驶无人车产品。针对物流运输和配送场景，生成自动驾驶货车和配送机器人；针对仓库、厂区、园区、社区等场景，生成安防巡检机器人；针对办公楼内场景，生成服务机器人。依托商业市场需求和用户需求，通过高效、低成本并且提升用户体验的运营模式来实现商业化运营服务。

### 2.顺丰科技：

主要产品：室内AGV

自动化及机器人实现了各项技术在物流场景中的应用，极大的降低了人力成本，是传统物流迈向智能物流的重要提升环节.

### 3.阿里达摩院：

主要产品：智能物流车

高精定位。探索基于高精度地图的高精智能定位技术，构建物理世界和数字世界的准确映射，为自动驾驶汽车提供精准的交通元素，POI等场景信息。研究云端的多源融合定位技术，搭建融合与处理的云平台，将车与人，车与车连接起来，形成一个动态的位置网络。这个网络在为自动驾驶提供位置服务的同时，也支持基于精确位置的数据收集和回传，对高精度地图进行在线更新，全面提升定位系统的准确性，可靠性和智能性。

决策规划。决策规划分为驾驶决策系统和运动规划系统。驾驶决策系统通过大量实测的高精度交通流数据分析，探寻人类驾驶行为的本质机理，挖掘出最优的行为模型和参数，保证在线驾驶行为的最优化。运动规划系统在有限的计算资源下，搜索成千上万可能的运行轨迹，并根据周边环境信息挑选最优轨迹，实现自动驾驶的平稳行驶。

智能控制。主要包含横向控制和纵向控制两个方面。横向控制主要研究自动驾驶汽车的路径跟踪能力，即如何控制车辆沿规划的路径行驶，并保证车辆的行驶安全性，平稳性。纵向控制主要是控制车辆速度跟踪能力，控制车辆按照预定的速度巡航。

自动驾驶仿真平台。由交通智能体系统，场景编辑生成系统，虚拟世界渲染系统，大规模服务器部署系统组成。交通智能体系统通过大量的交通数据抽取逼真的行为模型，仿真车辆，行人等物体行为；场景编辑生成系统支持各种极端场景的编辑和类似场景的生成，实现对自动驾驶算法的压力测试；虚拟世界渲染系统将仿真场景进行可视化渲染，提高分析问题的直观感觉;大规模服务器部署系统提高仿真的规模和效率，实现每年上亿公里的仿真测试；仿真平台为自动驾驶的测试节省大量时间和费用，极大降低了测试风险，随机模拟各种极端复杂场景，实现全面的测试覆盖。

数据平台。生产数据平台，数据生产流程化以及监控。为感知采集丰富的数据，以提高自动驾驶整车鲁棒性。研究如何建立高效的标注系统，减小标注的成本，提高效率和标注结果的准确率;研究如何更有效的监控车辆运行的状态和问题，以及把数据更加合理可视化;探索实际数据和仿真数据结合的过程提供结构化，半结构化，非结构化多种类型的数据整合，集成与索引。

车路协同。通过车与路之间的协同合作，构建“车 - 路 - 云”三位一体的全新模式研究开发路侧端的多传感器感知，多模态数据融合与处理，低功耗边缘计算，中短距直连通信等技术，打造全新的路侧智能设备，为交通工具提供实时数据服务，并为云端提供全面的交通信息基础数据。


### 4.北京极智嘉：

主要产品：智能的物流自动化解决方案

适用范围：极智拣选系统适用于中小件、多品类的仓库拣选作业，适用仓库面积可达上万平米，针对电商、零售、3PL、医药、鞋服、食品、日用品、工业、汽车制造等众多行业。

功能特点：稳定的举升搬运，最大负载达1,000kg。强大的导航避障，视觉组合导航方式，毫米级定位。灵活的智能调度，智能路径规划和拥塞控制算法。先进的自动充电，智能自主充电，24小时无间断运行。


### 5.旷视科技：

主要产品：智能仓储物流解决方案

旷视科技智能仓储物流解决方案由旷视全资子公司艾瑞思机器人（Ares）提供，可为电商、商超、大型仓储物流行业用户提供“货到人”“订单到人”“车到人”，以及“机器人 + 仓储系统 + 数据分析”的综合性解决方案，持续帮助供应链提升整体效能，为行业客户创造更多价值。

### 6.海康威视：

主要产品：智能仓储解决方案

针对传统仓储作业人工成本高、管理效率低、订单出错率高等难题，自主研发智能仓储机器人系统 , 提供了高效率的智能仓储解决方案。方案涉及海康威视智能仓储机器人、机器人调度系统（RCS）和智能仓储管理系统（iWMS）三大核心模块，以机器换人为核心理念，工人只需在工作台操作终端进行必要的操作，即可满足包括采购入库、生产入库、生产领料、成品出库等各项仓储业务需求，大幅提升电商分拣中心、3C制造业、传统制造业、医疗、食品及汽车制造等行业的仓储作业效率及管理水平。支持仓储管理中的冷热度分析、货架位置调整、货架整理、智能盘点等业务功能，操作终端界面支持可视化管理。


## 三 服务型机器人：

### 1.普渡科技有限公司：

主要产品：餐饮机器人

轻轻松松开始工作。作为餐厅新员工，“入职”对欢乐送来说再简单不过了。不需要地面导轨来辅助运行，更不需要进行培训，最短2个小时的时间内它就可以完成地图构建，正式投入使用。它没有工伤也没有病假，故障远程修复与软件远程升级等功能让餐厅运营者们省心又省力。

### 2.高仙机器人：

主要产品：楼宇配送机器人 自主定位导航模块

自主定位导航模块 .高仙Conbox自主定位导航模块系列产品具备顶尖的环境感知力、高鲁棒性精确定位开放的平台和完善的文档工具，可便捷、无缝式快速接入下游各类终端，被广泛应用于物流、安防、银行、商超、政务、零售等领域，在国内市场中市占率过半，为实现机器人典型场景应用和构建产业生态系统起到了关键性作用。

### 3.优必选机器人：

主要产品：人形机器人 优必选定位导航系统

优必选定位导航系统（U-SLAM）能根据不同场景装载不同的定位解决方案，通过不同解决方案的融合使用或切换，使应用主体能够建立周围环境地图并进行自身定位，可根据环境变化智能选择去往目标点的最优路径从而进行导航行为控制。

### 4.弗徕威智能机器人：

主要产品：家庭服务型机器人

整合全球研发资源，持续推动机器人技术与人工智能技术、移动互联技术、云计算技术、物联网技术的融合与创新，引领智慧家庭、智慧社区及智慧城市建设，为人们提供智能化的解决方案和先进的生活方式。不止于形深入考究人机交互。不止于外形，充分考虑躺，坐，站情况下的交互。 结合表情声音动作让人与机器人的交互更自然。

### 5.小米：

主要产品：扫地机器人

新一代石头扫地机器人配备了13类传感器，米家自研的高精度LDS激光测距传感器，能以5360/秒的速度扫描房间，地面的障碍物会在传感器里形成光斑，然后传感器会根据其独创的SLAM算法，准确的绘制出房间地图，同时合理规划清扫路线。在LDS激光测距传感器上方，石头扫地机器人还配备了全向压力传感器，它的作用在于感应顶部360°轻微的碰撞，防止进入低矮的沙发、柜子底部后被卡住，对激光传感器也起到保护的作用。沿墙传感器可以让扫地机器人以约10mm的距离，清扫墙边缝隙，红外回充技术可以在充好电后继续清扫。

### 6.科沃斯机器人：

主要产品：扫地机器人

科沃斯机器人作为全球最早的服务机器人研发与生产商之一, 专注于服务机器人的独立研发、设计、制造和销售。从创立伊始的十余年间,已成功推出包括扫地机器人地宝,擦窗机器人窗宝,空气净化机器人沁宝和管家机器人UNIBOT的完整家用机器人产品线,以及以公共服务机器人旺宝为主的商用机器人系列产品。科沃斯机器人十余年在服务机器人市场的耕耘,也赢得了用户的一致肯定。

### 7.平安科技：

主要产品：RPA安小蜂

RPA安小蜂是平安科技自主研发的流程自动化机器人，通过模拟人类操作，为替代手工操作提供最低成本、最快捷的解决方案。借助平安云RPA安小蜂，企业能够利用虚拟员工，在不同业务系统的用户交互界面上，高质高效地处理密集重复性的工作，释放人力，有效提升企业效益。

执行机器人提供多种机器人使用方式，可实现全流程无人值守，充分发挥自动化的价值。可提供手动运行、定时运行、远程控制及智能调度四种方式。

### 8.臻迪机器人：

主要产品：水下机器人

PowerDolphin小海豚搭载了一枚独特的双关节旋转相机，镜头拍摄广角达到132°，更可以通过旋转， 满足水上、水下不同视角的拍摄需求，视场角可旋转范围达到-150°至+70°（定义水平位置为0°，朝水下方向 转动为负），从而为用户提供了220°的全新拍摄视角。


### 9.猎户星空：

主要产品：服务型机器人

猎户星空为“真有用”机器人而生，是一家拥有服务机器人行业全链条AI技术、以互联网基因做机器人的新物种公司，公司自研机器人全链条AI技术集合了芯片+算法（脑）、全感知视觉识别（眼）、语音全链条技术（口）、麦克风阵列（耳）、七轴消费级机械臂（手）和室内自主导航平台（腿）。经过两年多的高速发展，猎户星空已发布了自主研发的机器人平台 OrionStar OS和一系列自研产品，包括猎户星空AI 智能服务机器人“豹小秘”、小豹AI家教机器人、智能新零售机器人“豹小贩”、机械臂咖啡亭“豹咖啡”等。

### 10.追觅科技：

主要产品：吸尘器

追觅科技 在高速数字马达、单目机器视觉、SLAM（即时定位与地图构建）、多锥旋风分离技术等方面拥有一系列和新发明技术，处于全球领先地位。同时这些技术也成功应用到了无绳吸尘器、扫地机器人等产品中。
## 四 无人机：

### 1.大疆：

主要产品：视觉传感导航系统的无人机

Guidance是一款全新的视觉传感导航系统，可感知附近障碍物，让飞行器主动躲避。它内置功能强大的处理核心，配备五组视觉超声波组合传感器，辅以先进的视觉算法，为用户带来安全飞行的体验高精度视觉定位Guidance采用高精度立体视觉算法，近地面定位精度可达厘米级。在复杂地形和高速飞行条件下均可提供定位信息。视觉定位系统的有效高度高达20米全方位障碍物感知Guidance可实时监测多个方向的环境信息并感知障碍物，与适当的飞行控制器配合，可使得飞行器在高速飞行中对可能发生的碰撞及时避让。

### 2.京东：

主要产品：无人机

京东无人机致力于打造干线级、支线级、末端级三级无人机+通航物流体系，意在覆盖全国广大农村地区，实现村村通，县县通，该体系先从末端布局，之后逐步建立干线和支线物流网络，最终构建天地一体化的智能物流网络，实现2小时物流生活圈，提升广大消费者的购物体验。 京东无人机正在打造三级无人机+通航物流体系，建立干线、支线、末端无人机物流配送，逐步构建天地一体的无人机智能物流网络。

### 3.顺丰科技：

主要产品：无人机

基于解决各种特殊场景（特色经济、医疗冷链、应急配送、特种物流等）下物流运输的末端配送问题，已成功研发出满足不同运营需求的多款机型和相关配套软硬件，包括多旋翼无人机、垂直起降固定翼无人机、运营管控系统、通讯系统、无人机快递接驳柜等。并于2018年3月27日获得国内首张无人机航空运营许可证，致力于为涉山涉水、陆路交通不便的广大偏远地区提供高质量的物流配送服务，为特定行业提供通用或定制化的无人机产品和综合解决方案。

### 4.亿航：

主要产品：无人机

亿航智能是一家集研发、生产、销售、服务为一体的智能飞行器高科技创新企业，总部位于中国广州，被国际权威媒体《快公司》评选为“全球最佳创新公司”，以及全球无人机企业前三强。秉持“让人类像鸟儿一样自由飞翔”的企业使命，亿航智能为各个行业领域客户提供简易、智能、安全、高效的飞行器产品和解决方案，包括自动驾驶飞行器、智慧城市指挥调度中心、行业应用网联无人机、无人机自动化集群编队、无人机物流配送等。作为全球民用无人机行业中，诸多创新技术与应用模式的先行者，亿航智能不断探索天空的边界，让飞行普惠智慧城市的美好生活。

### 5.易瓦特Ewatt：

主要产品：无人机

物流运输无人机 行业应用解决方案。无人机配送物件可以做到高效，快捷。尤其是对于交通欠发达地区，无人机可以利用空中交通缩短运送历程，提高效率。同时，无人机可以作为空中平台，搭载特殊设备，完成物流货仓盘点、园区巡查等高强度作业。

## 五 增强现实（AR）：

### 1.百度：

主要产品：AR特效

百度研发的SLAM技术具有低功耗、高实时性，可以支持多种数据源，比如单目、双目、RGBD等语义SLAM百度的语义SLAM技术结合百度SLAM技术、图像识别技术和物体识别技术构建精确的语义地图，赋能增强现实，实现所见即所得的AR交互体验。帮助开发者快速集成AR SDK，高效制作并分发AR内容。主要包括面向AR应用开发者的技术开放平台，以及提供内容制作和分发服务的内容开放平台。

### 2.华为：

主要产品：HUAWEI VR

HUAWEI VR是为华为VR内容开发者提供的平台。开发者使用华为VR SDK进行开发，开发完成后上传至华为VR应用商店，审核通过后拥有华为VR2眼镜的消费者即可直接购买下载。HUAWEI VR目前的硬件形态是VR2 眼镜 + 华为系列手机，具体支持手机型号见开发指南。VR2眼镜本身为3dof头显，配一只3dof功能的手柄，允许开发者直接移植其他平台的3+3内容，对于手机盒子类无手柄的应用稍加更改也很容易移植。

### 3.视辰科技：

主要产品：AR解决方案

EasyAR开放平台和视+AR内容平台。针对各行业业务特性形成的增强现实解决方案，为用户提供全方位服务。包括零售、金融、汽车、教育、短视频等行业领域。


### 4.联想研究院：

主要产品：AR解决方案

增强现实（Augmented Reality，简称 AR），是一种实时地计算摄影机影像的位置及角度并加上相应图像、视频和3D模型的技术，通过在屏幕上把虚拟世界套在现实世界并进行互动，不仅能让用户看到真实世界的信息，而且将虚拟的信息同时显示出来，两种信息相互补充、叠加。它主要包括三大特征：虚实结合、实时交互、以及三维注册，基于这些典型特征，联想晨星AR致力于提升企业生产力，为行业客户提供端到端的AR解决方案。
### 5.亮风台：

主要产品：AR解决方案

设计 • 大道至简HiAR G100 采用简洁的一体化设计，将东方美学融入科技美感，形神连贯、一气呵成。有删繁就简的流畅、轻盈，也有领异标新的自然、突破。

佩戴 • 舒适自然极致的人机工学设计，让每位用户如同体验“私人订制”。可拆可调的头带组件，创新性的弹性夹持支架，带来平衡又舒适的佩戴感。可选近视镜片，支持个性化调节瞳距和近视度数。

光学 • 体验出色HiAR G100 采用光学透视（Optical See - Through）方案，0延迟，无眩晕，使用户在虚实之间游刃有余。自由曲面光波导投影系统，兼顾舒适视角与轻便，高达 1000nit 的亮度，呈现令人惊叹的亮丽画面。

性能 • 强大无匹HiAR G100 创新配备 Qualcomm® 骁龙™ 820 处理器的 AR 眼镜，搭载 4GB 双通道 LPDDR4 闪存，与前代机型相比，运算速度、图形处理速度和数据传输速率均成倍提升。

视觉 • 超越人眼Sony 1300万高像素摄像头和5P 蓝玻滤噪82.2度广角镜头，使 HiAR G100 的视觉能力远超人眼。摄像头模组可以从5米甚至更远的距离获取高画质图像，特有 PDAF 相位对焦功能，仅需0.1秒即可完成画面对焦。


## 六 芯片相机

### 1.思岚科技：

主要产品：模块化自主定位导航解决方案

SLAMWARE是一种单模块化的机器人自主定位导航系统，集成了基于激光雷达的同步定位与建图(SLAM)及配套的路径规划功能。宿主系统可以利用SLAMWARE提供的通讯接口，并结合SDK实时获取的高精度机器人位置信息与SLAMWARE自主构建的环境地图数据，进行灵活、多样的功能扩展。可机器人实现自主定位、自动建图、路径规划与自动避障，确实解决机器人自主行走难题。

### 2.速腾聚创：

主要产品：RS-LiDAR-Algorithms感知算法

RS-LiDAR-Algorithms是专门为自动驾驶环境感知开发的一套软件开发套件，包括定位、路沿/可行驶区域检测、车道标识线检测、障碍物检测、动态物体跟踪、障碍物分类识别等功能模块。我们开发该SDK的目的在于方便自动驾驶项目开发者基于该套件进行二次开发，以加速您的自动驾驶项目。

### 3.镭神智能：

主要产品：机器人SLAM算法板卡

LS SLAM模块是在激光雷达的基础上，集成了自主定位与建图，以及配套的路径导航与避障功能，用于机器人自主导航与定位系统的解决方案模块。“激光雷达+ SLAM”让服务机器人行走自如。

### 4.小觅智能：

主要产品：双目相机解决方案

提供一套成熟的，适用于各类机器人的双目立体视觉系统，帮助机器人实现3D立体地图建模、规划导航路线、避障等多项功能。成熟整机研发经验。业界领先双目硬件方案。IR主动光解决白墙和无纹理物体识别难题。行业领先VSLAM / VIO 成熟算法支持。

### 5.禾赛科技：

主要产品：环境感知传感器融合系统

禾赛科技专注于开发激光传感器，目前产品线包括用于无人驾驶和机器人的激光雷达，以及用于能源行业安全巡检的激光遥测系统等。禾赛科技自主研发的激光雷达Pandar40已经装在了硅谷、底特律、匹兹堡及欧洲和中国各地的数十家顶尖自动驾驶公司的无人车上。美国加州现有的62家获得无人车公开道路测试牌照的高科技公司中，超过40%已经是禾赛Pandar40的付费客户。

### 6.魔视智能：

主要产品：自动驾驶芯片

魔视智能以“开启汽车的人工智能大脑，实现更安全更自由的自动驾驶”为愿景，持续致力于整合先进的人工智能技术和汽车电子系统成功经验，打通传统汽车智能化的技术鸿沟，将国际级的视觉感知、融合、定位、路径规划与控制算法实现在嵌入式低功耗的车规级芯片上，实现在不同的场景条件下的自动驾驶。

### 7.芯仑科技

主要产品：动态视觉传感器芯片



芯仑科技拥有全球领先的动态视觉传感器芯片技术，致力于创造高效的图像处理系统。动态视觉传感器从数据输入的源头实现革命性改变，实现像素级主动感知与传输，从前端减少数据的冗余提供结构化信息，实现系统运算效率的提升，减轻后端整体模组负担。
传统的图像传感器是基于帧来成像，在固定时间段（帧时间）内，像素阵列检测到的光电流被积分在电容器中，在每一帧时间内，每个像素的到达电压电平以顺序方式传送出芯片。因此，使用传统图像传感器时，每一帧时间内会将所有像素的信息传输出去，而不管单个像素上是否有变化进而判断是否需要进行信息传输。而DVS芯片由一个个独立感光像素组成，每一个像素都在独立判断自身是否被激发，当该像素被激发产生事件时，像素同时发出位置、灰度值和时间三组信息（X，Y，A，T）。这种单独触发机制与传统的全幅触发机制在设计机理上存在着巨大的差异，使得动态视觉传感器在SLAM这种对实时性分析有要求的场景中拥有明显优势。


### 8.速感科技：

主要产品：面向智能设备的系统化视觉解决方案


vSLAM（基于视觉的同时定位与构图）算法是团队的核心技术算法。团队自主研发的vSLAM算法可以融合多种传感器（激光雷达、惯性测量单元、里程计、超声波等）数据获得稳定且准确位置姿态信息的同时，帮助机器人等智能设备获取三维空间环境信息，使其具备自主移动、路径规划、场景理解等能力。前后经过多个版本迭代的Qfeeltech vSLAM算法在多个国际公开数据集下同业内其他算法相比，保持领先的定位定姿效果

Auto Navigating（自主导航）算法是团队基于具体应用场景开发的工程技术之一。团队自主研发的Path Planning算法以视觉图像和激光雷达数据作为主要输入，通过融合AMCL（粒子滤波）定位算法以及A*（全局规划）、DWA（局部规划）路径选择策略，获得较单一传感器方案更准确的位置结果，在应对特殊事件时该算法可以获得更快速的即时策略响应，选取更合适的移动路径。

Object Tracking（物体检测与跟踪）算法是团队基于传统视觉和深度视觉技术下的研究技术之一。团队自主研发的Visual Tracking算法可以在传统RGB视频流中利用MLD架构获得较学术界主流TLD算法更快速更准确的动态物体识别、检测与跟踪结果，后者目前被广泛应用在无人机自主跟随等领域。此外该算法可以基于带有深度信息的RGB-D视频流自动进行前景提取与受测物体分割，从而得到更好的检测与跟踪结果。

Scene Perception（图像场景理解）算法是团队在当前机器人行业背景下的在研技术之一。团队希望通过对深度视觉技术的前期技术积累，结合目前学术界已经成熟的基于CNN（卷积神经网络）的深度学习算法和行业数据，开发垂直应用的图像理解算法，该算法的创新性在于利用深度图像区别于传统图像的优势，通过更高维特征点集的获取得到更为精准的图像语言理解与认知。


# SLAM常用数据集

1． KITTI 装备4个相机、高精度GPS/IMU和激光雷达，在城市道路采集的数据。

网址：http://www.cvlibs.net/datasets/kitti/

2． EuRoC MAV 提供了在微型飞行器（MAV）上收集的视觉惯性数据集。数据集包含立体图像，同步IMU测量以及精确的运动和真值。

网址：https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets

3． RGB-D SLAM Dataset and Benchmark 提供包含RGB-D数据和地面实况数据的大型数据集。

网址：https://vision.in.tum.de/data/datasets/rgbd-dataset


# SLAM开源数据集汇总（中文版）
作者：泡泡机器人

## 类别
- [评估工具](#评估工具)
  - Evaluation Methods of SLAM
- [主题](#按主题分类)
  - [里程计](#里程计): Dataset for odometry Benchmark
  - [建图](#建图): Dataset for mapping task
  - [多样场景](#多样场景): Dataset gives correspondences of places (images)
  - [定位](#定位): Dataset for metric-level localization
  - [感知](#感知): Dataset with semantic labels / correspondences

- [特点](#按特点分类)
  - [大规模](#大规模): City-scale map, kilometer level Map
  - [长时间](#长时间): Multi-session, long-term data collection
  - [复杂地图](#复杂地图): Variation of mapping structures
  - [极端情况](#极端情况): Extreme environment, motions

- [载体平台](#按载体平台分类)
    - [汽车](#汽车): Commercial Vehicle (Four-wheeled on the road)
    - [移动机器人](#移动机器人): Mobile Robots (Ex. Husky, Rover.. )
    - [无人机](#无人机): Unmanned aerial robots include drone.
    - [水下自主航行器](#水下自主航行器): Underwater robots include ROV for simplicity.
    - [水面无人艇](#水面无人艇): Water surface vehicle such as canoe and boat.
    - [手持设备](#手持设备): Hand-held platform by human

- [环境](#按环境分类)
    - [城市](#城市): City, campus, town, and infrastructures
    - [室内](#室内): Indoor environment
    - [地形](#地形): Rough terrain, underground, lake and farm
    - [水下](#水下): Underwater floor, cave

## 数据集表格总览 (简版)
点击[查看完整版链接](https://sites.google.com/view/awesome-slam-datasets/)

| 名称                                                                                                | 机构  | 年份 | 载体平台   | 出版来源 | 环境           | 是否有 GT-Pose | GT-Map | IMU | GPS | 标签 | Lidar      | Camera | RGBD | 事件相机 | Radar | 声呐 | 多普勒速度记录 | 其他                   |
|----------------------------------------------------------------------------------------------------------|--------------|------|------------|-------------|-----------------------|---------|--------|-----|-----|--------|------------|---------|------|-------|-------|-------|-----|-------------------------|
| [Collaborative SLAM Dataset (CSD)](https://github.com/torrvision/CollaborativeSLAMDataset)               | Oxford       | 2018 | Hand       | TVCG/ISMAR  | Indoor                | O       | O      | O   |     |        |            | O       | O    |       |       |       |     | Tango (Asus ZenFone AR)
| [ADVIO Dataset](https://github.com/AaltoVision/ADVIO)               | Aalto U          | 2018 | Hand | ECCV                | Urban      | O | O | O |   |   |   | O |   |   |   |   |   | iPhone, Tango, Pixel                     |
| [DeepIO Dataset](http://deepio.cs.ox.ac.uk/)                        | Oxford           | 2018 | Hand | Arxiv               | Indoor     | O |   | O |   |   |   |   |   |   |   |   |   |                                          |
| [Aqualoc Dataset](http://www.lirmm.fr/aqualoc/)                     | ONERA-DTIS       | 2018 | ROV  | IROS WS             | Underwater | O |   | O |   |   |   | O |   |   |   |   |   | Pressure Sensor                          |
| [Rosario Dataset](http://www.cifasis-conicet.gov.ar/robot/doku.php) | CONICET-UNR      | 2018 | Mob  | IJRR (Under Review) | Terrain    | O |   | O |   |   |   | O |   |   |   |   |   | Encoder                                  |
| [InteriorNet](https://interiornet.org/)                             | Imperial College | 2018 | Hand | BMVC                | Indoor     | O | O | O |   | O |   | O | O | O |   |   |   | Texture, Lighting, Context, Optical Flow |
| [SPO Dataset](https://www.hs-karlsruhe.de/odometry-data/)           | TUM, Karlsruhe   | 2018 | Hand | Arxiv               | Urban      | O |   |   |   |   |   | O |   |   |   |   |   | Plenoptic Camera                         |
| [Complex Urban](http://irap.kaist.ac.kr/dataset/)                                                        | KAIST-IRAP   | 2018 | Veh        | ICRA        | Urban                 | O       | O      | O   | O   |        | O          |         |      |       |       |       |     | Encoder                 |
| [KAIST Day/Night](https://sites.google.com/view/multispectral/home)                                      | KAIST-RCV    | 2018 | Veh        | T-ITS       | Urban                 | O       |        | O   | O   | O      | O          | O       |      |       |       |       |     | Thermal Camera          |
| [TUM-Visual-Inertial](https://vision.in.tum.de/data/datasets/visual-inertial-dataset)                    | TUM          | 2018 | Hand       | Arxiv       | Indoor, Urban         |         |        | O   |     |        |            |         | O    |       | O     |       |     |                         |
| [Multi Vech Event](https://daniilidis-group.github.io/mvsec/)                                            | Upenn        | 2018 | Veh        | RA-L        | Urban                 | O       |        | O   | O   |        | O          | O       |      | O     |       |       |     |                         |
| [VI Canoe](https://databank.illinois.edu/datasets/IDB-9342111)                                           | UIUC         | 2018 | USV        | IJRR        | Terrain               | O       |        | O   | O   |        |            | O       |      |       |       |       |     |                         |
| [MPO-Japan](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)                   | ETH-RPG      | 2017 | UAV / Hand | IJRR        | Indoor                | O       |        | O   |     |        |            | O       |      | O     |       |       |     |                         |
| [Underwater Cave](http://cirs.udg.edu/caves-dataset/)                                                    | UDG          | 2017 | AUV        | IJRR        | Underwater            | O       |        | O   |     |        |            | O       |      |       |       | O     | O   | Profiling Sonar         |
| [Robot @ Home](http://mapir.isa.uma.es/mapirwebsite/index.php/mapir-downloads/203-robot-at-home-dataset) | MRPT         | 2017 | Mob        | IJRR        | Indoor                | O       | O      |     |     | O      | O          |         | O    |       |       |       |     | Semantic Labels         |
| [Zurich Urban MAV](http://rpg.ifi.uzh.ch/zurichmavdataset.html)                                          | ETH-RPG      | 2017 | UAV        | IJRR        | Urban                 | O       |        | O   | O   |        |            | O       |      |       |       |       |     | Streetview images       |
| [Chilean Underground](http://dataset.amtc.cl/#)                                                          | Trimble      | 2017 | Mob        | IJRR        | Terrain (Underground) | O       |        |     |     |        | O          | O       |      |       | O     |       |     | Encoder                 |
| [SceneNet RGB-D](https://robotvault.bitbucket.io/scenenet-rgbd.html)                                     | Imperial     | 2017 | Hand       | ICCV        | Indoor                | O       |        |     |     | O      |            |         | O    |       |       |       |     |                         |
| [Symphony Lake](http://dream.georgiatech-metz.fr/?q=node/79)                                             | Georgia Tech | 2017 | USV        | IJRR        | Terrain (Lake)        |         |        | O   | O   |        | O          | O       |      |       |       |       |     | PTZ camera, Longterm    |
| [Agricultural robot](http://www.ipb.uni-bonn.de/data/sugarbeets2016/)                                    | Bonn         | 2017 | Mob        | IJRR        | Terrain               | O       |        |     | O   | O      | O          | O       | O    |       |       |       |     | Multispectral camera    |
| [Beach Rover](https://robotics.estec.esa.int/datasets/katwijk-beach-11-2015/)                            | TEC-MMA      | 2017 | Mob        |             | Terrain               | O       |        | O   | O   |        | O          | O       | O    |       |       |       |     | Encoder                 |
| [EuRoC](http://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)                     | ETH-ASL      | 2016 | UAV        | IJRR        | Indoor                | O       | O      | O   |     |        |            | O       |      |       |       |       |     |                         |
| [Cartographer](https://google-cartographer-ros.readthedocs.io/en/latest/data.html)                     | Google      | 2016 | Hand        | ICRA        | Indoor                |         |        | O   |     |        | O          | O       |      |       |       |       |     |                         |
| [TUM-Mono](https://vision.in.tum.de/data/datasets/mono-dataset)                                          | TUM          | 2016 | Hand       | Arxiv       | Indoor, Urban         |         |        |     |     |        |            |         |      |       | O     |       |     | Photometric Calibration |
| [Cityscape](https://www.cityscapes-dataset.com/)                                                         | Daimler AG   | 2016 | Veh        | CVPR        | Urban                 | O       |        |     | O   | O      |            | O       |      |       |       |       |     |                         |
| [Solar-UAV](http://projects.asl.ethz.ch/datasets/doku.php?id=fsr2015)                                    | ETHZ         | 2016 | UAV        | CVPR        | Terrain               | O       | O      | O   | O   |        | O          |         |      |       |       |       |     |                         |
| [CoRBS](http://corbs.dfki.uni-kl.de/?pagerd_tumlltzzf42zsv6de7b9)                                        | DFKI         | 2016 | Hand       | WACV        | Indoor                | O       | O      |     |     |        |            |         | O    |       |       |       |     |                         |
| [Oxford-robotcar](http://robotcar-dataset.robots.ox.ac.uk)                                               | Oxford       | 2016 | Veh        | IJRR        | Urban                 | O       |        | O   | O   |        | O          | O       |      |       |       |       |     |                         |
| [NCLT](http://robots.engin.umich.edu/nclt/)                                                              | UMich        | 2016 | Mob        | IJRR        | Urban                 | O       |        | O   | O   |        | O          |         |      |       |       |       |     | FOG                     |
| [RPG-event](http://rpg.ifi.uzh.ch/davis_data.html)                                                       | Kyushu U     | 2016 | Veh        | IROS        | Urban, Terrain        |         |        | O   | O   |        | O          | O       |      |       |       |       |     | FARO 3D                 |
| [CCSAD](http://aplicaciones.cimat.mx/Personal/jbhayet/ccsad-dataset)                                     | CIMAT        | 2015 | Veh        | CAIP        | Urban                 |         |        | O   | O   |        |            | O       |      |       |       |       |     |                         |
| [TUM-Omni](https://vision.in.tum.de/data/datasets/omni-lsdslam)                                          | TUM          | 2015 | Hand       | IROS        | Indoor, Urban         |         |        |     |     |        |            | O       |      |       |       |       |     |                         |
| [Augmented ICL-NUIM](http://redwood-data.org/indoor/index.html)                                          | Redwood      | 2015 | Hand       | CVPR        | Indoor                | O       | O      |     |     |        |            |         | O    |       |       |       |     |                         |
| [Cambridge Landmark](http://mi.eng.cam.ac.uk/projects/relocalisation/)                                   | Cambridge    | 2015 | Hand       | ICCV        | Urban                 | O       | O      |     |     |        |            | O       |      |       |       |       |     |                         |
| [ICL-NUIM](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html)                                         | Imperial     | 2014 | Hand       | ICRA        | Indoor                | O       | O      |     |     |        |            |         | O    |       |       |       |     |                         |
| [MRPT-Malaga](https://www.mrpt.org/robotics_datasets)                                                    | MRPT         | 2014 | Veh        | AR          | Urban                 |         |        | O   | O   |        | O          | O       |      |       |       |       |     |                         |
| [KITTI](http://www.cvlibs.net/datasets/kitti/index.php)                                                  | KIT          | 2013 | Veh        | IJRR        | Urban                 | O       |        | O   | O   | O      | O          | O       |      |       |       |       |     |                         |
| [Canadian Planetary](http://asrl.utias.utoronto.ca/datasets/3dmap/#Datasets)                             | UToronto     | 2013 | Mob        | IJRR        | Terrain               | O       |        | O   | O   |        | O (sensor) | O       |      |       |       |       |     |                         |
| [Microsoft 7 scenes](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/)                               | Microsoft    | 2013 | Hand       | CVPR        | Indoor                | O       | O      |     |     |        |            | O       |      |       |       |       |     |                         |
| [SeqSLAM](https://wiki.qut.edu.au/display/cyphy/Open+datasets+and+software)                              | QUT          | 2012 | Veh        | ICRA        | Urban                 |         |        |     |     | O      |            | O       |      |       |       |       |     |                         |
| [ETH-challenging](http://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)  | ETH-ASL      | 2012 | Hand       | IJRR        | Urban, Terrain        |         |        | O   | O   |        | O          | O       | O    |       |       |       |     |                         |
| [TUM-RGBD](https://vision.in.tum.de/data/datasets/rgbd-dataset)                                          | TUM          | 2012 | Hand / Mob | IROS        | Indoor                | O       |        | O   |     |        |            |         | O    |       |       |       |     |                         |
| [ASRL-Kagara-airborne](http://asrl.utias.utoronto.ca/~mdw/kagarudataset.html)                            | UToronto     | 2012 | UAV        | FSR         | Terrain               |         |        | O   | O   |        |            | O       |      |       |       |       |     |                         |
| [Devon Island Rover](http://asrl.utias.utoronto.ca/datasets/devon-island-rover-navigation/)              | UToronto     | 2012 | Mob        | IJRR        | Terrain               | O       |        |     | O   |        |            | O       |      |       |       |       |     | Sunsensor, Inclinometer |
| [ACFR Marine](http://marine.acfr.usyd.edu.au/datasets/)                                                  | ACFR         | 2012 | AUV        |             | Underwater            | O       |        | O   |     | O      |            | O       |      |       |       | O     |     |                         |
| [UTIAS Multi-Robot](http://asrl.utias.utoronto.ca/datasets/mrclam/)                                      | UT-IAS       | 2011 | Mob        | IJRR        | Urban                 | O       |        |     |     | O      |            |         |      |       |       |       |     |                         |
| [Ford Campus](http://robots.engin.umich.edu/SoftwareData/Ford)                                           | UMich        | 2011 | Veh        | IJRR        | Urban                 | O       |        | O   | O   |        | O          | O       |      |       |       |       |     |                         |
| [San francisco](https://sites.google.com/site/chenmodavid/datasets)                                      | Stanford     | 2011 | Veh        | CVPR        | Urban                 | O       |        | O   | O   | O      |            | O       |      |       |       |       |     | DMI                     |
| [Annotated-laser](http://any.csie.ntu.edu.tw/data)                                                       | NTU          | 2011 | Veh        | IJRR        | Urban                 | O       |        |     |     | O      | O          | O       |      |       |       |       |     |                         |
| [MIT-DARPA](http://grandchallenge.mit.edu/wiki/index.php?title=PublicData)                               | MIT          | 2010 | Veh        | IJRR        | Urban                 | O       |        | O   | O   | O      | O          | O       |      |       |       |       |     |                         |
| [St Lucia Stereo](http://asrl.utias.utoronto.ca/~mdw/uqstluciadataset.html)                              | UToronto     | 2010 | Veh        | ACRA        | Urban                 |         |        | O   | O   |        |            | O       |      |       |       |       |     |                         |
| [St Lucia Multiple Times](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day)          | QUT          | 2010 | Veh        | ICRA        | Urban                 |         |        |     | O   |        |            | O       |      |       |       |       |     |                         |
| [Marulan](http://sdi.acfr.usyd.edu.au/)                                                                  | ACFR         | 2010 | Mob        | IJRR        | Terrain               | O       |        | O   | O   |        | O          | O       |      |       | O     |       |     | IR                      |
| [COLD](https://www.pronobis.pro/#data)                                                                   | KTH          | 2009 | Hand       | IJRR        | Indoor                | O       |        |     |     | O      | O          | O       |      |       |       |       |     |                         |
| [NewCollege](http://www.robots.ox.ac.uk/NewCollegeData/)                                                 | Oxford-Robot | 2009 | Mob        | IJRR        | Urban                 | O       |        |     | O   |        | O          | O       |      |       |       |       |     |                         |
| [Rawseeds-indoor](http://www.rawseeds.org/home/category/benchmarking-toolkit/datasets/)                  | Milano       | 2009 | Mob        | IROSW       | Indoor                | O       | O      | O   |     |        | O          | O       |      |       |       | O     |     |                         |
| [Rawseeds-outdoor](http://www.rawseeds.org/home/category/benchmarking-toolkit/datasets/)                 | Milano       | 2009 | Mob        | IROSW       | Urban                 | O       | O      | O   | O   |        | O          | O       |      |       |       | O     |     |                         |
| [FABMAP](http://www.robots.ox.ac.uk/~mobile/IJRR_2008_Dataset/)                                          | Oxford-Robot | 2008 | Veh        | IJRR        | Urban                 |         |        |     | O   |        |            | O       |      |       |       |       |     |                         |


## 评估工具
_Evaluation methods for SLAM benchmarks_
- Trajectory Evaluation with Alignment [[Paper](http://rpg.ifi.uzh.ch/docs/IROS18_Zhang.pdf)], [[Code](https://github.com/uzh-rpg/rpg_trajectory_evaluation)]
- Python package for the evaluation of odometry and SLAM [[Code](https://michaelgrupp.github.io/evo/)]
- SLAMBench2.0: SLAM performance evaluation framework [[Code](https://github.com/pamela-project/slambench2)]

## 按主题分类

### 里程计
_Dataset for odometry Benchmark_
- [TUM-Visual-Inertial](https://vision.in.tum.de/data/datasets/visual-inertial-dataset)
- [Visual-Inertial Canoe Dataset](https://databank.illinois.edu/datasets/IDB-9342111)
- [Multi Vehicle Stereo Event Camera Dataset](https://docs.google.com/spreadsheets/d/1mudM7LxXv09ywuQGDp3t_RlIjIdwzg_ZaMu78agLmH4/edit#gid=0)
- [Zurich Urban Micro Aerial Vehicle Dataset](http://rpg.ifi.uzh.ch/zurichmavdataset.html)
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
- [TUM Monocular Cameras Dataset](https://vision.in.tum.de/data/datasets/mono-dataset)
- [Event-Camera Dataset and Simulator](http://rpg.ifi.uzh.ch/davis_data.html)
- [TUM Omnidirectional Cameras Dataset](https://vision.in.tum.de/data/datasets/omni-lsdslam)
- [ICL-NUIM RGBD Dataset](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html)
- [TUM RGB-D SLAM Dataset and Benchmark](https://vision.in.tum.de/data/datasets/rgbd-dataset)
- [Google Cartographer](https://google-cartographer-ros.readthedocs.io/en/latest/data.html)
- [ADVIO Dataset](https://github.com/AaltoVision/ADVIO)
- [Deep Inertial Odometry Dataset](http://deepio.cs.ox.ac.uk/)
- [Aqualoc Underwater Dataset](http://www.lirmm.fr/aqualoc/)
- [Rosario Agricultural Dataset](http://www.cifasis-conicet.gov.ar/robot/doku.php)
- [Stereo Plenoptic Odometry Dataset](https://www.hs-karlsruhe.de/odometry-data/)


### 建图
_Dataset for mapping task_
- [Collaborative SLAM Dataset (CSD)](https://github.com/torrvision/CollaborativeSLAMDataset)
- [Complex Urban](http://irap.kaist.ac.kr/dataset/)
- [Multi-modal Panoramic 3D Outdoor Dataset (MPO)](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)
- [Underwater Caves SONAR and Vision Dataset](http://cirs.udg.edu/caves-dataset/)
- [Chilean Underground Mine Dataset](http://dataset.amtc.cl/#)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [University of Michigan North Campus Long-Term (NCLT) Vision and LIDAR Dataset](http://robots.engin.umich.edu/nclt/)
- [Málaga Stereo and Laser Urban Data Set](https://www.mrpt.org/MalagaUrbanDataset)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Challenging data sets for point cloud registration algorithms](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)
- [ACFR Marine Robotics Dataset](http://marine.acfr.usyd.edu.au/datasets/)
- [Ford Campus Vision and Lidar Dataset](http://robots.engin.umich.edu/SoftwareData/Ford)
- [InteriorNet](https://interiornet.org/)

### 多样场景
_Dataset gives correspondences of places (images)_
- [Visual-Inertial Canoe Dataset](https://databank.illinois.edu/datasets/IDB-9342111)
- [Symphony Lake Dataset](http://dream.georgiatech-metz.fr/?q=node/79)
- [Alderley Day/Night Dataset](https://wiki.qut.edu.au/pages/viewpage.action?pageId=181178395)
- [St Lucia Multiple Times of Day](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day)
- [New College Vision and Laser Data Set](http://www.robots.ox.ac.uk/NewCollegeData/)
- [FABMAP Dataset](http://www.robots.ox.ac.uk/~mobile/IJRR_2008_Dataset/)

### 定位
_Dataset for metric-level localization_
- [Cambridge Landmark Dataset](http://mi.eng.cam.ac.uk/projects/relocalisation/)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Microsoft 7 scenes](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/)
- [San Francisco Landmark Dataset](https://sites.google.com/site/chenmodavid/datasets)


### 感知
_Dataset with semantic labels / correspondences_
- [KAIST Day/Night Dataset](https://sites.google.com/view/multispectral/home)
- [Robot @ Home Dataset](http://mapir.isa.uma.es/mapirwebsite/index.php/mapir-downloads/203-robot-at-home-dataset)
- [SceneNet RBG-D Dataset](https://robotvault.bitbucket.io/scenenet-rgbd.html)
- [Sugar Beets 2016, Agricultural Robot Dataset](http://www.ipb.uni-bonn.de/data/sugarbeets2016/)
- [CityScapes Dataset](https://www.cityscapes-dataset.com/)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Multi-Sensor Perception (Marulan) Dataset ](http://sdi.acfr.usyd.edu.au/)
- [InteriorNet](https://interiornet.org/)

## 按特点分类

### 大规模
_City-scale map, kilometer level Map_
- [Complex Urban](http://irap.kaist.ac.kr/dataset/)
- [Multi Vehicle Stereo Event Camera Dataset](https://docs.google.com/spreadsheets/d/1mudM7LxXv09ywuQGDp3t_RlIjIdwzg_ZaMu78agLmH4/edit#gid=0)
- [Multi-modal Panoramic 3D Outdoor Dataset (MPO)](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)
- [CityScapes Dataset](https://www.cityscapes-dataset.com/)
- [Solar-powered UAV Sensing and Mapping Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=fsr2015)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [CCSAD (Stereo Urban) Dattaset](http://aplicaciones.cimat.mx/Personal/jbhayet/ccsad-dataset)
- [Málaga Stereo and Laser Urban Data Set](https://www.mrpt.org/MalagaUrbanDataset)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Kagaru Airborne Stereo Dataset Dataset](http://asrl.utias.utoronto.ca/~mdw/kagarudataset.html)
- [ACFR Marine Robotics Dataset](http://marine.acfr.usyd.edu.au/datasets/)

### 长时间
_Multi-session, long-term data collection_
- [KAIST Day/Night Dataset](https://sites.google.com/view/multispectral/home)
- [Visual-Inertial Canoe Dataset](https://databank.illinois.edu/datasets/IDB-9342111)
- [Symphony Lake Dataset](http://dream.georgiatech-metz.fr/?q=node/79)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [University of Michigan North Campus Long-Term (NCLT) Vision and LIDAR Dataset](http://robots.engin.umich.edu/nclt/)
- [Alderley Day/Night Dataset](https://wiki.qut.edu.au/pages/viewpage.action?pageId=181178395)
- [St Lucia Multiple Times of Day](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day)

### 复杂地图
_Variation of mapping structures_
- [Complex Urban](http://irap.kaist.ac.kr/dataset/)
- [Multi Vehicle Stereo Event Camera Dataset](https://docs.google.com/spreadsheets/d/1mudM7LxXv09ywuQGDp3t_RlIjIdwzg_ZaMu78agLmH4/edit#gid=0)
- [Multi-modal Panoramic 3D Outdoor Dataset (MPO)](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)
- [Málaga Stereo and Laser Urban Data Set](https://www.mrpt.org/MalagaUrbanDataset)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Challenging data sets for point cloud registration - algorithms](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)

### 极端情况
_Extreme environment, motions_
- [Underwater Caves SONAR and Vision Dataset](http://cirs.udg.edu/caves-dataset/): Underwater Environment
- [Chilean Underground Mine Dataset](http://dataset.amtc.cl/#): Underground Environment
- [CityScapes Dataset](https://www.cityscapes-dataset.com/): Foggy Scene
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets): Fast motion
- [Multi-Sensor Perception (Marulan) Dataset ](http://sdi.acfr.usyd.edu.au/):  Smoky, dust, and Rain condition

## 按载体平台分类

### 汽车
_Commercial Vehicle (Four-wheeled on the road)_
- [Complex Urban Dataset](http://irap.kaist.ac.kr/dataset/)
- [Multi Vehicle Stereo Event Camera Dataset](https://docs.google.com/spreadsheets/d/1mudM7LxXv09ywuQGDp3t_RlIjIdwzg_ZaMu78agLmH4/edit#gid=0)
- [KAIST Day/Night Dataset](https://sites.google.com/view/multispectral/home)
- [Multi-modal Panoramic 3D Outdoor Dataset (MPO)](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [CityScapes Dataset](https://www.cityscapes-dataset.com/)
- [CCSAD (Stereo Urban) Dattaset](http://aplicaciones.cimat.mx/Personal/jbhayet/ccsad-dataset)
- [Málaga Stereo and Laser Urban Data Set](https://www.mrpt.org/MalagaUrbanDataset)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Day and Night with Lateral Pose Change Dataset](https://wiki.qut.edu.au/display/cyphy/Day+and+Night+with+Lateral+Pose+Change+Datasets)
- [Alderley Day/Night Dataset](https://wiki.qut.edu.au/pages/viewpage.action?pageId=181178395)
- [Annotated-laser Dataset](http://any.csie.ntu.edu.tw/data) (Link Broken)
- [San Francisco Landmark Dataset](https://sites.google.com/site/chenmodavid/datasets)
- [Ford Campus Vision and Lidar Dataset](http://robots.engin.umich.edu/SoftwareData/Ford)
- [St Lucia Stereo Vehicular Dataset](http://asrl.utias.utoronto.ca/~mdw/uqstluciadataset.html)
- [St Lucia Multiple Times of Day](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day)
- [MIT DARPA Urban Challenge Dataset](http://grandchallenge.mit.edu/wiki/index.php?title=PublicData)
- [FABMAP Dataset](http://www.robots.ox.ac.uk/~mobile/IJRR_2008_Dataset/)


### 移动机器人
_Mobile Robots (Ex. Husky, Rover.. )_
- [Rosario Dataset](http://www.cifasis-conicet.gov.ar/robot/doku.php)
- [Sugar Beets 2016, Agricultural Robot Dataset](http://www.ipb.uni-bonn.de/data/sugarbeets2016/)
- [Chilean Underground Mine Dataset](http://dataset.amtc.cl/#)
- [Katwijk Beach Planetary Rover Dataset](https://robotics.estec.esa.int/datasets/katwijk-beach-11-2015/)
- [Robot @ Home Dataset](http://mapir.isa.uma.es/mapirwebsite/index.php/mapir-downloads/203-robot-at-home-dataset)
- [University of Michigan North Campus Long-Term (NCLT) Vision and LIDAR Dataset](http://robots.engin.umich.edu/nclt/)
- [Rawseeds In/Outdoor Dataset](http://www.rawseeds.org/home/category/benchmarking-toolkit/datasets/)
- [Canadian Planetary Emulation Terrain 3D Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/3dmap/#Datasets)
- [Devon Island Rover Navigation Dataset](http://asrl.utias.utoronto.ca/datasets/devon-island-rover-navigation/)
- [Multi-Robot Cooperative Localization and Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/mrclam/)
- [Multi-Sensor Perception (Marulan) Dataset ](http://sdi.acfr.usyd.edu.au/)
- [TUM RGB-D SLAM Dataset and Benchmark](https://vision.in.tum.de/data/datasets/rgbd-dataset)
- [New College Vision and Laser Data Set](http://www.robots.ox.ac.uk/NewCollegeData/)

### 无人机
_Unmanned aerial robots include drone_
- [Zurich Urban Micro Aerial Vehicle Dataset](http://rpg.ifi.uzh.ch/zurichmavdataset.html)
- [Event-Camera Dataset and Simulator](http://rpg.ifi.uzh.ch/davis_data.html)
- [Solar-powered UAV Sensing and Mapping Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=fsr2015)
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
- [Kagaru Airborne Stereo Dataset Dataset](http://asrl.utias.utoronto.ca/~mdw/kagarudataset.html)




### 水下自主航行器
_Underwater robots include ROV for simplicity_
- [Aqualoc Underwater Dataset](http://www.lirmm.fr/aqualoc/)
- [Underwater Caves SONAR and Vision Dataset](http://cirs.udg.edu/caves-dataset/)
- [ACFR Marine Robotics Dataset](http://marine.acfr.usyd.edu.au/datasets/)


### 水面无人艇
_Water surface vehicle such as canoe and boat_
- [Visual-Inertial Canoe Dataset](https://databank.illinois.edu/datasets/IDB-9342111)
- [Symphony Lake Dataset](http://dream.georgiatech-metz.fr/?q=node/79)


### 手持设备
_Hand-held platform by human_
- [Collaborative SLAM Dataset (CSD)](https://github.com/torrvision/CollaborativeSLAMDataset)
- [SceneNet RBG-D Dataset](https://robotvault.bitbucket.io/scenenet-rgbd.html)
- [Event-Camera Dataset and Simulator](http://rpg.ifi.uzh.ch/davis_data.html)
- [Comprehensive RGB-D Benchmark (CoRBS)](http://corbs.dfki.uni-kl.de/?pagerd_tumlltzzf42zsv6de7b9)
- [Augmented ICL-NUIM Reconstruction Dataset](http://redwood-data.org/indoor/index.html)
- [ICL-NUIM RGBD Dataset](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html)
- [Challenging data sets for point cloud registration algorithms](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)
- [Cosy Localization Database (COLD)](https://www.pronobis.pro/#data)
- [ADVIO Dataset](https://github.com/AaltoVision/ADVIO)
- [Deep Inertial Odometry Dataset](http://deepio.cs.ox.ac.uk/)
- [InteriorNet](https://interiornet.org/)
- [Stereo Plenoptic Dataset](https://www.hs-karlsruhe.de/odometry-data/)

## 按环境分类
### 城市
_City, campus, town, and infrastructures_
- [ADVIO Dataset](https://github.com/AaltoVision/ADVIO)
- [Stereo Plenoptic Dataset](https://www.hs-karlsruhe.de/odometry-data/)
- [KAIST Day/Night Dataset](https://sites.google.com/view/multispectral/home)
- [TUM-Visual-Inertial](https://vision.in.tum.de/data/datasets/visual-inertial-dataset)
- [Complex Urban](http://irap.kaist.ac.kr/dataset/)
- [Multi Vehicle Stereo Event Camera Dataset](https://docs.google.com/spreadsheets/d/1mudM7LxXv09ywuQGDp3t_RlIjIdwzg_ZaMu78agLmH4/edit#gid=0)
- [Zurich Urban Micro Aerial Vehicle Dataset](http://rpg.ifi.uzh.ch/zurichmavdataset.html)
- [TUM Monocular Cameras Dataset](https://vision.in.tum.de/data/datasets/mono-dataset)
- [CityScapes Dataset](https://www.cityscapes-dataset.com/)
- [Oxford Robotcar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
- [University of Michigan North Campus Long-Term (NCLT) Vision and LIDAR Dataset](http://robots.engin.umich.edu/nclt/)
- [Event-Camera Dataset and Simulator](http://rpg.ifi.uzh.ch/davis_data.html)
- [CCSAD (Stereo Urban) Dattaset](http://aplicaciones.cimat.mx/Personal/jbhayet/ccsad-dataset)
- [TUM Omnidirectional Cameras Dataset](https://vision.in.tum.de/data/datasets/omni-lsdslam)
- [Cambridge Landmark Dataset](http://mi.eng.cam.ac.uk/projects/relocalisation/)
- [Málaga Stereo and Laser Urban Data Set](https://www.mrpt.org/MalagaUrbanDataset)
- [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/index.php)
- [Alderley Day/Night Dataset](https://wiki.qut.edu.au/pages/viewpage.action?pageId=181178395)
- [Challenging data sets for point cloud registration algorithms](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)
- [Multi-Robot Cooperative Localization and Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/mrclam/)
- [Ford Campus Vision and Lidar Dataset](http://robots.engin.umich.edu/SoftwareData/Ford)
- [San Francisco Landmark Dataset](https://sites.google.com/site/chenmodavid/datasets)
- [Annotated-laser Dataset](http://any.csie.ntu.edu.tw/data) (Link Broken)
- [MIT DARPA Urban Challenge Dataset](http://grandchallenge.mit.edu/wiki/index.php?title=PublicData)
- [St Lucia Stereo Vehicular Dataset](http://asrl.utias.utoronto.ca/~mdw/uqstluciadataset.html)
- [St Lucia Multiple Times of Day](https://wiki.qut.edu.au/display/cyphy/St+Lucia+Multiple+Times+of+Day)
- [New College Vision and Laser Data Set](http://www.robots.ox.ac.uk/NewCollegeData/)
- [Rawseeds In/Outdoor Dataset](http://www.rawseeds.org/home/category/benchmarking-toolkit/datasets/)
- [FABMAP Dataset](http://www.robots.ox.ac.uk/~mobile/IJRR_2008_Dataset/)

### 室内
_Indoor environment_
- [Collaborative SLAM Dataset (CSD)](https://github.com/torrvision/CollaborativeSLAMDataset)
- [InteriorNet](https://interiornet.org/)
- [TUM-Visual-Inertial](https://vision.in.tum.de/data/datasets/visual-inertial-dataset)
- [Multi-modal Panoramic 3D Outdoor Dataset (MPO)](http://robotics.ait.kyushu-u.ac.jp/kurazume_lab/research-e.php?content=db)
- [Robot @ Home Dataset](http://mapir.isa.uma.es/mapirwebsite/index.php/mapir-downloads/203-robot-at-home-dataset)
- [SceneNet RBG-D Dataset](https://robotvault.bitbucket.io/scenenet-rgbd.html)
- [EuRoC MAV Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets)
- [TUM Monocular Cameras Dataset](https://vision.in.tum.de/data/datasets/mono-dataset)
- [Comprehensive RGB-D Benchmark (CoRBS)](http://corbs.dfki.uni-kl.de/?pagerd_tumlltzzf42zsv6de7b9)
- [TUM Omnidirectional Cameras Dataset](https://vision.in.tum.de/data/datasets/omni-lsdslam)
- [Augmented ICL-NUIM Reconstruction Dataset](http://redwood-data.org/indoor/index.html)
- [ICL-NUIM RGBD Dataset](https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html)
- [Microsoft 7 scenes](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/)
- [TUM RGB-D SLAM Dataset and Benchmark](https://vision.in.tum.de/data/datasets/rgbd-dataset)
- [Cosy Localization Database (COLD)](https://www.pronobis.pro/#data)
- [Rawseeds In/Outdoor Dataset](http://www.rawseeds.org/home/category/benchmarking-toolkit/datasets/)
- [Google Cartographer](https://google-cartographer-ros.readthedocs.io/en/latest/data.html)


### 地形
_Rough terrain, underground, lake and farm_
- [Rosario Agricultural Dataset](http://www.cifasis-conicet.gov.ar/robot/doku.php)
- [Visual-Inertial Canoe Dataset](https://databank.illinois.edu/datasets/IDB-9342111)
- [Chilean Underground Mine Dataset](http://dataset.amtc.cl/#)
- [Symphony Lake Dataset](http://dream.georgiatech-metz.fr/?q=node/79)
- [Sugar Beets 2016, Agricultural Robot Dataset](http://www.ipb.uni-bonn.de/data/sugarbeets2016/)
- [Katwijk Beach Planetary Rover Dataset](https://robotics.estec.esa.int/datasets/katwijk-beach-11-2015/)
- [Solar-powered UAV Sensing and Mapping Dataset](https://projects.asl.ethz.ch/datasets/doku.php?id=fsr2015)
- [Event-Camera Dataset and Simulator](http://rpg.ifi.uzh.ch/davis_data.html)
- [Canadian Planetary Emulation Terrain 3D Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/3dmap/#Datasets)
- [Challenging data sets for point cloud registration - algorithms](https://projects.asl.ethz.ch/datasets/doku.php?id=laserregistration:laserregistration)
- [Kagaru Airborne Stereo Dataset Dataset](http://asrl.utias.utoronto.ca/~mdw/kagarudataset.html)
- [Devon Island Rover Navigation Dataset](http://asrl.utias.utoronto.ca/datasets/devon-island-rover-navigation/)
- [Multi-Sensor Perception (Marulan) Dataset ](http://sdi.acfr.usyd.edu.au/)


### 水下
_Underwater floor, cave_
- [Aqualoc Underwater Dataset](http://www.lirmm.fr/aqualoc/)
- [Underwater Caves SONAR and Vision Dataset](http://cirs.udg.edu/caves-dataset/)
- [ACFR Marine Robotics Dataset](http://marine.acfr.usyd.edu.au/datasets/)
