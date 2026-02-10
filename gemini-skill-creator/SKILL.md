---
name: Gemini skill creator
description: 建立 Gemini Skill 的全域標準規範與模板。建立任何新 Skill 時必須引用此規範。
---

# Gemini Skill Creator

## 1. Skill 名稱 (Name)

- **規範**：
  - 資料夾名稱：使用 `kebab-case` (例如 `my-new-skill`)。
  - 顯示名稱 (Display Name)：在 `SKILL.md` frontmatter 的 `name` 欄位中使用自然語言，支援繁體中文 (例如 "股票分析助手")。
- **範例**：
  - 資料夾: `gemini-skill-creator`
  - Name: `Gemini skill creator`

## 2. 描述 (Description)

- **規範**：
  - 清楚說明此 Skill 的核心功能與解決的問題。
  - 必須包含在 `SKILL.md` 的 frontmatter `description` 欄位。
  - 語言：繁體中文 (台灣)。

## 3. 使用時機 (Usage Timing)

- **規範**：
  - 明確列出何時應該使用此 Skill。
  - 包含具體的觸發情境或用戶意圖 (User Intent)。
- **範例**：
  - "當用戶需要創建一個新的 MCP Tool 定義時..."
  - "當用戶詢問關於 n8n 節點配置時..."

## 4. 審查清單 (Review Checklist)

建立新 Skill 前，請務必確認以下項目：

- [ ] **結構完整性**：
  - 包含 `SKILL.md` (必備)。
  - 若有程式碼或複雜邏輯，包含 `README.md`。
  - 適當的目錄分級 (例如 `scripts/`, `examples/`)。
- [ ] **語言與風格**：
  - 內容為 **繁體中文 (台灣)**。
  - 遵循 **結論先行 (Pyramid Principle)**。
  - 註解解釋了 "為什麼" 而非僅是 "做什麼"。
- [ ] **安全性**：
  - 無明文 API Keys / Secrets。
  - 外部服務整合有提醒環境變數配置。
- [ ] **版本控管**：
  - 已初始化 Git。
  - 提交訊息 (Commit Message) 符合 Conventional Commits (feat:, fix:, docs:)。

## 5. 格式標準 (Format Standards)

- **檔案格式**：Markdown (`.md`)。
- **Frontmatter**：必須包含 YAML frontmatter 定義 `name` 與 `description`。
- **標題層級**：使用 H1 (#) 作為 Skill 標題，H2 (##) 作為主要章節。
- **程式碼區塊**：必須指定語言 (例如 ```python,```bash)。

## 6. 版本 (Version)

- **目前的版本**：1.0.0
- **更新日期**：2026-02-10
