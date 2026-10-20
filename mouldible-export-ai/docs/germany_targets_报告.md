## Website/named Kontakt Batch 128

> 合并前重读 CSV（任务初口径 **4456** / **3130** domains ~**3140** hosts；Directory Batch133dir 未再抬升）。本批按 live 合并，网站轨净增 **+10** → **4466** / **3133** domains (~**3144** hosts)。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4466** |
| high / medium | **4186** / **280** |
| 唯一域名（domain 列） | **3133** |
| 唯一邮箱主机（@host） | **3144** |
| 含电话 / 含城市 | **3850** / **3951** |
| 非 .de 邮箱 | **1186** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4108** |
| design_studio | **193** |
| oem_buyer | **130** |
| sourcing | **35** |

### 本批网站轨净增 **+10**（相对写时基线 4456）

- `alex.basistow@abas-werkzeugbau.de` — ABAS Werkzeug & Formenbau GmbH (Fulda) — `overseas_peer_overflow` / high — Alex Basistow (GF)
- `alexander.hamm@abas-werkzeugbau.de` — ABAS (Fulda) — `overseas_peer_overflow` / high — Alexander Hamm (Leitung Produktion)
- `willi.sawatzky@abas-werkzeugbau.de` — ABAS (Fulda) — `overseas_peer_overflow` / high — Willi Sawatzky (Leitung Konstruktion)
- `info@vema-gmbh.de` — VEMA plastineers² GmbH (Krauchenwies-Göggingen) — `oem_buyer` / high — Werner/Christian Veser
- `info@kb-das.de` — Konstruktionsbüro David Schuster (Pfofeld-Rehenbühl) — `design_studio` / high — David Schuster
- `info@eberle-spritzgiesstechnik.de` — Eberle Spritzgiesstechnik GmbH (Niedernhall) — `oem_buyer` / high — Frank Eberle
- `info@kt-breitungen.de` — Kunststofftechnik Breitungen GmbH & Co. KG (Breitungen) — `oem_buyer` / high
- `corinna.holland-moritz@kt-breitungen.de` — KTB Breitungen — `oem_buyer` / high — Corinna Holland-Moritz (GF & QM)
- `ronny.knott@kt-breitungen.de` — KTB Breitungen — `oem_buyer` / high — Ronny Knott (GF & Leiter Produktion)
- `sven.sauerbrey@kt-breitungen.de` — KTB Breitungen — `overseas_peer_overflow` / high — Sven Sauerbrey (Leiter Werkzeugbau)

### 本批质量剔除（节选）

- `Formacon j.sancar@` — SKIP site still unreachable — never invent; carry recovery
- `ABAS andreas.boschmann@` — DROP Kaufmännische Leitung
- `ABAS karl.menrad@ / viktor.sawatzky@` — SKIP invent / orphan JS
- `Finke Formenbau plain mailto` — SKIP no plain company-site mailto
- `CAD-KON / Reddikowsky / Dobener / ck-form` — SKIP dead / Aufmass off-ICP
- `invent g.helm@lh` — SKIP invent
- `Beck Plastics / beck-brehm` — SKIP joomla cloak (plain-only hint)
- `formenbau-rapp / auer / kb-sprung / heise / mohr / hochstadter / jordan` — SKIP 403/dead
- `h.wirth@werkzeugbau-wirth` — DROP Bewerbung-only
- `KTB auftragsbearbeitung@ / versand@` — DROP Buchhaltung / Versand
- `wetec.de / wetec-bauteilfertigung` — DROP non-ICP (Elektronikhandel / CNC-Ersatzteil)
- `FINI / Kroeger named` — SKIP already known

### 产物

- `data/germany_raw/batch128_new_verified.json`
- `data/germany_raw/batch128_quality_drops.json`
- `data/germany_raw/batch128_merge_log.json`
- `data/germany_raw/batch128_candidates_final.json`
- `data/germany_raw/batch129_queue_note.txt`

_报告更新：2026-10-21 05:55 Asia/Hong_Kong_

---

## Website/named Kontakt Batch 127

> 合并前重读 CSV（任务初口径 **4429** / **3119**；Directory Batch132dir steering → 写时 live **4450** / **3136**）。本批按 live 合并，网站轨净增 **+6** → 瞬时 **4456** / **3140**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4456** |
| high / medium | **4176** / **280** |
| 唯一域名 | **3140** |
| 含电话 / 含城市 | **3840** / **3941** |
| 非 .de 邮箱 | **1186** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4104** |
| design_studio | **192** |
| oem_buyer | **125** |
| sourcing | **35** |

### 本批网站轨净增 **+6**（相对写时基线 4450）

- `info@flicks-cad.de` — FLICKS-CAD Wolfgang Flickschuh (Suhl-Albrechts) — `design_studio` / high — Wolfgang Flickschuh
- `post@mertgens.de` — G. Mertgens & Co. GmbH (Meinerzhagen) — `oem_buyer` / high — Dominik Mertgens
- `tschorn@canto-web.de` — canto Ing. GmbH (Lüdenscheid) — `overseas_peer_overflow` / high — Hagen Tschorn
- `schulte@canto-web.de` — canto Ing. GmbH (Lüdenscheid) — `overseas_peer_overflow` / high — Hendrik Schulte
- `a.wienand@dietrich-gruppe.com` — Dietrich Formenbau (Dietrich Gruppe) (Lüdenscheid) — `overseas_peer_overflow` / high — André Wienand
- `info@aluconcept.com` — AluConcept AG (Dinslaken) — `oem_buyer` / high — Frank Hellmich

### 本批质量剔除（节选）

- `Formacon j.sancar@` — SKIP site still unreachable — never invent; carry recovery
- `Finke Formenbau plain mailto` — SKIP no plain company-site mailto
- `ABAS Fulda named` — SKIP Cloudflare 526 / only known info@
- `CAD-KON / Reddikowsky / Dobener / ck-form` — SKIP dead/unreachable
- `invent g.helm@lh` — SKIP invent
- `Beck Plastics` — SKIP joomla-hidden-mail cloak (plain-only hint)
- `formenbau-rapp / auer-formenbau / kb-sprung` — SKIP 403/unreachable
- `heise-formenbau / detlefmohr-cad / hochstadter` — SKIP dead
- `spritzgusswerkzeug-konstruktion.de` — DROP CH/AT-leaning prior pattern
- `l.graeve@dietrich-gruppe` — DROP Verwaltung
- `FINI / zi-systeme / krauss / Rosenberger` — SKIP already known

---

## 目录/展会轨 Batch132dir

> 合并前重读 CSV（直播基线 **4429** / **3108**；Website Batch126 steering +4）。合并后基线：**4450** / **3126**（hosts ~3136）。

### 累计（Batch132dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4450** |
| high / medium | **4170** / **280** |
| 唯一域名 | **3126** |
| 含电话 / 含城市 | **3834** / **3935** |
| 非 .de 邮箱 | **1184** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4101** |
| design_studio | **191** |
| oem_buyer | **123** |
| sourcing | **35** |

### 本轨成果（Batch132dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **207** |
| 有邮箱命中 | **69** |
| 本轨净增邮箱 | **21**（high **21** / medium **0**） |
| 相对基线 4429/3108 | **+21** / **+18** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B131 域名队列 | 空 |
| Allgäu/Oberland/Chiemgau/Bayerischer Wald 微城 × kw | 有效（150 城，DDG/Bing 598 + Maps/EP/GS） |
| Bing Maps / Europages / Gelbe Seiten | 部分（maps 72 / ep 18 / gs 15） |
| WebSearch 具名解析 | GERG/Förster/Frank/Pfaff/Vorbach/OptiCAMMS/ERBIWA/List/Osbra/Siller/MB/Günther 等 |
| Fakuma/VDWF / WLW | 未用 / 跳过 |
| 产量 | 207 候选核验 / 69 命中 / 质量门后 **+21**；剔 Blechumform/Druckguss/Galvanik/玻璃/橡胶/SEA-freelancer/协会/Verwaltung |

### 本轨新增邮箱（共 21）

- `info@kve-kunststofftechnik.de` (high, overseas_peer_overflow) · Teisendorf
- `info@kurz-gerhard.de` (high, overseas_peer_overflow) · Kaufbeuren-Neugablonz
- `info@hitex-ag.de` (high, overseas_peer_overflow) · Tittmoning
- `info@erbiwa.com` (high, overseas_peer_overflow) · Lindenberg im Allgäu
- `info@gerg.de` (high, overseas_peer_overflow) · Hohenthann
- `info@angermaiergmbh.de` (high, overseas_peer_overflow) · Bad Aibling
- `info@waltergmbh.eu` (high, overseas_peer_overflow) · Oberstdorf
- `info@formenbau-olinger.de` (high, overseas_peer_overflow) · Zwiesel
- `info@hummel-kunststofftechnik.de` (high, overseas_peer_overflow) · Schonach
- `office@sperrer-gmbh.de` (high, overseas_peer_overflow) · Freilassing
- `info@siller-technik.com` (high, overseas_peer_overflow) · Brannenburg
- `martin.siller@siller-technik.com` (high, overseas_peer_overflow) · Brannenburg
- `johanna.siller@siller-technik.com` (high, overseas_peer_overflow) · Brannenburg
- `info@coregenion.de` (high, overseas_peer_overflow) · Viechtach
- `info@heinzsimon.de` (high, overseas_peer_overflow) · Kaufbeuren
- `hello@gadgetto-manufacturing.com` (high, overseas_peer_overflow) · München
- `info@draexlmaier.com` (high, oem_buyer) · Vilsbiburg
- `werkzeugbau@fischer.de` (high, overseas_peer_overflow) · ?
- `info@hergil.de` (high, overseas_peer_overflow) · Schwaigern
- `tobias.gilbert@hergil.de` (high, overseas_peer_overflow) · Schwaigern
- `akzentrale@ak-kunststoff.de` (high, overseas_peer_overflow) · Isernhagen

### 产物

- `data/germany_raw/batch132dir_*.json`
- `data/germany_raw/batch132dir_next_search_seeds.json`

### 状态

Batch132dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch133dir（下一城带：Lüneburger Heide/Elbe-Weser/Ostfriesland）。全国目录轨饱和仍高，本带仍挖出 **+21** 新邮（含 KVE Teisendorf、Hitex Tittmoning、ERBIWA Lindenberg、Angermaier Bad Aibling、Olinger Zwiesel、Siller Brannenburg、Heinz Simon Kaufbeuren、DRÄXLMAIER Vilsbiburg OEM、Walter Oberstdorf、WeForm/Coregenion Viechtach 等）。多数带内大户已在库（opticamms/frank/pfaff/mueller-mf/list/stocker/langer/vorbach/mb-spritz）。

---
## Website/named Kontakt Batch 126

> 合并前重读 CSV（任务初口径 **4399** / **3080**；Directory Batch131dir steering → 写时 live **4425** / **3116**）。本批按 live 合并，网站轨净增 **+4** → 瞬时 **4429** / **3119**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4429** |
| high / medium | **4149** / **280** |
| 唯一域名 | **3119** |
| 含电话 / 含城市 | **3823** / **3915** |
| 非 .de 邮箱 | **1177** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4081** |
| design_studio | **191** |
| oem_buyer | **122** |
| sourcing | **35** |

### 本批网站轨净增 **+4**（相对写时基线 4425）

- `andreas.rudolph@cad-rudolph.de` — CAD-CAM Technologie Andreas Rudolph (Römerstein-Zainingen) — `design_studio` / high — Andreas Rudolph
- `info@solsec.de` — SOLSEC GmbH (Bobingen) — `design_studio` / high — Alexander Stotz / Ioannis Choumetis
- `info@kuehnlein-gmbh.de` — Karl Kühnlein GmbH (Mammendorf) — `oem_buyer` / high — Klaus Kühnlein
- `info@klaeger.de` — Kläger Spritzguss GmbH & Co. KG (Dornstetten) — `overseas_peer_overflow` / high

### 本批质量剔除（节选）

- `Formacon j.sancar@` — SKIP site still unreachable — never invent; carry recovery
- `FLICKS-CAD` — SKIP phone-only / E-Mail: Kontakt cloak
- `Finke Formenbau plain mailto` — SKIP no plain company-site mailto
- `ABAS Fulda named` — SKIP Cloudflare / only known info@
- `CAD-KON named beyond team_` — SKIP; `mail@cad-kon.com` Aufmass off-ICP
- `Reddikowsky / Dobener / ck-form.de` — SKIP dead/unreachable
- `invent g.helm@lh` — SKIP invent
- `THB Konstruktionsbüro` — DROP Stanz/Umform-primary
- `BWF Holzkirchen info@bwf-gmbh.de` — DROP Alu-CNC / not plastics Formenbau
- `c.bosch@klaeger` — DROP Beschaffung/Einkauf
- `antje.knoth@vorbach` — DROP Finanzen/Personal
- `job@haenel` — DROP Bewerbung
- `Beck Plastics` — SKIP cloak / no plain mailto
- `formenbau-rapp / auer-formenbau` — SKIP 403/unreachable
- `Gerken continuum` — DROP Stanz/Umform avoid

---

## Website/named Kontakt Batch 125

> 合并前重读 CSV（任务初口径 **4361** / **3052**；Directory Batch130dir steering → 写时 live **4391** / **3078**）。本批按 live 合并，网站轨净增 **+8** → 瞬时 **4399** / **3080**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4399** |
| high / medium | **4119** / **280** |
| 唯一域名 | **3080** |
| 含电话 / 含城市 | **3799** / **3886** |
| 非 .de 邮箱 | **1171** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4056** |
| design_studio | **189** |
| oem_buyer | **119** |
| sourcing | **35** |

### 本批网站轨净增 **+8**（相对写时基线 4391）

- `info@bergcad.de` — Berg Technologie GmbH (Bad Lippspringe) — `overseas_peer_overflow` / high — Wladimir Berg
- `info@bergcad.com` — Berg Technologie GmbH (Bad Lippspringe) — `overseas_peer_overflow` / high — Wladimir Berg
- `service@alento.eu` — Alento GmbH (Ebersberg) — `oem_buyer` / high — Manfred Zoss
- `matthias.dueran@haller-lahr.de` — Willi Haller GmbH (Lahr) — `overseas_peer_overflow` / high — Matthias Düran
- `oliver.danner@haller-lahr.de` — Willi Haller GmbH (Lahr) — `overseas_peer_overflow` / high — Oliver Danner
- `ralf.woelfle@haller-lahr.de` — Willi Haller GmbH (Lahr) — `overseas_peer_overflow` / high — Ralf Wölfle
- `alexander.weiss@haller-lahr.de` — Willi Haller GmbH (Lahr) — `overseas_peer_overflow` / high — Alexander Weiß
- `info@stolz-seng.de` — Stolz & Seng (Donaueschingen) — `oem_buyer` / high

### 本批质量剔除（节选）

- `Formacon j.sancar@` — SKIP site still unreachable — never invent; carry recovery
- `FLICKS-CAD` — SKIP phone-only / E-Mail anzeigen cloak
- `Finke Formenbau plain mailto / Privacy JS-split` — SKIP no plain company-site mailto
- `ABAS Fulda named` — SKIP Cloudflare 526 / only known info@
- `CAD-KON named beyond team_` — SKIP known
- `Reddikowsky / Dobener / ck-form.de` — SKIP dead/unreachable
- `invent g.helm@lh` — SKIP invent
- `Conrad Formenbau+Druckguss` — DROP Druckguss-primary (Zink)
- `Sieberkon / spritzgusswerkzeug-konstruktion` — DROP CH/AT-only
- `SCK Schneider CAD` — DROP aerospace-primary off-ICP
- `miriam.koessler@ / roland.hallmann@ haller` — DROP Einkauf / Finanzen+Personal
- `schell-connect` — DROP Stanz/connector
- `Gerken continuum` — DROP Stanz/Umform avoid

---

## Website/named Kontakt Batch 124

> 合并前重读 CSV（任务口径 **4356** / **3047**；Directory Batch130dir 未抬升 live）。本批按 live 合并，网站轨净增 **+5** → 瞬时 **4361** / **3052**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4361** |
| high / medium | **4081** / **280** |
| 唯一域名 | **3052** |
| 含电话 / 含城市 | **3765** / **3848** |
| 非 .de 邮箱 | **1163** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4023** |
| design_studio | **186** |
| oem_buyer | **117** |
| sourcing | **35** |

### 本批网站轨净增 **+5**（相对写时基线 4356）

- `mp@pauser-weinkauf.de` — pauser + weinkauf Vertrieb GmbH (Bamberg) — `design_studio` / high — Matthias Pauser
- `info@merkel-czeschner.de` — Merkel-Czeschner GmbH (Au am Rhein) — `oem_buyer` / high
- `info@icotek-kunststofftechnik.de` — icotek Kunststofftechnik GmbH (Gaildorf) — `oem_buyer` / high
- `fischer.wzb@t-online.de` — Fischer Formenbau GmbH (Eggenfelden) — `overseas_peer_overflow` / high — Udo Fischer
- `info@plastolen-kf.de` — Plastolen Kunststoffformen GmbH (Dinkelsbühl) — `overseas_peer_overflow` / high — Reinald Weiss

### 本批质量剔除（节选）

- `Formacon j.sancar@formacon.de` — SKIP site still unreachable — never invent; carry recovery
- `FLICKS-CAD` — SKIP phone-only / E-Mail anzeigen cloak
- `Finke Formenbau plain mailto` — SKIP no new plain beyond known finke-gruppe named
- `ABAS Fulda named` — SKIP Cloudflare 526 / only known info@
- `CAD-KON named beyond team_cad-kon@ / webmaster@` — SKIP known; DROP webmaster
- `Reddikowsky / Dobener` — SKIP dead sites
- `invent g.helm@lh` — SKIP invent
- `rommel-formen.de → Haas Metallguss` — DROP Druckguss/Metallguss-primary
- `WIBRA` — SKIP already known
- `ck-form.de` — SKIP unreachable
- `kaysan.t@r-weiss.de` — DROP DSB/third-party on Plastolen Impressum
- `info@icotek.biz` — SKIP secondary brand; keep primary impressum only
- `Gerken continuum` — DROP Stanz/Umform avoid

---

## Website/named Kontakt Batch 123

> 合并前重读 CSV（任务口径 **4333** / **3026**；Directory Batch129dir→写时 live **4351** / **3042**；steering 确认后再读）。本批按 live 合并，网站轨净增 **+5** → 瞬时 **4356** / **3047**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4356** |
| high / medium | **4076** / **280** |
| 唯一域名 | **3047** |
| 含电话 / 含城市 | **3760** / **3843** |
| 非 .de 邮箱 | **1163** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4021** |
| design_studio | **185** |
| oem_buyer | **115** |
| sourcing | **35** |

