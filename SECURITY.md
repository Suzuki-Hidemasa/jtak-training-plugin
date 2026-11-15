# セキュリティ方針 / Security Policy

**TRAINING USE ONLY / 訓練用**

[日本語](#日本語) | [English](#english)

---

## 日本語

このプラグインは、ミルシムやタクティカルトレーニングで使う訓練用のものです。実際の作戦、実弾射撃、実際の航空機の統制には使えません。

### 脆弱性の報告先

脆弱性を見つけたときは、公開の Issue や Discussions には書かず、GitHub の非公開の報告機能で知らせてください。

1. このリポジトリの「Security」タブを開きます。
2. 「Report a vulnerability」を選びます。
3. 内容を書いて送ります。

次の URL からも開けます。

https://github.com/Suzuki-Hidemasa/jtak-training-plugin/security/advisories/new

メールや SNS での受け付けはしていません。

### 対象

最新のリリース（現在は v0.1.0、プレリリース）と `main` ブランチが対象です。

次のようなものは、報告してください。

- LRF の入力（ATAK 標準の連携、UDP、手入力）の扱いに欠陥があり、プラグインや ATAK が落ちる、または端末のデータを不正に読み書きされるもの
- シナリオの取り込みや、テキスト・PDF の書き出しの欠陥で、同じ問題が起きるもの
- 配布している APK の署名やビルドの問題
- リポジトリに入っていてはいけない情報（認証情報、実在の場所、個人の情報）

次のものは対象外です。

- ATAK 本体の問題（ATAK の開発元に知らせてください）
- 兵器の表の値が、実際の諸元と違うこと（表の値は訓練用のサンプルです）

### 報告に書いてほしいこと

- 問題の内容と、起きると何が困るか
- 再現の手順
- ATAK と JTAK のバージョン
- 端末の機種と Android のバージョン

実在の場所、個人の情報、認証情報は書かないでください。

### 報告のあと

このプロジェクトは個人で保守しています。対応の期限は約束できません。受け付けたら返信します。修正のあとに、報告してくれた方の同意を得て、詳しい内容を公開します。

---

## English

This plugin is for training use in milsim and tactical training. It must not be used for real operations, live fire, or control of real aircraft.

### How to report a vulnerability

If you find a vulnerability, do not post it in a public Issue or Discussion. Use GitHub's private vulnerability reporting.

1. Open the "Security" tab of this repository.
2. Select "Report a vulnerability".
3. Fill in the details and submit.

You can also open the form from this URL.

https://github.com/Suzuki-Hidemasa/jtak-training-plugin/security/advisories/new

We do not accept reports by email or social media.

### Scope

The latest release (currently v0.1.0, a prerelease) and the `main` branch are covered.

Please report problems such as these.

- A flaw in how LRF input (the ATAK built-in link, UDP, manual entry) is handled that crashes the plugin or ATAK, or lets device data be read or written improperly
- A flaw in scenario import or text/PDF export that causes the same kind of problem
- A problem with the signing or build of the distributed APK
- Information that should not be in the repository (credentials, real locations, personal data)

These are out of scope.

- Problems in ATAK itself (please report them to the ATAK developer)
- Weapon table values that differ from real specifications (the values are training samples)

### What to include

- What the problem is and what harm it can cause
- Steps to reproduce it
- The ATAK and JTAK versions
- The device model and Android version

Do not include real locations, personal data, or credentials.

### After you report

This project is maintained by an individual, so we cannot promise a response deadline. We will reply when we receive your report. After a fix, we will publish the details with the reporter's agreement.
