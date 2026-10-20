## Website/named Kontakt Batch 99

> 合并前重读 CSV（Batch97dir 后基线 **3809** / **2589**；非 steering 初值 3779/2561。Batch98dir 未写入）。

### 累计（Batch 99 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3816** |
| high / medium | **3571** / **245** |
| 唯一域名 | **2591** |
| 含电话 / 含城市 | **3293** / **3368** |
| 非 .de 邮箱 | **1062** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3572** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **33** |

### 本轨成果（Batch 99）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+7**（high **7** / medium **0**） |
| 相对基线 3809/2589 | **+7** / **+2** 域名 |
| master 可选重叠跳过 | **4** |
| 质量剔除 | **10** |

### 方法

1. 重读确认 **3809/2589**（Batch97dir 已合并；Batch98dir 空）
2. Thin multi named Kontakt（Giebeler×4、WFK Steinbrück）+ NEW-domain Spritzgießformenbau
3. 命中：**Martin Müller Formenbau** / **Schmidtke ohG** 新域名；**martin@wfk**；**Giebeler** kowalewski/lauber/leinbach/hofmann
4. 质量门：Druckguss-primary（Conrad/Härer）；Buchhaltung/Versand；master-optional；names without mailto invent

### 本轨新增邮箱（共 7）

- `mail@mm-wzfb.de` · Geislingen bei Balingen · Martin Müller · Allgemeine Anfragen / Inhaber · high · **新域名**
- `info@schmidtke-ohg.de` · Lüdenscheid · Michaela Schmidtke / Andreas Schmidtke · Allgemeine Anfragen / Inhaber · high · **新域名**
- `martin@wfk-steinbrueck.de` · Lüdenscheid · Martin Steinbrück · Geschäftsführender Gesellschafter · high
- `kowalewski@giebeler.eu` · Eschenburg-Wissenbach · Jacqueline Kowalewski · Werkzeugbau Ansprechpartnerin · high
- `lauber@giebeler.eu` · Eschenburg-Wissenbach · Heiko Lauber · Werkzeugservice · high
- `leinbach@giebeler.eu` · Eschenburg-Wissenbach · Oliver Leinbach · Werkzeugservice · high
- `hofmann@giebeler.eu` · Eschenburg-Wissenbach · Peter Hofmann · Werkzeugservice · high

### 产物

- `data/germany_raw/batch99_new_verified.json` / `batch99_candidates_final.json`
- `data/germany_raw/batch99_quality_drops.json` / `batch99_merge_log.json`
- `data/germany_raw/batch100_queue_note.txt`

### 状态

Batch 99 已合并；下轮 Batch 100（Website）/ Batch98dir|99dir（目录）。队列剩余 thin multi ~**70+** + 新域名定向。DE-proven 优先；谨慎非 DE EU 国别邮箱。

---

## Website/named Kontakt Batch 98

> 合并前重读 CSV（Batch96dir 后基线 **3775** / **2559**；非 3734/2536。Batch97dir 未写入）。

### 累计（Batch 98 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3779** |
| high / medium | **3535** / **244** |
| 唯一域名 | **2561** |
| 含电话 / 含城市 | **3270** / **3349** |
| 非 .de 邮箱 | **1031** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3535** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **33** |

### 本轨成果（Batch 98）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+4**（high **3** / medium **1**） |
| 相对基线 3775/2559 | **+4** / **+2** 域名 |
| master 可选重叠 | **0** |
| 质量剔除 | **13** |

### 方法

1. 重读确认 **3775/2559**（Batch96dir 已合并；Batch97dir 空）
2. Thin multi named Kontakt（Gollmer）+ NEW-domain Spritzgießformenbau 定向
3. 命中：**Karl-Heinz Müller Formenbau** 新域名；**Gollmer** p.beckel/c.reichle；**Wagenknecht** 新域名（medium，Spritz+Stanz）
4. 质量门：Stanz/Umform（Heru）；Kokillen/Druckguss（Haasis/Karl Walter）；Rohstoff（TEKUMA）；Lager/Assistentin/Versand；Insolvenz（A-Form）；cloak/dead site

### 本轨新增邮箱（共 4）

