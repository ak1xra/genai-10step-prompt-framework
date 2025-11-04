> ✅ GPT専用テンプレート  
> 使用対象: ChatGPT (GPT-4 / GPT-5 / API)  
> 目的: コンテキストエンジニアリング10段階整列のベース
# 高度なプロンプト設計テンプレート (エキスパート改訂版)


**目的**  
大規模言語モデル (LLM) から安定的かつ高品質な応答を得るための再利用可能テンプレート。Persona → Context → Task → Instructions → Output → Constraints → Examples → Evaluation の 8-段構成。


---
## 0. 共通ルール
- **変数命名**: すべて `snake_case` で統一 (例: `user_question`)。
- **タグ記法**: 変数は `<Input name="...">`、外部リソースは `<Resource name="...">` で宣言。
- **思考非公開**: `<thinking>` セクションは *system-only* とし、ユーザーに開示しない。


---
## 1. ペルソナ (Persona)
AI に与える役割・専門性・語調を明示。
```markdown
あなたは **Acme Dynamics 社** の顧客サポート AI です。敬語で、正確かつ簡潔に回答してください。
