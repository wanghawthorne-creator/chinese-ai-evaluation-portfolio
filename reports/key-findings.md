[English README](../README.md) | [简体中文 README](../README.zh-CN.md)

# Key Findings / 核心研究发现

**Assessment v1.0 · Research snapshot: 11 November 2026 / 研究快照：2026年11月11日**

This synthesis preserves the findings of the approved assessment. It covers **10 task-specific case units from 9 conversations**, with **7 newly retrieved webpages** evaluated separately in three companion dossiers. It does not estimate model-wide accuracy or causal effects.

本综合保留已确定的评测结论，覆盖**9个对话中的10个任务案例单元**，另有**7条新检索网页**在三个配套档案中独立评测。本报告不估计模型总体准确率或因果效果。

## 1. Contextual meaning requires more than keyword matching / 语境理解不能只靠关键词

[CEA-008](../cases/ai-response-evaluation/CEA-008.md) interprets *bot* as a possible social-media submission account, while [CEA-020](../cases/ai-response-evaluation/CEA-020.md) addresses an agent product with computer and application capabilities. The response in [CEA-011](../cases/ai-response-evaluation/CEA-011.md) asks for the original usage of a community nickname instead of inventing its origin. These cases illustrate distinct pragmatic tasks, not interchangeable dictionary lookups.

[CEA-008](../cases/ai-response-evaluation/CEA-008.md)把bot解释为一种可能的社交媒体投稿账号用法；[CEA-020](../cases/ai-response-evaluation/CEA-020.md)讨论具有电脑和应用能力的Agent产品；[CEA-011](../cases/ai-response-evaluation/CEA-011.md)则在缺少社群称谓语境时索要原句，没有编造出处。这些是不同的语用任务，不能用同一个词典释义替代。

**Evidence boundary.** The specific “crying bot” post and the nickname's original context remain unavailable. A documented platform example establishes that a submission-account usage exists; it does not confirm the user's exact intended referent. This is a comparison of naturally occurring cases, not a controlled experiment.

**证据边界。** “痛哭bot”的具体原帖与称谓的原始语境仍缺失。平台实例只能证明投稿账号用法存在，不能确认用户所指的具体对象。这是自然交互案例对照，不是控制变量实验。

## 2. Clear explanation and factual support are separate / 解释清楚与事实支持需要分开

[CEA-019](../cases/ai-response-evaluation/CEA-019.md) distinguishes the simulation argument's assumptions from a proof that reality is simulated, and follows the user's questions about consciousness. Its teaching analogy compresses the formal argument, and the first response leaves the user reporting continued confusion. The review therefore recognizes calibrated assumptions while retaining limitations in precision and instructional load.

[CEA-019](../cases/ai-response-evaluation/CEA-019.md)区分模拟论证的前提与“现实已被证明是模拟”的结论，并跟随用户关于意识的追问。其教学类比压缩了形式化论证，用户也在首答后表示仍有困惑。因此评审认可其前提限定，同时保留精度与教学负担方面的局限。

[CEA-001](../cases/ai-response-evaluation/CEA-001.md) treats the “Chinese dragon” as a book-specific psychological metaphor and includes structural alternatives to individual psychological explanations. Author texts support attribution of the broad ideas, but do not establish their empirical validity. The complete book edition and every mechanism were not verified, so factual accuracy remains **NE** within the declared review.

[CEA-001](../cases/ai-response-evaluation/CEA-001.md)将“中国龙”作为书内心理隐喻处理，并为个人心理解释提供结构性替代视角。作者文本可以支持观点归属，不能证明其经验有效性。原书完整版本与全部机制尚未核实，因此本案事实准确性保留**NE**。

## 3. Methodological advice should not become invented fieldwork / 方法建议不能变成虚构成果

[CEA-022](../cases/ai-response-evaluation/CEA-022.md) distinguishes paid and unpaid work, agricultural output and community inputs, and activity counts and social meaning. It proposes recall periods, behavioral questions, versioned questionnaires, and recoding while explicitly labeling teaching scenarios and proposed processes.

[CEA-022](../cases/ai-response-evaluation/CEA-022.md)区分有偿与无偿劳动、农业产出与社区投入、活动数量与社会意义，并提出回忆周期、行为问题、问卷版本和重新编码。回答明确把相关情境与流程标为教学假设或方法建议。

**Evidence boundary.** The FA score of **4** concerns checked methodological facts, labor-form classification, and census timing. It does not verify that the illustrative household, craft activity, or questionnaire iterations occurred in the user's fieldwork. Implementation still requires mapping proposed measures to official statistical definitions. See [CEA-022 Track B](../cases/web-search-evaluation/CEA-022.md) for the two separately assessed webpages.

**证据边界。** FA的**4分**只涉及已核的方法事实、劳动分类和农普时点，不证明示例家庭、技艺活动或问卷迭代已在用户田野中发生。实际实施仍需把拟议指标与官方统计定义逐项对照。两条网页的独立评测见[CEA-022 Track B](../cases/web-search-evaluation/CEA-022.md)。

