# Architecture Decision Records

- 状態: Active
- 最終確認日: 2026-09-29

ADR は、後から見ても理由が必要な長期判断を残す。現在の状態は `docs/architecture.md` やプロダクト文書に反映し、ADR だけを読まないと現状が分からない構成にはしない。

## ADR が必要な判断

- 技術スタック、永続化、同期、認証、外部サービスの採否
- ドメイン境界やデータ所有権の変更
- セキュリティ、プライバシー、可用性に関する方針
- 将来の変更コストが高く、複数案に明確なトレードオフがある判断

小さく可逆な実装詳細や、一時的な作業手順には ADR を作らない。

## 命名と状態

ファイル名は `NNNN-short-kebab-title.md` とする。番号は連番。

- **Proposed**: 検討中
- **Accepted**: 採用済み
- **Superseded**: 後続 ADR に置換済み
- **Rejected**: 検討したが不採用

## テンプレート

```markdown
# ADR-NNNN: タイトル

- Status: Proposed
- Date: YYYY-MM-DD
- Deciders: ...

## Context

何を決める必要があり、どの制約があるか。

## Decision

何を選ぶか。規範的な内容を明確に書く。

## Alternatives considered

- 案: 採用しなかった理由

## Consequences

- Positive: ...
- Negative: ...
- Follow-up: ...
```

## Index

- [ADR-0001: MVP をレスポンシブ Web アプリ／PWA として提供する](0001-responsive-web-pwa.md) — Accepted