- `info@formenbau-mueller.de` · Balingen-Engstlatt · — · Allgemeine Anfragen · high · **新域名**
- `p.beckel@gollmer-formen.de` · Kirchheim unter Teck · Philipp Beckel · Technischer Leiter ppa. / Prokurist · high
- `c.reichle@gollmer-formen.de` · Kirchheim unter Teck · Christoph Reichle · Projektleiter · high
- `info@wagenknecht-werkzeugbau.de` · Ebersbach-Neugersdorf · Dietmar Wagenknecht · Allgemeine Anfragen / Geschäftsführung · medium · **新域名**

### 产物

- `data/germany_raw/batch98_new_verified.json` / `batch98_candidates_final.json`
- `data/germany_raw/batch98_quality_drops.json` / `batch98_merge_log.json`
- `data/germany_raw/batch99_queue_note.txt`

### 状态

Batch 98 已合并；下轮 Batch 99（Website）/ Batch97dir|98dir（目录）。队列剩余 thin multi ~**75+** + 新域名定向。DE-proven 优先；谨慎非 DE EU 国别邮箱。

---

## Website/named Kontakt Batch 97

> 合并前重读 CSV（Website B96 后基线 **3724** / **2533**；Batch96dir 未写入）。

### 累计（Batch 97 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3734** |
| high / medium | **3491** / **243** |
| 唯一域名 | **2536** |
| 含电话 / 含城市 | **3240** / **3343** |
| 非 .de 邮箱 | **996** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3492** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch 97）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+10**（high **10** / medium **0**） |
| 相对基线 3724/2533 | **+10** / **+3** 域名 |
| master 可选重叠 | **0** |
| 质量剔除 | **11** |

### 方法

1. 重读确认 **3724/2533**（Batch96dir 空）
2. Expand 空；thin multi + NEW-domain Spritzguss/Formenbau 定向
3. 命中：**Formenbau Jäger** t-online；**Meinecke** 新域名；**Schürholz** 新域名；MOLDINO EU 国别邮箱×7
4. 质量门：Rohstoff（Aurora）；Formkästen/Corian/Feuerfest；Stanz/Umform；Druckguss-primary；cloak invent

### 本轨新增邮箱（共 10）

- `formenbaujaeger@t-online.de` · Brunnthal · Gabriele Jäger · Allgemeine Anfragen / Vertretung · high · **新域名**
- `info@meinecke-formenbau.de` · Ennepetal · Bernd Meinecke / Stefan Hartmann · Geschäftsführer / Allgemeine Anfragen · high · **新域名**
- `info@schuerholz.eu` · Attendorn · — · Allgemeine Anfragen · high · **新域名**
- `italy@moldino.eu` · Brescia · — · Italien Niederlassung · high
- `france@moldino.eu` · Dijon · — · Frankreich Niederlassung · high
- `spain@moldino.eu` · Sant Cugat del Vallès · — · Spanien Niederlassung · high
- `portugal@moldino.eu` · Marinha Grande · — · Portugal Niederlassung · high
- `poland@moldino.eu` · Poznań · — · Polen Niederlassung · high
- `austria@moldino.eu` · Linz · — · Österreich Niederlassung · high
- `slovenia@moldino.eu` · Ljubljana · — · Slowenien Niederlassung · high

### 产物

- `data/germany_raw/batch97_new_verified.json` / `batch97_candidates_final.json`
- `data/germany_raw/batch97_quality_drops.json` / `batch97_merge_log.json`
- `data/germany_raw/batch98_queue_note.txt`

### 状态

Batch 97 已合并；下轮 Batch 98（Website）/ Batch96dir|97dir（目录）。队列剩余 thin multi ~**80** + 新域名定向。

---

## 目录/展会轨 Batch97dir

> 合并前重读 CSV（Website B98 后基线 **3779** / **2561**；非 3775）。合并后基线：**3809** / **2589**。

### 累计（Batch97dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3809** |
| high / medium | **3564** / **245** |
| 唯一域名 | **2589** |
| 含电话 / 含城市 | **3286** / **3361** |
| 非 .de 邮箱 | **1058** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3565** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **33** |

