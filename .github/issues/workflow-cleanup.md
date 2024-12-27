---
name: 'workflow-files-deletion'
title: '🧹 GitHub Actionsワークフローファイルの削除'
labels: 'cleanup'
assignees: ''
---

# 概要
プロジェクトの整理の一環として、不要となったGitHub Actionsワークフローファイル `.github/workflows/create-issue.yaml` および `.github/workflows/setup-labels.yml` を削除する必要があります。

## タスク
- [ ] `.github/workflows/create-issue.yaml` と `.github/workflows/setup-labels.yml` の現在の使用状況を確認する。
- [ ] これらのファイルがもはやプロジェクトにとって不要であることを確認する。
- [ ] **削除前に、これらのファイルに関連するワークフローが正しくラベル付けされていることを確認する。**
- [ ] 上記のファイルをリポジトリから削除する。
- [ ] ワークフローの削除に伴うドキュメントの更新が必要な場合は、それを行う。

## 目的
不要なワークフローファイルを削除することで、リポジトリの管理を簡素化し、プロジェクトの構成を明確にします。

## 備考
- 削除作業を行う前に、関連するチームメンバーやプロジェクトマネージャーと協議し、削除の承認を得てください。
- 削除するワークフローファイルに代わる新しいワークフローが必要な場合は、その開発についても計画を立ててください。