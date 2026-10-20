# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 88）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **3552** |
| 本轮净增（相对目录 Batch86dir 合并后基线 3534） | **+18** |
| 本轮因已在 master/targets 跳过 | **0** |
| 本轮质量剔除（死站/错垂/cloak 等） | **8** |
| 其中 high / medium | **3322** / **230** |
| 唯一域名 | **2452** |
| 非 .de 邮箱（累计） | **920** |
| 含电话 / 含城市 | **3106** / **3218** |
| 本轮新域名贡献 | **2** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3319** |
| design_studio | **134** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 88 · Website/named Kontakt）

1. **基线**：目录 Batch86dir 合并后 **重读 CSV** → **3534 / 2450**（非用户提示的 3480）。
2. **Expand 队列**：仍空；unprobed tooling singles ~10。
3. **Named Kontakt / Web 定向**：
   - K&B Kunststofftechnik Niederalteich（GF + Werkzeugbau + Spritzguss + QS；Buchhaltung/Einkauf 剔除）— **新域名**
   - Willy Sutter Formenbau Steinen/Kronach（`wsuttergmbh.de` 新域名 + Barnickel @.com；Buchhaltung 剔除）
   - TKT Kunststoff-Technik Bad Laer（Management/CS/Plant/PM；空格混淆 live-seen）
   - Schäfer `unterellen@` DE 工厂（海外工厂邮箱剔除）
4. **质量门**：Buchhaltung/Einkauf；Rummel third-party only；Tebis CAM 软件；FWI 协会；cloak。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| wave1 remaining singles | ~12 | WSutter/TKT/Schäfer |
| named Web（K&B/Lechner/Rummel…） | 多页 | **+5** K&B；Lechner 已入库；Rummel 未 live |

### 本轮新增（+18）

- `info@kb-kunststofftechnik.de` · Niederalteich ·    · high
- `willmerdinger@kb-kunststofftechnik.de` · Niederalteich · Kurt Willmerdinger · high
- `lukas.willmerdinger@kb-kunststofftechnik.de` · Niederalteich · Lukas Willmerdinger · high
- `szilard.kolozsi-nagy@kb-kunststofftechnik.de` · Niederalteich · Szilard Kolozsi-Nagy · high
- `qm-qs@kb-kunststofftechnik.de` · Niederalteich · Laura Weber · high
- `info@wsuttergmbh.de` · Steinen ·    · high
- `k.maier@wsuttergmbh.de` · Steinen · Karl Maier · high
- `s.gerring@wsuttergmbh.de` · Steinen · Stefan Gerring · high
- `t.winter@wsuttergmbh.de` · Steinen · Tom Winter · high
- `r.klatt@wsuttergmbh.de` · Steinen · Robert Klatt · high
- `a.weimer@wsuttergmbh.de` · Kronach · Alexander Weimer · high
- `a.meier@wsuttergmbh.de` · Kronach · Alexander Meier · high
- `a.barnickel@wsuttergmbh.com` · Kronach · Alexander Barnickel · high
- `peter.brinkmann@tkt-plastics.com` · Bad Laer · Peter Brinkmann · high
- `joerg.thomas@tkt-plastics.com` · Bad Laer · Jörg Thomas · high
- `barbara.moehlmann@tkt-plastics.com` · Bad Laer · Barbara Moehlmann · high
- `henning.funke@tkt-plastics.com` · Bad Laer · Henning Funke · high
- `unterellen@schaefer.biz` · Unterellen ·    · medium

### 本轮新域名

- `kb-kunststofftechnik.de`
- `wsuttergmbh.de`

### skipped-already-known（0）

（无）

### 质量剔除（节选）