### 本批网站轨净增 **+5**（相对写时基线 4351）

- `info@irb-werkzeugbau.de` — IRB Werkzeugbau GmbH (Kleinwallstadt) — `overseas_peer_overflow` / high
- `info@polytherm-plastic.com` — POLYTHERM Dipl.-Ing. Horst Sauer GmbH (Aschaffenburg) — `oem_buyer` / high
- `info@cad-konstruktionsbuero.de` — CAD Konstruktionsbüro Dennis Ptach (Hamm) — `design_studio` / high — Dennis Ptach
- `info@johannesmenz.de` — Johannes Menz GmbH (Steinbach-Hallenberg) — `overseas_peer_overflow` / high — Stephan Menz
- `info@lh-konstruktion.de` — LH Werkzeug-Konstruktion GmbH (Flachslanden) — `design_studio` / high — Georg Helm

### 本批质量剔除（节选）

- `a.mueller@ / k.sticker@ mueller-werkzeugbau-gmbh.de` — DROP Buchhaltung/Personal / Einkauf+Fakturierung
- `info@schuetze-seifert.de` — DROP Personaldienstleister off-ICP
- `info@masterformer.de` — DROP beauty/aesthetics wholesaler off-ICP
- `Formacon j.sancar@formacon.de` — SKIP site unreachable — never invent; carry recovery
- `FLICKS-CAD` — SKIP phone-only / E-Mail anzeigen cloak
- `Finke Formenbau plain mailto` — SKIP no plain company-site mailto this run
- `ABAS Fulda named` — SKIP Cloudflare 526 / only known info@
- `webmaster@cadkon-design.com / invent g.helm@` — DROP webmaster; SKIP invent
- `Wenker→growzb already known / Dobener phone-only / Gerken continuum` — SKIP/DROP

---

## Website/named Kontakt Batch 122

> 合并前重读 CSV（任务口径 **4324** / **3018**；Directory Batch127dir→**4327**、Batch128dir→写时 live **4329** / **3023**）。本批按 live 合并，网站轨净增 **+4** → 瞬时 **4333** / **3026**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4333** |
| high / medium | **4053** / **280** |
| 唯一域名 | **3026** |
| 含电话 / 含城市 | **3740** / **3820** |
| 非 .de 邮箱 | **1158** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4003** |
| design_studio | **183** |
| oem_buyer | **112** |
| sourcing | **35** |

### 本批网站轨净增 **+4**（相对写时基线 4329）

- `waldemar.kremer@cad-kremer.de` — CAD Kremer GmbH (Zimmern ob Rottweil) — `design_studio` / high — Waldemar Kremer
- `info@plastium.com` — Plastium GmbH (Lauterbach) — `oem_buyer` / high
- `m.costantino@plastium.com` — Plastium GmbH (Lauterbach) — `oem_buyer` / high — Marco Costantino
- `info@ww-moltics.com` — WERNER WIRTH MOLTICS GmbH (Hamburg) — `overseas_peer_overflow` / high

### 本批质量剔除（节选）

- `Finke Gruppe JS-split emails / info@finke-formenbau.de directory-only` — SKIP cloak invent (JS-split spaces); no plain company-site mailto this run
- `Formacon j.sancar@formacon.de` — SKIP site unreachable (curl 0 / WebFetch 500) — never invent; carry recovery
- `ABAS Fulda named` — SKIP only info@ known; Kontakt cloaked / no new plain named
- `Krauss Calw mailto@krauss-web.de / krauss-formenbau (at)` — SKIP already known / (at) already decoded known
- `Gollmer third-party sales (stolz/mks/atr/mf-couplings)` — DROP third-party on Gollmer kontakt
- `w.schiffl@cad-schiffl.de` — DROP off-ICP (Anlagenbau pipeXPRESS / CAD Schulung, not Formenbau)
- `dialog@seiten-werk.com / info@tim-gatzky.de / support@cosmiclabs` — DROP Werbeagentur/web designer third-party
- `dsb@polar-form.de` — DROP Datenschutzbeauftragter
- `d.marx@ / l.schuck@ rausch-formenbau.de` — DROP Buchhaltung/Verwaltung / Einkauf
- `einkauf@triwefo.de / FLICKS-CAD phone-only / Gerken continuum` — DROP Einkauf / phone-only invent / Gerken Stanz continuum
- `placeholder info@company.com etc Heinrich Schmitt template` — DROP template placeholders
- `Scheidig/HHK/Klomfass/KuKo/WTL/WISA/Polar/FBB/Spies/Eder already known` — SKIP already known

---

## Website/named Kontakt Batch 121

> 合并前重读 CSV（任务口径 **4306** / **3018**；Directory Batch125dir→**4312**、Batch126dir→写时 live **4316** / **3017**）。本批按 live 合并，网站轨净增 **+8** → 瞬时 **4324** / **3018**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4324** |
| high / medium | **4044** / **280** |
| 唯一域名 | **3018** |
| 含电话 / 含城市 | **3733** / **3812** |
| 非 .de 邮箱 | **1154** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3998** |
| design_studio | **181** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本批网站轨净增 **+8**（相对写时基线 4316）

- `info@ehformtechnik.de` — E & H Formtechnik-Entwicklung GmbH (Waldsassen) — `design_studio` / high
- `r.ernstberger@ehformtechnik.de` — E & H Formtechnik-Entwicklung GmbH (Waldsassen) — `design_studio` / high — R. Ernstberger
- `entwicklung@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high — Gereon Starke
- `gereon.starke@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high — Gereon Starke
- `projektmanagement@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high
- `wzb@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high — Kai Gerhardt
- `kai.gerhardt@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high — Kai Gerhardt
- `tobias.steidl@polymold.de` — POLYMOLD GmbH (Pähl) — `overseas_peer_overflow` / high — Tobias Steidl

### 本批质量剔除（节选）

- `info@weborbis-webdesign.de` — DROP Werbeagentur (BM Impressum web designer)
- `poststelle@datenschutz-bayern.de / poststelle@lra-ed.de` — DROP third-party Behörde on Impressum
- `sh@kreativstudio-hohmann.de / hallo@dieatemraeuber.de / info@7bytes.de` — DROP agency / photo / web designer third-party
- `bewerbung@spindler-formenbau.de / bewerbung@stolz-seng.de` — DROP Bewerbung/HR
- `dsb@stolz-seng.de` — DROP Datenschutzbeauftragter
- `warenausgang@p-w-f.de` — DROP Versand/Warenausgang
- `info.h@nel-praezision.de` — DROP cloak parse artifact (Hänel)
- `Gollmer kontakt third-party (stolz-industries / mks-sales / atr-solutions / mf-couplings)` — DROP third-party sales partners on Gollmer kontakt (carry-forward)
- `Meissner Formentechnologie` — DROP Sand-/Kokillen-/Druckguss-primary
- `Riedl / Frank / Bergmann / Happ / W&W / Fenkl / Marquart / Saur / Kaut / Kaspareth / Berger / KB-Hein / Voth / WTL / Spies / Stolz-Seng / Otto / EDEGS / OptiCAMMS / Gärtner / BM / Spindler / Hänel / CAD studios` — SKIP already known
- `Finke/ccoffice/Formacon/Krauss mailto∂` — SKIP cloak / phone-only / dead (carry forward to B122)

---

## Website/named Kontakt Batch 120

> 合并前重读 CSV（基线 **4303** / **3017**；任务口径 4303/3006 hosts~3017）。本批网站轨净增 **+3** → 瞬时 **4306** / **3018**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4306** |
| high / medium | **4029** / **277** |
| 唯一域名 | **3018** |
| 含电话 / 含城市 | **3718** / **3794** |
| 非 .de 邮箱 | **1154** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3982** |
| design_studio | **179** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本批网站轨净增 **+3**（相对基线 4303）

- `info@polynisterplastik.de` — Poly-Nister-Plastik GmbH & Co. KG (Streithausen) — `oem_buyer` / high
- `marco.sittler@polynisterplastik.de` — Poly-Nister-Plastik GmbH & Co. KG (Streithausen) — `oem_buyer` / high
- `fabian.zoeller@polynisterplastik.de` — Poly-Nister-Plastik GmbH & Co. KG (Streithausen) — `oem_buyer` / high

### 本批质量剔除（节选）

- `andreas.heinbach@polynisterplastik.de` — DROP Kaufmännische Leitung (admin/finance skew)
- `info@gh-werkzeuge.de` — SKIP partner mailbox on Polynister page; gh-werkzeuge.de site dead — never invent
- `sabine.schlessmann@ / diana.heimpel@ / karina.hoeld@ / andrea.willmann@ dorn-tt.de` — DROP Auftragsabwicklung / Buchhaltung
- `renate.wirth@dorn-tt.de` — SKIP QS-only secondary; ICP-fit Dorn GF/tech already known
- `kontakt@mold-design.de` — DROP Werbe-/Marketing-Design agency (not Formenbau ICP)
- `info@formtech-gmbh.de` — SKIP already in master
- `Formtech/Kesterke/WeKonSo/Walter/HWF named` — SKIP already known

---

## Website/named Kontakt Batch 119

> 合并前重读 CSV（任务口径 **4294** / **3012**；Directory Batch124dir 中途已合 → 写时 live **4298** / **3016**）。本批按 live 合并，网站轨净增 **+5** → 瞬时 **4303** / **3017**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4303** |
| high / medium | **4026** / **277** |
| 唯一域名 | **3017** |
| 含电话 / 含城市 | **3715** / **3791** |
| 非 .de 邮箱 | **1154** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3982** |
| design_studio | **179** |
| oem_buyer | **107** |
| sourcing | **35** |

### 本批网站轨净增 **+5**（相对写时基线 4298；相对任务口径 4294 为 +9 含目录）

- `info@kb-kunststoff.de` — KB Kunststofftechnik Vertriebs GmbH (Gummersbach) — `oem_buyer` / high
- `c.pfaff@pfaffgmbh.com` — Pfaff GmbH (Waldkirch) — `oem_buyer` / high
- `a.buff@pfaffgmbh.com` — Pfaff GmbH (Waldkirch) — `oem_buyer` / high
- `o.salvat@pfaffgmbh.com` — Pfaff GmbH (Waldkirch) — `oem_buyer` / high
- `h.seifried@pfaffgmbh.com` — Pfaff GmbH (Waldkirch) — `oem_buyer` / high

### 本批质量剔除（节选）

- `s.kaul@pfaffgmbh.com` — DROP Assistenz/Vertrieb (Assistentin)
- `c.biehler@pfaffgmbh.com` — DROP Assistenz/Buchhaltung
- `duerrbeck@ / erdogan@ / hanneder@ / mehdi@ wartenfelser.de` — DROP Personal/Buchhaltung / Versand / Logistik
- `Finke Gruppe named emails` — DROP cloak invent (JS-split E-Mail obfuscation)
- `info@ccoffice.de / webmaster@` — SKIP invent — live site shows phone only, no plain email
- `ABAS/Croner ansprechpartner` — SKIP no plain emails / thin page
- `seidltec.com` — DROP AT-only (Auerbach AT)

---

## Website/named Kontakt Batch 118

> 合并前重读 CSV（任务口径 **4281** / **3001**；Directory Batch123dir 中途已合 → 写时 live **4291** / **3010**）。本批按 live 合并，网站轨净增 **+3** → 瞬时 **4294** / **3012**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4294** |
| high / medium | **4018** / **276** |
| 唯一域名 | **3012** |
| 含电话 / 含城市 | **3706** / **3782** |
| 非 .de 邮箱 | **1149** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3978** |
| design_studio | **179** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本批网站轨净增 **+3**（相对写时基线 4291；相对任务口径 4281 为 +13 含目录）

- `michael.beckmann@beckmann-cad.de` — Konstruktionsbüro Beckmann GmbH (Altdorf) — `design_studio` / high
- `info@daut-imd.com` — Vitali Daut IMD (Bad Windsheim) — `design_studio` / high
- `info@toolytech.de` — ToolyTech UG (Jena) — `overseas_peer_overflow` / high

### 本批质量剔除（节选）

- `a.fuerst@formzeug.de` — DROP Lager-Logistikleiter (Versand/Lager)
- `a.maier@wsuttergmbh.de` — DROP Buchhaltung
- `info@wa21.de on rethemeier.eu` — DROP third-party/agency mailbox
- `mail@sieberkon.info` — DROP CH-only (Marbach CH)
- `j.sancar@formacon.de` — SKIP site unreachable — never invent from XING-only
- `info@geiger-formenbau.de` — SKIP invent — Impressum shows kontakt@ only (already known)
- `HHK/Karthaus/EJ/Beckmann info@ / HWF named / Sutter named / Voth / KuKo / Scheidig / Grimm` — SKIP already known

---

## Website/named Kontakt Batch 117

> 合并前重读 CSV（基线 **4279** / **2999**；Batch122dir 后父代理口径 4279/2988 hosts~2999）。勿用 4271。本批网站轨净增 **+2** → 瞬时 **4281** / **3001**；live 现为 **4281** / **3001**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4281** |
| high / medium | **4007** / **274** |
| 唯一域名 | **3001** |
| 含电话 / 含城市 | **3694** / **3769** |
| 非 .de 邮箱 | **1146** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3967** |
| design_studio | **177** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本批网站轨净增 **+2**（相对基线 4279）

- `info@baer-cad.de` — BÄR-CAD Inh. Manfred Bär (Eichstetten) — `design_studio` / high
- `info@hiltel-formentechnik.com` — Hiltel Formentechnik GmbH (Simmelsdorf) — `design_studio` / high

### 本批质量剔除（节选）

- `info@ke-services.de` — DROP wrong vertical — Entrümpelung/Umzüge Herford (LinkedIn false friend)
- `info@wk-konstruktion.de / w.kraus@` — DROP generic Konstruktion Stolberg — no Spritz/Formenbau ICP on site
- `bewerbung@spindler-formenbau.de` — DROP Bewerbung/HR
- `info@zi-systeme.de / info@sauer-tooldesign.de / info@kb-hiemer.de` — SKIP already known
- `zegla/jama named contacts` — SKIP phones only — no named emails live; info@ already known
- `reddikowsky / rommel-formen / formenbau-rapp` — SKIP dead/403 — never invent
- `info@thb-konstruktionsbuero.de` — SKIP site unreachable — never invent

---

## Website/named Kontakt Batch 116

> 合并前重读 CSV（基线 **4267** / **2990**；Batch121dir 后父代理口径 4267/2979 hosts~2990）。勿用 4260/4254。本批网站轨净增 **+4** → 瞬时 **4271** / **2993**；live 现为 **4271** / **2993**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4271** |
| high / medium | **3997** / **274** |
| 唯一域名 | **2993** |
| 含电话 / 含城市 | **3687** / **3759** |
| 非 .de 邮箱 | **1145** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3959** |
| design_studio | **175** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本批网站轨净增 **+4**（相对基线 4267）

- `mail@ruf-formentechnik.de` — RUF Formentechnik (Sankt Georgen im Schwarzwald) — `design_studio` / high
- `b.ruf@ruf-formentechnik.de` — RUF Formentechnik (Sankt Georgen im Schwarzwald) — `design_studio` / high
- `info@ssk-kunststoff.de` — Stefan Schmider Kunststoff und Kunststoffverarbeitung (SSK) (Berghaupten) — `oem_buyer` / high
- `info@ssk-schmider.de` — Stefan Schmider Kunststoff und Kunststoffverarbeitung (SSK) (Berghaupten) — `oem_buyer` / high

### 本批质量剔除（节选）

- `info@cad-cam-beichert.de` — SKIP already known (Beichert Spritzgießformen CAD)
- `info@tooldesign.de` — DROP Werbe- & Designagentur (not Formenbau ICP)
- `kb-das.de E-Mail empty` — DROP cloak/empty — David Schuster Spritz CAD, never invent
- `info@krauss-web.de from mailto ∂ krauss-web.de` — DROP cloak invent (mailto ∂); domain already has mailto@ placeholder
- `info@spritzgusswerkzeug-konstruktion.de` — SKIP no Impressum/DE address — DE+AT mobile-only (also B115 drop)
- `mail@sieberkon.info` — DROP CH-only (Marbach CH)
- `pauser-weinkauf.de` — SKIP site dead/minimal (336B); cannot live-verify
- `hiltel-formentechnik.com` — SKIP no plain email (JS SPA)

---

## Website/named Kontakt Batch 115

> 合并前重读 CSV（基线 **4247** / **2976**；Batch119dir 后父代理口径 4247/2965 hosts~2976）。勿用 4237。本批网站轨净增 **+7** → 瞬时 **4254** / **2977**；live 现为 **4254** / **2977**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4254** |
| high / medium | **3981** / **273** |
| 唯一域名 | **2977** |
| 含电话 / 含城市 | **3671** / **3744** |
| 非 .de 邮箱 | **1143** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3946** |
| design_studio | **173** |
| oem_buyer | **100** |
| sourcing | **35** |

### 本批网站轨净增 **+7**（相对基线 4247）

- `ingo.guettler@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `maxime.cerulus@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `guenter.dorsch@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `kai.kegelmann@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `karl.leitinger@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `ulrich.haas@r-hofmann.de` — Robert Hofmann GmbH (Lichtenfels) — `oem_buyer` / high
- `cad@khb-buebel.de` — Konstruktionsbüro Herbert Bübel (Nürnberg) — `design_studio` / high

### 本批质量剔除（节选）

- `maximilian.koenig@r-hofmann.de` — DROP Supply Chain Management
- `info@spritzgusswerkzeug-konstruktion.de` — SKIP no Impressum/address
- `info@gerken-konstruktionen.de` — DROP Stanz-/Umform-primary
- `info@wa21.de` — DROP third-party agency on Rethemeier
- `info@tool4tool.de` — SKIP secondary (prefer cad@khb-buebel.de Impressum)
- rethemeier / spritzguss.de / formzeug / croner / hwf — SKIP already known

---
## Website/named Kontakt Batch 114

> 合并前重读 CSV（基线 **4234** / **2966**；Batch118dir 后父代理口径 4234/2953 hosts~2966）。勿用 4219/4227。本批网站轨净增 +3 → **4237** / **2967**；live 现为 **4237** / **2967**。

### 累计（当前 live）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4237** |
| high / medium | **3967** / **270** |
| 唯一域名 | **2967** |
| 含电话 / 含城市 | **3656** / **3727** |
| 非 .de 邮箱 | **1141** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3936** |
| design_studio | **172** |
| oem_buyer | **94** |
| sourcing | **35** |

