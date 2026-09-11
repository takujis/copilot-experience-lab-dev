# Copilot Experience Lab

Microsoft Copilot を**自分の仕事で試す**ための、日本語の体験コンテンツ集です。  
パートナーが、お客様向けのハンズオンやデモ、導入後の伴走支援にそのまま利用できるように構成しています。

- 1 体験あたり約 5〜30 分
- Copilot Chat、Outlook、Teams、Excel、Word、Researcher、Analyst、Agent Builder などを収録
- 参加者自身の業務データ、または架空企業のサンプルデータで実施可能

> [!IMPORTANT]
> 体験の本文は [`contents/`](./contents) にだけ置きます。  
> [`programs/`](./programs) は体験の順番と進行方法を定義し、本文を複製しません。

## まずどこを見るか

| 目的 | 開く場所 |
|---|---|
| 公開ページから体験を探す | [`index.md`](./index.md) — GitHub Pages のトップページ |
| 30 日間の導入・定着支援を行う | [Copilot in 30](./programs/copilot-in-30/README.md) |
| 現場担当者向けの 90 分ワークショップを行う | [SMB Guided Experience](./programs/smb-guided-experience/README.md) |
| 経営層向けの 60〜120 分ワークショップを行う | [CXO Experience](./programs/cxo-experience/README.md) |
| 体験を 1 件だけ試す | [SETUP-01](./contents/00-setup/SETUP-01_サインイン確認と安全なAI利用の土台づくり.md)から開始し、[`contents/`](./contents) で興味のある体験を選ぶ |
| サンプルデータを準備する | [レイクショア データ](./contents/assets/lakeshore-sample-data-ja/README.md) ／ [CXO データ](./contents/assets/cxo-data/README.md) |
| コンテンツを追加・修正する | [CONTRIBUTING.md](./CONTRIBUTING.md) |

## リポジトリ構成

```text
.
├── README.md                    # この案内
├── index.md                     # GitHub Pages のトップページ
├── CONTRIBUTING.md              # 追加・改訂ルール
├── _config.yml                  # GitHub Pages / Jekyll 設定
├── _includes/                   # GitHub Pages の共通 HTML
├── contents/                    # 体験コンテンツの本文
│   ├── 00-setup/                # 事前準備
│   ├── 01-copilot-chat/         # Copilot Chat
│   ├── 02-outlook-teams/        # Outlook / Teams
│   ├── 03-excel/                # Excel
│   ├── 04-word/                 # Word
│   ├── 05-powerpoint/           # PowerPoint（準備中）
│   ├── 06-researcher-analyst/   # Researcher / Analyst
│   ├── 07-agent-builder/        # Agent Builder
│   ├── 08-personas/             # 役割別コンテンツ / CXO
│   └── assets/                  # 画像、動画、サンプルデータ
└── programs/                    # 複数の体験を組み合わせた進行ガイド
    ├── copilot-in-30/           # 30 日間の伴走プログラム
    ├── smb-guided-experience/   # 現場担当者向けワークショップ
    ├── cxo-experience/          # 経営層向けワークショップ
    └── templates/               # 新規プログラムの雛形
```

## `contents/` — 体験コンテンツ

各 Markdown ファイルが 1 つの「体験」です。目的、必要な製品やデータ、操作手順、コピーして使えるプロンプト、振り返り、次の体験へのリンクを収録しています。

| ディレクトリ | 内容 | 件数 |
|---|---|---:|
| [`00-setup/`](./contents/00-setup) | サインイン確認、安全な AI 利用、データ準備 | 1 |
| [`01-copilot-chat/`](./contents/01-copilot-chat) | 情報整理、要約、比較、画像生成、日常業務への定着 | 20 |
| [`02-outlook-teams/`](./contents/02-outlook-teams) | メール、チャット、会議の準備・要約・フォローアップ | 6 |
| [`03-excel/`](./contents/03-excel) | 売上データの分析と施策立案 | 1 |
| [`04-word/`](./contents/04-word) | 文書の作成とレビュー | 2 |
| [`05-powerpoint/`](./contents/05-powerpoint) | PowerPoint の体験（準備中） | 0 |
| [`06-researcher-analyst/`](./contents/06-researcher-analyst) | 調査・分析タスクのエージェントへの委任 | 2 |
| [`07-agent-builder/`](./contents/07-agent-builder) | 繰り返し業務を行うエージェントの設計・作成 | 5 |
| [`08-personas/`](./contents/08-personas) | 経営層など、役割別の業務シナリオ | 10 |

体験はファイル名の先頭にある ID（`CHAT-01`、`MTG-01`、`CXO-01` など）で識別します。詳しい命名規則と必須フォーマットは [CONTRIBUTING.md](./CONTRIBUTING.md) を参照してください。

## `programs/` — 実施プログラム

プログラムは、既存の体験を対象者や時間に合わせて並べた**進行ガイド**です。

