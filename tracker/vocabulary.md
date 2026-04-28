# Vocabulary Tracker

| Word / Phrase | Meaning | Example / Why it matters | Status | Date |
|---|---|---|---|---|
| orchestration | 複数のエージェント・プロセスを調整・制御すること | coordinator が sub-agent を orchestrate する | learning | 2026-04-26 |
| escalation | 対応範囲を超えた問題を上位（人間や別エージェント）に引き継ぐこと | 高額案件を人間に回す設計 | learning | 2026-04-26 |
| handoff | タスクや文脈を別のエージェントや人間に引き継ぐこと | sub-agent から coordinator への結果返却・人間への引き継ぎ | learning | 2026-04-26 |
| reliability | | | new | 2026-04-26 |
| least privilege | | | new | 2026-04-26 |
| single responsibility | | | new | 2026-04-26 |
| structured output | | | new | 2026-04-26 |
| schema validation | | | new | 2026-04-26 |
| error isolation | 1つの失敗が他に波及しない設計 | sub-agent の失敗が coordinator 全体を止めない | new | 2026-04-26 |
| audit trail | 誰が何をしたかの追跡記録 | 高リスク操作（払い戻し等）の監査に必要 | new | 2026-04-26 |
| reversibility | 操作を元に戻せること | アカウント削除より停止を選ぶ設計判断 | new | 2026-04-26 |
| idempotency | 何度実行しても同じ結果になること | retry 時に副作用が重複しない設計 | new | 2026-04-26 |
| retry with feedback | 失敗時に「何が違ったか」を伝えて再試行させること | structured output の validation 失敗後に使う | new | 2026-04-26 |
| cross-cutting concern | 複数のコンポーネントに横断する関心事 | Domain 5 は全シナリオに関係する横断的基盤 | new | 2026-04-26 |
| coordinator | 複数の sub-agent を管理・指示するエージェント | multi-agent system のオーケストレーター役 | learning | 2026-04-26 |
| explainability | エージェントの動作・判断が説明できること | tool を分割すると何をしているか追いやすい | new | 2026-04-26 |
| delegation | タスクを他のエージェントや担当者に任せること | coordinator が sub-agent に責務を委譲する | learning | 2026-04-27 |
| parallelization | 複数の処理を同時に行うこと | 複数ソース調査を sub-agent で同時に実行する | learning | 2026-04-27 |
| failure surfacing | sub-agent の失敗を coordinator に見える形で伝えること | 失敗を握りつぶすと retry も escalation もできない | learning | 2026-04-27 |
| task decomposition | 複雑なタスクを処理可能な単位に分解すること | coordinator の核心スキル。専門化・並列化・失敗切り分けのため | learning | 2026-04-27 |
| tool boundary | エージェントが持つ tool の範囲・権限の境界 | 返金処理 tool は返金担当 sub-agent だけが持つべき | learning | 2026-04-27 |
