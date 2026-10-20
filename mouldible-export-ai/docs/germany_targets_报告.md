# 德国 ICP 公开邮箱收获报告（germany_targets）

**范围：** 德国 ICP（Formenbau / Spritzguss / Werkzeugbau / Kunststoff / Thermoform / Modellbau）；不限 .de 邮箱（Impressum/+49/德地址可证即可）。  
**日期：** 2026-10-20（Asia/Hong_Kong）  
**原则：** 只保留公开可核验邮箱；不编造；未发任何邮件；单 worker；增量交付，**未宣称完成**。硬去重 `germany_targets ∪ target_emails_master ∪ enrichment_pilot_20`。邮箱级去重（同公司多联系人保留）。

---

## 1. 累计交付数量（如实，至 Batch 73）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **1881** |
| 本轮净增（相对 Batch 72 的 1870） | **+11** |
| 本轮因已在 master/targets/pilot 跳过 | **40** |
| 本轮质量剔除（死站/错垂/cloak 等） | **12** |
| 其中 high / medium | **1776** / **105** |
| 唯一域名 | **1343** |
| 非 .de 邮箱（累计） | **255** |
| 含电话 / 含城市 | **1647** / **1739** |
| 本轮新域名贡献 | **1** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **1653** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 73）

1. **Expand**：`formenbau-rapp.de` → 403/404，无法同域核验 → **+0**。
2. **目录/named**：zegla Plast named；Thenhausen named（[at]）；Forminplast Metzingen。
3. **质量门**：Haasis Kokillen/Metallguss；Rommel→Haas Metallguss；Finke Stanz；Thenhausen Einkauf/Buchhaltung。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| expand 队列 | 1 | **+0** |
| directory / named Kontakt | 多轮 | **+11** |

### 本轮新增（+11）

- `thomas.weiss@zegla-plast.de` · Schwarzenbach · high
- `florian.walberer@zegla-plast.de` · Schwarzenbach · high
- `wolfgang.ploessner@zegla-plast.de` · Schwarzenbach · high
- `wolfgang-ploessner@zegla-plast.de` · Schwarzenbach · high
- `thenhausen@thenhausen.com` · Leopoldshöhe · high
- `freyer@thenhausen.com` · Leopoldshöhe · high
- `diekmann@thenhausen.com` · Leopoldshöhe · high
- `schau@thenhausen.com` · Leopoldshöhe · high
- `vesic@thenhausen.com` · Leopoldshöhe · high
- `groetsch@thenhausen.com` · Leopoldshöhe · high
- `info@forminplast.de` · Metzingen · high

### 本轮新域名

- `forminplast.de`

### skipped-already-known（40）

`anfragen@sd-formen.de`, `einkauf@triwefo.de`, `info@antech-polymertechnik.de`, `info@bm-formenbau.de`, `info@buck-gmbh.net`, `info@croner-formenbau.de`, `info@dittrich-co.de`, `info@edegs.de`, `info@edegs.de`, `info@formenbau-spritzguss.de`, `info@formenbau-walter.de`, `info@formenbaugreiner.de`, `info@formentechnik-bayreuth.de`, `info@frank-formenbau-spritzguss.de`, `info@haenel-praezision.de`, `info@happ-gmbh.de`, `info@kaspareth.de`, `info@krauss-formenbau.de`, `info@kunststofftechnik-schroeder.de`, `info@lambrecht-vs.de`, `info@muellergmbh-formenbau.de`, `info@opticamms.de`, `info@pfletschinger-gauch.de`, `info@pohl-formenbau.de`, `info@rekuplast.de`…

### 质量剔除（节选）

**12**：Rapp unreachable；Haasis Aluminiumguss；Rommel Metallguss；Finke Stanz；Thenhausen Einkauf/Buchhaltung…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch73_new_verified.json`
- `data/germany_raw/batch73_expand_results.json`
- `data/germany_raw/batch73_merge_log.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B74：croner-formenbau.de）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 已排空；名录/named 仍有空间；B74 继续 directory + `croner-formenbau.de`。
