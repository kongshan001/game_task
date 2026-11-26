# MANIFEST — 任务记录与归档目录对照

- 生成时间：2026-11-26
- 来源仓库：`kongshan001/modelfw_demo` @ `22dfa74e0e65b60e358fabad8491bf5569294325`（分支 `feat/ai-slice`）
- 任务台账来源：`~/.cc-connect/tasks/{done,failed,running}` 的 `task.json` / `git.json`
- 记录总数：85 条 = 84 条历史任务 + 本归档任务 T-20261126-003；commit 取自 `git.json`，缺失时用 `git log --all --grep=<任务ID>` 或代表产物的首个提交
- 归档范围：modelfw_demo HEAD 已跟踪文件，白名单目录；未跟踪/忽略/白名单外内容不导出

## 1. 已完成任务（done，73 条）

| 任务 ID | 标题 | 状态 | game_task 目录 | modelfw_demo commit | 备注 |
| --- | --- | --- | --- | --- | --- |
| T-20261119-004 | 拆解 Windows 双击安装 APK 的开源项目 | done | docs/（APK 拆解） | 6ce4e9b | 早期批次（无队列 git.json） |
| T-20261119-005 | Water Pro + Three.js 体积云复刻 | done | threejs-water-clouds/ | f16303e | 早期批次（无队列 git.json）；2026-11-20 批量入库 |
| T-20261119-007 | Reelward 美术升级（T-002 follow-up） | done | godot-slot-defense/ | f16303e | 早期批次（无队列 git.json）；美术升级随批量入库提交 |
| T-20261119-008 | 齐天大圣·极意（游戏级可玩版） | done | godot-wukong-ultimate/、blender-wukong-ultimate/ | f16303e | 早期批次（无队列 git.json）；2026-11-20 批量入库 |
| T-20261120-001 | 拆解 Unity 仿绝区零 Demo | done | docs/ | a609e67 | — |
| T-20261120-002 | 像素水面 + 木筏效果复刻 | done | godot-pixel-ocean/ | 3d654e1 | — |
| T-20261120-003 | 像素木筏钓鱼/收集/扩建复刻 | done | godot-raft-fishing/ | 005ecdb | — |
| T-20261120-005 | 修正像素水面倒影/水线（T-002 follow-up） | done | godot-pixel-ocean/ | 576ad42 | — |
| T-20261120-006 | 木头人纸娃娃角色系统（T-004 重试） | done | godot-paper-doll/ | 2933440 | — |
| T-20261120-007 | 纸娃娃美术评审 + 美术 agent 提示词库 | done | docs/ | 3c37c57 | .claude/agents 提示词库按白名单排除 |
| T-20261120-009 | 纸娃娃美术实现（Game Artist） | done | godot-paper-doll/ | 763d25b | — |
| T-20261120-010 | 纸娃娃技术/性能/AA（Game Engineer） | done | godot-paper-doll/ | 7b78bc9 | — |
| T-20261120-011 | 纸娃娃 QA 独立验收（QA Lead） | done | godot-paper-doll/、docs/ | b381055 | QA 脚本位于 godot-paper-doll/tools/ |
| T-20261120-012 | 纸娃娃独立美术复评（Art Director） | done | docs/ | 71e011e | — |
| T-20261120-013 | 纸娃娃策划设计方案（Game Designer） | done | docs/ | fa004e3 | — |
| T-20261121-001 | 纸娃娃走路脚姿/滑步修复（Game Artist） | done | godot-paper-doll/ | 18537e7 | — |
| T-20261121-002 | 走路脚姿 QA 复验（QA Lead） | done | docs/ | b2487fb | — |
| T-20261121-003 | 走路动画独立复评（Art Director） | done | docs/ | 3b81ed6 | — |
| T-20261121-004 | 外部参考对标 · 美术质量差距量化（Art Director） | done | docs/ | 8b15792 | — |
| T-20261121-005 | 复刻《地图随机生成》波函数坍缩（WFC）可交互 Demo | done | godot-wfc/ | 9bae264 | — |
| T-20261121-006 | 复刻《群体寻路与避障》Steering Behavior 可交互 Demo | done | godot-steering/ | c7c7bea | — |
| T-20261121-007 | 材质与特效专项整改（Game Artist） | done | godot-paper-doll/ | f4fd975 | — |
| T-20261121-009 | 续跑 Flow Field 流场寻路 Demo（T-008 重试） | done | godot-flowfield/ | 21dfe97 | — |
| T-20261121-010 | 调研 · 回合制游戏法术表现性能分析与审计方法 | done | docs/ | 6b65665 | — |
| T-20261121-011 | Flow Field 审计级性能复测与优化消融（Game Engineer） | done | godot-flowfield/ | 8ca2b90 | — |
| T-20261121-012 | Flow Field 技术原理报告 + 文档沉淀（T-009 follow-up） | done | godot-flowfield/、docs/ | 0b9983a | 跨引擎文档在 godot-flowfield/docs/portable/ |
| T-20261121-013 | 复刻 Duelyst 式卡牌战棋（CC0 资产）可玩 Vertical Slice | done | godot-card-tactics/ | 3f74a35 | — |
| T-20261121-014 | 复刻《幻唐志》手游道具背包界面（Godot UI） | done | godot-inventory-ui/ | f8240d0 | — |
| T-20261121-015 | 背包界面 1:1 复刻校正（T-014 follow-up） | done | godot-inventory-ui/ | c19ea97 | — |
| T-20261121-016 | Duelyst 复刻开发文档 + 跨引擎资产包（T-013 follow-up） | done | godot-card-tactics/ | 70fb1ff | — |
| T-20261121-017 | 背包界面开发文档 + 跨引擎资产包（T-015 follow-up） | done | godot-inventory-ui/ | 4881e07 | — |
| T-20261121-018 | 格间牌战独立美术评审（T-013 follow-up） | done | docs/ | 41b5995 | — |
| T-20261121-019 | 格间牌战美术整改（T-018 follow-up） | done | godot-card-tactics/ | 6715f71 | — |
| T-20261121-021 | Godot 程序化地图生成优秀案例复刻（T-020 follow-up） | done | godot-proc-map/ | 4bec289 | — |
| T-20261121-022 | 调研 · Godot 3D 海岛生成方案（T-020 follow-up） | done | docs/ | 3a0ef20 | — |
| T-20261121-023 | 复刻 PixelFX 像素特效（挥剑/火球/冰冻/捡金币）Godot Demo | done | godot-pixel-vfx/ | 8dd135f | — |
| T-20261121-024 | 复刻 Opus 5.5 长安城动作游戏 · 设计规格（Game Designer） | done | docs/ | 9a5ad10 | — |
| T-20261121-025 | 复刻 Opus 5.5 长安城动作游戏 · 可玩 Vertical Slice（T-024 follow-up） | done | godot-changan-action/ | aca4af5 | — |
| T-20261121-026 | 复刻《雾港撤离》式俯视角搜打撤 Demo | done | godot-fog-harbor/ | b5796cb | — |
| T-20261121-027 | 调研 · 独立开发者 10 个开源游戏工具链 | done | docs/ | 2f00828 | publisher: no_changes（产出已由 worker 提交） |
| T-20261121-029 | 美术 Agent Blender 二次元角色能力探针 | done | agent-probes/ | 5cb3fc5 | — |
| T-20261121-030 | 调研 · Blender 二次元女性角色管线（供美术 Agent 能力建设） | done | docs/ | bc221b2 | — |
| T-20261121-032 | 调研 · 鬼灭「无限城」AI 3D 动作游戏 + MotionStage 工具 | done | docs/ | 1a6b8c8 | — |
| T-20261121-033 | 调研 · 玩法创新方法与案例库（Game Designer 能力建设） | done | docs/ | 12a3562 | — |
| T-20261121-034 | Game Designer 玩法创新能力建设（T-033 follow-up） | done | docs/ | dbf9f8a | .claude/skills/gameplay-innovation 按白名单排除；docs/design、docs/templates 已归档 |
| T-20261121-035 | 玩法创新方案红队评审（T-034 follow-up） | done | docs/ | 1ae4103 | — |
| T-20261121-036 | 调研 · 小游戏换皮/重皮肤管线 | done | docs/ | a87afbc | publisher: no_changes（产出已由 worker 提交） |
| T-20261121-037 | 复刻 Godot Particles 魔法发射特效教程 | done | godot-magic-vfx/ | 045bd38 | — |
| T-20261121-038 | 拆解「挑战极限，一局搞定，你能顶住几波进攻」并给复刻 brief | done | docs/ | 3b6e4e7 | — |
| T-20261121-040 | 续跑 Godot 程序化地图调研（T-020 重试） | done | docs/ | 3bcf49e | — |
| T-20261121-041 | 续跑 AI 半成品 4 步抢救法（T-028 重试） | done | docs/ | f81202e | — |
| T-20261121-042 | 雾港撤离玩法创新迭代（T-026 follow-up） | done | docs/ | 5e8e6d0 | — |
| T-20261121-043 | 长安城动作游戏美术评审（T-025 follow-up） | done | docs/ | 3d911c6 | — |
| T-20261121-044 | 商品截图比价 Web 应用（Product Scout） | done | docs/（infra 规划） | 4d021f2 | product-scout/ 按白名单排除，仅规划文档归档 |
| T-20261123-002 | 鬼灭 P2 模型本地接入长安城动作 Demo（不入库） | done | — | — | 排除：第三方 IP（鬼灭）模型，commit_paths 为空，按任务要求不入库 |
| T-20261124-001 | 复刻《迷雾北境 / Bad North》式极简实时战术防守 Demo | done | godot-island-defense/ | 1158569 | — |
| T-20261124-002 | 复刻《时之笛重制版》雾气效果（Godot 大气/体积雾） | done | godot-fog-atmosphere/ | 64d9c32 | — |
| T-20261124-003 | 复刻 Godot 弹幕教程（10 种弹幕 + Boss 时间轴） | done | godot-bullet-hell/ | bbb99be | — |
| T-20261124-004 | 复刻 GPT-6 + Hyper3D 3D 小游戏（AI 资产管线） | done | godot-ai-3d-game/ | a968a71 | — |
| T-20261124-005 | 雾效 Demo 追加角色与动态驱散（T-002 follow-up） | done | godot-fog-atmosphere/ | 4f4bfd7 | — |
| T-20261125-001 | 用 Tripo 重建《青岚杯》赛车资产（T-004 follow-up） | done | godot-ai-3d-game/ | b7507f1 | — |
| T-20261125-002 | 《青岚杯》真实感汽车 Tripo 重建（T-001 follow-up） | done | godot-ai-3d-game/ | ebbc707 | — |
| T-20261125-003 | 续跑波次生存 Vertical Slice（T-039 重试） | done | godot-wave-defense/ | 206b365 | — |
| T-20261125-004 | 复刻 Unity 雨天积水（Godot 2D 像素雨/水洼） | done | godot-rain-puddles/ | 0f9c750 | — |
| T-20261125-005 | 复刻《Memoria Wake》式等轴类魂银河城（雨伞弹反）Vertical Slice | done | godot-dream-parry/ | d78a029 | — |
| T-20261125-006 | 沉淀「打击感」设计经验：浏漓顿挫与 Godot 实现参数 | done | docs/ | b300842 | — |
| T-20261125-007 | 复刻 2D 像素樱花树动态日照（三角函数/无 3D 灯光） | done | godot-sakura-sunlight/ | cb86eb8 | — |
| T-20261125-008 | 复刻 2D 像素法线受光 + 零额外相机水面夜景反射 | done | godot-pixel-normal-water/ | 5dcbaf8 | — |
| T-20261125-009 | 复刻 feralui 风格治愈场景（AI 游戏场景 / 微动画） | done | godot-feralui-scene/ | ff131aa | — |
| T-20261125-010 | 复刻《八方旅人》式 2D 像素光影 + 移轴景深 | done | godot-hd2d/ | fdc3c4c | — |
| T-20261125-011 | 原创角色眨眼动画能力测试（Blender 形态键） | done | agent-probes/ | 22dfa74 | — |
| T-20261125-012 | 复刻 LDtk 式 2D 关卡编辑器（Godot 工具） | done | godot-level-editor/ | 7e5752a | — |
| T-20261125-013 | 复刻 Godot 法线贴图精灵光照教程 | done | godot-sprite-normal-light/ | f502293 | — |

