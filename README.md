# CNN Fear & Greed Index 戦略検証

**[サイトを見る → https://hk201003.github.io/fear-greed-backtest/](https://hk201003.github.io/fear-greed-backtest/)**

「恐怖で買い、強欲で売れ」は本当か？ 15年分のデータで検証した結果をまとめています。

## レポート

- [Part 1: バックテスト再検証](https://hk201003.github.io/fear-greed-backtest/backtest.html) — 記事の主張を独自データで再現検証
- [Part 2: レバレッジ戦略](https://hk201003.github.io/fear-greed-backtest/leverage.html) — 勝率の高いゾーンにレバをかけたらどうなるか

## 主要な発見

- 記事の数値は93%一致（ほぼ正確）
- ただしベンチマーク比較が欠如 — SPYを21日持てばPF 1.9
- 恐怖ゾーンでのレバは最悪手（3xで CAGR -1.4%）
- 強欲ゾーンでのレバが正解（2x+1xで Sharpe 1.04）
