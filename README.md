# KyaraFlip 基本ライセンス（KFL）

このリポジトリは **KyaraFlip 基本ライセンス（KFL）** の正本（canonical）です。  
英語版 README は `README.en.md` を参照してください。

- **安定版（不変）**: `v0.9r/`
- **ドラフト（変更あり）**: `v1.0-draft/`

## 言語の正本（日本語 / English）

- `v*/license.ja.md` が正本（拘束力のある本文）
- `v*/license.en.md` は参考訳（便利のために提供）
- 齟齬がある場合は **日本語版が優先**します

## リポジトリのライセンスと本文の境界

- リポジトリのツール/スキーマ等（ライセンス本文以外）は **Apache-2.0**（`LICENSE`）
- `v*/` 配下の **ライセンス本文** には、リポジトリの Apache-2.0 は適用されません（契約文書として別扱い）

## バージョニング方針

- 版を Release/tag で固定したら、そのディレクトリは **不変**（編集禁止、roll-forward only）
- 作業中の変更は `v1.0-draft/` に集約し、確定したら新しい版ディレクトリへ昇格する

## フォルダ構成

```
v0.9r/                 # 不変の版
  license.ja.md
  license.en.md
  manifest.json
v1.0-draft/            # ドラフト（まだ効力なし）
  license.ja.md
  license.en.md
  rrr-spec.md
  metadata-schema.json
  revshare-schemas/
    kf-1.0-default.json
```

## 他リポからの参照方法

`git submodule` は使わず、**tag** または **commit hash** で参照してください。

- 例: `KFL v0.9r (commit <sha>)`
- Canonical URL: https://github.com/NexA-LLC/kyaraflip-basic-license
