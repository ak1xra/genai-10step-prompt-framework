⸻

# 🧩 GenAI Prompt Template — 10段階構造テンプレ集

「平文を整列せよ。」
コンテキストエンジニアリングを最短で学び、実務で使うためのプロンプトテンプレート集。
GPT / Claude / Cursor / Notion 向けの即利用版を /templates/ に収録。

⸻

## 🚀 Quick Start

1️⃣ このリポジトリを使う
	•	Forkするか、右上の 「Use this template」 をクリックして複製。
	•	目的に応じて /templates/ 内のテンプレートを選ぶ。

```
/templates/
├── gpt-10step-template.md       # ChatGPT用・完全構造化版
├── claude-10step-template.md    # Claude用・出力制御版
├── cursor-10step-template.mdc   # Cursor用・STRUCTUREモード
└── notion-10step-template.md    # Notion用・単発整列版
```

⸻

## 2️⃣ 使い方（GPT例）

1. ChatGPTを開く
2. 「10段階テンプレをロード」として以下を貼る
3. 平文を下に入力する

※推奨モデル: GPT-4 / GPT-5
※ClaudeやCursorでは、該当ファイルをそのまま読み込めばOK。

⸻

## 🧠 10段階プロンプト構造とは？

```markdown
| 段階 | 意味 | 目的 |
| --- | --- | --- |
| 1 | Goal | 最終目的を定義する |
| 2 | Context | 前提・状況を明示 |
| 3 | Constraints | 制約条件を整理 |
| 4 | Input | 対象テキストやデータを指定 |
| 5 | Process | Why→How→What整列 |
| 6 | Format | 出力形式を指定 |
| 7 | Rubric | 評価基準を定義 |
| 8 | Output | 構造化結果を出力 |
| 9 | Feedback | 改善点を抽出 |
| 10 | Next Action | 実行タスクを提示 |
```

この10段階を踏むことで、
「プロンプト＝指示」から「プロンプト＝設計」へと進化する。

⸻

## 💡 各テンプレの特徴

```markdown
| テンプレート | 主な用途 | 特徴 |
| --- | --- | --- |
| gpt-10step-template.md | ChatGPT用 | フル構造・最も再現性高い |
| claude-10step-template.md | Claude用 | 出力暴走防止・トークン制限あり |
| cursor-10step-template.mdc | Cursor | STRUCTUREモード対応、自動整列可能 |
| notion-10step-template.md | Notion AI | 単発整列・メモ整理用（10段階簡略版） |
```

⸻

## 🧰 LICENSE

このテンプレートは MIT License￼ で提供されています。
商用利用・改変・再配布すべて自由。クレジット表記のみ残してください。

⸻

## ✨ Author

Akira Hayakawa (早川 明良)
	•	[GitHub](https://github.com/ak1ra)￼
	•	[Notion Portfolio](https://www.notion.com/ja/@ak1ra)￼

⸻

🔁 更新履歴
	•	2025-11-05：/templates/ 追加（GPT / Claude / Cursor / Notion 向け）
	•	2025-10-24：初期版公開（10段階プロンプトテンプレ構造）

⸻

🔥 鬼教官コメント

Forkよりも「Use this template」で使え。
コピーした瞬間から、君の文脈が整列を始める。

⸻

✅ ファイル配置（最終確認）

```
GenAI-Prompt-Template/
│
├── README.md              ← このファイル
├── LICENSE
│
└── templates/
    ├── gpt-10step-template.md
    ├── claude-10step-template.md
    ├── cursor-10step-template.mdc
    └── notion-10step-template.md
```

⸻
