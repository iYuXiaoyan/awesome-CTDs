# 世界上的各种CTD（v0.2)

> **CTD/C/T/D 厂家、型号及规格的详尽列表 (修订版)**

本文是由于小焱基于公开信息整理，完成了一个尽量详尽的、多层级的列表，涵盖了主要制造商、核心元件供应商、专业应用厂家、关键研究/计量机构以及中国的相关单位。尽可能提供了详细规格，但是由于信息获取的局限性（特别是漂移数据和旧型号），并不能完全覆盖所有信息，有些信息可能存在错误，请仔细甄别。

**我们已经梳理和列出了包括：**

-   **顶级国际 CTD 制造商:** Sea-Bird, RBR, Valeport, AML, Idronaut, NKE, FSI, Sea & Sun, SAIV 等。
-   **日本主要制造商:** JFE Advantech, TSK。
-   **专注于特定领域或传感器的国际公司:** Star-Oddi (微型), Aanderaa (长期观测), KELLER & Paroscientific (压力传感器), Teledyne 旗下多家公司 (uCTD, SVP, 集成), Odom (SVP), Nortek (集成 T/P), PME (小型记录仪), In-Situ & OTT Hydromet (水质仪集成), Aquatec, Turner, Sequoia, Rockland 等。
-   **中国主要制造商和机构:** 国家海洋技术中心 (NOTC), 青岛道万, 杭州海询/谱海, 杭州浅海, 无锡海鹰加科, 山东科学院海洋仪器仪表研究所, 中科院相关研究所, 广州海洋地质调查局等。



## **A. 主要海洋学仪器制造商**

**1. Sea-Bird Scientific (美国)**

*   **厂家简介:** 全球 CTD 市场领导者。以其仪器的准确度高、产品线全面、校准服务权威而闻名。
*   **核心传感器来源 (推测/部分已知):**
    *   **温度 (T):** 采用高稳定性铂电阻温度计 (PRT) 元件 (很可能来自顶级供应商如 Heraeus, IST AG 等，经 Sea-Bird 严格筛选、老化和标定)。采用自有专利设计 (例如 SBE 3 传感器)。
    *   **电导率 (C):** 采用专利的、自主设计和制造的电导池 (例如 SBE 4 硼硅玻璃/铂电极电导池)。电导测量技术是其核心竞争力。
    *   **压力 (P/D):**
        *   对于最高精度/稳定性的应用，采用 **Paroscientific Digiquartz®** 石英谐振式传感器 (例如 SBE 9plus, SBE 26plus, SBE 50)。
        *   其他多数型号采用高品质的压阻传感器 (例如 SBE 19plus V2, SBE 37, SBE 49)。这些压阻传感器的具体供应商通常不公开，但*可能*包括 **Druck** (现属 Baker Hughes，前属 GE)、**Keller**、**TE Connectivity** 或其他满足 Sea-Bird 规格的厂家。
        *   历史上，**Paine Electronics** 可能用于特定的超高压需求，或**Kistler** (主要生产压电式传感器) 。
*   **代表性型号及规格:**

    *   **CTD - 剖面测量类:**
        *   **型号:** SBE 9plus CTD (常与 SBE 11plus V2 甲板单元组成 SBE 911plus 系统)
            *   **应用:** 高精度船载实时剖面测量系统 (WOCE 标准)。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.001 °C; 分辨率 0.0003 °C; 年漂移 (典型) < 0.001 °C/年。
                *   电导率 (C): 量程 0 至 7 S/m; 准确度 ±0.0003 S/m (±0.003 mS/cm); 分辨率 0.00004 S/m (0.0004 mS/cm); 月漂移 (典型) < 0.0003 S/m/月 (< 0.003 mS/cm/月)。
                *   压力 (P/D, 石英): 可用量程至 10500 dbar; 准确度 ±0.015% FS (满量程); 分辨率 0.001% FS; 年漂移 (典型) < 0.015% FS/年。
            *   **备注:** 采样率 24 Hz。SBE 917plus 是其自容版本 (使用 SBE 17plus VME Searam 记录单元)。
        *   **型号:** SBE 19plus V2 SeaCAT Profiler CTD
            *   **应用:** 自容或实时剖面测量 (中高精度)。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.005 °C; 分辨率 0.0001 °C; 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 9 S/m; 准确度 ±0.0005 S/m (±0.005 mS/cm); 分辨率 0.00005 S/m (0.0005 mS/cm); 月漂移 (典型) < 0.0008 S/m/月 (< 0.008 mS/cm/月)。
                *   压力 (P/D, 压阻式): 可用量程 20 至 7000 dbar; 准确度 ±0.1% FS; 分辨率 0.002% FS; 年漂移 (典型) < 0.05% FS/年。
            *   **备注:** 采样率 4 Hz (可选 8 Hz)。SBE 19 (无 plus) 是更早的型号，已被取代。
        *   **型号:** SBE 25plus Sealogger CTD
            *   **应用:** 自容式剖面 CTD，采样率较高。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.002 °C; 分辨率 0.0001 °C; 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 7 S/m; 准确度 ±0.0003 S/m (±0.003 mS/cm); 分辨率 0.00007 S/m (0.0007 mS/cm); 月漂移 (典型) < 0.0003 S/m/月 (< 0.003 mS/cm/月)。
                *   压力 (P/D, 标配压阻式, 可选石英): 可用量程至 7000 dbar (压阻); 准确度 ±0.1% FS (压阻) / ±0.015% FS (石英); 分辨率 0.001% FS (压阻) / 0.0005% FS (石英); 年漂移 (典型) < 0.05% FS/年 (压阻) / < 0.015% FS/年 (石英)。
            *   **备注:** 采样率 16 Hz。SBE 25 (无 plus) 是早期型号 (8 Hz)。
        *   **型号:** SBE 49 FastCAT CTD
            *   **应用:** 适用于高速载体 (AUV, ROV, 拖体) 的实时剖面 CTD。
            *   **规格:**
                *   温度 (T): 量程 -5 至 45 °C; 准确度 ±0.005 °C; 分辨率 0.0001 °C; 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 7 S/m; 准确度 ±0.0005 S/m (±0.005 mS/cm); 分辨率 0.00005 S/m (0.0005 mS/cm); 月漂移 (典型) < 0.0008 S/m/月 (< 0.008 mS/cm/月)。
                *   压力 (P/D, 压阻式): 可用量程 20 至 7000 dbar; 准确度 ±0.1% FS; 分辨率 0.002% FS; 年漂移 (典型) < 0.05% FS/年。
            *   **备注:** 采样率 16 Hz。
        *   **型号:** SBE 41/41CP/41N Argo Float CTD
            *   **应用:** Argo 剖面浮标核心传感器 (特别强调高稳定性)。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.002 °C; 分辨率 0.00025 °C; 年漂移 (保证值) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 6.5 S/m; 准确度 ±0.0003 S/m (±0.003 mS/cm); 分辨率 0.00001 S/m (0.0001 mS/cm); 年漂移 (保证值) < 0.003 S/m/年 (< 0.03 mS/cm/年)。
                *   压力 (P/D, 压阻式): 量程约 2000/2600 dbar; 准确度 ±2.4 dbar; 分辨率 0.05 dbar; 年漂移 (保证值) < 0.5 dbar/年。
        *   **型号:** SBE 61 Deep Argo CTD
            *   **应用:** 深海 Argo 浮标 (4000-6000m)。
            *   **规格:** T/C 稳定性同 SBE 41。P 量程至 6000 dbar, 准确度目标 ±3 dbar, 漂移目标 < 1 dbar/年。
        *   **型号:** Glider Payload CTD (GPCTD)
            *   **应用:** 水下滑翔机专用 CTD。
            *   **规格:** 通常基于 SBE 37 技术。T 准确度 ±0.002 °C, C 准确度 ±0.0003 S/m, P 准确度 ±1 dbar 或 0.1% FS。漂移类似 SBE 37。

    *   **CTD/TC/CT(D) - 锚系观测类:**
        *   **型号:** SBE 16plus V2 SeaCAT CT(D) Recorder
            *   **应用:** 高精度锚系观测 (自容或实时)。
            *   **规格:**
                *   温度 (T): 准确度 ±0.005 °C (可选 ±0.001 °C TC-Ducted); 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 准确度 ±0.0005 S/m (可选 ±0.0003 S/m TC-Ducted); 月漂移 (典型) < 0.0008 S/m/月。
                *   压力 (P/D, 压阻式或可选石英): 准确度 ±0.1% FS (压阻) / ±0.015% FS (石英); 年漂移 (典型) < 0.05% FS/年 (压阻) / < 0.015% FS/年 (石英)。
            *   **备注:** -IM 型号是感应耦合版本。SBE 16 (无 plus) 和 SBE 16plus 是早期型号。
        *   **型号:** SBE 37 MicroCAT (系列 - SI, SIP, SM, SMP, IM, IMP 等)
            *   **应用:** 长期低功耗锚系观测 (自容或感应/串口)。
            *   **规格 (以高精度有泵型 SBE 37-SIP 为例):**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.002 °C; 分辨率 0.0001 °C; 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 7 S/m; 准确度 ±0.0003 S/m (±0.003 mS/cm); 分辨率 0.00001 S/m (0.0001 mS/cm); 月漂移 (典型) < 0.0003 S/m/月 (< 0.003 mS/cm/月)。
                *   压力 (P/D, 压阻式): 量程 20 至 7000 dbar; 准确度 ±0.1% FS (可选 ±0.05% 或 ±0.02%); 分辨率 0.002% FS; 年漂移 (典型) < 0.05% FS/年。
            *   **备注:** SM/SMP 型号精度较低 (T:±0.01°C, C:±0.001 S/m)。IM/IMP 是感应耦合型。
        *   **型号:** HydroCAT / HydroCAT-EP V2
            *   **应用:** 长期水质监测仪 (CTD+溶解氧+可选 pH/ORP)。
            *   **规格 (CTD 部分):** 类似 SBE 37 高精度型号。带防污措施。

    *   **TD (温度, 深度/压力):**
        *   **型号:** SBE 39plus / 39plus-IM Temperature/Pressure Recorder
            *   **应用:** 自容式或感应耦合式 T/D 记录。
            *   **规格:** T: 准确度 ±0.002 °C (<0.002 °C/年漂移); P: 准确度 ±0.1% FS (<0.05% FS/年漂移)。
        *   **型号:** SBE 52-MP Moored Profiler CTD/CT/T/TD
            *   **应用:** 搭载在系留剖面仪上。可配置为 TD。
            *   **规格:** 基于 SBE 37 技术。

    *   **D (深度/压力):**
        *   **型号:** SBE 26plus Seagauge Wave & Tide Recorder
            *   **应用:** 高精度潮位和波浪测量。
            *   **规格 (核心为压力):** P (石英) 准确度 ±0.01% FS; 年漂移 < 0.01% FS/年。附带 T 测量 ±0.01 °C。
        *   **型号:** SBE 50 Digital Ocean Pressure Sensor
            *   **应用:** 高精度压力/深度传感器，用于集成。
            *   **规格:** P (石英) 量程至 10500 dbar; 准确度 ±0.01% FS; 分辨率 0.0002% FS; 年漂移 < 0.01% FS/年。
        *   **型号:** SBE 29 Strain-Gauge Pressure Sensor
            *   **应用:** 模拟输出压力传感器，用于集成。
            *   **规格:** P (压阻式) 准确度 ±0.1% FS (可选至 0.01%); 漂移取决于精度等级。

    *   **T (温度):**
        *   **型号:** SBE 3plus / 3F / 3S Temperature Sensor
            *   **应用:** 高精度参考级温度传感器。
            *   **规格:** 准确度 ±0.001 °C; 年漂移 < 0.001 °C/年。
        *   **型号:** SBE 38 Secondary Temperature Sensor
            *   **应用:** 用于 SBE 9plus 双温配置。规格同 SBE 3plus。
        *   **型号:** SBE 56 Temperature Logger
            *   **应用:** 低成本自容式温度记录仪。
            *   **规格:** 准确度 ±0.01 °C; 年漂移 < 0.005 °C/年。

    *   **C (电导率):**
        *   **型号:** SBE 4 / 4C Conductivity Sensor
            *   **应用:** 高精度参考级电导率传感器。
            *   **规格:** 准确度 ±0.0003 S/m (±0.003 mS/cm); 月漂移 < 0.0003 S/m/月 (< 0.003 mS/cm/月)。

    *   **TC (温盐仪):**
        *   **型号:** SBE 21 Thermosalinograph
            *   **应用:** 船用表层水温盐连续测量。
            *   **规格:** T 准确度 ±0.001 °C, C 准确度 ±0.0003 S/m。无压力传感器。

    *   **旧型号 (部分提及):** SBE 9, SBE 16, SBE 19, SBE 25, SBE 37 (早期版本), SBE 39 (早期版本), SBE 21 (早期版本)。规格通常低于现行 'plus' 或 'V2' 版本，漂移数据更难获取。SBE 17 是 SBE 917plus 的核心记录单元。SBE 20/20Plus 可能是更早期的型号。SBE 5 (P) 和 SBE 5T (T) 是早期的模块化传感器。

