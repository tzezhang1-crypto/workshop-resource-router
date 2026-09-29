# 教師研習資源路由

`workshop-resource-router` 是給 ChatGPT App／Codex 使用的資源導航 Skill，協助教師研習時判斷應該使用哪個設定、Skill、Plugin、repo 或 OpenAI 官方文件。

## 功能

- 判斷需求屬於設定規則、內部工具、外部連接、可安裝 Skill、repo 工作流或 OpenAI 內建功能。
- 選擇最小且直接對應的資源入口。
- 提供資源名稱、連結、適用原因、使用方式與可驗收的成功條件。
- 避免把 OpenCode 專用路徑套用到 ChatGPT App／Codex。

## 使用方式

在 Codex 中使用：

```text
$workshop-resource-router
幫我為這個教師研習任務選擇正確的資源與驗收方式。
```

也可以直接描述任務，讓 Skill 協助判斷應使用的工具或資源。

## 內容

- `SKILL.md`：主要路由規則。
- `agents/openai.yaml`：Skill 在 Codex 中的顯示名稱、簡介與預設提示。
- `references/repo-map.md`：需求與正式資源入口的對照表。

## 重要原則

- 優先使用 ChatGPT App／Codex 的內建功能與官方入口。
- 不推薦不必要的 API key。
- 不推薦 `~/.config/opencode/skills`、`opencode.json` 或其他 OpenCode 專用路徑。
- GitHub 只作為資源入口或配套工具，不把 GitHub 操作本身變成課程主題。

