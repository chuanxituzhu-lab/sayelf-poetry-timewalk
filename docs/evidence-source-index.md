# Evidence-source index / 证据链来源索引

This guide broadens the public Starter's evidence sources while keeping each source bounded by what it can establish. 本指南扩展公开版可使用的证据来源，同时明确每类材料能支持什么、不能支持什么。

## Source roles / 来源角色

| Role | Examples and use | Boundary |
| --- | --- | --- |
| **Primary text / contemporaneous record 原始文本/同时代记录** | The poem and preface, letters, diaries, histories, gazetteers, inscriptions, archives; use an exact passage to support wording or a recorded event. 诗词小序、书信日记、正史方志、碑刻档案；应定位具体文本。 | First establishes what that source records. Assess date, genre, provenance, transmission, and possible bias. 首先证明“该文献如此记载”，还需评估年代、体裁、传承与立场。 |
| **Edition / classical commentary 版本校注/古代评注** | Named editions, collations, collected works, ci-hua and historical criticism; use for variants, editorial decisions, and reception. 具名版本、校勘记、全集、词话等；用于异文、编校判断和接受史。 | Record edition and locator. A later commentary is not an eyewitness to the poet's intent. 记录版本和位置；后世评论不等于作者本意的现场证据。 |
| **Modern scholarship 现代学术研究** | Peer-reviewed articles, research books, university-press editions, and research by identifiable specialists; use for an attributed argument or documented state of research. 同行评审论文、学术专著、大学出版社版本及具名专家研究。 | “Famous” alone is not a quality test. Check expertise, venue, date, citations, and passage; distinguish argument from consensus. 不能只凭名气；核对领域、发表信息、引文和页码，并区分个人观点与学界共识。 |
| **Contemporary interpretation 当代阐释** | Named writers, critics, educators, and cultural commentators; use for that person's reading and contemporary reception. 具名作家、评论者、教师及文化传播者；用于呈现其解读和当代接受。 | Attribute the view. Popularity or eloquence does not prove historical facts; trace factual claims to underlying evidence. 保留观点归属；传播度和感染力不能证明史实。 |
| **Catalog / bibliography / search index 馆藏目录/书目/检索索引** | National, university, and public-library catalogs; public bibliographies and academic database records; use to confirm catalog metadata and discover candidate sources. 国家/高校/公共图书馆目录、公开书目及学术数据库记录；用于核对著录并发现候选材料。 | A catalog hit or search result does not prove the book's contents or a passage. Mark it `index/discovery` until the item or relevant passage is inspected. 目录或搜索结果不能证明书中内容；未核对原件/具体段落前标为索引线索。 |
| **Digitized item / facsimile 数字化原件/影印件** | A library-hosted scan or item-level text can support claims about that specific witness after edition and page/folio are checked. 核对版本与页/叶码后，馆藏书影或具体数字文本可支持关于该见本的判断。 | Record shelfmark/resource ID, edition, page/folio, OCR status, and access terms. Unchecked OCR is not a checked facsimile. 记录索书号/资源 ID、版本、页叶、OCR 核验状态和使用条款。 |

Public discovery starting points include the [National Library of China](https://www.nlc.cn/web/), its [advanced search](https://www.nlc.cn/web/shouye/gaojijiansuo/index.shtml), and the [Chinese Ancient Books Resource Library](https://read.nlc.cn/thematDataSearch/toGujiIndex). These are discovery portals, not blanket proof of every result or permission to reuse digitized content. 国家图书馆入口和古籍资源库可作公开检索起点，但不代表每条结果已核实，也不自动授予数字内容再利用权。

## Claim-level record / 按论断建档

Assign stable `evidence_id` and `claim_id` values and record, where applicable:

- `source_role`, `source_type`, `creator`, `title`, `work_or_edition`;
- exact `locator` (volume, chapter, page, folio, entry, DOI, shelfmark, or resource ID);
- `source_url` plus `url_kind` (`item`, `catalog`, `search`, or `landing-page`); never invent a direct URL;
- `accessed_at`, `transcription_status` (`facsimile`, checked transcription, OCR, abstract, or metadata-only);
- `supports` and `limitations` for the specific claim;
- `verification_status`: `discovery_only`, `metadata_checked`, `item_opened`, `passage_checked`, `claim_assessed`, or `pending`;
- `independence_group` to identify mirrors or sources derived from the same edition;
- `rights_status`: public domain, a named license, permission required, access restricted, or unknown.

`claim_assessed` means a reviewer examined fit and limits; it does not settle a scholarly dispute. If only catalog metadata is visible, say so explicitly. Search links are search links, not item citations. Multiple mirrors of one source do not count as independent corroboration.

## Evidence, interpretation, and rights / 证据、阐释与版权

- Keep `C` (poem text), `E` (bounded evidence), and `S` (interpretation/creative synthesis) distinct. Attribute modern readings: “Scholar X interprets this image as…” is different from “the poet therefore felt…”.
- For disputed dates, variants, or biography, preserve competing views and their sources. A difference alone does not prove which version is wrong.
- Publicly searchable does not mean public domain or reusable. Review the separate rights of modern editions, commentary, scans, images, fonts, and transcriptions before commercial or public redistribution. Quote only what is necessary and permitted.
- Do not upload local catalogs, private materials, or restricted records as part of this public guide.

---

## 中文速览

证据链可引用古籍、同时代记录、版本校注、古代词话、现代学术研究和当代名家解读，也可以用国家图书馆等公开目录发现材料。每条证据必须连接到具体论断，注明作者/版本、精确位置、链接类型、核验状态、独立性和权利状态。目录证明的是著录信息，不是未经核对的正文；现代解读应保留作者观点归属；公开可访问不等于可复制再发布。