### 本轨成果（Batch97dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **80** |
| 有邮箱命中 | **32** |
| 本轨净增邮箱 | **30**（high **29** / medium **1**） |
| 相对 Website B98 基线 3779/2561 | **+30** / **+28** 域名 |
| 再播种剩余 | **80** |
| 队列剩余 | **80** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空队列 | **80**（B96dir reseed：master_strict + VDWF） |
| 超时强制 no_email | 7（kikou-mold / moldspec / quality-mold / wepmolding / yongshengmould / starda-mould / precisionmoldandtool） |
| VDWF/Fakuma | 饱和 |
| WLW | CAPTCHA — 跳过 |
| 再播种 | master_strict 续取 **80**（已滤中国竞品 mould） |

### 方法

1. 排空上轮 **80** → Impressum（ThreadPool JSONL）
2. 合并前重读 **3779/2561** = Website B98
3. 质量剔除：中国竞品 mould、ISP/off-domain（hinet/cmdppl）、accounting/hr/tinfo；保留 MHS related medium
4. 再播种：master_strict 续 → 队列 **80**

### 本轨新增邮箱（共 30，节选）

- DE：`info@lahme-praezision.de` · `info@osp-praezision.de` · `info@thome-praezision.de`
- `info@werkzeugbau.com` · `info@bussmold.com` · `info@fischer-cnc.com` · `info@cncalvi.com`
- `info@mhs-hotrunners.com`（medium，related moldhotrunnersolutions）
- 及其他 mould/CNC peer `.com`（见 verified.json）

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 7 域名超时 → forced no_email
- 中国竞品 mould 域名排除
- 见 `data/germany_raw/batch97dir_merge_log.json`

### 产物

- `data/germany_raw/batch97dir_impressum.json`
- `data/germany_raw/batch97dir_verified.json` / `batch97dir_hits.json`
- `data/germany_raw/batch97dir_merge_log.json` / `batch97dir_reseed.json`

### 状态

Batch97dir 已合并；队列剩余 **80**（master_strict 续）供 Batch98dir。

---

## 目录/展会轨 Batch96dir

> 合并前重读 CSV（Website B97 后基线 **3734** / **2536**；非 3724）。合并后基线：**3775** / **2559**。

### 累计（Batch96dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3775** |
| high / medium | **3532** / **243** |
| 唯一域名 | **2559** |
| 含电话 / 含城市 | **3266** / **3345** |
| 非 .de 邮箱 | **1031** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3533** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch96dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **64** |
| 有邮箱命中 | **26** |
| 本轨净增邮箱 | **41**（high **41** / medium **0**） |
| 相对 Website B97 基线 3734/2536 | **+41** / **+23** 域名 |
| 再播种剩余 | **80** |
| 队列剩余 | **80** |

### 种子状态

| 项 | 状态 |
|---|---|
| 严格 ICP 过滤残留 | **4**（自 B95dir 弱词队列 80） |
| master_strict 新域名 | **60** |
| 核验合计 | **64** |
| 超时强制 no_email | cncmetal.com, jpmprototype.com |
| VDWF/Fakuma | 饱和；VDWF HTML 再提取供再播种 |
| WLW | CAPTCHA — 跳过 |

### 方法

1. 排空严格 ICP 过滤残留 **4** + master_strict **60** → Impressum（ThreadPool JSONL）
2. 合并前重读 **3734/2536** = Website B97
3. 质量剔除：协会/媒体 off-domain（gkv/vdma/hanser/ruffini）、digit-prefix junk local
4. 再播种：master_strict 续取 + VDWF HTML 域名 → 队列 **80**

### 本轨新增邮箱（共 41，节选）

- `info@kunststoffverpackungen.de` · `pro-kunststoff.de`（5）
- `normalientooling.com` · `rpimolding.com`（8）· `decaturmold.com`（6）
- `murraymold.com` · `blackhawkmolding.com` · `allamericanmold.com` · `artmarkmold.com`
- `jmjmoldes.com` · `grupomoldoeste.com` · 及其他 mould/CNC peer `.com`

完整列表见 `data/germany_raw/batch96dir_verified.json` / `batch96dir_hits.json`。

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 2 域名超时 → forced no_email
- 弱词非严格残留 **76** 未回队（本轮仅严格 ICP）
- 见 `data/germany_raw/batch96dir_merge_log.json`

### 产物

- `data/germany_raw/batch96dir_impressum.json`
- `data/germany_raw/batch96dir_verified.json` / `batch96dir_hits.json`
- `data/germany_raw/batch96dir_merge_log.json` / `batch96dir_reseed.json`

### 状态

