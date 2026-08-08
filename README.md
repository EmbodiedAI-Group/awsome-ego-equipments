# Ego数据采集设备市场对比

> 以下为市场上主流Ego（Egocentric，第一人称视角）数据采集设备的汇总对比。信息来源于各公司官网、新闻稿及公开技术文档，部分参数为估算值或未公开标注。欢迎提交PR补充和修正。

## 设备对比表

| # | 产品名称 | 公司 | 摄像头数量 | 分辨率 | FoV | IMU | HDR | 重量 | 价格 | 参考链接 |
|---|---------|------|-----------|--------|-----|-----|-----|------|------|---------|
| 1 | [Aria Gen 2](https://www.projectaria.com) | Meta | 1×RGB + 4×CV + 2×眼动 | 12MP RGB | 更宽FoV（前向立体） | 双6轴IMU | 120dB | 75g | 未公开售卖，国外研究机构可申请，国内无获取渠道 | [projectaria.com](https://www.projectaria.com) |
| 2 | [JoyEgoCam](https://www.jd.com) | 京东 | 双目 | 4K @60fps | 130° | 未公开 | 未公开 | 未公开 | 未公开 | [报道链接](https://finance.eastmoney.com) |
| 3 | [Primus Ego](https://cn.piagroup.com) | 均普智能 | 5路（3×RGB + 双目立体） | 未公开 | >270° | 高精度IMU | 未公开 | 未公开 | 未公开 | [cn.piagroup.com](https://cn.piagroup.com/news/company2/538.html) |
| 4 | [创维 E2](https://www.skyworthxr.com) | 创维新世界 | 双RGB全局快门 | 未公开 | 未公开 | 高精度IMU | 未公开 | 135g | 未公开 | [skyworthxr.com](https://www.skyworthxr.com) |
| 5 | 创维 E6 | 创维新世界 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [skyworthxr.com](https://www.skyworthxr.com) |
| 6 | 创维 E8 | 创维新世界 | 旗舰级 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [skyworthxr.com](https://www.skyworthxr.com) |
| 7 | [EGO RGB-D](https://www.orbbec.com.cn) | 奥比中光 | Gemini330双目3D | RGB+深度 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 8 | [EGO 双目](https://www.orbbec.com.cn) | 奥比中光 | 双目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 9 | [EGO 四目](https://www.orbbec.com.cn) | 奥比中光 | 四目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 10 | [KAI Halo](https://www.kai.com) | 超维动力 | 四路鱼眼全局快门RGB | 1920×1200 | 未公开 | 200Hz IMU | 未公开 | 轻量化头环 | ¥12,999 | [报道链接](https://m.zhidx.com) |
| 11 | [DAS Ego](https://www.genrobot.com/products/ego) | 简智机器人 | 6×超广角 | 1600×1300 @30Hz | >270°（H）/ >150°（V） | 6轴IMU @200Hz | 全局快门 | 350g | 未公开 | [genrobot.com](https://www.genrobot.com/products/ego) |
| 12 | [FastUMI Ego](https://www.fastumi.com) | 鹿明机器人 | 超广角视觉 | 640×480 | >180°（H/V） | IMU+TOF | 未公开 | 235g | 未公开 | [fastumi.com](https://www.fastumi.com/data-market) |
| 13 | [MEgo View](https://www.mego.ai) | 觅蜂科技 | 7摄像头 | 未公开 | >300°全景 | 未公开 | 未公开 | 未公开 | 未公开 | [报道链接](https://news.ifeng.com) |
| 14 | [DAS Ego](https://www.genrobot.com) | GenRobot AI | 6摄像头 | 1600×1300 @30Hz | >270° | 6轴IMU | 全局快门 | 350g | 未公开 | [genrobot.com](https://www.genrobot.com) |
| 15 | [Pika Ego](https://www.agilex.ai) | 松灵机器人 | 第一视角采集系统 | 未公开 | 未公开 | 未公开 | 未公开 | 448g（Pika Pro） | 未公开 | [agilex.ai](https://www.agilex.ai) |
| 16 | [EgoKit](https://www.astralive.com) | 星忆科技 | 头戴多目视觉终端 | RGB+深度 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [报道链接](https://36kr.com) |
| 17 | [OmniEgo](https://www.damon-group.com) | 德马科技 | 头戴式全模态采集 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [damon-group.com](https://www.damon-group.com) |
| 18 | [EgoSuite](https://www.lightwheel.ai) | 光轮智能 | RGB+Depth+PointCloud | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [lightwheel.ai](https://www.lightwheel.ai) |
| 19 | [DexCap](https://www.dex-robot.com) | 灵巧智能 | RGB-D LiDAR + 3×SLAM | 未公开 | 未公开 | IMU | 未公开 | <2kg（轻量化） | 未公开 | [dex-robot.com](https://www.dex-robot.com) |
| 20 | [Ego Unit](https://www.fairplus.com) | Fairplus | 双RGB | 2048×1536 @30Hz | 180°鱼眼 | 6轴IMU @120Hz | 未公开 | 157g | 未公开 | 用户提供 |
| 21 | [HeadGo Ego](https://www.foxtech.com) | Foxtech | 双目+RGB×1 | 未公开 | 150°D/128°H/80°V | 9轴IMU | 未公开 | 未公开 | 未公开 | 用户提供 |
| 22 | [Tobii Pro Glasses 3](https://www.tobii.com) | Tobii | 场景相机+4眼动传感器 | 1920×1080 @25fps | 106°H | 未公开 | 未公开 | 76.5g | 未公开 | [tobii.com](https://www.tobii.com) |
| 23 | [LANYVE-OMNI 4P](https://www.aili-light.com) | 艾利光 | 四目同步 | 720P×4 | 220° | 500Hz高频IMU | 未公开 | 未公开 | 未公开 | [aili-light.com](https://www.aili-light.com) |
| 24 | Lyn 双目 | Lyn | 双目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 25 | Lyn 四目 | Lyn | 四目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 26 | [MEgo Gripper](https://www.mego.ai) | 觅蜂科技 | 夹爪+视觉 | 1080P @60fps | 未公开 | 未公开 | 未公开 | 480g | 未公开 | [报道链接](https://post.smzdm.com) |
| 27 | [深度机智 头戴式](https://deepcybo.site) | 深度机智 | 头戴感知模块 | 未公开 | 未公开 | 未公开 | 未公开 | 分体式设计 | 未公开 | [deepcybo.site](https://deepcybo.site) |
| 28 | 灵初智能 外骨骼手套 | 灵初智能 | 视觉+触觉+关节传感 | 未公开 | 未公开 | 未公开 | 未公开 | 轻量化 | 未公开 | 用户提供 |
| 29 | [KAI Halo 四摄版](https://www.kai.com) | 超维动力 | 4摄 | 1920×1200 | 未公开 | 200Hz IMU | 未公开 | 轻量化头环 | ¥12,999 | [报道链接](https://m.zhidx.com) |
| 30 | [FastUMI Go](https://www.fastumi.com) | 鹿明机器人 | 背包版UMI | 未公开 | 未公开 | 未公开 | 未公开 | 背包形态 | 未公开 | [fastumi.com](https://www.fastumi.com) |
| 31 | [UMI](https://www.orbbec.com.cn) | 奥比中光 | 腕部近场 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 32 | [WristCam](https://www.orbbec.com.cn) | 奥比中光 | 腕部 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 33 | TOBI E2 | TOBI拓比科技 | 双目EGO | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 34 | TOBI E6 | TOBI拓比科技 | EGO | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 35 | TOBI E8 | TOBI拓比科技 | 旗舰EGO | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 36 | [FastUMI Pro](https://www.fastumi.com) | 鹿明机器人 | 多模态无本体 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [fastumi.com](https://www.fastumi.com) |
| 37 | [DexCap UL](https://www.dex-robot.com) | 灵巧智能 | RGB-D+SLAM | 未公开 | 未公开 | IMU | 未公开 | <2kg（轻量化） | 未公开 | [dex-robot.com](https://www.dex-robot.com) |
| 38 | [DexCap GL](https://www.dex-robot.com) | 灵巧智能 | RGB-D+SLAM | 未公开 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [dex-robot.com](https://www.dex-robot.com) |
| 39 | NS MEME | NS（日本） | EOG眼动 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 用户提供 |
| 40 | [Ego-1K Rig](https://www.projectaria.com) | Meta | 12相机（6立体对） | 1280×1280 | 120°HFOV | 未公开 | 未公开 | VR头戴式 | 未公开 | [projectaria.com](https://www.projectaria.com) |

## 详细说明

### 关于本列表

本列表涵盖了目前市场上主要的Ego（Egocentric，第一人称视角）数据采集设备，主要用于具身智能、机器人训练、VLA模型训练等场景的数据采集。这些设备通常采用头戴式、眼镜式或头环形态，以第一人称视角记录人类操作过程。

### 主要参数说明

- **摄像头数量**：从双目到多目（最多12相机），部分设备集成深度传感器
- **分辨率**：从720P到4K不等，高端设备支持2160×2160@60fps
- **FoV（视场角）** ：主流在150°-270°之间，部分设备可达300°以上全景感知
- **IMU（惯性测量单元）** ：多数设备集成6轴或9轴IMU，用于空间定位与姿态感知
- **HDR（高动态范围）** ：仅少数高端设备（如Meta Aria Gen 2具备120dB HDR）明确支持
- **价格**：目前仅超维动力KAI Halo公开价格为12,999元

### 市场趋势

1. **多摄像头趋势**：从早期双目为主，发展到6摄、7摄、8摄甚至12相机的配置
2. **轻量化设计**：主流设备重量在75g-350g之间，追求长时间佩戴舒适性
3. **多传感融合**：RGB+Depth+IMU+触觉等多模态数据同步采集成为标配
4. **头手协同**：头部Ego设备与手部数据采集设备（手套、夹爪等）的毫秒级同步成为行业方向

### 信息补充说明

由于Ego数据采集设备属于新兴的细分赛道，多数厂商尚未公开详细的技术规格表。部分设备的详细参数在公开渠道难以获取，欢迎通过PR补充。

---

*最后更新：2026年8月*
