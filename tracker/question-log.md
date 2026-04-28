# Question Log

| Date | Domain | Topic | Why I Missed It | Correct Principle | Follow-up |
|---|---|---|---|---|---|
| 2026-04-26 | D4 | Structured data extraction の核心 | フォーマット設計で止めた。validation + retry with feedback が抜けた | schema → validate → retry with feedback の3ステップで安定出力を設計する | schema → validate → retry を手書きで図示する |
| 2026-04-26 | D1/D5 | Domain 1 と Domain 5 の境界 | 「複数エージェント」だけを D1 の判断基準にした。handoff も D1 のトリガー | D1 のトリガー：複数エージェント・handoff・human escalation | 8シナリオを D1 トリガー3条件で再分類する |
| 2026-04-26 | D2 | Agentic tools における tool の定義 | tool = アプリと誤解。tool = エージェントが呼び出す function と理解できていなかった | tool = function call（read_file, execute_code など）。broad tool は least privilege 違反 | 自分の Claude Code 操作を tool名(引数)→返り値 の形で3つ書く |
| 2026-04-27 | D1 | task decomposition の目的（why） | 「分割してサブエージェントに渡すため」と手段を答えた | 目的：複雑な問題を専門化・並列化・失敗切り分けが可能な単位に整理するため | 「なぜ分割するのか」を1文で言えるよう練習する |
| 2026-04-27 | D1 | ハンドオフの最小情報 | 入力情報と出力フォーマットのみ回答。担当範囲・制約条件が抜けた | 5要素：目的・担当範囲・利用可能tool・出力フォーマット・制約条件 | 5要素をセットで暗記する |
| 2026-04-27 | D1 | sub-agent の escalation 判断 | sub-agent が自分で escalation を判断するとした | sub-agent は結果/失敗を coordinator に返す → coordinator が escalation を判断する | coordinator と sub-agent の責務境界を図で整理する |
