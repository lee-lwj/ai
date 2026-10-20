# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 80）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **2924** |
| 本轮净增（相对目录 Batch80dir 合并后基线 2912） | **+12** |
| 本轮因已在 master/targets 跳过 | **1** |
| 本轮质量剔除（死站/错垂/cloak 等） | **9** |
| 其中 high / medium | **2748** / **176** |
| 唯一域名 | **2032** |
| 非 .de 邮箱（累计） | **646** |
| 含电话 / 含城市 | **2580** / **2682** |
| 本轮新域名贡献 | **1** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2696** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 80 · Website/named Kontakt）

1. **基线**：目录 Batch80dir 合并后 **重读 CSV** → **2912 / 2031**，再合并本轮。
2. **Expand 队列**：仍空；wave1 ~55 unprobed tooling singles → 3 promising domains after gate。
3. **Named Kontakt / Web 定向**：
   - Sauer & Sohn Dieburg Formentechnik（info@ + Schultheis GF + Schneider；Lambracht 等页面 404/redirect 本轮不取）
   - Werkzeugbau Berger Salzkotten（Neubert/Haacke GF + Klocke/Berhorst Projekt + J.Berger Konstruktion；Einkauf 剔除）
   - Dressel Kunststofftechnik Selb（Lang/S.Dressel GF + Kiesl Prok. + A.Dressel Vertrieb；Bewerbung 剔除）
   - Schröder+Heidler `info@` → **master skip**（已有 vertrieb@）
4. **质量门**：Einkauf/Bewerbung；doettling.de 现为 Beratung/Mediation（非 Werkzeugbau）；formtechnik-gmbh.de 为 Blech/Umform；Croner/FBB cloak。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| wave1 single-email peers | ~55 | **+9**（Berger+Dressel） |
| named Web（Sauer/Schröder/Formtechnik） | 多页 | **+3** Sauer；Schröder master-skip；Formtechnik 错垂剔除 |

### 本轮新增（+12）

- `info@sauerundsohn.de` · Dieburg ·   · high
- `b.schultheis@sauerundsohn.de` · Dieburg · Benjamin Schultheis · high
- `r.schneider@sauerundsohn.de` · Dieburg · Ralph Schneider · high
- `m.neubert@wzb-berger.de` · Salzkotten-Scharmede · Michael Neubert · high
- `m.haacke@wzb-berger.de` · Salzkotten-Scharmede · Marius Haacke · high
- `n.klocke@wzb-berger.de` · Salzkotten-Scharmede · Norbert Klocke · high
- `f.berhorst@wzb-berger.de` · Salzkotten-Scharmede · Florian Berhorst · high
- `j.berger@wzb-berger.de` · Salzkotten-Scharmede · Jens Berger · high
- `d.lang@dressel-kt.de` · Selb · Daniel Lang · high
- `s.dressel@dressel-kt.de` · Selb · Susanne Dressel · high
- `t.kiesl@dressel-kt.de` · Selb · Tina Kiesl · high
- `a.dressel@dressel-kt.de` · Selb · Annette Dressel · high

### 本轮新域名

- `sauerundsohn.de`

### skipped-already-known（1）

`info@schroeder-heidler.de`

### 质量剔除（节选）

**9**：Berger Einkauf；Dressel Bewerbung；doettling Beratung（非 Werkzeugbau）；formtechnik-gmbh Blech/Umform；Sauer Formenbau named 页面不可达；Croner/FBB cloak…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch80_new_verified.json`
- `data/germany_raw/batch80_expand_results.json`
- `data/germany_raw/batch80_merge_log.json`
- `data/germany_raw/batch80_candidates.json` / `batch80_probe_wave1.json`
- `data/germany_raw/batch80_quality_drops.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B81：empty expand）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空。B81 继续 named Kontakt；cloak 观察；Sauer Formenbau named 若页面恢复可补；doettling.de 域名需复核（现站非 Werkzeugbau）。


---

## 目录/展会轨 Batch80dir

> 合并前重读 CSV（Website B79 后基线 **2824** / **1950**）。合并后基线供 Website B80：**2912** / **2031**。

### 累计（Batch80dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2912** |
| 唯一域名 | **2031** |
| 本轨净增（相对 2824） | **+88** |

### 本轨要点

见 `data/germany_raw/batch80dir_merge_log.json` / `batch80dir_hits.json`。

### 状态

Batch80dir 已合并；Website Batch 80 在其上再合并 **+12** → 累计 **2924 / 2032**。

---

## 目录/展会轨 Batch79dir

> 合并前重读 CSV；合并后基线供 Website B79：**2808** / **1948**。

### 累计（Batch79dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2808** |
| 唯一域名 | **1948** |