**2. RBR (加拿大)**

*   **厂家简介:** 以仪器的准确度高、易用性强（USB-C 接口，部分型号带 Wi-Fi）、功耗低和快速定制响应而闻名。产品线覆盖从微型记录仪到高精度多通道记录器及石英压力计。
*   **核心传感器来源 (推测/部分已知):**
    *   **温度 (T):** 使用高稳定性 PRT 或热敏电阻元件 (具体类型取决于型号和精度要求)，经过 RBR 精心标定。
    *   **电导率 (C):** 采用电极式电导池，设计和制造工艺是其专长之一，注重稳定性和抗污染。
    *   **压力 (P/D):**
        *   标准型号 (Concerto³, Virtuoso³, Solo³, Duet³) 通常采用高品质的压阻传感器 (供应商未公开，可能包括 Keller, TE Connectivity 等)。
        *   高精度海底压力和潮位记录仪 (RBRquartz³ 系列) 明确使用 **Paroscientific Digiquartz®** 石英谐振式传感器。
*   **代表性型号及规格:**

    *   **CTD (电导率, 温度, 深度/压力)**
        *   **型号:** RBRconcerto³ C.T.D
            *   **应用:** 高精度剖面或系留测量，可扩展多通道。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.002 °C; 分辨率 < 0.00005 °C; 年漂移 (典型) < 0.002 °C/年。
                *   电导率 (C): 量程 0 至 85 mS/cm; 准确度 ±0.003 mS/cm (±0.0003 S/m); 分辨率 < 0.0001 mS/cm; 年漂移 (典型) < 0.010 mS/cm/年 (< 0.001 S/m/年)。
                *   压力 (P/D, 标准压阻式): 可用量程 20 至 10000 dbar; 准确度 ±0.05% FS; 分辨率 < 0.001% FS; 年漂移 (典型) < 0.05% FS/年。
            *   **备注:** 最高 32 Hz 采样。可选 Wi-Fi, 多种外壳。
        *   **型号:** RBRvirtuoso³ C.T.D
            *   **应用:** 高精度系留观测。
            *   **规格:** (传感器规格同 Concerto³) T: ±0.002 °C; C: ±0.003 mS/cm; P: ±0.05% FS。相应漂移同上。
            *   **备注:** 最高 2 Hz 采样 (CTD模式)，侧重低功耗。
        *   **型号:** RBRlegato³ C.T.D
            *   **应用:** OEM CTD，用于集成到第三方平台 (AUV, Glider, Floats)。
            *   **规格:** (传感器规格同 Concerto³) T: ±0.002 °C; C: ±0.003 mS/cm; P: ±0.05% FS。相应漂移同上。
            *   **备注:** 最高 32 Hz 采样，紧凑、低功耗。
        *   **型号:** RBRmaestro³ C.T.D (多通道记录仪平台)
            *   **应用:** 可集成多个 RBR 或第三方传感器的系留/剖面平台。
            *   **规格 (CTD 核心):** 同 RBRconcerto³。
            *   **备注:** 最多 10 个通道。
        *   **旧型号:** RBR XR-420 / XR-620 CTD (Concerto/Maestro 的前代)
            *   **应用:** 多通道记录仪平台。
            *   **规格 (基于历史数据):** 精度可能略低于 ³ 代产品，例如 T: ±0.005°C, C: ±0.01 mS/cm, P: ±0.1% FS。漂移数据难考证。

    *   **TD (温度, 深度/压力)**
        *   **型号:** RBRconcerto³ T.D / RBRvirtuoso³ T.D / RBRduet³ T.D
            *   **应用:** 高精度/小型 T/D 记录。
            *   **规格:** T: ±0.002 °C (<0.002 °C/年漂移); P: ±0.05% FS (<0.05% FS/年漂移)。Duet³ 最高 8 Hz。
        *   **型号:** RBRduet³ T.D|deep / RBRsolo³ T|deep (深海型号)
            *   **应用:** 深海温度或温深记录。
            *   **规格:** 压力传感器量程可达 10000 dbar。T/P 准确度和漂移同标准型号。
        *   **旧型号:** TDR-2050 / TR-1050 / TR-1060 (早期 Richard Brancker Research 型号或继承)
            *   **TDR-2050 (代表性):** T: ±0.002 °C; P (石英): 至 ~7000m, ±0.01% FS (<0.01% FS/年漂移)。
            *   **TR-1060:** (现由 Lowell Instruments 生产) T: ±0.002 °C (<0.002 °C/年); P: ±0.05% FS (<0.05% FS/年)。
        *   **旧型号:** TGR-1050 / TGR-2050 (温度梯度记录仪，也可作 T/TD)
            *   **TGR-1050 (代表性):** T: ±0.002 °C; (若有P) P: ±0.1% FS。漂移信息难考证。

    *   **TC (温度, 电导率)**
        *   **型号:** RBRconcerto³ T.C / RBRvirtuoso³ T.C / RBRduo³ C.T (可配置)
            *   **应用:** T/C 测量。
            *   **规格:** T: ±0.002 °C (<0.002 °C/年); C: ±0.003 mS/cm (<0.010 mS/cm/年)。

    *   **D (深度/压力)**
        *   **型号:** RBRconcerto³ D / RBRvirtuoso³ D / RBRduet³ D / RBRsolo³ D
            *   **应用:** 单独的压力/深度记录 (标准压阻式)。
            *   **规格:** P: ±0.05% FS; 年漂移 < 0.05% FS/年。Solo³ 最高 2 Hz。
        *   **型号:** RBRquartz³ BPR / BPR|zero (海底压力记录仪)
            *   **应用:** 高精度海底压力/潮位长期观测。
            *   **规格:** (使用 Paroscientific Digiquartz® 传感器)
                *   压力 (P/D): 量程至 ~7000 dbar 或更高; 准确度 ±0.01% FS; 分辨率 ppb 级; 年漂移 (典型) < 0.01% FS/年。
        *   **型号:** RBRquartz³ Q / Q|plus (潮汐和波浪记录仪)
            *   **应用:** 高精度潮汐和波浪测量。
            *   **规格:** (使用 Paroscientific Digiquartz® 或高精度压阻传感器) P 准确度 ±0.01% FS (石英) 或更高。
        *   **型号:** RBRquartz³ APT (高精度压力变送器)
            *   **应用:** 集成用高精度压力传感器。
            *   **规格:** (石英传感器) P 准确度 ±0.01% FS。

    *   **T (温度)**
        *   **型号:** RBRconcerto³ T / RBRvirtuoso³ T / RBRsolo³ T
            *   **应用:** 单独的温度记录。
            *   **规格:** T: ±0.002 °C; 年漂移 < 0.002 °C/年。Solo³ 最高 2 Hz。
        *   **型号:** RBRconcerto³ Tx (温度链)
            *   **应用:** 多点温度剖面系留测量。
            *   **规格:** 可连接多个 RBR T 或第三方温度传感器。

    *   **C (电导率)**
        *   **型号:** RBRconcerto³ C / RBRvirtuoso³ C (可配置)
            *   **应用:** 单独的电导率记录。
            *   **规格:** C: ±0.003 mS/cm; 年漂移 < 0.010 mS/cm/年。

    *   **备注:** RBR 的 ³ 代产品线是当前主力。旧型号（如 TDR, TGR, XR 系列）虽可能仍在用，但规格和支持可能有限。

---

**3. Valeport (英国)**

*   **厂家简介:** 产品线广泛，以坚固耐用和可靠性著称，在感应式电导、声速和压力测量方面有专长。
*   **核心传感器来源 (推测/部分已知):**
    *   **温度 (T):** 使用 PRT 元件，经 Valeport 标定。
    *   **电导率 (C):** **感应式电导**是其特色和优势技术，自主设计和制造。也提供**电极式电导**型号。
    *   **压力 (P/D):** 自主设计和制造**高精度压阻传感器** (精度可达 0.01%FS)，也可能在其最高精度潮位计中使用**谐振式石英传感器** (可能来自 Paroscientific 或类似供应商)。
