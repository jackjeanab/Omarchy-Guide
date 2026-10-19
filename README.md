# Omarchy Linux 完全入門指南

一本給完全新手的 Omarchy Linux 教材，重點放在**內建 AI 代理**。

## 這是什麼

[Omarchy](https://omarchy.org/) 是由 DHH（David Heinemeier Hansson）主導的 Linux 發行版，基於 Arch Linux + Hyprland + Quickshell，主打「開箱即用」與內建的 AI 代理。

本書從零開始，帶你從安裝到善用 AI 代理，每一章都是獨立檔案。

## 目錄

| 章節 | 內容 |
|---|---|
| [00-前言與目錄](00-前言與目錄.md) | 導讀、排版約定、閱讀方式 |
| [01-導論](01-導論.md) | Omarchy 是什麼、技術堆疊、三大特色 |
| [02-安裝與基本操作](02-安裝與基本操作.md) | 下載驗證、寫入 USB、安裝、pacman 套件管理 |
| [03-桌面環境與工作流程](03-桌面環境與工作流程.md) | Hyprland 平鋪視窗、工作區、快捷鍵、主題 |
| [04-內建軟體介紹](04-內建軟體介紹.md) | Neovim、Obsidian、Chromium、Docker、tmux、Git… |
| [05-內建AI代理](05-內建AI代理.md) ⭐ | 本書重點：AI 代理的六大功能與實例 |
| [06-實務應用](06-實務應用.md) | 提問技巧、除錯迴圈、從零做一個網站 |
| [07-系統管理與維護](07-系統管理與維護.md) | 更新、監控、清理、備份、讀日誌 |
| [08-進階客製化](08-進階客製化.md) | 自訂提示詞、接 API、寫插件、自動化 |
| [09-學習資源與附錄](09-學習資源與附錄.md) | 資源地圖、FAQ、指令速查表 |

## 怎麼讀

- **新手**：照 00 → 01 → … → 09 的順序讀，每章的「動手練習」一定要做。
- **有基礎**：直接跳到 [05-內建AI代理](05-內建AI代理.md)。

## 圖表

- `assets/` 內含 3 張 SVG 圖（技術堆疊、桌面佈局、AI 代理架構）
- 各章內文另有 Mermaid 流程圖／時序圖，用 Obsidian 或 GitHub 都能直接渲染

建議用 [Obsidian](https://obsidian.md/) 開啟此資料夾（Open folder as vault），連結與圖表會完整顯示。

## 作者

**jackjeanab** &lt;jackjeanab@gmail.com&gt;

## 授權

MIT License（見 [LICENSE](LICENSE)）

## 版本

內容依 **Omarchy 4.x（Quattro）** 撰寫，最後更新：2026-10-19。
Linux 更新快速，實際功能請以[官方手冊](https://learn.omacom.io/2/the-omarchy-manual)為準。
