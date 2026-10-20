# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 75）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **1934** |
| 本轮净增（相对 Batch 74 的 1903） | **+31** |
| 本轮因已在 master/targets/pilot 跳过 | **86** |
| 本轮质量剔除（死站/错垂/cloak 等） | **13** |
| 其中 high / medium | **1829** / **105** |
| 唯一域名 | **1347** |
| 非 .de 邮箱（累计） | **256** |
| 含电话 / 含城市 | **1699** / **1792** |
| 本轮新域名贡献 | **0** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **1706** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 75）

1. **Expand 队列**：empty（B74 已排空 Croner）→ **+0**。
2. **Named Kontakt / Ansprechpartner**（已知 peer Formenbau 域名，非目录翻页）：
   - BamA Marsberg Kontakt（7 named）
   - Battenberger Über-uns GF
   - Droigk `info@…de`（CSV 仅有 `.com`）
   - Ganser Kontakt Günter Ganser
   - HPF/FUS Ansprechpartner（7 keep；Sekretariat/enesty 剔除）
   - WISA Ansprechpartner（4）
   - OM Werkzeugbau Kontakt（3；HR Thomas 剔除）
   - Weckerle 角色邮箱 konstruktion@ / werkzeugbau@
   - Müller Werkzeugbau Kontakt via mueller-formenbau-gmbh.de host（5；Buchhaltung/Einkauf 剔除）
3. **质量门**：ABAS/Hack/Croner/FBB cloak；Sekretariat/HR/Einkauf/Buchhaltung/third-party enesty；scrape junk。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| expand 队列 | 0 | **+0** |
| named Kontakt / Ansprechpartner | ~90+ peer domains probed | **+31** |

### 本轮新增（+31）

- `wirth@bama-formenbau.de` · Marsberg · Jörg Wirth · high
- `matthaeus@bama-formenbau.de` · Marsberg · Elmar Matthäus · high
- `b.bannenberg@bama-formenbau.de` · Marsberg · Bernd Bannenberg · high
- `hefer@bama-formenbau.de` · Marsberg · Andreas Hefer · high
- `teszler@bama-formenbau.de` · Marsberg · Kerstin Teszler · high
- `brandmaehl@bama-formenbau.de` · Marsberg · Lars Brandmehl · high
- `dornow@bama-formenbau.de` · Marsberg · Maria Dornow · high
- `h.kreuzberger@battenberger-formenbau.de` · Battenberg · Harald Kreuzberger · high
- `info@droigk-formenbau.de` · Iserlohn ·  · high
- `g.ganser@ganser-werkzeugbau.de` · Georgsmarienhütte · Günter Ganser · high
- `uwe.friedrich@fus-werkzeugbau.de` · Großdubrau · Uwe Friedrich · high
- `rene.spahn@fus-werkzeugbau.de` · Großdubrau · René Spahn · high
- `philipp.heinze@fus-werkzeugbau.de` · Großdubrau · Philipp Heinze · high
- `catharina.mielsch@fus-werkzeugbau.de` · Großdubrau · Catharina Mielsch · high
- `clemens.menzel@fus-werkzeugbau.de` · Großdubrau · Clemens Menzel · high
- `andre.pischtschan@fus-werkzeugbau.de` · Großdubrau · André Pischtschan · high
- `uwe.mittasch@fus-werkzeugbau.de` · Großdubrau · Uwe Mittasch · high
- `torsten.decker@wisa-formenbau.de` · Denkendorf · Torsten Decker · high
- `marion.dresel@wisa-formenbau.de` · Denkendorf · Marion Dresel · high
- `gabriele.kantschick@wisa-formenbau.de` · Denkendorf · Gabriele Kantschick · high
- `michael.kornprobst@wisa-formenbau.de` · Denkendorf · Michael Kornprobst · high
- `d.pieper@om-werkzeugbau.de` · Mühlen · Dennis Pieper · high
- `a.ortmann@om-werkzeugbau.de` · Mühlen · Alexander Ortmann · high
- `g.boergerding@om-werkzeugbau.de` · Mühlen · Gregor Börgerding · high
- `werkzeugbau@weckerle-werkzeugbau.de` · Ingolstadt · Markus Weckerle, Dennis Weckerle · high
- `konstruktion@weckerle-werkzeugbau.de` · Ingolstadt · Uwe Weckerle · high
- `c.mueller@mueller-werkzeugbau-gmbh.de` · Ludwigsstadt · Carlo Müller · high
- `p.zwosta@mueller-werkzeugbau-gmbh.de` · Ludwigsstadt · Pascal Zwosta · high
- `t.schramm@mueller-werkzeugbau-gmbh.de` · Ludwigsstadt · Tobias Schramm · high
- `s.thiele@mueller-werkzeugbau-gmbh.de` · Ludwigsstadt · Stephan Thiele · high
- `a.zwosta@mueller-werkzeugbau-gmbh.de` · Ludwigsstadt · Anja Zwosta · high

### 本轮新域名

- （无 — 均在已有 peer 域名上扩 named）

### skipped-already-known（86）

`a.guentner@musterbau.info`, `b.strassberger@steinhauser-formenbau.de`, `bettina.weiss@swo-formenbau.de`, `d.walter@oesterle-formenbau.de`, `felsch@felsch-spritzguss.de`, `firma@formenbau-meyer.de`, `info@aulbach-werkzeugbau.de`, `info@bama-formenbau.de`, `info@battenberger-formenbau.de`, `info@becker-formenbau.de`, `info@bf-formenbau.de`, `info@blochwitz-formenbau.de`, `info@blum-praezision.de`, `info@brand-werkzeugbau.de`, `info@breit-formenbau.de`, `info@croner-formenbau.de`, `info@droigk-formenbau.com`, `info@ebs-werkzeugbau.de`, `info@efi-formenbau.de`, `info@egle-werkzeugbau.de`, `info@fbb-formenbau.de`, `info@fenkl-formenbau.de`, `info@formen-modellbau.de`, `info@formen-werkzeugbau.de`, `info@formenbau-borchert.de` … (+61 more)