### 本批网站轨净增 **+3**（相对基线 4234）

- `m.lehr@schneider-form.de` — Schneider Form GmbH (Dettingen unter Teck) — `oem_buyer` / high
- `info@cad4u.de` — Ingenieurbüro Helge Feddersen / CAD4U (Rosenheim) — `design_studio` / high
- `ffb-formen@t-online.de` — FFB Förster Formenbau / Inh. Andreas Kunert (Bad Aibling) — `oem_buyer` / high

### 本批质量剔除（节选）

- Bauer Werkzeugbau JS HTML-entity cloak — DROP cloak invent
- `info@wepf.de` / named — DROP Schlauch/Rohrleitungen
- `fthormann@spritzguss-bergmann.de` — DROP Lager/Versand
- `vschouwink@spritzguss-bergmann.de` — DROP Buchhaltung
- `info@sipka.de` — SKIP dead; Formenpolier/Druckguss
- steinhauser / eckerle / bama / quattro / weiland / gollmer — SKIP already known
- TBI Formenbau .at — SKIP AT

---
## Website/named Kontakt Batch 113

> 合并前重读 CSV（基线 **4200** / **2941**）。本批网站轨净增 +4 → 瞬时 **4204** / **2942**；随后并发目录合并，live 现为 **4219** / **2951**（B113 KEEP 仍在库）。

### 累计（当前 live，含并发目录）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4219** |
| high / medium | **3952** / **267** |
| 唯一域名 | **2951** |
| 含电话 / 含城市 | **3639** / **3711** |
| 非 .de 邮箱 | **1139** |

### 按 icp_tag（累计 live）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3921** |
| design_studio | **171** |
| oem_buyer | **92** |
| sourcing | **35** |

### 本批网站轨净增 **+4**（相对基线 4200）

- `info@gbeil.com` — G. Beil Formtechnik / Konstruktion / Entwicklung (Messkirch-Langenhart) — `design_studio` / high
- `peter.dorn@dorn-tt.de` — Dorn Spritzguss GmbH (Tettnang-Hiltensweiler) — `oem_buyer` / high
- `marc.tobias@dorn-tt.de` — Dorn Spritzguss GmbH (Tettnang-Hiltensweiler) — `oem_buyer` / high
- `michael.dorner@dorn-tt.de` — Dorn Spritzguss GmbH (Tettnang-Hiltensweiler) — `oem_buyer` / high

### 本批质量剔除（节选）

- `info@form-tec.de` — DROP Photovoltaik-Unterkonstruktionen — not Spritz/Formenbau
- `info@formtech.de` — DROP Umformtechnik SPF/Diffusion Bonding — not Spritz ICP
- `a.fuerst@formzeug.de` — DROP Lager-Logistikleiter
- `diana.heimpel@dorn-tt.de` — DROP Buchhaltung
- Carmen Dorn Assistentin — DROP Assistentin der GF
- sabine.schlessmann@ / karina.hoeld@ / andrea.willmann@ dorn-tt — DROP Auftragsabwicklung/office
- `renate.wirth@dorn-tt.de` — DROP QS-only
- pakulla / timm / formzeug named / franz-lechner / marquart / happ / geiger — SKIP already known

---

## Website/named Kontakt Batch 112

> 合并前重读 CSV（基线 **4192** / **2934**；Batch114dir +11 后邮箱 **4192**，父代理域名口径 2919 / hosts~2934；本机重计域名 **2934**）。勿用 4177/4181。

### 累计（Batch 112 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4194** |
| high / medium | **3930** / **264** |
| 唯一域名 | **2935** |
| 含电话 / 含城市 | **3616** / **3691** |
| 非 .de 邮箱 | **1136** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3900** |
| design_studio | **170** |
| oem_buyer | **89** |
| sourcing | **35** |

### 本批净增 **+2**

- `team_cad-kon@t-online.de` — CAD-KON GmbH (Dettingen unter Teck) — `design_studio` / high
- `info@fun-gmbh.eu` — FuN GmbH (Rott am Inn) — `oem_buyer` / high

### 本批质量剔除（节选）

- `m.nagl@web.de` — DROP personal web.de mailbox (FuN GF) — prefer company info@
- `webmaster@cadkon-design.com` — DROP webmaster technical contact
- `info@eberhardt-wk.de` — DROP Stanz-/Umform-primary Werkzeugkonstruktion
- `h.wirth@werkzeugbau-wirth.com` — DROP Bewerbung/HR mailbox
- `bewerbung@spindler-formenbau.de` — DROP HR/Bewerbung
- `terminbuchung@aboutjell.de` — DROP appointment-booking only
- `info@raba-tech.de` — SKIP unreachable 404
- ferratec / vogel / w-p-k / hwf / opticamms / kaspareth / edegs / frank / wtl / spindler / triwefo / khp / schwendemann / bayreuth / winkelmühle / ermet / croner / steiert / haenel / seeger / mueller / wefo / kon-form / schneider / km / formtech / benkert — SKIP already known

---
## Website/named Kontakt Batch 111

> 合并前重读 CSV（基线 **4171** / **2918**；Batch111dir 后邮箱 **4160**，父代理域名口径 2893 / hosts~2909；本机重计域名 **2918**）。

### 累计（Batch 111 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4177** |
| high / medium | **3915** / **262** |
| 唯一域名 | **2921** |
| 含电话 / 含城市 | **3601** / **3674** |
| 非 .de 邮箱 | **1134** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3885** |
| design_studio | **169** |
| oem_buyer | **88** |
| sourcing | **35** |

### 本批净增 **+6**

- `neumayr@cad-solutions.cc` — CAD Solutions Neumayr (Hirschau) — `design_studio` / high
- `info@fischer-werkzeugbau.de` — Fischer Formenbau / Tarek Fischer (Taunusstein) — `oem_buyer` / high
- `info@hofmann-wze.de` — Hofmann Erodiertechnik GmbH / Hofmann die Werkzeugentwickler (Helmbrechts) — `oem_buyer` / high
- `mh@hofmann-wze.de` — Hofmann Erodiertechnik GmbH / Hofmann die Werkzeugentwickler (Helmbrechts) — `oem_buyer` / high
- `felix.meister@hofmann-wze.de` — Hofmann Erodiertechnik GmbH / Hofmann die Werkzeugentwickler (Helmbrechts) — `oem_buyer` / high
- `info@fus-werkzeugbau.de` — HPF / Friedrich & Partner Werkzeug- und Formenbau (Großdubrau) — `oem_buyer` / high

### 本批质量剔除（节选）

- `info@cad-eckes.de` — DROP generic Maschinenbau/Metallbau CAD + Beschaffung/Einkauf — not Spritz/Formenbau peer
- `info@werkzeugbauschmidt.de` — DROP Stanz/Biege co-primary with Spritz
- `info@gerken-konstruktionen.de` — DROP Stanz/Umform primary (prior continuum Gerken)
- `info@formenbau-conrad.de` — DROP Druckguss-primary (Formenbau und Druckguss GmbH)
- `info@3d-tooldesign.com` — SKIP CH country-box Langnau (not DE-proven)
- `steffen.schulz@kws-dresden.de` — DROP Stanz/Umform/Folgeverbund-primary career; Spritz secondary
- `gerd.hoelzel@hofmann-wze.de` — DROP Leiter Konstruktion|Einkauf — Einkauf in title
- `kathrin.friedrich@ / nadine.reichelt@ fus-werkzeugbau` — DROP untitled reception/office (phone -0 only)
- `mail@hilzensauer-cad-design.de` — SKIP already known
- `mold-engineering UnCryptMailto` — DROP cloak invent
- `info@korropol.com / korropol.de` — DROP Composite/GFK/CFK primary

---
## Website/named Kontakt Batch 110

> 合并前重读 CSV（基线 **4136** / **2887**；Batch110dir 后邮箱 **4136**，父代理域名口径 2871 / hosts~2887；本机重计域名 **2887**）。

### 累计（Batch 110 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4140** |
| high / medium | **3879** / **261** |
| 唯一域名 | **2889** |
| 含电话 / 含城市 | **3566** / **3638** |
| 非 .de 邮箱 | **1131** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3854** |
| design_studio | **168** |
| oem_buyer | **83** |
| sourcing | **35** |

### 本批净增 **+4**

- `info@goletz-gmbh.de` — Goletz GmbH (Kierspe) — `oem_buyer` / high
- `asommer@oelfke.de` — Ulrich Oelfke Formenbau GmbH & Co. KG (Lüdenscheid) — `oem_buyer` / high
- `jsommer@oelfke.de` — Ulrich Oelfke Formenbau GmbH & Co. KG (Lüdenscheid) — `oem_buyer` / high
- `info@kompetenzkunststoff.de` — ma Kompetenz Kunststoff / Ingenieurbüro Michael Ahrens (Niedereschach) — `sourcing` / high

### 本批质量剔除（节选）

- `thorsten.meyer@meykon.net` — DROP Feinguss + Blasformen/PET primary
- `info@cad-konstruktionsbuero.de` — DROP generic Maschinenbau CAD — not Spritzguss/Formenbau peer
- `info@flicks-cad.de / Wolfgang Flickschuh` — DROP cloak — Impressum shows E-Mail: Kontakt / E-Mail anzeigen only; never invent
- `arichter@oelfke.de` — DROP Verwaltung
- `anfragen@mf-schwinn.de` — DROP Schwinn Umform/Druckguss co-primary (prior continuum)
- `info@jskonstruktion.de` — DROP Gießerei/Modellbau/Kernkästen primary; Spritz listed secondary
- `info@spritzgusswerkzeug-konstruktion.de` — SKIP prior continuum
- `office@formenbau-gmbh.at` — SKIP AT country-box + Feinguss/Schmiede co
- `bewerbung@spindler-formenbau.de` — DROP HR/jobs mailbox

---
## Website/named Kontakt Batch 109

> 合并前重读 CSV（基线 **4103** / **2865**；Batch109dir 后邮箱 **4103**，父代理域名口径曾报 2849；本机重计域名 **2865**）。

### 累计（Batch 109 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4108** |
| high / medium | **3847** / **261** |
| 唯一域名 | **2870** |
| 含电话 / 含城市 | **3534** / **3619** |
| 非 .de 邮箱 | **1130** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3826** |
| design_studio | **168** |
| oem_buyer | **80** |
| sourcing | **34** |

### 本批净增 **+5**

- `e.jakimenko@ej-konstruktionsbuero.de` — Konstruktionsbüro Eugen Jakimenko (Espelkamp) — `design_studio` / high
- `info@cad-plast.de` — CAD-Plast GmbH (Aichach/Ecknach) — `oem_buyer` / high
- `info@radtke-konstruktionen.de` — Konstruktionsbüro Horst Radtke (Espelkamp) — `design_studio` / high
- `info@kraemer-e.de` — Krämer Engineering Solutions GmbH (Jevenstedt) — `oem_buyer` / high
- `info@ewkon.de` — E.W. Konstruktionen / EWK (Hille) — `design_studio` / high

### 本批质量剔除（节选）

- `info@formenschmiede.com / Formenschmiede` — DROP Silikon/Juwelier FormenSchmiede — not Spritzguss ICP
- `info@selve.de` — DROP Rollladen-primary (SELVE)
- `kontakt@formenbau-bockenem.de / Bockenem` — DROP Druckguss/Kokille-primary
- `info@hkr-werkzeugtechnik.de / j.dittrich@` — DROP unreachable / live verify fail
- `kb-das.de David Schuster` — DROP empty E-Mail field on home+Impressum — never invent
- `info@midena-formenbau.de / info@rocolani.de` — SKIP master-optional
- `d.marx@ / l.schuck@ rausch-formenbau` — DROP Buchhaltung/Verwaltung / Einkauf (info@+a.marx already known)
- `werkzeuge@pakulla FAQ-only` — SKIP invent — FAQ invent-ish; info@ already known
- `info@spritzgusswerkzeug-konstruktion.de` — SKIP prior continuum (non-DE country-box / known skip)
- `h.radtke@radtke-konstruktionen.de` — SKIP invent — only on third-party PDF directory; not live on own site

---
## Website/named Kontakt Batch 108

> 合并前重读 CSV（基线 **4052** / **2820**；Batch107 后 4052/2820）。

### 累计（Batch 108 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4057** |
| high / medium | **3798** / **259** |
| 唯一域名 | **2822** |
| 含电话 / 含城市 | **3488** / **3569** |
| 非 .de 邮箱 | **1115** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3780** |
| design_studio | **165** |
| oem_buyer | **78** |
| sourcing | **34** |

### 本批净增 **+5**

- `info@jell-konstruktion.de` — JELL GmbH & Co. KG (Bernau am Chiemsee) — `design_studio` / high
- `anfrage@aboutjell.de` — JELL GmbH & Co. KG (Bernau am Chiemsee) — `design_studio` / high
- `holwarth@haenel-praezision.de` — Hänel Präzisionsformenbau GmbH (Neuendettelsau) — `design_studio` / high
- `info@embayer.de` — E.M.Bayer GmbH & Co. KG (Freystadt) — `oem_buyer` / high
- `info@burms.de` — BURMS – 3D Druck Jena GmbH & Co. KG (Kahla) — `oem_buyer` / high

### 本批质量剔除（节选）

- `info@krauss-web.de` — SKIP invent — Impressum shows mailto∂ krauss-web.de obfuscation; mailto@ already known junk; do not invent info@
- `daniel.faltus@embayer.de` — DROP Personal/HR jobs mailbox
- `info@wds-werkzeugbau.de` — DROP Thermoform/Siegel packaging (prior continuum)
- `info@sundermeier-werkzeugbau.de` — DROP Druckguss/Stanz co-primary
- `info@konstruktion-weides.de / weides@arcor.de` — DROP Druckguss co + personal arcor mailbox
- `info@ck-form.de` — DROP unreachable
- `rfk-formenbau Druckguss tags` — SKIP already-known; Druckguss co on site
- `croner-formenbau.de` — SKIP already-known; site 401/thin

---

## Website/named Kontakt Batch 107

> 合并前重读 CSV（基线 **4048** / **2818**；Batch106 后 4048/2818）。

### 累计（Batch 107 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4052** |
| high / medium | **3793** / **259** |
| 唯一域名 | **2820** |
| 含电话 / 含城市 | **3483** / **3564** |
| 非 .de 邮箱 | **1115** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3780** |
| design_studio | **162** |
| oem_buyer | **76** |
| sourcing | **34** |

### 本批净增 **+4**

- `info@schmitt-brackenheim.de` — Schmitt GmbH (Brackenheim-Dürrenzimmern) — `oem_buyer` / high
- `cad@schmitt-brackenheim.de` — Schmitt GmbH (Brackenheim-Dürrenzimmern) — `design_studio` / high
- `konstruktion@schmitt-brackenheim.de` — Schmitt GmbH (Brackenheim-Dürrenzimmern) — `design_studio` / high
- `info@explicad.de` — expliCAD GmbH (Gilching) — `design_studio` / high

### 本批质量剔除（节选）

- `d.marx@rausch-formenbau.de` — DROP Buchhaltung/Verwaltung
- `l.schuck@rausch-formenbau.de` — DROP Einkauf
- `info@wds-werkzeugbau.de` — DROP Thermoform-/Siegel-Verpackungswerkzeuge primary
- `info@sundermeier-werkzeugbau.de` — DROP Druckguss + Schnitt/Stanz co-primary Schwerpunkte alongside Spritzgieß
- `info@hgs-schmitz.de` — DROP Schnittwerkzeuge/Pressformen co-branded with Spritzgusswerkzeuge
- `info@formenbau-klomfass.de` — DROP Druckguss co (Zink/Alu Druckguss + Spritz)
- `info@ck-form.de` — DROP site unreachable (again)
- `info@hack-formenbau.de` — SKIP ROT13/JS cloak — do not invent decoded address
- `info@formtec-kt.com` — DROP Thermoformen/PU packaging primary
- `hhk-konstruktion Stanz branding` — SKIP known domain; home Stanz-co branding

---

## Website/named Kontakt Batch 106

> 合并前重读 CSV（Batch107dir 后基线 **4044** / **2816**；中途 Batch106dir 后曾为 4012/2769；初值 3985/2744）。

### 累计（Batch 106 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4048** |
| high / medium | **3789** / **259** |
| 唯一域名 | **2818** |
| 含电话 / 含城市 | **3479** / **3560** |
| 非 .de 邮箱 | **1115** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3780** |
| design_studio | **159** |
| oem_buyer | **75** |
| sourcing | **34** |

### 本批净增 **+4**

- `konstruktion@fm-kunststoffteile.de` — Franz Moderegger GmbH / Fm Kunststoffteile (Bischofswiesen) — `design_studio` / high
- `info@awm-tec.de` — Arnstädter Werkzeug- und Maschinenbau GmbH (AWM) (Arnstadt) — `overseas_peer_overflow` / high
- `anfrage-wzb@awm-tec.de` — Arnstädter Werkzeug- und Maschinenbau GmbH (AWM) (Arnstadt) — `overseas_peer_overflow` / high
- `info@leweku.de` — LeWeKu Kunststofftechnik GmbH (Hallerndorf) — `oem_buyer` / high

### 本批质量剔除（节选）

- `info@formenbau-olinger.de` — DROP — general Formen-/Modellbau + Dreh/Fräs/Erodieren, not Spritzgießwerkzeuge-primary; site dating "bis (2020)" stale
- `jens.rabin@rabin-werkzeugbau.de` — DROP Druckguss/Umform/Blechumform co-branded with Spritz
- `info@rommel-formen.de` — DROP — rommel-formen.de Impressum redirects to HAAS Metallguss (not Formenbau peer)
- `info@schroeder-heidler.de` — SKIP master-optional
- `info@jordan-spritzguss.de` — SKIP master-optional; jordan-spritzguss.de unreachable
- `info@wzb-humme.de` — SKIP — secondary domain; Impressum primary info@werkzeugbau-humme.de already known
- `c.zils@formenbau-gf.de` — DROP Karriere/Personal
- `info@wagenknecht-werkzeugbau.de` — DROP Stanz-/Umform co-primary branding
- `lahme named contacts (no role)` — SKIP — Kontakt lists many names without titles; cannot quality-gate Assistentin/Buchhaltung
- `info@wb-gmbh.de` — SKIP master-optional

---

## Website/named Kontakt Batch 105

> 合并前重读 CSV（Batch105dir 后基线 **3982** / **2741**；中途 Batch104dir 后曾为 3967/2726；初值 3947/2706）。