| プログラム | 対象 | 所要 | ゴール |
|---|---|---:|---|
| [Copilot in 30](./programs/copilot-in-30/README.md) | Microsoft 365 Copilot のトライアルを支援するパートナー | Day 0〜21 | 繰り返し業務を 1 つ Copilot に置き換え、導入判断の材料を残す |
| [SMB Guided Experience](./programs/smb-guided-experience/README.md) | SMB の現場担当者と実施パートナー | 約 90 分 | Chat から業務コンテキスト、調査・分析、Agent Builder までを一通り体験する |
| [CXO Experience](./programs/cxo-experience/README.md) | 中小企業の経営層と実施パートナー | 約 120 分（短縮版 60 分） | 自社で着手する AI 活用を 1 件決め、最初のエージェントにつなげる |
| [プログラム雛形](./programs/templates/README.md) | 新しい進行プログラムの作成者 | — | 体験を複製せず、対象者・順番・必須項目・運用方法を定義する |

`programs/copilot-in-30/` だけは用途別に 2 つの入口があります。

- [`README.md`](./programs/copilot-in-30/README.md)：パートナー・ファシリテーター向け進行ガイド
- [`index.md`](./programs/copilot-in-30/index.md)：参加者向けの GitHub Pages

## `contents/assets/` — 素材とサンプルデータ

| 配置先 | 内容 |
|---|---|
| `contents/assets/<体験ID>/` | 体験ページで使う画像、GIF、動画など |
| [`contents/assets/lakeshore-sample-data-ja/`](./contents/assets/lakeshore-sample-data-ja) | SMB Guided Experience 向けの架空企業「レイクショア」のデータ案内 |
| [`contents/assets/cxo-data/`](./contents/assets/cxo-data) | CXO Experience 向けの架空企業「株式会社みなとフーズ」のデータ一式 |

レイクショアの配布ファイルは [GitHub Releases](https://github.com/miookawa/copilot-experience-lab/releases/tag/lakeshore-sample-data-ja-v1.0.0) から取得します。CXO 用ファイルはリポジトリ内にあります。各データの準備方法と利用する体験は、それぞれの README に記載しています。

## パートナー向けの実施手順

1. **対象者とゴールを決める**  
   単発体験、30 日間の伴走、90 分の現場向け、60〜120 分の経営層向けから選びます。
2. **進行ガイドを確認する**  
   対応する `programs/<プログラム名>/README.md` で、必須の体験、順番、代替進行を確認します。
3. **利用環境を確認する**  
   職場アカウント、Microsoft 365 Copilot のライセンス、対象アプリ、Researcher / Analyst / Agent Builder の利用可否を確認します。
4. **データを準備する**  
   原則として参加者の業務データを使います。利用できない場合は `contents/assets/` の架空データへ切り替えます。
5. **体験を実施する**  
   各ページの `TRY — 手順` に沿って操作し、`REFLECT — 振り返り` で業務価値を確認します。
6. **次の行動を決める**  
   継続して使う業務、担当者、判定基準を具体化します。

## 実施前チェックリスト

- [ ] 参加者、所要時間、実施形式（ハンズオン／デモ）を決めた
- [ ] 参加者が職場アカウントでサインインできる
- [ ] 必要なライセンスとテナント設定を確認した
- [ ] 使用する体験と、利用できない場合の代替体験を決めた
- [ ] 業務データまたはサンプルデータを準備した
- [ ] OneDrive / SharePoint 上の必要なファイルを開ける
- [ ] 画面共有に機密情報や個人情報が映らない進行を決めた

> [!CAUTION]
> 参加者のメール、会議、チャット、ファイルを使う体験があります。機密情報、個人情報、人事・法務・財務情報、機微な顧客情報の取り扱いは、参加組織のポリシーに従ってください。Copilot の出力はうのみにせず、引用元や根拠を確認してください。

## コンテンツを追加・更新する

変更前に [CONTRIBUTING.md](./CONTRIBUTING.md) を確認してください。特に次の原則を守ります。

1. 体験の本文は `contents/` に 1 ファイルだけ置く
2. 画像や動画は `contents/assets/<体験ID>/` に置く
3. プログラムから体験を相対リンクで参照する
4. `programs/` に体験本文をコピーしない
5. ファイル名、体験 ID、ページタイトルの整合性を保つ
6. 機密情報や実在の顧客情報を含めない

GitHub Pages のトップに表示するカテゴリや注目コンテンツは [`index.md`](./index.md) の front matter で管理しています。通常、既存カテゴリへ体験を追加するだけなら、一覧カードは自動生成されます。

## 参考リンク

- [Copilot in 30 キット](https://aka.ms/Copilotin30Kit)
- [Copilot Success Planner](https://adoption.microsoft.com/copilot/success-planner)
- [M365 Copilot + Agents Guided Experience](https://aka.ms/CopilotBusinessGuidedExperience)
