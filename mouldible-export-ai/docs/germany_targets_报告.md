# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 77）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **2612** |
| 本轮净增（相对目录 Batch77dir 合并后基线 2586） | **+26** |
| 本轮因已在 master/targets 跳过 | **10** |
| 本轮质量剔除（死站/错垂/cloak 等） | **11** |
| 其中 high / medium | **2453** / **159** |
| 唯一域名 | **1793** |
| 非 .de 邮箱（累计） | **548** |
| 含电话 / 含城市 | **2330** / **2428** |
| 本轮新域名贡献 | **2** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2384** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 77）

1. **基线**：目录 Batch77dir 合并后 **重读 CSV** → **2586 / 1791**，再合并本轮。
2. **Expand 队列**：仍空；master-seed ~33 DE peer 域名多数死站 → **+0**。
3. **Named Kontakt**：
   - Güthner Oberrot（info@ + Manfred / Markus；Verwaltung 剔除）
   - Wefo Inden Ansprechpartner（Ruhwiedel / Weiland / Gatzweiler；Assistentin 剔除）
   - MM Formenbau Heiligenhaus `info@mm-formenbau.de`
   - priomold Schömberg Ansprechpartner（11 named；Rechnung 剔除）
   - Moldingtec Steinberg Kontakt（6 named）
   - Servomold Erbach sales@ / service@
4. **质量门**：Verwaltung/Assistentin/Buchhaltung/Personal；cloak；dead master-seed。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| expand / master-seed Impressum | ~33 | **+0** |
| named Kontakt | 多轮 | **+26** |

### 本轮新增（+26）

- `info@guethner-gmbh.de` · Oberrot-Marbächle ·  · high
- `manfred.guethner@guethner-gmbh.de` · Oberrot-Marbächle · Manfred Güthner · high
- `markus.visser@guethner-gmbh.de` · Oberrot-Marbächle · Markus Visser · high
- `mario.ruhwiedel@wefo.com` · Inden · Mario Ruhwiedel · high
- `nils.weiland@wefo.com` · Inden · Nils Weiland · high
- `thomas.gatzweiler@wefo.com` · Inden · Thomas Gatzweiler · high
- `info@mm-formenbau.de` · Heiligenhaus · Michael Müller · high
- `t.camek@priomold.de` · Schömberg · Tobias Camek · high
- `t.green@priomold.de` · Schömberg · Tom Green · high
- `s.geist@priomold.de` · Schömberg · Stefan Geist · high
- `m.oezdemir@priomold.de` · Schömberg · Murat Özdemir · high
- `s.scherer@priomold.de` · Schömberg · Sebastian Scherer · high
- `d.jensen@priomold.de` · Schömberg · Daniel Jensen · high
- `m.krebs@priomold.de` · Schömberg · Matthias Krebs · high
- `k.konusch@priomold.de` · Schömberg · Kevin Konusch · high
- `s.oezkorucu@priomold.de` · Schömberg · Sitav Özkorucu · high
- `n.schmidt@priomold.de` · Schömberg · Nils Schmidt · high
- `r.frey@priomold.de` · Schömberg · Regina Frey · high
- `monty.tepper@moldingtec.de` · Steinberg · Monty Tepper · high
- `ralf.singer@moldingtec.de` · Steinberg · Ralf Singer · high
- `sandy.hoera@moldingtec.de` · Steinberg · Sandy Höra · high
- `thomas.riedel@moldingtec.de` · Steinberg · Thomas Riedel · high
- `thomas.schneider@moldingtec.de` · Steinberg · Thomas Schneider · high
- `torsten.meyer@moldingtec.de` · Steinberg · Torsten Meyer-Quendt · high
- `sales@servomold.com` · Erbach ·  · high
- `service@servomold.com` · Erbach ·  · high

### 本轮新域名

- `guethner-gmbh.de`
- `mm-formenbau.de`

### skipped-already-known（10）

`bettina.weiss@swo-formenbau.de`, `info@ghd-formenbau.de`, `info@moldingtec.de`, `info@mouldtec.de`, `info@mp-werkzeugbau.de`, `info@priomold.de`, `info@servomold.com`, `info@wefo.com`, `info@will-werkzeugbau.de`, `office@i-mold.com`

### 质量剔除（节选）

**11**：Güthner Verwaltung；Wefo Assistentin；priomold Rechnung；mouldtec Personal；master-seed dead；ABAS/Hack/Croner/RFK/Ruhla cloak…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch77_new_verified.json`
- `data/germany_raw/batch77_expand_results.json`
- `data/germany_raw/batch77_merge_log.json`
- `data/germany_raw/batch77_probe_seeds.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B78：empty expand）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；master-seed DE peers 大多死站。B78 继续 named Kontakt（剩余 single-email peers；ABAS/Hack/Croner/RFK cloak 观察）。


---

## 目录/展会轨 Batch78dir

> 续跑队列 ~123；合并前重读 CSV（Website B77 后基线 **2612** / **1793** 域名）。

### 累计（合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **2706** |
| high / medium | **2537** / **169** |
| 唯一域名 | **1867** |
| 含电话 / 含城市 | **2401** / **2495** |
| 非 .de 邮箱 | **586** |

### 按 icp_tag（累计）

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

Batch78dir 完成：**+94** 邮箱；队列 **110** 待 Batch79dir。