Batch96dir 已合并；队列剩余 **80**（master_strict 续 + VDWF）供 Batch97dir。

---

## Website/named Kontakt Batch 96

> 合并前重读 CSV（Website B95 + Batch94dir 后基线 **3717** / **2532**；Batch95dir **+0**）。

### 累计（Batch 96 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3724** |
| high / medium | **3481** / **243** |
| 唯一域名 | **2533** |
| 含电话 / 含城市 | **3233** / **3333** |
| 非 .de 邮箱 | **988** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3482** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch 96）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+7**（high **7** / medium **0**） |
| 相对基线 3717/2532 | **+7** / **+1** 域名 |
| master 可选重叠 | **2**（formenbau@hkm-kunststoff.de, steffen@autenrieth-kunststofftechnik.de） |
| 质量剔除 | **12** |

### 方法

1. 重读确认 **3717/2532**（Batch95dir +0）
2. Expand 空；thin multi named Kontakt + NEW-domain 定向
3. 命中：HKM formenbau@+cnc@；Autenrieth steffen@ GF；nico nschmid@ GF；Junghans info@；Krauß t.riester@ GF；**FORMA** 新域名 info@
4. 质量门：Druckguss-primary（Cox/Weinmüller）；Verwaltung/Buchhaltung/Einkauf；Liquidation（Beiter）；cloak invent

### 本轨新增邮箱（共 7）

- `formenbau@hkm-kunststoff.de` · Ebersbach-Neugersdorf · — · Anfrage Formenbau · high
- `cnc-fertigung@hkm-kunststoff.de` · Ebersbach-Neugersdorf · — · Anfrage CNC-Präzisionsteile · high
- `steffen@autenrieth-kunststofftechnik.de` · Heroldstatt · Steffen Autenrieth · Geschäftsführer · high
- `nschmid@nico-kunststofftechnik.de` · Fellbach · Norman Schmid · Geschäftsleitung · high
- `info@junghans-microtec.de` · Dunningen · — · Allgemeine Anfragen · high
- `t.riester@krauss-formenbau.de` · Reutlingen-Sondelfingen · Timo Riester · Geschäftsführer · high
- `info@forma-gmbh.de` · Redwitz/Trainau · Frank Wich-Heiter / Klaus Bruchmann · Geschäftsführer / Allgemeine Anfragen · high · **新域名**

### 产物

- `data/germany_raw/batch96_new_verified.json` / `batch96_candidates_final.json`
- `data/germany_raw/batch96_quality_drops.json` / `batch96_merge_log.json`
- `data/germany_raw/batch97_queue_note.txt`

### 状态

Batch 96 已合并；下轮 Batch 97（Website）/ Batch96dir（目录）。队列剩余 thin multi ~**81** + 新域名定向。

---

## Website/named Kontakt Batch 95

> 合并前重读 CSV（目录 Batch93dir 后基线 **3702** / **2527**）。终写前再读：Batch94dir 并发后 **3717** / **2532**。

### 累计（Batch 95 + 并发 Batch94dir 后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3717** |
| high / medium | **3474** / **243** |
| 唯一域名 | **2532** |
| 含电话 / 含城市 | **3226** / **3326** |
| 非 .de 邮箱 | **988** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3475** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch 95）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+13**（high **13** / medium **0**） |
| 相对 Batch93dir 基线 3702/2527 | **+13** 邮箱 / **+3** 域名（B95 单独贡献 → 3715/2530） |
| 终写实时（含 Batch94dir） | **3717** / **2532** |
| master 可选重叠 | **2**（info@formenbau-klomfass.de、info@modelltechnik.de — 仍写入） |
| 质量剔除 | **13** |

### 方法

1. 重读确认 Batch93dir 后 **3702/2527**；终写前再读 Batch94dir 后 **3717/2532**
2. Expand 空；DE tooling singles 已尽；thin multi named Kontakt + Web 定向
3. 命中：Karl s.karl@；**Erwes-Reifenberg** 新域名×2；babyplast Marc Tesche GF；**PETA Formenbau** 新域名×3；Klomfass info@；**ModellTechnik** design_studio×5
4. 质量门：Buchhaltung/Personal；Stanz/Umform（Schwinn）；cloak invent；第三方无公司 mailto；收购收购 stale

### 本轨新增邮箱（共 13）

