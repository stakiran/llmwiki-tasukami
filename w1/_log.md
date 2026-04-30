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

## [2026-05-01] ingest | dousen_and_remind「動線とリマインド」
- 出典: `raw/dousen_and_remind.md`（311 行）
- 要約ページ: [「動線とリマインド」](source_dousen_and_remind.md)
- 新規作成した概念ページ:
    - [リマインド](remind.md) — リマインダーの種類と戦略
- 既存ページの更新:
    - [動線](dousen.md) — 章 2 で予告した本格定義に大幅増補（ハブ/ジョイント、ネグレクテッド/ロスト、動線のデザイン、動線リマインド、RSAF 段階導入）
- メモ:
    - 章内の小概念（動線リマインド、ネグレクテッド、ロスト、ハブ/ジョイント、動線のデザイン、強度、選定→親近→RSAF の段階、オンデマンド戦略/定期戦略、5 種のリマインダー）はすべて親ページのセクションに収めた
    - **アクティブリマインド / トラップリマインド / ロケーションリマインド / ヒューマンリマインド / 雰囲気リマインド** は [remind.md](remind.md) 内のセクションで扱い独立ページにせず
    - chap4 の 1 つ目（chap4 = dousen_and_remind / habit / context / warp / furikaeri / attributes、計 6 章）

## [2026-05-01] ingest | habit「習慣」
- 出典: `raw/habit.md`（282 行）
- 要約ページ: [「習慣」](source_habit.md)
- 新規作成した概念ページ:
    - [習慣](habit.md) — オルタスク「習慣・日課」の本格定義
    - [ハビットエンジニアリング](habit_engineering.md) — GSAAD ループ + 悪い習慣減らし + 捨て身
- 既存ページの更新:
    - [オルタスク](altask.md) — 「習慣・日課」の説明から [習慣](habit.md) への参照を追記。これで 5 つすべてのオルタスクが本格定義ページにリンク済
- メモ:
    - 章内の小概念（GSAAD ループ、行動パラメーター、着手ベース、ハビットスタッキング、IF-THEN プランニング、定着/ハビチュエーション、撤収、妨害/排除/撹乱）はすべて [ハビットエンジニアリング](habit_engineering.md) 内のセクションに収めた
    - **習慣の 3 種類**（良い/悪い/微妙）は [habit.md](habit.md) 内
    - **「人間が変わる方法は 3 つ」**（時間配分・住む場所・付き合う人）は inline 言及
    - chap4 の 2 つ目

## [2026-05-01] ingest | context「コンテキスト」
- 出典: `raw/context.md`（409 行）
- 要約ページ: [「コンテキスト」](source_context.md)
- 新規作成した概念ページ:
    - [コンテキスト](context.md) — 文脈の本格定義。章 2 [調動脈](choudoumyaku.md) で持ち越されていた概念。5 種類（タスク/セルフ/ツール/トリガー/ロード）
    - [ロードコンテキスト](load_context.md) — コンテキストスイッチング・モデル + スプリント/マラソン + 土地勘
- 既存ページの更新:
    - [調動脈](choudoumyaku.md) — 「文脈は後の章で詳述」の予告を [コンテキスト](context.md) への正式リンクに置き換え
- メモ:
    - 章内の小概念（動的/静的、文脈理解猶予、現場のコンテキスト、5W1H、ツールーロール、コンテキスト四天王、オーバーヒート/オーバーウォント/オーバーマスト、ニュートラル、4 原則、ニア、歩きづらさ）はすべて親ページのセクションに収めた
    - **異文化理解力 / ストレングス・ファインダー / ビッグファイブ / Miro / ネガティブ・ケイパビリティ** は inline 言及のみ
    - chap4 の 3 つ目

## [2026-05-01] ingest | warp「割り込みと脱線」
- 出典: `raw/warp.md`（298 行）
- 要約ページ: [「割り込みと脱線」](source_warp.md)
- 新規作成した概念ページ:
    - [ワープ](warp.md) — 割り込み・脱線・SWAP マトリックス・4 パターン
    - [Explicit Attention](explicit_attention.md) — Passive Strong の対処（書きながら注意を明示）
    - [リズムリマインド](rhythm_remind.md) — Passive Strong の対処（生活リズムからのツッコミ）
