### Icrest3支持哪些大疆无人机和配套的云台相机？

具体查看DJI 开发者网站

https://developer.dji.com/doc/payload-sdk-tutorial/cn/function-set/basic-function/basic-camera-management.html

| 机型                             | 云台相机相机            | 备注                                                 |
| :------------------------------- | :---------------------- | ---------------------------------------------------- |
| Matrice 350 RTK、Matrice 300 RTK | H20、H20T、H20N、P1、L1 | L1仅支持可见光数据获取，不支持激光实时点云数据获取。 |
| M30系列、M3E、M3T                | √                       |                                                      |



### 云冠 3系列与妙算2-G有什么差异？

|          |                          云冠3系列                          | 妙算2-G                                                      | 云冠3优势                                                    |
| -------- | :---------------------------------------------------------: | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 重量     |                           ＜150g                            | 230g                                                         | 更轻量化设计，更适合无人机应用                               |
| 尺寸     |              888x59x27 mm88x59x35.9mm（版本）               | 91x61x35mm                                                   | 更轻量化设计，更适合无人机应用                               |
| 接口     | USB3.1 x 1，USB 2.0 x 3，HDMI x 1，UART x 3，百兆以太网 x 1 | USB 3.0接口（Type A）×2，USB 3.0接口（Micro-B）×1，CAN接口x2，UART接口x2，I2C接口x1，SPI接口x1，UART接口x1 | 云冠3接口为大疆无人机定制，接口更精简，性能更稳定；如需更多通讯接口，也可通过USB口进行扩展 |
| 网络     |                           5G+WIFI                           | WIFI                                                         | 5G通信不受距离限制                                           |
| 处理器   |      NVIDIA Jetson NX;  21 TOPS(INT8)  6 TFLOPS(FP16)       | NVIDIA Jetson TX2;  1.3 TFLOPS(FP16)                         | 是妙算3-G性能的10倍，强大的算力能够支持更复杂的AI模型进行前端识别 |
| 防护能力 |                            IP45                             | 无防护                                                       | 能在雨中等复杂环境中使用                                     |
| 软件支持 |                 支持英伟达原生镜像和软件包                  | 只能用大疆镜像，而且不再更新                                 | 支持最新的英伟达软件包                                       |

### 云冠 3系列影响飞行续航吗？

云冠 3系列最大功率25W，对于飞行续航影响几乎可以忽略。

### Icrest3-5G支持哪些5G频段？

Icrest3-5G使用工业级5GSub-6GHz模块。采用3GPPRelease16技术，同时支持5GNSA和SA模式。支持的频段如下：

- **5G NR**
  - **NSA**：n1/ 2/ 3/ 5/ 7/ 8/ 12/ 13/14/ 18/ 20/ 25/ 26/ 28/29/ 30/ 38/40/ 41/ 48/ 66/ 70/ 71/ 75/ 76/ 77/ 78/79; 
  - **SA**：n1/ 2/ 3/ 5/ 7/ 8/ 12/ 13/14/ 18/ 20/ 25/ 26/ 28/29/ 30/ 38/ 40/ 41/ 48/ 66/ 70/ 71/ 75/ 76/ 77/ 78/79; 

- **LTE**

  - **LTE-FDD**:B1/ 2/ 3/ 4/ 5/ 7/ 8/ 12/ 13/ 14/ 17/ 18/ 19/ 20/ 25/26/ 28/ 29/ 30/ 32/ 66/ 71; 

  - **LTE-TDD**: B34/ 38/ 39/ 40/ 41/ 42/ 43/ 48;

  - **LAA**:B46;

- **UMTS**
  - **WCDMA**:B1/ 2/ 4/ 5/ 8/ 19