*   **代表性型号及规格:**

    *   **CTD (电导率, 温度, 深度/压力)**
        *   **型号:** MIDAS CTD+
            *   **应用:** 剖面或系留观测，多参数平台。
            *   **规格:**
                *   温度 (T): 量程 -5 至 35 °C; 准确度 ±0.005 °C; 分辨率 0.001 °C; 漂移: 未明确说明。
                *   电导率 (C, 感应式): 量程 0 至 80 mS/cm; 准确度 ±0.01 mS/cm (±0.001 S/m); 分辨率 0.001 mS/cm; 漂移: 未明确说明 (感应式通常较稳定)。
                *   压力 (P/D, 压阻式): 量程 10 至 6000 dbar; 准确度 ±0.01% FS; 分辨率 0.001% FS; 年漂移 (典型) < 0.02% FS/年。
            *   **备注:** 采样率 1, 2, 4, 8 Hz。钛合金外壳。
        *   **型号:** SWiFT CTD
            *   **应用:** 手持式快速剖面测量。
            *   **规格:**
                *   温度 (T): 准确度 ±0.01 °C; 分辨率 0.001 °C。
                *   电导率 (C, 电极式): 准确度 ±0.05 mS/cm; 分辨率 0.001 mS/cm。
                *   压力 (P/D): 量程 50 dbar; 准确度 ±0.1% FS (可选 0.01%)。
            *   **备注:** 内置 GPS, 蓝牙, 无线充电。漂移信息未详述。
        *   **型号:** miniCTD / monitorCTD
            *   **应用:** 小型化剖面或系留。
            *   **规格:** T: ±0.01 °C; C(电极式): ±0.01 mS/cm; P: ±0.1% FS (可选 0.01%)。漂移信息未详述。
        *   **型号:** fastCTD Profiler
            *   **应用:** 快速剖面优化。
            *   **规格:** T: ±0.005 °C; C(电极式): ±0.005 mS/cm; P: ±0.01% FS。高采样率。漂移信息未详述。
        *   **旧型号:** Model 600 Series (例如 606 CTD) (可能已停产)。规格需查旧资料。

    *   **TD (温度, 深度/压力)**
        *   **型号:** miniTIDE
            *   **应用:** 潮位和温度记录。
            *   **规格:** T: ±0.01 °C; P(压阻式): 量程 10-600 dbar, 准确度 ±0.01% FS (<0.02% FS/年漂移)。
        *   **型号:** MIDAS WTR (Water Level Recorder)
            *   **应用:** 高精度潮位和温度记录。
            *   **规格:** T: ±0.01 °C; P(谐振式或高精度压阻式): 准确度 ±0.01% FS; 年漂移 < 0.01% FS/年 (谐振式) 或 < 0.02% FS/年 (压阻式)。

    *   **D (深度/压力)**
        *   **型号:** miniIPS (智能压力传感器)
            *   **应用:** 集成用压力/深度传感器。
            *   **规格:** P(压阻式): 量程 10-6000 dbar; 准确度 ±0.01% FS; 年漂移 < 0.02% FS/年。
        *   **型号:** TideMaster Portable Water Level Recorder
            *   **应用:** 便携式潮位计。
            *   **规格:** P 准确度 ±0.1% FS (典型)。

    *   **T (温度)**
        *   **型号:** miniT Recorder
            *   **应用:** 自容式温度记录。
            *   **规格:** T 准确度 ±0.01 °C。

    *   **TC / C:** 独立产品较少。

*   **备注:** Valeport 的文档通常很详细，但漂移数据并非对所有型号都明确标注。

**4. AML Oceanographic (加拿大)**

*   **厂家简介:** 以 Xchange™ 可现场插拔、独立校准的传感器系列为核心特色，提供灵活配置的仪器平台。漂移数据通常指传感器本身在推荐校准周期内的性能。
*   **核心传感器来源:** AML 自主设计和制造其 Xchange™ 系列传感器，包括温度、电导率和压阻式压力传感器。这使其能够控制整个测量链并提供模块化的校准服务。
*   **核心 Xchange™ 传感器 (决定仪器性能)**
    *   **传感器类型:** **Temperature Xchange™ (T•Xchange)**
        *   **规格:**
            *   量程: -5 至 +45 °C
            *   准确度: ±0.005 °C
            *   分辨率: 0.0001 °C
            *   年漂移 (典型): < 0.005 °C/年
    *   **传感器类型:** **Conductivity Xchange™ (C•Xchange)**
        *   **规格:**
            *   量程: 0 至 70 mS/cm (或更高范围可选)
            *   准确度: ±0.01 mS/cm (±0.001 S/m)
            *   分辨率: 0.001 mS/cm (0.0001 S/m)
            *   年漂移 (典型): < 0.02 mS/cm/年 (< 0.002 S/m/年) (AML 建议每年校准以维持精度)
    *   **传感器类型:** **Pressure Xchange™ (P•Xchange)** (压阻式)
        *   **规格:**
            *   可用量程: 10, 20, 50, 100, 200, 300, 500, 1000, 2000, 4000, 6000 dbar
            *   准确度: ±0.05% FS (标准); 可选 ±0.02%, ±0.01% FS
            *   分辨率: 0.001% FS
            *   年漂移 (典型): < 0.05% FS/年 (标准); 更高精度选项漂移 < 0.02% / < 0.01% FS/年 (需确认具体型号)
    *   **传感器类型:** **Sound Velocity Xchange™ (SV•Xchange)** (常与 T/P 结合)
        *   **规格:** 准确度 ±0.02 m/s (典型)。
    *   **其他传感器:** Turbidity•Xchange™, Chl•Xchange™, pH•Xchange™, DO•Xchange™ 等。

*   **仪器平台 (可配置为 CTD, TD, TC, D, T, C, SV 等)**
    *   **平台系列:** AML-3 / AML-6 Series
        *   **应用:** 实时/自容, 3 或 6 传感器端口，剖面或系留。
        *   **采样率:** 最高 10 Hz (AML-3) 或 25 Hz (AML-6)。
        *   **性能:** 由所选 Xchange™ 传感器决定。
    *   **平台系列:** Base•X₂ / Plus•X
        *   **应用:** 剖面仪。Base•X₂ 小型，Plus•X 实时输出。
        *   **性能:** 由所选 Xchange™ 传感器决定。
    *   **平台系列:** Metrec•X / Metrec•XL
        *   **应用:** 长期系留记录仪。
        *   **性能:** 由所选 Xchange™ 传感器决定。XL 型电池容量更大。
    *   **平台系列:** Minos•X
        *   **应用:** 小型多参数仪 (ROV, AUV)。
        *   **性能:** 由所选 Xchange™ 传感器决定。
    *   **平台系列:** Micro•X
        *   **应用:** 超小型单参数记录仪 (可配 T•Xchange 或 P•Xchange)。
        *   **性能:** 由所选 Xchange™ 传感器决定。
    *   **型号 (特定应用):** MVP300 / MVP30 / MVPX (Moving Vessel Profiler 系统)
        *   **应用:** 搭载在走航船只上进行快速剖面测量，使用 AML 的仪器作为核心传感器。
        *   **性能:** 取决于探头配置的 Xchange™ 传感器。
    *   **旧型号:** 可能存在基于早期传感器技术的平台，如 Smart•X 等，规格需查阅历史资料。

*   **总结:** AML 通过其模块化设计，提供了所有 CTD, TD, TC, D, T, C 的组合。其性能指标和漂移取决于用户选择的具体 Xchange™ 传感器类型和精度等级。

---

**5. Idronaut (意大利)**

*   **厂家简介:** 以制造极高精度的海洋测量仪器闻名，尤其在深海 CTD 领域处于领先地位。漂移数据是其关键优势之一。
*   **核心传感器来源:** Idronaut 自主研发和制造其核心的高精度温度传感器 (铂电阻)、电导率传感器 (独特的 7 铂金电极石英电导池) 和压力传感器 (包括高精度压阻式和石英谐振式，石英可能与顶级供应商合作或基于其技术)。
*   **代表性型号及规格:**

    *   **CTD (电导率, 温度, 深度/压力)**
        *   **型号:** OCEAN SEVEN 316Plus CTD
            *   **应用:** 高精度剖面/系留观测 (旗舰型号之一)。
            *   **规格:**
                *   温度 (T): 量程 -2 至 40 °C; 准确度 ±0.0015 °C; 分辨率 0.0001 °C; 年漂移 (典型) < 0.001 °C/年。
                *   电导率 (C, 7电极石英池): 量程 0 至 70 mS/cm; 准确度 ±0.0018 mS/cm (±0.00018 S/m); 分辨率 0.0001 mS/cm; 年漂移 (典型) < 0.003 mS/cm/年 (< 0.0003 S/m/年)。
                *   压力 (P/D, 石英传感器): 量程 100 至 10000 dbar; 准确度 ±0.01% FS; 分辨率 0.0001% FS; 年漂移 (典型) < 0.01% FS/年。 (可选压阻式，精度略低)
            *   **备注:** 最高 25 Hz 采样。
        *   **型号:** OCEAN SEVEN 320Plus CTD
            *   **应用:** WOCE 级全海深多参数 CTD。
            *   **规格:** CTD 核心规格同 316Plus (或更高，如 40Hz 采样)。
        *   **型号:** OCEAN SEVEN 304 CTD (早期型号，可能仍有使用)
            *   **规格:** 精度可能略低于 316Plus，但仍属高精度。年漂移是其优势。
        *   **型号:** OCEAN SEVEN 310 Multiparameter CTD
            *   **应用:** 低功耗自容/剖面多参数 CTD。
            *   **规格:** T: ~±0.003°C, C: ~±0.003 mS/cm, P: ~±0.02% FS (压阻)。漂移性能依然优秀。
        *   **型号:** OCEAN SEVEN 308 CTD Logger
            *   **应用:** 极低功耗，长期系留。
            *   **规格:** T: ±0.005°C, C: ±0.005 mS/cm, P: ±0.05% FS (压阻)。漂移控制严格。
        *   **型号:** OCEAN SEVEN 305 Micro CTD / OCEAN SEVEN 28 Micro CTD
            *   **应用:** 小型化高精度 CTD (AUV/ROV)。
            *   **规格:** (305) T: ±0.003°C, C: ±0.003 mS/cm, P: ±0.02% FS。
        *   **型号:** OCEAN SEVEN 319 Deep Ocean CTD (全海深)
            *   **应用:** 11000m 级探测。
            *   **规格:** 核心 CTD 指标同 316Plus，压力传感器特殊设计。

    *   **TD / TC / D / T / C:** Idronaut 提供高精度的独立传感器模块 (IDRO-T/C/P)，规格和漂移性能参考其 CTD 对应部件。
    *   **其他:** Ocean Seven 314 (在线温盐仪), Ocean Seven 306 (pH/ORP 探头)。

---

**6. JFE Advantech (日本) (原 Alec Electronics)**

*   **厂家简介:** 日本主要的海洋和环境测量仪器制造商，产品线包括 CTD, ADCP, 水质仪等。RINKO 快速响应传感器是其特色。
*   **核心传感器来源:** JFE 自主研发其部分传感器技术，尤其是 RINKO 系列光学传感器（如溶解氧），以及配套的 T/C/P 传感器。
*   **代表性型号及规格:** (信息相对不集中，规格和漂移需仔细核对最新手册)

    *   **CTD (电导率, 温度, 深度/压力)**
        *   **型号:** RINKO Profiler (如 ACTW-CMP, ACLW 系列)
            *   **应用:** 剖面测量，常集成 RINKO DO。
            *   **规格 (典型):** T: ±0.01 °C; C: ±0.02 mS/cm; P: ±0.2% FS (至 2000m)。漂移信息不详。
        *   **型号:** Compact-CTD (如 AAQ176)
            *   **应用:** 小型自容 CTD。
            *   **规格 (典型):** T: ±0.01 °C; C: ±0.02 mS/cm; P: ±0.2% FS (至 200m)。漂移信息不详。
        *   **型号:** AAQ-RINKO (系列水质仪, 如 AAQ1183)
            *   **应用:** 多参数水质监测。规格类似 Compact-CTD 或更高。
        *   **旧型号:** ALEC CTD (如 MDS-CTD)。

    *   **TD (温度, 深度/压力)**
        *   **型号:** Compact-TD (AAQ175) / RINKO Profiler ASTD102 / ASTD687/103
            *   **规格 (典型):** T: ±0.01 °C; P: ±0.2% FS。漂移信息不详。
        *   **型号:** DEFI2-T/DHG / ATD-HG
            *   **规格 (典型):** T: ±0.05 °C; P: ±0.5% FS。漂移信息不详。
        *   **旧型号:** ALEC TD (如 ATD 系列)。

    *   **D (深度/压力)**
        *   **型号:** Compact-D (AAQ174)。规格 P: ±0.2% FS。漂移信息不详。
        *   **型号:** AWH-USB (水位记录仪)。

    *   **T (温度)**
        *   **型号:** Compact-T (AAQ171)。规格 T: ±0.01 °C 或 ±0.05 °C。漂移信息不详。

    *   **C (电导率)** / **TC (温度, 电导率)**
        *   **型号:** Compact-C (可能存在) / A7CT-USB (可能是 TC)。规格需查询。

