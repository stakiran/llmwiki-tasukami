# プロジェクトタスク管理

仕事におけるチームなど、複数人で行うタスク管理。[3P 分類](3p.md) の Project に対応する。

## 本質: 3A

- [Assign / アサイン](assign.md) — 人にタスクを割り当てる
- [Adjust / 調整](adjust.md) — タスクの属性値を変える
- [Alternate / 俯瞰と注視](alternate.md) — 全体俯瞰と特定タスクの注視を行き来する

詳細は [3A](3a.md) を参照。

## 俯瞰と注視の実現度合い

[Alternate モデル](alternate_model.md) の 4 段階で表現される:

1. N-Micro（注視のみ／脳内）
2. 1-Macro（俯瞰のみ／管理票）
3. 1-Macro N-Micro（タスク管理ツール常用）— **キャズム** が存在
4. N-Macro N-Micro（ビューカスタマイズ／API）

第 3 段階はクリエイティブ職以外には到達が難しく、長い啓蒙と経営者の協力が要る。

## 俯瞰のための [ビュー](views.md)

リスト / テーブル / ボード / チャート / ネットワーク / センテンスの 6 種。当面はテーブルが無難。

## ツール例
- Trello
- Asana / ClickUp / monday.com
- Redmine / JIRA / GitHub Issues
- Microsoft 365 / Notion

## フレームワーク例
- WBS / ガントチャート
- PERT / CPM
- カンバン
- バーンダウンチャート

近年は **連携・自動化（Automation）・カスタマイズ** が高度化している。

## ものすごく単純に言えば「ただの見える化」

要は皆の方向性と認識を揃えるために、タスクという情報を外に出して原本にする。

> 見える化する以上の能力は無い

- 結局口頭やチャットで催促が要る
- 更新の形骸化、聞きまわるあるある
- 高頻度の会議で補うあるある
- 中長期がおざなりになりがち

## 隠れた負荷: [シャドータスク](shadow_task.md)

ツール上に計上されない隠れタスクが膨大に存在する。**シャドーエフェクト** が生産性を蝕む。対処は [キャパシティベース](capacity.md)、[バッファとスラック](buffer_slack.md)、ダイレクトシャドーのタスク化。

## 実際は周辺も管理してしまっている: [5 つの管理対象](management_targets.md)

| 対象 | 概要 |
| --- | --- |
| [進捗](progress_management.md) | ゴールへの進行具合 |
| [質](quality_management.md) | 状態の良さや安定性 |
| [プロセス](process_management.md) | 順序やルールへの踏襲 |
| [リソース](resource_management.md) | 時間やお金 |
| [専有](property_management.md) | 拘束＝時間と場所の所有 |

愚直に捉えると **タスク管理 ＝ 進捗管理** だが、実際は質・プロセス・リソース・専有まで管理されがち。**管理も過ぎれば毒**。

専有は [脱拘束](unbinding.md)（非同期コミュニケーション、QWIC、Communication Injection）で軽減する。

## 使われる層

主に現場で使われる。中間管理職以上はツールではなく自分の脳内＋ミーティングで何とかしがち。

## 総括

> やると決まったもの（あるいは決めたこと）を確実にこなすために、やることを外部化すること、およびそれをメンテナンスすること

## 関連
- [3P 分類](3p.md) / [タスク管理](task_management.md)
- [パートナータスク管理](partner_task_management.md) / [個人タスク管理](personal_task_management.md)
- [タスク管理の公理](axioms.md) — ツールの公理

## 出典
- [「タスク管理を眺める」](source_view_taskmanagement.md)
- [「プロジェクトタスク管理」](source_project_taskmanagement.md)