- `s.karl@karl-formenbau.de` · Untermeitingen · Sebastian Karl · Zerspanung/Programmierung · high · **新域名列** karl-formenbau.de
- `info@erwes-reifenberg.de` · Finnentrop · Präzisions-Formenbau · high · **新域名**
- `j.erwes@erwes-reifenberg.de` · Finnentrop · John Rudolf Erwes · GF · high
- `marc.tesche@babyplast.de` · Kierspe · Marc Tesche · GF · high
- `peta@peta-formenbau.de` · Bad Soden-Salmünster · high · **新域名**
- `alexander.wolf@peta-formenbau.de` · Alexander Wolf · GF Gesellschafter · high
- `manfred.ullrich@peta-formenbau.de` · Manfred Ullrich · GF Gesellschafter · high
- `info@formenbau-klomfass.de` · Heiligenhaus · high
- `info@modelltechnik.de` · Waltershausen · design_studio · high
- `sales@modelltechnik.de` · Waltershausen · Vertrieb · design_studio · high
- `formenbau@modelltechnik.de` · Waltershausen · Formenbau · design_studio · high
- `technikum@modelltechnik.de` · Waltershausen · Kunststoff-Technikum · design_studio · high
- `prototyping@modelltechnik.de` · Waltershausen · Prototyping · design_studio · high

### 产物

- `data/germany_raw/batch95_new_verified.json` / `batch95_candidates_final.json`
- `data/germany_raw/batch95_quality_drops.json` / `batch95_merge_log.json`
- `data/germany_raw/batch96_queue_note.txt`

### 状态

Batch 95 已合并（相对 B93dir **+13**）。实时合计 **3717** / **2532**（含 Batch94dir）。下轮 Batch 96（Website）。队列剩余 thin multi ~90–100 + 新域名定向。


---

## 目录/展会轨 Batch95dir

> 合并前重读 CSV（Website B95 后基线仍为 **3717** / **2532**）。合并后基线供 Website B96：**3717** / **2532**。

### 累计（Batch95dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3717** |
| high / medium | **3474** / **243** |
| 唯一域名 | **2532** |
| 含电话 / 含城市 | **3226** / **3326** |
| 非 .de 邮箱 | **988** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3475** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch95dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **29** |
| 有邮箱命中 | **3** |
| 本轨净增邮箱 | **0**（high **0** / medium **0**） |
| 相对基线 3717 | **+0** |
| 再播种剩余 | **80** |
| 队列剩余 | **80** |

### 种子状态

| 项 | 状态 |
|---|---|
| 上轮队列排空 | **8** |
| 档案再挖 fresh | **21** |
| master_strong ICP | **0**（已空） |
| VDWF/Fakuma | **saturated** |
| GKV Mitglieder | **404** |

### 本轮队列来源构成

| 来源 | 数量 |
|---|---:|
| `prior_queue` | **8** |
| `archive_batch85_candidates.json` | **1** |
| `archive_batch24_peer_expand2.jso` | **3** |
| `archive_batch24_peer_expand3.jso` | **2** |
| `archive_batch24_design_peer_expa` | **15** |

### 方法

1. 排空上轮 **8** + 档案 design/peer leftover **21** → **29** Impressum  
2. 尝试再播种：master_strong（0）、GKV（404）、弱 token master 残余 → 队列 **80**  
3. append-dedupe（合并前重读 **3717/2532**）；命中均为 known / 非 ICP（suedleasing）→ **净增 0**  
4. WLW 跳过

### 本轨新增邮箱

- （无）

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 目录/展会轨主源接近枯竭；弱 master 再播种质量预期偏低
- 见 `data/germany_raw/batch95dir_merge_log.json` / `batch95dir_hits.json`

### 产物

- `data/germany_raw/batch95dir_impressum.json`
- `data/germany_raw/batch95dir_verified.json` / `batch95dir_hits.json`
- `data/germany_raw/batch95dir_merge_log.json` / `batch95dir_reseed.json`

### 状态

Batch95dir 已合并（**+0**）；队列剩余 **80**（弱 master 残余）供 Batch96dir。

---

## 目录/展会轨 Batch94dir

> 合并前重读 CSV（Website B95 后基线 **3715** / **2530**）。合并后基线供 Website B96：**3717** / **2532**。

