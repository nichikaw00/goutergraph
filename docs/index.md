# ドキュメント索引

- 状態: Active
- 最終確認日: 2026-09-29

このディレクトリは、プロダクトと実装に関するリポジトリ内の正本である。入口は短く保ち、詳細は目的別に分ける。

## 読み方

| 目的 | 読む文書 | 状態 |
| --- | --- | --- |
| プロダクトの目的を理解する | [product/brief.md](product/brief.md) | Active |
| 実装対象と期待動作を確認する | [product/requirements.md](product/requirements.md) | Draft |
| 用語とデータの境界を理解する | [product/domain-model.md](product/domain-model.md) | Draft |
| 判断待ちの論点を確認する | [product/open-questions.md](product/open-questions.md) | Active |
| 技術構成と制約を確認する | [architecture.md](architecture.md) | Placeholder |
| 長期的な決定理由を確認する | [decisions/README.md](decisions/README.md) | Active |
| 複数工程の作業を引き継ぐ | [plans/README.md](plans/README.md) | Active |
| 元の探索内容を確認する | [references/product-discovery-2026-09-26.md](references/product-discovery-2026-09-26.md) | Historical |

## 状態の意味

- **Active**: 現在の正本。変更と同時に更新する。
- **Draft**: 方向性は有効だが、未決定事項を含む。確定部分と候補を区別する。
- **Placeholder**: 必要な判断項目だけを示す。内容を推測で埋めない。
- **Historical**: 出典・経緯。現在の仕様を決める根拠として単独では使わない。
- **Superseded**: 後継文書へのリンクだけを残し、新規判断には使わない。

## 保守ルール

- 同じ事実の正本を複数作らず、他文書からはリンクする。
- 実装から自動生成できる情報は手書きで複製しない。
- 文書には現在形で事実を書く。時系列の履歴は ADR、実行計画、Git に置く。
- 文書を追加・移動・廃止したら、この索引と参照リンクを同じ変更で更新する。
- 大きな機能ごとの仕様が必要になった時点で `docs/product/specs/` を作る。先回りして空の仕様書を増やさない。
