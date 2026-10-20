## 目录/展会轨 Batch91dir

> 合并前重读 CSV（Website B92 后基线 **3654** / **2506**）。合并后基线供 Website B93：**3657** / **2509**。

### 累计（Batch91dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3657** |
| high / medium | **3418** / **239** |
| 唯一域名 | **2509** |
| 含电话 / 含城市 | **3174** / **3281** |
| 非 .de 邮箱 | **971** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3422** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch91dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **120** |
| 有邮箱命中 | **16** |
| 本轨净增邮箱 | **3**（high **2** / medium **1**） |
| 相对 Website B92 基线 3654 | **+3** |
| 再播种剩余 | **85** |
| 队列剩余 | **85** |

### 本轮队列来源构成

| 来源 | 数量 |
|---|---:|
| fakuma | **1** |
| master_strong_icp | **1** |
| broader_master | **118** |

### 方法

1. 尝试再播种：vdwf_data_www, fakuma_lists, europages_cache, kunststoffweb_cleaned, master_strong_icp（多数已核验过，仅补入 **2** 个新 ICP 候选）  
2. 排空 **120** 域名（118 broader master + 2 ICP）→ Impressum/Kontakt  
3. append-dedupe（合并前重读 **3654/2506** = Website B92）  
4. WLW 跳过（CAPTCHA）

### 本轨新增邮箱（共 3）

- `info@speth-zerspanung.de`
- `info@giemotec.de`
- `info@gizeh.com`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- Fakuma/VDWF/Europages 缓存 / KunststoffWeb 清理后几乎无新域名（已在 B75–B90 耗尽）
- broader master 继续收益递减
- 见 `data/germany_raw/batch91dir_merge_log.json` / `batch91dir_hits.json`

### 产物

- `data/germany_raw/batch91dir_impressum.json`
- `data/germany_raw/batch91dir_verified.json` / `batch91dir_hits.json`
- `data/germany_raw/batch91dir_merge_log.json` / `batch91dir_reseed.json`

### 状态

Batch91dir 已合并；队列剩余 **85** 供 Batch92dir。

---

## 目录/展会轨 Batch90dir

> 合并前重读 CSV（Website B91 后基线 **3645** / **2504**）。合并后基线供 Website B92：**3646** / **2505**。

### 累计（Batch90dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3646** |
| high / medium | **3408** / **238** |
| 唯一域名 | **2505** |
| 含电话 / 含城市 | **3165** / **3270** |
| 非 .de 邮箱 | **969** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3411** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch90dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **120** |
| 有邮箱命中 | **11** |
| 本轨净增邮箱 | **1**（high **1** / medium **0**） |
| 相对 Website B91 基线 3645 | **+1** |
| 再播种剩余 | **120** |
| 队列剩余 | **120** |

### 方法

1. 排空上轮 **120** 个 broader master `.de/.at/.ch` → Impressum/Kontakt  
2. append-dedupe（合并前重读 **3645/2504** = Website B91）  
3. 命中率极低（多数 no_email / off-domain）；仅 **+1** 入库  
4. 续播种 broader master → 队列 **120**；WLW 跳过

### 本轨新增邮箱（共 1）

