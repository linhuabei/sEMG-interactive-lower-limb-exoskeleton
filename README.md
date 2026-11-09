# sEMG-interactive-lower-limb-exoskeleton

下肢外骨骼项目。当前仓库包含机械设计（SolidWorks）与硬件设计（原理图、FOC 工程）文件。

> 仓库中暂无软件、固件源码， sEMG 算法相关文件与独立仓库。

## 仓库结构

```
sEMG-interactive-lower-limb-exoskeleton/
├── Mechanical Design/                  # SolidWorks 文件
│   ├── 双腿装配版.SLDASM               # 双腿总装配体
│   ├── 固定器.SLDPRT
│   ├── 大腿动力段甲.SLDPRT
│   ├── 大腿动力段乙.SLDPRT
│   ├── 大腿输出端垫片.SLDPRT
│   ├── 胯C型乙件.SLDPRT
│   └── ...                             # 其他零件
├── hardware/
│   ├── FOC_STM32F103C8T6.epro2         # FOC 工程文件
│   ├── IMU_Schematic.pdf               # IMU 原理图
│   └── SCH_Schematic1_2026-11-08.pdf   # 原理图
└── README.md
```

## 机械设计

`Mechanical Design/` 下为 SolidWorks 文件：

- `双腿装配版.SLDASM`：双腿总装配体
- 其余为 `.SLDPRT` 零件文件（固定器、大腿动力段甲/乙、输出端垫片、胯C型乙件等）

用 SolidWorks 打开 `双腿装配版.SLDASM` 查看整体装配。

## 硬件设计

`hardware/` 下为硬件设计文件：

- `IMU_Schematic.pdf`：IMU 原理图，PDF 阅读器直接打开
- `SCH_Schematic1_2026-11-08.pdf`：原理图，PDF 阅读器直接打开
- `FOC_STM32F103C8T6.epro2`：FOC 工程文件，需用对应的 EDA 工具打开