### 累计（Batch 105 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3985** |
| high / medium | **3729** / **256** |
| 唯一域名 | **2744** |
| 含电话 / 含城市 | **3424** / **3499** |
| 非 .de 邮箱 | **1110** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3719** |
| design_studio | **158** |
| oem_buyer | **74** |
| sourcing | **34** |

### 本轨成果（Batch 105）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+3**（high **3** / medium **0**） |
| 相对基线 3982/2741 | **+3** / **+3** 域名 |
| 质量剔除 | **10** |

### 方法

1. 重读确认 **3982/2741**（Batch105dir 已合并；Batch104dir 亦已并入）
2. NEW-domain: Beichert design_studio + IGENO oem_buyer + Polymeric oem_buyer（Spritzguss+Formenbau）
3. 质量门：Druckguss-co（Borchert）；Stanz（Gerken）；CH（Sieber）；incomplete Impressum；site 500/dead；Kokillen（Meissner）；cross-domain residual；Buchhaltung

### 本轨新增邮箱（共 3）

- `info@cad-cam-beichert.de` · Kleines Wiesental · Alexander/Levin Beichert · Geschäftsführer / Konstruktion Spritzgießformen · high · **新域名**
- `info@igeno-fat.de` · Nordhausen · Dr. Marlies Brandt · Geschäftsführerin / Spritzgießteile Formenbau · high · **新域名**
- `info@polymeric.de` · Neusäß · Sebastian Wimmer · Geschäftsführer / Spritzguss Formenbau · high · **新域名**

### 产物

- `data/germany_raw/batch105_new_verified.json`
- `data/germany_raw/batch105_candidates_final.json`
- `data/germany_raw/batch105_quality_drops.json`
- `data/germany_raw/batch105_merge_log.json`
- `data/germany_raw/batch106_queue_note.txt`

---

## Website/named Kontakt Batch 104

> 合并前重读 CSV（Batch103dir 后基线 **3943** / **2703**；非初值 3925/2688）。

### 累计（Batch 104 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3947** |
| high / medium | **3696** / **251** |
| 唯一域名 | **2706** |
| 含电话 / 含城市 | **3390** / **3462** |
| 非 .de 邮箱 | **1108** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3684** |
| design_studio | **157** |
| oem_buyer | **72** |
| sourcing | **34** |

### 本轨成果（Batch 104）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+4**（high **4** / medium **0**） |
| 相对基线 3943/2703 | **+4** / **+3** 域名 |
| 质量剔除 | **10** |

### 方法

1. 重读确认 **3943/2703**（Batch103dir 已合并）
2. NEW-domain: Rethemeier design_studio + AB-FormTECH peer + SEBIKO info/Inhaber (Elastomer/LSR Formenbau)
3. 质量门：third-party agency（wa21）；GF invent（Heim）；CH（Sieber）；incomplete Impressum；Wartenfelser Logistik/Personal/Einkauf/Assistenz

### 本轨新增邮箱（共 4）

- `info@rethemeier.eu` · Kalletal · Bernd Rethemeier · Inhaber / Werkzeugkonstruktion Spritzguss · high · **新域名**
- `info@ab-form.tech` · Bad Aibling · Andreas Brandner · Inhaber / Werkzeug-Formenbau Spritzguss · high · **新域名**
- `info@sebiko.de` · Büdingen · Matthias Lohrey · Inhaber / Präzisionsformen Elastomer Spritzguss · high · **新域名**
- `mlohrey@sebiko.de` · Büdingen · Matthias Lohrey · Inhaber / Werkzeug- und Formenbau · high · **新域名**

### 产物

- `data/germany_raw/batch104_new_verified.json`
- `data/germany_raw/batch104_candidates_final.json`
- `data/germany_raw/batch104_quality_drops.json`
- `data/germany_raw/batch104_merge_log.json`
- `data/germany_raw/batch105_queue_note.txt`

---

## Website/named Kontakt Batch 103

> 合并前重读 CSV（Batch102dir 后基线 **3920** / **2685**；中途 Batch101dir 后曾为 3903/2668；初值 3897/2662）。

### 累计（Batch 103 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3925** |
| high / medium | **3679** / **246** |
| 唯一域名 | **2688** |
| 含电话 / 含城市 | **3370** / **3441** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3663** |
| design_studio | **156** |
| oem_buyer | **72** |
| sourcing | **34** |

### 本轨成果（Batch 103）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+5**（high **5** / medium **0**） |
| 相对基线 3920/2685 | **+5** / **+3** 域名 |
| master 可选重叠跳过 | **1**（direktform） |
| 质量剔除 | **12** |

### 方法

1. 重读确认 **3920/2685**（Batch102dir 已合并；Batch101dir 亦已并入）
2. NEW-domain: KB Wunner (design_studio) + Greschbach info/Ralf/Volker (oem_buyer) + pro forma concept (peer)
3. 质量门：Stanz（THB）；Druckguss（Conrad）；CH（Sieber）；无 Impressum（spritzgusswerkzeug-konstruktion）；Medizin distributor（TriRad）；Composite（ZVZ）；Lager-Logistik（Formzeug a.fuerst）；cloak（mold-engineering）；Sondermaschinen（AKON）；dead（Formacon/rs-formtec）；master-optional（direktform）

### 本轨新增邮箱（共 5）

- `info@kb-wunner.de` · Meißen · Mirko Wunner · Inhaber / Konstruktion Spritzgussformenbau · high · **新域名**
- `info@greschbach-gmbh.de` · Herbolzheim · — · Allgemeine Anfragen / Kunststoffverarbeitung Konstruktion · high · **新域名**
- `r.greschbach@greschbach-gmbh.de` · Herbolzheim · Ralf Greschbach · Dipl.-Kfm. / Ansprechpartner · high · **新域名**
- `v.greschbach@greschbach-gmbh.de` · Herbolzheim · Volker Greschbach · Dipl.-Ing. (BA) / Geschäftsführer · high · **新域名**
- `info@proforma-concept.de` · Radeburg · Bilal Demirel · Geschäftsführer / Werkzeug- und Formenbau · high · **新域名**

### 产物

- `data/germany_raw/batch103_new_verified.json`
- `data/germany_raw/batch103_candidates_final.json`
- `data/germany_raw/batch103_quality_drops.json`
- `data/germany_raw/batch103_merge_log.json`
- `data/germany_raw/batch104_queue_note.txt`

---

## Website/named Kontakt Batch 102

> 合并前重读 CSV（Batch100dir 后基线 **3893** / **2659**；非初值 3874/2642。Batch101dir 未写入）。

### 累计（Batch 102 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3897** |
| high / medium | **3651** / **246** |
| 唯一域名 | **2662** |
| 含电话 / 含城市 | **3345** / **3413** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3639** |
| design_studio | **155** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch 102）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+4**（high **4** / medium **0**） |
| 相对基线 3893/2659 | **+4** / **+3** 域名 |
| master 可选重叠跳过 | **2** |
| 质量剔除 | **9** |

### 方法

1. 重读确认 **3893/2659**（Batch100dir 已合并；Batch101dir 空）
2. NEW-domain: Gebr. Schwarz（info+GF）+ Quinger peer + Grimm & Remmert design_studio
3. 质量门：Stanz/Umform（Spill/Gerken）；CNC-only（Engl）；Honwerkzeuge（PWG）；弱 ICP（Olinger）；Consulting（Schötz）；master-optional（EMS/Stolz-Seng）；Druckguss-primary（Cox）

### 本轨新增邮箱（共 4）

- `info@schwarz-gmbh.de` · Rottweil-Neukirch · — · Allgemeine Anfragen / Werkzeugbau Spritzguss · high · **新域名**
- `j.roth@schwarz-gmbh.de` · Rottweil-Neukirch · Jens Roth · Geschäftsführer · high · **新域名**
- `info@quinger-gmbh.de` · Flöha · — · Allgemeine Anfragen / Formenbau Spritzguss · high · **新域名**
- `info@grimm-remmert.de` · Bad Lobenstein · Mathias Grimm / Peter Remmert · Geschäftsführung / Konstruktion Spritzgießwerkzeuge · high · **新域名**

### 产物

- `data/germany_raw/batch102_new_verified.json`
- `data/germany_raw/batch102_candidates_final.json`
- `data/germany_raw/batch102_quality_drops.json`
- `data/germany_raw/batch102_merge_log.json`
- `data/germany_raw/batch103_queue_note.txt`

---

## Website/named Kontakt Batch 101

> 合并前重读 CSV（Batch99dir 后基线 **3867** / **2635**；非初值 3854/2623。Batch100dir 未写入；dir 队列空）。

### 累计（Batch 101 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3874** |
| high / medium | **3629** / **245** |
| 唯一域名 | **2642** |
| 含电话 / 含城市 | **3324** / **3390** |
| 非 .de 邮箱 | **1105** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3617** |
| design_studio | **154** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch 101）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+7**（high **7** / medium **0**） |
| 相对基线 3867/2635 | **+7** / **+7** 域名 |
| master 可选重叠跳过 | **0** |
| 质量剔除 | **7** |

### 方法

1. 重读确认 **3867/2635**（Batch99dir 已合并；Batch100dir 空；dir queue empty）
2. NEW-domain Konstruktionsbüros + WBKT Präzisionsformenbau/Spritzguss
3. 命中：Scheidig / Kesterke / WeKonSo / WBKT Kruse / Karthaus / RDCAD / Piston（7 NEW domains）
4. 质量门：Druckguss-primary（Cox）；Stanz/Umform（DK/Gerken）；general CAD（Ptach）；unpublished（Banas）；no mailto（Thermo-Tec）

### 本轨新增邮箱（共 7）

- `info@cad-scheidig.de` · Gräfenthal · Frank Scheidig · Inhaber / Konstruktion Spritzgießwerkzeuge · high · **新域名**
- `info@kesterke.de` · Bargstedt · Peter Kesterke · Geschäftsführer / Konstruktion Spritzgiesswerkzeuge · high · **新域名**
- `info@wekonso.de` · Löhne · Frank Balsmeier · Inhaber / CAD Konstruktion Spritzgießwerkzeuge · high · **新域名**
- `kruse@wbkt.de` · Egeln · — · Allgemeine Anfragen / Werkzeugbau Spritzgießwerkzeuge · high · **新域名**
- `info@cad-karthaus.de` · Wipperfürth · Jörg Karthaus · Inhaber / Werkzeugkonstruktion Spritzguss · high · **新域名**
- `rdcad@rdcad.de` · Ansbach · Dieter Rößl · Inhaber / Konstruktion Spritzgußwerkzeuge · high · **新域名**
- `info@konstruktionsbuero-piston.de` · Hatzfeld-Reddighausen · Maximilian Schneider · Geschäftsführer / Konstruktion Spritzgießwerkzeuge · high · **新域名**

### 产物

- `data/germany_raw/batch101_new_verified.json`
- `data/germany_raw/batch101_candidates_final.json`
- `data/germany_raw/batch101_quality_drops.json`
- `data/germany_raw/batch101_merge_log.json`
- `data/germany_raw/batch102_queue_note.txt`

---

## Website/named Kontakt Batch 100

> 合并前重读 CSV（Batch98dir 后基线 **3846** / **2615**；非初值 3816/2591。Batch99dir 未写入）。

### 累计（Batch 100 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3854** |
| high / medium | **3609** / **245** |
| 唯一域名 | **2623** |
| 含电话 / 含城市 | **3310** / **3381** |
| 非 .de 邮箱 | **1092** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3603** |
| design_studio | **148** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch 100）

| 指标 | 数值 |
|---|---:|
| 本轨净增邮箱 | **+8**（high **8** / medium **0**） |
| 相对基线 3846/2615 | **+8** / **+8** 域名 |
| master 可选重叠跳过 | **0** |
| 质量剔除 | **7** |

### 方法

1. 重读确认 **3846/2615**（Batch98dir 已合并；Batch99dir 空）
2. Thin multi + NEW-domain: Konstruktionsbüros（Hiemer/Lais/KuKo/Beckmann/Krauss/HHK）+ LiuTek sourcing + Tettenborn Formenbau
3. 命中：8 NEW domains（design_studio×6 + sourcing×1 + peer×1）
4. 质量门：Buchhaltung/Personal（sonja.karl）；invent sebastian.karl；Glauchau 无 Spritz；rausch .com 错 TLD；Einkauf

### 本轨新增邮箱（共 8）

- `info@kb-hiemer.de` · Burggriesbach · Leonas Hiemer · Inhaber / Konstruktion Formenbau · high · **新域名**
- `info@liutek.de` · Neuendettelsau · Xinhui Liu · Geschäftsführung / China Formen DE · high · **新域名**
- `info@formenbau-tettenborn.de` · Solingen · — · Allgemeine Anfragen / Formenbau · high · **新域名**
- `sl@lais-konstruktion.de` · Münstertal · Stefan Lais · Inhaber / Konstruktion Spritzgießformen · high · **新域名**
- `info@kuko-web.de` · Pforzen · Peter Kunert · Inhaber / Konstruktion Spritzgusswerkzeuge · high · **新域名**
- `info@beckmann-cad.de` · Altdorf · Michael Beckmann · Geschäftsführer / Konstruktion Spritzgusswerkzeuge · high · **新域名**
- `mailto@krauss-web.de` · Calw · — · Allgemeine Anfragen / Formenkonstruktion · high · **新域名**
- `info@hhk-konstruktion.de` · Lohkirchen · Helmut Höllbauer · Inhaber / Konstruktion Werkzeugbau · high · **新域名**

### 产物

- `data/germany_raw/batch100_new_verified.json`
- `data/germany_raw/batch100_candidates_final.json`
- `data/germany_raw/batch100_quality_drops.json`
- `data/germany_raw/batch100_merge_log.json`
- `data/germany_raw/batch101_queue_note.txt`

---

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

---


## 目录/展会轨 Batch131dir

> 合并前重读 CSV（直播基线 **4399** / **3080**；Website Batch125 后 steering）。合并后基线：**4425** / **3105**（hosts ~3116）。

### 累计（Batch131dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4425** |
| high / medium | **4145** / **280** |
| 唯一域名 | **3105** |
| 含电话 / 含城市 | **3819** / **3911** |
| 非 .de 邮箱 | **1177** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4080** |
| design_studio | **189** |
| oem_buyer | **121** |
| sourcing | **35** |

### 本轨成果（Batch131dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **127** |
| 有邮箱命中 | **54** |
| 本轨净增邮箱 | **26**（high **26** / medium **0**） |
| 相对基线 4399/3080 | **+26** / **+25** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B130 域名队列 | 空 |
| Rhön/Spessart/Odenwald/Frankenwald/Kinzig 微城 × kw | 有效（149 城，DDG 300 + Bing/Maps/EP/GS） |
| Bing Maps / Europages / Gelbe Seiten | 部分（maps 61 / ep 15 / gs 12；GS 站链 JS 隐藏） |
| Fakuma/VDWF / WLW | 未用 / 跳过 |
| 产量 | 127 候选核验 / 54 命中 / 质量门后 **+26**；剔 Blechumform/Extrusion/玻璃/Formdrehteile/Verwaltung/混淆邮箱/AT-only；ABAS Fulda JS-邮箱跳过 |

### 本轨新增邮箱（共 26）

- `info@formwerk.org` (high, overseas_peer_overflow) · Erbach
- `info@schick-kunststoffverarbeitung.de` (high, overseas_peer_overflow) · Groß-Umstadt
- `info@jb-werkzeugbau.de` (high, overseas_peer_overflow) · Ludwigsstadt
- `info@vogel-kunststofftechnik.com` (high, overseas_peer_overflow) · Burgthann-Ezelsdorf
- `info@laudenbach-formtechnik.de` (high, overseas_peer_overflow) · Gosheim
- `info@gela-werkzeugbau.de` (high, overseas_peer_overflow) · Rohrdorf-Achenmühle
- `info.kunststofftechnik@warema.de` (high, overseas_peer_overflow) · Marktheidenfeld
- `info@vogel-kunststoffverarbeitung.de` (high, overseas_peer_overflow) · Lampertswalde
- `info@gealan.com` (high, oem_buyer) · Oberkotzau
- `info@kurt-aue.com` (high, overseas_peer_overflow) · Garbsen
- `info@weich-gmbh.de` (high, overseas_peer_overflow) · Neustadt
- `info@pro-tech.de` (high, overseas_peer_overflow) · Neustadt
- `bossler.support@bossler-wzb.com` (high, overseas_peer_overflow) · Kümmersbruck
- `internet@uralan.de` (high, overseas_peer_overflow) · ?
- `info@wiesmayer.de` (high, overseas_peer_overflow) · Neustadt an der Donau
- `info@formica-gmbh.com` (high, overseas_peer_overflow) · Bad Salzungen
- `post@dplusl.de` (high, overseas_peer_overflow) · Heidenau
- `info@strathmann-gmbh.de` (high, overseas_peer_overflow) · Rödinghausen
- `motzener@kunststoff-gummi.de` (high, overseas_peer_overflow) · Mittenwalde
- `service@hebragmbh.de` (high, overseas_peer_overflow) · Alfeld
- `info@hebragmbh.de` (high, overseas_peer_overflow) · Alfeld
- `info@gealan.de` (high, oem_buyer) · Oberkotzau
- `info@kst-stoecker.de` (high, overseas_peer_overflow) · Nümbrecht
- `info@mueller-kunststofftechnik.de` (high, overseas_peer_overflow) · Hagenow
- `info@haas-werkzeugbau.de` (high, overseas_peer_overflow) · Loßburg-Lombach
- `modelle@harmsen-modellbau.de` (high, overseas_peer_overflow) · Petersberg

### 产物

- `data/germany_raw/batch131dir_*.json`
- `data/germany_raw/batch131dir_next_search_seeds.json`

### 状态

Batch131dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch132dir（下一城带：Allgäu/Oberland/Chiemgau/Bayerischer Wald）。全国目录轨饱和仍高，本带仍挖出 **+26** 新邮（含 formwerk Erbach、Schick Groß-Umstadt、WAREMA Marktheidenfeld、Harmsen Petersberg、JB Ludwigsstadt、GEALAN Oberkotzau 等）。

---
## 目录/展会轨 Batch130dir

> 合并前重读 CSV（直播基线 **4361** / **3052**；Website Batch124 后 steering）。合并后基线：**4391** / **3088**。

### 累计（Batch130dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4391** |
| high / medium | **4111** / **280** |
| 唯一域名 | **3088** |
| 含电话 / 含城市 | **3791** / **3878** |
| 非 .de 邮箱 | **1169** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4050** |
| design_studio | **189** |
| oem_buyer | **117** |
| sourcing | **35** |

