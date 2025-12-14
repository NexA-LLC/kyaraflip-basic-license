# AGENTS.md

KyaraFlip 基本ライセンス（KFL）の正本リポジトリ向けのルールだよ。

## 正本（言語）

- **日本語版（`v*/license.ja.md`）が正本**（拘束力のある本文）
- 英語版（`v*/license.en.md`）は参考訳
- 齟齬がある場合は **日本語版を優先**する

## バージョニング / 不変性

- リリース済み（タグ/Release で固定した）バージョンのディレクトリは **不変**（編集禁止、roll-forward only）
- 変更は `v1.0-draft/` に入れて、確定したら新しい `vX.Y.../` を追加して進める

## manifest の更新

- `v*/` 配下の本文を更新した場合は、同ディレクトリの `manifest.json` の `sha256` も更新する

## リポジトリのライセンス境界

- `LICENSE`（Apache-2.0）は、ツール/スキーマ等（ライセンス本文以外）に適用
- `v*/` 配下のライセンス本文には適用されない（契約文書として別扱い）

## 参照のさせ方

- 他リポからは `git submodule` ではなく **tag** / **commit hash** で参照する
- Canonical URL: https://github.com/NexA-LLC/kyaraflip-basic-license
