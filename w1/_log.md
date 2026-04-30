# Log

## [2026-04-30] ingest | view_taskmanagement「タスク管理を眺める」
- 出典: `raw/view_taskmanagement.md`
- 要約ページ: [「タスク管理を眺める」](source_view_taskmanagement.md)
- 新規作成した概念ページ:
    - [タスク](task.md) / [オルタスク](altask.md)
    - [タスク管理](task_management.md) / [狭義と広義](narrow_broad.md) / [MCA](mca.md) / [タスク管理の公理](axioms.md)
    - [3P 分類](3p.md) / [プロジェクトタスク管理](project_task_management.md) / [パートナータスク管理](partner_task_management.md) / [個人タスク管理](personal_task_management.md)
    - [模索](exploration.md)

## [2026-04-30] migrate | 構造のフラット化
- w1 の運用ルール変更に伴い、`concepts/` と `sources/` を廃止しフラット構造に移行
- リンク記法を `[[basename]]` 形式から `[読みやすいテキスト](実ファイル.md)` 形式に変更
- `log.md` を `_log.md` にリネーム
- `sources/view_taskmanagement.md` を `source_view_taskmanagement.md` にリネーム

## [2026-04-30] migrate | frontmatter の削除
- 全ファイルから YAML frontmatter を削除（Obsidian 不使用方針のため）

## [2026-04-30] ingest | view_personal_taskmanagement「個人タスク管理を眺める」
- 出典: `raw/view_personal_taskmanagement.md`
- 要約ページ: [「個人タスク管理を眺める」](source_view_personal_taskmanagement.md)
- 新規作成した概念ページ:
    - [トレメント](trement.md)
    - [忘迷怠](boumeitai.md) / [調動脈](choudoumyaku.md) / [熱夢集](netsumushuu.md)
    - [動線](dousen.md) / [RSAF サイクル](rsaf.md)
    - [浅い/深いタスク管理](shallow_deep.md) / [アナログ/デジタル](analog_digital.md)
    - [戦略](strategies.md) / [スタンス](stances.md) / [盤外戦](bangaisen.md)

## [2026-05-01] ingest | project_taskmanagement「プロジェクトタスク管理」
- 出典: `raw/project_taskmanagement.md`
- 新規作成した概念ページ:
    - [3A](3a.md) / [Assign](assign.md) / [Adjust](adjust.md) / [Alternate](alternate.md) / [Alternate モデル](alternate_model.md)
    - [ビューの種類](views.md)
    - [シャドータスク](shadow_task.md) / [キャパシティ](capacity.md) / [バッファとスラック](buffer_slack.md)
    - [5 つの管理対象](management_targets.md) / [進捗の管理](progress_management.md) / [質の管理](quality_management.md) / [プロセスの管理](process_management.md) / [リソースの管理](resource_management.md) / [専有の管理](property_management.md)
    - [脱拘束](unbinding.md)

## [2026-05-01] ingest | partner_taskmanagement「パートナータスク管理」
- 出典: `raw/partner_taskmanagement.md`
- 新規作成した概念ページ:
    - [ファミリア・デバフ](familiar_debuff.md) / [3C](3c.md) / [トーカビリティ](talkability.md)
- [盤外戦](bangaisen.md) — 章 2 の仮置きから本格定義に書き直し、6 つのテクニックを追記

## [2026-05-01] ingest | strategy「タスク管理の戦略」
- 出典: `raw/strategy.md`（803 行）
- 新規作成した概念ページ:
    - 9 戦略: [Dailer](dailer.md) / [Calendarer](calendarer.md) / [Slotter](slotter.md) / [Issueist](issueist.md) / [Topician](topician.md) / [Richild](richild.md) / [Monolith](monolith.md) / [Robot](robot.md) / [Tracker](tracker.md) / [Inboxer](inboxer.md)
    - 前提知識: [物タスク](object_task.md) / [ルーチンタスク](routine_task.md)
    - 重要な造語: [オプラン](oplan.md) / [アクティブレイジー](active_lazy.md)
- [戦略](strategies.md) — 章 2 の概要から、9 戦略の各論ハブに昇格

## [2026-05-01] ingest | stance「タスク管理のスタンス」
- 出典: `raw/stance.md`（438 行）
- 要約ページ: [「タスク管理のスタンス」](source_stance.md)
- 新規作成した概念ページ:
    - 9 スタンス: [デリゲーター](delegator.md) / [スプリンター](sprinter.md) / [スキッパー](skipper.md) / [オートマトン](automaton.md) / [リジェクター](rejecter.md) / [フォーカシスト](focusist.md) / [スラキスト](slackist.md) / [コンテキストン](contexton.md) / [ミキサー](mixer.md)
    - 重要な造語: [メンタルロード](mental_load.md) / [フラティズム](flatism.md)
- 既存ページの更新:
    - [スタンス](stances.md) — 章 2 の概要から、9 スタンスの各論ハブに昇格
    - [盤外戦](bangaisen.md) — 主なスタイル冒頭に「[スラキスト](slackist.md) / [コンテキストン](contexton.md) / [ミキサー](mixer.md) がそれぞれ体現する」と追記