### 本轨要点

见 `data/germany_raw/batch79dir_merge_log.json` / `batch79dir_hits.json`。

### 状态

Batch79dir 已合并；Website Batch 79 在其上再合并 **+16** → 累计 **2824 / 1950**。

---

## 目录/展会轨 Batch78dir

> 续跑队列 ~123；合并前重读 CSV（Website B77 后基线 **2612** / **1793** 域名）。合并后基线供 Website B78：**2706** / **1867**。

### 累计（Batch78dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2706** |
| high / medium | **2537** / **169** |
| 唯一域名 | **1867** |
| 含电话 / 含城市 | **2401** / **2495** |
| 非 .de 邮箱 | **586** |

### 按 icp_tag（Batch78dir 合并后）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2478** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch78dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **123** |
| 有邮箱命中 | **76** |
| 本轨净增邮箱 | **94**（high **84** / medium **10**） |
| 相对 Website B77 基线 2612 | **+94** |
| WLW 再播种候选（p21–28 + 扩类） | **111** |
| 队列剩余 | **110** |

### 方法

1. 排空上轮 123 域名队列 → Impressum/Kontakt  
2. append-dedupe 入库（与 Website 轨并行，合并前重读）  
3. WLW formenbau/spritzguss/werkzeugbau/kunststofftechnik 等 **p21–28** 再播种

### 本轨新增邮箱（节选前 25 / 共 94）

- `info@alexander-magnettechnik.de`
- `info@agathon.ch`
- `info@cnc-dreherei.de`
- `t.allenstein@cnc-dreherei.de`
- `r.allenstein@cnc-dreherei.de`
- `k.allenstein@cnc-dreherei.de`
- `a.bettermann@cnc-dreherei.de`
- `n.hardt@cnc-dreherei.de`
- `office@alu-future.com`
- `info@alumina.systems`
- `info@ama-maschinen.de`
- `info@abp-blech.de`
- `info@alptec.de`
- `info@aaubry.ch`
- `info@amsler-frey.ch`
- `office@aewwzb.at`
- `office@wiba.co.at`
- `info@federn-weigel.de`
- `info@normdreh.de`
- `vertrieb@addiprint3d.de`
- `technik@addiprint3d.de`
- `vertrieb@asp-germany.de`
- `info@adkom.de`
- `info@aw-color.de`
- `info@bedra.com`
… 另有 69 个，见 `data/germany_raw/batch78dir_hits.json`

### 本轨新域名（节选）

`aaubry.ch`, `abp-blech.de`, `addiprint3d.de`, `adkom.de`, `adnandogangroup.com`, `aewwzb.at`, `agathon.ch`, `alexander-magnettechnik.de`, `alkaz.pl`, `allenstein-cnc-dreherei.de`, `alptec.de`, `alu-future.com`, `alumina.systems`, `ama-maschinen.de`, `amsler-frey.ch`, `asd-bochum.de`, `asp-germany.de`, `atcweb.at`, `atositalia.com`, `aundl-kunststoff.de`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch78dir_impressum.json`
- `data/germany_raw/batch78dir_verified.json` / `batch78dir_hits.json`
- `data/germany_raw/batch78dir_merge_log.json` / `batch78dir_reseed.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**110**）

### 状态

Batch78dir 完成：**+94** 邮箱；队列 **110** 待 Batch79dir。Website Batch 78 已在其上再合并 **+14** → 累计 **2720 / 1872**。


---


---

## 目录/展会轨 Batch80dir

> 续跑队列 ~118；合并前重读 CSV（Website B79 后基线 **2824** / **1950** 域名）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2912** |
| high / medium | **2736** / **176** |
| 唯一域名 | **2031** |
| 含电话 / 含城市 | **2568** / **2670** |
| 非 .de 邮箱 | **646** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2684** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch80dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **118** |
| 有邮箱命中 | **87** |
| 本轨净增邮箱 | **88**（high **84** / medium **4**） |
| 相对 Website B79 基线 2824 | **+88** |
| WLW 再播种（p37–44 + 扩类） | **119** |
| 队列剩余 | **119** |

### 方法

1. 排空上轮 118 域名 → Impressum/Kontakt  
2. append-dedupe（Website B79 并行后重读 CSV）  
3. WLW p37–44 + kunststoffverarbeitung 等再播种

### 本轨新增邮箱（节选前 25 / 共 88）

