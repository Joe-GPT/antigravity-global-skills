---
name: 品牌設計系統 (Brand Design System)
description: 管理與調用品牌設計規範的核心 Skill。負責根據用戶需求路由至適當的子 Skill (視覺、工程、文案)。
---

# 品牌設計系統 (Brand Design System)

## 1. Skill 名稱

- **資料夾**: `brand-design-system`
- **顯示名稱**: 品牌設計系統 (Brand Design System)

## 2. 描述

本 Skill 作為品牌設計系統的總入口。它定義了如何在專案中應用一致的視覺、工程和內容策略。根據用戶的具體需求，它會指引你調用下轄的子 Skill：

- **視覺識別 (Visual Identity)**: 顏色、字體、Logo。
- **工程標準 (Engineering Standards)**: 代碼規範、框架。
- **內容策略 (Content Strategy)**: 文案語氣、溝通風格。

## 3. 使用時機

- **當用戶需求涉及**：
  - 創建新的網頁或應用程式介面。
  - 撰寫行銷文案或系統通知。
  - 統一現有產品的視覺風格。
  - 詢問關於 Logo 使用或品牌顏色的問題。

## 4. 審查清單 (Review Checklist)

在執行品牌相關任務時，請確認：

- [ ] **需求分析**：是否已釐清用戶是需要「視覺設計」、「程式開發」還是「文案撰寫」？
- [ ] **子 Skill 調用**：
  - 若涉及 UI/圖片 -> 調用 `visual-identity`。
  - 若涉及 CSS/Code -> 調用 `engineering-standards`。
  - 若涉及 文字/語氣 -> 調用 `content-strategy`。
- [ ] **資源檢查**：
  - 是否需要從 `assets/` 目錄獲取 Logo 或 PDF 指南？

## 5. 格式標準

- **語言**：繁體中文 (台灣)。
- **原則**：結論先行。

## 6. 資產 (Assets)

- **位置**: `assets/` 目錄。
- **內容**: 包含 Logo 原始檔、PDF 品牌手冊等。
