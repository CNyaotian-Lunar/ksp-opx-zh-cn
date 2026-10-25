# KSP OPX 系列 简体中文补丁

为《坎巴拉太空计划》(KSP) 的 **OPX** 系列行星包提供简体中文本地化，覆盖全部 480 条本地化条目。

**本仓库只包含翻译文本。不包含任何原模组的模型、纹理、代码或配置。使用前请自行安装对应的 OPX 模组。**

A Simplified Chinese localization for the **OPX** series of KSP planet packs, covering all 480 localization entries.

**This repository contains translation text only. It does not include any assets from the original mods. You must install the corresponding OPX modules separately.**

---

## 覆盖范围 / Scope

| 文件 / File | 条目数 / Entries | 对应模组 / Target mod |
|---|---|---|
| `GameData/0001_OPX_CN/OPX-JoolPlus-zh-cn.cfg` | 116 | OPX: Jool Plus |
| `GameData/0001_OPX_CN/OPX-SarnusPlus-zh-cn.cfg` | 88 | OPX: Sarnus Plus |
| `GameData/0001_OPX_CN/OPX-UrlumPlus-zh-cn.cfg` | 122 | OPX: Urlum Plus |
| `GameData/0001_OPX_CN/OPX-NeidonPlus-zh-cn.cfg` | 154 | OPX: Neidon Plus |

包含：天体名称、天体描述、生物群系名称。
Includes: body names, body descriptions, biome names.

---

## 安装 / Installation

1. 确认已安装对应的 OPX 模组（OPX 系列需要 Outer Planets Mod 作为前置）。
2. 将本仓库的 `GameData/0001_OPX_CN/` 目录复制到 KSP 安装目录的 `GameData/` 下。
3. 启动游戏，语言设为简体中文。

```
Kerbal Space Program/
└── GameData/
    ├── OPM/                      (前置 / prerequisite)
    ├── OPX-JoolPlus/             (原模组 / original mod)
    └── 0001_OPX_CN/              (本补丁 / this patch)
        ├── OPX-JoolPlus-zh-cn.cfg
        └── ...
```

1. Make sure the corresponding OPX modules are installed (OPX requires Outer Planets Mod).
2. Copy `GameData/0001_OPX_CN/` into your KSP `GameData/` directory.
3. Launch the game with language set to Simplified Chinese.

本补丁尚未收录进 CKAN，请使用手动安装。CKAN listing is not available yet.

---

## 与 OPM 中文补丁的关系 / Relation to the OPM patch

OPM 本体有单独的汉化补丁，两个补丁互不覆盖，可以同时安装。

The base OPM has a separate Chinese patch. Both patches are independent and can be installed together.

---

## 翻译约定 / Translation conventions

- **天体名称保留英文原文**，不音译：`Meto`、`Alnes`、`Betazed`、`Klip`、`Jimel`、`Riga`、`Maia`、`Karn`、`Colwin`、`Silal`、`Rator`、`Pakran`、`Manaris`、`Annun`、`Spar` 等一律不译。
  Celestial body names stay in English and are never transliterated.
- **生物群系名称音译**，涉及其他作品的梗按对应官方中文译名。
  Biome names are transliterated; references to other works follow their official Chinese names.
- **格式控制符原样保留**：`\n`、`^N`、`<i>`、`</i>`、`<br>`。
  Format control sequences are preserved verbatim.

完整生物群系译名表见 `TERMS-biome-map.json`。
The full biome mapping is in `TERMS-biome-map.json`.

---

## 兼容性 / Compatibility

- 游戏版本 / Game version：KSP 1.12.5
- OPX：Jool Plus 1.0.1 / Sarnus Plus 0.4.3 / Urlum Plus 0.8.0 / Neidon Plus 0.8.6

---

## 已知问题 / Known issues

- 上游新增文本时对应条目回退英文，等待本补丁同步。
- 翻译由 AI 辅助初翻，格式、条目完整性与术语一致性经过程序校验；个别语句可能生硬，欢迎在 issue 报告（请注明 localization key）。
- New upstream strings fall back to English until this patch is updated.
- Translation was produced with AI assistance and machine-verified for format and completeness.

---

## 许可 / License

翻译文本继承 OPX 各包的许可：**MIT**。详见 `LICENSE`。

The translation text inherits the OPX modules' license: **MIT**. See `LICENSE`.

### 致谢 / Credits

- OPX: Jool Plus / Sarnus Plus / Urlum Plus — TheMinmusDerp 及其贡献者
- OPX: Neidon Plus — TheWhistleGang 及其贡献者
- 翻译与校验 — CNyaotian-Lunar

---

## 贡献 / Contributing

发现错误请开 issue，注明 key（形如 `LOC_OPX-JP_Jool_Desc`）。上游更新后同步新条目的 PR 欢迎。
Open an issue for errors with the localization key. PRs syncing new upstream entries are welcome.