**8**：K&B Buchhaltung/Einkauf；Sutter Buchhaltung；Rummel plasticker-only；Schäfer 海外厂；Tebis；FWI；cloak。

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch88_new_verified.json`
- `data/germany_raw/batch88_expand_results.json`
- `data/germany_raw/batch88_merge_log.json`
- `data/germany_raw/batch88_candidates.json` / `batch88_probe_wave1.json`
- `data/germany_raw/batch88_quality_drops.json`

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；singles 队列近空。B89 优先 web-search named Kontakt；Watch Batch87dir。

---

## 目录/展会轨 Batch88dir

> 合并前重读 CSV（基线 **3560** / **2460**；Website B89 当时尚未改写）。合并后基线供 Website B89/B90：**3597** / **2486**。

### 累计（Batch88dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3597** |
| high / medium | **3365** / **232** |
| 唯一域名 | **2486** |
| 含电话 / 含城市 | **3121** / **3232** |
| 非 .de 邮箱 | **951** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3362** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch88dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **120** |
| 有邮箱命中 | **40** |
| 本轨净增邮箱 | **37**（high **36** / medium **1**） |
| 相对基线 3560 | **+37** |
| 再播种剩余 | **120** |
| 队列剩余 | **120** |

### 方法

1. 排空上轮 **120** 个 broader master `.de/.at/.ch` → Impressum/Kontakt  
2. append-dedupe（合并前重读 **3560/2460**）  
3. 质量剔除：web.de / freenet 门户、医院等非 ICP（broader master 噪音）  
4. 续播种 broader master → 队列 **120**；WLW 跳过

### 本轨新增邮箱（节选前 25 / 共 37）

- `info@helios-ac.ch`
- `admin@digisens.ch`
- `admin@mafix.ch`
- `automotive@preh.de`
- `contact@nose.ch`
- `commercial@rmontavon.ch`
- `contact@rmontavon.ch`
- `corresp@schallersa.ch`
- `info@werba-print.de`
- `daten@lmd-innovation.de`
- `dave@wats-on.de`
- `post@schoenmueller.de`
- `contact@dixi.ch`
- `communication@he-arc.ch`
- `juridique@he-arc.ch`
- `office@hadi.at`
- `presse@bingo-ev.de`
- `support@bingo-ev.de`
- `info@rudolfpuetzergmbh.de`
- `hewa@hewa-ft.de`
- `info@tectro.de`
- `info@hund.de`
- `info@realag.ch`
- `info@adax.ch`
- `info@admo.ch`
… 另有 12 个，见 `data/germany_raw/batch88dir_hits.json`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- broader master 含门户噪音，已剔除 web.de/freenet/hcuge
- 见 `data/germany_raw/batch88dir_merge_log.json` / `batch88dir_hits.json`

### 产物

- `data/germany_raw/batch88dir_impressum.json`
- `data/germany_raw/batch88dir_verified.json` / `batch88dir_hits.json`
- `data/germany_raw/batch88dir_merge_log.json` / `batch88dir_reseed.json`

### 状态

Batch88dir 已合并；队列剩余 **120** 供 Batch89dir。

---

## 目录/展会轨 Batch87dir

> 合并前重读 CSV（Website B88 后基线 **3552** / **2452**）。合并后基线供 Website B89：**3560** / **2460**。

### 累计（Batch87dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3560** |
| high / medium | **3329** / **231** |
| 唯一域名 | **2460** |
| 含电话 / 含城市 | **3109** / **3221** |
| 非 .de 邮箱 | **927** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3325** |
| design_studio | **136** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch87dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **37** |
| 有邮箱命中 | **11** |
| 本轨净增邮箱 | **8**（high **7** / medium **1**） |
| 相对 Website B88 基线 3552 | **+8** |
| 再播种剩余 | **121** |
| 队列剩余 | **121** |

### 方法

1. 排空上轮 **37** 个 master ICP 剩余域名 → Impressum/Kontakt  
2. append-dedupe（合并前重读 **3552/2452** = Website B88）  
3. 严格 ICP master 池已空 → 再播种放宽为 broader master `.de/.at/.ch` + expand/design 队列（**121**）  
4. WLW 跳过（CAPTCHA）

### 本轨新增邮箱（共 8）

- `christoph@formfabrik.ch`
- `office@formschluss.at`
- `office@kmould.at`
- `contact@peschke.at`
- `office@researchstudio.at`
- `proform@proform.ch`
- `spritzguss@prontoplast.ch`
- `wehapost@weha-plastic.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 严格 keyword master ICP 耗尽；已切换 broader master 再播种
- 见 `data/germany_raw/batch87dir_merge_log.json` / `batch87dir_hits.json`