### 本轨成果（Batch130dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **80** |
| 有邮箱命中 | **38** |
| 本轨净增邮箱 | **30**（high **30** / medium **0**） |
| 相对基线 4361/3052 | **+30** / **+36** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B129 域名队列 | 空 |
| Sauerland/Siegerland/Westerwald/Taunus + Lahn-Dill/Märkisch 微城 × kw | 有效（93 城，DDG 199 + Bing 60） |
| Bing Maps / Europages / Gelbe Seiten | 部分（maps 31 / ep 15 / gs 10；GS 站链 JS 隐藏） |
| BVMF Westfalen-Süd 名录 | 有效（Modellbau/Formenbau 带核验） |
| Fakuma/VDWF / WLW | 未用 / 跳过 |
| 产量 | 80 候选核验 / 38 命中 / 质量门后 **+30**；剔金属 Härte/Stanz/Kokille/Beton/Extrusion、Mehrwegbecher、Brill Personal/Einkauf/Assistenz |

### 本轨新增邮箱（共 30）

- `kontakt@ksm.info` (high, overseas_peer_overflow) · Meschede
- `info@modellbau-nebeling.de` (high, overseas_peer_overflow) · Drolshagen
- `info@mk-modellbau.com` (high, overseas_peer_overflow) · Werdohl
- `ohm@modellbauohm.de` (high, overseas_peer_overflow) · Olpe
- `info@modellbauohm.de` (high, overseas_peer_overflow) · Olpe
- `info@schrichten.de` (high, overseas_peer_overflow) · Schmallenberg
- `info@friedrichs-kunststoffe.de` (high, overseas_peer_overflow) · Meschede
- `office@friedrichs-kunststoffe.de` (high, overseas_peer_overflow) · Meschede
- `info@innovative-cad-cam-solutions.com` (high, design_studio) · Meschede
- `info@ktm-kunststofftechnik.de` (high, overseas_peer_overflow) · Montabaur
- `info@modellbau-brueggemann.de` (high, overseas_peer_overflow) · Hemer
- `info@gutberlet-modellbau.de` (high, overseas_peer_overflow) · Lüdenscheid
- `eike-lotz@gl-spritzgusstechnik.de` (high, overseas_peer_overflow) · Menden
- `info@herscheider-modellbau.de` (high, overseas_peer_overflow) · Herscheid
- `singer@singerengineering.de` (high, design_studio) · Montabaur
- `info@modellbau-nassal.de` (high, overseas_peer_overflow) · Hohentengen
- `engineering@rikutec.de` (high, overseas_peer_overflow) · Altenkirchen
- `info@hjs-kunststoff.de` (high, overseas_peer_overflow) · Tirschenreuth
- `info@burk-kunststofftechnik.com` (high, overseas_peer_overflow) · Gladenbach
- `info@inkuplastics.com` (high, overseas_peer_overflow) · Meinerzhagen
- `info@simon-kunststoff.de` (high, overseas_peer_overflow) · Sundern
- `kontakt@kunststoff-mende.de` (high, overseas_peer_overflow) · Klingenberg
- `info@ma-formfabrik.de` (high, overseas_peer_overflow) · Steinbach-Hallenberg
- `info@zoellner-kunststoff.de` (high, overseas_peer_overflow) · Burbach
- `mail@simon-kunststofftechnik.de` (high, overseas_peer_overflow) · Berglen
- `info@ht-tooldesign.de` (high, overseas_peer_overflow) · Marsberg
- `info@kkt-siegen.de` (high, overseas_peer_overflow) · Siegen
- `info@newtonian.gmbh` (high, design_studio) · Wetzlar
- `d.stahl@brillundadloff.de` (high, overseas_peer_overflow) · Lennestadt — Dominik Stahl
- `m.koenig@brillundadloff.de` (high, overseas_peer_overflow) · Lennestadt — Michael König

### 产物

- `data/germany_raw/batch130dir_*.json`
- `data/germany_raw/batch130dir_next_search_seeds.json`

### 状态

Batch130dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch131dir（下一城带：Rhön/Spessart/Odenwald/Frankenwald）。全国目录轨饱和仍高，本带仍挖出 **+30** 新邮（含 brill+adloff Lennestadt 具名、KSM/Schrichten/Ohm/Nebeling 等 Sauerland/Siegerland 同业）。

---

## 目录/展会轨 Batch129dir

> 合并前重读 CSV（直播基线 **4333** / **3026**；Website Batch122 后 steering）。合并后基线：**4351** / **3042**。

### 累计（Batch129dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4351** |
| high / medium | **4071** / **280** |
| 唯一域名 | **3042** |
| 含电话 / 含城市 | **3756** / **3838** |
| 非 .de 邮箱 | **1162** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4019** |
| design_studio | **183** |
| oem_buyer | **114** |
| sourcing | **35** |

### 本轨成果（Batch129dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **73** |
| 有邮箱命中 | **37** |
| 本轨净增邮箱 | **18**（high **18** / medium **0**） |
| 相对基线 4333/3026 | **+18** / **+16** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B128 域名队列 | 空 |
| Eifel/Hunsrück/Weserbergland/Harz/Bodensee + RLP/NS 微城 × kw | 有效（74 城，DDG 164 + Bing 56） |
| Bing Maps / Europages | 部分（maps 30 / ep 12） |
| Fakuma/VDWF DDG | 挑战页，跳过 |
| WLW / GS | 跳过 / 耗尽 |
| 产量 | 73 候选核验 / 37 命中 / 质量门后 **+18**；剔金属 Umform、假人泡沫、仅 Verwaltung 等 |

### 本轨新增邮箱（共 18）

- `info@atplast.de` (high, overseas_peer_overflow) · Idar-Oberstein
- `u.labusga@la-kunststoff.de` (high, overseas_peer_overflow) · Birkenfeld
- `kontakt@jost-plastec.de` (high, overseas_peer_overflow) · Ingelheim
- `info@zeller-plastik.de` (high, oem_buyer) · Zell
- `info@winkler-werkzeugbau.de` (high, overseas_peer_overflow) · Taufkirchen
- `info@gartzke-kunststoffe.de` (high, overseas_peer_overflow) · Hameln
- `c.gartzke@gartzke-kunststoffe.de` (high, overseas_peer_overflow) · Hameln
- `k-galleske@gartzke-kunststoffe.de` (high, overseas_peer_overflow) · Hameln
- `info@rk-werkzeugbau.de` (high, overseas_peer_overflow) · Düsseldorf
- `info@moldtecs.com` (high, oem_buyer) · Bad Harzburg
- `info@pohl-kunststofftechnik.de` (high, overseas_peer_overflow) · Nentershausen
- `info@memoplast.de` (high, overseas_peer_overflow) · Troisdorf
- `info@kunststoffspritzguss-service.de` (high, overseas_peer_overflow) · Syke
- `info@ks-kunststoff.de` (high, overseas_peer_overflow) · Zweibrücken
- `kontakt@k-form.com` (high, overseas_peer_overflow) · Minden
- `info@formwerk.eu` (high, overseas_peer_overflow) · Neukirchen
- `info@rr-kunststoff.de` (high, overseas_peer_overflow) · Saalburg-Ebersdorf
- `verkauf@gbm-kunststoff.com` (high, overseas_peer_overflow) · Hamburg

### 产物

- `data/germany_raw/batch129dir_*.json`
- `data/germany_raw/batch129dir_next_search_seeds.json`

### 状态

Batch129dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch130dir（下一城带：Sauerland/Siegerland/Westerwald/Taunus）。全国目录轨饱和仍高，但本带仍挖出 **+18** 新邮（含 MoldTecs Bad Harzburg OEM、Gartzke Hameln 具名）。

## 目录/展会轨 Batch128dir

> 合并前重读 CSV（直播基线 **4327** / **3021**；指令预期 4327）。合并后基线：**4329** / **3023**。

### 累计（Batch128dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4329** |
| high / medium | **4049** / **280** |
| 唯一域名 | **3023** |
| 含电话 / 含城市 | **3736** / **3816** |
| 非 .de 邮箱 | **1155** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4002** |
| design_studio | **182** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本轨成果（Batch128dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **5** |
| 有邮箱命中 | **3** |
| 本轨净增邮箱 | **2**（high **2** / medium **0**） |
| 相对基线 4327/3021 | **+2** / **+2** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B127 域名队列 | 空 |
| Lausitz/BB/MV + Mecklenburg/Uckermark/Spreewald/Altmark × kw | 有效（103 城，search 206） |
| Bing Maps / Europages / Fakuma | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| 产量 | **极薄**：5 候选 / 3 命中 / 剔 1 非 ICP（Thermokon 传感器） |

### 本轨新增邮箱（共 2）

- `info@metra-kunststoffdesign.de` (high, design_studio)
- `info@rskunststoffgmbh.de` (high, overseas_peer_overflow)

### 产物

- `data/germany_raw/batch128dir_*.json`
- `data/germany_raw/batch128dir_next_search_seeds.json`

### 状态

Batch128dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch129dir（下一城带：Eifel/Hunsrück/Weserbergland/Harz/Bodensee）。全国目录轨饱和明显，仍按「应有尽有」推进。

## 目录/展会轨 Batch127dir

> 合并前重读 CSV（Website B121 后直播基线 **4324** / **3018**；指令预期 4324；目录轨原基线 4316）。合并后基线：**4327** / **3021**。

### 累计（Batch127dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4327** |
| high / medium | **4047** / **280** |
| 唯一域名 | **3021** |
| 含电话 / 含城市 | **3735** / **3815** |
| 非 .de 邮箱 | **1155** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **4001** |
| design_studio | **181** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本轨成果（Batch127dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **4** |
| 有邮箱命中 | **4** |
| 本轨净增邮箱 | **3**（high **3** / medium **0**） |
| 相对基线 4324/3018 | **+3** / **+3** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B126 域名队列 | 空 |
| Sachsen/Oberfranken + Vogtland/Erzgebirge/Thüringen × kw | 有效（117 城，search 234） |
| Bing Maps / Europages / Fakuma | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| 产量 | 全国饱和，新域名稀薄（本批仅 4 候选） |

### 本轨新增邮箱（共 3）

- `info@1st-mould.de` (high)
- `info@mk-kunststofftechnik.com` (high)
- `info@mankeplast.de` (high)

### 产物

- `data/germany_raw/batch127dir_*.json`
- `data/germany_raw/batch127dir_next_search_seeds.json`

### 状态

Batch127dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch128dir（下一城带：Lausitz/Brandenburg/MV 东）。

## 目录/展会轨 Batch126dir

> 合并前重读 CSV（直播基线 **4312** / **3013**；指令预期 4312）。合并后基线：**4316** / **3017**。

### 累计（Batch126dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4316** |
| high / medium | **4036** / **280** |
| 唯一域名 | **3017** |
| 含电话 / 含城市 | **3725** / **3804** |
| 非 .de 邮箱 | **1154** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3992** |
| design_studio | **179** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本轨成果（Batch126dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **11** |
| 有邮箱命中 | **7** |
| 本轨净增邮箱 | **4**（high **2** / medium **2**） |
| 相对基线 4312/3013 | **+4** / **+4** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B125 域名队列 | 空 |
| Oberbayern/Schwaben/Niederbayern/Oberpfalz/Allgäu × kw | 有效（126 城，search 252） |
| Bing Maps / Europages / Fakuma | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| 质量 | 剔除 Bundesverband modell-formenbau；offdomain borchert/sewa |

### 本轨新增邮箱（共 4）

- `info@ikw-kunststofftechnik.de` (high)
- `info@halbich-kunststoffe.de` (high)
- `info@gaebert-kunststoffteile.de` (medium)
- `info@kwm.de` (medium)

### 产物

- `data/germany_raw/batch126dir_*.json`
- `data/germany_raw/batch126dir_next_search_seeds.json`

### 状态

Batch126dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch127dir（下一城带：Sachsen/Oberfranken 边境）。

## 目录/展会轨 Batch125dir

> 合并前重读 CSV（Website B120 后直播基线 **4306** / **3007**；指令预期 4306）。合并后基线：**4312** / **3013**（已剔除 rechnungswesen@ 会计本地）。

### 累计（Batch125dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4312** |
| high / medium | **4034** / **278** |
| 唯一域名 | **3013** |
| 含电话 / 含城市 | **3722** / **3800** |
| 非 .de 邮箱 | **1154** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3988** |
| design_studio | **179** |
| oem_buyer | **110** |
| sourcing | **35** |

### 本轨成果（Batch125dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **14** |
| 有邮箱命中 | **9** |
| 本轨净增邮箱 | **6**（high **5** / medium **1**） |
| 相对基线 4306/3007 | **+6** / **+6** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B124 域名队列 | 空（主靠城种子） |
| Rhein-Main/Pfalz/Saar + BW/Bayern/ST/BB × kw | 有效（144 城） |
| Bing Maps / Europages / Fakuma | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| 质量 | 剔除 plexiglas/roehm 材料商；剔除 rechnungswesen@ |

### 本轨新增邮箱（共 6）

- `info@steck-plastics.de` (high)
- `info@beckmann-kunststoffe.de` (high)
- `info@hiendl.de` (medium)
- `info@gw-werkzeugbau.de` (high)
- `info@mskunststofftechnik.de` (high)
- `hendrik.voelker@jetmold.de` (high)

### 产物

- `data/germany_raw/batch125dir_*.json`
- `data/germany_raw/batch125dir_next_search_seeds.json`

### 状态

Batch125dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch126dir（主靠 Oberbayern/Schwaben 城种子）。

## 目录/展会轨 Batch124dir

> 合并前重读 CSV（直播基线 **4294** / **3001**；指令预期 4294，含 B123dir+Website B118）。合并后基线：**4298** / **3005**。

### 累计（Batch124dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4298** |
| high / medium | **4021** / **277** |
| 唯一域名 | **3005** |
| 含电话 / 含城市 | **3710** / **3786** |
| 非 .de 邮箱 | **1150** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3982** |
| design_studio | **179** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本轨成果（Batch124dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **8** |
| 有邮箱命中 | **7** |
| 本轨净增邮箱 | **4**（high **3** / medium **1**） |
| 相对基线 4294/3001 | **+4** / **+4** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B123 域名队列 | 空（主靠城种子） |
| Nord/SH/MV/Harz/北德 × kw | 有效（99 城，search 198） |
| Bing Maps | 部分（35） |
| Europages DE | 有效（16） |
| Fakuma/VDWF 公开搜索 | 部分（10） |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 4）

- `michael.quast@qm-formtechnik.de` (high)
- `info@zippel-werkzeugbau.de` (high)
- `mail@rm-plast.com` (medium)
- `info@storm-kunststoff.de` (high)

### 产物

- `data/germany_raw/batch124dir_*.json`
- `data/germany_raw/batch124dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch124dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch125dir（下一城带：Rhein-Main/Pfalz/Saar）。

---

## 目录/展会轨 Batch123dir

> 合并前重读 CSV（Website B117 后直播基线 **4281** / **2990**；指令预期 4281）。合并后基线：**4291** / **2999**。

### 累计（Batch123dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4291** |
| high / medium | **4015** / **276** |
| 唯一域名 | **2999** |
| 含电话 / 含城市 | **3703** / **3779** |
| 非 .de 邮箱 | **1148** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3977** |
| design_studio | **177** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本轨成果（Batch123dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **21** |
| 有邮箱命中 | **11** |
| 本轨净增邮箱 | **10**（high **8** / medium **2**） |
| 相对基线 4281/2990 | **+10** / **+9** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B122 域名队列 | 有效（4） |
| Sachsen/Thüringen/Franken/Ost × kw | 有效（104 城，search 208） |
| Bing Maps | 部分（30） |
| Europages DE | 有效（18） |
| Fakuma/VDWF 公开搜索 | 部分（6） |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 10）

- `info@joysonplastec.com` (medium)
- `info@praezisionstools.de` (high)
- `info@terraplastik.de` (high)
- `martin.bauer@terraplastik.de` (high)
- `info@allinplastics.com` (medium)
- `info@former-fab.de` (high)
- `info@praezisionstechnik-dresden.de` (high)
- `info@riplast.de` (high)
- `info@werkzeugbau-glauchau.de` (high)
- `info@frankenplastik.de` (high)

### 产物

- `data/germany_raw/batch123dir_*.json`
- `data/germany_raw/batch123dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch123dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch124dir（主靠 Nord 城种子）（下一城带：Nord/SH/MV/Harz）。

---

## 目录/展会轨 Batch122dir

> 合并前重读 CSV（Website B116 后直播基线 **4271** / **2982**；指令预期 4271）。合并后基线：**4279** / **2988**。

### 累计（Batch122dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4279** |
| high / medium | **4005** / **274** |
| 唯一域名 | **2988** |
| 含电话 / 含城市 | **3692** / **3767** |
| 非 .de 邮箱 | **1145** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3967** |
| design_studio | **175** |
| oem_buyer | **102** |
| sourcing | **35** |

### 本轨成果（Batch122dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **15** |
| 有邮箱命中 | **9** |
| 本轨净增邮箱 | **8**（high **8** / medium **0**） |
| 相对基线 4271/2982 | **+8** / **+6** 域名 |
| 域名队列剩余 | **4** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B121 域名队列 | 有效（5） |
| Südwestfalen/OWL/Hessen/BW/Bayern × kw | 有效（87 城，search 174） |
| Bing Maps | 部分（28） |
| Europages DE | 有效（20） |
| Fakuma/VDWF 公开搜索 | 部分（10） |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 8）

- `udo.orth@formenbau-bockenem.de` (high)
- `kontakt@formenbau-bockenem.de` (high)
- `info@mela-kunststofftechnik.de` (high)
- `info@deutsche-thermo.de` (high)
- `lv@deutsche-thermo.de` (high)
- `info@toolmoulding.de` (high)
- `info@scheplast.de` (high)
- `info@cnc-teschke.de` (high)

### 产物

