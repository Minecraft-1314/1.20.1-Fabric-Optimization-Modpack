# 1.20.1-Fabric 优化整合包

一个面向 **Minecraft 1.20.1 + Fabric 0.20.1** 的性能优化整合包，兼顾画面表现、界面体验与联机稳定性。基于 Modrinth 格式打包，可通过 PCL2 或任何支持 Modrinth 整合包的启动器一键导入。

> 提供 `.zip` 与 `.mrpack` 两个文件，内容完全相同，仅扩展名不同。`.mrpack` 是 Modrinth 格式的标准扩展名，推荐优先使用。

---

## 📌 基本信息

| 项目 | 内容 |
|---|---|
| 游戏版本 | Minecraft 1.20.1（正式版） |
| Mod 加载器 | Fabric Loader 0.20.1 |
| Fabric API | 0.92.12+1.20.1 |
| Mod 总数 | 151 个（含 17 个支持库）
| Java 版本 | **Java 17 +**（已实测两者都能正常启动） |
| 打包时间 | 2026-11-06 |

---

## 快速开始

### 通过 PCL2 导入

1. 打开 PCL2 → **版本** → **导入整合包**
2. 选择 `1.20.1-Fabric-优化整合包 1.0.0.mrpack`（或 `.zip`，两者内容相同）
3. 等待下载与安装完成
4. 启动游戏

---

## Mod 分类清单

### 性能优化（43 个）

| Mod | 说明 |
|---|---|
| Sodium | 渲染优化，显著提升帧率 |
| Starlight | 光照引擎重写 |
| FerriteCore | 降低内存占用 |
| ModernFix | 大量现代修复与优化 |
| BadOptimizations | 移除非必要开销 |
| Cull Less Leaves | 树叶渲染剔除 |
| Entity Culling | 异步路径追踪剔除不可见实体 |
| ImmediatelyFast | 立即模式渲染优化 |
| Smooth Chunk | 区块保存优化 |
| Async Particles | 粒子异步处理 |
| Async Locator | 定位器异步化 |
| Krypton | 网络栈优化 |
| Memory Leak Fix | 修复内存泄漏 |
| GPU Memleak Fix | 修复 GPU 内存泄漏 |
| Crash Exploit Fixer | 修复崩溃漏洞利用 |
| Enhanced Block Entities | 方块实体渲染优化 |
| TT20 | 技术性方块优化 |
| Better FPS Distance | 更智能的渲染距离，进一步提升帧率 |
| Vanillin | 基于 Flywheel 的实体实例化渲染 |
| Jasione | 减少 Enum.values 克隆，降低 GC 压力 |
| Kerria | 纹理动画加速 |
| Sound Culling | 自动抑制拥挤区域的重复音效 |
| Frame Pacer | 帧率节流 |
| Frame to the Trash | 减少多余的显示刷新 |
| Ixeris | 缓冲原始输入与线程化事件轮询 |
| Reflex | NVIDIA Reflex 低延迟渲染 |
| FISM | 加速 Iris 阴影贴图处理 |
| PAPI | 内存泄漏修复与内存优化 |
| Achievement Optimizer | 成就系统优化 |
| Blanket Client Tweaks | 修复若干原版恼人特性 |
| Auto Log Remover | 自动清理旧日志文件 |
| Async Logger | 异步日志 |
| Fix Attack Lag | 修复攻击粒子过多导致的卡顿 |
| MC-249136 Fix | 修复沉船宝藏生成时的服务器卡顿 |
| DEUF Refabricated | 防止实体 UUID 重复导致的日志刷屏与崩溃 |
| Dimension Leak Fix | 修复切换维度时的内存泄漏 |
| 0Pack2Reload | 资源包惰性重载 |
| Stfu | 修复若干恼人细节 |
| Substrate | 基岩底层优化 |
| Lomka | 杂项小优化集合 |
| HTP CIT Optimizer | CIT Resewn 内存开销优化补丁 |
| Smooth Movement | 平滑移动插值 |
| View Bobbing Mod | 移除画面摇晃 |

### 画面渲染（10 个）

| Mod | 说明 |
|---|---|
| Iris | 光影支持（OptiFine 兼容） |
| Reese's Sodium Options | Sodium 视频设置界面 |
| Sodium Extra | OptiFine 视觉选项移植 |
| Sodium Dynamic Lights | 动态光源 |
| Sodium Extras | Sodium 附加选项 |
| Better Grassify | 更好的草地 |
| Continuity | 连接纹理 |
| Connectivity | 方块连接渲染 |
| CIT Resewn | 自定义物品纹理 |
| WI Zoom | WI 变焦 |

### 物品与配方（8 个）

| Mod | 说明 |
|---|---|
| JEI | 物品管理器 |
| Just Enough Professions | 村民职业显示 |
| Just Enough Beacons | 信标显示 |
| Jecharacters | JEI 界面优化 |
| JEED | 药水效果显示 |
| JEPP | 绘画预览 |
| Enchantment Descriptions | 附魔描述 |
| EnchLevel LangPatch | 附魔等级显示优化 |

### 世界与地图（5 个）

| Mod | 说明 |
|---|---|
| JourneyMap | 旅行地图 |
| Bobby | 区块缓存，支持更大渲染距离 |
| Better Biome Blend | 生物群系过渡优化 |
| Dimension Data Fix | 维度数据修复 |
| Dimension Sync Fixes | 维度同步修复 |

### 聊天与社交（3 个）

