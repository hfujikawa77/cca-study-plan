# Vocabulary Tracker

| Word / Phrase | Meaning | Example / Why it matters | Status |
|---|---|---|---|
| orchestration | | | new |
| escalation | | | new |
| handoff | | | new |
| reliability | | | new |
| least privilege | | | new |
| single responsibility | | | new |
| structured output | | | new |
| schema validation | | | new |
| error isolation | 1つの失敗が他に波及しない設計 | sub-agent の失敗が coordinator 全体を止めない | new |
| audit trail | 誰が何をしたかの追跡記録 | 高リスク操作（払い戻し等）の監査に必要 | new |
| reversibility | 操作を元に戻せること | アカウント削除より停止を選ぶ設計判断 | new |
| idempotency | 何度実行しても同じ結果になること | retry 時に副作用が重複しない設計 | new |
| retry with feedback | 失敗時に「何が違ったか」を伝えて再試行させること | structured output の validation 失敗後に使う | new |
| cross-cutting concern | 複数のコンポーネントに横断する関心事 | Domain 5 は全シナリオに関係する横断的基盤 | new |
| coordinator | 複数の sub-agent を管理・指示するエージェント | multi-agent system のオーケストレーター役 | new |
| explainability | エージェントの動作・判断が説明できること | tool を分割すると何をしているか追いやすい | new |