- `data/germany_raw/batch122dir_*.json`
- `data/germany_raw/batch122dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch122dir 已合并；gsbiz **0**；域名队列 **4** 供 Batch123dir（下一城带：Sachsen/Thüringen/Franken）。

---

## 目录/展会轨 Batch121dir

> 合并前重读 CSV（直播基线 **4260** / **2972**；指令预期 4260；Website B116 未改变或已对齐）。合并后基线：**4267** / **2979**。

### 累计（Batch121dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4267** |
| high / medium | **3993** / **274** |
| 唯一域名 | **2979** |
| 含电话 / 含城市 | **3683** / **3755** |
| 非 .de 邮箱 | **1145** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3959** |
| design_studio | **173** |
| oem_buyer | **100** |
| sourcing | **35** |

### 本轨成果（Batch121dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **17** |
| 有邮箱命中 | **9** |
| 本轨净增邮箱 | **7**（high **7** / medium **0**） |
| 相对基线 4260/2972 | **+7** / **+7** 域名 |
| 域名队列剩余 | **5** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B120 域名队列 | 有效（8） |
| Niederrhein/Ruhr/Sauerland × kw DDG/Bing | 有效（59 城，search 118） |
| Bing Maps | 部分（25） |
| Europages DE | 有效（24；外国 peer 已剔） |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 7）

- `post@withoeft-werkzeuge.de` (high)
- `info@jhwerkzeug.de` (high)
- `info@koblenzer-werkzeugbau.de` (high)
- `info@werkzeugbau-schulz.de` (high)
- `info@horst-kunststofftechnik.de` (high)
- `info@werkzeugbau-schmidt.com` (high)
- `info@cnc-connection-germany.de` (high)

### 产物

- `data/germany_raw/batch121dir_*.json`
- `data/germany_raw/batch121dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch121dir 已合并；gsbiz **0**；域名队列 **5** 供 Batch122dir（下一城带：Südwestfalen/OWL/Hessen）。

---

## 目录/展会轨 Batch120dir

> 合并前重读 CSV（Website B115 后直播基线 **4254** / **2966**；指令预期 4254）。合并后基线：**4260** / **2972**。

### 累计（Batch120dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4260** |
| high / medium | **3986** / **274** |
| 唯一域名 | **2972** |
| 含电话 / 含城市 | **3676** / **3748** |
| 非 .de 邮箱 | **1144** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3952** |
| design_studio | **173** |
| oem_buyer | **100** |
| sourcing | **35** |

### 本轨成果（Batch120dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **24** |
| 有邮箱命中 | **8** |
| 本轨净增邮箱 | **6**（high **5** / medium **1**） |
| 相对基线 4254/2966 | **+6** / **+6** 域名 |
| 域名队列剩余 | **8** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B119 域名队列 | 有效（7，via b119_domain_queue） |
| Rheinland 城 × 关键词 DDG/Bing | 有效（search pages 60） |
| Bing Maps | 部分（15） |
| Europages DE | 有效（14；外国 peer 已剔） |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 6）

- `info@plastec-technology.com` (high)
- `info@singold-kunststoff.de` (high)
- `info@ks-engineering-tools.de` (high)
- `info@spritzgusswerkzeuge.de` (high)
- `info@werkzeugbau-hotz.de` (high)
- `info@schneider-technologies.de` (medium)

### 产物

- `data/germany_raw/batch120dir_*.json`
- `data/germany_raw/batch120dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch120dir 已合并；gsbiz **0**；域名队列 **8** 供 Batch121dir。

---

## 目录/展会轨 Batch119dir

> 合并前重读 CSV（Website B114 后直播基线 **4237** / **2955**；指令预期 4237）。合并后基线：**4247** / **2965**。

### 累计（Batch119dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4247** |
| high / medium | **3974** / **273** |
| 唯一域名 | **2965** |
| 含电话 / 含城市 | **3664** / **3737** |
| 非 .de 邮箱 | **1143** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3946** |
| design_studio | **172** |
| oem_buyer | **94** |
| sourcing | **35** |

### 本轨成果（Batch119dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **24** |
| 有邮箱命中 | **14** |
| 本轨净增邮箱 | **10**（high **7** / medium **3**） |
| 相对基线 4237/2955 | **+10** / **+10** 域名 |
| 域名队列剩余 | **7** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B118 域名队列 | 有效（via b118_domain_queue） |
| NRW 中等城 × 关键词 DDG/Bing | 有效（via search） |
| Europages DE | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| Druckguss / Stanz / HR locals | 质量剔除 |

### 本轨新增邮箱（共 10）

- `sales@jcb-plastics.com` (high)
- `kontakt@praeziform.de` (high)
- `info@httooling.de` (high)
- `info@stemmle-kunststofftechnik.de` (high)
- `info@trowista.de` (medium)
- `info@brueckner-kunststoffspritzerei.de` (high)
- `info@precisionmould-germany.com` (high)
- `220pferber@megatec-gmbh.de` (medium)
- `info@brinkmann-gmbh.de` (medium)
- `info@wds-werkzeugbau.de` (high)

### 产物

- `data/germany_raw/batch119dir_*.json`
- `data/germany_raw/batch119dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch119dir 已合并；gsbiz **0**；域名队列 **7** 供 Batch120dir。

---

## 目录/展会轨 Batch118dir

> 合并前重读 CSV（基线 **4227** / **2946**）。合并后基线：**4234** / **2953**。

### 累计（Batch118dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4234** |
| high / medium | **3964** / **270** |
| 唯一域名 | **2953** |
| 含电话 / 含城市 | **3653** / **3724** |
| 非 .de 邮箱 | **1141** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3936** |
| design_studio | **171** |
| oem_buyer | **92** |
| sourcing | **35** |

### 本轨成果（Batch118dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **36** |
| 有邮箱命中 | **23** |
| 本轨净增邮箱 | **7**（high **5** / medium **2**） |
| 相对基线 4227/2946 | **+7** / **+7** 域名 |
| 域名队列剩余 | **11** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B117 域名队列 | 有效 |
| 种子城 × 关键词 DDG/Bing | 有效（via search） |
| Europages DE | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| Druckguss / 加热暖通 / 门户 | 质量剔除 |

### 本轨新增邮箱（共 7）

- `info@lmk-werkzeugbau.de` (high)
- `info@weku.de` (high)
- `info@werkzeugbau-reinartz.de` (medium)
- `info@namac.de` (medium)
- `info@bevaplast.de` (high)
- `info@geweku.de` (high)
- `info@inweku.com` (high)

### 产物

- `data/germany_raw/batch118dir_*.json`
- `data/germany_raw/batch118dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch118dir 已合并；gsbiz **0**；域名队列 **11** 供 Batch119dir。

---

## 目录/展会轨 Batch117dir

> 合并前重读 CSV（基线 **4219** / **2938**）。合并后基线：**4227** / **2946**。

### 累计（Batch117dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4227** |
| high / medium | **3959** / **268** |
| 唯一域名 | **2946** |
| 含电话 / 含城市 | **3647** / **3717** |
| 非 .de 邮箱 | **1140** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3929** |
| design_studio | **171** |
| oem_buyer | **92** |
| sourcing | **35** |

### 本轨成果（Batch117dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **18** |
| 有邮箱命中 | **10** |
| 本轨净增邮箱 | **8**（high **7** / medium **1**） |
| 相对基线 4219/2938 | **+8** / **+8** 域名 |
| 域名队列剩余 | **15** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B116 域名队列 | 有效（via b116_domain_queue） |
| 种子城 × 关键词 DDG/Bing | 有效（via search） |
| Europages DE | 部分 |
| WLW / GS | 跳过 / 耗尽 |
| Druckguss | **质量剔除** |

### 本轨新增邮箱（共 8）

- `corina.kilian@tausan-tool.com` (high)
- `info@krampe.de` (high)
- `info@krampe-werkzeuge.de` (high)
- `a.heim@heim-pt.de` (high)
- `kontakt@afk-kunststoff.de` (high)
- `info@khduschek.de` (medium)
- `info@gfkabsi.de` (high)
- `info@plexi-jaeger.de` (high)

### 产物

- `data/germany_raw/batch117dir_*.json`
- `data/germany_raw/batch117dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch117dir 已合并；gsbiz **0**；域名队列 **15** 供 Batch118dir。

---

## 目录/展会轨 Batch116dir

> 合并前重读 CSV（基线 **4204** / **2928**）。合并后基线：**4219** / **2938**。

### 累计（Batch116dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4219** |
| high / medium | **3952** / **267** |
| 唯一域名 | **2938** |
| 含电话 / 含城市 | **3639** / **3711** |
| 非 .de 邮箱 | **1139** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3921** |
| design_studio | **171** |
| oem_buyer | **92** |
| sourcing | **35** |

### 本轨成果（Batch116dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **29** |
| 有邮箱命中 | **15** |
| 本轨净增邮箱 | **15**（high **12** / medium **3**） |
| 相对基线 4204/2928 | **+15** / **+10** 域名 |
| 域名队列剩余 | **12** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| B115 域名队列 | 有效（via b115_domain_queue） |
| 种子城 × 关键词 DDG/Bing | 有效（via search） |
| Europages DE | 部分 |
| WLW / GS | 跳过 / 耗尽 |

### 本轨新增邮箱（共 15）

- `info@forma-coburg.de` (high)
- `korn@fromm-praezision.de` (high)
- `steidle@fromm-praezision.de` (high)
- `macedo@fromm-praezision.de` (high)
- `schmidt@fromm-praezision.de` (high)
- `paul@fromm-praezision.de` (high)
- `info@lausberg-kunststofftechnik.de` (high)
- `alexander.may@k-tech.de` (medium)
- `kontakt@k-tech.de` (medium)
- `m.siegele@ser-kunststoffverarbeitung.de` (high)
- `info@eisenmann-druckguss.de` (high)
- `riedmueller@form-sachen.de` (high)
- `info@saratools.com` (high)
- `info@sartorius-werkzeuge.de` (high)
- `info@fischer-plastic-praezision.de` (medium)

### 产物

- `data/germany_raw/batch116dir_*.json`
- `data/germany_raw/batch116dir_next_search_seeds.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`

### 状态

Batch116dir 已合并；gsbiz **0**；域名队列 **12** 供 Batch117dir。

---

## 目录/展会轨 Batch115dir

> 合并前重读 CSV（基线 **4194** / **2921**）。合并后基线：**4200** / **2927**。

### 累计（Batch115dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4200** |
| high / medium | **3936** / **264** |
| 唯一域名 | **2927** |
| 含电话 / 含城市 | **3621** / **3697** |
| 非 .de 邮箱 | **1137** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3906** |
| design_studio | **170** |
| oem_buyer | **89** |
| sourcing | **35** |

### 本轨成果（Batch115dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **16** |
| 有邮箱命中 | **10** |
| 本轨净增邮箱 | **6**（high **6** / medium **0**） |
| 相对基线 4194/2921 | **+6** / **+6** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0**（GS 耗尽） |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| 排空最后 1 gsbiz | 完成 |
| 中小城镇 × 关键词 DDG/Bing | **主贡献**（via search） |
| 展会目录 | 弱 |
| 商会/目录 | 部分（噪声多，已滤） |
| WLW | 跳过 |

### 饱和备注

Gelbe Seiten gsbiz **已耗尽**。后续目录轨以 **地图/网页检索 + 域名队列** 为主；本批已写入 `queue_directory_domains_remaining.txt`（**0**）。

### 本轨新增邮箱（共 6）

- `info@kemmer-praezision.com` (high)
- `info@riedl-kunststofftechnik.de` (high)
- `info@k-tech.de` (high)
- `info@praezis-dresden.de` (high)
- `info@settele.de` (high)
- `info@skn-technik.de` (high)

### 产物

- `data/germany_raw/batch115dir_*.json`
- `data/germany_raw/queue_directory_domains_remaining.txt`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`（空）

### 状态

Batch115dir 已合并；gsbiz **0**；域名队列 **0** 供 Batch116dir。

---

## 目录/展会轨 Batch114dir

> 合并前重读 CSV（基线 **4181** / **2909**）。合并后基线：**4192** / **2919**。

### 累计（Batch114dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4192** |
| high / medium | **3928** / **264** |
| 唯一域名 | **2919** |
| 含电话 / 含城市 | **3614** / **3689** |
| 非 .de 邮箱 | **1135** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3900** |
| design_studio | **169** |
| oem_buyer | **88** |
| sourcing | **35** |

### 本轨成果（Batch114dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **33** |
| 有邮箱命中 | **12** |
| 本轨净增邮箱 | **11**（high **11** / medium **0**） |
| 相对基线 4181/2909 | **+11** / **+10** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **1** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| 排空 gsbiz **30** | 有效（主贡献） |
| 城市×关键词 Bing/DDG | 有效（via search **10**） |
| Europages DE 深页 | 部分（多页 404） |
| 协会/展会目录 | 弱（多数 404） |
| GS 新 id | 枯竭（扩期仅 +2） |
| WLW / Örtliche / Kompass | 跳过 |

### 饱和备注

Gelbe Seiten gsbiz 池高度重叠；本批净增主要来自 **已排空的 30 ids + 城市×关键词网页检索**，而非新 GS 列表页。

### 本轨新增邮箱（共 11）

- `info@eurotech-kunststofftechnik.de` (high)
- `info@dlkunststofftechnik.de` (high)
- `info@gh-kunststofftechnik.de` (high)
- `info@kunststofftechnik-hennigsdorf.de` (high)
- `info@borchert-fuhrmann.de` (high)
- `info@isomer.de` (high)
- `info@hf-fischer.de` (high)
- `info@rotasin.de` (high)
- `mail@schnorr.de` (high)
- `automotive@schnorr.de` (high)
- `stark@stark-leisten.de` (high)

### 产物

- `data/germany_raw/batch114dir_*.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch114dir 已合并；域名队列 **0**；gsbiz 余 **1**。

---

## 目录/展会轨 Batch113dir

> 合并前重读 CSV（基线 **4177** / **2905**；父指令约 4177/2921）。合并后基线：**4181** / **2909**。

### 累计（Batch113dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4181** |
| high / medium | **3917** / **264** |
| 唯一域名 | **2909** |
| 含电话 / 含城市 | **3604** / **3678** |
| 非 .de 邮箱 | **1135** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3889** |
| design_studio | **169** |
| oem_buyer | **88** |
| sourcing | **35** |

### 本轨成果（Batch113dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **20** |
| 有邮箱命中 | **7** |
| 本轨净增邮箱 | **4**（high **2** / medium **2**） |
| 相对基线 4177/2905 | **+4** / **+4** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **0** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| GS 东/北联邦州 + niche | 有效但新 gsbiz 仅 **2**（重叠高） |
| Europages DE | 部分（via ep **7**） |
| DDG/Bing | 部分（via search **2**） |
| Örtliche / Kompass / WLW | 跳过 |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 gsbiz | **11** + 扩 **2** |
| 多源 jobs | **76** |
| 本轮核验 | **20** |
| 再播种 | gsbiz **0** |

### 本轨新增邮箱（共 4）

- `sales@hoerauf.com` (high)
- `kontakt@merima.de` (high)
- `kluecher@geruschke.de` (medium)
- `info@ttp-papenburg.de` (medium)

### 阻塞 / 备注

- GS 全国/区域页高度重叠，新 id 枯竭
- 见 `data/germany_raw/batch113dir_merge_log.json`

### 产物

- `data/germany_raw/batch113dir_*.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch113dir 已合并；域名队列 **0**；gsbiz 余 **0**。

---

## 目录/展会轨 Batch112dir

> 合并前重读 CSV（基线 **4160** / **2893**）。合并后基线：**4171** / **2902**。

### 累计（Batch112dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4171** |
| high / medium | **3909** / **262** |
| 唯一域名 | **2902** |
| 含电话 / 含城市 | **3595** / **3668** |
| 非 .de 邮箱 | **1133** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3885** |
| design_studio | **168** |
| oem_buyer | **83** |
| sourcing | **35** |

### 本轨成果（Batch112dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **31** |
| 有邮箱命中 | **15** |
| 本轨净增邮箱 | **11**（high **11** / medium **0**） |
| 相对基线 4160/2893 | **+11** / **+9** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **11** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| GS niche/regions + 余 9 gsbiz | 有效（via gsbiz/ajax） |
| Europages DE p1–3 | 有效（via ep **9**；外国已滤） |
| DDG/Bing 区域查询 | 部分（via search **0**） |
| Das Örtliche / Kompass / WLW | **跳过** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 gsbiz | **9** + niche 扩 **36** |
| 多源 jobs | **75** |
| 本轮核验 | **31**（curl 短超时） |
| 再播种 | gsbiz **11** |

### 本轨新增邮箱（共 11）

- `hofmann@erodiertechnik-hofmann.de` (high)
- `info@ets-erodiertechnik.de` (high)
- `info@korthals-erodiertechnik.de` (high)
- `info@erotec-berlin.de` (high)
- `aldenhoven@halex.de` (high)
- `gussago@halex.de` (high)
- `verdello@halex.de` (high)
- `info@jaeger-et.de` (high)
- `kontakt@eco-kunststoff.com` (high)
- `order@vbkunststoffe.de` (high)
- `info@technikinform.de` (high)

### 阻塞 / 备注

- WLW / Örtliche / Kompass — 按策略跳过
- 见 `data/germany_raw/batch112dir_merge_log.json`

### 产物

- `data/germany_raw/batch112dir_*.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch112dir 已合并；域名队列 **0**；gsbiz 余 **11**。

---

## 目录/展会轨 Batch111dir

> 合并前重读 CSV（Website B110 后基线 **4140** / **2873**；非 4136）。合并后基线：**4160** / **2893**。

### 累计（Batch111dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4160** |
| high / medium | **3898** / **262** |
| 唯一域名 | **2893** |
| 含电话 / 含城市 | **3585** / **3658** |
| 非 .de 邮箱 | **1132** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3874** |
| design_studio | **168** |
| oem_buyer | **83** |
| sourcing | **35** |

### 本轨成果（Batch111dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **38** |
| 有邮箱命中 | **22** |
| 本轨净增邮箱 | **20**（high **19** / medium **1**） |
| 相对基线 4140/2873 | **+20** / **+20** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **9** |

### 扩展来源（本批）

| 来源 | 结果 |
|---|---|
| Gelbe Seiten niche + 余 4 gsbiz | 有效（via gsbiz/ajax） |
| Europages DE | 有效（via ep **12**；外国同行已滤） |
| DDG/Bing HTML | 部分（via search **1**） |
| Das Örtliche | 部分（有字节，贡献弱） |
| Kompass DE | **无效**（0 bytes） |
| Fakuma/Motek/K/VDWF | 弱/404；WLW 跳过 |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 gsbiz | **4** + niche 扩 **31** |
| 多源 jobs | **80** |
| 本轮核验 | **38** |
| 超时强制 no_email | kunststoff-kaeppel.de, hartfelder-cnc.de, jura-plast.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz **9** |

### 本轨新增邮箱（共 20）

