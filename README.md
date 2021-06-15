# X-TRACK
> 开源GPS自行车码表。
> 
> 拥有可显示实时位置的离线地图。
> 
> 支持记录轨迹以及导出标准GPX格式的轨迹文件。
> 
> 全新设计的[页面调度](https://github.com/FASTSHIFT/X-TRACK/tree/main/Software/X-Track/USER/App/Utils/PageManager)和[消息框架](https://github.com/FASTSHIFT/X-TRACK/tree/main/Software/X-Track/USER/App/Utils/DataCenter)。

![image](https://github.com/FASTSHIFT/X-TRACK/blob/main/Images/%E9%AA%91%E8%A1%8C%E6%B5%8B%E8%AF%95.jpg)

## GUI
> [LVGL V8.0.0](https://github.com/lvgl/lvgl/releases/tag/v8.0.0)

## 硬件配置
* 1.主控: AT32F403ACGU7 (主频:240MHz RAM:224KB ROM:1MB)
* 2.屏幕: ST7789 IPS 1.54inch SPI接口 240x240分辨率 60Hz刷新率
* 3.储存器: Micro SD CARD 32GB 
* 4.输入设备: 旋转编码器
* 5.RTC: MCU内置RTC时钟
* 6.加速度计: LSM6DSM (支持硬件计步输出)
* 7.地磁计: LIS3MDL
* 8.GPS: ATGM336H (BDS + GPS + GLONASS + GALILEO + QZSS + SBAS)
* 9.电池: Li-ion 3.7V 683030 700mAh
* 10.电源管理: LP5904-3.3 + MCP73831
* 11.外壳: 3D打印 光固化

## 功能
* 1.支持速度、距离、时间、卡路里、航向显示
* 2.拥有**离线地图**，支持显示实时位置，支持缩放
* 3.支持计步
* 4.支持经纬度、海拔显示
* 5.支持RTC自动根据GPS校准
* 6.支持记录轨迹，可导出[GPX](https://zh.wikipedia.org/wiki/GPX)格式的文件
* 7.支持掉电自动保存数据(JSON格式文件)
* 8.四小时续航 (持续工作，始终亮屏)
* 9.支持在[PC模拟器](https://github.com/FASTSHIFT/X-TRACK/tree/main/Software/X-Track/Simulator)模拟，脱离硬件调试
* 10.待续...

## 实物演示
https://user-images.githubusercontent.com/26767803/120889722-1f8d8e80-c631-11eb-8294-df79f151dedb.mp4

## 致谢
> 感谢[@davidce](https://www.geek-workshop.com/home.php?mod=space&uid=204)贡献的参考设计“[自制基于arduino的GPS地图导航系统3.0](https://www.geek-workshop.com/thread-8835-1-1.html)”以及地图选择工具。

> 感谢[@W-Mai](https://github.com/W-Mai)改进的地图下载链接生成工具、地图下载器、[LVGL图片转换器(Python版)](https://github.com/W-Mai/lvgl_image_converter)、批量文件重命名工具。

> 感谢[@Trigger-CN](https://github.com/Trigger-CN)的UI设计。

> 感谢[@MouriNaruto](https://github.com/MouriNaruto)的LVGL Visual Studio模拟器[lv_sim_visual_studio](https://github.com/lvgl/lv_sim_visual_studio)。

> 感谢[@dj140](https://github.com/dj140)编写地图下载教程。