### 累计（Batch94dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3717** |
| high / medium | **3474** / **243** |
| 唯一域名 | **2532** |
| 含电话 / 含城市 | **3226** / **3326** |
| 非 .de 邮箱 | **988** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3475** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch94dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **98** |
| 有邮箱命中 | **24** |
| 本轨净增邮箱 | **2**（high **1** / medium **1**） |
| 相对 Website B95 基线 3715 | **+2** |
| 再播种剩余 | **9** |
| 队列剩余 | **9** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空队列 | **98**（已剔 *-messe / schall-messen 等） |
| VDWF re-extract 新域名 | **3** |
| Fakuma re-extract 新域名 | **6** |

### 方法

1. 排空上轮 **98** VDWF/Fakuma live 域名（预过滤展会门户）→ Impressum  
2. append-dedupe（合并前重读 **3715/2530** = Website B95）  
3. 质量剔除：媒体/高校非 ICP（perglermedia、th-deg）  
4. WLW 跳过；直播页再提取剩余极少

### 本轨新增邮箱（共 2）

- `support@dcam.de`
- `info.de@zeiss.com`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- VDWF/Fakuma live 再提取接近饱和（队列仅余 **9**）
- 见 `data/germany_raw/batch94dir_merge_log.json` / `batch94dir_hits.json`

### 产物

- `data/germany_raw/batch94dir_impressum.json`
- `data/germany_raw/batch94dir_verified.json` / `batch94dir_hits.json`
- `data/germany_raw/batch94dir_merge_log.json` / `batch94dir_reseed.json`

### 状态

Batch94dir 已合并；队列剩余 **9** 供 Batch95dir。

---

## 目录/展会轨 Batch93dir

> 合并前重读 CSV（Website B94 后基线 **3681** / **2514**）。合并后基线供 Website B95：**3702** / **2527**。

### 累计（Batch93dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3702** |
| high / medium | **3460** / **242** |
| 唯一域名 | **2527** |
| 含电话 / 含城市 | **3212** / **3312** |
| 非 .de 邮箱 | **987** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3465** |
| design_studio | **137** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch93dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **98** |
| 有邮箱命中 | **29** |
| 本轨净增邮箱 | **21**（high **19** / medium **2**） |
| 相对 Website B94 基线 3681 | **+21** |
| 再播种剩余 | **98** |
| 队列剩余 | **98** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空队列 | **98** |
| VDWF live HTML | **ok**（新提取 **94**） |
| Fakuma live HTML | **ok**（新提取 **4**） |
| 剔除展会门户 | schall-messen / control / motek / stanztec / schweisstec |

### 方法

1. 排空上轮 **98** VDWF/Fakuma live+archive 域名 → Impressum  
2. 刷新 VDWF Mitglieder / Fakuma 展商列表再播种  
3. append-dedupe（合并前重读 **3681/2514**）；剔除展会主办方与租赁非 ICP  
4. WLW 跳过

### 本轨新增邮箱（节选前 25 / 共 21）

- `ehs@dietrich-gruppe.com`
- `info@siebenwurst.com`
- `info@q-tech-roding.de`
- `info@tefmeflex.de`
- `contact@tepcon.de`
- `info@tepcon.de`
- `info@tooling-cooperation.de`
- `info@topseal-group.de`
- `info@zenit.de`
- `office@3s-gmbh.at`
- `office@ach-solution.at`
- `jm.saby@addiplast-group.com`
- `s.huguet@addiplast-group.com`
- `d.sautour@addiplast-group.com`
- `s.guyenot@addiplast-group.com`
- `a.colombet@addiplast-group.com`
- `c.iribarne@addiplast-group.com`
- `l.kamp@addiplast-group.com`
- `l.lesova@addiplast-group.com`
- `sales@artooling.com`
- `info@artopmold.com`


### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch93dir_merge_log.json` / `batch93dir_hits.json`

### 产物

- `data/germany_raw/batch93dir_impressum.json`
- `data/germany_raw/batch93dir_verified.json` / `batch93dir_hits.json`
- `data/germany_raw/batch93dir_merge_log.json` / `batch93dir_reseed.json`

### 状态

Batch93dir 已合并；队列剩余 **98** 供 Batch94dir。

---

## 目录/展会轨 Batch92dir

> 合并前重读 CSV（Website B93 后基线 **3668** / **2510**）。合并后基线供 Website B94：**3669** / **2511**。

