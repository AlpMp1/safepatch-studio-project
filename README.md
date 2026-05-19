# SafePatch Studio

SafePatch Studio 是一个 AI 依赖风险分析与安全修复工作台，面向开源项目与中小团队。

## 项目能力

- 读取 lockfile、SBOM、依赖公告、源码调用链、测试日志和历史升级记录
- 判断依赖风险是否真实可达，减少无效告警
- 生成兼容升级计划、依赖修复 patch、回归测试 fixture 和发布报告
- 输出 PR 级验证矩阵、风险等级、灰度建议和回滚方案

## 部署方式

这是一个静态 HTML demo，可以直接部署到 GitHub Pages、Netlify、Vercel 或任意静态托管平台。

GitHub Pages:
1. 新建公开仓库
2. 上传 index.html、README.md 和 demo-data 文件夹
3. Settings → Pages → Deploy from a branch
4. 选择 main / root
5. 保存后等待发布链接生成
