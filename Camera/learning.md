1. 手机影像极度依赖硬件 ISP 和专有计算单元（如 NPU/DSP），但专业影像设备（如电影机、专业相机、流媒体设备）由于量产规模、RAW 格式处理、高码率等原因，往往会更重度地依赖 GPU（通过 Vulkan / OpenCL / CUDA）来进行图像后处理、3D LUT 映射、色彩科学管理甚至实时 AI 降噪。

2. 异构计算与软硬件协同设计（Heterogeneous Computing）
专业设备往往是定制化方案。理解 CPU、GPU、NPU、DSP 以及专用图像加速器（Hardware Encoders/Decoders）之间如何协同工作，如何设计一套最高效的 Pipeline（流水线），这是顶级影像架构师的底层逻辑。

2. 色彩科学与视频流媒体标准（Color Science）
手机影像过去更讨好眼球（计算摄影），而专业影像更讲究还原度和后期空间。

* 深入研究 Log 曲线、RAW 数据处理、BT.2020 / BT.709 色域转换、HDR（HDR10+, Dolby Vision） 的全链路管理。

* 掌握专业视频容器（MP4、MOV）的封装、时间戳（Timestamp）对齐、元数据（Metadata）写入。
