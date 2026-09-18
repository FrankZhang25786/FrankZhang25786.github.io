# 张帆 · Fan Zhang

视觉检测与机器人学习项目作品集。页面使用原生 HTML / CSS，无外部字体、CDN 或访问统计；GitHub Pages 直接发布，无需构建。Vite 仅供开发时预览和验证。

## 项目

- 果园苹果检测与计数：YOLOv8、重叠切片、跨数据集评估；明确个人职责与小组集成结果。
- 强化学习优化器蒸馏：RNN / MLP × seq20 / seq100；统一更新次数及匹配种子评估。
- HeroBot：图像分类、传感器聚类与表格强化学习导航。

## GitHub Pages 发布

1. 在自己的 GitHub 账号下创建一个公开仓库，建议名称为 `frankzhang25786.github.io`。
2. 将 `index.html`、`assets` 文件夹和 `.nojekyll` 上传到 `main` 分支根目录；不要仅上传 ZIP 文件。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**，然后选择 **main** 和 **/(root)**，点击 **Save**。
5. 等待 GitHub Pages 构建完成，以该页面显示的 **Visit site** 地址为准。

如果使用不同名称的仓库，也可以采用同样设置；所有本地资源均为相对路径。

## 内容来源与维护

- `assets/orchard-000.jpg` 和 `assets/orchard-001.jpg` 原样提取自课程小组《Project Report》Figure 3，图像数据为 MinneApple。保留数据及小组来源说明；这些资产不随网站代码自动取得新的开放许可。
- 苹果检测指标来自课程最终报告的基线/集成方案对比；F1 是去重后的检测指标，不是计数准确率。
- HeroBot 准确率取提交材料中实际测试输出 `0.9950124621391296`，四舍五入为 99.50%；未沿用不一致的正文 99.75%。
- 论文数据取 `EMATM0055_dissertation_final_audit_20260904.pdf` 的 Table IV / VI / VII。CartPole corrected RNN L20 / L100 均值分别为 80.5117 / 51.7627，不沿用早期项目状态文件中的 113.261 / 63.215。教师来自原研究，页面不声称重新训练教师或已完成实体机器人部署。
- 项目日期尚未核定的课程项目不标年份。
- 网站不包含完整简历、电话、签名、原始团队报告或未公开的组员个人资料。

如更新学位状态、求职方向、项目结果或链接，请直接编辑 `index.html`。源代码分支链接应保留到实际工作的分支，避免只链接上游仓库。

GitHub Pages 官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