*   **备注:** 获取 JFE 所有型号的详细规格和漂移数据有一定难度。



**7. Sea & Sun Technology GmbH (德国)**

*   **厂家简介:** 德国海洋技术公司，提供标准 CTD 探头和用于海洋微结构湍流测量的 MSS (Microstructure Sonde) 剖面仪系列。
*   **核心传感器来源:** Sea & Sun 自主研发其 CTD 传感器技术，并特别擅长制造用于湍流测量的快速响应 T/C 传感器。压力传感器可能采用外购高品质元件（如压阻式或石英）。
*   **代表性型号及规格:**

    *   **CTD (标准多参数探头系列)**
        *   **型号:** CTD 48 / 48M / 48Mc
            *   **应用:** 浅水到中深水剖面或系留。
            *   **规格 (以 CTD 48M 为例):**
                *   温度 (T): 量程 -2 至 32°C (可选 -2 至 45°C); 准确度 ±0.005 K; 分辨率 0.001 K; 年漂移 (典型) < 0.005 K/年。
                *   电导率 (C): 量程 0 至 70 mS/cm; 准确度 ±0.01 mS/cm (±0.001 S/m); 分辨率 0.001 mS/cm; 年漂移 (典型) < 0.01 mS/cm/年。
                *   压力 (P/D, 压阻式): 可用量程 100 至 6000 dbar; 准确度 ±0.05% FS (可选 ±0.02%); 分辨率 0.005% FS; 年漂移 (典型) < 0.05% FS/年。
            *   **备注:** 采样率 1 Hz (标准), 可选更高。48Mc 为紧凑型。
        *   **型号:** CTD 60Mc / CTD 75M / CTD 90 / CTD 90M / CTD 115 / CTD 115M
            *   **应用:** 功能更强的多参数探头平台。
            *   **规格:** 核心 CTD 指标与 48M 类似或更高。例如: CTD 90M/115M 可选配高精度压力传感器 (±0.01%FS 石英 或 ±0.02%FS 压阻)。T/C 准确度同 48M 或更高 (e.g., T: ±0.003 K)。漂移性能类似。采样率通常更高。

    *   **CTD (集成于 MSS 微结构剖面仪)**
        *   **型号:** MSS60 / MSS90 / MSS90L / MSS90D / MSS90DM 等
            *   **应用:** 海洋微结构湍流测量。
            *   **规格 (标准 CTD 部分):** T 准确度 ±0.005 K; C 准确度 ±0.01 mS/cm; P 准确度 ±0.1% FS 或更高。
            *   **规格 (快速响应传感器):** T (FP07 热敏电阻) 响应时间 ~7ms; C (微电导池) 响应时间 ~1ms。

    *   **TD / TC / D / T / C:** Sea & Sun 主要提供完整的 CTD 探头或 MSS 系统，独立的记录仪产品线不突出。

---

**8. SAIV AS (挪威)**

*   **厂家简介:** 挪威公司，提供海洋学和环境监测仪器。
*   **核心传感器来源:** SAIV 自主集成或与供应商合作。
*   **代表性型号及规格:**

    *   **CTD / STD / TD:**
        *   **型号:** SD204 CTD/STD/TD Recorder
            *   **应用:** 自容式或实时 CTD/STD/TD 记录仪。
            *   **规格:** (基于官网或产品手册信息，建议核实)
                *   温度 (T): 量程 -2 至 +40 °C; 准确度 ±0.01 °C (可选 ±0.005 °C); 分辨率 0.001 °C; 年漂移: 未明确说明。
                *   电导率 (C): 量程 0 至 70 mS/cm (0-7 S/m); 准确度 ±0.02 mS/cm (±0.002 S/m); 分辨率 0.001 mS/cm; 年漂移: 未明确说明。
                *   压力 (P/D, 压阻式): 可用量程 10 至 6000 m; 准确度 ±0.05% FS (可选 ±0.02%); 分辨率 0.001% FS; 年漂移: 未明确说明。
            *   **备注:** 可选集成 DO, Turbidity 等。
        *   **型号:** SD208 CTD/STD Recorder
            *   **应用:** 功能可能更强或接口不同的版本。
            *   **规格:** 核心 CTD 指标预计与 SD204 类似或更高。
        *   **型号:** SD202 (可能为旧型号或特定应用)。

    *   **T / D:**
        *   **型号:** TD301/TD304 (温度记录仪), TD302/TD303 (深度记录仪)。规格需查询。

---

**9. NKE Instrumentation (法国)**

*   **厂家简介:** 专注于低功耗、自主式海洋观测设备，Argo 浮标技术和无线传输是特长。
*   **核心传感器来源:** NKE 自主研发或合作开发，特别是在满足 Argo 要求的低功耗、高稳定性传感器方面有积累。
*   **代表性型号及规格:**

    *   **CTD:**
        *   **型号:** WiSens CTD
            *   **应用:** 无线自容 CTD (WiFi 下载)，用于系留观测。
            *   **规格:** T: ±0.01°C; C: ±0.02 mS/cm; P: ±0.1%FS (或更高)。漂移未明确说明。
        *   **型号:** Provor CTS5 / CTS5-Payload CTD (Argo CTD)
            *   **应用:** Argo 剖面浮标用高稳定性 CTD。
            *   **规格 (参考 Argo 要求):** T: ±0.002°C (<0.002°C/年漂移); C: ±0.005 mS/cm (<0.01 mS/cm/年漂移); P: ±1 dbar (<0.5 dbar/年漂移)。
        *   **型号:** Deep-Arvor CTD (深海 Argo)
            *   **应用:** 4000m/6000m Argo 浮标。
            *   **规格:** 针对深海优化，P 精度和稳定性要求更高。

    *   **TD:**
        *   **型号:** WiSens TD / SP2T
            *   **应用:** 自容式 TD 记录仪。
            *   **规格:** T: ±0.01°C; P: ±0.1%FS。漂移未明确说明。

    *   **T:**
        *   **型号:** WiSens T / STH
            *   **应用:** 自容式 T 记录仪。
            *   **规格:** WiSens T: ±0.01°C; STH (高精度): ±0.002°C。漂移未明确说明。

    *   **D:**
        *   **型号:** WiSens D
            *   **应用:** 自容式压力/深度记录仪。
            *   **规格:** P: ±0.1%FS。漂移未明确说明。

    *   **TC / C:** 非主打独立产品。

---

**10. Falmouth Scientific, Inc. (FSI) (美国)**

*   **厂家简介:** 老牌海洋仪器制造商，提供 CTD 和声学流速仪等。感应式电导是其技术特点之一。
*   **核心传感器来源:** FSI 自主研发其传感器技术，尤其是感应式电导传感器。
*   **代表性型号及规格:**

    *   **CTD:**
        *   **型号:** FSI CTD (Standard / OEM / ACM-PLUS 集成)
            *   **应用:** 剖面/系留/集成。
            *   **规格:**
                *   温度 (T): 量程 -5 至 32 °C; 准确度 ±0.005 °C; 分辨率 0.0001 °C; 漂移信息未详述。
                *   电导率 (C, 感应式): 量程 0 至 70 mS/cm; 准确度 ±0.005 mS/cm (±0.0005 S/m); 分辨率 0.0001 mS/cm; 漂移信息未详述。
                *   压力 (P/D, 压阻式): 可用量程至 7000 m; 准确度 ±0.05% FS (可选 0.01%); 分辨率 0.001% FS; 漂移信息未详述。
            *   **备注:** 采样率可达 32 Hz。

    *   **TD / TC / D / T / C:** FSI 提供基于其 CTD 技术的这些组合或单独传感器模块。规格参考 CTD 对应部分。

---

**11. Star-Oddi (冰岛)**

*   **厂家简介:** 专注于微型数据记录仪，广泛用于渔业、生物学研究和小型平台。
*   **核心传感器来源:** Star-Oddi 自主集成适用于微型化的传感器元件。
*   **代表性型号及规格:** (精度相对较低，体积小、寿命长是优势，漂移数据通常不提供)

    *   **CTD:** DST CTD (T ±0.032°C (校准后), C ±0.7 mS/cm (典型), D 0.5-1.5%FS)
    *   **TD:** Starmon TD (T ±0.05°C, D 0.4%FS), DST centi-TD / milli-TD (更小，精度更低)
    *   **TC:** DST CT (参考 CTD 的 T/C)
    *   **D:** Starmon D (D 0.4%FS), DST centi-D / milli-D (更小，精度更低)
    *   **T:** Starmon T (T ±0.05°C), DST centi-T / milli-T (更小，精度更低)



**12. Aanderaa Data Instruments (挪威 - Xylem 旗下)**

*   **厂家简介:** 以长期、低功耗、高稳定性海洋观测传感器和系统闻名。采用智能传感器概念，传感器可独立校准。
*   **核心传感器来源:** Aanderaa 自主研发和制造其核心的智能传感器系列，包括温度、感应式电导、压力（压阻式和高精度石英）、溶解氧（光学）等。
*   **代表性型号及规格 (通过组合智能传感器和平台实现):**

    *   **智能传感器 - 核心部件:**
        *   **Temperature Sensor 4060 / 4880:**
            *   规格: 量程 -4 至 +36 °C; 准确度 ±0.01 °C; 分辨率 0.001 °C; 年漂移 (典型) < 0.005 °C/年。
        *   **Conductivity Sensor 4319B:** (感应式)
            *   规格: 量程 0 至 7.5 S/m; 准确度 ±0.0018 S/m (±0.018 mS/cm); 分辨率 0.0002 S/m; 年漂移 (典型) < 0.003 S/m/年 (< 0.03 mS/cm/年)。
        *   **Pressure Sensor 4117:** (高精度石英)
            *   规格: 可用量程至 6000 dbar; 准确度 ±0.01% FS; 分辨率 0.0001% FS; 年漂移 (典型) < 0.01% FS/年。
        *   **Pressure Sensor 5217 / 5218:** (压阻式, 深海)
            *   规格: 可用量程至 11000 dbar; 准确度 ±0.02% - ±0.04% FS; 分辨率 0.0002% FS; 年漂移 (典型) < 0.02% - 0.04% FS/年。

    *   **仪器平台 (用于承载传感器):**
        *   **SeaGuard CTD Recorder / RCM / DCP:** 系留平台，可根据配置的传感器组合实现 CTD, TD, TC, D, T, C 等功能。
        *   **SmartGuard:** 节点式数据记录仪。

    *   **备注:** Aanderaa 产品的核心优势在于长期部署的稳定性和可靠性，其漂移指标经过充分验证。

