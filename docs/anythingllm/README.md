# AnythingLLM 使用指南

![版本](https://img.shields.io/badge/版本-1.7.4-blue)
![更新日期](https://img.shields.io/badge/更新日期-2025--04--05-brightgreen)
![作者](https://img.shields.io/badge/作者-AI%20工具教學團隊-orange)

## 關於 AnythingLLM

AnythingLLM 是一個功能強大的本地知識庫問答工具，它允許您從各種文件中提取資訊，並使用大型語言模型（LLM）來回答與這些文件相關的問題。無論您是初學者還是進階使用者，本指南都將幫助您充分利用 AnythingLLM 的強大功能。

### 主要功能

- **文件處理**：支援 PDF、Word、TXT、Markdown 等多種格式
- **智能問答**：基於您的文件內容提供準確的回答
- **知識庫管理**：輕鬆組織和管理您的文件和資訊
- **多模型支援**：可使用本地或雲端的各種 LLM 模型
- **多平台支援**：提供 Windows 和 macOS 版本

## 文檔目錄

### 入門指南
- [完整入門指南](../getting-started.md) - 快速了解 AnythingLLM 的基本概念和安裝
- [Windows 快速上手](quickstart/windows/README.md) - Windows 系統安裝和基本設置
- [macOS 快速上手](quickstart/macos/README.md) - macOS 系統安裝和基本設置

### 基礎使用指南
- [Windows 基礎使用](basic/windows/README.md) - Windows 版本的日常操作和功能介紹
- [macOS 基礎使用](basic/macos/README.md) - macOS 版本的日常操作和功能介紹

### 進階使用指南
- [Windows 進階使用](advanced/windows/README.md) - Windows 版本的高級功能和最佳實踐
- [macOS 進階使用](advanced/macos/README.md) - macOS 版本的高級功能和最佳實踐

### 問卷調查工具指南
- [問卷調查工具總覽](survey/README.md) - 了解如何使用 AnythingLLM 進行問卷設計和分析
- [問卷設計與 LLM 輔助指南](survey/survey_guide_with_llm.md) - 使用 AI 優化問卷設計
- [問卷分析指南](survey/survey_analysis_guide.md) - 深入分析問卷結果
- [使用者體驗問卷範本](survey/user_experience_survey.md) - 現成可用的問卷範本
- [問卷操作指南](survey/survey_operation_guide.md) - 問卷發放與管理的詳細步驟

## 新手必讀：從零開始使用 AnythingLLM

如果您是首次使用 AnythingLLM，請按照以下步驟開始：

1. **安裝軟體**：
   - 根據您的作業系統選擇相應的[安裝指南](#入門指南)
   - 確保您的系統符合[最低需求](#系統需求)
   - 完成初始設定和登入

2. **上傳您的第一個文件**：
   - 點擊界面上的「新增文件」按鈕
   - 選擇您要上傳的文件（PDF、Word、TXT 等）
   - 等待系統處理文件（這可能需要幾分鐘，取決於文件大小）

3. **開始提問**：
   - 在下方的對話框輸入您的問題
   - 系統將根據您上傳的文件內容回答問題
   - 您可以繼續追問或變更問題方向

4. **管理您的知識庫**：
   - 使用左側的文件管理器組織文件
   - 建立文件夾分類不同主題
   - 為文件添加標籤以便快速查找

## 系統需求

### Windows 版本
- Windows 10/11 (64位元)
- 至少 8GB RAM（建議 16GB 以上）
- 至少 10GB 可用硬碟空間
- 穩定的網路連線

### macOS 版本
- macOS 11.0 (Big Sur) 或更新版本
- 支援 Intel 或 Apple Silicon 處理器
- 至少 8GB RAM（建議 16GB 以上）
- 至少 10GB 可用硬碟空間
- 穩定的網路連線

## 常見問題解答

### Q1: AnythingLLM 需要連接網際網路嗎？
**A**: 如果您使用本地模型（強烈建議），基本功能完全不需要網際網路。您只需在初次下載本地模型後，即可在完全離線的環境中使用 AnythingLLM 處理和查詢您的文件，這也是我們推薦的使用方式，以確保最佳的隱私保護和數據安全。

### Q2: 如何提高回答的準確性？
**A**: 上傳更多相關文件、使用較大參數的本地模型（如 Llama 3 70B）、優化文件分段設定，並學習如何提出明確的問題都可以提高回答的準確性。詳細請參考[進階使用指南](#進階使用指南)。

### Q3: 我可以在多台設備之間同步我的知識庫嗎？
**A**: 是的，您可以通過設定雲端同步功能來實現。詳情請參見進階使用指南中的「資料同步」部分。

### Q4: 我的文件安全嗎？
**A**: 使用本地模型時，AnythingLLM 將所有數據儲存在您的本地設備上，您的數據不會離開您的設備，完全確保隱私。這是我們推薦的使用方式。如果使用雲端模型，只有查詢會發送到雲端，而不是完整文件，但仍存在一定的隱私風險。

### Q5: 本地模型的效能如何？
**A**: 現代本地模型（如 Llama 3、Mistral、Vicuna 等）已經達到很高的效能水平，特別是在文件問答任務上表現優異。Apple Silicon 用戶還可以享受 Metal 優化的加速效能，提供流暢的使用體驗。對於大多數使用情境，本地模型已完全足夠，同時還能保護您的隱私。

## 版本資訊
- 當前版本：1.7.4
- 最後更新：2025-04-05

## 取得協助
- [官方文檔](https://docs.useanything.com/)
- [GitHub 討論區](https://github.com/Mintplex-Labs/anything-llm/discussions)
- [Discord 社群](https://discord.gg/anything-llm)

## 文檔更新機制
本文檔會定期根據官方更新進行維護。如發現任何問題或需要更新，請透過 GitHub Issues 回報。