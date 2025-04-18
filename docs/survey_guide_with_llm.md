# 使用 AnythingLLM 輔助問卷調查指南

![版本](https://img.shields.io/badge/版本-1.7.5-blue)
![更新日期](https://img.shields.io/badge/更新日期-2025--03--29-brightgreen)
![作者](https://img.shields.io/badge/作者-AI%20工具教學團隊-orange)

## 目錄
1. [問卷調查方法概述](#問卷調查方法概述)
2. [使用 AnythingLLM 輔助問卷設計](#使用-anythingllm-輔助問卷設計)
3. [問卷執行與資料收集](#問卷執行與資料收集)
4. [使用 AnythingLLM 分析問卷結果](#使用-anythingllm-分析問卷結果)
5. [最佳實踐建議](#最佳實踐建議)

## 問卷調查方法概述

### 研究方法的三個維度

1. **態度 vs. 行為**
   - 態度研究：了解受訪者的陳述信念
   - 行為研究：觀察實際行動
   
2. **質性 vs. 量性**
   - 質性：直接觀察或聽取意見
   - 量性：通過測量工具間接收集數據

3. **使用情境**
   - 自然使用
   - 腳本引導
   - 限定範圍
   - 非使用情境

### 研究階段
1. **策略階段**：確定研究方向
2. **設計階段**：改進問卷設計
3. **評估階段**：衡量成效

## 使用 AnythingLLM 輔助問卷設計

### 前置準備
1. 將研究目標和相關資料匯入 AnythingLLM
2. 建立專屬知識庫

### 問卷設計流程
1. **目標定義**
   - 使用 AnythingLLM 分析研究目標
   - 確定關鍵指標

2. **問題設計**
   - AI 輔助問題形式選擇
   - 問題措辭優化
   - 避免偏差檢查

3. **問卷結構**
   - 邏輯流程設計
   - 篩選題設置
   - 完整性檢查

## 問卷執行與資料收集

### 執行前準備
1. 預測試與修正
2. 取樣策略制定
3. 發放管道選擇

### 資料收集過程
1. 進度追蹤
2. 品質控制
3. 即時調整

## 使用 AnythingLLM 分析問卷結果

### 資料預處理
1. 資料清理
2. 格式標準化
3. 缺失值處理

### 分析方法
1. **描述性統計**
   - 基本統計量計算
   - 圖表視覺化

2. **進階分析**
   - 相關性分析
   - 群集分析
   - 因素分析

3. **質性資料分析**
   - 文本分析
   - 主題歸納
   - 情感分析

### 報告生成
1. 結果摘要
2. 關鍵發現
3. 建議事項

## 最佳實踐建議

### 問卷設計
1. 保持問題清晰簡潔
2. 避免引導性問題
3. 適當的問卷長度

### 執行過程
1. 確保樣本代表性
2. 維護資料安全
3. 遵守研究倫理

### 分析階段
1. 交叉驗證結果
2. 謹慎解釋數據
3. 提供可行建議

## 參考資源
- [Nielsen Norman Group 研究方法指南](https://www.nngroup.com/articles/which-ux-research-methods/)
- AnythingLLM 官方文件
- 問卷調查方法論相關文獻

## 附錄
- 常用問題類型範例
- 分析腳本範本
- 報告模板

## Prompt 設計指南

### 問卷設計階段的 Prompt 範例

1. **研究目標確認**
   ```
   請協助分析以下研究目標，並列出：
   1. 核心研究問題
   2. 關鍵測量指標
   3. 目標受眾特徵
   4. 預期研究成果
   
   研究目標：[您的研究目標]
   ```

2. **問題設計優化**
   ```
   請針對以下問題進行優化：
   1. 檢查問題是否有引導性
   2. 確保語言表達清晰簡潔
   3. 建議更好的問題形式
   4. 提供選項設計建議
   
   原始問題：[您的問題]
   目標受眾：[受眾描述]
   預期獲得的資訊：[資訊描述]
   ```

3. **問卷結構規劃**
   ```
   請協助規劃問卷結構，考慮：
   1. 問題順序邏輯
   2. 篩選題設置
   3. 分支邏輯
   4. 預估填答時間
   
   問卷主題：[主題]
   目標問題數：[數量]
   特殊需求：[需求描述]
   ```

### 資料分析階段的 Prompt 範例

1. **資料清理指引**
   ```
   請協助制定資料清理策略：
   1. 異常值判定標準
   2. 缺失值處理方法
   3. 資料轉換建議
   
   資料類型：[類型描述]
   樣本數量：[數量]
   特殊考量：[考量描述]
   ```

2. **統計分析建議**
   ```
   請建議適合的統計分析方法：
   1. 基礎統計分析
   2. 進階統計檢定
   3. 視覺化圖表
   
   研究假設：[假設描述]
   資料特性：[特性描述]
   分析目標：[目標描述]
   ```

3. **文本分析指引**
   ```
   請協助進行開放式問題回答分析：
   1. 關鍵主題識別
   2. 情感傾向分析
   3. 意見分類建議
   
   問題內容：[問題描述]
   回答數量：[數量]
   分析重點：[重點描述]
   ```

### Prompt 設計原則

1. **明確性**
   - 清楚說明目的和需求
   - 提供必要的背景資訊
   - 指定期望的輸出格式
   - 設定具體的評估標準

2. **結構化**
   - 使用編號或項目符號
   - 將複雜要求分解成小步驟
   - 按邏輯順序組織內容
   - 設定檢查點和確認步驟

3. **情境化**
   - 提供研究背景和目的
   - 說明目標受眾特徵
   - 描述應用場景和限制
   - 指出特殊考量事項

4. **可執行性**
   - 確保要求具體可行
   - 設定合理的範圍和限制
   - 提供必要的參考資料
   - 說明資源和時間限制

### 常見問題與解決方案

1. **回應不夠具體**
   - 加入量化要求（如：列出至少 3 個具體建議）
   - 要求提供實際例子
   - 設定明確的輸出格式
   - 要求包含可行性評估

2. **方向偏離**
   - 在 prompt 開頭重申核心目標
   - 設定明確的範圍限制
   - 要求定期確認方向
   - 提供檢查清單

3. **建議不切實際**
   - 明確說明資源限制
   - 提供現有條件和限制
   - 要求考慮實施成本
   - 要求提供替代方案

### 實際應用範例

1. **設計客戶滿意度調查**
   ```
   請協助設計一份客戶滿意度調查問卷：
   
   目標：評估我們的產品/服務滿意度
   受眾：現有客戶
   預期問題數：10-15題
   特殊需求：
   1. 包含 NPS 題目
   2. 評估各服務面向
   3. 收集改進建議
   
   請提供：
   1. 問題清單和選項
   2. 問題順序建議
   3. 填答時間估計
   4. 可能的分支邏輯
   ```

2. **分析開放式回答**
   ```
   請協助分析以下開放式問題的回答：
   
   問題：「您對我們的服務有什麼建議？」
   回答數量：50則
   
   請提供：
   1. 主要主題分類（至少3個）
   2. 每個主題的關鍵字
   3. 情感傾向分析
   4. 優先改進建議
   ```

### 效果評估與優化

1. **評估指標**
   - 回應的相關性
   - 建議的可行性
   - 分析的深度
   - 實施的效果

2. **優化策略**
   - 記錄成功的 prompt 模式
   - 持續調整和改進
   - 建立 prompt 範本庫
   - 收集使用者回饋 