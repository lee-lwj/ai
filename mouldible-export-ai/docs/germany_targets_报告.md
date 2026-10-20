# Germany ICP Targets — 报告

## 1. 累计交付数量（如实，至 Batch 74）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数（累计） | **1903** |
| 本轮净增（相对 Batch 73 的 1881） | **+22** |
| 本轮因已在 master/targets/pilot 跳过 | **43** |
| 本轮质量剔除（死站/错垂/cloak 等） | **14** |
| 其中 high / medium | **1798** / **105** |
| 唯一域名 | **1347** |
| 非 .de 邮箱（累计） | **256** |
| 含电话 / 含城市 | **1669** / **1761** |
| 本轮新域名贡献 | **4** |

### 按 `icp_tag`（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **1675** |
| design_studio | **129** |
| oem_buyer | **69** |
| sourcing | **30** |

---

## 2. 本轮方法（Batch 74）

1. **Expand**：`croner-formenbau.de` → 401（全路径）+ Wayback CDX 空；第三方 Netzwerk 有 `w.croner@` / `bewerbung@` 但**不可同域核验** → **+0**（drained）。
2. **目录/named**：HWF Jelinek；Eckerle Brosig/Rieder/Balo/Gilch；WB GmbH 六人；HEIM Coburg；Formtech Hilmer/Stettmer；Merschbrock Vertrieb；Wartenfelser QS/Instandhaltung；Oelrich `px-spritzgussformen.com`（DE-proven）。
3. **质量门**：Croner third-party；Wetec Handel；Coregenion agency；Eckerle Einkauf/Lack；Formzeug Logistik；Wartenfelser Buchhaltung/Logistik；AUT-FIT Stanz。

| 来源 | 尝试 | 可用命中 |
|---|---:|---:|
| expand 队列 | 1 | **+0** |
| directory / named Kontakt | 多轮 | **+22** |

### 本轮新增（+22）

- `m.jelinek@hwf-werkzeugbau.de` · Eppertshausen · high
- `c.brosig@eckerle-gmbh.de` · Beilngries · high
- `d.rieder@eckerle-gmbh.de` · Beilngries · high
- `m.balo@eckerle-gmbh.de` · Beilngries · high
- `h.gilch@eckerle-gmbh.de` · Beilngries · high
- `j.meli@wb-gmbh.de` · Bad Endorf · high
- `g.hartl@wb-gmbh.de` · Bad Endorf · high
- `s.murner@wb-gmbh.de` · Bad Endorf · high
- `c.schaffer@wb-gmbh.de` · Bad Endorf · high
- `a.schuhbeck@wb-gmbh.de` · Bad Endorf · high
- `f.angerer@wb-gmbh.de` · Bad Endorf · high
- `info@heim-werkzeugbau.de` · Coburg · high
- `detlef.mueller@heim-werkzeugbau.de` · Coburg · high
- `franz.hilmer@formtech-gmbh.de` · Niederwinkling · high
- `martin.stettmer@formtech-gmbh.de` · Niederwinkling · high
- `sebastian.hilmer@formtech-gmbh.de` · Niederwinkling · high
- `vertrieb@merschbrock.de` · Verl · high
- `bauer@wartenfelser.de` · Hemhofen · high
- `chomitsch@wartenfelser.de` · Hemhofen · high
- `goetz@wartenfelser.de` · Hemhofen · high
- `protzer@wartenfelser.de` · Hemhofen · high
- `oelrich@px-spritzgussformen.com` · Kaarst · high

### 本轮新域名

- `heim-werkzeugbau.de`
- `merschbrock.de`
- `px-spritzgussformen.com`
- `wb-gmbh.de`

### skipped-already-known（43）

`info@croner-formenbau.de`, `info@wisa-formenbau.de`, `info@fb-knott.de`, `info@norik.de`, `info@tooltec-spritzgusswerkzeuge.de`, `info@hwf-werkzeugbau.de`, `vertrieb@hwf-werkzeugbau.de`, `m.fischer@hwf-werkzeugbau.de`, `a.jakob@hwf-werkzeugbau.de`, `k.kretzschmar@hwf-werkzeugbau.de`, `s.hermanns@hwf-werkzeugbau.de`, `t.eckert@hwf-werkzeugbau.de`, `m.schmidt@hwf-werkzeugbau.de`, `r.maiwald@hwf-werkzeugbau.de`, `u.karg@hwf-werkzeugbau.de`, `info@eckerle-gmbh.de`, `a.eckerle@eckerle-gmbh.de`, `j.eckerle@eckerle-gmbh.de`, `j.schneider@eckerle-gmbh.de`, `f.pfahler@eckerle-gmbh.de`, `m.schmid@eckerle-gmbh.de`, `s.obermeyer@eckerle-gmbh.de`, `info@wb-gmbh.de`, `zentrale@formtech-gmbh.de`, `info@formtech-gmbh.de`…

### 质量剔除（节选）

**14**：Croner 401/third-party；Wetec Handel；Coregenion agency；Blank Einkauf；Lack；Formzeug Logistik；Wartenfelser Buchhaltung/Logistik；AUT-FIT Stanz；FBB cloaked named…

---

## 3. 产物路径

- `data/germany_targets.csv` / `data/germany_targets.xlsx`
- `docs/germany_targets_报告.md`
- `data/germany_raw/batch74_new_verified.json`
- `data/germany_raw/batch74_expand_results.json`
- `data/germany_raw/batch74_merge_log.json`
- `data/germany_raw/queue_expand_de_remaining.txt`（B75：empty — no real expand seed）

---

## 4. 状态

**应有尽有 — 尚未完成。** Croner expand 已排空；名录/named 仍有空间；B75 继续 directory reseed + named Kontakt。