### 产物

- `data/germany_raw/batch87dir_impressum.json`
- `data/germany_raw/batch87dir_verified.json` / `batch87dir_hits.json`
- `data/germany_raw/batch87dir_merge_log.json` / `batch87dir_reseed.json`

### 状态

Batch87dir 已合并；队列剩余 **121** 供 Batch88dir。

---

## 目录/展会轨 Batch86dir

> 合并前重读 CSV（Website B87 后基线 **3480** / **2404**）。合并后基线供 Website B88：**3534** / **2450**。

### 累计（Batch86dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3534** |
| high / medium | **3305** / **229** |
| 唯一域名 | **2450** |
| 含电话 / 含城市 | **3088** / **3200** |
| 非 .de 邮箱 | **914** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3301** |
| design_studio | **134** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch86dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **150** |
| 有邮箱命中 | **60** |
| 本轨净增邮箱 | **54**（high **49** / medium **7**） |
| 相对 Website B87 基线 3480 | **+54** |
| master ICP 再播种剩余 | **37** |
| 队列剩余 | **37** |

### 方法

1. 排空上轮 **150** 个 master ICP 再播种域名 → Impressum/Kontakt  
2. append-dedupe（合并前重读 **3480/2404** = Website B87）  
3. 质量过滤：同域 high；品牌相关 medium（含 `.swiss` 孪生）；丢弃 digit-prefix 刮取垃圾邮箱  
4. 再播种 master ICP 续段 → 队列 **37**；WLW 跳过

### 本轨新增邮箱（节选前 25 / 共 54）

- `max.eberle@glaroform.swiss`
- `robin.eberle@glaroform.swiss`
- `peter.hotz@glaroform.swiss`
- `markus.blessing@glaroform.swiss`
- `michele.freuler@glaroform.swiss`
- `info@glaroform.swiss`
- `info@hf-cncbearbeitung.de`
- `info@hipp-praezisionstechnik.de`
- `info@hs-formtechnik.de`
- `info@hs-kunststoffe.de`
- `info@ils-fertigungstechnik.de`
- `info@indra-metall.de`
- `info@kaiser-metallwaren.de`
- `info@keim-fasertechnik.de`
- `info@ks-biegetechnik.de`
- `info@lamers-metallverarbeitung.de`
- `info@lappe-metallbau.de`
- `info@maedel-metall.de`
- `info@maschinentechnik.de`
- `info@mcadform.de`
- `info@metallbearbeitung-bruno.de`
- `info@mform.de`
- `info@mjm-metallverarbeitung.de`
- `info@mould2part.ch`
- `info@multiple-design.ch`
… 另有 31 个，见 `data/germany_raw/batch86dir_hits.json`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch86dir_merge_log.json` / `batch86dir_hits.json`

### 产物

- `data/germany_raw/batch86dir_impressum.json`
- `data/germany_raw/batch86dir_verified.json` / `batch86dir_hits.json`
- `data/germany_raw/batch86dir_merge_log.json` / `batch86dir_reseed.json`

### 状态

Batch86dir 已合并；队列剩余 **37**（master ICP）供 Batch87dir。

---

## 目录/展会轨 Batch85dir

> 合并前重读 CSV（Website B86 后基线 **3435** / **2386**）。合并后基线供 Website B87：**3462** / **2404**。

### 累计（Batch85dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3462** |
| high / medium | **3241** / **221** |
| 唯一域名 | **2404** |
| 含电话 / 含城市 | **3031** / **3148** |
| 非 .de 邮箱 | **878** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3230** |
| design_studio | **133** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch85dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **60** |
| 有邮箱命中 | **23** |
| 本轨净增邮箱 | **27**（high **25** / medium **2**） |
| 相对 Website B86 基线 3435 | **+27** |
| master ICP 再播种剩余 | **150** |
| 队列剩余 | **150** |

### 方法

1. 排空上轮 **60** 个 master/pool leftover 域名 → Impressum/Kontakt  
2. append-dedupe（合并前重读 **3435/2386** = Website B86）  
3. 再播种：master ICP `.de/.at/.ch` → 队列 **150**  
4. WLW 跳过（CAPTCHA）

### 本轨新增邮箱（节选前 25 / 共 27）

- `info@d-plast.ch`
- `info@eph-elektronik.com`
- `kevin.szvitok@eph-elektronik.com`
- `info@formreich.ch`
- `info@fatra.cz`
- `contact@geficca.fr`
- `geocad@geocad.es`
- `david@geocad.es`
- `joao.silva@geocad.es`
- `jack.zhao@geocad.es`
- `juan.martinez@geocad.es`
- `info@kessler-ag.ch`
- `info@kvl-gmbh.com`
- `kontakt@layertech.pl`
- `office@maplan.at`
- `helpdesk@maplan.at`
- `guss@mettec.at`
- `office@mettec.at`
- `geral@natigam.pt`
- `info@ocellrings.com`
- `info@perezlinares.com`
- `info@pinsundmehr.de`
- `32info@pfwag.ch`
- `info@pfwag.ch`
- `info@piu.nl`
… 另有 2 个，见 `data/germany_raw/batch85dir_hits.json`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch85dir_merge_log.json` / `batch85dir_hits.json`

