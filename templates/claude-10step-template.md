> ⚠️ Claude用プロンプトテンプレート  
> 出力上限: 1500 tokens  
> 形式: Markdown  
> 出力は各Stepごとに区切って短文で生成せよ。


**目的**  
大規模言語モデル (LLM) から安定的かつ高品質な応答を得るための再利用可能テンプレート。Persona → Context → Task → Instructions → Output → Constraints → Examples → Evaluation の 8-段構成。

### Step 9-10. Feedback & Next Action
- 生成結果に対する改善提案（最大3点）
- 次に取るべきアクション（1文）

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
