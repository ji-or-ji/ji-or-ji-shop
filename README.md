# 是季不是鸡的小店

## 介绍

这是是季不是鸡的小店~！欢迎各位前来休憩~

## 置物架

是的，这里只是一个置物架，用来存放各种我自己做的一些小玩意。大部分项目在 **GitHub** 与 **Gitee** 双仓维护：「链接」列一般指向 **GitHub 主仓库** 与 **Gitee 镜像**；个别只有 Gitee，会标注「GitHub 镜像待建」。「备注」列是该项目的说明。本店仓库的 Gitee 镜像在 [gitee.com/ji-or-ji/ji-or-ji-shop](https://gitee.com/ji-or-ji/ji-or-ji-shop)。

## 使用说明

很简单，只需要点击 **相应的链接** 就可以跳转到 **相应的界面** 了。

## 现在有什么

| 项目 | 链接 | 备注 |
| :-- | :-- | :-- |
| Python重温计划 | [GitHub](https://github.com/ji-or-ji/Python-Rediscovery-Path) · [Gitee](https://gitee.com/ji-or-ji/Python-Rediscovery-Path) | 从零重温 Python 的学习记录：学习地图、笔记与练习。 **进行中。** |
| 一个简单的随机点歌小软件 | [GitHub](https://github.com/ji-or-ji/random_songs) · [Gitee](https://gitee.com/ji-or-ji/random_songs) | 功能丰富的 Python 命令行随机点歌系统：歌曲 / 点歌人 / 多歌单管理、自动网页跳转、操作历史。 _（旧版，已由下面的重制版取代，仅作留档）_ |
| 随机点歌系统 · 重制版 | [GitHub](https://github.com/ji-or-ji/replace_random_songs_system) · [Gitee](https://gitee.com/ji-or-ji/replace_random_songs_system) | 在原版基础上完整重写：数据改用 YAML、可离线安装；既有命令行版（静默抽歌，便于与 ClassIsland 联动），也有原生的 Windows 桌面端（.NET 8 + WinUI 3），两边共用同一份数据。详细功能见仓库说明。 |
| desk-ink · 桌面墨水屏信息站 | [GitHub](https://github.com/ji-or-ji/desk-ink) · [Gitee](https://gitee.com/ji-or-ji/desk-ink) | ESP32-C3 + 4.2 寸墨水屏，显示课表 / 待办 / 每日一言 / 新闻 / 插画；设计主线是省电（深睡 + RTC 定时唤醒，目标约 18µA、1000mAh 续航约 32 天）。配套 PC 端工具同样是 .NET 8 + WinUI 3。**尚未实机验证**：代码与 UI 已完成（UI 在 QEMU 里逐状态验证过），但尚未点亮真实墨水屏、未连接真实硬件、PCB 尚未布线。 |
| 御风bot | [GitHub](https://github.com/ji-or-ji/yufeng-bot) · [Gitee](https://gitee.com/ji-or-ji/yufeng-bot) | _（一个基于 NapCat 与 Python 的赛博群友）_ **已停止开发**（相关能力已由 MaiBot 配合自研插件实现）从零搭建的多 AI 代理群聊系统：人格代理、长期记忆、富媒体理解与主动社交，试图在代码中注入"灵魂"的实验。 |
| 卧底机器人 (UndercoverBot) | [GitHub](https://github.com/ji-or-ji/Undercover-Bot) · [Gitee](https://gitee.com/ji-or-ji/Undercover-Bot) | 一个用于潜伏在 QQ 群中监控关键词、自动预警、收集证据的机器人框架。**目前暂时搁置**（已确认技术可行性；初衷是应对网络不良信息，眼下不再需要）。代码留作参考，欢迎感兴趣的朋友自行取用。 |
| 超薄版 ZHAO-watchV2 · CLion 版 | [GitHub](https://github.com/ji-or-ji/ZHAO-watch-V2_CLion_Edition) · [Gitee](https://gitee.com/ji-or-ji/ZHAO-watch-V2_CLion_Edition) | 原版是 Keil（µVision5）工程，这里重制为 CLion + CMake 工程（超薄版），以适合现代化开发。 |
| SPIKE 项目版本控制工具集 | [GitHub](https://github.com/ji-or-ji/spike-handler) · [Gitee](https://gitee.com/ji-or-ji/spike-handler) | 解包 / 打包 .llsp3 文件，配合 Git 做版本管理：仓库初始化与配置、一键清理 SPIKE 缓存、支持回退到任意历史版本。 |
| 浮墨笔记（flomo）接入插件 | [GitHub](https://github.com/ji-or-ji/open-hanako-flomo) · [Gitee](https://gitee.com/ji-or-ji/open-hanako-flomo) | 为 Hanako 提供 flomo 笔记的写入、导入、搜索与管理能力（Agent 驱动）。 Apache-2.0。 |
| 终末地风格局域网设备监视台 | [GitHub](https://github.com/ji-or-ji/endfield-monitor) · [Gitee](https://gitee.com/ji-or-ji/endfield-monitor) | 不开远程桌面就能看见一台 Windows 机器的运行状况：C# + Avalonia 桌面客户端配一个只读的 Go 单文件采集端（早期 Python 版已弃用，留作参考），实时读 CPU / 内存 / 磁盘 / 网络 / 进程，也能顺带盯住指定的服务与端口。界面风格致敬 zmd-manager。 **进行中。** |
| RVC 实时变声 · ONNX 版 | [GitHub](https://github.com/ji-or-ji/rvc-onnx-realtime) · [Gitee](https://gitee.com/ji-or-ji/rvc-onnx-realtime) | 把 RVC 实时变声接到 **ONNX Runtime** 上，绕开 `torch-directml` 的性能坑，并横向对比 CPU / 独显(DML) / 核显(DML) 三种后端。同硬件下快 10~25 倍；结论是核显跑实时不成立，真正有意义的是 2060 走 ONNX 或 CPU 走 ONNX。附带浏览器控制台与三处 RVC-WebUI 补丁。 |
| 机械动力：浆果工业（模组企划） | [Gitee](https://gitee.com/ji-or-ji/Create-Berries) · _GitHub 镜像待建_ | 把原版那条单薄的「浆果」食物线接进机械动力的自动化与多步加工逻辑，让浆果不只是食物，更是工业原料。仓库目前是设计文档：新物品 / 方块 / 流体清单，外加连锁经济与生存机制平衡（副产物双向决策、兼容 Tough As Nails 的水分值惩罚）。 **企划阶段。** |
| 插件安装审批器 | [GitHub](https://github.com/ji-or-ji/maibot-plugin-installer) · [Gitee](https://gitee.com/ji-or-ji/maibot-plugin-installer) | 把造好的麦麦插件经**管理员批准**后自动安装并启用，在发起任务的聊天流里请求审批；是[麦麦 × dsh 桥](https://github.com/ji-or-ji/maibot-dsh-bridge)的配套下游。 |
| 麦麦 × dsh 桥 | [GitHub](https://github.com/ji-or-ji/maibot-dsh-bridge) · [Gitee](https://gitee.com/ji-or-ji/maibot-dsh-bridge) | 把 DeepSeek Harness 接入麦麦：一句话下单、dsh 在后台把活干完，过程以合并转发回传，产出的文件打包发回群，还能定时自排班。 |
| Hanako2DSH | [GitHub](https://github.com/ji-or-ji/hanako2dsh) · [Gitee](https://gitee.com/ji-or-ji/hanako2dsh) | 把本机官方的 DeepSeek Harness 接进 Hana：**一个页签里看它干活，一句话把活派给它。** |
| 麦麦假装看视频 | [GitHub](https://github.com/ji-or-ji/mai-video-adaptive) · [Gitee](https://gitee.com/ji-or-ji/mai-video-adaptive) | 麦麦视频理解插件：抽多少帧由画面内容决定（不是定时抽），配合语音转录交给视觉模型理解，重复视频秒级复用。**不会主动对视频发表评论。** |
| Hanako 假装看视频 | [Gitee](https://gitee.com/ji-or-ji/hanako-video-understand) · _GitHub 镜像待建_ | HanaAgent 的视频理解插件：抽多少帧由画面变化决定，不是定时抽；配合语音转录交给视觉模型，产出带时间戳的描述。纯音频文件也能直接读。算法移植自「麦麦假装看视频」，外壳换成 Hana 插件。 PolyForm Noncommercial 1.0.0。 |
| 麦麦不发 emoji 了 | [GitHub](https://github.com/ji-or-ji/maimai-no-more-emoji) · [Gitee](https://gitee.com/ji-or-ji/maimai-no-more-emoji) | 检测麦麦出站消息里的 emoji，由 LLM 判断是否该替换，若该换就从表情包库挑一张合适的图片放到消息末尾，治「结尾/句中硬塞 emoji、用得多且不贴切、显得出戏」。 |
| 窝幺烟牌（预警管家） | [GitHub](https://github.com/ji-or-ji/guardian-alert-plugin) · [Gitee](https://gitee.com/ji-or-ji/guardian-alert-plugin) | 监测私聊 / 群聊中的风险信号（拉群邀请 / 情感依赖 / 隐私泄露 / 金钱往来 / 冒充话术 / 诱导操纵），命中后自动推送管理员，及时发现 bot 被拐带、群友过度依赖等异常。 |
| 麦麦喊新人说话（加群考察期） | [GitHub](https://github.com/ji-or-ji/group-probation-plugin) · [Gitee](https://gitee.com/ji-or-ji/group-probation-plugin) | 新人入群自动 @ 欢迎邀请发言，超过考察时长（默认 48 小时）仍不发言的新成员自动移出群聊。 |
| 麦麦看到你了（群感知插件） | [GitHub](https://github.com/ji-or-ji/group-awareness-plugin) · [Gitee](https://gitee.com/ji-or-ji/group-awareness-plugin) | 感知群人员变动（进群 / 退群 / 禁言 / 群名 / 管理变动），可选固定模板 / 人格化 LLM / 注入上下文三种处理；提供群荣誉、群员称号、群头像、群公告、禁言列表等工具化查询。 |
| 麦麦财务总结优化 | [GitHub](https://github.com/ji-or-ji/maibot-expenses-summary-plus) · [Gitee](https://gitee.com/ji-or-ji/maibot-expenses-summary-plus) | 统计当天模型调用次数、回复量和成本并生成财报；在保留原版功能的基础上，新增官方牌价引擎、订阅制 / 混合计费口径与账本人工修正量。 **与原版互斥。** 本仓库是优化分支，另有一个原版 fork（maibot-expenses-summary-plugin，含捐赠账本等改动），不单独收录。 |
| 背水一战（Last Stand） | [Gitee](https://gitee.com/ji-or-ji/last-stand) · _GitHub 镜像待建_ | Minecraft 1.21.1 的 NeoForge 模组：你身上的某个部分还没打算让你死。致命一击到来时，若身体还有余粮就把死亡换成三分钟的锁血窗口，窗口里每一次受伤都在加倍燃烧饱食度；撑过去是虚弱期，撑不过去是一段能看着自己倒下的处决演出。含二连触发、PVP 五秒回溯、低血预演与全参数配置。 **开发中，加载与渲染已实机跑通，数值与手感仍在调。** Apache-2.0。 |
| PC Status（电脑状态感知） | [GitHub](https://github.com/ji-or-ji/hanako-pc-status) · [Gitee](https://gitee.com/ji-or-ji/hanako-pc-status) | HanaAgent 插件：让 Agent 看清这台机器的处境，包括电量、是否插电、剩余可用时间、电源计划、CPU / 内存 / 磁盘，以及 hana-server 到底还活着没有。另有一条暗线：每十分钟在任意工具返回的末尾补一行带秒的时间；电量紧张时再加一句鼓励，专治模型见到资源不足就缩手。hana-server 异常终止后，下次会话会悄悄递一张便条，提醒它上下文断了一截，用户看不见。 Apache-2.0。 |
