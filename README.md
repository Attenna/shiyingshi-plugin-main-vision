# 演播室2 插件：main_vision（主视觉）

主视觉直播场景插件，独立仓库。安装：把本仓库内容放到 `{exe}/mods/main_vision/`。

- 清单：`plugin.json`（`api_version: >=2.0.0 <3.0.0`）；
- 入口：`plugin.gd`；
- 场景：`scenes/main_vision.tscn`。

## CI

`.github/workflows/smoke.yml` 在 `core` 的 `main` 与 `core-v2.0.0` 两个 ref 上各跑一次冒烟：
把本仓库复制进 core 的 `plugins/main_vision`，无头启动并断言
`[PluginManager] 插件已加载并启用: main_vision`。

## 版本

`v1.0.0` 为拆分后的首个插件版本，供 `shiyingshi-dist` 的 manifest 固定引用。
