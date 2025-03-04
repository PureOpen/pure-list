# PureOpen - ピュアオープンソースプロジェクトリスト

[![English](https://img.shields.io/badge/lang-English-blue.svg)](../README.md)
[![简体中文](https://img.shields.io/badge/lang-简体中文-red.svg)](README_zh-CN.md)
[![繁體中文](https://img.shields.io/badge/lang-繁體中文-orange.svg)](README_zh-TW.md)
[![日本語](https://img.shields.io/badge/lang-日本語-green.svg)](README_ja.md)
[![한국어](https://img.shields.io/badge/lang-한국어-brightgreen.svg)](README_ko.md)
[![Español](https://img.shields.io/badge/lang-Español-yellow.svg)](README_es.md)
[![Français](https://img.shields.io/badge/lang-Français-lightblue.svg)](README_fr.md)
[![Deutsch](https://img.shields.io/badge/lang-Deutsch-blueviolet.svg)](README_de.md)

## プロジェクト紹介

**PureOpen**は、真のオープンソースプロジェクトを維持・保護することに専念する組織です。**pure-list**プロジェクトを通じて、純粋なオープンソースの精神を守るプロジェクトを収集・推進し、開発者や貢献者の利益を保護し、オープンソース世界の完全性を守ります。

現在のオープンソース環境では、多くのプロジェクトが「オープンソース」の旗を掲げながら、実際には商業化への道を開き、開発者の熱意と貢献を企業成長の踏み台として利用しています。PureOpenは、真にオープンソースの精神に従うプロジェクトを特定し、推進することを目的とし、開発者とユーザーに信頼できる参考リストを提供します。

## 私たちの使命

1. **純粋なオープンソースプロジェクトのキュレーション**：オープンソースの精神を真に守るプロジェクトを厳選し、推進し、才能ある開発者の参加を促進します
2. **開発者と質の高いプロジェクトの接続**：開発者や起業家が様々な分野で最高のオープンソースソリューションを見つけるのを支援します
3. **オープンソース貢献の促進**：ユーザーが使用するプロジェクトに貢献することを奨励し、ポジティブなオープンソースエコシステムを形成します
4. **オープンソースの原則の維持**：最初から商業化を計画している「疑似オープンソース」プロジェクトを含めることを拒否し、オープンソース貢献者の権利を保護します
5. **中立性と客観性の維持**：政治的傾向を持つプロジェクトを拒否し、技術とオープンソースの精神の伝達に焦点を当てます

## このリストの使い方

このリストは技術分野などの多次元で分類されています。あなたは以下のことができます：
- 特定分野の高品質オープンソースプロジェクトを閲覧する
- 新興で有望なオープンソースツールやフレームワークを発見する
- 貢献する価値のあるプロジェクトを見つけ、オープンソースコミュニティ構築に参加する
- スタートアップやプロジェクト開発のための信頼できるオープンソースソリューションを見つける

## 貢献方法

pure-listへの貢献を歓迎します：
1. このリポジトリをフォークする
2. 基準を満たすと思われるオープンソースプロジェクトを追加する
3. プルリクエストを提出し、推薦するプロジェクトとその包含基準を満たす理由を詳細に説明する
4. 私たちのメンテナがあなたの提出物をレビューし、PureOpenの理念に合致していることを確認します

## プロジェクト包含基準

pure-listに含まれるためには、プロジェクトは以下の条件を満たす必要があります：

1. **明確なオープンソースライセンス**：認められたオープンソースライセンス（MIT、GPL、Apacheなど）を使用している
2. **コミュニティ主導**：単一の企業や個人によって管理されるのではなく、活発なコミュニティの貢献がある
3. **純粋なオープンソースの意図**：商業的なマーケティングツールとしてではなく、オープンソースを目的としてプロジェクトが設立された
4. **技術志向**：政治やイデオロギーではなく、技術的・機能的メリットに基づいて判断される
5. **持続可能な開発**：明確な貢献ガイドラインと長期的なメンテナンス計画がある

## お問い合わせ

ご提案やご質問がございましたら、以下の方法でお問い合わせください：
- GitHub Issues：[問題を提出する](https://github.com/PureOpen/pure-list/issues)
- Email：[連絡先メール]

---

# プロジェクト構造

## 1. 多言語サポート

世界中の開発者がpure-listを便利に使用できるよう、多言語サポートを提供しています：

```
/
├── README.md (英語メインドキュメント)
├── translations/
│   ├── README_zh-CN.md (簡体字中国語)
│   ├── README_zh-TW.md (繁体字中国語)
│   ├── README_ja.md (日本語)
│   ├── README_ko.md (韓国語)
│   ├── README_es.md (スペイン語)
│   ├── README_fr.md (フランス語)
│   ├── README_de.md (ドイツ語)
│   └── ... (その他の言語)
```

各言語バージョンには、完全なプロジェクト紹介、使用ガイド、貢献方法が含まれています。

## 2. プロジェクト収集構造

プロジェクトはドメインと技術スタックによって分類され、各プロジェクトのマークダウンファイルは以下のように構成されています：

```
/
├── categories/
│   ├── backend/
│   │   ├── frameworks.md
│   │   ├── databases.md
│   │   └── ...
│   ├── frontend/
│   │   ├── frameworks.md
│   │   ├── ui-libraries.md
│   │   └── ...
│   ├── devops/
│   ├── ai-ml/
│   ├── mobile/
│   ├── desktop/
│   ├── security/
│   └── ...
└── special-collections/
    ├── newcomers.md (初心者に適したプロジェクト)
    ├── high-impact.md (高影響力プロジェクト)
    ├── underrated.md (過小評価された質の高いプロジェクト)
    └── needs-contributors.md (貢献者を必要とするプロジェクト)
```

## 3. プロジェクトエントリテンプレート

各プロジェクトエントリには以下の情報が含まれます：

```markdown
### [プロジェクト名](プロジェクトGitHubリンク)

![Stars](https://img.shields.io/github/stars/ユーザー名/プロジェクト?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/ユーザー名/プロジェクト?style=flat)
![License](https://img.shields.io/github/license/ユーザー名/プロジェクト?style=flat)

**紹介**: プロジェクトの主な機能と目的を一文で説明

**ハイライト**:
- 特徴1
- 特徴2
- 特徴3

**オープンソースライセンス**: MIT/GPL/Apacheなど

**コミュニティ活動**: 高/中/低 (貢献者数、問題応答時間などに基づく)

**貢献者に適した**: 初心者/中級/上級

**関連リンク**:
- [ドキュメント](ドキュメントリンク)
- [貢献ガイドライン](貢献ガイドラインリンク)
- [コミュニティ/フォーラム](コミュニティリンク)

**推薦理由**: プロジェクトがPureOpenの理念に合致する理由とエコシステムにおけるユニークな価値の簡単な説明
```

## 4. レビュープロセス

含まれるプロジェクトの品質とPureOpenの理念との整合性を確保するために、厳格なレビュープロセスを確立しています：

1. **初期レビュー**：基本情報が完全であるか、プロジェクトが活発であるかを確認
2. **詳細評価**：プロジェクトのオープンソースの純粋性を評価（歴史、コミュニティ構造、意思決定の透明性など）
3. **コミュニティ投票**：議論のあるプロジェクトについては、コミュニティ投票が開かれる場合がある
4. **定期的な再レビュー**：含まれるプロジェクトは定期的に再レビューされ、包含基準を継続的に満たしていることを確認

## 5. コミュニティ構築

純粋なオープンソース哲学を促進するために、以下を行います：

1. **定期的な推薦**：月次/四半期ごとに新しく含まれた質の高いプロジェクトを推薦
2. **成功事例**：pure-listを通じて見つかった質の高いプロジェクトの成功事例を共有
3. **貢献者インセンティブ**：含まれるプロジェクトに重要な貢献をした開発者を認識
4. **オープンソース教育**：オープンソースコラボレーション、ライセンス選択などに関する教育リソースを提供