- `info@ks-kunststoffbau.de` (high)
- `info@dmd-werkzeug.de` (high)
- `office@agema-germany.de` (high)
- `info@esm-mueller.de` (high)
- `info@carlon.de` (high)
- `info@kaufmann-zertech.de` (high)
- `info@ma-kro.de` (high)
- `info@poggengerd.de` (high)
- `info@seipp-kehl.de` (high)
- `info@winter-mechanik.de` (high)
- `info@werimo.de` (high)
- `r.mann@braungmbh.com` (medium)
- `info@ito-plast.de` (high)
- `info@kirsch-kunststofftechnik.de` (high)
- `info@recknagel-praezisionsteile.de` (high)
- `info@qin-form.de` (high)
- `info@formpack.de` (high)
- `vertrieb@krumbeck-kunststoff.de` (high)
- `kontakt@finado-gmbh.de` (high)
- `info@ha-beck.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过；Kompass 无内容；展会目录薄
- 保留 B110：goletz-gmbh / oelfke / kompetenzkunststoff
- 见 `data/germany_raw/batch111dir_merge_log.json`

### 产物

- `data/germany_raw/batch111dir_*.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch111dir 已合并；域名队列 **0**；gsbiz 余 **9**。

---

## 目录/展会轨 Batch110dir

> 合并前重读 CSV（Website B109 后基线 **4108** / **2854**；非 4103）。合并后基线：**4136** / **2871**。

### 累计（Batch110dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4136** |
| high / medium | **3875** / **261** |
| 唯一域名 | **2871** |
| 含电话 / 含城市 | **3562** / **3634** |
| 非 .de 邮箱 | **1131** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3854** |
| design_studio | **168** |
| oem_buyer | **80** |
| sourcing | **34** |

### 本轨成果（Batch110dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **45** |
| 有邮箱命中 | **19** |
| 本轨净增邮箱 | **28**（high **28** / medium **0**） |
| 相对基线 4108/2854 | **+28** / **+17** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **4** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B109dir gsbiz | **21** |
| 扩展 | formenbau/spritzguss p5–11 + niche（Erodieren/Blasformen）+ Europages；niche 补 **67** gsbiz |
| 本轮核验队列 | **45**（42+ resume；3 超时 forced no_email） |
| 超时强制 no_email | hellerkunststoffe.de, kvr-radeburg.de, psg-online.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **4**（cached ajax） |

### 方法

1. 排空 gsbiz **21** + 扩展 → Impressum（`.json` out_path；resume `.jsonl`）  
2. 合并前重读 **4108/2854**（保留 B109 行）  
3. 质量剔除：portal/webmail/off-domain  
4. 再播种：gsbiz 余 **4**

### 本轨新增邮箱（共 28）

- `info@crt-goering.de` (high)
- `info@cnc-maske.de` (high)
- `info@buettner-praezisionswerk.de` (high)
- `e.buettner@buettner-praezisionswerk.de` (high)
- `d.dedauw@buettner-praezisionswerk.de` (high)
- `a.vorsatz@buettner-praezisionswerk.de` (high)
- `m.poempner@buettner-praezisionswerk.de` (high)
- `j.grossmann@buettner-praezisionswerk.de` (high)
- `ch.lierkamp@buettner-praezisionswerk.de` (high)
- `f.knoechel@buettner-praezisionswerk.de` (high)
- `info@boela.de` (high)
- `kontakt@erotool.com` (high)
- `info@fhdunker.de` (high)
- `info@froetek.de` (high)
- `info@hebach.de` (high)
- `info@firma-wennrich.de` (high)
- `info@inden-gmbh.de` (high)
- `info@lqm-heers.de` (high)
- `info@lueco-plastic.de` (high)
- `info@nowack.de` (high)
- `info@ow-feinwerk.de` (high)
- `info@prae-aero.de` (high)
- `info@spohrgmbh.de` (high)
- `info@schmitz-cnc.de` (high)
- `t.schmitz@schmitz-cnc.de` (high)
- `m.senger@schmitz-cnc.de` (high)
- `m.mestekemper@schmitz-cnc.de` (high)
- `av@schmitz-cnc.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 3 域名超时 → forced no_email
- GS bundesweit 重复率高；靠 niche 类目补量
- 见 `data/germany_raw/batch110dir_merge_log.json`

### 产物

- `data/germany_raw/batch110dir_impressum.json`
- `data/germany_raw/batch110dir_verified.json` / `batch110dir_hits.json`
- `data/germany_raw/batch110dir_merge_log.json` / `batch110dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch110dir 已合并；域名队列 **0**；gsbiz 余 **4** 供 Batch111dir。

---

## 目录/展会轨 Batch109dir

> 合并前重读 CSV（基线 **4078** / **2827**）。合并后基线：**4103** / **2849**。

### 累计（Batch109dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4103** |
| high / medium | **3842** / **261** |
| 唯一域名 | **2849** |
| 含电话 / 含城市 | **3529** / **3614** |
| 非 .de 邮箱 | **1130** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3826** |
| design_studio | **165** |
| oem_buyer | **78** |
| sourcing | **34** |

### 本轨成果（Batch109dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **45** |
| 有邮箱命中 | **23** |
| 本轨净增邮箱 | **25**（high **23** / medium **2**） |
| 相对基线 4078/2827 | **+25** / **+22** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **21** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B108dir gsbiz | **50** |
| 扩展 | BW/BY 城 + Präzision/2K/Silikon/LSR 类目；ajax **75** → 新 gsbiz **75**（全部取用） |
| 本轮核验队列 | **45** |
| WLW | CAPTCHA — 跳过 |
| 再播种 | formenbau/spritzguss p3–4 + Ruhr 城 → gsbiz **21** |

### 方法

1. 排空 gsbiz **50** + GS 扩展 → Impressum（out_path `.json` 避免 `.jsonll`）  
2. 合并前重读 **4078/2827**  
3. 质量剔除：portal/IHK/the.net/off-domain/admin  
4. 再播种：gsbiz 余 **21**

### 本轨新增邮箱（共 25）

- `info@1st-cut.de` (high)
- `mail@alois-mueller.de` (high)
- `info@garthe-stoltenhoff.de` (high)
- `info@filatech.de` (high)
- `info@i-winterhalder.de` (high)
- `info@d-reinhardt.de` (high)
- `info@kueckundhoeck.de` (high)
- `info@kunstguss.net` (high)
- `post@koeckert.de` (high)
- `info@osbra.com` (medium)
- `peter.mayer@osbra.com` (medium)
- `info@praezision-mueller.de` (high)
- `info@plasticguss.de` (high)
- `info@pwg-leutkirch.de` (high)
- `info@siegle.de` (high)
- `mail@schuetz-berlin.de` (high)
- `info@stintmann.de` (high)
- `info@ppm-pforzheim.com` (high)
- `g.roth@ppm-pforzheim.com` (high)
- `d.mueller@ppm-pforzheim.com` (high)
- `info@tik-gmbh.com` (high)
- `info@wiederholt.com` (high)
- `info@wiro.com` (high)
- `info@wto.de` (high)
- `manz@wilhelm-manz.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch109dir_merge_log.json`

### 产物

- `data/germany_raw/batch109dir_impressum.json`
- `data/germany_raw/batch109dir_verified.json` / `batch109dir_hits.json`
- `data/germany_raw/batch109dir_merge_log.json` / `batch109dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch109dir 已合并；域名队列 **0**；gsbiz 余 **21** 供 Batch110dir。

---

## 目录/展会轨 Batch108dir

> 合并前重读 CSV（Website B106–B108 后基线 **4057** / **2806**）。合并后基线：**4078** / **2827**。

### 累计（Batch108dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4078** |
| high / medium | **3819** / **259** |
| 唯一域名 | **2827** |
| 含电话 / 含城市 | **3505** / **3590** |
| 非 .de 邮箱 | **1121** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3801** |
| design_studio | **165** |
| oem_buyer | **78** |
| sourcing | **34** |

### 本轨成果（Batch108dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **55** |
| 有邮箱命中 | **27** |
| 本轨净增邮箱 | **21**（high **21** / medium **0**） |
| 相对基线 4057/2806 | **+21** / **+21** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **50** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B107dir gsbiz | **32** |
| 扩展 | BW/BY/HE/NRW 城 + spritz/thermo/elastomer 类目；ajax **105** → 新 gsbiz **140**（取 90，余 50） |
| 本轮核验队列 | **55**（53 完成 + 2 超时 forced no_email） |
| 超时强制 no_email | onlinehome.de, werto-plast.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **50** |

### 方法

1. 排空 gsbiz **32** + GS 扩展 → Impressum（未整队重跑，用 `.jsonll` 部分结果收尾）  
2. 合并前重读 **4057/2806**（Website B106–B108 已入）  
3. 质量剔除：portal/presse/thyssenkrupp/formbeton/off-domain/msn；保留 brand_related medium  
4. 再播种：gsbiz 余 **50**

### 本轨新增邮箱（共 21）

- `info@aptoplast.com` (high)
- `info@bayer-praezisionsteile.de` (high)
- `info@feintech-richter.de` (high)
- `info@g-k-schoen.de` (high)
- `info@hms-gmbh.eu` (high)
- `info@greineroffenburg.de` (high)
- `info@kern.de` (high)
- `info@cncform.de` (high)
- `info@koenig-automotive.de` (high)
- `info@hallerkt.de` (high)
- `sekretariat@komos.de` (high)
- `info@kostal-co.de` (high)
- `info@rmax-poliertechnik.de` (high)
- `info@rietzel-plexi.de` (high)
- `info@schreck-kunststofftechnik.com` (high)
- `office@richter-wolfgang.com` (high)
- `info@schulze-schulze.com` (high)
- `info@profiform-feinwerktechnik.de` (high)
- `info@kremm.de` (high)
- `info@uebelgoenne.de` (high)
- `fp@waltonphilipps.com` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 2 域名超时 → forced no_email（onlinehome.de, werto-plast.de）
- 见 `data/germany_raw/batch108dir_merge_log.json`

### 产物

- `data/germany_raw/batch108dir_impressum.json`
- `data/germany_raw/batch108dir_verified.json` / `batch108dir_hits.json`
- `data/germany_raw/batch108dir_merge_log.json` / `batch108dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch108dir 已合并；域名队列 **0**；gsbiz 余 **50** 供 Batch109dir。

---

## 目录/展会轨 Batch107dir

> 合并前重读 CSV（基线 **4012** / **2769**；Website B106 可能并行写入）。合并后基线：**4044** / **2800**。

### 累计（Batch107dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4044** |
| high / medium | **3785** / **259** |
| 唯一域名 | **2800** |
| 含电话 / 含城市 | **3475** / **3556** |
| 非 .de 邮箱 | **1115** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3778** |
| design_studio | **158** |
| oem_buyer | **74** |
| sourcing | **34** |

### 本轨成果（Batch107dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **55** |
| 有邮箱命中 | **34** |
| 本轨净增邮箱 | **32**（high **30** / medium **2**） |
| 相对基线 4012/2769 | **+32** / **+31** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **32** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B106dir gsbiz | **22** |
| 扩展 | 26 城 × formenbau/spritzguss + 12 类目 bundesweit + page2；ajax **67** → 新 gsbiz **112**（取 80 核验，余 32） |
| 本轮核验队列 | **55**（预筛弱域名后） |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **32** |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **22** + GS 城市/类目扩展 → Impressum  
2. 合并前重读 **4012/2769**  
3. 质量剔除：freenet/portal/off-domain；保留 brand_related medium（aundm、knoblauch）  
4. 再播种：gsbiz 余 **32**

### 本轨新增邮箱（共 32）

- `info@bartz-werke.de` (high)
- `info@aundm.eu` (medium)
- `info@arias.de` (high)
- `info@daenekamp.de` (high)
- `kontakt@ewf-steinau.de` (high)
- `anfrage@ewf-steinau.de` (high)
- `info@bm-kunststoffe.de` (high)
- `info@3d-formtec.de` (high)
- `info@fiwec.de` (high)
- `info@gottron-hoffmann.de` (high)
- `service@gms-24.de` (high)
- `info@fwb-gmbh.de` (high)
- `email@eneratio.de` (high)
- `info@kallichundpartner.de` (high)
- `info@hufer-kunststofftechnik.de` (high)
- `info@jakob-partner.de` (high)
- `info@hugo-ackermann.de` (high)
- `info@heinz-feld.de` (high)
- `info@kellercnc.de` (high)
- `mail@hkl-aachen.de` (high)
- `service@kulisch-gmbh.de` (high)
- `info@neuhof-dies.com` (high)
- `info@knoblauch-gmbh.eu` (medium)
- `info@polywerk-berlin.de` (high)
- `info@leicht-mueller.de` (high)
- `info@enkst.de` (high)
- `info@schade-gmbh.de` (high)
- `info@shapetool.de` (high)
- `info@tis-europa.com` (high)
- `info@wefo-spaeth.de` (high)
- `rimmele@formentechnik.com` (high)
- `anselm.baumann@ostpool.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch107dir_merge_log.json`

### 产物

- `data/germany_raw/batch107dir_impressum.json`
- `data/germany_raw/batch107dir_verified.json` / `batch107dir_hits.json`
- `data/germany_raw/batch107dir_merge_log.json` / `batch107dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch107dir 已合并；域名队列 **0**；gsbiz 余 **32** 供 Batch108dir。

---

## 目录/展会轨 Batch106dir

> 合并前重读 CSV（Website B105 后基线 **3985** / **2744**；非 3982）。合并后基线：**4012** / **2769**。

### 累计（Batch106dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **4012** |
| high / medium | **3755** / **257** |
| 唯一域名 | **2769** |
| 含电话 / 含城市 | **3448** / **3526** |
| 非 .de 邮箱 | **1110** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3746** |
| design_studio | **158** |
| oem_buyer | **74** |
| sourcing | **34** |

### 本轨成果（Batch106dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **50** |
| 有邮箱命中 | **32** |
| 本轨净增邮箱 | **27**（high **26** / medium **1**） |
| 相对 Website B105 基线 3985/2744 | **+27** / **+25** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **22** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B105dir gsbiz | **69** |
| 扩展 | NRW 城市 + Formteile/Spritzgießwerkzeuge + 新 gsbiz |
| 本轮核验队列 | **50** |
| 超时强制 no_email | opifexweimar.de, kunststoff-kaeppel.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **22** |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **69** + 城市/类目扩展 → **50** 域名 Impressum  
2. 合并前重读 **3985/2744** = Website B105  
3. 质量剔除：ionos/darmstadt/bau/yumpu/off-domain；保留 agru→frank related medium  
4. 再播种：gsbiz 余 **22**

### 本轨新增邮箱（共 27）

- `info@mjm-werkzeug.de` (high)
- `info@hls-kluge.de` (high)
- `info@composite-sys.de` (high)
- `info@schoenberg-acryl.de` (high)
- `info@tierock-hirth.de` (high)
- `bjoern.kemmler@ycm-consulting.de` (high)
- `info@langetec.de` (high)
- `info@kunststoffspritzguss-24.de` (high)
- `info@debus-aw.de` (high)
- `josef.zemek@rgf-praezision.de` (high)
- `info@cziotec.de` (high)
- `info@brillundadloff.de` (high)
- `sales@brillundadloff.de` (high)
- `info@loekutec.de` (high)
- `info@kunststoffe-giro.de` (high)
- `info@drinhaus-technik.de` (high)
- `info@moelders.de` (high)
- `info@frank-gmbh.de` (medium)
- `info@sattler-scm.de` (high)
- `anfrage@sattler-scm.de` (high)
- `info@ibkopp.de` (high)
- `info@rmm-gmbh.de` (high)
- `info@smd-olpe.de` (high)
- `info@3d-cad-design.de` (high)
- `info@ktr-rethwisch.de` (high)
- `info@woelky-partner.de` (high)
- `info@ib-muenster.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 2 域名超时 → forced no_email
- 见 `data/germany_raw/batch106dir_merge_log.json`

### 产物

- `data/germany_raw/batch106dir_impressum.json`
- `data/germany_raw/batch106dir_verified.json` / `batch106dir_hits.json`
- `data/germany_raw/batch106dir_merge_log.json` / `batch106dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch106dir 已合并；域名队列 **0**；gsbiz 余 **22** 供 Batch107dir。

---

## 目录/展会轨 Batch105dir

> 合并前重读 CSV（基线 **3967** / **2726**；Website B105 未改写或同值）。合并后基线：**3982** / **2741**。

### 累计（Batch105dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3982** |
| high / medium | **3726** / **256** |
| 唯一域名 | **2741** |
| 含电话 / 含城市 | **3421** / **3496** |
| 非 .de 邮箱 | **1110** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3719** |
| design_studio | **157** |
| oem_buyer | **72** |
| sourcing | **34** |

### 本轨成果（Batch105dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **35** |
| 有邮箱命中 | **19** |
| 本轨净增邮箱 | **15**（high **13** / medium **2**） |
| 相对基线 3967/2726 | **+15** / **+15** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余（再播种） | **69** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空末批 gsbiz | **3**（B104dir 余） |
| 新源扩展 | GS 新类目（Spritzgießerei/Kunststoffspritzguss/Erodieren）+ 东/南部城市；Europages DE Formenbau/Spritzguss/Werkzeugbau；DDG |
| 扩展抓取 gsbiz | ~50 新详情页 → 核验队列 **35** |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **69**（域名队列空） |

### 方法

1. 排空末 **3** gsbiz + 非 WLW 新源重建 → Impressum **35**  
2. 合并前重读 **3967/2726**  
3. 质量剔除：muster.de / 混淆垃圾；保留 mks-spritzguss、wb-rau related medium  
4. 再播种：新发现 gsbiz **69**

### 本轨新增邮箱（共 15）

- `info@hujer-lasertechnik.de` (high)
- `info@ptz-prototypen.de` (high)
- `bvt@bvt-bremen.de` (high)
- `mail@toelke-gmbh.de` (high)
- `info@mks-spritzguss.de` (medium)
- `info@schubert-wzb.de` (high)
- `a.g.weiss@adolf-weiss-ing.de` (high)
- `info@zwerenz-industries.de` (high)
- `info@jjweiler.de` (high)
- `d.pfeifer@dp-werkzeugbau.de` (high)
- `info@wb-rau.de` (medium)
- `info@merten-zerspanungstechnik.de` (high)
- `kontakt@springer-zerspanungstechnik.de` (high)
- `nagler@normalien.de` (high)
- `info@dahmen-umformtechnik.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 见 `data/germany_raw/batch105dir_merge_log.json`

### 产物

