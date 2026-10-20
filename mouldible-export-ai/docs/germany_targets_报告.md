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
