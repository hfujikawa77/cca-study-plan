# Question Log

| Date | Domain | Topic | Why I Missed It | Correct Principle | Follow-up |
|---|---|---|---|---|---|
| 2026-04-26 | D4 | Structured data extraction の核心 | フォーマット設計で止めた。validation + retry with feedback が抜けた | schema → validate → retry with feedback の3ステップで安定出力を設計する | schema → validate → retry を手書きで図示する |
| 2026-04-26 | D1/D5 | Domain 1 と Domain 5 の境界 | 「複数エージェント」だけを D1 の判断基準にした。handoff も D1 のトリガー | D1 のトリガー：複数エージェント・handoff・human escalation | 8シナリオを D1 トリガー3条件で再分類する |
| 2026-04-26 | D2 | Agentic tools における tool の定義 | tool = アプリと誤解。tool = エージェントが呼び出す function と理解できていなかった | tool = function call（read_file, execute_code など）。broad tool は least privilege 違反 | 自分の Claude Code 操作を tool名(引数)→返り値 の形で3つ書く |
