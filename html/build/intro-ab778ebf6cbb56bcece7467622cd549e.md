# CEMC数据指南

本指南介绍如何使用 cedarkit 工具栈加载 CEMC 数值天气预报业务系统 GRIB2 数据。

cedarkit 是 CEMC 地球系统数据分析和可视化工具套件 (**C**EMC **E**arth **D**ata **A**nalysis and **R**endering Tool**kit**，cedarkit) 的简称，提供一组 Python 工具集，用于分析地球系统数值预报数据。
该套件基于 Python 科学计算社区的开源工具库开发，并开源发布。

本指南以 CMADaaS 平台上的数值天气预报业务系统数据为例，介绍如何使用 reki 加载模式数据。
示例默认从 CMADaaS 挂载目录拷贝数据到临时目录，也可以根据实际环境修改为本地文件路径。

本数据指南包含如下系统数据：

- CMA-GFS：全球预报系统
- CMA-MESO 1KM：区域 1 公里预报系统
- CMA-TYM：区域台风预报系统
- CMA-GEPS：全球集合预报系统
- CMA-REPS：区域集合预报系统

```{note}
本文所有代码均在可以访问 CMADaaS 平台的环境中运行。

注：发布的文档在 Windows 的 WSL 环境中生成。
```
