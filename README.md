# 热门 AI 工具平替 · 变现项目收藏库

> 创建：2026-07-11 ｜ 目标：从 GitHub 拉取当前热门、可复刻赚钱的 AI 工具平替类开源项目
> 方向：**AI 工具平替**（对标 ElevenLabs / 商业 SaaS，clone 下来包装成 API 或托管服务收费）
> 目标仓库：`msa505/money-makers`（待老王建空仓库或给 token 后 push）

## 为什么选「AI 工具平替」这个方向

商业 AI 工具按量/订阅收费（ElevenLabs $22-99/月、商业 PDF/OCR/爬虫 API 按调用计费）。
开源平替把同样能力本地化、免费化，你拿它做两件事就能赚钱：
1. **包装成托管 API**——按调用量定价，对标商业档打 6-8 折，中小客户直接迁移
2. **垂直行业私有化部署**——给电商/律所/教育/播客做专项服务，项目制定价，客单 $500+

这类项目最适合「复刻赚钱」：需求已被商业产品验证，开源平替去掉了获客教育成本。

## 已收录项目（5 个代表）

| 项目 | 对标商业品 | Star | 一句话 | 变现切入点 |
|------|-----------|------|--------|-----------|
| [voicebox](projects/voicebox/) | ElevenLabs | ~22K | 本地语音克隆+合成工作室，REST API | 托管 TTS API / 播客·有声书·游戏 NPC 配音 |
| [stirling-pdf](projects/stirling-pdf/) | 商业 PDF 编辑器 | ~51K | 瑞士军刀级 PDF 处理，Docker 一键 | PDF 处理 API / 企业私有化部署 |
| [firecrawl](projects/firecrawl/) | 商业爬虫 API | ~52K | 搜索/抓取/交互网页的 API | 数据采集 API / SEO·市场调研服务 |
| [ai-website-cloner](projects/ai-website-cloner/) | 建站服务 | ~425 | 一条命令克隆任意网站 | 建站外包 / 竞品站快速复刻 |
| [unlimited-ocr](projects/unlimited-ocr/) | 商业 OCR | ~800 | 长文档一次性 OCR 解析 | 文档数字化 API / 票据·档案识别 |

> 每个项目子目录下有 `00-变现分析.md`，含：许可证、具体变现路径、复刻难度、给老王的建议。

## 复刻优先级建议（明天审核参考）

1. **stirling-pdf** — 最稳：需求永恒（PDF 处理），Docker 部署简单，企业私有化部署客单高
2. **voicebox** — 最热：语音赛道需求爆发，但本地 TTS 延迟高，适合预生成/批量场景
3. **firecrawl** — 最刚需：AI 应用都需要网页数据，API 化最容易收费
4. **unlimited-ocr** — 最轻：OCR 是高频长尾需求，做垂直（票据/档案）容易差异化
5. **ai-website-cloner** — 最新：建站外包市场大，但技术门槛低、易被卷，适合做模板差异化

## 许可证提醒（重要）

所有项目均为开源，但许可证不同（MIT / Apache / AGPL 等）。**AGPL 项目若提供网络服务必须开源衍生代码**。
复刻前务必读各项目 `LICENSE` 文件，确认商用合规。详细见各 `00-变现分析.md`。

## 待办

- [ ] 老王在 GitHub 建空仓库 `msa505/money-makers` 或提供 msa505 写 token
- [ ] 我 `git init` + commit 本地内容，add remote 后 `git push -u origin main`
- [ ] 补充更多赛道代表（AI 视频 / 图像生成平替）视明天审核方向
