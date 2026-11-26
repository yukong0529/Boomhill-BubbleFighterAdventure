<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 泡泡战士：冒险（BubbleFighter Adventure）

一款手机平台上的动作游戏。

> **警告：仅限获准参加 Lab Track 的创作者使用。** 未经批准的使用一律禁止，不因其属于内部制作、学习、研究、个人学习或商业用途而例外。

> 使用条件以仓库根目录中的 [LICENSE](LICENSE) 和 [NOTICE](NOTICE) 为准。查看器：[在查看器中浏览本游戏](https://nexon-replay.github.io/Boomhill/#/g/bubblefighter-adventure)。其他游戏请访问[资源中心](https://nexon-replay.github.io/Boomhill/)。

## 目录

| 目录 | 内容 |
|---|---|
| `2d/` | 2D 图像，按资源包分别存放；图像为 PNG，多帧图像使用精灵图集，并附有图集 JSON |
| `3d/` | 3D 预览模型，按类别分别存放；每个模型包含 `<id>.glb` 模型、`<id>.webp` 缩略图和 `<id>.json` 附加信息 |
| `3d/_shared/` | 多个模型共用的纹理、表情图和组装部件（文件名为原始名称_短哈希） |
| `2d/manifest.json`、`3d/manifest.json` | 记录每个文件的大小和 SHA-256 |

## 2D 图像

| 资源包 | 内容 | 图像数 | 帧数 |
|---|---|---:|---:|
| `010_ui` | UI | 312 | 312 |
| `020_item` | 道具、武器图标 | 143 | 143 |
| `030_map` | 地图、背景 | 54 | 54 |
| `040_fx` | 特效纹理 | 119 | 119 |
| `050_texture` | 角色、地图、武器纹理 | 81 | 81 |
| | 合计 | 709 | 709 |

## 3D 预览模型

这些模型可直接在浏览器中预览（压缩后的 GLB、纹理最长边为 512 px，角色仅包含基础动作）。如需用于游戏制作或编辑，请使用下方的原始 ZIP 文件。

| 目录 | 类别 | 模型数 |
|---|---|---:|
| `3d/010_character/` | 角色 | 47 |
| `3d/020_weapon/` | 武器、道具 | 45 |
| `3d/030_map/` | 地图 | 16 |
| `3d/040_anim/` | 动画 | 492 |
| | 合计 | 600 |

## 3D 原始 ZIP

原始文件按类别打包，包含未压缩的 GLB、原始分辨率的 PNG 纹理和完整动作。请从仓库的 Releases 下载。

| 类别 | 文件 | 大小 | 模型数 |
|---|---|---:|---:|
| 全部资源 | [bubblefighter-adventure-3d-all.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighterAdventure/releases/download/3d-originals-v1/bubblefighter-adventure-3d-all.zip) | 18.8 MB | 629 |

文件格式见[资源中心仓库的 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md)，使用方法见[资料指南](https://nexon-replay.github.io/Boomhill/guide.html)。
