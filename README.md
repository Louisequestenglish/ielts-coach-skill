# 雅思教练 IELTS Coach

> 雅思教练系列 · 旷野英语雅思核心课配套。三份学员端 AI 教练，各占「练透」流程的一步：不代写、不打分、不当考官，只在他自己那一版上给反馈。
>
> 作者：旷野英语工作室 路易斯 & Kaylee · License: [CC-BY-NC-4.0](LICENSE)

## 三个教练

| 教练 | 定位 |
|---|---|
| `ielts-speaking-coach` 口语超级陪练 | 只占「练透 1 道雅思口语」第 3 步；单句 + P1/P2/P3 同一套；嫌难随时降难度；练完说「收清单」 |
| `ielts-reading-coach` 精读教练 | 只带三件事：卡住的长难句 / 段落层次批改 / 验收（长难句 + chunks） |
| `ielts-writing-coach` 写作教练 | 只接「练透 1 道写作」后半段：查扣题 / 查标注 / 润色 / 核对 / 收复盘 |

另有附加件：

| 附加件 | 定位 |
|---|---|
| `ielts-my-lifestory` 我的生活故事 | P2 语料工坊：把学生真实经历打磨成 P2 故事底料（串题 / 积累两种模式，逐段配跟读），只做材料、不教答题 |

## 安装

选一条适合你的：

| 你的情况 | 安装方式 |
|---|---|
| 手机 / 豆包 App 用户 | 让老师发你技能分享链接，在**豆包 App 内**点开 → 「添加技能」。微信或浏览器里打开无效，必须是豆包 App |
| Claude Code · 海外 / 有代理 | 一条命令：`npx skills add Louisequestenglish/ielts-coach-skill -g -y`（自动检查更新） |
| Claude Code · 国内直连 | 一条命令：`npx skills add https://gitee.com/louises-english-quest/ielts-coach-skill/repository/archive/main.zip -g -y`（更新时重跑这条命令） |
| 手动安装 | 打开 [Gitee 仓库](https://gitee.com/louises-english-quest/ielts-coach-skill) →「下载 ZIP」→ 解压 → 把四个文件夹拖进技能目录：macOS/Linux 放 `~/.claude/skills/`，Windows 放 `C:\Users\用户名\.claude\skills\`，WorkBuddy 放 `~/.workbuddy/skills/` |

装到 Claude Code / Codex / WorkBuddy 等 agent；装完直接说「练口语」「查扣题」就能用。skill 版能读本地文件、帮学生留练习档案。

课程学员在课程文档里就有嵌好的短提示词，不用装任何东西（随课程内部分发，不在这里）。

## 设计原则

- AI 只在学生无法自评的地方给反馈；他能自己判断的，做成功能只会让他更弱。
- 顺序永远是：先让他自己出东西，再给判断。他什么都没给 → 先要一次。
- 不代写、不给范文、不打分、不估分、不模拟考官。
- 题目、答案、解析、步骤都在学生自己的课程文档里，AI 一律指回，不复制。
- 口语的第 1/2/4 步、写作的前 3 步是学生自己的活，AI 不参与、也不讲怎么做。

## 配套课程

三个教练对位「旷野英语雅思核心课」的练透模块，「我的生活故事」对位 P2 语料线；建议配合课程使用。

课程咨询：抖音 路易斯@旷野英语雅思托福

## 质量验证

口语、写作教练的 `evals/` 里是 skill 版盲测样本（skill-evals.json）与运行记录：改一次源，重跑同一批样本，对照判定标准逐条过，破线才改、改完再验。（提示词版盲测夹具已随提示词版一起退役。）

## Credit

- 作者：旷野英语工作室 路易斯 & Kaylee——四个教练 skill 合作研发
- 「我的生活故事」方法借鉴李笑来《人人都能用英语》「说自己想说的话」：https://github.com/xiaolai/everyone-can-use-english

## License

[CC-BY-NC-4.0](LICENSE)——署名-非商业使用；课程学员随课程使用不受限。
