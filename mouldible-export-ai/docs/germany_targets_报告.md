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


---

## 目录/展会轨 Batch76dir

> 续跑 `queue_directory_domains_remaining.txt`（352）；合并前重读 CSV（Website Batch76 后基线 **2168**）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2519** |
| high / medium | **2360** / **159** |
| 唯一域名 | **1738** |
| 含电话 / 含城市 | **2253** / **2348** |
| 非 .de 邮箱 | **522** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2291** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch76dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验域名 | **352**（队列排空） |
| 有邮箱命中 | **260** |
| 本轨净增邮箱 | **351**（high **316** / medium **35**） |
| 相对 Website B76 基线 2168 | **+351** |
| 质量剔除（已知/错垂/垃圾本地部分等） | known+qual（见 merge_log） |
| 队列剩余（已排除已核验+已入库） | **77** |

### 方法

对队列 352 域名并行拉取 `/impressum` `/kontakt` 等路径，仅保留同域或相关域真实 mailto；与 Website Batch76 并行写入后 **re-read CSV → append-dedupe**。

### 本轨新增邮箱（节选前 25 / 共 351）

- `info@gc-heat.de`
- `mail@fliegel.de`
- `robotics@fpt.de`
- `info@fimatech.de`
- `info@fiberflon.com`
- `sales@fiberflon.com`
- `info@ganzelewski.de`
- `info@fg-hachtel.com`
- `info@goettfert.de`
- `info@germantwinscrews.de`
- `info@finke-colors.de`
- `bitterle@fellereng.de`
- `otterbein@fellereng.de`
- `diehl@fellereng.de`
- `order@fellereng.de`
- `schardt@fellereng.de`
- `dotterweich@fellereng.de`
- `sales@fellereng.de`
- `hotline@fellereng.de`
- `info@groche.com`
- `info@fiege-electronic.com`
- `grafe@grafe.com`
- `info@fuchs-umwelttechnik.com`
- `info@hamos.com`
- `info@hanshuonker.de`
… 另有 326 个，见 `data/germany_raw/batch76dir_hits.json`

### 本轨新域名（节选）

`ak-form-reinigung.info`, `ams-systems.com`, `as-plast.at`, `aubryag.ch`, `bernhofer.at`, `biho.eu`, `feddem.com`, `fellereng.de`, `ferrofacta.com`, `fg-hachtel.com`, `fiberflon.com`, `fiege-electronic.com`, `fimatech.de`, `finke-colors.eu`, `fliegel.de`, `fpt.de`, `friedrichshuette.com`, `fuchs-umwelttechnik.com`, `ganzelewski.de`, `gbneuhaus.de`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch76dir_impressum.json`
- `data/germany_raw/batch76dir_verified.json` / `batch76dir_hits.json`
- `data/germany_raw/batch76dir_merge_log.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**77**）

### 状态

原 352 队列已排空并入库；剩余种子队列 **77**（含 WLW p6–12 再播种）（未核验且未入库）。Formenbau JS 阻断与 Europages CAPTCHA 仍在，续跑可扩 WLW/Fakuma 新页。


---

## 目录/展会轨 Batch77dir

> 续跑 WLW p6–12 再播种队列（77）；合并前重读 CSV（基线 **2519**；Website B77 本轮未抢先写入）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2586** |
| high / medium | **2427** / **159** |
| 唯一域名 | **1791** |
| 含电话 / 含城市 | **2304** / **2402** |
| 非 .de 邮箱 | **543** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2358** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch77dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **77** |
| 有邮箱命中 | **59** |
| 本轨净增邮箱 | **67**（全部 high） |
| 相对基线 2519 | **+67** |
| 再播种新域名（WLW p13–20 + KW 详情） | **123** |
| 队列剩余 | **123** |

### 方法与 blockers

1. 队列 77 域名 Impressum/Kontakt 核验 → email-unique merge  
2. 排空后扩种：WLW formenbau/spritzguss/werkzeugbau **p13–20**（firm `sameAs`）+ KunststoffWeb 详情页  
3. **Gelbe Seiten**：静态 HTML 无 website/mailto（consent/JS）— blocker  
4. **KW Formenbau p100362** 仍空列表；3 域名连接失败（alform.de / bornemann.de / lanolin.de）

### 本轨新增邮箱（节选前 25 / 共 67）

- `office@threedreamz.com`
- `info@leibe.eu`
- `info@bechtold-sohn.com`
- `info@alstertaler.de`
- `fj@alstertaler.de`
- `info@startech24.de`
- `info@3dock.de`
- `info@mve-bahl.de`
- `info@apppex.com`
- `velisa.pantic@aartech.ch`
- `finance@aartech.ch`
- `dragan.filipovic@aartech.ch`
- `hr@aartech.ch`
- `info@abk-pressenbau.de`
- `schwarz@schwarz-stuttgart.de`
- `feinguss@buerstlein-guss.de`
- `anfragen@buerstlein-guss.de`
- `info@carlfroh.net`
- `info@geyerwerkzeugbau.de`
- `info@cam4solid.de`
- `info@braunmetall.de`
- `info@bintek.ch`
- `info@3ddrucklife.de`
- `info@martanplastics.com`
- `info@cb-feinmechanik.de`
… 另有 42 个，见 `data/germany_raw/batch77dir_hits.json`

### 本轨新域名（节选）

`3d-druck-amann.de`, `3ddrucklife.de`, `3dock.de`, `3dprintpoint.de`, `aartech.ch`, `abk-pressenbau.de`, `ahwzb.de`, `alstertaler.de`, `apppex.com`, `bechtold-sohn.com`, `benkon.de`, `bintek.ch`, `braunmetall.de`, `buerstlein-guss.de`, `cam4solid.de`, `carlfroh.net`, `carlpabst.de`, `cast-tec.de`, `cb-feinmechanik.de`, `cleveland.de`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch77dir_impressum.json`
- `data/germany_raw/batch77dir_verified.json` / `batch77dir_hits.json`
- `data/germany_raw/batch77dir_merge_log.json` / `batch77dir_reseed.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**123**）

### 状态

Batch77dir 完成：**+67** 邮箱；队列再播种至 **123** 待 Batch78dir。
