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
