# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 79）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **2824** |
| 本轮净增（相对目录 Batch79dir 合并后基线 2808） | **+16** |
| 本轮因已在 master/targets 跳过 | **0** |
| 本轮质量剔除（死站/错垂/cloak 等） | **11** |
| 其中 high / medium | **2652** / **172** |
| 唯一域名 | **1950** |
| 非 .de 邮箱（累计） | **620** |
| 含电话 / 含城市 | **2494** / **2596** |
| 本轮新域名贡献 | **2** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **2596** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 79 · Website/named Kontakt）

1. **基线**：目录 Batch79dir 合并后 **重读 CSV** → **2808 / 1948**，再合并本轮。
2. **Expand 队列**：仍空；wave1 ~60 + wave2 部分 single-email peers → 几乎无新 named（junk/DPO only）。
3. **Named Kontakt / Web 定向**：
   - HAAG Präzisionsformen Schorndorf Ansprechpartner（info@ + Rainer/Steffen Vertrieb + Andreas Projektmanagement）
   - OPUS Schönau `info@opus-mold.de`（Kontakt+Impressum）
   - Zimmermann/ziform Gladenbach `jens.meier@` Vertrieb/Projektleitung
   - Haselbeck Deggendorf 补 Stefan Ruh / Andreas Thoma（已有 Geiger）
   - WESKO Stollberg Ansprechpartner ×8（GF/Sales/Vertrieb/Werkzeugbau/Spritzguss/Technik；Finanzen/Personal 剔除）
4. **质量门**：Einkauf/Buchhaltung/Personal；cloak（FBB/ABAS/Hack/Croner/RFK）；dead Cloudflare（buck-formenbau）；无角色；DPO。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| wave1/2 single-email peers | ~110 | **+0** usable |
| named Kontakt / 定向 Web | HAAG·OPUS·ziform·Haselbeck·WESKO | **+16** |

### 本轮新增（+16）

- `info@haag-formen.de` · Schorndorf ·   · high
- `rainer.haag@haag-formen.de` · Schorndorf · Rainer Haag · high
- `steffen.kientz@haag-formen.de` · Schorndorf · Steffen Kientz · high
- `andreas.haag@haag-formen.de` · Schorndorf · Andreas Haag · high
- `info@opus-mold.de` · Schönau ·   · high
- `jens.meier@ziform.com` · Gladenbach · Jens Meier · high
- `stefan.ruh@haselbeck.de` · Deggendorf · Stefan Ruh · high
- `andreas.thoma@haselbeck.de` · Deggendorf · Andreas Thoma · high
- `andreas.ebert@wesko-gmbh.de` · Stollberg · Dr. Andreas Ebert · high
- `kai.reisner@wesko-gmbh.de` · Stollberg · Kai Reisner · high
- `felix.vogel@wesko-gmbh.de` · Stollberg · Felix Vogel · high
- `florian.patzer@wesko-gmbh.de` · Stollberg · Florian Patzer · high
- `heiko.uhlmann@wesko-gmbh.de` · Stollberg · Heiko Uhlmann · high
- `heiko.lehm@wesko-gmbh.de` · Stollberg · Heiko Lehm · high
- `andre.haertel@wesko-gmbh.de` · Stollberg · André Härtel · high
- `norman.mueller@wesko-gmbh.de` · Stollberg · Norman Müller · high

### 本轮新域名

- `haag-formen.de`
- `opus-mold.de`

### skipped-already-known（0）

（无）

### 质量剔除（节选）

**11**：WESKO Finanzen/Personal/无角色；Thenhausen Einkauf/Buchhaltung；Haselbeck Greil 未在本轮页面；buck-formenbau Cloudflare 520；FBB/ABAS/Hack/Croner/RFK cloak；wave junk/DPO…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch79_new_verified.json`
- `data/germany_raw/batch79_expand_results.json`
- `data/germany_raw/batch79_merge_log.json`
- `data/germany_raw/batch79_candidates.json` / `batch79_probe_wave1.json`
- `data/germany_raw/batch79_quality_drops.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B80：empty expand）

---

## 4. 状态

**应有尽有 — 尚未完成。** Expand 仍空；single-email peers 探针饱和。B80 继续 named Kontakt（剩余 peers；cloak 观察；buck-formenbau 若站恢复可重试）。


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