## 4. A coherent causal story can overrun its evidence / 连贯的因果故事仍可能超出证据

[CEA-028](../cases/ai-response-evaluation/CEA-028.md) organizes a personal observation of AI nostalgia images into technological, distributional, emotional, and social-memory explanations. It also warns against treating realistic images as historical evidence. However, the response elevates a qualified personal-feed observation into an unmeasured population pattern and presents several possible mechanisms as settled explanations.

[CEA-028](../cases/ai-response-evaluation/CEA-028.md)将个人观察中的AI怀旧图像组织成技术、传播、情绪和社会记忆层面的解释，也提醒读者不能把逼真图像直接当作历史证据。但回答把有条件的个人信息流观察提升为未测量的总体分布，并将若干可能机制写得过于确定。

The review assigns **UC = 1** for uncertainty calibration. **FA = NE** and **TR = NE** remain evidence-status judgments: the relevant model training distribution, platform amplification, user production pattern, and historical state were not established. These values do not assert that every proposed mechanism is false. The improvement is to state testable hypotheses and specify the data needed to distinguish them.

本案不确定性表达为**UC = 1**；**FA = NE、TR = NE**则保留证据不足的判断：所指模型训练分布、平台放大、用户生成偏好及历史状态尚未建立。这不表示所有机制都已被证伪。改进方向是将其表述为可检验假设，并明确区分机制所需的数据。

## 5. Verification should test precise claims / 核查应针对精确命题

[CEA-021](../cases/ai-response-evaluation/CEA-021.md) has identifiable primary material for the Japanese warning error and the cited Shanghai trust study. An unusual number alone is therefore not a basis for a hallucination label. The consequential issue is the summary's compression of differences across information-quality dimensions, trust components, and statistical models.

[CEA-021](../cases/ai-response-evaluation/CEA-021.md)所述日本预警错误与上海信任研究均可定位一手资料，因此不能仅凭数字异常就标为幻觉。实质问题在于摘要压缩了信息质量维度、信任维度和统计模型之间的差别。

The response's observational-versus-causal qualification is a strength; the research-summary precision still warrants **FA = 3**. The initial weather image and fault diagnosis remain outside what can be verified. See [CEA-021 Track B](../cases/web-search-evaluation/CEA-021.md) for the two newly retrieved, independently scored pages.

回答对观察性关联与因果关系的区分值得保留，但研究概述的精度仍对应**FA = 3**。最初天气图片与故障诊断不在本次可核范围内。两条新网页的独立评分见[CEA-021 Track B](../cases/web-search-evaluation/CEA-021.md)。

## 6. Version changes and claim ownership affect the judgment / 版本变化与命题归属会改变评审

[CEA-020](../cases/ai-response-evaluation/CEA-020.md) supports a distinction between group-chat presentation, serial role-play, and parallel task execution. Its product comparison remains limited by the conditional identification of Muse, changing documentation, and unavailable historical session conditions. The cited research summary and later paper version use different configuration counts; that difference must be interpreted by version rather than treated automatically as fabrication.

[CEA-020](../cases/ai-response-evaluation/CEA-020.md)区分了群聊呈现、串行角色扮演和并行任务执行，但产品比较仍受到Muse所指不确定、文档更新和历史会话条件缺失的限制。所引研究博客与后续论文版本的配置数量不同，需要按版本解释，不能自动判为编造。

**Attribution boundary.** The claim that one product is more popular or more successful is a reviewer scope check, not an assertion made by the original response; the response explicitly lacks independent comparative data. Likewise, the refuted “latest version” inference and the broad multi-agent question are reviewer checks, not AI factual errors. See [CEA-020 Track B](../cases/web-search-evaluation/CEA-020.md) for three separately scored new webpages.

**归属边界。** 关于哪个产品更火或成功率更高的命题是评审范围检查，不是原答作出的断言；原答明确表示缺少独立比较数据。同样，对“最新版本”推论的反证与广义多Agent问题属于评审核验，不算AI事实错误。三条新网页的独立评分见[CEA-020 Track B](../cases/web-search-evaluation/CEA-020.md)。

## 7. Creative usefulness is not objective aesthetic agreement / 创作有用性不等于客观审美一致

[CEA-007](../cases/ai-response-evaluation/CEA-007.md) extracts stylistic constraints from informal Chinese and supplies concise English caption options. The desired level of subtlety remains a user preference; no later feedback establishes adoption or satisfaction. Purely creative factual, temporal, sourcing, and uncertainty dimensions are marked **NA** where no substantive assessment requirement applies. “Original” is not expanded into a promise of exhaustive uniqueness checking.

[CEA-007](../cases/ai-response-evaluation/CEA-007.md)从非正式中文中提取风格约束，并提供简洁英文文案。含蓄程度仍取决于用户偏好，后续反馈不足以证明采用或满意。纯创作任务中没有实质评测要求的事实、时间、来源和不确定性维度标为**NA**；不把“原创”扩大为已经完成穷尽式唯一性检查。