- メモ:
    - スタンス内の小さな名前付き概念（拒否ルール、リジェクターの 4T、オートマトンのパラドックス、エセコンテキストン、学生症候群、不可逆要素、退屈の第一/第二/第三形式、オールドバチェラー等）は親スタンスページのセクションに収めた
    - **Maximize Positives / Minimize Negatives** は inline 言及（[リジェクター](rejecter.md) / [フラティズム](flatism.md) で繋がっている）
    - **GTD の 2 分ルール / フロントローディング** は inline 言及。`ref.md` ingest 時に独立リンク化を検討
    - **暇と退屈の倫理学** は書籍参照、inline 言及のみ

## [2026-05-01] ingest | container「コンテナ」
- 出典: `raw/container.md`
- 要約ページ: [「コンテナ」](source_container.md)
- 新規作成した概念ページ:
    - [コンテナ](container.md) — オルタスク「入れ物」の本格定義
    - [コンテキストタグ](context_tag.md) — 文脈（Context）とは別概念
- 既存ページの更新:
    - [オルタスク](altask.md) — 入れ物の説明から [コンテナ](container.md) への参照を追記
- メモ:
    - 章内の名前付き概念（リッチコンテナ/プレインコンテナ、箱モデル/接続モデル、こうもり問題、コンテナのパピプペポ、コミュニケーション 1.0、4 Based）はすべて [コンテナ](container.md) 内のセクションに収めた
    - **PARA メソッド** / **PMBOK** / **GTD** / **HEY** / **Wrike** は inline 言及のみ
    - **Scrapbox** は Topician と本章の両方で言及。`ref.md` ingest 時にリンク化検討
    - chap3 = container / event / motto / memo / source（オルタスクの各論）の最初

## [2026-05-01] ingest | event「イベント」
- 出典: `raw/event.md`
- 要約ページ: [「イベント」](source_event.md)
- 新規作成した概念ページ:
    - [イベント](event.md) — オルタスク「予定」の本格定義
- 既存ページの更新:
    - [オルタスク](altask.md) — 「予定」の説明から [イベント](event.md) への参照を追記
- メモ:
    - 章内の小概念（割り込み、ミュートデイ、儀式、メリハリ制/明示的提案/ダミーイベント、グッドタイム/バッドタイム）はすべて [イベント](event.md) 内のセクションに収めた
    - **GitLab Coffee Chat / デスマーチ / タイムボックス** は inline 言及のみ
    - chap3 の 2 つ目（オルタスク各論）

## [2026-05-01] ingest | motto「モットー」
- 出典: `raw/motto.md`
- 要約ページ: [「モットー」](source_motto.md)
- 新規作成した概念ページ:
    - [モットー](motto.md) — オルタスク「ビジョン・理念・標語・心がけ」の本格定義
    - [アスリートとアプライア](athlete_applier.md) — タスク管理の 2 才能（独立ページ化、本書全体に関わる二分法のため）
- 既存ページの更新:
    - [オルタスク](altask.md) — 「ビジョン・理念・標語・心がけ」の説明から [モットー](motto.md) への参照を追記
- メモ:
    - 章内の概念（応用、格言問題、エモットー/イモットー、共感事項、漂白）は親ページ内のセクションに収めた
    - **異文化理解力** / **階層主義** / **OJT** は inline 言及のみ
    - chap3 の 3 つ目

## [2026-05-01] ingest | memo「メモ」
- 出典: `raw/memo.md`
- 要約ページ: [「メモ」](source_memo.md)
- 新規作成した概念ページ:
    - [メモ](memo.md) — オルタスク「メモ」の本格定義
- 既存ページの更新:
    - [オルタスク](altask.md) — 「メモ」の説明から [メモ](memo.md) への参照を追記
- メモ:
    - 章内の概念（メモのフロー、タイミングの壁/解読の壁、WRR Life、Act first Manage second、解釈と解読、もったいない精神）はすべて [メモ](memo.md) 内のセクションに収めた
    - **インボックスゼロ** / **NotebookLM** / **Claude** は inline 言及のみ
    - chap3 の 4 つ目

## [2026-05-01] ingest | source「タスクソース」
- 出典: `raw/source.md`（252 行）
- 要約ページ: [「タスクソース」](source_source.md)
- 新規作成した概念ページ:
    - [タスクソース](task_source.md) — タスクの源泉と 4 種類（目標 / 維持 / 連想 / 発想事項）
    - [発散と収束](divergent_convergent.md) — 動的な連想事項。本書全体に応用される技法
    - [SP 臨界点](sp_threshold.md) — ソースアプローチ → プランアプローチの切り替えポイント
- 既存ページの更新:
    - [オルタスク](altask.md) — タスクソースとの関連を追記
- メモ:
    - 章内の小概念（連想リスト/トリガーリスト、俯瞰のつくりこみ、俯瞰物、要約と蒸留、ソースアプローチ/プランアプローチの 4 戦略）はすべて親ページのセクションに収めた
    - **GTD のレビュー / PARA メソッド / オズボーンのチェックリスト / ストレングス・ファインダー / KJ 法 / ブレインストーミング** は inline 言及のみ
    - **探索的なあり方** は後章 [探索的タスク管理](exploratory.md) で詳述予定（task_source.md と source_source.md で予告）
    - chap3 完了 = container / event / motto / memo / source（オルタスクの各論）の最後