### 产物

- `data/germany_raw/batch85dir_impressum.json`
- `data/germany_raw/batch85dir_verified.json` / `batch85dir_hits.json`
- `data/germany_raw/batch85dir_merge_log.json` / `batch85dir_reseed.json`

### 状态

Batch85dir 已合并；队列剩余 **150**（master ICP）供 Batch86dir。

---

## 目录/展会轨 Batch84dir

> 合并前重读 CSV（Website B84 后基线 **3382** / **2349**）。合并后基线供 Website B85：**3419** / **2384**。

### 累计（Batch84dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3419** |
| high / medium | **3200** / **219** |
| 唯一域名 | **2384** |
| 含电话 / 含城市 | **3000** / **3116** |
| 非 .de 邮箱 | **851** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3187** |
| design_studio | **133** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch84dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **100** |
| 有邮箱命中 | **43** |
| 本轨净增邮箱 | **37**（high **35** / medium **2**） |
| 相对 Website B84 基线 3382 | **+37** |
| 再播种剩余 | **60** |
| 队列剩余 | **60** |

### 方法

1. 排空上轮 ~21 Fakuma unused（剔协会/展会/畸形域名）→ 16 可用  
2. 再播种：VDWF extras + Europages 缓存站 + master ICP `.de` → 共核验 **100**  
3. append-dedupe（合并前重读 **3382/2349**）；同域 high / 品牌相关 medium  
4. WLW 跳过（CAPTCHA）

### 本轨新增邮箱（节选前 25 / 共 37）