| Mod | 说明 |
|---|---|
| No Chat Reports | 禁用聊天举报 |
| Chat Patches | 聊天界面优化 |
| Chat Heads | 聊天头像 |

### 汉化与本地化（3 个）

| Mod | 说明 |
|---|---|
| I18n Update Mod | 自动汉化更新 |
| SCLP | Sodium 界面汉化 |
| Language Reload | 语言即时重载 |

### 技术/建造工具（5 个）

| Mod | 说明 |
|---|---|
| Carpet | 地毯技术 Mod |
| Litematica | 投影（蓝图建造） |
| Litematica Printer | 投影自动打印 |
| Tweakeroo | 批量操作与调试工具 |
| Replay Mod | 录像回放 |

### 联机相关（6 个）

| Mod | 说明 |
|---|---|
| Fast IP Ping | 跳过 IP 反查降低联机延迟 |
| PingFix | 定期刷新服务器列表延迟 |
| Server Pinger Fixer | 修复服务器列表刷新异常 |
| Server Core | 服务端优化 |
| Lan Server Properties | 局域网联机设置 |
| Too Many Players | 支持更多玩家同服 |

### 界面与实用（29 个）

| Mod | 说明 |
|---|---|
| Mod Menu | Mod 配置菜单 |
| Controlling | 按键冲突检测 |
| Searchables | 配置界面搜索 |
| Shulker Box Tooltip | 潜影盒内容预览 |
| Inventory HUD+ | 物品栏 HUD |
| Inventory Profiles Next | 一键背包整理 |
| InvMove | 背包中移动 |
| Mouse Tweaks | 鼠标手势 |
| AppleSkin | 食物饱和度显示 |
| Better Stats | 统计界面优化 |
| Better Advancements | 进度界面优化 |
| Better Ping Display | 显示具体延迟数字 |
| Title Fix | 标题修复 |
| Tooltip Fix | 提示框修复 |
| Boat Item View | 船中物品显示 |
| Client Crafting | 客户端合成 |
| Fast Items | 物品加载加速 |
| Fast Recipes | 配方加载加速 |
| Quick Pack | 数据包加载加速 |
| Freecam | 自由视角 |
| Dynamic Crosshair | 动态准星 |
| Dynamic Crosshair Compat | 动态准星兼容 |
| Gamma Utils | 亮度/夜视调节 |
| Hide Modded | 隐藏"已修改"标记 |
| No Realms Button | 移除 Realms 按钮 |
| Remove Welcome Screen | 移除欢迎界面 |
| Disable Custom Worlds Advice | 禁用自定义世界警告 |
| No Pack Compat Check | 禁用资源包兼容性检查 |
| IMBlocker | 输入法自动关闭 |

### 系统与兼容（7 个）

| Mod | 说明 |
|---|---|
| Custom Skin Loader | 万用皮肤加载 |
| Windows Priority Boost | 进程优先级提升 |
| Window Fix | 窗口位置修复 |
| Fastquit | 快速退出 |
| Packet Fixer | 数据包/NBT 兼容性修复 |
| macOS Input Fixes | macOS 输入修复 |
| Windows Keyboard Fixes | Windows 键盘修复 |

### 游戏体验与杂项（16 个）

| Mod | 说明 |
|---|---|
| Cerulean | 进度系统优化 |
| BugJump | 修复 BugJump 相关 Bug |
| Fix Horizontal Camera Lag | 修复骑乘时视角水平移动延迟（MC-259512） |
| Game Menu Remove GFARB | 移除游戏菜单的 GFARB 元素 |
| Highlighter | 高亮新拾取的物品 |
| Iceberg | 事件与工具支持库 |
| MCFC | 服务端函数编译为 Java 字节码 |
| Naiy | 娱乐性 Mod |
| Ruok | 娱乐性 Mod |
| PCA Protocol | PCA 协议支持 |
| Resource Pack Checker | 服务端资源包检查 |
| ShadowConfig | 可扩展配置库 |
| Craft Config | 支持预设与按键绑定的配置库 |
| WMB | 工具库 |
| Infinite Music | 移除音乐曲目间延迟 |
| Modern UI | 现代化 UI 框架 |

### 支持库（17 个，均被其他 Mod 依赖，请勿单独移除）

| 支持库 | 被谁依赖 |
|---|---|
| Fabric API | 全部 Fabric Mod |
| Architectury | 跨平台 Mod |
| Fabric Language Kotlin | Inventory Profiles Next、libIPN |
| Cloth Config | Gamma Utils、FastQuit、InvMove、Shulker Box Tooltip |
| Yet Another Config Lib | Stfu、Cull Less Leaves、BetterGrassify |
| Forge Config API Port | Highlighter、ModernUI |
| Bookshelf | Enchantment Descriptions、Better Stats |
| CoroUtil | 多个 Mod 共享 |
| MidnightLib | FastItems |
| MossyLib | CollisionFix |
| TCDCommons | BetterStats |
| Txnilib | Cerulean |
| libIPN | Inventory Profiles Next |
| CerbonsAPI | Just Enough Beacons |
| Malilib | Litematica、Tweakeroo |
| Resourceful Config | 多个 Mod 的配置界面 |
| Cupboard | 通用工具库 |

---

## 许可协议

本项目采用 MIT 许可证。

## 支持我们

如果这个项目对您有帮助，欢迎点亮 GitHub 仓库右上角的 Star。

## 许可与致谢

本整合包仅收集并打包了各 Mod 作者的公开作品，未对 Mod 本身做任何修改。各 Mod 的许可协议请参阅其原始发布页面。

感谢所有 Mod 作者的无私贡献。