### 质量剔除（节选）

**13**：FUS Sekretariat；enesty third-party；OM Talent/HR；Weckerle Buchhaltung；Müller Buchhaltung/Einkauf；ABAS/Hack/Croner/FBB cloak；mouldtec personal@；scrape junk…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch75_new_verified.json`
- `data/germany_raw/batch75_expand_results.json`
- `data/germany_raw/batch75_merge_log.json`
- `data/germany_raw/batch75_probe_wave1.json` / `batch75_probe_wave2.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B76：empty expand — continue named Kontakt）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；named Kontakt 在剩余 single-email peer 域名上仍有空间（ABAS cloak 待观察；rausch/midena/snw/sohl 等）。B76 继续 website/named Kontakt track。


---

## 目录/展会轨 Batch75dir

> 与 website Batch 75 并行；按邮箱去重 append-merge，未删除 website 轨行。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2153** |
| high / medium | **2029** / **124** |
| 唯一域名 | **1508** |
| 含电话 / 含城市 | **1892** / **1986** |
| 非 .de 邮箱 | **330** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **1925** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch75dir）

| 指标 | 数值 |
|---|---:|
| 新域名种子（目录/展会，相对 known） | **614** |
| Impressum/Kontakt 已核验域名 | **314** |
| 本轨净增邮箱（email-unique） | **219**（high≈200 / medium≈19） |
| 本轨涉及新域名（有邮箱入库） | **161** |
| 剩余未核验目录域名队列 | **352** |

### 来源与吞吐

1. **Fakuma 2026 Ausstellerliste**：WP AJAX 下载全量 XLSX（1495 展商）+ `?Land=56&pg=1..8` HTML 解析 **735 DE** 展商联系方式（邮箱+官网）→ 过滤 known 后约 **600+ 新域名**。
2. **KunststoffWeb**：Spritzgieß-/Presswerkzeuge + Andere Formwerkzeuge 列表 **152 DE** 公司；拉取 80 家详情页。**Formenbau 大类 p100362（标称 498）curl 无公司列表**（疑似 JS/反爬）— blocker。
3. **WLW**：formenbau/spritzguss/werkzeugbau 分页合计 **316** firm slug；详情页经 schema.org `sameAs` 解析官网；本轮核验一批 `.de`。
4. **Europages**：列表可采，公司页静态 HTML **无可用 websiteUrl/mailto**（reCAPTCHA 提示）— blocker。

### 本轨新增邮箱（节选前 30 / 共 219）

- `8170-29post@coltec-mb.de`
- `a.beek@bsg.de`
- `anders.karlsson@centramec.com`
- `andre.miertschin@shouju.com`
- `anfrage@basarigmbh.de`
- `anfrage@e-braun.de`
- `arjanne.wijnen@ascenta.de`
- `askbinks@binks.com`
- `askus@binks.com`
- `banken@ceracon.com`
- `career@daikinchem.de`
- `carlos.aguila@shouju.com`
- `chango@chango-glo.com`
- `contact@polymerize.io`
- `contact@se-k.de`
- `cs-eu@binks.com`
- `daniel.carlsson@centramec.com`
- `dce.info@daikinchem.de`
- `de.info@donnerberg.net`
- `dk@dk-kunststoffe.de`
- `dy@pro-plast.de`
- `epost@ceracon.com`
- `extruder@leistritz.com`
- `extrusion-psirt@leistritz.com`
- `fakuma@asahi-kasei.eu`
- `gruppe@eifeler.com`
- `hallen@shouju.com`
- `hesco@hesco.de`
- `holger_weisser@kkt-vs.de`
- `info-america@tebis.com`
… 另有 189 个，见 `data/germany_raw/batch75dir_hits.json`

### 本轨新域名（节选）

`3d-schilling.de`, `aboutjell.de`, `albea.de`, `ascenta.de`, `autosol.de`, `aw-schumacher.de`, `barnet.com`, `basarigmbh.de`, `bauerschmidt-folien.de`, `bfa-kunststofftechnik.de`, `bgf-enztech.com`, `bieglo.com`, `biesinger-gmbh.com`, `binks.com`, `bio-circle.de`, `biw.de`, `boyke-tec.de`, `braunform.com`, `bretthauer.de`, `brueggemann.com`, `bruno-weisser.de`, `bsg.de`, `buss-werkzeugbau.de`, `carbo.de`, `cas-kunststoffe.de`…

### Blockers

- KunststoffWeb Formenbau 分类页空列表（curl）
- Europages 公司站链接/邮箱被前端/CAPTCHA 挡住
- 部分站点超时/无 Impressum mailto；Fakuma 目录邮箱未二次核验者未标 high

### 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `data/germany_raw/batch75dir_seeds.json`
- `data/germany_raw/batch75dir_hits.json` / `batch75dir_verified.json`
- `data/germany_raw/batch75dir_merge_log.json`
- `data/germany_raw/batch75dir_impressum_*.json`
- `data/germany_raw/batch75dir_fakuma_de_parsed.json`
- `data/germany_raw/batch75dir_new_domains.txt`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**352** 待 Impressum）

### 状态

目录/展会轨 Batch75dir 已交付：**219** 封核验入库邮箱，**614** 新域名种子，队列仍有 **352** 可续跑。
