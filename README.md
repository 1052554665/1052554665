<picture>
 <source media="(prefers-color-scheme: dark)" srcset="[YOUR-DARKMODE-IMAGE](https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png)">
 <source media="(prefers-color-scheme: light)" srcset="[YOUR-LIGHTMODE-IMAGE](https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png)">
 <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

# About me
> Stay hungry, stay foolish.
— Steve Jobs
<!-- TO DO: add more details about me later -->


Hi, I'm Yang Chen.

- 🔭 I’m currently pursuing postgraduate degree.
- 🌱 I’m currently learning signal processing, voiceprint recognition, data sicence and artificial intelligence.
- 📫 How to reach me: chen1052554665@gmail.com

<details open>
<summary>My top languages</summary>
  
| Rank | Languages |
|-----:|---------------|
|     1| Python          |
|     2| Matlab        |
|     3| C          |
|     4| C++         |
|     4| Java        |
|     5| Shell          |
</details>


# 整体科研工作流架构
```
1. Notion 定任务
2. Obsidian 查知识 / 记想法
Docker 保证环境一致 / 论文复现
1. PyCharm 写代码
2. GitHub 提交版本
3. W&B / TensorBoard 记录实验
Zotero 管理论文 / 自动生成引用
1. Notion 记录结果
2. Obsidian 复盘总结
```

## 整体科研工作流架构（核心设计）

```
数据层 → 知识层 → 实验层 → 项目层 → 输出层
```

| 层级  | 目标         | 工具                         |
| --- | ---------- | -------------------------- |
| 数据层 | 数据集、原始资料   | 本地 + NAS + Git LFS         |
| 知识层 | 理论、论文、笔记   | Obsidian、TexStudio、Drawio、Origin                   |
| 实验层 | 模型训练、调参    | PyCharm / VS Code + GPU服务器 |
| 项目层 | 代码管理、版本控制  | GitHub                     |
| 输出层 | 论文、报告、进度管理 | Notion                     |

👉 核心思想：
**Notion管“做什么”，Obsidian管“学什么”，GitHub管“做了什么”**


## 具体落地方案

- Notion：科研项目管理中枢
- Obsidian：知识管理（构建“科研大脑”）
- GitHub：科研工程化


# 工具协同
## AI工具协同

| 工具      | 用途                |
| ------- | ----------------- |
| ChatGPT | 方案设计 / debug / 思路 |
| Copilot、Codex | 写代码               |
| Lingma  | 国内补充（代码生成）        |
| Warp    | agent终端管理|



## 开发工具协同


| 工具      | 使用场景        |
| ------- | ----------- |
| PyCharm | 主项目（深度学习）   |
| VS Code | 远程开发 / 轻量编辑 |
| MATLAB  | 信号处理验证      |

```text
Ubuntu
 ├── Miniconda
 ├── PyTorch
 ├── PyCharm
 ├── Docker
 ├── Node20(nvm)
 ├── Claude Code
 └── GitHub
```
```text
Ubuntu
 └── Miniconda
      └── conda env
           └── PyTorch
```

# My Current projects
- [AW-DPCNN](https://github.com/1052554665/AW-DPCNN)
- [mvdr-based-on-multi-arm-spiral-array](https://github.com/1052554665/mvdr-based-on-multi-arm-spiral-array)
- [transformer](https://github.com/1052554665/transformer)
---