- `contact@iveyfrank.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- broader master 收益递减；建议下轮改非-WLW 目录/展会源或 OEM 定向
- 见 `data/germany_raw/batch90dir_merge_log.json` / `batch90dir_hits.json`

### 产物

- `data/germany_raw/batch90dir_impressum.json`
- `data/germany_raw/batch90dir_verified.json` / `batch90dir_hits.json`
- `data/germany_raw/batch90dir_merge_log.json` / `batch90dir_reseed.json`

### 状态

Batch90dir 已合并；队列剩余 **120** 供 Batch91dir。

---

## Website/named Kontakt Batch 92

> 合并前重读 CSV（目录 Batch90dir 后基线 **3646** / **2505**）。Batch91dir 合并时未出现。

### 累计（Batch 92 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3654** |
| high / medium | **3416** / **238** |
| 唯一域名 | **2506** |
| 含电话 / 含城市 | **3172** / **3278** |
| 非 .de 邮箱 | **970** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3419** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch 92）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+8**（high **8** / medium **0**） |
| 相对 Batch90dir 基线 3646/2505 | **+8** / **+1** 域名 |
| master 可选跳过 | **3** |
| 质量剔除 | **15** |

### 方法

1. 重读 CSV 确认 Batch90dir 后 **3646/2505**；Batch91dir 未到
2. Expand 空；DE tooling singles 耗尽 → thin multi named Kontakt + Web 定向
3. 命中：Pakulla Vertriebsleitung Guido Rieder；Eitner anfragen@；**Wiegelmann** 新域名 info@+vertrieb@；Servomold GF tmeister@；SUK Schwerin info@/verkauf@/qs@
4. 质量门：Sauer 旧索引 invent；cloak FBB/Croner；Assistentin/Einkauf/Versand/Verwaltung/Logistik；master 可选跳过 Schroeder/Moellering/Stolz-Seng

### 本轨新增邮箱（共 8）

- `guido.rieder@pakulla.de` · Bergisch Gladbach · Guido Rieder · Vertriebsleitung · high
- `anfragen@u-eitner.de` · Dieburg · high
- `info@wiegelmann-gmbh.de` · Olsberg · **新域名** · high
- `vertrieb@wiegelmann-gmbh.de` · Olsberg · **新域名** · high
- `tmeister@servomold.com` · Erbach · Thomas Meister · GF · high
- `info@suk-schwerin.de` · Schwerin · high
- `verkauf@suk-schwerin.de` · Schwerin · high
- `qs@suk-schwerin.de` · Schwerin · high

### 阻塞 / 备注

- Sauer Formenbau 页面已改版至 sauer-praezision；搜索索引中的 Lambracht/Kunkel/Reeh 等不可再核验 → 不 invent
- FBB/Croner 仍 cloak；Roth/Hugo Stiehl 仅共享 vertrieb@/anfrage@
- 见 `data/germany_raw/batch92_*.json` / `batch93_queue_note.txt`

### 产物

- `data/germany_raw/batch92_new_verified.json` / `batch92_candidates_final.json`
- `data/germany_raw/batch92_quality_drops.json` / `batch92_merge_log.json`
- `data/germany_raw/batch93_queue_note.txt`

### 状态

Batch 92 已合并；下轮 Batch 93（Website）/ Batch91dir（目录）。

---

# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 92）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **3654** |
| 本轮净增（相对目录 Batch90dir 合并后基线 3646） | **+8** |
| 本轮因已在 master/targets 跳过 | **3** |
| 本轮质量剔除（死站/错垂/cloak 等） | **15** |
| 其中 high / medium | **3416** / **238** |
| 唯一域名 | **2506** |
| 非 .de 邮箱（累计） | **970** |
| 含电话 / 含城市 | **3172** / **3278** |
| 本轮新域名贡献 | **1**（wiegelmann-gmbh.de） |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3419** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 上轮方法（Batch 91 · Website/named Kontakt）

1. **基线**：目录 Batch89dir 合并后 **重读 CSV** → **3635 / 2504**（非用户提示的 3620）。
2. **Expand**：仍空；DE tooling singles 耗尽。
3. **Named Kontakt / Web 定向**：
   - hesco Kunststoffverarbeitung Luckenwalde（GF×2 + Vertrieb + QM + Produktion + PM/Konstruktion；Einkauf/Personal 剔除）
   - KE-Technik Mönchweiler（Technische GF Helms + Leitung Vertrieb Kaiser）
   - Lammers Formenbau `marek.kolodziej@`（DE peer 波兰办事处，同域 .de）
4. **质量门**：hesco Einkauf/Personal；Kindtner Rechnungswesen；Jantsch Personal；HPF Sekretariat；EHRWA Europages-only；Fus invent info@；cloak/third-party。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| thin multi peer probe | ~17 URLs | 低产（已入库） |
| named Web（hesco/KE/Lammers/WPK/…） | 多页 | **+10** |

### 本轮新增（+10）

- `marek.kolodziej@lammers-formenbau.de` · Haren-Erika / Tarnów · Marek Kołodziej · high
- `felix.reiche@hesco.de` · Luckenwalde · Dr. Felix Reiche · high
- `klaus.reiche@hesco.de` · Luckenwalde · Klaus Reiche · high
- `yuliia.dubinchuk@hesco.de` · Luckenwalde · Yuliia Dubinchuk · high
- `manuel.mommert@hesco.de` · Luckenwalde · Manuel Mommert · high
- `detlef.grove@hesco.de` · Luckenwalde · Detlef Grove · high
- `oliver.ast@hesco.de` · Luckenwalde · Oliver Ast · high
- `marcel.boche@hesco.de` · Luckenwalde · Marcel Boche · high
- `harald.helms@ke-technik.de` · Mönchweiler · Harald Helms · high
- `siegfried.kaiser@ke-technik.de` · Mönchweiler · Siegfried Kaiser · high

### 本轮质量剔除（摘要）

- jana.schneider@hesco.de: DROP Einkauf/Buchhaltung/Personal
- rechnungswesen@kindtner.de: DROP Rechnungswesen
- personal@jantsch.de: DROP Personal/Verwaltung
- nadine.reichelt@ / kathrin.friedrich@fus-werkzeugbau.de: DROP Sekretariat
- bruno.ehrhardt / joachim.danner EHRWA: DROP — only on Europages third-party; company Kontakt shows info@ only
- info@fus-werkzeugbau.de: DROP invent — Impressum shows mail@ only (already known)
- Gollmer kontakt page third-party sales@ emails: DROP third-party-only
- Croner/FBB cloak named: DROP never invent
- Andreas Weise Blechumform: DROP Stanz/Umform vertical

---

## 3. 下轮（Batch 93）提示

Expand empty; DE tooling singles exhausted. Prefer named Kontakt on remaining thin multi-email Spritzguss/Formenbau peers (Ganser/Nelles/Saur/Heim/Rausch/Härer/Battenberger already thin). Watch Batch91dir. Avoid Stanz/Umform, Assistentin/Buchhaltung/Einkauf/Personal/Verwaltung/Versand/Sekretariat, Europages-only invent, cloak invent, Sauer stale-search invent.

---

_报告更新：2026-10-21 01:56 Asia/Hong_Kong_
