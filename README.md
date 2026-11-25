# .github

このアカウントの repo に共通の既定ファイルを置く repo です。

自前の `.github/ISSUE_TEMPLATE/` を持たない repo の「New issue」には、ここの Issue テンプレートが既定で出ます。

| 型 | ファイル | 使う時 |
|---|---|---|
| 機能・改善 | `.github/ISSUE_TEMPLATE/feature.md` | 新しい機能・改善・マイルストーン |
| 不具合 | `.github/ISSUE_TEMPLATE/bug.md` | 期待と違う動き(再現手順・期待・実際・影響) |
| 調査・研究 | `.github/ISSUE_TEMPLATE/research.md` | 問い・測り方・採否の決まりを先に固定する調査 |
| 本人の作業 | `.github/ISSUE_TEMPLATE/human.md` | 認証・支払い・画面の操作など、本人の操作が要る作業 |

どの型も、目的・背景・範囲・進め方・完成の定義(確かめ方つき)・やらないこと・根拠の欄を持ちます。
閉じてよいかは「完成の定義」の項目がすべて確かめられたかで判断します。

仕組みは GitHub の公式文書 [Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) のとおりです。