- `info@3d-profi-druck.de`
- `office@alu-tech-trade.at`
- `info@2b-klebebaender.de`
- `info@alpaco-lueck.de`
- `wagner@beck-federn.de`
- `info@amb-germany.de`
- `info@all-in-optics.de`
- `info@3ddesign24.de`
- `info@mueller-ohlenrode.de`
- `info@atr-solutions.de`
- `ettingshausen@subtil-group.com`
- `info@buerojetzt.de`
- `info@buntenbach-cnc.de`
- `info@aps-techgroup.de`
- `mail@andreasweisegmbh.de`
- `c.weise@andreasweisegmbh.de`
- `office@modellbau-richter.at`
- `mail@bb-plastpack.de`
- `info@bb-plastpack.de`
- `info@ayhan-online.de`
- `info@asti-filter.de`
- `info@atka.de`
- `info@bohl.biz`
- `info@altenis.de`
- `info@almetec.de`
… 另有 63 个，见 `data/germany_raw/batch80dir_hits.json`

### 本轨新域名（节选）

`2b-klebebaender.de`, `3d-profi-druck.de`, `3ddesign24.de`, `3pcorporate.com`, `aet-kunststoffe.de`, `all-in-optics.de`, `almetec.de`, `alpaco-lueck.de`, `altenis.de`, `alu-tech-trade.com`, `amb-germany.de`, `andreasweisegmbh.de`, `aps-techgroup.de`, `asti-filter.de`, `atka.de`, `atr-solutions.de`, `aupperle-gmbh.de`, `ayhan-online.de`, `bb-plastpack.de`, `beck-federn.de`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch80dir_impressum.json`
- `data/germany_raw/batch80dir_verified.json` / `batch80dir_hits.json`
- `data/germany_raw/batch80dir_merge_log.json` / `batch80dir_reseed.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**119**）

### 状态

Batch80dir 完成：**+88** 邮箱；队列 **119** 待下一批。


---

## 目录/展会轨 Batch81dir

> 续跑队列 ~119；合并前重读 CSV（Website B80 后基线 **2924** / **2032** 域名）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3022** |
| high / medium | **2834** / **188** |
| 唯一域名 | **2117** |
| 含电话 / 含城市 | **2656** / **2765** |
| 非 .de 邮箱 | **686** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2794** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch81dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **119** |
| 有邮箱命中 | **91** |
| 本轨净增邮箱 | **98**（high **86** / medium **12**） |
| 相对 Website B80 基线 2924 | **+98** |
| 再播种（VDWF 会员站） | **330** |
| 队列剩余 | **328** |

### 方法与 blockers

1. 排空上轮 119 域名 → Impressum/Kontakt  
2. append-dedupe（Website B80 并行后重读 CSV）  
3. **WLW p45+ 详情页 CAPTCHA（Human Verification）**— 无法再取 sameAs  
4. 改用 **VDWF Mitglieder** 公开会员页解析官网 → **330** 新域名入队

### 本轨新增邮箱（节选前 25 / 共 98）

- `kontakt@aim3d.de`
- `info@3d-metall-theobald.de`
- `info@boho-moebel.de`
- `info@appinger-ks.de`
- `info@3dmarkt.shop`
- `info@am-gebhart.de`
- `info@adelmann.net`
- `info@biodelta.de`
- `info@aquaduna.com`
- `office@astria-sourcing.com`
- `info@breuer-stahlhandel.de`
- `info@berlet-formenbau.de`
- `info@brobeil-maschinenbau.de`
- `info@bws.ag`
- `s.rickli@bws.ag`
- `kontakt@csb-metalsolutions.de`
- `info@braeuersysteme.de`
- `info@desetec.de`
- `info@rahmede.de`
- `info@merki-ag.ch`
- `info@deco-pack.com`
- `ernst@nutricos.at`
- `office@nutricos.at`
- `kontakt@weydemeyer.de`
- `info@klappmoebel.de`
… 另有 73 个，见 `data/germany_raw/batch81dir_hits.json`

### 本轨新域名（节选）

`3d-metall-theobald.de`, `3dmarkt.shop`, `adelmann.net`, `aim3d.de`, `am-gebhart.de`, `appinger-ks.de`, `aquaduna.de`, `astria-sourcing.com`, `avalumitran.com`, `becher-schilder.de`, `berlet-formenbau.de`, `biodelta-privatelabel.de`, `boho-moebel.de`, `braeuersysteme.de`, `breuer-stahlhandel.de`, `brobeil-maschinenbau.de`, `bws.ag`, `cnc-praniess.at`, `csb-metalsolutions.de`, `de.halfar.com`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch81dir_impressum.json`
- `data/germany_raw/batch81dir_verified.json` / `batch81dir_hits.json`
- `data/germany_raw/batch81dir_merge_log.json` / `batch81dir_reseed.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**328**）

### 状态

Batch81dir 完成：**+98** 邮箱；队列 **328**（VDWF 再播种，ICP 优先）待下一批。