- メモ:
    - 章内の小概念（割り込み/脱線、攻略派/防衛派、強い/弱い後回し、対処/防止、アタック/エスケープ/ガード、4 パターン詳細、シークレット・シチュエーション、木こりのジレンマ）はすべて親ページのセクションに収めた
    - **左ききのエレン / 道は開ける / サーカディアンリズム** は inline 言及のみ
    - chap4 の 4 つ目（残り: furikaeri / attributes）

## [2026-05-01] ingest | furikaeri「振り返り」
- 出典: `raw/furikaeri.md`（399 行）
- 要約ページ: [「振り返り」](source_furikaeri.md)
- 新規作成した概念ページ:
    - [振り返り](furikaeri.md) — PROC、DWMY ヒエラルキー、4R マトリックス、KAP（知る/進む/守る）、設計やり方、タスクデット
- メモ:
    - 章内の概念（PROC、DWMY ヒエラルキー、4R マトリックス、KAP、Enum and Assign、振り返りアワー、Diary Based DWMY、5 分振り返りんぐ、もくもく振り返り会、タスクデット、動的/静的なヒント、MSCW）はすべて [振り返り](furikaeri.md) 内のセクションに収めた
    - **GTD のレビュー / KPT / YWT / mad sad glad / リーンコーヒー / マリオカート / テディベア効果** は inline 言及のみ
    - chap4 の 5 つ目（残り: attributes）

## [2026-05-01] ingest | attributes「タスクの属性」
- 出典: `raw/attributes.md`（476 行、リファレンス章）
- 要約ページ: [「タスクの属性」](source_attributes.md)
- 新規作成した概念ページ:
    - [タスクの属性](attributes.md) — 3A（Attribute/Arrow/Attachment）+ 関係の 3P（Parent-Child/Point/Pre-Post）+ 9 系統 25 種類前後の属性リファレンス
- メモ:
    - 25+ の各属性は単独ページ化せず、リファレンス用途として 1 つの大きな [タスクの属性](attributes.md) に集約
    - **重要な注意**: タスク管理には 2 つの異なる「3A」がある。本章の **Attribute/Arrow/Attachment**（タスク構成）と、[3a.md](3a.md) で扱う **Assign/Adjust/Alternate**（プロジェクトタスク管理の本質）。同名異概念
    - 章内の概念（属性のジレンマ、ツールのパラドックス、ルーチンタスク設置方式 3 つ、キャンセルタスク、貢献者属性のジレンマ、Manual Listup）はすべて [attributes.md](attributes.md) 内のセクションに収めた
    - chap4 完了 = dousen_and_remind / habit / context / warp / furikaeri / attributes（6 章）

## [2026-05-01] ingest | plaintext「プレーンテキストによるタスク管理」
- 出典: `raw/plaintext.md`（839 行）
- 要約ページ: [「プレーンテキストによるタスク管理」](source_plaintext.md)
- 新規作成した概念ページ:
    - [プレーンテキスト](plain_text.md) — 媒体の仕様（行・文字・保存単位・カーソル・デジタル特有）+ 5 つの道具（IME / エディタ / 形式記法 / 情報管理 / ヘルパー）
    - [PTTM](pttm.md) — プレーンテキストタスク管理。タスクリスト + 属性の運用、6 設計原則、扱わないもの、設計概念
- 既存ページの更新:
    - [オルタスク](altask.md) — PTTM では原則扱わない旨を関連に追記
    - [ルーチンタスク](routine_task.md) — PTTM では扱わない旨を関連に追記
    - [Monolith](monolith.md) — 「後の章で扱う予定」を [PTTM](pttm.md) への正式リンクに置換、関連に PTTM / プレーンテキストを追加
    - [Dailer](dailer.md) — PTTM のデイリータスクリスト推奨を関連に追記
    - [メモ](memo.md) — PTTM ファイルに直接書ける旨を関連に追記