## 2. 失败任务（failed，9 条）

失败任务未产生独立提交；下表的目录是后继重试/接力任务补齐后的最终位置。

| 任务 ID | 标题 | 状态 | game_task 目录 | modelfw_demo commit | 备注 |
| --- | --- | --- | --- | --- | --- |
| T-20261120-004 | 木头人 17 槽位纸娃娃角色系统复刻 | failed | godot-paper-doll/ | — | failed：由 T-20261120-006 重试补齐 |
| T-20261120-008 | 纸娃娃美术整改（P0+P1） | failed | godot-paper-doll/ | — | failed：由 T-20261120-009/010/012 接力补齐 |
| T-20261121-008 | 复刻 Flow Field 流场寻路群体寻路 Demo | failed | godot-flowfield/ | — | failed：由 T-20261121-009 重试补齐 |
| T-20261121-020 | 调研 · Godot 程序化地图生成技术方案与优秀案例 | failed | docs/ | — | failed：由 T-20261121-040 重试补齐 |
| T-20261121-028 | 调研 · AI 半成品游戏 4 步抢救法 | failed | docs/ | — | failed：由 T-20261121-041 重试补齐 |
| T-20261121-031 | 美术 Agent Blender 二次元能力建设（T-029 follow-up） | failed | docs/、agent-probes/（部分） | — | failed：tools/blender_anime 未入库；探针能力由 T-20261121-029/030 补齐 |
| T-20261121-039 | 波次生存 Vertical Slice（T-038 follow-up） | failed | godot-wave-defense/ | — | failed：由 T-20261125-003 重试补齐 |
| T-20261121-045 | Tripo 高质量图生 3D 工作流调研 + 鬼灭主角私有测试 | failed | docs/（工作流文档由后继提交补齐） | — | failed：鬼灭主角私有测试产物不入库 |
| T-20261123-001 | 3D 角色动画方案对比（Mixamo vs 商业/开源/AI 动捕） | failed | — | — | failed：无归档产出 |

