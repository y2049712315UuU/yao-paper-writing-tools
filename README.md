<div align="center">

# 🏔️ 垚·论文写作工具链

**v1.0.0 — 初版冰封**

</div>

一个专为中国农业政策/农村发展专业研究生设计的学术论文写作工具链。
目标期刊：**Land** (MDPI)。核心方法：**DID / PSM / 面板 / IV** 等定量分析。

## 📦 工具箱一览

| # | Skill | 功能 | 什么时候用 |
|---|-------|------|-----------|
| ① | **垚·文献深耕** | 搜论文 + 文献矩阵 + 精读 | 选题和写文献综述时 |
| ② | **垚·文章润色** | IMRaD 撰写 + 计量方法 + 英文润色 | 写初稿和改稿时 |
| ③ | **垚·引文鉴真** | 配引文 + DOI 验证 + 数据声明 | 怕引文不够或有假引用时 |
| ④ | **垚·模型诊断** | DID/PSM/面板诊断工具箱 | 模型跑完需要检查时 |
| ⑤ | **垚·审稿鉴证** | 3 审稿人模拟 + 魔鬼代言人 | 投稿前自检 |
| ⑥ | **垚·投稿打包** | MDPI 格式 + Cover Letter + PPT | 临门一脚 |
| 🧩 | **垚·论文工作流** | 6 合 1 编排器 | 想全流程走一遍时 |

## 🚀 快速开始

### 安装

将 skill 文件夹复制到 OpenClaw 的 `skills/` 目录下：

```bash
cp -r yao-* /path/to/your/skills/
```

或者直接 `git clone` 整个仓库到 workspace：

```bash
git clone https://github.com/BlackJack-UuU/yao-paper-writing-tools.git
cp -r yao-paper-writing-tools/yao-* /path/to/your/skills/
```

### 使用

在 OpenClaw 中直接说：

```
"搜中国农业补贴政策的 DID 文献"     →  垚·文献深耕
"帮我写 Land 期刊的 Introduction"    →  垚·文章润色
"帮我做 DID 平行趋势检验"            →  垚·模型诊断
"模拟 Land 期刊审稿"                 →  垚·审稿鉴证
"垚系列，全流程启动"                 →  垚·论文工作流
```

## ⚙️ 自定义指南

每个 skill 都有明确的 **自定义点位**，按你的研究内容改这些地方：

| 改什么 | 在哪改 | 举例 |
|--------|--------|------|
| 关键词表 | `yao-lit-deep/references/keywords.md` | 改成你的研究领域关键词 |
| 方法模板 | `yao-polish-write/references/method-templates.md` | 改成你的模型设定 |
| 数据来源 | `yao-citation-verify/references/data-declaration-templates.md` | 改成你用的数据 |
| 审稿关注点 | `yao-review-sim/SKILL.md` | 改成你目标期刊的审稿偏好 |

## 📌 版本历史

| 版本 | 日期 | 说明 |
|------|------|------|
| v1.0.0 | 2026-06-24 | 🎉 初版发布。中国农业政策 + Land (MDPI) 方向 |

后续版本建议按你的研究方向自定义后打 `v1.x.x` 标签。

## 📄 许可证

MIT — 随便改，随便分享，改完也不用通知我。

<div align="center">

**作者：BlackJack-UuU**

</div>
