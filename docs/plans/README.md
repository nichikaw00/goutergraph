# 実行計画

- 状態: Active
- 最終確認日: 2026-09-29

複数工程、複数セッション、または移行を伴う作業では、`docs/plans/active/YYYY-MM-DD-short-title.md` を正本として進捗を残す。1 回で終わる小さな変更には作成しない。

完了後は最終結果と検証結果を記録し、ファイルを `docs/plans/completed/` へ移す。計画の途中で判明した恒久的な知識は、プロダクト文書、アーキテクチャ、ADR のいずれかへ移す。

## 必須要素

```markdown
# 計画名

- Status: Active
- Started: YYYY-MM-DD
- Related requirements: PR-...

## Outcome

ユーザーから見た完了状態。

## Scope

- In: ...
- Out: ...

## Constraints and decisions

既知の制約。未決定事項は決定済みのように書かない。

## Milestones

- [ ] 確認可能な成果 1
- [ ] 確認可能な成果 2

## Progress log

- YYYY-MM-DD: 実施内容、判明事項、次の一手

## Verification

- コマンドまたは手動確認: 期待結果

## Completion note

実際に達成したこと、残件、関連 ADR・文書へのリンク。
```

チェックリストだけでなく、再開した別のエージェントが「現在地」「次の一手」「検証方法」を判断できる内容にする。