## 3. 进行中任务（running，3 条）

| 任务 ID | 标题 | 状态 | game_task 目录 | modelfw_demo commit | 备注 |
| --- | --- | --- | --- | --- | --- |
| T-20261126-001 | 复刻 2D 海/河/湖共用 1 个水面 Shader（零额外网格） | running | godot-water-shader/（待同步） | — | running：本地未跟踪目录，本快照未包含 |
| T-20261126-002 | 复刻 2D 太阳/月亮动态影子（零额外灯光） | running | godot-sun-moon-shadows/（待同步） | — | running：本地未跟踪目录，本快照未包含 |
| T-20261126-003 | 新建 game_task 仓库归档游戏代码与资产 | running | （本仓库） | — | running：正在创建 game_task 并归档（即本仓库） |

## 4. 未包含 / 待同步项

| 项目 | 状态 | 原因 / 计划 |
| --- | --- | --- |
| `godot-water-shader/` | 待同步 | T-20261126-001 运行中，modelfw_demo 工作区中仍未跟踪；源仓库提交后按增量同步补入 |
| `godot-sun-moon-shadows/` | 待同步 | T-20261126-002 运行中，同上 |
| 鬼灭 P2 模型 | 排除 | T-20261123-002 明确不入库（第三方 IP，commit_paths 为空） |
| `bench_*`、`bench_results/`、`cpp/`、`ark-examples/`、`product-scout/`、`tools/` | 排除 | 基准、工具链、非游戏工程，按归档白名单排除 |
| 根 `.claude/`、`.github/`、`CLAUDE.md`、`README.md`、`Makefile`、`pytest.ini`、`benchmark*.py`、`cmodel*.py`、`compare.py`、`demo_batch.py` | 排除 | harness / 基准 / 仓库级配置，不属于游戏资产快照 |
| `tripo-out/`、`.tripo/`、`.cc-connect/` | 排除 | 生成中间产物与会话数据 |
| 子项目内 `CLAUDE.md` / `AGENTS.md` / `.claude/skills/` | 保留 | 属各项目自带的 AI 使用入口（README 有引用），非仓库级 harness 配置 |

