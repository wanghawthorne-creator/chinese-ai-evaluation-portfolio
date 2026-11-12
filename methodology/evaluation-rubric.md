# Evaluation Rubric v1.0 / 评分标准

[Research framework](research-framework.md) · [Limitations](limitations.md) · [Project overview](../README.md)

## Track A / AI回答维度与双语评分锚点



IU — Intent Understanding / 意图理解：0完全偏离；1主意图误读；2只覆盖部分或关键前提被误设；3主要意图吻合、少量遗漏；4准确覆盖约定任务与关键约束，必要时澄清/更新。 English: 0 misses the task; 1 misreads the main intent; 2 partial coverage or a material assumption; 3 main intent met with minor omissions; 4 fully addresses scoped intent and constraints, clarifying/updating when needed.

SR — Semantic Relevance / 语义相关性：0无关；1主要离题；2相关与离题混杂；3主体相关、少量冗余；4直接、聚焦、层次与问题对应。 English: 0 unrelated; 1 mostly off topic; 2 mixed relevance; 3 largely relevant with minor drift; 4 focused and directly aligned.

CC — Cultural Competence / 文化语境理解：0关键文化含义颠倒或严重本质化；1重大误读/刻板化；2部分理解但概括边界不足；3理解恰当且有必要限定；4准确处理语用、群体内部差异和解释边界。 English: 0 reverses core meaning or severe essentialism; 1 major misreading/stereotyping; 2 partial understanding with overgeneralization; 3 appropriate and qualified; 4 nuanced pragmatic/contextual interpretation with clear boundaries. 不要求所有非文化案例硬用CC。

FA — Factual Accuracy / 事实准确性：0关键结论被直接反证且使回答失效；1多个重大事实错误；2已核查事实混合正确/错误且实质影响结论；3关键可核查事实成立但有局部不精确；4范围内重要可核查事实均有支持、没有发现实质错误。 English: 0 decisive refutation of a central claim; 1 multiple major factual errors; 2 material mixture of verified correct/incorrect claims; 3 key verified claims sound with minor imprecision; 4 material checkable claims within the declared scope supported. 只有“未验证”不能给0/1/2；关键事实无法裁定时NE，并把局部可核查事实另列。

TR — Temporal Relevance / 时效性：0使用错误时间导致关键结论失效；1重大过期/时点误配；2有实质时间歧义或多时点混用；3时点合适、局部版本或日期说明欠缺；4日期、版本、历史/当前/预测均区分清楚。 English: 0 wrong time invalidates the answer; 1 materially outdated/misaligned; 2 substantial temporal ambiguity; 3 appropriate time with minor gaps; 4 explicit and consistent time/version distinctions. 非动态任务NA；缺当时状态且关键时效无法判定NE。

SC — Source Credibility / 来源可信度：0已证实伪造的关键来源；1关键结论主要依赖可辨的不适当来源；2来源可追溯但不足/不直接支持关键命题；3主要来源适当、少量支持链欠缺；4来源可逐命题追溯、直接适配并区分自述/独立证据。 English: 0 confirmed fabrication; 1 identifiable key sources unsuitable; 2 traceable but inadequate/indirect support; 3 generally appropriate with minor gaps; 4 claim-level traceable, direct, context-appropriate support. 工具仅保留内部引文、无法取回对应URL时NE；不把检索工具显示损失归罪AI。纯创作文案不需要外源则NA。

RH — Response Helpfulness / 回答有用性：0无法使用且关键目标未满足；1主要不可用；2部分有用但需实质修改；3可用、少量补充可改善；4清楚、可用且满足任务。 English: 0 unusable for the goal; 1 mostly unusable; 2 useful in part but needs material revision; 3 useful with limited improvements; 4 clear and usable for the scoped task. 无后续反馈时不推断用户满意。

UC — Uncertainty Calibration / 不确定性表达：0将已知关键反证或假说当确定事实；1核心机制/未知事项明显过度确定；2有局部限定但关键解释仍过度肯定；3整体区分已知与推断，有少量遗漏；4明确区分证据、假设、解释和未知，澄清条件恰当。 English: 0 presents refuted claims or hypotheses as certain; 1 strongly overconfident on central unknowns; 2 some caveats but material overstatement; 3 generally calibrated with minor gaps; 4 clear separation of evidence, assumptions, interpretation, and unknowns.

## Track B dimensions / 网页结果独立评分

不与A轨混分。只评价实际取得的新网页结果对象，不伪称历史SERP或复现排名。每条记录需包含原始查询、实际检索式（若改写）、检索工具/日期、网页真实标题/URL、摘要概括、用户意图、来源时间信息与版本限制。

WR Query–Result Relevance / 查询结果相关性：0无关；1边缘；2部分满足；3主要满足；4直接完整满足约定子意图。 0 unrelated; 1 marginal; 2 partial; 3 largely meets the intent; 4 directly meets the scoped sub-intent.

WA Authority & Evidence / 权威与证据适配：0已证伪/伪造来源；1来源明显不适配；2存在相关内容但证据链弱/厂商自述不足以支持效果比较；3来源对该命题合适且可追溯；4直接一手且范围/交叉证据清楚。 0 discredited/fabricated; 1 unsuitable; 2 weak support; 3 appropriate and traceable; 4 direct primary evidence with clear scope/corroboration. 官方不自动得4，不把厂商能力宣称当独立效果验证。

WT Temporal Fit / 时间匹配：0明确错时；1严重过期；2版本/日期不足且影响使用；3当前核验合适但历史复原受限；4与声明时间/版本直接匹配。0 wrong period; 1 materially stale; 2 consequential dating/version gaps; 3 suitable for current checks with limits; 4 matched to the declared time/version. 查不到网页日期NE，不用抓取时间冒充发布日期。

WC Cultural/Contextual Fit / 文化与语境适配：0关键语义或语境颠倒；1重大错配；2部分匹配；3恰当有小缺口；4精确适配用户语境。0 inverted meaning; 1 major mismatch; 2 partial; 3 appropriate; 4 precise contextual fit. 不适用NA。 网页摘要事实准确性单独在claims中核对，不把未核实数字硬评分。



