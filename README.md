
### 欧加真 Android 15 通用内核构建流程

**核心功能**：
1. **自动化内核构建**：为欧加系（OPPO/一加/Realme）骁龙8Gen3设备构建 Android 15 内核
2. **关键特性集成**：
   - SukiSU-Ultra 增强 root 方案
   - SUSFS 虚拟文件系统（支持隐藏 root）
   - 可选 LZ4K 高效内存压缩
   - SCX 风驰调度器优化
   - BBR/FQ 网络加速
3. **智能配置**：
   - 120Hz 动态刷新率支持
   - 国密加密算法支持
   - SELinux 安全增强
   - IPv6 网络优化
4. **灵活定制**：
   - 内核后缀自定义
   - 模块化功能开关（LZ4K/SCX/网络增强）
5. **自动化发布**：生成 AnyKernel3 刷机包并创建 GitHub Release

**输出成果**：  
- 完整的可刷写内核 ZIP 包
- 包含详细安装指南的 Release 页面
- 支持 ColorOS 15 / RealmeUI 6.0 系统

**编译环境**：Ubuntu 最新版 + LLVM 20 工具链
