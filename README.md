# Hi, I'm Ryuki Tobita 👋

フロントエンドからクラウド基盤まで手がけるエンジニアです。最近は、AI エージェント (Claude Code / Codex) を日々の開発に組み込むための道具を作っています。
Engineer working across the stack, from frontend to cloud infrastructure. Lately I build tools that put AI coding agents (Claude Code / Codex) to work in day-to-day development.

🌐 **Portfolio:** [my-portfolio-second.vercel.app](https://my-portfolio-second.vercel.app)

## 主な制作物 / Featured work

### AI エージェントまわり / Agent tooling

| リポジトリ / Repo | 内容 / What it is |
| --- | --- |
| [shared-memory](https://github.com/reeschan/shared-memory) | Claude Code / Codex / Kimi が共通で参照する、ローカル完結の共有メモリ RAG (Markdown を正とし、OpenSearch + Sudachi・Qwen3-Embedding で検索、MCP で読み書き) / Local-only shared memory RAG for multiple AI agents: Markdown as the source of truth, OpenSearch + Sudachi and Qwen3-Embedding for search, served over MCP |
| [pbi-orchestration-jev](https://github.com/reeschan/pbi-orchestration-jev) | 複数ファイルにまたがる実装を PBI に分け、サブエージェント (Codex / Antigravity / Claude Code) に振り分けてレビューする Claude Code スキル。モデル選びと差し戻しの判断を Jev で点検する / Claude Code skill that splits multi-file work into PBIs, routes them to sub-agents (Codex / Antigravity / Claude Code) and reviews the results, with Jev-gated model selection and rework |
| [agentcron](https://github.com/reeschan/agentcron) | Cron 式でローカルの AI エージェント (Claude Code / Codex / 任意のコマンド) を起動する Go 製の常駐スケジューラ。ロック・リトライ・実行履歴つき / Resident scheduler in Go that launches local AI agents (Claude Code / Codex / any command) on cron schedules, with locking, retries and run history |
| [ai-session-knowledge-viewer](https://github.com/reeschan/ai-session-knowledge-viewer) | Claude Code / Codex の会話ログを LLM で要約・分類し、学びをナレッジとして閲覧するローカル Web アプリ (Hono) / Local web app (Hono) that summarizes and categorizes Claude Code / Codex session logs with an LLM and turns them into a browsable knowledge base |
| [claude-skill-style-guide](https://github.com/reeschan/claude-skill-style-guide) | 自由記述から UI テーマ (Tailwind v4 `theme.css`・トークン・スタイルガイド) を生成する Claude Code スキル / Claude Code skill that generates UI themes from a free-form description |

### アプリ / Apps

| リポジトリ / Repo | 内容 / What it is |
| --- | --- |
| [my-portfolio-second](https://github.com/reeschan/my-portfolio-second) | タブ風 UI・three.js の 3D 背景・職務経歴に答える AI チャットを備えたポートフォリオ / Portfolio with a tab-style UI, three.js backgrounds and a résumé chat |
| [management-self-pieces](https://github.com/reeschan/management-self-pieces) | 自分の成果物 (アプリ・スキル・文書) を Node として 3D 空間に浮かべ、Asana でチケット管理する個人用ダッシュボード / Personal dashboard that shows my work (apps, skills, docs) as nodes in a 3D graph and tracks tickets in Asana |

## 技術 / Tech

TypeScript · React · Next.js · Hono · Tailwind CSS · three.js · Node.js · Go · Python · PostgreSQL (Neon + Drizzle) · OpenSearch · MCP · AWS · Vercel · Claude Code · Codex