---

**13. Teledyne Marine (美国 - 综合集团)**

*   **厂家简介:** 旗下品牌众多，提供广泛的海洋技术解决方案。
*   **核心传感器来源:** 各子品牌根据其产品定位，可能采用自研传感器、集团内共享技术，或外购传感器（如从 Paroscientific, Keller 或其他供应商采购压力传感器，或从 Sea-Bird/RBR OEM CTD 模块）。
*   **代表性产品线 (涉及 C/T/D):**

    *   **Teledyne RD Instruments (RDI):**
        *   **产品:** ADCPs (如 Workhorse, Sentinel V, Pinnacle, Tasman 等)。
        *   **集成 T/P/CTD:** 集成 T (精度 ±0.1°C 至 ±0.4°C); 可选 P (压阻式, 精度 ±0.1% FS 到 ±0.5% FS); 可选外置 CTD (精度一般)。漂移通常不突出。
    *   **Teledyne Webb Research:**
        *   **产品:** Slocum Gliders, APEX Profiling Floats。
        *   **集成 CTD/TD:** 通常 OEM 自 Sea-Bird (GPCTD, SBE 41/61) 或 RBR (RBRlegato³)。规格和漂移遵循 OEM 指标。
    *   **Teledyne Ocean Science (原 Oceanscience):**
        *   **产品:** UnderwayCTD (uCTD) 系统。
        *   **规格 (探头内传感器, 可能 OEM):** T: ±0.01°C-±0.02°C; C: ±0.02-±0.05 mS/cm; P: ±0.2%-±0.5%FS。漂移不详。
    *   **Teledyne Odom Hydrographic (原 Odom Hydrographic Systems):**
        *   **产品:** 声速剖面仪 (SVP) (如 Digibar Pro, SVP-C)。
        *   **集成 T/P:** T: ±0.01°C-±0.05°C; P: ±0.1%-±0.2%FS。漂移不详。
    *   **Teledyne TSS:**
        *   **产品:** 水下导航传感器。可能提供高精度压力传感器 (D) 用于深度辅助。
    *   **Teledyne Benthos:**
        *   **产品:** 声学释放器, Modem 等。可能集成基础 T/P 监测。

*   **总结:** Teledyne 提供多样化集成方案，但在独立标准 CTD 记录仪方面不如 Sea-Bird/RBR。

---

**14. TSK (Tsurumi Seiki Co., Ltd.) (日本)**

*   **厂家简介:** 日本老牌海洋和气象观测仪器制造商。
*   **核心传感器来源:** TSK 自主研发或与日本国内供应商合作。
*   **代表性产品线 (涉及 C/T/D, 信息可能不完整):**

    *   **CTD/STD:** 可能存在船载或自容式 CTD/STD 型号 (如早期的 Model 102 CTD)。规格和漂移需查找具体资料。
    *   **BT (Bathythermograph):** 著名的 XBT 生产商 (System MK-21, MK-130)。
        *   **XBT:** T: ~±0.1°C; D: ~±2% 或 ±5m。一次性，无漂移。
        *   **DBT:** 数字可回收式 BT。
    *   **潮位计/温盐仪:** 可能有相关产品。

*   **备注:** TSK 在 XBT 和日本市场有重要地位，其可重复使用 CTD/TD 的详细国际资料相对较少。

---



## **B. 关键传感器元件供应商**

**15. Paroscientific, Inc. (美国)**

*   **厂家简介:** **高精度石英谐振式压力传感器 (Digiquartz®)** 的全球领导者。
*   **产品:** Digiquartz® 压力传感器/变送器 (D)。
*   **规格:** 准确度可达 ±0.005% FS; 分辨率 ppb 级; 年漂移 < 0.01% FS/年。
*   **应用:** 为顶级仪器制造商提供最高精度的压力测量核心。

---

**16. KELLER AG für Druckmesstechnik (瑞士)**

*   **厂家简介:** 领先的**压阻式压力传感器和变送器**制造商。
*   **产品:** OEM 压阻式压力传感器/变送器 (D), 以及完整的压力/水位记录仪。
*   **规格 (OEM 传感器):** 准确度可达 ±0.01% FS; 年漂移 < 0.01% FS/年 (高精度系列)。
*   **应用:** 广泛应用于需要高精度、低功耗压力测量的仪器中。

---

**17. Druck (英国 - Baker Hughes 旗下, 原属 GE)**

*   **厂家简介:** 著名的**压阻式压力传感器、校验仪**制造商。
*   **产品:** 高性能压力传感器 (D)。
*   **规格:** 提供高精度、高稳定性的压力传感器。
*   **应用:** 其高性能传感器**可能**被一些海洋仪器制造商选用。

---

**18. Paine Electronics (美国)**

*   **厂家简介:** 专注于**极端环境 (高温、高压等) 压力和温度传感器**。
*   **产品:** 极端环境压力传感器 (D)。
*   **应用:** **极深海或特定水下工程**可能选用其超高压传感器。

---

**19. Kistler (瑞士)**

*   **厂家简介:** **压电式**传感器技术的领导者。
*   **产品:** 压电式压力传感器。
*   **应用:** 测量动态压力，**不适用**于海洋深度测量。

---

**20. Heraeus Sensor Technology (德国) / IST AG (瑞士)**

*   **厂家简介:** 领先的**铂电阻温度计 (PRT) 元件**制造商。
*   **产品:** 高精度 PRT 元件 (T)。
*   **应用:** 为顶级 CTD 制造商提供高精度温度测量的基础元件。

---

**21. TE Connectivity (Measurement Specialties) (美国/全球)**

*   **厂家简介:** 广泛的传感器解决方案提供商。
*   **产品:** 压阻式压力传感器 (D), PRT 和热敏电阻温度传感器 (T) 元件及模块。
*   **应用:** 重要的传感器供应商，覆盖标准到较高精度需求。

---



## **C. 专业仪器/应用制造商 (侧重特定利基市场或集成应用)**

**22. Lowell Instruments LLC (美国)**

*   **厂家简介:** 提供坚固耐用 (钛合金外壳)、低成本、长续航的 T 和 TD 数据记录仪。继承并发扬了部分早期 RBR (Richard Brancker Research) 的技术。
*   **核心传感器来源:** 采用高品质的 PRT 和压阻式压力传感器元件，并进行标定和封装。
*   **代表性型号及规格:**

    *   **TD:** TR-1060 (T: ±0.002°C, <0.002°C/yr; P: ±0.05%FS, <0.05%FS/yr), TR-1050 (T: ±0.01°C; P: ±0.1%FS)。
    *   **T:** TR-1060T (T: ±0.002°C, <0.002°C/yr), TR-1050T (T: ±0.01°C)。
    *   **D:** 基于 TR-1060/1050 配置 (P: ±0.05%FS / ±0.1%FS)。

---

**23. Precision Measurement Engineering (PME) (美国)**

*   **厂家简介:** 专注于小型、低功耗、高精度的水生环境记录仪，尤以溶解氧 (集成 T) 和 TC 记录仪见长。
*   **核心传感器来源:** PME 自主集成或合作开发适用于小型记录仪的传感器。
*   **代表性型号及规格:**

    *   **TC:** miniCT (T: ±0.01°C; C: ±0.01 mS/cm), MicroCT (更小)。漂移不详。
    *   **TD:** TDR-2050 (T: ±0.002°C, <0.002°C/yr; P: ±0.1%FS)。漂移不详。
    *   **T:** miniDOT Logger (含 T: ±0.005°C 或 ±0.01°C), miniT (±0.01°C), MicroT (±0.1°C)。

---

**24. In-Situ Inc. (美国)**

*   **厂家简介:** 水质和水量监测仪器专家，CTD/TD 通常作为其多参数水质仪的一部分。
*   **核心传感器来源:** In-Situ 自主集成或采用适合环境监测市场的传感器元件。
*   **代表性型号及规格:**

    *   **平台:** Aqua TROLL 500 / 600 (多参数水质仪)
        *   规格 (传感器): T: ±0.1°C; C: ±0.5%读数+1µS/cm; P(非通气): ±0.1%FS。漂移不详。
    *   **平台:** Level TROLL 400 / 500 / 700 (水位/压力记录仪)
        *   规格: T: ±0.1°C 或 ±0.2°C; P: 可达 ±0.05% FS, 漂移 < 0.1% FS/年 (典型)。

---

**25. OTT HydroMet (德国/美国 - 旗下 Hydrolab, OTT 等)**

*   **厂家简介:** 综合性水文气象测量方案提供商。
*   **核心传感器来源:** 各品牌自主集成或采用适合环境监测和水文市场的传感器。
*   **代表性型号及规格:**

    *   **平台:** Hydrolab HL4 / HL7 (多参数水质仪)
        *   规格 (传感器): T: ±0.10°C; C: ±0.5%读数或1µS/cm; D: ±0.03m-±0.3m。漂移不详。
    *   **型号:** OTT CTD (地下水 CTD)
        *   规格: T: ±0.1°C; C: ±0.5%读数; P: ±0.05%FS。漂移不详。
    *   **型号:** OTT PLS / Orpheus Mini (压力/水位记录仪)
        *   规格: P: ±0.05% FS (陶瓷单元); 含 T (±0.1°C)。漂移不详。

---

**26. Nortek (挪威)**

*   **厂家简介:** 全球领先的声学多普勒流速测量仪器 (ADCP, ADV, DVL) 制造商。
*   **核心传感器来源:** 采用标准工业级温度和压力传感器元件，主要目的是为声学测量提供辅助参数。
*   **集成 T/P:**
    *   **温度 (T):** 集成于 ADCP/ADV/DVL (如 Signature, Vector, Aquadopp 系列)。准确度典型 ±0.1°C。
    *   **压力 (P/D):** 可选配集成。压阻式，准确度典型 ±0.1% FS 到 ±0.5% FS。
*   **备注:** 不生产独立 CTD/TD/TC/C 记录仪。漂移不是关键指标。

---

**27. Aquatec Group (英国)**

*   **厂家简介:** 提供水下声学通讯、监测和数据记录解决方案。
*   **核心传感器来源:** 集成第三方或自研传感器。
*   **代表性型号及规格 (AQUAlogger 系列):**

    *   **TD:** AQUAlogger 210TY/310PT (T: ±0.05°C 或更高; P: ±0.1%FS 或更高)。
    *   **T:** AQUAlogger 520T/560T (T: ±0.05°C 或更高)。
    *   **D:** AQUAlogger 210P/310P (P: ±0.1%FS 或更高)。
    *   **C:** AQUAlogger 210C (可能存在，需确认)。
    *   **CTD:** AQUAlogger 210 (可能可配置，需确认)。
*   **备注:** 漂移信息不详。

---

**28. Turner Designs (美国)**

*   **厂家简介:** 荧光计和浊度计的领导者。
*   **核心传感器来源:** 集成工业级温度传感器。
*   **集成 T:** 在其荧光计/浊度计 (如 Cyclops-7F, PhytoFlash) 中集成温度传感器 (T)。准确度典型 ±0.05°C 到 ±0.1°C，主要用于补偿或记录。
*   **备注:** 不生产独立 CTD/TD/TC/D/C。

