# 容量型NAS {#concept_1012851 .concept}

本文档介绍容量型NAS的特点、性能规格、应用场景等信息，您可以根据需求选择合适的NAS类型。

NAS容量型使用SATA HDD作为存储介质，以更低的成本提供高效性能的存储空间。适用于大吞吐，业务弹性扩展，成本敏感型的文件共享存储服务。对于读写访问不太频繁，时延响应要求不高的业务，有较好的成本优势。

## 产品特点 {#section_iyl_1y5_bj7 .section}

-   容量弹性扩展，吞吐随容量线性扩，最大可达10GB/s。
-   单TB吞吐150MB/s，10毫秒级时延。
-   性能优化，适合大容量，高吞吐的业务。

## 性能规格 {#section_rce_ktv_808 .section}

-   容量：10PB
-   时延：10ms毫秒级时延
-   IOPS：最大15K（4k随机IO读写）
-   吞吐：随容量线性扩展，适用于大容量高吞吐并且对时延响应要求不高的计算性业务

## 应用场景 {#section_kyg_ar8_qh3 .section}

适用于大容量扩展以及成本敏感型工作负载，如大数据分析、文件共享、备份等。

## 吞吐计算 {#section_y60_ioh_l2h .section}

容量型文件系统吞吐上限（MB/s）= 0.15MB/s \* 文件系统存储空间（GB）+ 150MB/s（初始带宽）（最大10GB/s）

