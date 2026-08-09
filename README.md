# Ego 数据采集设备市场对比

> 本列表聚焦 **Ego（Egocentric，第一人称视角）** 数据采集设备，主要用于具身智能、机器人 VLA 模型训练等场景的数据采集。信息来源于各公司官网、新闻稿及公开技术文档，部分参数为估算值或未公开标注。欢迎提交 PR 补充和修正。


## 设备对比表

| # | 产品名称 | 公司 | 摄像头/传感器配置 | 分辨率 | FoV | IMU | HDR | 重量 | 价格 | 参考链接 |
|---|---------|------|------------------|--------|-----|-----|-----|------|------|---------|
| 1 | [Aria Gen 2](https://www.projectaria.com) | Meta | 1×RGB + 4×CV + 2×眼动 | 12MP RGB | 更宽 FoV（前向立体） | 双 6 轴 IMU | 120dB | 75g | 未公开 | [projectaria.com](https://www.projectaria.com) |
| 2 | [JoyEgoCam](https://baike.baidu.com/item/JoyEgoCam/67635473) | 京东 | 双目 | 2160×2160 @60fps | 130°（H/V） | 车规级 6 轴 IMU | 未公开 | 220g | 未公开 | [百度百科](https://baike.baidu.com/item/JoyEgoCam/67635473) |
| 3 | [Primus Ego](https://cn.piagroup.com) | 均普智能 | 5 路（3×RGB + 双目立体） | 未公开 | >270° | 高精度 IMU | 未公开 | 未公开 | 未公开 | [科技日报报道](https://www.stdaily.com/web/gdxw/2026-07/10/content_545061.html) [citation:3] |
| 4 | [创维 AI 智能眼镜](https://www.skyworthxr.com/views/prodduct/A1.html?did=153065&page=2) | 创维新世界 | 1×1200万像素摄像头 | 12MP | 未公开 | IMU（防抖） | 未公开 | 34.7g | 未公开 | [创维XR官网](https://www.skyworthxr.com) |
| 5 | [EGO RGB-D](https://www.orbbec.com.cn) | 奥比中光 | Gemini330 双目 3D | RGB+深度 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) [citation:8] |
| 6 | [EGO 双目](https://www.orbbec.com.cn) | 奥比中光 | 双目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 7 | [EGO 四目](https://www.orbbec.com.cn) | 奥比中光 | 四目 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 8 | [KAI Halo](https://zhidx.com/p/575454.html) | 超维动力 | 4 路鱼眼全局快门 RGB | 1920×1200 | 未公开 | 200Hz IMU | 未公开 | 轻量化头环 | ¥12,999 | [智东西报道](https://zhidx.com/p/575454.html) |
| 9 | [DAS Ego](https://www.genrobot.com/why) | 简智机器人 | 6×超广角 RGB（多摄像头感知矩阵） | 1600×1300 @30Hz | >270°（H）/ >150°（V） | 6 轴 IMU @200Hz | 全局快门 | 350g | 未公开 | [genrobot.com](https://www.genrobot.com/why) |
| 10 | [FastUMI Ego](https://www.fastumi.com) | 鹿明机器人 | 超广角视觉 | 640×480 | >180°（H/V） | IMU+TOF | 未公开 | 235g | 未公开 | [fastumi.com](https://www.fastumi.com/data-market) |
| 11 | [MEgo View](https://news.ifeng.com/c/8u3Sm70A3pQ) | 觅蜂科技 | 头戴+腕部双视角 | 1080P @60fps | >300° 全景 | 未公开 | 未公开 | 未公开 | 未公开 | [凤凰网报道](https://news.ifeng.com/c/8u3Sm70A3pQ) |
| 12 | [Pika Ego](https://www.agilex.ai/page/690ac4905e78cfa260412ca1) | 松灵机器人 | 第一视角采集系统 | 未公开 | 未公开 | 未公开 | 未公开 | 448g（Pika Pro） | 未公开 | [agilex.ai](https://www.agilex.ai/page/690ac4905e78cfa260412ca1) |
| 13 | [EgoKit](https://36kr.com) | 星忆科技 | 头戴多目视觉终端 | RGB+深度 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [36kr 报道](https://36kr.com) |
| 14 | [OmniEgo](https://www.damon-group.com/company-news-177) | 德马科技 | 头戴式全管线采集系统 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [damon-group.com](https://www.damon-group.com/company-news-177) |
| 15 | [EgoSuite](https://www.lightwheel.ai/egosuite) | 光轮智能 | RGB+Depth+PointCloud | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [lightwheel.ai](https://www.lightwheel.ai/egosuite) |
| 16 | [DexCap](https://www.dex-robot.com/dexCap) | 灵巧智能 | RGB-D LiDAR + 3×SLAM | 未公开 | 未公开 | IMU | 未公开 | 4.2kg（全身） | 未公开 | [dex-robot.com](https://www.dex-robot.com/dexCap) |
| 17 | [Ego Unit](https://www.fairplus.com) | Fairplus | 双 RGB | 2048×1536 @30Hz | 180° 鱼眼 | 6 轴 IMU @120Hz | 未公开 | 157g | 未公开 | 用户提供 |
| 18 | [HeadGo Ego](https://www.foxtech.com) | Foxtech | 双目+RGB×1 | 未公开 | 150°D/128°H/80°V | 9 轴 IMU | 未公开 | 未公开 | 未公开 | 用户提供 |
| 19 | [Tobii Pro Glasses 3](https://www.tobii.com) | Tobii | 场景相机+4 眼动传感器 | 1920×1080 @25fps | 106°H | 未公开 | 未公开 | 76.5g | 未公开 | [tobii.com](https://www.tobii.com) |
| 20 | [LANYVE-OMNI 4P](https://www.aili-light.com) | 艾利光 | 四目同步 | 720P×4 | 220° | 500Hz 高频 IMU | 未公开 | <60g | 未公开 | [aili-light.com](https://www.aili-light.com) |
| 21 | [Lynx HS600](http://www.teledyneoptech.com/en/products/mobile-survey/lynx-hs600/) | Teledyne Optech | 车载移动测绘系统 | 未公开 | 360°（无遮挡） | 未公开 | 未公开 | 未公开 | 未公开 | [teledyneoptech.com](http://www.teledyneoptech.com/en/products/mobile-survey/lynx-hs600/) |
| 22 | [MEgo Gripper](https://news.ifeng.com/c/8u3Sm70A3pQ) | 觅蜂科技 | 二指夹爪+视觉 | 1080P @60fps | 200° 鱼眼 | 未公开 | 未公开 | 480g | 未公开 | [凤凰网报道](https://news.ifeng.com/c/8u3Sm70A3pQ) |
| 23 | [深度机智 头戴式](https://deepcybo.top) | 深度机智 | 头戴感知模块 | 未公开 | 未公开 | 未公开 | 未公开 | 分体式设计 | 未公开 | [deepcybo.top](https://deepcybo.top) |
| 24 | [灵初智能 外骨骼手套](https://www.psibot.ai) | 灵初智能 | 视觉+触觉+关节传感 | 未公开 | 未公开 | 未公开 | 未公开 | 轻量化 | 未公开 | [psibot.ai](https://www.psibot.ai) |
| 25 | [FastUMI Go](https://www.fastumi.com) | 鹿明机器人 | 背包版 UMI | 未公开 | 未公开 | 未公开 | 未公开 | 背包形态 | 未公开 | [fastumi.com](https://www.fastumi.com) |
| 26 | [UMI](https://www.orbbec.com.cn) | 奥比中光 | 腕部近场 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 27 | [WristCam](https://www.orbbec.com.cn) | 奥比中光 | 腕部 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [orbbec.com.cn](https://www.orbbec.com.cn) |
| 28 | [DexCap UL](https://www.dex-robot.com/dexCap) | 灵巧智能 | RGB-D+SLAM（轻量版） | 未公开 | 未公开 | IMU | 未公开 | <2kg | 未公开 | [dex-robot.com](https://www.dex-robot.com/dexCap) |
| 29 | [DexCap GL](https://www.dex-robot.com/dexCap) | 灵巧智能 | RGB-D+SLAM（旗舰版） | 未公开 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [dex-robot.com](https://www.dex-robot.com/dexCap) |
| 30 | [Ego-1K Rig](https://www.projectaria.com) | Meta | 12 相机（6 立体对） | 1280×1280 | 120°HFOV | 未公开 | 未公开 | VR 头戴式 | 未公开 | [projectaria.com](https://www.projectaria.com) |
| 31 | [TOBI E2](https://www.tobi.cn) | TOBI 拓比科技 | 多路传感器阵列 | 未公开 | 全景覆盖 | 未公开 | 未公开 | 未公开 | 未公开 | [tobi.cn](https://www.tobi.cn/portal/resolve/resolve_03) |
| 32 | [TOBI E6](https://www.tobi.cn) | TOBI 拓比科技 | 6 路相机硬同步 | 未公开 | DFOV 200° | 未公开 | 未公开 | 370g | 未公开 | [tobi.cn](https://www.tobi.cn/portal/resolve/resolve_03) |
| 33 | [TOBI E8](https://www.tobi.cn) | TOBI 拓比科技 | 多模态旗舰 | 未公开 | 270°FOV | 未公开 | 未公开 | 未公开 | 未公开 | [tobi.cn](https://www.tobi.cn/portal/resolve/resolve_03) |
| 34 | [Delta D1](https://deltai.com/) | 德塔智能 | 头戴式全身全景采集 | 未公开 | 全景 | 未公开 | 未公开 | 未公开 | 未公开 | [经济日报报道](http://rss.jingjiribao.cn/static/detail.jsp?id=673023) |
| 35 | [美格智能 数采方案](https://www.meigsmart.com/articledetail/632.html) | 美格智能 | AI模组+可穿戴/多视角 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [钛媒体报道](https://m.tmtpost.com/nictation/8089069.html) |
| 36 | [AH-D 双目面捕头盔](https://m.virdync.com/cn/h-nd-1651.html) | 虚拟动力（Virdync） | 双目摄像头 | 未公开 | 未公开 | 未公开 | 未公开 | 320g | 未公开 | [virdync.com](https://m.virdync.com/cn/h-nd-1651.html) |
| 37 | [SenseHub](https://www.tars.com) | 它石智航（TARS） | 五指/两指手套 + 第一视角摄像机 | 未公开 | 未公开 | IMU | 未公开 | 轻量化 | 未公开 | [网易报道](https://m.163.com/dy/article/KKOM5TA505568W0A.html) |
| 38 | [StellarNex DualEgo](https://www.xiaohongshu.com/explore/6a54a21e0000000015026726?xsec_token=ABMiCZ7943Dh8x03-zchVss8TDWjaJGzebR8wrY5zaNBU=&xsec_source=pc_search&source=web_explore_feed) | 星际硅途 | 动作捕捉+视觉感知+语义标注 | 未公开 | 未公开 | IMU | 未公开 | 未公开 | 未公开 | [交大报道](https://itf.sjtu.edu.cn/itf/news/96010.html |
| 39 | [BeingBeyond OpenMMEgo](https://github.com/BeingBeyond/OpenMMEgo) | 智在无界（BeingBeyond） | 第一人称视频数据平台 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | 未公开 | [GitHub](https://github.com/BeingBeyond/OpenMMEgo) |

## 详细说明

### 关于本列表

本列表涵盖目前市场上主要的 Ego（Egocentric，第一人称视角）数据采集设备，主要用于具身智能、机器人训练、VLA 模型训练等场景的数据采集。这些设备通常采用头戴式、眼镜式或头环形态，以第一人称视角记录人类操作过程。

Ego 第一人称采集是目前具身智能数据采集中被认为兼具**轻量化、低成本和强通用性**优势的主流路线之一。

### 主要参数说明

- **摄像头/传感器配置**：从单目到多目（最多 12 相机），部分设备集成深度传感器和触觉模块
- **分辨率**：从 720P 到 4K 不等，部分设备支持 2160×2160@60fps
- **FoV（视场角）** ：主流在 150°-270° 之间，部分设备可达 300° 以上全景感知
- **IMU（惯性测量单元）** ：多数设备集成 6 轴或 9 轴 IMU，用于空间定位与姿态感知
- **HDR（高动态范围）** ：仅少数高端设备（如 Meta Aria Gen 2 具备 120dB HDR）明确支持
- **价格**：目前仅超维动力 KAI Halo 公开价格为 12,999 元

### 市场趋势

1. **多摄像头趋势**：从早期双目为主，发展到 6 摄、7 摄甚至 12 相机的配置
2. **轻量化设计**：主流设备重量在 75g-370g 之间，创维 AI 眼镜仅 34.7g
3. **多传感融合**：RGB+Depth+IMU+触觉等多模态数据同步采集成为标配
4. **工业场景深化**：均普智能、德塔智能等厂商将 Ego 设备深度锚定工业制造场景 [citation:3][citation:9]

### 信息补充说明

由于 Ego 数据采集设备属于新兴赛道，多数厂商尚未公开详细技术规格表。部分设备参数来源于公开报道或用户提供，欢迎通过 PR 补充和修正。

---

*最后更新：2026 年 8 月*
