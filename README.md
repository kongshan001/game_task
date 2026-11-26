# game_task

> AI 游戏任务代码与资产归档 —— 从 [modelfw_demo](https://github.com/kongshan001/modelfw_demo) 快照导出的 Godot / Blender / Three.js 游戏 demo 与配套文档。

## 这是什么

本仓库是 `modelfw_demo` 中**游戏产物**的只读快照：36 个独立可运行的 Godot 4.6 demo、3 个 Blender 资产工程、Three.js / Web 场景、跨引擎工具，以及 84 条历史任务对应的设计、评审与经验文档。

- 任务过程记录与台账在 [modelfw-tasks](https://github.com/kongshan001/modelfw-tasks)；
- 本仓库只放代码、资产与文档，不混放任务 JSON、worker 日志或运行时会话数据。

## 快照信息

| 项 | 值 |
| --- | --- |
| 来源仓库 | `kongshan001/modelfw_demo` |
| 来源 commit | `22dfa74e0e65b60e358fabad8491bf5569294325`（`feat/ai-slice`） |
| 快照日期 | 2026-11-26 |
| 导出方式 | `git archive HEAD -- <白名单目录>`，只含已跟踪文件 |
| 规模 | 3663 个文件 / 约 834 MiB |
| 已剔除 | `*.blend1`、`.DS_Store`、`__pycache__/`、`.godot/`、`.import/` |
| 任务映射 | 见 [MANIFEST.md](MANIFEST.md)（85 条记录，含 84 条历史任务） |

## 快速开始

### Godot demo

每个 `godot-*` 目录是独立可运行 demo（含 `project.godot`），用 Godot 4.6 打开即可；操作方式、验证命令与效果截图见**各目录自己的 README**。

```bash
godot --path godot-flowfield
```

### Blender 资产

`blender-*` 目录用 Blender 4.x 打开 `.blend` 源文件；GLB 导出与骨骼/动画说明见各目录 README。

### Three.js / Web

```bash
cd threejs-water-clouds && python3 -m http.server 8000
```

`craft-cloudride/`、`craft-island/` 为 Rust + Web 工程，构建方式见各自 README。

### 文档

`docs/` 包含任务规划、设计规格、美术评审、QA 记录、经验沉淀、效果截图与交互式讲义；任务总表见 `docs/task-plans/`。

## 目录

| 目录 | 内容 | 类型 |
| --- | --- | --- |
| `godot-ai-3d-game/` | 风车原野 · 青岚杯（AI 资产管线小游戏） | Godot |
| `godot-ai-slice/` | AI Slice — Sky Circuit | Godot |
| `godot-battle/` | 山海试炼 · 2D 回合制战斗 | Godot |
| `godot-bullet-hell/` | 绯星弹幕 · Scarlet Orbit（10 种弹幕 + Boss） | Godot |
| `godot-card-tactics/` | 格间牌战 · Gridbound（卡牌战棋） | Godot |
| `godot-changan-action/` | 灯下客 · 长安一夜（动作 Vertical Slice） | Godot |
| `godot-dream-parry/` | 梦隙 · 残响（等轴类魂，雨伞弹反） | Godot |
| `godot-feralui-scene/` | 苔光浮庭 · Mosslight Isle（治愈场景微动画） | Godot |
| `godot-flowfield/` | 流场寻路 · Flow Field（含技术原理与性能消融） | Godot |
| `godot-fog-atmosphere/` | 雾林微光 · Fogwood（大气/体积雾） | Godot |
| `godot-fog-harbor/` | 雾港余烬 · Fogfall Extraction（俯视角搜打撤） | Godot |
| `godot-garden/` | 废墟花园 · 黄昏 | Godot |
| `godot-hd2d/` | 晨光农田 · 微缩沙盘（HD-2D 光影 + 移轴） | Godot |
| `godot-inventory-ui/` | 云璃背包 · Inventory UI Study | Godot |
| `godot-island-defense/` | 雾屿守望 · Mistbound Watch（实时战术防守） | Godot |
| `godot-iso-slice/` | 烛光地牢 · Iso Slice | Godot |
| `godot-level-editor/` | 苔井工坊 · Mossgarden Level Studio（LDtk 式编辑器） | Godot |
| `godot-magic-vfx/` | Magic Projectile Lab · 魔法发射实验室 | Godot |
| `godot-mech-bee/` | Mellis HB-7 · 3D Teardown Study | Godot |
| `godot-mixamo-demo/` | Mixamo → Godot 4.6 动画重定向 Demo | Godot |
| `godot-paper-doll/` | 纸偶工坊 · Paper Doll Atelier（17 槽位纸娃娃） | Godot |
| `godot-pixel-normal-water/` | 静水回廊 · Stillwater（2D 法线受光 + 夜景反射） | Godot |
| `godot-pixel-ocean/` | Pixel Ocean · 像素海 | Godot |
| `godot-pixel-vfx/` | Pixel VFX Lab · 像素特效试验场 | Godot |
| `godot-proc-map/` | 边境制图台 · 程序化地图实验 | Godot |
| `godot-raft-fishing/` | 浮木湾 · Driftwood Cove（钓鱼/收集/扩建） | Godot |
| `godot-rain-puddles/` | 雨落青苔 · Rain Puddles（2D 像素雨/水洼） | Godot |
| `godot-sakura-sunlight/` | 樱庭日照 · Sakura Sunlight | Godot |
| `godot-sea-water/` | 星海浅湾 · Starwater | Godot |
| `godot-slot-defense/` | Reelward · 转轮守卫（老虎机塔防） | Godot |
| `godot-snowfall/` | 雪夜墓园 · Snowfall | Godot |
| `godot-sprite-normal-light/` | 灯影工坊 · Sprite Normal Light Lab | Godot |
| `godot-steering/` | 转向行为实验场 · Steering Behavior | Godot |
| `godot-wave-defense/` | 苔关八波 · Mossgate Stand（波次生存） | Godot |
| `godot-wfc/` | 坍缩花园 · Wave Function Collapse | Godot |
| `godot-wukong-ultimate/` | 齐天大圣 · 极意 — 极意试炼场 | Godot |
| `blender-hb7/` | Blender HB-7 · 10s 程序化产品短片 | Blender |
| `blender-wukong/` | 齐天大圣 · 斗战形态（首版） | Blender |
| `blender-wukong-ultimate/` | 齐天大圣 · 极意 — Blender 资产 | Blender |
| `threejs-water-clouds/` | Volumetric Shore（水体 + 体积云） | Three.js |
| `craft-cloudride/` | Cloudride · 云海骑行复刻 | Rust + Web |
| `craft-island/` | Craft Island · 海岛复刻 | Rust + Web |
| `animation-retarget-kit/` | Blender 动作重定向工具包（含第三方许可） | 工具 |
| `portable-core/` | 跨引擎核心层（spec / impl / tests） | 工具 |
| `agent-probes/` | Blender 二次元角色能力探针与眨眼测试资产 | 资产 |
| `docs/` | 任务规划、设计、评审、经验、截图与讲义 | 文档 |

## 许可与素材

- 各 demo 的第三方素材、参考来源与许可见各目录的 `CREDITS.md`（24 个目录已附）；`animation-retarget-kit/LICENSES/` 收录第三方许可原文。
- 复刻类 demo 只复刻玩法与技术方案，不复用参考作品的商标、角色、UI 与素材；角色与场景素材为原创或 CC0。
- 未附 `CREDITS.md` 的目录默认视为原创演示代码；第三方依赖以目录内说明为准。

## 与另外两个仓库的关系

| 仓库 | 用途 |
| --- | --- |
| `kongshan001/modelfw_demo` | 活跃工作区：游戏 demo + 工具链 + 基准 + harness，持续提交 |
| `kongshan001/game_task`（本仓库） | 游戏代码 / 资产 / 文档的只读快照归档 |
| `kongshan001/modelfw-tasks` | 任务台账（任务记录、INDEX/COVERAGE），只放任务记录 |

## 快照与增量同步策略

1. **初始快照**：2026-11-26，`modelfw_demo@22dfa74`，按白名单目录导出。
2. **增量同步**：源仓库相关目录提交后，用同一白名单重新 `git archive` 覆盖/新增，并更新 `MANIFEST.md` 的来源 commit。
3. **只同步已跟踪文件**：未跟踪目录（例如运行中的 `godot-water-shader/`、`godot-sun-moon-shadows/`）需在源仓库提交后再补入。
4. **单向**：本仓库不直接开发；改动请回到 `modelfw_demo`。
5. **历史快照**：可用 tag `snapshot-YYYYMMDD-<short-commit>` 保留各期归档。

## 归档范围

包含：`godot-*`、`blender-*`、`threejs-water-clouds/`、`agent-probes/`、`animation-retarget-kit/`、`craft-cloudride/`、`craft-island/`、`portable-core/`、`docs/`。

不包含：`bench_*`、`bench_results/`、`cpp/`、`ark-examples/`、`product-scout/`、`tools/`、根 `.claude/`、`.github/`、根 `CLAUDE.md`、根 `README.md`、`Makefile`、`pytest.ini`、`benchmark*.py`、`cmodel*.py`、`compare.py`、`demo_batch.py`、`tripo-out/`、`.tripo/`、`.cc-connect/`，以及第三方 IP 模型（T-20261123-002）。

未同步与排除明细见 [MANIFEST.md](MANIFEST.md) 第 4 节。
