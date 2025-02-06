# STM32G413 HAL 工程模板

这是一个基于 STM32G413 微控制器的 HAL 库工程模板,使用 MDK-ARM IDE 开发。

## 项目特点

- 基于 STM32Cube FW_G4 V1.6.1 固件库
- 使用 HAL 库进行外设配置和控制
- 支持 HSE 外部晶振时钟源
- 默认堆栈配置:
  - 堆大小: 0x200
  - 栈大小: 0x400
- 工程默认使用 MDK-ARM V5.32 工具链

## 目录结构

- `Core/` - 核心代码目录
  - `Inc/` - 头文件
  - `Src/` - 源代码文件
- `Drivers/` - STM32 HAL 驱动库
- `MDK-ARM/` - Keil MDK 工程文件

## 开发环境要求

- MDK-ARM V5.32 或更高版本
- STM32CubeMX 
- STM32G4xx HAL 驱动库

## 使用说明

1. 使用 MDK-ARM 打开 `MDK-ARM/STM32_G413_Template_HAL.uvprojx` 工程文件
2. 编译工程
3. 下载程序到目标板

## 配置修改

如需修改工程配置:
1. 使用 STM32CubeMX 打开 `STM32_G413_Template_HAL.ioc` 文件
2. 修改相关配置
3. 重新生成代码

## 许可证

本项目采用 MIT 许可证