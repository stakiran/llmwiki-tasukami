# Log

## [2026-04-30] ingest | view_taskmanagement「タスク管理を眺める」
- 出典: `raw/view_taskmanagement.md`
- 要約ページ: [「タスク管理を眺める」](source_view_taskmanagement.md)
- 新規作成した概念ページ:
    - [タスク](task.md) / [オルタスク](altask.md)
    - [タスク管理](task_management.md) / [狭義と広義](narrow_broad.md) / [MCA](mca.md) / [タスク管理の公理](axioms.md)
    - [3P 分類](3p.md) / [プロジェクトタスク管理](project_task_management.md) / [パートナータスク管理](partner_task_management.md) / [個人タスク管理](personal_task_management.md)
    - [模索](exploration.md)
- メモ:
    - 第 1 章として土台概念が一気に出る章。以降の章で各概念ページが厚くなっていく想定
    - オルタスク（予定、入れ物、ビジョン、メモ、習慣など）は後の章で詳述されるとの記述あり。詳細は届いていない

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
- 既存ページの更新:
    - [個人タスク管理](personal_task_management.md) — 章の各観点へのクロスリンクを追加
    - [オルタスク](altask.md) — 繰り返しの力でまわす [戦略](strategies.md) との関連を追加
    - [狭義と広義](narrow_broad.md) — [調動脈](choudoumyaku.md) を広義の例として追加
- メモ:
    - 文脈（Context）は重要かつ奥深い概念として後の章へ持ち越し（[choudoumyaku.md](choudoumyaku.md) 内に予告のみ）
    - 盤外戦の詳細はパートナータスク管理の章で扱われる予定。現時点ではこの章での記述から要約ページを作成
    - ポモドーロ・テクニック、タスクシュート、アイビー・リー・メソッド、時間管理マトリクス、マニャーナの法則、タイムボックス、Habitica などの固有名詞は inline 言及のみ。`ref.md` を ingest した際にリンクを張る想定

## [2026-05-01] ingest | project_taskmanagement「プロジェクトタスク管理」
- 出典: `raw/project_taskmanagement.md`
- 要約ページ: [「プロジェクトタスク管理」](source_project_taskmanagement.md)
- 新規作成した概念ページ:
    - [3A](3a.md) / [Assign](assign.md) / [Adjust](adjust.md) / [Alternate](alternate.md) / [Alternate モデル](alternate_model.md)
    - [ビューの種類](views.md)
    - [シャドータスク](shadow_task.md) / [キャパシティ](capacity.md) / [バッファとスラック](buffer_slack.md)
    - [5 つの管理対象](management_targets.md) / [進捗の管理](progress_management.md) / [質の管理](quality_management.md) / [プロセスの管理](process_management.md) / [リソースの管理](resource_management.md) / [専有の管理](property_management.md)
    - [脱拘束](unbinding.md)
- 既存ページの更新:
    - [プロジェクトタスク管理](project_task_management.md) — 章全体のハブとして大幅増補
    - [パートナータスク管理](partner_task_management.md) — 注視機能の洗練について本書での言及を追記
    - [個人タスク管理](personal_task_management.md) — [脱拘束](unbinding.md) との同義性を追記
    - [スタンス](stances.md) — Automation の詳細が [ビューの種類](views.md) 余談に展開されている旨を追記
- メモ:
    - 678 行の大ボリューム章。プロジェクトタスク管理の体系的整理が一通り完了
    - **反応的状況**（Reactive Situation）は [Adjust](adjust.md) 内のセクションに収めた（独立ページにせず）
    - **強い人** はシャドータスク文脈で繰り返し登場。[shadow_task.md](shadow_task.md) と [capacity.md](capacity.md) の両方で取り上げ
    - **ネガティブ・ケイパビリティ**、**プロセス原理主義**、**グッドハートの法則** は inline 言及のみ
    - **文芸的タスク管理** は後の章（literate.md）で扱われる予定。views.md の「ネットワーク」「センテンス」で言及
