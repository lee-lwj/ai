# 联系人富化试点报告（20 家）/ Contact Enrichment Pilot

**客户:** Rocky Lee · Longxiang / Mouldible  
**日期:** 2026-10-19（Asia/Hong_Kong）  
**方法:** 官网 Contact/About/Impressum + 公开搜索 LinkedIn/Facebook/Xing 片段（无登录爬取）。**下一批将并列使用多引擎搜索、地图、展会公开名录与使馆商务信息（见主方案 §3A v1.3）。**

---

## 1. 产出文件

| 文件 | 路径 |
|---|---|
| 联系人明细 CSV | `/workspace/mouldible-export-ai/data/enrichment_pilot_20.csv` |
| Excel | `/workspace/mouldible-export-ai/data/enrichment_pilot_20.xlsx` |
| 本报告 | `/workspace/mouldible-export-ai/docs/enrichment_pilot_20_报告.md` |
| 试点域名清单 | `/workspace/mouldible-export-ai/data/pilot_domains.txt` |

**CSV 粒度:** 每个找到的联系人/邮箱一行（同一公司可多行）。共 **40 行 / 20 个域名**。

---

## 2. 试点样本构成（20）

| ICP | 数量 | 域名 |
|---|---:|---|
| 买家路径 design_studio | 5 | crescentinnovation, morosinidesign, flynn-product-design, seymourpowell, productdesignco |
| 买家路径 oem_buyer | 2 | digisens.ch, parkmfg.com |
| 买家路径 sourcing | 1 | smart-sourcing.com |
| 海外同行溢出 overseas_peer_overflow | 11 | admo, gebrema, promolding, stutcheng, modelsllc, reichert-formenbau, catalystpdg, as-form(→Schwendemann), jokey, ruetschi, fischerwzb |
| other（模具标准件生态） | 1 | dms-diemould.co.uk |

**替换说明:** 原候选 `bulteplastics.co.uk`、`nectardesign.com` 站点不可达，已换为名单内仍存活的 `fischerwzb.de`（DE 同行）、`productdesignco.com`（设计工作室）。

**地理:** US / UK / DE / CH / NL / AU 均有覆盖。

---

## 3. 关键统计

| 指标 | 数值 |
|---|---:|
| 域名尝试 | **20** |
| 站点可抓取/有实质内容 | **18**（reichert 全挂；jokey 反爬仅薄内容） |
| 找到 LinkedIn 公司/个人页 URL | **17/20 域名** |
| 找到 Facebook 页 URL | **6/20 域名** |
| Xing（.de） | **1**（fischerwzb） |
| 相对 master 的**新邮箱** | **14**（见下） |
| 有姓名+职位的联系人（去重约） | **14 人**（部分无个人邮箱） |
| enrichment_status=enriched | 31 行 |
| partial | 8 行 |
| blocked_site | 1 行（reichert） |

### 3.1 新发现邮箱（不在 master 该域名下）

| 域名 | 新邮箱 | 来源 |
|---|---|---|
| smart-sourcing.com | info@smart-sourcing.com | 官网首页 |
| morosinidesign.com.au | quotes@morosinidesign.com.au | contact.php |
| flynn-product-design.com | hello@flynn-product-design.com | 官网 footer |
| seymourpowell.com | hello@seymourpowell.com | 官网 footer |
| promolding.nl | facturen@promolding.nl | contact（财务，外联价值低） |
| promolding.nl | mx_promolding@126.com | 中国办公室 |
| as-form.de → Schwendemann | info@ / js@ / rs@ / mk@ / dz@ / rb@ / kf@ **formenbau-schwendemann.de** | Kontakt 团队页（**本批最高产**） |
| ruetschi.com | hr@ruetschi.com | About（招聘信箱） |

### 3.2 高质量具名联系人（建议优先人工复核）

| 姓名 | 职位 | 公司 | 邮箱 | 置信度 |
|---|---|---|---|---|
| Jonas Schwendemann | Geschäftsführer | Formenbau Schwendemann | js@formenbau-schwendemann.de | high |
| Ralf Schwendemann | Technischer Leiter | 同上 | rs@… | high |
| Ben Morosini | Owner / ID | Morosini Design | info@ / quotes@ | high |
| Jack Lawson | Co-Founder/CEO | Catalyst PDG | jlawson@… | high |
| Chris Flynn | Founder | FLYNN | chris@… | medium（种子+公开描述） |
| Christoph Ruetschi / Christian Moser | Co-CEO / CEO | Ruetschi | 仅公司 info@ | high 姓名 / 无个人邮 |
| Bob Kocken | Sales（2019 官网稿） | Gebrema | 无个人邮 | medium（可能过时） |
| Chip McMann / Michael Talbot | Owner-CEO / VP | Models LLC | 无个人邮 | medium（LI 搜索片段） |

---

## 4. 什么有效 / 什么被挡

### 有效