---

**29. Sequoia Scientific, Inc. (美国)**

*   **厂家简介:** 主要生产 LISST 系列水下激光粒度仪。
*   **核心传感器来源:** 集成标准 T/P 传感器。
*   **集成 T/D:** 在其 LISST 仪器 (如 LISST-200X, LISST-Deep) 中通常包含 T 和 P 传感器。准确度满足辅助需求 (如 T: ±0.1°C, P: ±0.2%FS)。
*   **备注:** 不生产独立 CTD/TD/TC/C。

---

**30. Rockland Scientific International Inc. (加拿大)**

*   **厂家简介:** 海洋微结构湍流测量仪器专家。
*   **核心传感器来源:** 采用特殊的快速响应热敏电阻 (FP07) 和微电导池，可能自主研发或与专门供应商合作。压力传感器可能外购。
*   **代表性型号及规格:**

    *   **CTD (高频响):** MicroCTD。
    *   **快速 T:** FP07 (响应时间 ~7ms)。
    *   **快速 C:** 微电导池 (响应时间 ~1ms)。
    *   **标准 T/C/P:** 也集成用于背景场测量，精度类似标准 CTD。
*   **备注:** 核心是快速响应，绝对精度和长期漂移不是首要关注点（相对于背景场传感器）。

---



## **D. 国家/区域性研究与计量机构 (部分列举)**

*   **美国:** WHOI (伍兹霍尔海洋研究所), SIO (斯克里普斯海洋研究所) - 具备高水平校准设施，支持科研。NIST (国家标准与技术研究院) - 国家计量基准。
*   **英国:** NOC (国家海洋学中心) - 领先的校准设施。NPL (国家物理实验室) - 国家计量基准。OSIL (海洋系统仪器有限公司) - 提供仪器租赁、集成和校准服务（可能部分外包或使用自有设施）。
*   **加拿大:** NRC (国家研究委员会) - 国家计量基准。部分大学如 Dalhousie。
*   **德国:** GEOMAR, AWI - 主要海洋研究中心，有校准能力。PTB - 国家计量基准。
*   **法国:** IFREMER - 国家海洋开发研究院，有校准能力。LNE - 国家计量基准。
*   **意大利:** INRiM - 国家计量基准。部分研究机构。
*   **日本:** JAMSTEC - 主要海洋研究机构，有校准能力。NMIJ - 国家计量基准。
*   **澳大利亚:** CSIRO Oceans and Atmosphere - 主要海洋研究机构，有校准能力。NMIA - 国家计量基准。
*   **中国:** **NCOSM (国家海洋标准计量中心)** - **国家级海洋计量和标准权威机构，具有社会公用计量标准，提供法定检定/校准服务——是国家海洋计量站（位于天津）**。当然还有北海、东海、南海分站。NOTC (国家海洋技术中心) - 技术研发、测试评估、观测网支撑。中科院各相关所 (南海所、深海所、声学所、海洋所等) - 科研与特定设备研发。

---



## **E. 中国国内制造商和相关机构 (基于已有公开信息整理)**

* **主要仪器制造商 (提供 CTD/TD/TC/D/T 产品线):**

  **E1. 青岛道万科技有限公司 (青岛)**

  -   **产品线:** DW16(CTD), DW15(TC), DW14(TD), DW12(T), DW11(D)。
  -   **规格 (以官网或宣传资料为参考，可能不完整或需更新):**
      -   **DW16 系列 CTD (例 DW1633F):**
          -   T: 量程 -5~40°C, 准确度 ±0.01°C / ±0.005°C (可选), 分辨率 0.001°C.
          -   C: 量程 0~7S/m, 准确度 ±0.01 mS/cm / ±0.005 mS/cm (可选), 分辨率 0.001 mS/cm.
          -   P: 量程可选至 6000m, 准确度 ±0.1%FS / ±0.05%FS (可选), 分辨率 0.01%FS.
          -   漂移: 未提供详细信息。
      -   **DW14 系列 TD:** 规格参考 CTD 中的 T/P。
      -   **DW12 系列 T:** 规格参考 CTD 中的 T。
      -   **DW11 系列 D:** 规格参考 CTD 中的 P。
      -   **DW15 系列 TC:** 规格参考 CTD 中的 T/C。

  **E2. 杭州海询科技有限公司 / 杭州谱海科技有限公司 (杭州)**

  -   **产品线:** OceanPlot CTD-IM, OceanPlot TD-IM, OceanPlot CTD-DR, OceanPlot ODR 等。
  -   **规格 (以官网或宣传资料为参考):**
      -   **OceanPlot CTD 系列 (例 CTD-DR 自容式):**
          -   T: 量程 -5~40°C, 准确度 ±0.01°C / ±0.005°C, 分辨率 0.001°C.
          -   C: 量程 0~7S/m, 准确度 ±0.02 mS/cm / ±0.01 mS/cm, 分辨率 0.001 mS/cm.
          -   P: 量程可选至 6000m, 准确度 ±0.1%FS / ±0.05%FS, 分辨率 0.01%FS.
          -   漂移: 未提供详细信息。
      -   **OceanPlot TD / T / D:** 规格参考 CTD 对应部分。

  **E3:杭州智海科技有限公司:** ZHC 系列 (CTD, FCTD, MCTD, TD, T, D)。规格类似国内同行，漂移不详。【待确认】

  **E4:天津德华海洋仪器有限公司:** TDH-CTD 系列。规格类似国内同行，漂移不详。【待确认？】

  **E5:国内其他制造商：**待补充。

  

* **专业仪器或传感器制造商:**

  *   **无锡市海鹰加科海洋技术有限责任公司:** 主要生产声速仪 (SVP)，涉及压力 (D) 和温度 (T) 传感器。
  *   北京海卓同创：也生产绝对法声速仪。

* **系统集成、代理或新兴公司:**

  *   **杭州浅海科技有限责任公司:** 产品线待确认和补充。
  *   **北京麦润海通科技有限公司:** 可能涉及代理、集成或自主产品，需确认。
  *   湖南国天电子科技有限公司：待补充。
  *   海洲赛维：DT100prp
  *   其他：待补充。

* **研发与技术支持机构:**

  *   **国家海洋技术中心 (NOTC):** 研发、测试、技术支撑。生产项目性仪器 (OST, SZC 系列)。
  *   **山东科学院海洋仪器仪表研究所:** 地方科研机构。
  *   **中科院南海海洋研究所 / 深海科学与工程研究所:** 特定领域（南海/深海）研发？
  *   **广州海洋地质调查局:** 可能研发或使用特定型号 (FY-1, ZY-1？)。
  *   **大学及其他研究所:** (华北电力大学、山东大学、中科院半导体所、吉林大学、中北大学、中船重工710所、沈阳自动化所等) - 基础研究、原型开发。

---



## ==**声明**：==

- 1.本文所列具体的型号规格和参数指标仅供参考，需读者向制造商索取，以制造商提供的官方文件为准。

- 2.本文可能存在记录错误，请读者后台反馈后我们将在下一个版本中修正。
- 3.以上为个人整理，方便大家工作，不代表任何机构的观点。



## Ref

- NOAA:Depth calculation for the CTD data files
- Multiparameter probe CTD 48M
- Sea Water Density According to UNESCO Formula
- ctd-methods
- UNESCO Pressure to Depth
- google: CTD formula UNESCO
- Seabird Third Party Equipment
- RBR官网。
- https://www.seabird.com/model-number-list

## Log

- 210507 Xiaoyan Created.

- 210510 update.

- 210926 update.

- 220304 update.

- 2025-03-19 transfer to `E:yxyKM\Pts`

- 2025-03-20 xiaoyan added more types of ctds , and  more.形成v0.1版本，转入公众号。

- 2025-03-30 xiaoyan add more info to the article to be the version 0.2.

- 2025-03-21 增加海洲赛维,发布到github的awesome-CTDs.

- 2025-04-01 v0.1版和v0.2版不太一样，现增加进来，待合并，另外分支从master变成了 main

  ```
  The default branch has been renamed!
  master is now named main
  If you have a local clone, you can update it by running the following commands.
  
  git branch -m master main
  git fetch origin
  git branch -u origin/main main
  git remote set-head origin -a
  ```

  

---

# Awesome_CTDs

## 1.概述

The are many CTDs used in the world to test the basic parameters of the sea. Here are the list of the Oceanographic, Hydrographic and Hydrometric Instruments.

制造商集中为：SBE、RBR、JFE(ALEC)、YSI、SeaSun(SST)、Valeport（安德拉）、Saivas、KELLER；技术中心、广地调局、沈阳自动化所、中船重工710所、山仪所。

## 2. CTD 制造商和印象