- メモ:
    - 粒度判断: warp/furikaeri/attributes パターンに倣い、章固有の小概念は親ページに集約
    - 「5 つの道具」は単一の名前を持った概念ではないため、独立ページ化せず [プレーンテキスト](plain_text.md) のセクションに収める（context/load_context の関係に近い独立化に留める）
    - 章内の独自用語（**管理的安全性 / 3 秒の壁 / 曖昧な日付感 / 管理範囲 / 動線化 / フォーマット統一**）はすべて [PTTM](pttm.md) のセクション化
    - **VSCode / 秀丸 / SAKURA Editor / メモ帳 / mi / CotEditor / Markdown / HTML / JSON / Text Expansion / Gyazo Pro / PowerToys / todo.txt / ワークインライフ / ワークアズライフ** は inline 言及のみ
    - 先人の実践例 8 件はリンクとして [PTTM](pttm.md) 内に残した（章内コンテンツとして価値が高いため）
    - chap5 の 1 つ目（chap5 = plaintext / literate / exploratory / exploratory2 / ref、計 5 章）

## [2026-05-01] ingest | literate「文芸的タスク管理」
- 出典: `raw/literate.md`（489 行）
- 要約ページ: [「文芸的タスク管理」](source_literate.md)
- 新規作成した概念ページ:
    - [ネットワーク型ノートツール](network_note.md) — リンクでノートを繋ぐパラダイム。トピック指向、第二の脳、無限キャンバス比較、アウトライナーとの違い
    - [LTM](ltm.md) — 文芸的タスク管理本体。ホーム 4 種 / メモタスク文脈の 3 種 / エリアとマーク / アンカバード / 文脈のつくりかた / ライティングスタック / 切り出し / 微修正とエイリアス / アイキャッチとエキサイトメント
- 既存ページの更新:
    - [PTTM](pttm.md) — 関連に LTM を追加（PTTM のダイアリーベースは LTM 未満）
    - [オルタスク](altask.md) / [ルーチンタスク](routine_task.md) — LTM でもアンカバード扱い、を関連に追記
    - [メモ](memo.md) — LTM の 3 種類の情報の一つ、を関連に追記
    - [コンテキストン](contexton.md) — 文脈重視のタスク管理として LTM を関連に追記
    - [Topician](topician.md) — 仮置きの「後の章 literate.md」を [LTM](ltm.md) と [ネットワーク型ノートツール](network_note.md) への正式リンクに置換
- メモ:
    - 粒度判断: plaintext と同じ「媒体 vs 実践」分割（[ネットワーク型ノートツール](network_note.md) ↔ [LTM](ltm.md)）。plain_text ↔ pttm の構造に揃える
    - 章固有の小概念（**ホーム / ライティングスタック / 切り出し / 微修正とエイリアス / アイキャッチ / エキサイトメント / アンカバード / タスクビュー / タスクノート / エリアとマーク / トランク / 日付ノート / ホームノート / ホームビュー**）はすべて [LTM](ltm.md) のセクションに収める（warp/furikaeri/attributes パターン）
    - **ダイアリーベース / プロジェクトベース / ネットワークベース** の 3 スタイルも [LTM](ltm.md) 内のセクション
    - **イメージスタック** はライティングスタックの対比として `ltm.md` 内に収める
    - **Scrapbox / Obsidian / Roam Research / Logseq / WorkFlowy / Dynalist / Miro / Jupyter Notebook / hown / Embark** は inline 言及のみ
    - 文芸的プログラミングは [LTM](ltm.md) のルーツ節で軽く触れるのみ
    - chap5 の 2 つ目（残り: exploratory / exploratory2 / ref）

## [2026-05-01] ingest | exploratory「探索的タスク管理」
- 出典: `raw/exploratory.md`（802 行）
- 要約ページ: [「探索的タスク管理」](source_exploratory.md)
- 新規作成した概念ページ:
    - [ETM](etm.md) — 探索的タスク管理本体。No ABCD、メリット/目的/適用、指向的アプローチとの対比、情報単位（ゴール/カード/トピック/ブロック）、育て方（広げる/詰める/導く、要約と蒸留、ブレイクスルー、ダシ）、ワークフロー 3 ステップ、動的 ETM
    - [ETM の 4 つの管理](etm_management.md) — ロード（一桁の原則）/ ターゲット（3T モデル、当事者、単一当事者の原則、ブースター）/ リソース（管理 2.0、ミニマイザー vs マキシマイザー、ネガティブ因子）/ コンテキスト（コンテキストメンテナンス、コンテキスト駆動）