- `data/germany_raw/batch105dir_impressum.json`
- `data/germany_raw/batch105dir_verified.json` / `batch105dir_hits.json`
- `data/germany_raw/batch105dir_merge_log.json` / `batch105dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch105dir 已合并；域名队列 **0**；gsbiz 再播种 **69** 供 Batch106dir。

---

## 目录/展会轨 Batch104dir

> 合并前重读 CSV（Website B104 后基线 **3947** / **2706**；非 3943）。合并后基线：**3967** / **2726**。

### 累计（Batch104dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3967** |
| high / medium | **3713** / **254** |
| 唯一域名 | **2726** |
| 含电话 / 含城市 | **3406** / **3481** |
| 非 .de 邮箱 | **1110** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3704** |
| design_studio | **157** |
| oem_buyer | **72** |
| sourcing | **34** |

### 本轨成果（Batch104dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **51** |
| 有邮箱命中 | **26** |
| 本轨净增邮箱 | **20**（high **17** / medium **3**） |
| 相对 Website B104 基线 3947/2706 | **+20** / **+20** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **3** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B103dir gsbiz | **79** |
| 扩展 | 中等城市 Formenbau + 新 gsbiz（池将尽） |
| 本轮核验队列 | **51** |
| 超时强制 no_email | erlmann.de, befi-plastic.de, magenta.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **3**（近耗尽） |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **79** + 城市扩展 → **51** 域名 Impressum  
2. 合并前重读 **3947/2706** = Website B104  
3. 质量剔除：fotodesign/maler/pudelwohl/metallbau/metallverarbeitung  
4. 再播种：gsbiz 余 **3**

### 本轨新增邮箱（共 20）

- `service@bero-werkzeugbau.de` (high)
- `info@cst-gmbh.de` (high)
- `info@spey.de` (high)
- `info@jedig-heyns.de` (high)
- `kontakt@mkl-online.com` (medium)
- `info@demgen.de` (high)
- `info@saritec.de` (high)
- `service@stanzerei-werkzeugbau.de` (high)
- `info@fritzschneidergmbh.de` (high)
- `info@praezimolds-gmbh.de` (medium)
- `info@kunststoff-cuba.de` (high)
- `info@bwa-werkzeugbau.de` (high)
- `info@grotefeld-kunststofftechnik.de` (high)
- `info@pape-engineering.com` (medium)
- `info@ds-elektrodenservice.de` (high)
- `elpro@elprotec.de` (high)
- `info@sudholt-wasemann.de` (high)
- `info@modellbau-mueller-gmbh.de` (high)
- `kontakt@sen-ff.de` (high)
- `info@modellundformenbau.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- gsbiz 池近耗尽（余 **3**）
- 见 `data/germany_raw/batch104dir_merge_log.json`

### 产物

- `data/germany_raw/batch104dir_impressum.json`
- `data/germany_raw/batch104dir_verified.json` / `batch104dir_hits.json`
- `data/germany_raw/batch104dir_merge_log.json` / `batch104dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch104dir 已合并；域名队列 **0**；gsbiz 余 **3** 供 Batch105dir。

---

## 目录/展会轨 Batch103dir

> 合并前重读 CSV（Website B103 后基线 **3925** / **2688**；非 3920）。合并后基线：**3943** / **2703**。

### 累计（Batch103dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3943** |
| high / medium | **3692** / **251** |
| 唯一域名 | **2703** |
| 含电话 / 含城市 | **3386** / **3458** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3681** |
| design_studio | **156** |
| oem_buyer | **72** |
| sourcing | **34** |

### 本轨成果（Batch103dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **32** |
| 有邮箱命中 | **17** |
| 本轨净增邮箱 | **18**（high **13** / medium **5**） |
| 相对 Website B103 基线 3925/2688 | **+18** / **+15** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **79** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B102dir gsbiz | **56** |
| 扩展 | Formenbau 城市（Paderborn/Osnabrück/Heidelberg 等）+ werkzeugbau ajax + 新 gsbiz |
| 本轮核验队列 | **32** |
| 超时强制 no_email | wachsmuth.de, netsurf.de, funke-blecher.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **79**（域名队列空） |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **56** + 城市/werkzeugbau 扩展 → **32** 域名 Impressum  
2. 合并前重读 **3925/2688** = Website B103  
3. 质量剔除：the.net junk、dsa-marketing；保留 hetec-online / modellbau-giesserei related medium  
4. 再播种：新 gsbiz ids → **79**

### 本轨新增邮箱（共 18）

- `info@gaertner-lang.de` (high)
- `info@plexiglas-lehmann.de` (high)
- `info@modellbau-giesserei.de` (medium)
- `info@hammergmbh.de` (high)
- `f.herhaus@hetec-online.de` (medium)
- `g.herhaus@hetec-online.de` (medium)
- `t.herhaus@hetec-online.de` (medium)
- `info@hetec-online.de` (medium)
- `info@ucar.de` (high)
- `info@art-tec.de` (high)
- `info@kokillenbau-friedrich.de` (high)
- `info@doerken-wkzbau.de` (high)
- `info@waltergoetz.de` (high)
- `zentrale@bretting-werkzeugbau.de` (high)
- `info@swwp.de` (high)
- `julius@julius-gmbh.de` (high)
- `info@suski.de` (high)
- `m.schwarze@swk-konstruktion.de` (high)

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 3 域名超时 → forced no_email
- 见 `data/germany_raw/batch103dir_merge_log.json`

### 产物

- `data/germany_raw/batch103dir_impressum.json`
- `data/germany_raw/batch103dir_verified.json` / `batch103dir_hits.json`
- `data/germany_raw/batch103dir_merge_log.json` / `batch103dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch103dir 已合并；域名队列 **0**；gsbiz 余 **79** 供 Batch104dir。

---

## 目录/展会轨 Batch102dir

> 合并前重读 CSV（基线 **3903** / **2668**；Website B103 未改写或同值）。合并后基线：**3920** / **2685**。

### 累计（Batch102dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3920** |
| high / medium | **3674** / **246** |
| 唯一域名 | **2685** |
| 含电话 / 含城市 | **3365** / **3436** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3662** |
| design_studio | **155** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch102dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **46** |
| 有邮箱命中 | **22** |
| 本轨净增邮箱 | **17**（high **17** / medium **0**） |
| 相对基线 3903/2668 | **+17** / **+17** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **56** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B101dir gsbiz | **80** |
| 扩展 gsbiz | +约 40 新 ids |
| ajax/城市 | Formenbau pos 160–220；Bochum/Essen/Wuppertal 等 |
| 本轮核验队列 | **46** |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **56**（域名队列空） |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **80** + ajax/城市扩展 → **46** 域名 Impressum  
2. 合并前重读 **3903/2668**  
3. 质量剔除：pumpen/metallguss/bakbau/kennzeichnungs、off-domain  
4. 再播种：新 gsbiz ids → **56**

### 本轨新增邮箱（共 17）

- `info@rp-kunststofftechnik.de`
- `info@clausen-kunststoff.de`
- `markus@3d-druck-ww.de`
- `info@tks-aue.de`
- `info@idesa-gmbh.de`
- `mail@thorwarth-grebe.de`
- `info@an-gmbh.de`
- `service@weide-gmbh.de`
- `info@risse-warstein.de`
- `tristar@tristar-technik.de`
- `info@tiefbohren-graf-klett.de`
- `info@boric.de`
- `info@print4use.de`
- `info@formtechnik-gmbh.de`
- `mail@s-form.de`
- `info@formo.de`
- `info@herms-produktentwicklung.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- Spritzguss ajax 深分页已空（242B）
- 见 `data/germany_raw/batch102dir_merge_log.json`

### 产物

- `data/germany_raw/batch102dir_impressum.json`
- `data/germany_raw/batch102dir_verified.json` / `batch102dir_hits.json`
- `data/germany_raw/batch102dir_merge_log.json` / `batch102dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch102dir 已合并；域名队列 **0**；gsbiz 余 **56** 供 Batch103dir。

---

## 目录/展会轨 Batch101dir

> 合并前重读 CSV（Website B102 后基线 **3897** / **2662**；非 3893）。合并后基线：**3903** / **2668**。

### 累计（Batch101dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3903** |
| high / medium | **3657** / **246** |
| 唯一域名 | **2668** |
| 含电话 / 含城市 | **3351** / **3419** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3645** |
| design_studio | **155** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch101dir）

| 指标 | 数值 |
|---|---:|
| 核验域名 | **22** |
| 有邮箱命中 | **7** |
| 本轨净增邮箱 | **6**（high **6** / medium **0**） |
| 相对 Website B102 基线 3897/2662 | **+6** / **+6** 域名 |
| 域名队列剩余 | **0** |
| gsbiz ids 剩余 | **80** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 B100dir gsbiz 余 | **20** |
| 扩展 gsbiz + ajax/城市 | Formenbau pos 90–150、Spritzguss 60–100、Freiburg/Ulm/Kassel 等 |
| 本轮核验队列 | **22** |
| 超时强制 no_email | motan-colortronic.de, lampersberger-gmbh.de |
| WLW | CAPTCHA — 跳过 |
| 再播种 | gsbiz ids **80**（域名队列空） |

### 方法

1. 排空 `queue_gsbiz_ids_remaining.txt` **20** + 更深 ajax/城市 → 提取邮箱域名 **22**  
2. 合并前重读 **3897/2662** = Website B102  
3. 质量剔除：seghost off-domain（performgmbh）  
4. 再播种：新发现 gsbiz ids → 保留 **80**

### 本轨新增邮箱（共 6）

- `info@stranghoener-kunststoff.de`
- `info@stocker-kunststoff.de`
- `info@wetekk.de`
- `info@ebr-formenbau.de`
- `info@wtl-group.de`
- `info@deege-formenbau.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 2 域名超时 → forced no_email
- 见 `data/germany_raw/batch101dir_merge_log.json`

### 产物

- `data/germany_raw/batch101dir_impressum.json`
- `data/germany_raw/batch101dir_verified.json` / `batch101dir_hits.json`
- `data/germany_raw/batch101dir_merge_log.json` / `batch101dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch101dir 已合并；域名队列 **0**；gsbiz 余 **80** 供 Batch102dir。

---

## 目录/展会轨 Batch100dir

> 合并前重读 CSV（Website B101 后基线 **3874** / **2642**；非 3867）。合并后基线：**3893** / **2659**。

### 累计（Batch100dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3893** |
| high / medium | **3647** / **246** |
| 唯一域名 | **2659** |
| 含电话 / 含城市 | **3341** / **3409** |
| 非 .de 邮箱 | **1106** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3636** |
| design_studio | **154** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch100dir）

| 指标 | 数值 |
|---|---:|
| 新建队列域名 | **38**（Gelbe Seiten + Europages） |
| Impressum 核验 | **38** |
| 有邮箱命中 | **20** |
| 本轨净增邮箱 | **19**（high **18** / medium **1**） |
| 相对 Website B101 基线 3874/2642 | **+19** / **+17** 域名 |
| 域名队列剩余 | **0** |
| gsbiz 未抓详情 | **20** ids（见 `queue_gsbiz_ids_remaining.txt`） |

### 种子状态

| 项 | 状态 |
|---|---|
| 上轮队列 | **0**（B99dir 耗尽） |
| Gelbe Seiten | Formenbau/Spritzguss 全国+城市 + ajax 分页 + **60** gsbiz 详情 |
| Europages DE | Formenbau/Spritzguss 列表 + firma 页 |
| KunststoffWeb | **404** |
| Das Örtliche | **410** |
| Bing/DDG | 垃圾/验证码 — 未用 |
| WLW | CAPTCHA — 跳过 |
| master/VDWF/Fakuma | 饱和 — 未用 |

### 方法

1. 从非 WLW 公开目录重建队列（GS email/json + EP STRICT）→ **38** 域名  
2. 合并前重读 **3874/2642** = Website B101  
3. 质量剔除：Stuck/Trocknung/Spanntechnik/媒体门户；保留 Formenbau/Formteile/Werkzeugbau/Modellbau/Plastiform  
4. 再播种：gsbiz 剩余 ids **20**（域名队列空）

### 本轨新增邮箱（共 19）

- `contact@luettgens.de`
- `info@ermet.de`
- `info@hm-fraas.de`
- `info@werkzeugbau-wick.de`
- `info@bk-formteile.de`
- `info@max-schuster.de`
- `info@ncb-lohmann.de`
- `info@w-potthoff.de`
- `info@stemotec.de`
- `mail@fiberglas.net`
- `info@cox-formenbau.de`
- `info@fmf-wwf.de`
- `h.stange@schramm-stanzformenbau.de`
- `info@procito.de`
- `martin@procito.de`
- `robert@procito.de`
- `info@modellbau-schmidgall.de`
- `info@albert-fuchs-gmbh.de`
- `info@plastiform.de`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过；master/VDWF/Fakuma 饱和
- KunststoffWeb 404；Das Örtliche 410
- 下轮优先继续 Gelbe Seiten gsbiz 剩余 ids / 更深 ajax
- 见 `data/germany_raw/batch100dir_merge_log.json`

### 产物

- `data/germany_raw/batch100dir_impressum.json`
- `data/germany_raw/batch100dir_verified.json` / `batch100dir_hits.json`
- `data/germany_raw/batch100dir_merge_log.json` / `batch100dir_reseed.json`
- `data/germany_raw/queue_gsbiz_ids_remaining.txt`

### 状态

Batch100dir 已合并；域名队列 **0**；gsbiz 详情余 **20** 供 Batch101dir。

---

## 目录/展会轨 Batch99dir

> 合并前重读 CSV（Website B100 后基线 **3854** / **2623**；非 3846）。合并后基线：**3867** / **2635**。

### 累计（Batch99dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3867** |
| high / medium | **3622** / **245** |
| 唯一域名 | **2635** |
| 含电话 / 含城市 | **3317** / **3383** |
| 非 .de 邮箱 | **1105** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3616** |
| design_studio | **148** |
| oem_buyer | **69** |
| sourcing | **34** |

### 本轨成果（Batch99dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **85** |
| 有邮箱命中 | **60** |
| 本轨净增邮箱 | **13**（high **13** / medium **0**） |
| 相对 Website B100 基线 3854/2623 | **+13** / **+12** 域名 |
| 已知重复跳过 | **45** |
| 再播种剩余 | **0** |
| 队列剩余 | **0** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空 master_strict 残 | **22** |
| VDWF HTML 新域名 | **63**（非 WLW） |
| master_strict 新 | **0**（已尽） |
| 核验合计 | **85** |
| 超时强制 no_email | bus-werkzeugbau.de |
| WLW | CAPTCHA — 跳过 |
| maps/OEM/embassy | 无可用新队列；kunststoff-magazin 403 |
| 再播种 | **空**（master/VDWF/peer 近耗尽） |

### 方法

1. 排空残 **22** + VDWF mitglieder HTML 再提取 **63** → Impressum
2. 合并前重读 **3854/2623** = Website B100
3. 质量剔除：institut/marktspiegel/OWL、beispiel.de、bewerbung、careers@；多数 VDWF 命中已在库（known **45**）
4. 再播种尝试后队列 **0**

### 本轨新增邮箱（共 13）

- `sales@topgrademolds.com` · `spareparts@topgrademolds.com`
- `sales@vannormanmolding.com` · `sales@vsmolding.com` · `sales@wentworthmold.com`
- `sales@wundermold.com` · `sales@xcentricmold.com` · `info@kunststoff-teile.com`
- `sege@semoulding.com` · `th@visualcnc.com` · `sales@eriemolded.com`
- `webinfo@cncke.com` · `msicustomerservice@msimoldbuilders.com`

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- master_strict 耗尽；依赖 VDWF 再提取
- 目录轨队列现为 **0** — 下轮需新源（非 WLW：Gelbe Seiten/Europages/OEM maps/展商新页）
- 见 `data/germany_raw/batch99dir_merge_log.json`

### 产物

- `data/germany_raw/batch99dir_impressum.json`
- `data/germany_raw/batch99dir_verified.json` / `batch99dir_hits.json`
- `data/germany_raw/batch99dir_merge_log.json` / `batch99dir_reseed.json`

### 状态

Batch99dir 已合并；队列剩余 **0**（种子近耗尽）。

---

## 目录/展会轨 Batch98dir

> 合并前重读 CSV（Website B99 后基线 **3816** / **2591**；非 3809）。合并后基线：**3846** / **2615**。

### 累计（Batch98dir 合并后）

| 指标 | 数值 |
|---|---:|
| 去重后邮箱总数 | **3846** |
| high / medium | **3601** / **245** |
| 唯一域名 | **2615** |
| 含电话 / 含城市 | **3302** / **3373** |
| 非 .de 邮箱 | **1092** |

### 按 icp_tag（累计）

| icp_tag | 数量 |
|---|---:|
| overseas_peer_overflow | **3602** |
| design_studio | **142** |
| oem_buyer | **69** |
| sourcing | **33** |

### 本轨成果（Batch98dir）

| 指标 | 数值 |
|---|---:|
| Impressum 核验 | **80** |
| 有邮箱命中 | **27** |
| 本轨净增邮箱 | **30**（high **30** / medium **0**） |
| 相对 Website B99 基线 3816/2591 | **+30** / **+24** 域名 |
| 再播种剩余 | **22** |
| 队列剩余 | **22** |

### 种子状态

| 项 | 状态 |
|---|---|
| 排空队列 | **80**（B97dir reseed：master_strict，已滤中国竞品） |
| 超时强制 no_email | 7（pro-moulds / procnc / esteemold / itpmolding / mgrmold / smimolding / tdimolding） |
| VDWF/Fakuma | 饱和 |
| WLW | CAPTCHA — 跳过 |
| 再播种 | master_strict 残池 **22**（接近耗尽） |

### 方法

1. 排空上轮 **80** → Impressum（ThreadPool JSONL）
2. 合并前重读 **3816/2591** = Website B99
3. 质量剔除：off-domain（z-group / magenta LLC）、webmaster；中国竞品已在种子层过滤
4. 再播种：master_strict 残 → 队列 **22**

### 本轨新增邮箱（共 30，节选）

- `kanagata@ishida-mold.com` · `jmfalcao@moldplast.com` · `comercial@idealmolde.com`
- `sales@emeraldtoolandmold.com` · `sales@underwoodmoldco.com` · `info@injectionplastic.com`
- `sales@cncdynamics.com` · `sales@flashcutcnc.com` · `sales@ptms-mold.com`
- 及其他 mould/CNC peer `.com`（见 `batch98dir_verified.json`）

### 阻塞 / 备注

- WLW CAPTCHA — 跳过
- 7 域名超时 → forced no_email
- master_strict 残池将尽（再播种仅 **22**）
- 见 `data/germany_raw/batch98dir_merge_log.json`

### 产物

- `data/germany_raw/batch98dir_impressum.json`
- `data/germany_raw/batch98dir_verified.json` / `batch98dir_hits.json`
- `data/germany_raw/batch98dir_merge_log.json` / `batch98dir_reseed.json`

### 状态

Batch98dir 已合并；队列剩余 **22**（master_strict 残）供 Batch99dir。

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