## 5. 计划文件中存在、未进入 cc-connect 队列的早期任务（4 条）

这批任务记录在 `docs/task-plans/*.md`，但早于 dispatcher 队列，产出已在本快照中。

| 任务 ID | 标题 | 状态 | game_task 目录 | modelfw_demo commit | 备注 |
| --- | --- | --- | --- | --- | --- |
| T-20261119-001 | 拆解 Rogue 程序化关卡生成算法 | done | `docs/`（讲义 + 算法 demo） | 6ce4e9b | 计划记录，无队列 JSON |
| T-20261119-002 | 复刻老虎机塔防（Slotbound 风格） | done | `godot-slot-defense/` | f16303e | 计划记录，无队列 JSON |
| T-20261119-003 | cc-connect 异步并行任务调度 | done | `docs/`（任务路由文档） | 6ce4e9b | `tools/` 与根 `CLAUDE.md` 排除 |
| T-20261119-006 | 齐天大圣 · 斗战形态（首版） | done | `blender-wukong/` | f16303e | 计划记录，无队列 JSON |

## 6. 无任务记录的早期目录（13 个）

早于 cc-connect 任务体系的产物；按白名单整体归档，首个提交如下。

| 目录 | 内容 | 首个提交 | 备注 |
| --- | --- | --- | --- |
| `animation-retarget-kit/` | Blender 动作重定向工具包 | f884783（2026-11-14） | 含 `LICENSES/` 第三方许可 |
| `blender-hb7/` | Blender HB-7 程序化产品短片 | f16303e（2026-11-20） | 批量入库 |
| `craft-cloudride/` | Cloudride 云海骑行复刻 | f16303e（2026-11-20） | Rust + Web 工程 |
| `craft-island/` | Craft Island 海岛复刻 | f16303e（2026-11-20） | Rust + Web 工程 |
| `godot-ai-slice/` | AI Slice — Sky Circuit | 20f0ce9（2026-11-14） | 早期 AI 迭代切片 |
| `godot-battle/` | 山海试炼 · 2D 回合制战斗 | 6d1209b（2026-10-24） | 早于任务队列 |
| `godot-garden/` | 废墟花园 · 黄昏 | f16303e（2026-11-20） | 后续 f30ee2c 有更新 |
| `godot-iso-slice/` | 烛光地牢 · Iso Slice | f16303e（2026-11-20） | 批量入库 |
| `godot-mech-bee/` | Mellis HB-7 · 3D Teardown Study | f16303e（2026-11-20） | 批量入库 |
| `godot-mixamo-demo/` | Mixamo → Godot 4.6 Demo | 12e74ec（2026-11-12） | 动画重定向演示 |
| `godot-sea-water/` | 星海浅湾 · Starwater | f16303e（2026-11-20） | 批量入库 |
| `godot-snowfall/` | 雪夜墓园 · Snowfall | f16303e（2026-11-20） | 批量入库 |
| `portable-core/` | 跨引擎核心层 | f16303e（2026-11-20） | 含 spec/impl/tests |

## 7. 归档统计与核对

- 归档目录：46 个 —— 36 个 `godot-*` 可运行 demo、3 个 `blender-*` 资产、`threejs-water-clouds/`、`craft-cloudride/`、`craft-island/`、`animation-retarget-kit/`、`portable-core/`、`agent-probes/`、`docs/`
- 归档文件：3664 个（`git archive` 导出 3665 个；删除 `*.blend1` 2 个与嵌套 `tripo-out/` 2 个；新增 README/MANIFEST/.gitignore 3 个；以 `git ls-files | wc -l` 复核为 3664）
- 最大文件：`agent-probes/blender-anime-girl/qinghe.blend`（约 19.3 MiB）；无 >100 MiB 文件
- 任务记录覆盖：85 条全部给出目录映射或排除原因（84 条历史 + 本归档任务）
- 未闭环：2 个运行中目录待同步；1 个第三方 IP 任务明确排除
- 核对命令：`git ls-files | wc -l`、`find . -type f -size +100M`，并以密钥/会话 ID 模式（GitHub token、云厂商 AK、私钥头、OAuth 前缀、cc-connect 会话标识）扫描，结果 0 命中