- [Sea Bird](https://www.seabird.com/)(USA)：简称“海鸟”、”美国海鸟“、”SBE“

- [RBR](https://rbr-global.com/)(Canada)：简称“RBR”、“加拿大RBR”

- [AML](www.AMLoceanographic.com)(Canada)

- [JFE-Alec](https://www.jfe-advantech.co.jp/eng/ocean/)(Japan)

- [Idronaut](https://www.idronaut.it/)(Italy)

- [Sea-Sun](https://www.sea-sun-tech.com/)(Germany)

- [Valeport](https://www.valeport.co.uk/products/)(UK)：

- [Aanderaa](https://www.aanderaa.com/about)( Norway)

> Aanderaa Data Instruments，AADI；a branch of Xylem. 

- KELLER(Switzerland)

- Odom(US)

- Xylem(US)

- YSI(USA)

- [TSK](https://tsurumi-seiki.co.jp/en/servicetag/e-expendable/)(Japan)

- NKE(France)

- SAIVas(Norway)

- Teledyne-Ocean Science (US)：主要生产UCTD，Ocean Science被Teledyne收购。

- Paroscientific(US):简称”Paros“、“派若斯”；世界顶级的压力传感器生产商，其石英谐振式压力传感器的准确度极高。

  > 以下是中国国内制造商

- 国家海洋技术中心[NOTC](http://www.notcsoa.org.cn/cn/index/show/3043)(China)：研究CTD、生产CTD的顶级机构。

- 杭州浅海科技有限责任公司：

- 杭州海询/谱海：

- 无锡市海鹰加科海洋技术有限责任公司：主要生产声速仪，绝对法。也有压力传感器。

- 青岛道万科技有限公司

- 北京麦润海通科技有限公司

- 湖南国天

- 山东科学院仪器仪表研究所

- 中国科学院南海海洋研究所

- 中国科学院深海科学与工程研究所

- 广州海洋地质调查局

- 华北电力大学（保定）

- 山东大学

- 中科院半导体所

- 吉林大学

- 中北大学

  

## 3.主要厂家的CTD主要型号

### 3.1 SBE海鸟主要型号

- [剖面类](https://www.seabird.com/profiling/family?productCategoryId=54627473767): [SBE 911plus CTD](https://www.seabird.com/profiling/sbe-911plus-ctd/family?productCategoryId=54627473769),[SBE 19plus V2 Profiler CTD](https://www.seabird.com/profiling/sbe-19plus-v2-seacat-profiler-ctd/family?productCategoryId=54627473770),[SBE 25plus CTD](https://www.seabird.com/profiling/sbe-25plus-sealogger-ctd/family?productCategoryId=54627473768),[SBE 41/41CP Argo CTD](https://www.seabird.com/profiling/argo-ctd-sbe-41-41cp/family?productCategoryId=54627870408&brParentId=54627473767),[SBE 49 FastCAT CTD](https://www.seabird.com/profiling/sbe-49-fastcat-ctd-sensor/family?productCategoryId=54627473793&brParentId=54627473767),[SBE 61 Argo CTD](https://www.seabird.com/profiling/sbe-61-deep-argo-ctd/family?productCategoryId=54627870409&brParentId=54627473767)

- [锚系类](https://www.seabird.com/moored/family?productCategoryId=54627473771)：[SBE 16plus V2 SeaCAT](https://www.seabird.com/moored/sbe-16plus-v2-seacat-ct-d/family?productCategoryId=54627473773)，[SBE 16plus-IM V2 CT(D)](https://www.seabird.com/moored/sbe-16plus-im-v2-seacat-ct-d/family?productCategoryId=54627473784)，[SBE 37-IM, IMP, IMP-ODO](https://www.seabird.com/moored/sbe-37-microcat/family?productCategoryId=54627473772)，[SBE 37-SI and SIP](https://www.seabird.com/moored/sbe-37-si-and-sip-microcat/family?productCategoryId=54627473785)，[SBE 37 MicroCAT](https://www.seabird.com/moored/sbe-37-microcat/family?productCategoryId=54627473786)，[SBE 39plus Temperature (Depth)](https://www.seabird.com/moored/sbe-39plus-temperature-depth-recorder/family?productCategoryId=54627473774)，[SBE 39plus-IM Temperature (Depth)](https://www.seabird.com/moored/sbe-39plus-im-temperature-depth-recorder/family?productCategoryId=54627473775)，[HydroCAT CTD, DO](https://www.seabird.com/moored/hydrocat-conductivity-temperature-depth-and-optical-dissolved-oxygen/family?productCategoryId=54627473776)，[HydroCAT-EP V2 CTD](https://www.seabird.com/moored/hydrocat-ep-v2/family?productCategoryId=62331495701)

- [可用于移动平台类](https://www.seabird.com/moving-platform/family?productCategoryId=54627473787)：[SBE 41/41CP Argo CTD](https://www.seabird.com/moving-platform/argo-ctd-sbe-41-41cp/family?productCategoryId=54627870408&brParentId=54627473787)，[SBE 49 FastCAT CTD](https://www.seabird.com/moving-platform/sbe-49-fastcat-ctd-sensor/family?productCategoryId=54627473793&brParentId=54627473787)，[SBE 50 Digital Ocean Pressure](https://www.seabird.com/moving-platform/sbe-50-digital-oceanographic-pressure-sensor/family?productCategoryId=54627473794)，[SBE 52-MP Moored Profiler](https://www.seabird.com/moving-platform/sbe-52-mp-moored-profiler-ctd-optional-do-sensor/family?productCategoryId=54627473795&brParentId=54627473787)，[SBE 61 Argo CTD](https://www.seabird.com/moving-platform/sbe-61-deep-argo-ctd/family?productCategoryId=54627870409&brParentId=54627473787)，[Glider Payload CTD](https://www.seabird.com/moving-platform/glider-payload-ctd-gpctd/family?productCategoryId=54627473789&brParentId=54627473787)

- 新型号：待补充。

- 另一种分类：[911-917plus](https://www.laureltechnologies.com/zh-hant/products/sbe-911-plus%e7%9b%b4%e8%af%bb%e5%bc%8f%e6%b8%a9%e7%9b%90%e6%b7%b1%e5%89%96%e9%9d%a2%e4%bb%aa-2/)；[25plus](https://www.laureltechnologies.com/zh-hant/products/sbe-25plus-sealogger-ctd-%e6%b8%a9%e7%9b%90%e6%b7%b1%e5%89%96%e9%9d%a2%e4%bb%aa/)/SBE25；[SBE19plus V2](https://www.laureltechnologies.com/zh-hant/products/sbe-19plus-v2-seacat%e6%b8%a9%e7%9b%90%e6%b7%b1%e5%89%96%e9%9d%a2%e4%bb%aa/)；[SBE16plus V2压阻]([https://www.laureltechnologies.com/zh-hant/products/sbe-16plus-v2-seacat%e6%b8%a9%e7%9b%90%ef%bc%88%e6%b7%b1%ef%bc%89%e8%ae%b0%e5%bd%95%e4%bb%aa/](https://www.laureltechnologies.com/zh-hant/products/sbe-16plus-v2-seacat温盐（深）记录仪/))/[16plus V2谐振]([https://www.laureltechnologies.com/zh-hant/products/sbe-16plus-v2-seacat%e6%b8%a9%e7%9b%90%ef%bc%88%e6%b7%b1%ef%bc%89%e8%ae%b0%e5%bd%95%e4%bb%aa/](https://www.laureltechnologies.com/zh-hant/products/sbe-16plus-v2-seacat温盐（深）记录仪/))；HydroCAT-EP；WQM；[SBE37]((https://www.laureltechnologies.com/zh-hant/products/sbe37-microcat系列超小型温盐（深）记录仪/))系列；  [SBE39plus](https://www.laureltechnologies.com/zh-hant/products/sbe-39-plus%e6%b8%a9%e7%9b%90%e6%b7%b1%e4%bc%a0%e6%84%9f%e5%99%a8/)；  [GPCTD](https://www.seabird.com/quick.search-download.search.jsa?keywords=GPCTD)；SBE 41/41CP(Argo)；SBE61(Deep Argo)；[SBE49]([https://www.laureltechnologies.com/zh-hant/products/sbe49-fastcat%e5%bf%ab%e9%80%9f%e6%b8%a9%e7%9b%90%e6%b7%b1%e4%bc%a0%e6%84%9f%e5%99%a8/](https://www.laureltechnologies.com/zh-hant/products/sbe49-fastcat快速温盐深传感器/))；52MP

  > SBE的产品主要集中在19种：SBE37/SI、SBE56、SBE41、SBE19（Plus）、SBE39、SBE911、SBE917、SBE25（Plus）、WQM、SBE37IM、TD0820、SBE49、GPCTD、SBE21、OS304、SBE37TC、SBE20Plus、SBE16、SBE50。
  >
  > SBE19类对于SBE 的19中型号的仪器来说，又可以分为以下几大类：SBE37类对SBE37来说，又可以分为：SBE37SI、37SIP（泵P）SBE37IMSBE37SM、37SMP（泵P）SBE37TCSBE56对于SBE56，只有温度，作为温度链，通常为自容。
  >
  > SBE41对于SBE41，是大型仪器。温度盐度压力都有。
  >
  > SBE19(Plus)对于SBE19（Plus）：SBE19是老款的 CTD，海鸟的前几代产品，现在基本被 SBE19Plus 取代。
  >
  > SBE39：对于SBE39，主要是 T，作为温度链，通常为自容。也有部分做有压力，例如 6244 、6245、6247（2km）
  >
  > SBE9类对于SBE9来说：可以分为 SBE911和 SBE917两种变体（其实是一个）。其中9是电路板和中央处理器，11是甲板单元，17电池仓和存储器；911是直读式的，917是自容式的。SBE911SBE917SBE25(Plus)对于SBE25和 SBE25Plus，这俩区别有点大。软件用的不太一样。WQMSBE49对于SBE49，一般为小型，一般放在浮标上。

  海鸟常见型号2：

  > SBE16系列：SBE 16plus、16plus-IM、16plus V2和16plus-IM V2 SeaCAT
  > SBE19系列：SBE 19plus和19plus V2 SeaCAT Profiler【剖面】 
  > SBE25系列：SBE 25 Sealogger CTD
  > SBE25plus系列:SBE 25plus Sealogger CTD【剖面】
  > SBE37系列：SBE 37 MicroCAT(IM,IMP,IMP-IDO,IMP-ODO,SM,SMP,SMP-IDO,SMP-ODO,SI,SIP,SIP-IDO)
  > SBE39系列：SBE 39和39-IM、SBE 39plus 
  > SBE49系列：SBE 49 FastCAT CTD【剖面】
  > SBE5系列：SBE 52-MP和SBE 50
  > SBE9系列：SBE 911/917plus CTD【剖面】
  > SBE41系列：Argo CTD (SBE 41/41CP)
  > SBE61系列：SBE 61 Deep Argo CTD
  > slocum系列：
  > Hydrocat系列：
  > HTI系列：
  > HC-SMP系列：

### 3.2 RBR主要型号

- 标准记录器：可以集成 1 到 10 个通道，包括第三方传感器

  - [RBR*virtuoso³* 和 RBR*duo³* 单通道和双通道记录仪](https://rbr-global.com/products/standard-loggers/rbrvirtuoso-rbrduo/)；[RBR*virtuoso³* T 和 RBR*duo³* T.D 潮汐和波浪记录仪](https://rbr-global.com/products/standard-loggers/standard-tide-wave/)
  - [RBR*brevio³* C.T.D logger](https://rbr-global.com/products/standard-loggers/rbrbrevio/)
  - [RBR*duo³* C.T and RBR*concerto³* C.T.D multi-channel loggers](https://rbr-global.com/products/standard-loggers/rbrduo-ct/)
  - [RBR*duo³* C.T | uv & RBR*concerto³* C.T.D | uv](https://rbr-global.com/products/standard-loggers/rbrduo-ct-uv/)
  - [RBR*maestro³* C.T.D multi-channel logger](https://rbr-global.com/products/standard-loggers/rbrmaestro/)
  - [RBR*quartz³* APT bottom pressure recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-apt/)
  - [RBR*quartz³* BPR bottom pressure recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-bpr/)
  - [RBR*quartz³* BPR|zero bottom pressure recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-bpr-zero/)
  - [RBR*quartz³* Q tide and wave recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-q/)
  - [RBR*quartz³* Q|plus tide and wave recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-q-plus/)
  - [RBR*virtuoso³* T and RBR*duo³* T.D tide and wave loggers](https://rbr-global.com/products/standard-loggers/standard-tide-wave/)
  - [RBR*quartz³* Q tide and wave recorder](https://rbr-global.com/products/standard-loggers/rbrquartz-q/)
  - [RBR*concerto³* Tx thermistor string](https://rbr-global.com/products/standard-loggers/thermistor-strings/)

- 紧凑型：

  - [RBR*solo³* T compact temperature logger](https://rbr-global.com/products/compact-loggers/rbrsolo-t-2/)
  - [RBR*solo³* D compact depth logger](https://rbr-global.com/products/compact-loggers/rbrsolo-d/)
  - [RBR*duet³* T.D compact temperature and depth loggers](https://rbr-global.com/products/compact-loggers/rbrduet-td/)
  - [RBR*solo³* D and RBR*duet³* T.D compact tide and wave loggers](https://rbr-global.com/products/compact-loggers/compact-tide-wave/)
  - [RBR*duet³* T.ODO compact temperature and oxygen logger](https://rbr-global.com/products/compact-loggers/rbrduet-t-odo/)
  - [RBR*solo³* PAR and RBR*solo³* rad compact PAR and narrow-band loggers](https://rbr-global.com/products/compact-loggers/rbrsolo-par-rad/)
  - [RBR*solo³* DO, Tu, and PAR compact single channel loggers](https://rbr-global.com/products/compact-loggers/rbrsolo-do-tu-par/)
  - [RBR*solo³* T|deep and RBR*duet³* T.D|deep compact deepwater loggers](https://rbr-global.com/products/compact-loggers/deepwater-loggers/)

- RBR 市场常见：

  ```
  >RBR 的产品主要集中在9种：
  - RBRduoTD
  - RBR-TGR/TDR/TWR
  - RBRduetT.D
  - RBR-XR-620
  - RBRconcerto
  - RBRsoloT
  - RBRsoloD
  - RBR-TGR-1050
  - RBR-XRX-620
  - RBRvirtuoso
  ```

  

### 3.3 OST主要型号(ONTC)

> 国家海洋技术中心主要是OST系列，另有其他型号待补充。

| 型号 | 备注1 | 备注2 |
| ---- | ----- | ----- |
| 15D  |       |       |
| 15M  |       |       |
| 19   |       |       |
| 27   |       |       |
| 30D  |       |       |
| 30M  |       |       |
| 31D  |       |       |
| 31M  |       |       |
| 32D  |       |       |
| 32M  |       |       |
| 33D  |       |       |
| 33M  |       |       |
| 34D  |       |       |
| 34M  |       |       |
| 35D  |       |       |
| 35M  |       |       |
| 36D  |       |       |
| 36M  |       |       |
| 41   |       |       |
| 42   |       |       |
| 43   |       |       |
| 44U  |       |       |
| 44G  |       |       |
| 71   |       |       |
| 72   |       |       |
| 73   |       |       |
| 35M  |       |       |

> 技术中心的产品前期5种：YZY4-3、SZC(F or P)、LC-PT400、WR-2050、CSS3

- 常见：OST19、OST27、SZC15-5、SXF4-1、SZF4-1等

### 3.4 SeaSun公司的SST系列

- 标准型号

  - [Multiparameter Probe CTD 48](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-48/), detail: [SeaandSun_CTD48-datasheet.pdf](https://www.sea-sun-tech.com/wp-content/uploads/2018/10/SeaandSun_CTD48-datasheet.pdf)


    - [Multiparameter Probe CTD 48M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-48m/)


    - [Multiparameter Probe CTD 48Mc](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd48-mc/)


    - [Multiparameter Probe CTD 60Mc](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-60-memory/)

    - [Multiparameter Probe CTD 75M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-75/)

  

    -  [Multiparameter Probe CTD 90](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-90/)

  

    -  [Multiparameter Probe CTD 90M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-90-memory/)

  

    -  [Multiparameter Probe CTD 115M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-115-memory/)


- 微观结构测量系统：([SST_datasheet_MSS-Family-v1.2_opt.pdf](https://www.sea-sun-tech.com/wp-content/uploads/2019/05/SST_datasheet_MSS-Family-v1.2_opt.pdf))

  - MSS60: Light profiler for coastal waters, lakes and rivers 

  - MSS90: Easy to handle profiler for ocean measurements from small ships

  - MSS90L: Our “work horse” for measurements down to 500 m (optional 1000 m) 

  - MSS90LH: Heavy version of the MSS90L with lower profiler vibration level

  - MSS90D: Profiler for measurements down to 1000 m, cable length up to 1500 m  

  - MSS90DH: Heavy version of the MSS90D with lower profiler vibration level 

  - MSS90DM: Profiler for measurements down to 2000 m with memory, cable length up to 3000 m  

  - MSS90DMH: Heavy version of the MSS90DM with lower profiler vibration level

- SST常见型号：

  > 德国SeaSun公司:48M、90M

- 常见分类链接：[CTD 48](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-48/)，[CTD 48M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-48-memory/)，[CTD 48 Mc](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd48-mc/)，[CTD 60Mc](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-60-memory/)，[CTD 75M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-75/)，[CTD 90](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-90/)，[CTD 90M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-90-memory/)，[CTD 115](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-115/)，[CTD 115M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-115-memory/)

### 3.5 意大利 Idronaut

- [Environmental CTDs](https://www.idronaut.it/multiparameter-ctds/environmental-ctds/)

  - Ocean Seven 310 Multiparameter CTD [Learn more](https://www.idronaut.it/multiparameter-ctds/environmental-ctds/os310-environmental-ctds/)： Low Power Self Recording and Profiling 28Hz Multi-Parameter CTD.

  - Ocean Seven 316S[Learn more](https://www.idronaut.it/multiparameter-ctds/environmental-ctds/os316s/)：28hz Workhorse Multi-parameter CTD Profiler And Self-recording. Most Sold More Than 1000 Units All Over The World.


  - Ocean Seven 308 CTD Logger [Learn more](https://www.idronaut.it/multiparameter-ctds/environmental-ctds/os308-environmental-ctds/)： Very low power, Self-recording, UV-Antifouling, Arctic, Antarctica, Brine, Moorings, ROVs, AUVs

  - Ocean Seven 28 Micro CTD [Learn more](https://www.idronaut.it/multiparameter-ctds/environmental-ctds/os28/)： VERY SMALL DIAMETER AND ACCURATE CTD UP TO 28Hz

- [Oceanographic CTDs](https://www.idronaut.it/multiparameter-ctds/oceanographic-ctds/)

  - Ocean Seven 320Plus [Learn more](https://www.idronaut.it/multiparameter-ctds/oceanographic-ctds/os320plus-oceanographic-ctd/)：WOCE 40HZ, FULL-OCEAN MULTI-PARAMETER CTD FOR OCEANOGRAPHY
  - Ocean Seven 316S [Learn more](https://www.idronaut.it/multiparameter-ctds/oceanographic-ctds/os316s/)：28hz Workhorse Multi-parameter CTD Profiler And Self-recording. Most Sold More Than 1000 Units All Over The World.
  - Ocean Seven 308 CTD Logger [Learn more](https://www.idronaut.it/multiparameter-ctds/oceanographic-ctds/os308-oceanographic-ctd/)：Very low power, Self-recording, UV-Antifouling, Arctic, Antarctica, Brine, Moorings, ROVs, AUVs
  - Ocean Seven 306 pH and Redox Probe [Learn more](https://www.idronaut.it/multiparameter-ctds/oceanographic-ctds/os306-oceanographic-ctd/)：Full Ocean Analogue Ph And Redox Probe.

- [On-Line Modules](https://www.idronaut.it/multiparameter-ctds/on-line-modules/)

  - Ocean Seven 314 On-Line Module  [Learn more ](https://www.idronaut.it/multiparameter-ctds/on-line-modules/os314-on-line-module/)：On-Board Multi-Parameter On-line Module, Thermo-Salinograph, Ferrybox.

- [Borehole CTDs](https://www.idronaut.it/multiparameter-ctds/borehole-ctds/)

- [Advanced Tools](https://www.idronaut.it/multiparameter-ctds/advanced-tools/)

- 常见型号:OCEAN SEVEN 304等系列。

### 3.6 青岛道万

- [DW16系列温盐深仪](http://www.daowantech.cn/index.php/product/167)
- [DW15系列温盐仪](http://www.daowantech.cn/index.php/product/168)
- [DW14系列温深仪](http://www.daowantech.cn/index.php/product/169)
- [DW12系列温度仪](http://www.daowantech.cn/index.php/product/170)
- [DW11系列深度仪](http://www.daowantech.cn/index.php/product/171)
- [DW10系列配件](http://www.daowantech.cn/index.php/product/172)
- [水质多参数传感器](http://www.daowantech.cn/index.php/product/177)

- 常见：DW1633F、DW1616-D

### 3.7 杭州海询

- OceanPlot CTD-IM

- OceanPlot TD-IM
- OceanPlot CTD-DR
- OceanPlot ODR

### 3.8 AML

- 常见型号：AML MINO-X、MVP300、MVPX

- [AML-6 RT CTD+SV 等](https://amloceanographic.com/catalogsearch/result/index/?cat=93%29&p=2&q=Pressure) 

  

### 3.9 日本JFE(ALEC)

> 亚力克的主要产品集中为8大类：

- A7CT-USB

- ALEC/ATD-HG

- ASTD687/102/103

- ACTW-CAR

- AWH-USB

- AROW2(3)-USB(CAR)

- AAQ1183

- AAQ171

- 常见：ATD-HG、ACLW2-USB

### 3.10 Teledyne-Ocean Science 

- [UCTD](http://www.teledynemarine.com/Documents/Brand Support/OCEANSCIENCE/Technical Resources/Manuals and Guides/Underway Profiling System (UCTD)/UCTD Guide_Jul18.pdf)

### 3.21 广州地调局

>广州地调局产品主要集中在2种：

- FY-1

- ZY-1





## 4.主要型号CTD操作注意事项（Private）

- 

## 5.ONQI

> Ocean National Quality Infrastructure:

### 6.1 [WHOI](https://www.whoi.edu/science/PO/ctd/ctdcal1.html)(USA)

### 6.2 [NCOSM](https://www.ncosm.org.cn)(China)

### 6.3 [CSIRO](https://www.csiro.au/)(Australia)

### 6.4 [JAMSTEC ](https://www.jamstec.go.jp/j/)(Japan)

### 6.5 [OSIL](https://osil.com/product/calibration/)(UK)



## Ref

- [NOAA:Depth calculation for the CTD data files](https://www.nodc.noaa.gov/archive/arc0022/0001155/1.1/data/0-data/docs/common/depthCTD-calculated.htm)
- [Multiparameter probe CTD 48M](https://www.sea-sun-tech.com/product/multiparameter-probe-ctd-48-memory/#detail)
- [Sea Water Density According to UNESCO Formula](https://link.springer.com/content/pdf/bbm%3A978-3-319-18908-6%2F1.pdf)
- [ctd-methods](https://calcofi.org/about-calcofi/methods/119-ctd-methods.html)
- [UNESCO Pressure to Depth](https://www.navlab.net/Publications/From_Pressure_to_Depth_-_Estimation_of_underwater_vertical_position.pdf)
- [google: CTD formula UNESCO](https://www.google.com/search?q=UNESCO+formulae+CTD&newwindow=1&safe=strict&sxsrf=ALeKk011VhZo7GQW26tHxEuH5vPLO-8Xtg%3A1620618634954&ei=iq2YYJ70ONbT-wSRyKWoCg&oq=UNESCO+formulae+CTD&gs_lcp=Cgdnd3Mtd2l6EANQ3owUWN6MFGCpnBRoAHAAeACAAY8CiAHwA5IBAzItMpgBAKABAqABAaoBB2d3cy13aXrAAQE&sclient=gws-wiz&ved=0ahUKEwie4bTwmr7wAhXW6Z4KHRFkCaUQ4dUDCA8&uact=5)
- [Seabird Third Party Equipment](https://www.seabird.com/products/third-party-equipment)
- [RBR](https://rbr-global.com/)
- https://www.seabird.com/model-number-list

## Log

- 210507 Xiaoyan Created.
- 210510 update.
- 210926 update.
- 220304 update.
- 2025-03-19 transfer to `E:\iyuxiaoyan\yxyKM\Pts`
- 2025-03-20 xiaoyan added more types of ctds , and  more.
- 250401 merge with v0.2