### 累计（Batch92dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3669** |
| high / medium | **3429** / **240** |
| 唯一域名 | **2511** |
| 含电话 / 含城市 | **3185** / **3292** |
| 非 .de 邮箱 | **971** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3434** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch92dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **120** |
| 有邮箱命中 | **22** |
| 本轨净增邮箱 | **1**（high **0** / medium **1**） |
| 相对 Website B93 基线 3668 | **+1** |
| 已知重复跳过 | **15** |
| 再播种剩余 | **98** |
| 队列剩余 | **98** |

### 种子状态

| 项 | 数值 |
|---|---:|
| 排空上轮队列 | **85** |
| 档案再挖 fresh | **104**（入本轮核验 **35**） |
| VDWF mitglieder 直播 HTML | **ok** |
| Fakuma Ausstellerliste 直播 HTML | **ok** |
| 直播页新域名候选 | **29** |

### 方法

1. 排空上轮 **85** + 档案 ICP fresh **35** → 共 **120** Impressum  
2. 同步拉取 VDWF Mitglieder / Fakuma 展商列表（非 WLW）再播种  
3. append-dedupe（合并前重读 **3668/2510**）；多数命中已在库（known **15**）  
4. WLW 跳过

### 本轨新增邮箱（共 1）

- `ivonne.schulze@frank-formenbau.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 收益仍低：大量 formenbau 域名邮箱此前已以其它 domain key 入库
- 见 `data/germany_raw/batch92dir_merge_log.json` / `batch92dir_hits.json`

### 产物

- `data/germany_raw/batch92dir_impressum.json`
- `data/germany_raw/batch92dir_verified.json` / `batch92dir_hits.json`
- `data/germany_raw/batch92dir_merge_log.json` / `batch92dir_reseed.json`

### 状态

Batch92dir 已合并；队列剩余 **98**（VDWF/Fakuma live + archive）供 Batch93dir。

---

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

## Website/named Kontakt Batch 94

> 合并前重读 CSV（目录 Batch92dir 后基线 **3669** / **2511**）。

### 累计（Batch 94 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3681** |
| high / medium | **3441** / **240** |
| 唯一域名 | **2514** |
| 含电话 / 含城市 | **3196** / **3303** |
| 非 .de 邮箱 | **973** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3444** |
| design_studio | **137** |
| oem_buyer | **69** |
| sourcing | **31** |

### 本轨成果（Batch 94）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+12**（high **12** / medium **0**） |
| 相对 Batch92dir 基线 3669/2511 | **+12** / **+3** 域名 |
| master 可选跳过 | **0** |
| 质量剔除 | **13** |

### 方法

1. 重读确认 Batch92dir 后 **3669/2511**
2. Expand 空；thin multi named Kontakt + Web 定向
3. 命中：Haselbeck Greil；**Orthey** 新域名×2（.de/.com）Team×7；Ortmann Mould Engineering sourcing；ENDERS vertrieb@；Weis & Gutjahr GF×2
4. 质量门：Büroleitung/Buchhaltung/Einkauf/Verwaltung/EDV；HTML-comment；cloak invent；Stanz/Umform

### 本轨新增邮箱（共 12）

- `richard.greil@haselbeck.de` · Deggendorf · Richard Greil · Technischer Vertrieb · high
- `j.orthey@ortheymold.de` · Nister · Johannes Orthey · GF · high · **新域名**
- `c.kraemer@ortheymold.de` · Nister · Chris Kraemer · Projektleitung · high
- `t.gross@ortheymold.de` · Nister · Thomas Groß · Kfm. Leitung · high
- `k.karl@ortheymold.de` · Nister · Kathrin Karl · Vertrieb · high
- `m.troeger@ortheymold.de` · Nister · Marko Tröger · Projektleitung · high
- `info@ortheymold.de` · Nister · high · **新域名**
- `info@ortheymold.com` · Nister · high · **新域名**
- `tobi.ortmann@ortmann-mould-eng.com` · sourcing · high · **新域名**
- `vertrieb@enders-konstruktion.de` · Trebur · design_studio · high
- `weis@weis-gutjahr.de` · Vörstetten · Daniel Weis · GF · high
- `gutjahr@weis-gutjahr.de` · Vörstetten · Christian Gutjahr · GF · high

### 产物

- `data/germany_raw/batch94_new_verified.json` / `batch94_candidates_final.json`
- `data/germany_raw/batch94_quality_drops.json` / `batch94_merge_log.json`
- `data/germany_raw/batch95_queue_note.txt`

### 状态

Batch 94 已合并；下轮 Batch 95（Website）/ Batch93dir（目录）。

---

## Website/named Kontakt Batch 93

> 合并前重读 CSV（目录 Batch91dir 后基线 **3657** / **2509**）。

### 累计（Batch 93 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3668** |
| high / medium | **3429** / **239** |
| 唯一域名 | **2510** |
| 含电话 / 含城市 | **3184** / **3292** |
| 非 .de 邮箱 | **971** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3433** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch 93）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+11**（high **11** / medium **0**） |
| 相对 Batch91dir 基线 3657/2509 | **+11** / **+1** 域名 |
| master 可选跳过 | **1**（info@ds-werkzeugbau.de） |
| 质量剔除 | **9** |

### 方法

1. 重读确认 Batch91dir 后 **3657/2509**
2. Expand 空；thin multi named Kontakt + Web 定向
3. 命中：**RSD Polytec** 新域名（GF/Betriebsleiter/Vertrieb/Formenbau×7）；Hehnke Vertrieb+GF+anfrage@；OPUS kontakt@
4. 质量门：Stüwe HTML-comment；Sutter Buchhaltung；Jama invent；Flex-Punkt 错垂；cloak

### 本轨新增邮箱（共 11）

- `martin.rasenberger@rsdpolytec.de` · Efringen-Kirchen · Martin Rasenberger · GF · high · **新域名**
- `nico.rasenberger@rsdpolytec.de` · Bad Säckingen · Nico Rasenberger · Betriebsleiter · high
- `felix.thoma@rsdpolytec.de` · Efringen-Kirchen · Felix Thoma · Vertrieb · high
- `thomas.tremmel@rsdpolytec.de` · Bad Säckingen · Thomas Tremmel · Formenbau · high
- `peter.wolf@rsdpolytec.de` · Bad Säckingen · Peter Wolf · Vertrieb · high
- `info@rsdpolytec.de` · Efringen-Kirchen · high
- `juergen.klausmann@rsdpolytec.de` · Bad Säckingen · high
- `m.hilpert@hehnke.de` · Steinbach-Hallenberg · Martin Hilpert · Vertrieb · high
- `t.herrmann@hehnke.de` · Steinbach-Hallenberg · Torsten Herrmann · GF · high
- `anfrage@hehnke.de` · Steinbach-Hallenberg · high
- `kontakt@opus-mold.de` · Schönau · high

### 产物

- `data/germany_raw/batch93_new_verified.json` / `batch93_candidates_final.json`
- `data/germany_raw/batch93_quality_drops.json` / `batch93_merge_log.json`
- `data/germany_raw/batch94_queue_note.txt`

### 状态

Batch 93 已合并；下轮 Batch 94（Website）/ Batch92dir（目录）。

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

## 1. 累计交付数量（如实，至 Batch 94）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **3681** |
| 本轮净增（相对目录 Batch92dir 合并后基线 3669） | **+12** |
| 本轮因已在 master/targets 跳过 | **0** |
| 本轮质量剔除（死站/错垂/cloak 等） | **13** |
| 其中 high / medium | **3441** / **240** |
| 唯一域名 | **2514** |
| 非 .de 邮箱（累计） | **973** |
| 含电话 / 含城市 | **3196** / **3303** |
| 本轮新域名贡献 | **3**（ortheymold.de / ortheymold.com / ortmann-mould-eng.com） |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3444** |
| design_studio | **137** |
| oem_buyer | **69** |
| sourcing | **31** |

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

## 3. 下轮（Batch 95）提示

Expand empty; DE tooling singles exhausted. Prefer named Kontakt on remaining ~100 thin multi Spritzguss/Formenbau peers. Watch Batch93dir. Avoid Stanz/Umform, Assistentin/Buchhaltung/Einkauf/Personal/Verwaltung/Versand/Sekretariat, Europages-only invent, cloak invent, HTML-comment-only (Stüwe), Sauer stale invent.

---

_报告更新：2026-10-21 02:06 Asia/Hong_Kong_