- `office@simcon.com`
- `infohrde@synventive.com`
- `info@topas.com`
- `info@ifu-online.de`
- `info@kolibri.de.com`
- `info@hohlgmbh.com`
- `info@kunststoff-meyer.com`
- `info@ak-kunststoffspritzguss.com`
- `info@oks-germany.com`
- `info@iesgmbh.com`
- `info@pfaffgmbh.com`
- `info@schuemann-gmbh.com`
- `info@moeller-gmbh.com`
- `fkb@fkb-gmbh.com`
- `info@abs-gmbh.com`
- `info@baum-gmbh.com`
- `info@braun-gmbh.com`
- `info@si-tech-gmbh.com`
- `info@wethje-gmbh.com`
- `fredrik.sporrong@materialise.com`
- `proyectos@materialise.com`
- `contato@materialise.com`
- `info@sagerbeton.de`
- `baufakturaschulungenbuchungsseite@huonker.de`
- `mateo.adam@glory-injectionplastique.fr`
… 另有 12 个，见 `data/germany_raw/batch84dir_hits.json`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch84dir_merge_log.json` / `batch84dir_hits.json`

### 产物

- `data/germany_raw/batch84dir_impressum.json`
- `data/germany_raw/batch84dir_verified.json` / `batch84dir_hits.json`
- `data/germany_raw/batch84dir_merge_log.json` / `batch84dir_reseed.json`

### 状态

Batch84dir 已合并；队列剩余 **60**（master/pool leftover）供 Batch85dir。

---

## 目录/展会轨 Batch83dir

> 合并前重读 CSV（Website B83 后基线 **3333** / **2327**）。合并后基线供 Website B84：**3368** / **2349**。

### 累计（Batch83dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3368** |
| high / medium | **3154** / **214** |
| 唯一域名 | **2349** |
| 含电话 / 含城市 | **2958** / **3070** |
| 非 .de 邮箱 | **821** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3137** |
| design_studio | **132** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch83dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **117** |
| 有邮箱命中 | **46** |
| 本轨净增邮箱 | **35**（high **33** / medium **2**） |
| 相对 Website B83 基线 3333 | **+35** |
| Fakuma/VDWF 再播种剩余 | **21** |
| 队列剩余 | **21** |

### 方法

1. 清理上轮 26 个 VDWF 再播种（剔 youtu.be/fb.me/pressebox 等噪音）→ 12 可用  
2. 再播种：VDWF `data-www` 未核验域名 + Fakuma unused → 共核验 **117**  
3. append-dedupe（合并前重读 **3333/2327**）；同域 high / 品牌相关 medium；丢弃 off-domain 与截断垃圾邮箱  
4. WLW / Europages / Gelbe Seiten 本轮不依赖（CAPTCHA/consent）

### 本轨新增邮箱（节选前 25 / 共 35）

- `brackenheim@haerterei.com`
- `bochum@haerterei.com`
- `chemnitz@haerterei.com`
- `weimar@haerterei.com`
- `info@hirschmann-automotive.com`
- `mail@konsens.de`
- `info@mcu-gmbh.de`
- `buchhaltung@mcu-gmbh.de`
- `info@nachreiner-werkzeuge.de`
- `info@polytalent.de`
- `mail@kunststoff-institut.de`
- `mumme@kunststoff-institut.de`
- `info@badico-trading.com`
- `info@bbsautomation.com`
- `info.blaichach@bbsautomation.com`
- `info.hallbergmoos@bbsautomation.com`
- `info.stuttgart@bbsautomation.com`
- `info.caravaggio@bbsautomation.com`
- `info.poggibonsi@bbsautomation.com`
- `info.atlanta@bbsautomation.com`
- `info.chicago@bbsautomation.com`
- `info@belaser.de`
- `info@bohler.de`
- `info.bosch.iam@bosch.com`
- `info@byk.com`
… 另有 10 个，见 `data/germany_raw/batch83dir_hits.json`

### 阻塞 / 备注

- WLW 公司页 CAPTCHA — 跳过
- Fakuma 域名命中率偏低（多数 no_email / 死站）
- 见 `data/germany_raw/batch83dir_merge_log.json` / `batch83dir_hits.json`

### 产物

- `data/germany_raw/batch83dir_impressum.json`
- `data/germany_raw/batch83dir_verified.json` / `batch83dir_hits.json`
- `data/germany_raw/batch83dir_merge_log.json` / `batch83dir_reseed.json`

### 状态

Batch83dir 已合并；队列剩余 **21**（Fakuma unused）供 Batch84dir。

---

## 目录/展会轨 Batch82dir（VDWF）

> 合并前重读 CSV（Website B82 后基线 **3042** / **2119**）。合并后基线供 Website B83：**3320** / **2326**。

### 累计（Batch82dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3320** |
| 唯一域名 | **2326** |
| 本轨净增（相对 3042） | **+278** |
| Impressum 核验 | **328** |

### 本轨要点

VDWF Mitglieder extras（WLW CAPTCHA 阻断）；见 `batch82dir_merge_log.json` / `batch82dir_hits.json`。

### 状态

Batch82dir 已合并；Website Batch 83 在其上再合并 **+13** → 累计 **3333 / 2327**。

---

## 目录/展会轨 Batch82dir

> 合并前重读 CSV（Website B82 后基线 **3042** / **2119**）。合并后基线供 Website B83：**3320** / **2326**。

### 累计（Batch82dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3320** |
| high / medium | **3108** / **212** |
| 唯一域名 | **2326** |
| 含电话 / 含城市 | **2912** / **3025** |
| 非 .de 邮箱 | **800** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3089** |
| design_studio | **132** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch82dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **328** |
| 有邮箱命中 | **235** |
| 本轨净增邮箱 | **278**（high **254** / medium **24**） |
| 相对 Website B82 基线 3042 | **+278** |
| VDWF 再播种剩余 | **26** |
| 队列剩余 | **26** |

### 方法

1. 排空上轮 **328** 个 VDWF 域名队列 → Impressum/Kontakt（WLW CAPTCHA，本轮不用 WLW 公司页）
2. append-dedupe 入库（与 Website 轨并行，合并前重读 **3042/2119**）
3. 质量过滤：同域 high；品牌相关异域 medium；丢弃 off-domain 广告/占位/混淆邮箱
4. VDWF mitglieder 额外域名再播种 → 队列剩余 **26**（供 Batch83dir）

### 本轨新增邮箱（节选前 25 / 共 278）

- `mail@kellermanngmbh.de`
- `info@cadkaiser.de`
- `info@inevo.eu`
- `mail@alte.de`
- `info@harnischmacher.de`
- `tooling@tsetinis.com`
- `info@inwetec.de`
- `anfrage@elektrodenfabrik.de`
- `info@hotec-gmbh.de`
- `anfragen@hotec-gmbh.de`
- `info@laserkraftwerk.de`
- `info@hydropneu.de`
- `info@iket-horb.de`
- `o.kessling@iket-horb.de`
- `s.epple@iket-horb.de`
- `b.rief@iket-horb.de`
- `mail@polymold.de`
- `info@wika-erodiertechnik.de`
- `info@reutlingen-university.de`
- `sabine.loebbe@reutlingen-university.de`
- `daniela.goller@reutlingen-university.de`
- `aniela.goller@reutlingen-university.de`
- `maximilian.musch@reutlingen-university.de`
- `rmz-leitung@reutlingen-university.de`
- `info@cnc-sicks.de`
… 另有 253 个，见 `data/germany_raw/batch82dir_hits.json`

### 阻塞 / 备注

- WLW 公司页 Human Verification CAPTCHA — Batch82dir 仅用 VDWF
- 见 `data/germany_raw/batch82dir_merge_log.json` / `batch82dir_hits.json`

### 产物

- `data/germany_raw/batch82dir_impressum.json`
- `data/germany_raw/batch82dir_verified.json` / `batch82dir_hits.json`
- `data/germany_raw/batch82dir_merge_log.json` / `batch82dir_reseed.json`

### 状态

Batch82dir 已合并；队列剩余 **26** VDWF 再播种域名供 Batch83dir。

---

## 目录/展会轨 Batch81dir

> 合并前重读 CSV（Website B80 后基线 **2924** / **2032**）。合并后基线供 Website B81：**3022** / **2117**。

### 累计（Batch81dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3022** |
| 唯一域名 | **2117** |
| 本轨净增（相对 2924） | **+98** |

### 本轨要点

见 `data/germany_raw/batch81dir_merge_log.json` / `batch81dir_hits.json`。

### 状态

Batch81dir 已合并；Website Batch 81 在其上再合并 **+13** → 累计 **3035 / 2118**。

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
