# 🧩 GenAI Prompt Template — 10段階構造テンプレ集

「平文を整列せよ。」<br>
コンテキストエンジニアリングを最短で学び、実務で使うためのプロンプトテンプレート集。<br>
GPT / Claude / Gemini / Cursor 向けの即利用版を /templates/ に収録。

## 🚀 Quick Start

1️⃣ このリポジトリを使う<br>
	•	Forkするか、右上の 「Use this template」 をクリックして複製。<br>
	•	目的に応じて /templates/ 内のテンプレートを選ぶ。<br>

```
/templates/
├── gpt-10step-template.md       # ChatGPT用・完全構造化版
├── claude-10step-template.md    # Claude用・出力制御版
├── gemini-10step-template.md    # Gemini用・完全構造化版
└── cursor-10step-template.mdc   # Cursor用・STRUCTUREモード
```

## 2️⃣ 使い方（GPT例）

1. ChatGPTを開く
2. 「10段階テンプレをロード」として以下を貼る
3. 平文を下に入力する

※推奨モデル: GPT-4 / GPT-5
※ClaudeやCursorでは、該当ファイルをそのまま読み込めばOK。

## 🧠 10段階プロンプト構造とは？

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

この10段階を踏むことで、<br>
「プロンプト＝指示」から「プロンプト＝設計」へと進化する。

## 📖 使い方

このテンプレート集を効果的にご活用いただくために、以下の手順をご案内いたします。

### ステップ1: テンプレートの選択

ご利用になるAIツールに応じて、適切なテンプレートをお選びください。

- **ChatGPTをご利用の場合**: `templates/gpt-10step-template.md` をご使用ください
- **Claudeをご利用の場合**: `templates/claude-10step-template.md` をご使用ください
- **Geminiをご利用の場合**: `templates/gemini-10step-template.md` をご使用ください
- **Cursor IDEをご利用の場合**: `templates/cursor-10step-template.mdc` をご使用ください

### ステップ2: テンプレートの読み込み

選択したテンプレートファイルの内容を、ご利用のAIツールに読み込んでください。

- **ChatGPT / Claude / Gemini**: テンプレートの内容をコピーして、チャット画面に貼り付けてください
- **Cursor IDE**: `@` 記号を使用して、テンプレートファイルを直接参照することができます

### ステップ3: 入力テキストの準備

構造化したいテキストやデータを準備してください。以下のような形式に対応しています。

- 会議の議事録やメモ
- 要件定義や仕様書の草案
- アイデアや思考のメモ
- その他、整理したい任意のテキスト

### ステップ4: プロンプトの実行

テンプレートに従って、準備したテキストを入力し、AIに処理を依頼してください。テンプレート内の各段階（Goal、Context、Constraintsなど）に沿って、必要な情報を補完していただくことで、より精度の高い結果が得られます。

### ステップ5: 結果の確認と改善

AIから返された構造化された結果をご確認ください。必要に応じて、以下の点を調整することで、より良い結果を得ることができます。

- **Context（前提・状況）**: より詳細な背景情報を追加する
- **Constraints（制約条件）**: 出力形式や制限事項を明確にする
- **Rubric（評価基準）**: 品質の基準を具体的に指定する

### よくある質問

**Q: どのテンプレートを使えばよいですか？**<br>
A: ご利用のAIツールに合わせて選択してください。各テンプレートは、それぞれのツールの特性に最適化されています。

**Q: テンプレートをカスタマイズしてもよいですか？**<br>
A: はい、もちろんです。ご自身の用途に合わせて、自由にカスタマイズしていただけます。

**Q: 複数のテンプレートを組み合わせて使えますか？**<br>
A: はい、可能です。異なるテンプレートの良い部分を組み合わせることで、より効果的なプロンプトを作成できます。

## 💡 各テンプレの特徴

| テンプレート | 主な用途 | 特徴 |
| --- | --- | --- |
| gpt-10step-template.md | ChatGPT用 | フル構造・最も再現性高い |
| gemini-10step-template.md | Gemini用 | フル構造・最も再現性高い |
| claude-10step-template.md | Claude用 | 出力暴走防止・トークン制限あり |
| cursor-10step-template.mdc | Cursor | STRUCTUREモード対応、自動整列可能 |

## 🧰 LICENSE

このテンプレートは [MIT License](LICENSE)￼ で提供されています。
商用利用・改変・再配布すべて自由。クレジット表記のみ残してください。

## ✨ Author

AK1RA<br>
	•	[GitHub](https://github.com/ak1ra)￼<br>
	•	[Notion Portfolio](https://www.notion.com/ja/@ak1ra)￼

⸻

🔁 更新履歴
	•	2025-12-10：/templates/ 追加（Gemini）
	•	2025-11-05：/templates/ 追加（GPT / Claude / Cursor）
	•	2025-10-24：初期版公開（10段階プロンプトテンプレ構造）

⸻

🔥 鬼教官コメント

Forkよりも「Use this template」で使え。<br>
コピーした瞬間から、君の文脈が整列を始める。

⸻

✅ ファイル配置（最終確認）

```
genai-10step-prompt-framework/
│
├── README.md              ← このファイル
├── LICENSE
│
└── templates/
    ├── gpt-10step-template.md
    ├── claude-10step-template.md
    └──cursor-10step-template.mdc
```

⸻
