# ExclusionForge

> **Forge the exclusions.** — The in-house mod foundry of Exclusion Protocol.
> Every mod is an independent citizen: its own identity, license, and release cadence.

Sister repo: **[Exclusion-Protocol](../Exclusion-Protocol)** (the modpack)

---

## Family Constitution (the Module Sovereignty Doctrine)

Every mod forged in this repository is a **fully independent citizen**:

- **Independent modId** — no identifier shared with any other mod
- **Independent package** — Java package paths fully separate; detachable with zero residue
- **Independent asset paths** — assets/data namespaces belong to no one else
- **Independent creative tab** — in-game presentation belongs to each mod itself
- **Independent distribution file** — jar filename mirrors the modpack distribution name, preventing update confusion

No mixed payloads: one jar never carries economy + medicine. Module ownership is decided at project inception, never defaulted into the current workspace.

> The constitution was decreed by the Creator (2026-11-07); this section is its transcription.

## Mod family

| Mod | modId | Current | Positioning |
|-----|-------|---------|-------------|
| **ExclusionEconomy** (black-market economy) | `exclusioneconomy` | 0.2.0 | Physical-currency economy: black-market terminal blocks + five-tier placeholder prices (final values await the economy design doc) |
| **StaminaSurge** (stamina surge) | `staminasurge` | 0.4.7 | Stamina system patch: MobEffect-pool driven + dedicated HUD feedback, referencing the Tarkov injector family |

> Naming protocol: the Creator decrees the Chinese name; the engineering side coins the English one (quality register + reference-system fit).

## Build chain

Build artifacts flow straight into the modpack repo's `overrides/mods/`.

<!-- [Build details — pending: gradle config, artifact hashes, packaging pipeline] -->

## License

All original code and content in this repository is **All Rights Reserved** — matching the license field in the jars' `mods.toml`.

**The author is maskday (GitHub: Shy).** The jars' `authors` fields credit maskday and Mask (engineering collaboration) — both refer to the same author as this account.

---

# ExclusionForge（中文版）

> **Forge the exclusions.** —— Exclusion Protocol 的自研模组铸造厂。
> 每个模组都是独立公民：完全独立的身份、许可与发布节奏。

姊妹仓库：**[Exclusion-Protocol](../Exclusion-Protocol)**（整合包主仓）

---

## 家族宪法（模块主权宣言）

本仓铸造的每一个模组都是**完全独立的公民**：

- **modId 独立** —— 不与任何其他模组共享标识符
- **包名独立** —— Java 包路径各自独立，零残留拆装
- **资源路径独立** —— assets/data 命名空间互不隶属
- **创造栏独立** —— 游戏内呈现各自归属
- **分发文件独立** —— jar 文件名与整合包分发名同名同步，防更新混淆

功能不混装：一个 jar 不塞经济+医疗。归属模块在立项时先问，不默认塞进当前工程。

> 宪法原文由创造者颁布（2026-11-07），本节为其落文本。

## 模组家族

| 模组 | modId | 当前版本 | 定位 |
|------|-------|----------|------|
| **ExclusionEconomy**（黑市经济） | `exclusioneconomy` | 0.2.0 | 实物货币制经济：黑市终端方块 + 五档占位价（终版数值待经济设计文档） |
| **StaminaSurge**（体力涌泉） | `staminasurge` | 0.4.7 | 体力系统补丁：MobEffect 池驱动 + HUD 专属反馈，参照塔科夫针剂族 |

> 命名协议：创造者拍中文名，工程侧起英文名（品质感 + 贴参照系气质）。

## 构建链

构建产物直接进入整合包主仓 `overrides/mods/`。

<!-- [构建细节 · 待补：gradle 配置、产物哈希、入包管线] -->

## 许可

本仓库所有原创代码与内容 **保留所有权利（All Rights Reserved）**——与 jar 内 `mods.toml` 的 license 声明一致。

**作者 maskday（GitHub 账号 Shy）。** jar 内 authors 字段署名 maskday 与 Mask（工程协作署名），与本账号同属作者。

---

*This forge only casts what the Creator designs. — 人类审美最重要。*
