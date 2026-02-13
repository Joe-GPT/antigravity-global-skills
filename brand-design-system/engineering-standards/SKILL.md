---
name: Engineering Standards
description: 定義前端框架、組件命名規則、CSS 架構與代碼風格。
---

# 工程開發標準 (Engineering Standards)

## 1. Skill 名稱

- **資料夾**: `engineering-standards`
- **顯示名稱**: 工程開發標準 (Engineering Standards)

## 2. 描述

本 Skill 專注於品牌的「技術實作」。它將視覺設計轉化為可維護的代碼，確保開發的一致性與品質。

## 3. 使用時機

- **當用戶需求涉及**：
  - 撰寫 HTML/CSS/JavaScript 代碼。
  - 建立前端組件 (Components)。
  - 設定 CSS 框架 (如 Tailwind, Bootstrap)。
  - 命名變數與類別 (Naming Conventions)。

## 4. 審查清單 (Review Checklist)

在編寫代碼時，請確認：

- [ ] **技術堆疊 (Tech Stack)**：
  - **CSS 框架**: Tailwind CSS (優先) 或 Modern Vanilla CSS.
  - **核心功能**: 必須支援 **Dark Mode** (預設).
- [ ] **視覺特效實作**:
  - **Glow Effects**: 使用 `box-shadow` 與 `filter: drop-shadow` 模擬霓虹發光.
  - **Glassmorphism**: 使用 `backdrop-filter: blur()` 與半透明背景.
  - **Animations**: 使用 CSS Keyframes 實現流線動態與 Hover 效果.
- [ ] **命名規範**：
  - Class 命名是否具語意化 (BEM 或 Utility-first)？
  - 變數命名是否清晰 (例如 `--neon-blue`, `--deep-navy`)？
- [ ] **組件複用**：
  - 是否遵循 DRY (Don't Repeat Yourself) 原則？
  - 是否將可複用的 UI 封裝為組件？
- [ ] **響應式設計**：
  - **Grid System**: 針對高密度資訊 (High-density information) 優化網格佈局.
  - 是否考慮了 Mobile-first 的斷點設定？

## 5. 格式標準

- **語言**：繁體中文 (台灣)。
- **代碼風格**：Prettier / ESLint 標準。