- 既存ページの更新:
    - [LTM](ltm.md) — 関連に「ETM は LTM の発展形」を追記
    - [SP 臨界点](sp_threshold.md) — 関連に ETM を追記（探索 → 指向のハイブリッド構造が同じ）
    - [コンテキストン](contexton.md) — 関連に ETM を追記（No ABCD で文脈を育てる発展形）
- メモ:
    - 粒度判断: ETM は階層的・全体的な体系で、3T モデル / 管理 2.0 など独立性の高い名前付き概念がある。本体 + 管理で 2 ページに分割（context/load_context、habit/habit_engineering の 2 分割パターン）
    - 章固有の小概念（**No ABCD / ゴール / カード / ブロック / 要約と蒸留 / ブレイクスルー / ダシにする / 探索期間 / 探索時間 / ミュートデイ / ミュートウィーク / 動的 ETM / 探索モード / 指向モード**）はすべて [ETM](etm.md) のセクション
    - **3T モデル / 当事者 / 単一当事者の原則 / 助言者 / ブースター / ロードキャパシティ / 当事者キャパシティ / 一桁の原則 / 管理 2.0 / 理想状態 / ミニマイザー / マキシマイザー / コンテキストメンテナンス / コンテキスト駆動** はすべて [ETM の 4 つの管理](etm_management.md) のセクション
    - **指向的（Directional）アプローチ** はレトロニムとして etm.md 内で扱う
    - **ティール組織 / Engineering Effectiveness / KJ 法 / GTD の収集ステップ / Tak. のシェイク / リーンスタートアップ / アジャイル開発** は inline 言及のみ
    - exploratory2 は探索 part5 の分量都合の分離、別途 ingest 予定（block_writing / etm_tips を新規作成、etm.md にヒント集参照を追記）
    - chap5 の 3 つ目（残り: exploratory2 / ref）

## [2026-05-01] ingest | exploratory2「探索的タスク管理（ヒント集）」
- 出典: `raw/exploratory2.md`（831 行）
- 要約ページ: [「探索的タスク管理（ヒント集）」](source_exploratory2.md)
- 新規作成した概念ページ:
    - [ブロックライティング](block_writing.md) — CBS（Consideration Breakdown Structure）+ サマリー駆動 + ブロックライティング本体（ABCD ブロック + サマリー + 検討 + 用語 + 参考情報 + 文脈）+ レターのカスタマイズ
    - [ETM のヒント集](etm_tips.md) — スクイーズアウト / 個人と協調の線引き（パーソナルスペース、パブリックスペース、表札）/ 個と和のバランス（興味ドリブン、スルー許容、オタク注意報、明示的な否定、役割）/ 便利なトピック（日付、メンション、ポスト、サルベージ、ステーション）
- 既存ページの更新:
    - [ETM](etm.md) — 概要表に有限化（スクイーズアウト）行を追加、関連にブロックライティング・ヒント集を追加
    - [ETM の 4 つの管理](etm_management.md) — 関連にブロックライティング・ヒント集を追加
- メモ:
    - exploratory2 は exploratory part5 の分量都合の分離だが、内容量が多く独立性のあるテクニック群（ブロックライティング、パーソナルスペース）を含むので 2 ページに分割
    - 章固有の小概念（**スクイーズアウト / トピックは個人でつくる / パーソナルスペース 4 レイヤー / パブリックスペース / 表札 / 興味ドリブン / 興味を引く / スルーを許容する / オタク注意報 / 捲し立て / 明示的な否定 / ウェイト / 役割 / 動的な役割 / ロールプレイ / 日付トピック / メンショントピック / ポストトピック / サルベージトピック / ステーショントピック**）はすべて [etm_tips.md](etm_tips.md) のセクション
    - **CBS / サマリー駆動 / ブロックレター / ABCD ブロック / 検討ブロック / 用語ブロック / 参考情報ブロック / 文脈ブロック / サイクル / 下から上に書く** はすべて [block_writing.md](block_writing.md) のセクション
    - **ストレングスファインダー / MBTI / WOM / オズボーンのチェックリスト / SCAMPER / Miro / Cosense** は inline 言及のみ
    - block_writing.md 内の cx 文脈ブロックは [ETM の 4 つの管理](etm_management.md) のコンテキスト駆動の実装にあたるため相互参照を仕込んだ
    - chap5 の 4 つ目（残り: ref）
