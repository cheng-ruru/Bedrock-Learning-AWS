# Bedrock-Learning-AWS
從零開始學AWS Re：Learning AWS

## AWS Bedrock 是什麼？

簡單來說，AWS Bedrock 是一個讓 AI 變得超簡單的服務！你不需要自己架設伺服器或訓練 AI 模型，只要挑選適合的模型，就可以開始建立 AI 應用。
 **自動生成內容、讓客服更聰明、推薦個性化商品**，還是幫助用戶更快獲取資訊，Bedrock 都能搞定。

---

## 🔹 主要特色

1. **多種 AI 模型可選**：AWS 提供了不同的 AI 模型，讓你挑選最適合的。
2. **可客製化 AI 行為**：你可以微調模型，讓它更符合你的需求。
3. **可以跟其他 AWS 服務整合**：像是客服系統、電商推薦、文件處理等。

---

## 📌 AWS Bedrock 的資安解決方案

1. **資料隱私與保護**：
   - AWS Bedrock 支援資料加密，確保企業機密資訊不會被未授權存取。
   - 可與 AWS Identity and Access Management (IAM) 搭配使用，確保只有授權用戶可以存取 AI 服務。

2. **內容安全與合規性**：
   - 內建 **Guardrails (安全護欄)**，確保 AI 生成內容不偏離合規與道德標準，防止不適當內容的產生。
   - 可依據企業政策，設定 AI 生成內容的安全範圍，確保符合行業法規（如 GDPR、HIPAA）。

3. **存取控制與審計**：
   - 使用 AWS CloudTrail 進行活動監控，記錄 AI 服務的使用情況，確保系統合規。
   - 可設定 API 存取權限，確保只有特定應用程式或用戶可以與 AI 模型互動。

4. **模型安全性**：
   - AI 模型經過 AWS 內部測試，確保不會因惡意輸入而產生安全風險（如對抗性攻擊）。
   - 可設定 AI 輸出篩選機制，防止洩露敏感資訊。

---

## 📌 AWS Bedrock 的可以應用在哪?

- **電子商務個性化推薦**：某電商平台使用 Bedrock 來分析顧客購物行為，並提供個人化的產品推薦，提升銷售轉換率。
- **新聞與內容創作**：一間媒體公司運用 Bedrock 自動撰寫新聞摘要，提高新聞產出的速度與精準度。
- **智能客服**：某家企業的客服中心透過 Bedrock 來自動回應常見問題，減少人工負擔，並提高客戶滿意度。
- **遊戲 AI 劇情生成**：某款 RPG 遊戲使用 Bedrock 來生成角色對話，讓遊戲世界更具互動性與沉浸感。
- **文件處理與摘要**：企業運用 Bedrock 幫助快速整理大量文件，讓員工能更快獲取關鍵資訊。

---
## 🛠 Bedrock 的使用方式（適合不同技術背景的人）

### ✅ 不會寫程式的人
1. **使用 AWS 管理控制台**：
   - 透過簡單的介面選擇 AI 模型，輸入你的需求，Bedrock 會幫你產生結果。
   - 適合需要快速測試 AI 功能的使用者，如行銷團隊、客服人員。
   
2. **透過低程式設計工具**：
   - 可以結合 **Amazon Lex**、**Amazon Connect** 等 AWS 服務，讓 AI 自動處理客戶詢問。
   - 企業可利用 **Amazon Bedrock + No-Code/Low-Code 工具**（如 AWS SageMaker Canvas）來建立 AI 服務。
   
### ✅ 會寫程式的人
1. **使用 AWS SDK / API 呼叫 Bedrock**：
   - 透過 Python、JavaScript 等語言，使用 AWS SDK 設定和調用 AI 模型。
   - 適合開發者建立 AI 應用，如聊天機器人、自動化推薦系統。
   
2. **結合 AWS Lambda、API Gateway，打造 AI 服務**：
   - 可將 Bedrock AI 模型與 AWS Lambda 結合，讓應用程式能夠動態回應使用者需求。
   - API Gateway 可讓外部應用透過 REST API 方式存取 AI 功能。
   
3. **微調與強化模型**：
   - 若有較高的技術需求，開發者可以透過 **Fine-tuning** 方式，根據企業內部數據微調 AI 行為，讓 AI 輸出更貼合業務需求。
   - 
## 📚 參考文件來源

- [AWS Bedrock 官方文件](https://docs.aws.amazon.com/bedrock/latest/userguide/what-is-bedrock.html)
- [Amazon Titan 官方介紹](https://aws.amazon.com/titan/)
- [AWS AI 服務官方指南](https://aws.amazon.com/machine-learning/)
