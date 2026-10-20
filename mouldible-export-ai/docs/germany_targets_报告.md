# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 78）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **2720** |
| 本轮净增（相对目录 Batch78dir 合并后基线 2706） | **+14** |
| 本轮因已在 master/targets 跳过 | **2** |
| 本轮质量剔除（死站/错垂/cloak 等） | **9** |
| 其中 high / medium | **2551** / **169** |
| 唯一域名 | **1872** |
| 非 .de 邮箱（累计） | **586** |
| 含电话 / 含城市 | **2414** / **2509** |
| 本轮新域名贡献 | **5** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2492** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 78 · Website/named Kontakt）

1. **基线**：目录 Batch78dir 合并后 **重读 CSV** → **2706 / 1867**，再合并本轮。
2. **Expand 队列**：仍空；~75 single-email peers wave1 探针多为 info@-only → **+0 named**。
3. **Named Kontakt / Web 定向**：
   - Betz Wernberg-Köblitz `vertrieb@betz-wzb.de`（Florian Betz GF/Vertrieb；info@ 已在 targets）
   - REBHAN Kronach Ansprechpartner（info@ + Löffler Vertrieb / Welsch Blasformen / Bayer·Trebes Auftragsbearbeitung；Personal/Rechnung 剔除；无角色 mailto 剔除）
   - ECHO Steinfeld Kontakt（info@ + Chodura / König Vertrieb / Rausch）
   - Funke Heiligenhaus Impressum `info@funke-werkzeugbau.de`
   - Future Inside Schömberg Formenbau（william.thier@ + info@）
   - SWO Oberau 补 `info@swo-formenbau.de`（已有 bettina.weiss@）
4. **质量门**：Personal/Rechnungswesen；无角色 orphan mailto；cloak（ABAS/Hack/Croner/RFK）；master skip；空站（cc-bark）。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| wave1 single-email peers | ~75 | **+0** |
| named Kontakt / 定向 Web | Betz·Rebhan·Echo·Funke·Future·SWO | **+14** |

### 本轮新增（+14）

- `vertrieb@betz-wzb.de` · Wernberg-Köblitz · Florian Betz · high
- `info@rebhan-wzb.de` · Kronach ·  · high
- `mloeffler@rebhan-wzb.de` · Kronach · Michael Löffler · high
- `fwelsch@rebhan-wzb.de` · Kronach · Frank Welsch · high
- `cbayer@rebhan-wzb.de` · Kronach · Christian Bayer · high
- `strebes@rebhan-wzb.de` · Kronach · Sandra Trebes · high
- `info@echo-werkzeugbau.de` · Steinfeld ·  · high
- `ewald.chodura@echo-werkzeugbau.de` · Steinfeld · Ewald Chodura · high
- `elisabeth.koenig@echo-werkzeugbau.de` · Steinfeld · Elisabeth König · high
- `arnulf.rausch@echo-werkzeugbau.de` · Steinfeld · Arnulf Rausch · high
- `info@funke-werkzeugbau.de` · Heiligenhaus · Dennis Funke · high
- `william.thier@future-inside.de` · Schömberg · William Thier · high
- `info@future-inside.de` · Schömberg ·  · high
- `info@swo-formenbau.de` · Oberau ·  · high

### 本轮新域名

- `betz-wzb.de`
- `echo-werkzeugbau.de`
- `funke-werkzeugbau.de`
- `future-inside.de`
- `rebhan-wzb.de`

### skipped-already-known（2）

`info@betz-wzb.de`, `info@grobusch.de`

### 质量剔除（节选）

**9**：Rebhan Personal/Rechnung；abrueckner/rvoelk 无角色；Grobusch master；cc-bark 空站；future-inside.eu 未确认；wave1 junk；ABAS/Hack/Croner/RFK cloak…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch78_new_verified.json`
- `data/germany_raw/batch78_expand_results.json`
- `data/germany_raw/batch78_merge_log.json`
- `data/germany_raw/batch78_candidates.json` / `batch78_probe_wave1.json`
- `data/germany_raw/batch78_quality_drops.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B79：empty expand）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；wave1 对已有单邮箱 peers 几乎无新 named。B79 继续 named Kontakt（剩余 peers；ABAS/Hack/Croner/RFK cloak 观察；Grobusch/cc-bark 若站恢复可重试）。


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

## 目录/展会轨 Batch79dir

> 续跑队列 ~110；合并前重读 CSV（Website B78 后基线 **2720** / **1872** 域名）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2808** |
| high / medium | **2636** / **172** |
| 唯一域名 | **1948** |
| 含电话 / 含城市 | **2478** / **2580** |
| 非 .de 邮箱 | **619** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2580** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

### 本轨成果（Batch79dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **110** |
| 有邮箱命中 | **79** |
| 本轨净增邮箱 | **88**（high **85** / medium **3**） |
| 相对 Website B78 基线 2720 | **+88** |
| WLW 再播种（p29–36 + 扩类） | **119** |
| 队列剩余 | **118** |

### 方法

1. 排空上轮 110 域名 → Impressum/Kontakt  
2. append-dedupe（Website B78 并行后重读 CSV）  
3. WLW p29–36 + formteile 等再播种

### 本轨新增邮箱（节选前 25 / 共 88）

- `sales@allucan.ch`
- `alu@allucan.ch`
- `info@zwei-r.com`
- `info@3dmensionals.de`
- `angebote@3dmensionals.de`
- `info@tielke.de`
- `info@antares-industrietechnik.de`
- `askagmbhcokg@as-ka.de`
- `info@as-ka.de`
- `info@anlagenmontage-hippe.de`
- `kontakt@3dprintedparts.de`
- `contact@airloc.com`
- `kontakt@fertigungscenter.at`
- `info@addtec.eu`
- `a.nebert@addtec.eu`
- `info@band.ch`
- `info@aston.de`
- `info@royersignal.de`
- `info@beyergmbh.de`
- `info@amco-plast.de`
- `info@bdg-online.de`
- `service@bdg-online.de`
- `info@besche.de`
- `christine.behrens@besche.de`
- `susanne.grimme@besche.de`
… 另有 63 个，见 `data/germany_raw/batch79dir_hits.json`

### 本轨新域名（节选）

`3d-druck-dilba.de`, `3dmensionals.de`, `3dprintedparts.de`, `addtec.eu`, `airloc.com`, `allucan.ch`, `amco-plast.de`, `anlagenmontage-hippe.de`, `antares-industrietechnik.de`, `aqualonwaterjet.se`, `as-ka.de`, `aston.de`, `autmaring.eu`, `band.ch`, `bbk-kunststofftechnik.de`, `bdg-online.de`, `besche.de`, `beyergmbh.de`, `blombach-spindeln.de`, `bm-engineering.eu`…

### 产物

- `data/germany_targets.csv` / `.xlsx`
- `data/germany_raw/batch79dir_impressum.json`
- `data/germany_raw/batch79dir_verified.json` / `batch79dir_hits.json`
- `data/germany_raw/batch79dir_merge_log.json` / `batch79dir_reseed.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`（**118**）

### 状态

Batch79dir 完成：**+88** 邮箱；队列 **118** 待 Batch80dir。