1. **欧洲中小模具厂「Kontakt / Impressum / Ansprechpartner」页** — 尤其德国：姓名+职位+直拨分机+个人邮箱一次给齐（Schwendemann 一页 6 人）。
2. **设计工作室小站** — footer/contact 常直接挂 `hello@` / `info@` / 老板手机（Morosini、FLYNN、Seymourpowell、Crescent）。
3. **WebSearch 公开片段** — 在无法登录 LinkedIn/Facebook 时，仍可稳定拿到 **公司页 URL**，偶见电话/通用邮箱（Smart Sourcing、Jokey、Gebrema FB）。
4. **域名迁址发现** — `as-form.de` 死站 → 搜索指向 `formenbau-schwendemann.de`，反而比原站 enrichment 更完整。

### 受限 / 阻塞

| 阻塞 | 影响 |
|---|---|
| **LinkedIn / Facebook 无登录** | 无法稳定抓 About 邮箱、员工列表、InMail；仅靠搜索引擎摘要与公司页 URL |
| **Jokey 反爬** | WebFetch「Zugriff eingeschränkt」；curl 拿到 HTML 但无邮箱明文 |
| **reichert-formenbau.de** | 500 / 连接失败；仅黄页目录可证 info@ + 电话 |
| **Google Sites / 薄站**（modelsllc） | 电话可见，mailto 不可见 |
| **productdesignco** | 极简静态页，邮箱为图片/链接文案，未解析出明文 mailto |
| **Xing** | 仅对明确 .de 且搜索命中时记录（Fischer）；未系统爬取 |

**诚实结论:** 无 LinkedIn Sales Navigator / 无浏览器登录态时，**「公司页 URL + 官网公开邮箱/电话」可达 80%+ 域名**；**具名决策人+个人邮箱**主要来自 **德语/欧陆 Kontakt 页**，英文设计站多为通用信箱。

---

## 5. 按路径的外联建议（试点洞察）

1. **设计工作室:** 用 `hello@` / `info@` + 点名创始人（若有）；话术偏 DFM、钢模交期、原型→量产。
2. **OEM（digisens / park）:** 通用 admin@/info@ + LI 上找 Purchasing/Mechanical；本批官网未暴露采购岗。
3. **Sourcing（Smart Sourcing）:** info@ + sales@ 双投；强调中国模具产能溢出与 QC。
4. **海外同行溢出:** 优先 **Geschäftsführer / Technischer Leiter / Sales**；话术「产能互补、交期 backup、钢模性价比」，勿写成抢客户。Schwendemann / Fischer / Gebrema / Admo 适合此路径。
5. **DMS Diemould:** 标准件商 — 可作生态伙伴，非主买家。

---

## 6. 扩量建议（Next scale-up）

| 步骤 | 建议 | 预期 |
|---|---|---|
| A | 对全部 ~10k 企业域做 **HTTP 探活 + /contact|/impressum|/kontakt|/about** 路径探测 | 滤掉死域，优先欧陆 Kontakt 富矿 |
| B | 对存活站跑 **mailto + 邮箱正则**（仅可见文本，不猜造） | 批量新通用邮箱 |
| C | DE/CH/AT/NL 加 **Impressum 解析**（常含 GF 姓名） | 具名 MD 提升 |
| D | LinkedIn：人工或授权工具补 **Purchasing / Sourcing / Tooling / Design** 个人页（本试点不做未授权抓取） | 买家路径补决策人 |
| E | Facebook About：对已有公司页 URL 用浏览器人工抽邮箱/电话 | 补 6→更多 FB |
| F | 试点高置信行先做 **邮箱验证（MX/SMTP）** 再进 CRM | 降弹信 |
| G | 单独队列：域名迁址（as-form 类）用搜索「旧域名 + Formenbau」找回新站 | 挽救死链种子 |

**建议下一档规模:** 先做 **200 域**（100 欧陆同行 + 50 设计/sourcing + 50 OEM 候选），复用本表 schema，再决定是否全量 10k。

**方法补充（Rocky 确认）：** 下一批 enrichment 将把 **多搜索引擎 + 地图 + 展会登记/参展商名录 + 大使馆商务信息** 与官网/社媒并列执行（查询模式见 `目标客户学习与关键词.md` §3.7；流水线见主方案 §3A v1.3），覆盖六大渠道，不再仅依赖网站与 LinkedIn/Facebook/Xing。

---

## 7. 已知局限（请 Rocky 知悉）

- 未登录 LinkedIn/Facebook，**不编造**未在公开页出现的邮箱/职位。
- Bob Kocken 等信息来自 **旧新闻帖**，外联前需再确认是否在职。
- `solutions@catalystpdg.com` 来自 master 第二邮箱，本批未在官网复验。
- 中国大陆同行过滤策略仍按 ICP 文档：本批未选中国大陆模具厂。

---

*试点完成 · Grok Bot · 2026-10-19 Asia/Hong_Kong*
