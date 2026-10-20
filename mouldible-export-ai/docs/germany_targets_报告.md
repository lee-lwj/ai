# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 76）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **2168** |
| 本轮净增（相对目录合并后基线 2153） | **+15** |
| 本轮因已在 master/targets 跳过 | **76** |
| 本轮质量剔除（死站/错垂/cloak 等） | **12** |
| 其中 high / medium | **2044** / **124** |
| 唯一域名 | **1512** |
| 非 .de 邮箱（累计） | **330** |
| 含电话 / 含城市 | **1907** / **2001** |
| 本轮新域名贡献 | **4** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **1940** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 76）

1. **基线**：开工时 B75 为 1934；目录 sibling 合并后 **重读 CSV** → **2153 / 1508**，再合并本轮。
2. **Expand 队列**：仍空 → **+0**。
3. **Named Kontakt / Ansprechpartner**（website track）：
   - Josef Weischer（Emsdetten）Werkzeugbau 页：info@ / vertrieb@ / entwicklung@
   - Gebr. Kieninger：Martin / Dominik（homepage Kontakt）
   - Formenbau Althaus：info@ + Rath / Stremmel / Otto
   - Vorbach Kaufbeuren：info@ + Neuhorn / Kees / Bergmann / Haindl（dot/at 现场解混淆）
   - Klomfass Heiligenhaus：sprenaj@（info@ 在 master 已跳过）
4. **质量门**：Rausch Buchhaltung/Einkauf；Hanfland 域名停放；Kieninger Versand/Buchhaltung；Althaus Buchhaltung；Vorbach Finanzen/Personal；WIBRA Verwaltung；Tillmann 非 Spritz ICP；ABAS/Hack cloak。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| expand 队列 | 0 | **+0** |
| named Kontakt / Impressum | 多轮 peer + 搜索命中 | **+15** |

### 本轮新增（+15）

- `info@weischer.de` · Emsdetten · Stephan Weischer · high
- `vertrieb@weischer.de` · Emsdetten · Uwe Teepe / Finn Weischer / Simon Kaiser / Kai Wüller · high
- `entwicklung@weischer.de` · Emsdetten · Rupert Hune · high
- `martin.kieninger@gebrueder-kieninger.de` · St. Georgen · Martin Kieninger · high
- `dominik.kieninger@gebrueder-kieninger.de` · St. Georgen · Dominik Kieninger · high
- `info@formenbau-althaus.de` · Erndtebrück ·  · high
- `i.rath@formenbau-althaus.de` · Erndtebrück · Ingo Rath · high
- `d.stremmel@formenbau-althaus.de` · Erndtebrück · Dennis Stremmel · high
- `m.otto@formenbau-althaus.de` · Erndtebrück · Mathias Otto · high
- `info@vorbach-formenbau.de` · Kaufbeuren ·  · high
- `stefan.neuhorn@vorbach-formenbau.de` · Kaufbeuren · Stefan Neuhorn · high
- `florian.kees@vorbach-formenbau.de` · Kaufbeuren · Florian Kees · high
- `andreas.bergmann@vorbach-formenbau.de` · Kaufbeuren · Andreas Bergmann · high
- `klemens.haindl@vorbach-formenbau.de` · Kaufbeuren · Klemens Haindl · high
- `sprenaj@formenbau-klomfass.de` · Heiligenhaus · Shtjefen Prenaj · high

### 本轮新域名

- `formenbau-althaus.de`
- `formenbau-klomfass.de`
- `vorbach-formenbau.de`
- `weischer.de`

### skipped-already-known（76）

`a.marx@rausch-formenbau.de`, `d.scheumann@wibra-formenbau.de`, `entwicklung@weischer.de`, `info@ak-kunststoffspritzguss.com`, `info@antech-polymertechnik.de`, `info@buck-gmbh.net`, `info@dittrich-co.de`, `info@edegs.de`, `info@fb-knott.de`, `info@formenbau-klomfass.de`, `info@gde-werkzeuge.de`, `info@gebrueder-kieninger.de`, `info@gissler-formenbau.de`, `info@gk-formenbau.de`, `info@grauer-formenbau.com`, `info@guentner-formenbau.de`, `info@haenel-praezision.de`, `info@happ-gmbh.de`, `info@jochum-formenbau.de`, `info@jung-formenbau.de` … (+56 more)

### 质量剔除（节选）

**12**：Rausch Buchhaltung/Einkauf；Hanfland parking；Kieninger Versand/Buchhaltung；Althaus Buchhaltung；Vorbach Personal；WIBRA Verwaltung；Tillmann Profil；cloak…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch76_new_verified.json`
- `data/germany_raw/batch76_expand_results.json`
- `data/germany_raw/batch76_merge_log.json`
- `data/germany_raw/batch76_probe_wave1.json` / `batch76_probe_wave2.json` / `batch76_probe_master_seed.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B77：empty expand — named + master-seed）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；named Kontakt 与 master-seed Impressum 核验仍有空间。B77 继续 website/named track（ABAS/Hack cloak 观察；RFK 有名无邮箱；剩余 single-email peers）。
