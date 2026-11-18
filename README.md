# sfc-roms

SFC / SNES 游戏库，供 GameEmulator 使用。

目录：`catalog.json`。ROM 位于 `roms/` 目录；`download_url` 相对于 `rom_url_base`，兼容完整 URL。每个条目包含文件名、文件大小、SHA-256、来源仓库和固定版本。

| 平台 | 游戏数 |
|---|---:|
| SFC | 64 |

游戏类别包含经典游戏与自制游戏，语言以目录标签为准。来源及原始下载地址保存在每个条目的 `source_url`、`source_repository`、`source_revision`、`upstream_download_url` 中。去重依据为 ROM 内容的 SHA-256。

## 来源

- [AlexBlackmore/roms](https://github.com/AlexBlackmore/roms/tree/d76e034c11599ea9da7f775bde15a45634798d12)
- [retrobrews/snes-games](https://github.com/retrobrews/snes-games/tree/2329cb432b4cad13aa6a9d2ad0699c771780b378)

游戏、图片、商标等内容的权利属于各自权利人。自制游戏的作者记录在目录的 `developer` 字段；上游的发布和许可说明仍适用。
