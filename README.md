# Audit Report Lab｜内部审计报告写作实验室

**核心主张:心中有报告,全过程成稿。**

一个开源的内部审计报告写作知识库——包含原创理论、写作方法论、通用模板、脱敏案例与 AI 辅助 Prompt,目标是逐步成长为一份内部审计报告写作知识图谱,而非又一个审计资料大杂烩。

## 项目结构

```
audit-report-lab/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
│
├── 01-theory/                          理论层:项目的原创理论主线
│   ├── 01-心中有报告.md
│   ├── 02-审计成果形成理论.md
│   ├── 03-审计报告三角模型.md          ← 项目最具辨识度的原创理论
│   ├── 04-全过程成稿理论.md
│   └── 05-审计信息沉淀与认知阻抗.md
│
├── 02-methodology/                     方法层:理论如何落地为写作动作
│   ├── 01-审计报告写作逻辑.md
│   ├── 02-审计问题六要素.md            (FDRRRA 模型)
│   ├── 03-问题标题写作.md
│   ├── 04-原因分析方法.md              (五层根因模型)
│   ├── 05-风险影响分析.md
│   ├── 06-审计建议设计.md
│   └── 07-审计报告十条黄金法则.md
│
├── 03-templates/                       工具层:可直接复用的报告模板
│   ├── 综合审计报告模板.md
│   ├── 专项审计报告模板.md
│   ├── 经济责任审计报告模板.md
│   └── 内控审计报告模板.md
│
├── 04-case-library/                    案例层:脱敏案例(v1.0 起步 3 个,规划扩展至 500+)
│   ├── README.md
│   ├── 采购审计案例.md
│   ├── 工程审计案例.md
│   └── 费用审计案例.md
│
└── 05-ai/                              AI 辅助:审计报告 Prompt Library
    ├── README.md
    ├── 审计问题提炼Prompt.md
    ├── 审计报告生成Prompt.md
    └── 审计报告质量复核Prompt.md
```

## 四层结构总览

```
                 Audit Report Lab
                       │
        ┌──────────────┼──────────────┐
        │              │              │
      理论层          方法层          工具层
        │              │              │
   成果形成理论     六要素模型       Templates
   三角模型         原因模型         Checklist / Prompt
   认知阻抗         风险模型
   全过程成稿       问题模型
        │              │              │
        └──────────────┼──────────────┘
                       │
                    案例层
                       │
                 3 → 50 → 100 → 500 个案例
```

## 从这里开始读

- **只想直接用模板**:进 `03-templates/`,挑选对应报告类型
- **想理解方法为什么这样设计**:从 `02-methodology/01-审计报告写作逻辑.md` 开始
- **想理解项目的原创理论**:从 `01-theory/01-心中有报告.md` 开始,按编号顺序读完五篇,`03-审计报告三角模型.md` 是核心
- **想看实际案例怎么写**:进 `04-case-library/`
- **想用 AI 辅助**:进 `05-ai/`

## 版本规划

| 版本 | 内容 |
|---|---|
| v1.0.0 | 5篇理论 + 7篇方法论 + 4个模板 + 3个案例 + 3个AI Prompt(当前版本) |
| v1.1 | 案例库扩展至 50 个 |
| v1.2 | 案例库扩展至 100 个 |
| v2.0 | 案例库扩展至 500 个,AI Prompt 体系与案例检索联动 |

详见 `CHANGELOG.md`。

## 如何参与

见 `CONTRIBUTING.md`。

## 上传/同步到你自己的 GitHub

```bash
cd audit-report-lab
git init
git add .
git commit -m "Initial commit: Audit Report Lab v1.0.0"
git branch -M main
git remote add origin https://github.com/<你的用户名>/audit-report-lab.git
git push -u origin main
```

（请先在 GitHub 网站新建一个空仓库,不要勾选自动生成 README,再替换上面的远程地址。）

## License

MIT — 见 `LICENSE`。

---

> 本项目的原创理论主线是"心中有报告"与"审计报告三角模型",请在传播和引用时保留这条主线的完整性,不要将其拆散混入通用模板资料中。
