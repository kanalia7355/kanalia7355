# 金糸雀 / kanalia7355

Pythonを中心に、身近な課題を解決するツールや、研究・実験を支援する仕組みを開発しています。  
Webアプリ、Discord Bot、画像処理、AIエージェントを活用した開発に取り組んでいます。研究室では、画像処理・最適化を扱っています。

## 主なプロジェクト

### [給与計算カレンダー](https://github.com/kanalia7355/salary-calender)

自分の勤務・給与管理のために開発しているWebアプリです。  
勤務情報から給与や交通費を計算し、支払元ごとの条件に応じた振込予定を管理します。勤務月と振込予定月を分けた集計や、実振込額との比較に対応しています。

**使用技術：** TypeScript / React / Vite / Zustand / Supabase

### [Agent Room](https://github.com/kanalia7355/AgentPost)

CLI型AIエージェントの活動を、作業ディレクトリごとの「部屋」として可視化するWindowsアプリです。  
ローカルやSSH接続先のプロセス、Git、tmuxなどから観測できる情報をまとめ、作業状況を確認できます。

**使用技術：** Rust / Tauri 2 / Git / SSH

### [RLkit — Research Loop Kit](https://github.com/kanalia7355/RLkit)

AIエージェントによる実験・検証・分析・報告・次の提案を進めるためのシステムです。  
研究方針の整理、実験の状態保存、中断・再開、実行履歴の記録を扱います。実装済みの機能、検証範囲、今後の拡張計画はリポジトリに記載しています。

**使用技術：** Python / SQLite / CLI型AIエージェント

## その他のプロジェクト

| プロジェクト | 内容 |
|---|---|
| [Computer Vision Lab](https://github.com/kanalia7355/cvlab) | カメラ映像に画像処理を適用し、処理の違いを比較する展示 |
| [Gesture Controller](https://github.com/kanalia7355/gesgame) | 手の動きで操作するゲーム |
| [Invisible Mirror](https://github.com/kanalia7355/mirror) | 人物領域を背景に置き換える画像合成の展示 |
| [Human vs AI](https://github.com/kanalia7355/hvai) | 人間と画像分類モデルの回答を見比べるゲーム |
| [exRAG](https://github.com/kanalia7355/exRAG) | コードや文書を取り込み、質問できるローカルRAG |

## 技術・開発環境

- **Python**：Bot開発、データ処理、研究・実験支援
- **TypeScript / React**：Webアプリ、展示用インターフェース
- **Rust / Tauri**：Windows向けデスクトップアプリ
- **SQLite / PostgreSQL / Supabase**：データ保存、状態管理、認証
- **OpenCV / MediaPipe**：画像処理、人物・手の認識
- **Git / GitHub、Codex / Claude Code**：バージョン管理、AIエージェントを活用した開発

## GitHub Stats

[![GitHub Stats](https://github-stats-extended.vercel.app/api?username=kanalia7355&hide=stars&hide_rank=true&show_icons=true&locale=ja&include_all_commits=false&commits_year=2026)](https://github.com/kanalia7355)
[![Top Languages](https://github-stats-extended.vercel.app/api/top-langs?username=kanalia7355&layout=compact&langs_count=6)](https://github.com/kanalia7355?tab=repositories)

コミット数は2026年分、使用言語は公開リポジトリの構成です。非公開の研究や開発は含みません。
