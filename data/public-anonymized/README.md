# Anonymized Research Records / 匿名研究记录

[Project overview](../../README.md) · [Methodology](../../methodology/research-framework.md)

`evaluations.json` contains the ten approved case records and seven new web-result assessments. It preserves the published scoring and claim-status fields; it is not a raw chat export. / 该文件保留10个已批准案例及7条新网页评测的评分、命题状态，不是私人聊天导出。

## Record interpretation / 字段解释

- `case_id`: stable original CEA identifier; gaps in numbering reflect selection, not missing generated cases. / 保留原编号，跳号是筛选结果。
- `provenance.conversation_group`: anonymous S01–S09; CEA-007/008 share one group. / 匿名来源组，两案同源不增加独立样本量。
- `ai_evidence.evidence_id`: local A01-style labels used by scores and case pages. / 仓库内匿名证据编号。
- `scores.value`: 0–4 integer, `NA`, or `NE`; no total or imputed score. / 不合计、不补值。
- `claims.claim_origin`: response claim, background assumption, or reviewer question; a contradicted reviewer inference is not an AI error. / 归属区分原答与评审问题。
- `sources`: existing public references with dates and limitations. / 真实外部引用及日期、局限。
- `track_b`: actual new retrievals; no historical rank reconstruction. / 实际新检索，不复现历史排名。

## Privacy and rights / 隐私与权利

Private conversation/message identifiers, source-file paths, raw chat archives, personal institution names, and sensitive age/date combinations are excluded. External source URLs remain intact. No third-party PDFs, images, long book excerpts, or song lyrics are distributed. / 不含私聊定位、原始档案和不必要身份信息；只链接外部来源，不附带第三方原件。

No open-source license has been added. No rights to third-party sources are asserted. / 未添加开源许可证，不主张第三方来源权利。
