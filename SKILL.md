---
name: workshop-resource-router
description: 為 ChatGPT App／Codex 教師研習選擇正確的設定、repo 或 Skill。使用者詢問內部工具、外部工具、語音、YAML、簡報、影片、RDQ、Apps、Plugins 或 Sites 的資源與安裝入口時使用；不要套用 OpenCode 專用路徑。
---

# 教師研習資源路由

1. 先判斷使用者要的是：
   - 設定規則
   - 內部工具包
   - 外部連接指南
   - 可安裝 Skill
   - repo 工作流
   - OpenAI 內建功能或官方文件
2. 讀取 `references/repo-map.md`，選最小且直接對應的入口。
3. 回覆時提供：
   - 資源名稱
   - 連結
   - 為什麼適合
   - ChatGPT App／Codex 的使用方式
   - 一個可驗收的成功條件
4. 若來源文件包含 `~/.config/opencode/skills`、`opencode.json`、OpenCode 重啟或 OpenCode plugin，停止照抄，改用本 Skill 的 ChatGPT App／Codex 路徑。
5. 不把 GitHub 操作教成課程主題。學員可用下載 ZIP、ChatGPT Skills 上傳或由 Codex 安裝。
6. 不引導使用者申請不必要的 API key。
7. 若功能是 ChatGPT 內建（語音輸入、Apps／Plugins、Sites），優先給官方入口；repo 只作判斷指南或配套資源。

## 路由原則

- 四大內部工具 → `ai-agent-ep03`
- 外部工具與授權 → `ai-agent-ep04`
- 語音回答 → `agent-speak-skill`
- 語音文字輸入 → 本 repo 的設定檔
- YAML 圖片簡報 → `yaml-image-deck`
- 簡報 → `codex-presentation-skills`
- 影片 → `codex-video-specs` repo 模式
- RDQ → `rdq-skill-chatgpt-app`
- Apps／Plugins／Sites → OpenAI 官方說明

不要推薦 OpenCode 專版 RDQ、`~/.config/opencode/skills` 或 `opencode.json` 給本課學員。