[CEA-004](../cases/ai-response-evaluation/CEA-004.md) distinguishes shared false memory from social forgetting while recognizing different forms of forgetting. Its checked core facts align with the retrieved primary materials. The review still recommends making overlapping cognitive and social mechanisms explicit rather than inviting an exclusive binary interpretation.

[CEA-004](../cases/ai-response-evaluation/CEA-004.md)区分共享错误记忆与社会遗忘，并承认不同的遗忘形式。已核的核心事实与所取得一手材料相符，但仍建议明确认知与社会机制可能重叠，避免被读成互斥二分。

**FA scope reminder.** In CEA-008, FA = 4 covers verified song metadata, not confirmation of the specific *bot* referent or a uniquely correct lyric interpretation. In CEA-004, it covers the selected section's checked core facts, not the full compound answer or a universal causal model.

**FA范围提示。** CEA-008的FA = 4只覆盖歌曲元数据，不确认具体bot所指或唯一歌词释义；CEA-004的分数只覆盖选定章节中已核核心事实，不涵盖整段复合回答或普遍因果模型。

## Recorded Dimension Scores / 已确定的逐维分数

The following values reproduce assessment v1.0. They are ordinal judgments over different scoped tasks and must not be averaged into a model score or used as a league table. **NA = not applicable; NE = not evaluable from available evidence. Neither is zero.**

下表保留v1.0评测分值。不同案例的范围不同，序数分值不能平均为模型总分，也不能据此排名。**NA = 不适用；NE = 证据不足以评分，均不等于0。**

| Case | IU | SR | CC | FA | TR | SC | RH | UC |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| [CEA-028](../cases/ai-response-evaluation/CEA-028.md) | 2 | 4 | 2 | NE | NE | NE | 2 | 1 |
| [CEA-022](../cases/ai-response-evaluation/CEA-022.md) | 4 | 4 | 3 | 4 | 4 | NE | 4 | 4 |
| [CEA-021](../cases/ai-response-evaluation/CEA-021.md) | 4 | 4 | 4 | 3 | 3 | NE | 4 | 3 |
| [CEA-020](../cases/ai-response-evaluation/CEA-020.md) | 3 | 3 | 3 | NE | NE | 3 | 3 | 3 |
| [CEA-019](../cases/ai-response-evaluation/CEA-019.md) | 4 | 3 | NA | 3 | NA | NE | 3 | 4 |
| [CEA-011](../cases/ai-response-evaluation/CEA-011.md) | 4 | 4 | 4 | NE | NA | NE | 3 | 4 |
| [CEA-007](../cases/ai-response-evaluation/CEA-007.md) | 4 | 4 | 4 | NA | NA | NA | 4 | NA |
| [CEA-008](../cases/ai-response-evaluation/CEA-008.md) | 4 | 4 | 4 | 4 | NA | 3 | 4 | 4 |
| [CEA-004](../cases/ai-response-evaluation/CEA-004.md) | 4 | 4 | 4 | 4 | NA | NE | 4 | 3 |
| [CEA-001](../cases/ai-response-evaluation/CEA-001.md) | 4 | 4 | 4 | NE | NA | NE | 4 | 4 |


IU: Intent Understanding / 意图理解 · SR: Semantic Relevance / 语义相关性 · CC: Cultural Competence / 文化语境 · FA: Factual Accuracy / 事实准确性 · TR: Temporal Relevance / 时效性 · SC: Source Credibility / 来源可信度 · RH: Response Helpfulness / 回答有用性 · UC: Uncertainty Calibration / 不确定性表达。

## Research Interpretation / 研究解释范围

These cases demonstrate why intent, evidence quality, context, time, and uncertainty need separate assessment. They do not establish an error prevalence, a causal improvement, a controlled prompt effect, or a comparison between model populations. The seven web pages are selected newly retrieved result objects, not a representative sample of a search engine's results. No historical ranking is claimed.

这些案例说明意图、证据质量、语境、时间与不确定性需要分别评估，但不构成错误发生率、因果提升、控制提示效果或不同模型总体之间的比较。七条网页是选取的新检索结果对象，不代表某搜索引擎结果的代表性样本，也不声称复现历史排名。

The review is independent and AI-assisted, without independent human blinded ratings, inter-rater reliability estimates, or controlled retesting. Source capture gaps are not automatically response defects, and reviewer-generated questions are not original-response claims. The [research framework](../methodology/research-framework.md), [rubric](../methodology/evaluation-rubric.md), and [limitations](../methodology/limitations.md) define the interpretation boundaries.

本评测是AI辅助的独立研究，没有独立人类盲评、评审一致性估计或控制变量复测。材料采集缺口不自动算作回答缺陷；评审者提出的问题也不是原答断言。解释边界详见[研究框架](../methodology/research-framework.md)、[评测标准](../methodology/evaluation-rubric.md)和[研究局限](../methodology/limitations.md)。

