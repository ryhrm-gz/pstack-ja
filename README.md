# pstack-ja

pstackを日本語向けに最適化したCursorプラグインです。

- 元のpstack: [0.15.2](https://github.com/cursor/plugins/tree/e31650eea443aaea1e84cc15d88c13f40080b275/pstack)
- pstack-ja: **0.1.0**

## 導入する

公式の`pstack`はオフにしてから入れてください。`poteto-mode`などのスキル名が同じなので、同時に有効にすると衝突します。`/add-plugin`での導入は推奨しません。入れた時点のcommitに固定されることがあります。

```bash
mkdir -p ~/.cursor/plugins/local
rsync -a --delete --exclude .git /path/to/pstack-ja/ ~/.cursor/plugins/local/pstack-ja/
```

使い方は元の [pstack guide](https://github.com/cursor/plugins/blob/e31650eea443aaea1e84cc15d88c13f40080b275/pstack/docs/guide/README.md) を見てください。

## 日本語向けに最適化したスキル

| スキル                                                 | 対応内容                                 |
| ------------------------------------------------------ | ---------------------------------------- |
| [poteto-mode](skills/poteto-mode/SKILL.md)             | 日本語の依頼解釈、作業報告、TODO、PR本文 |
| [unslop](skills/unslop/SKILL.md)                       | 自然で簡潔な日本語への推敲               |
| [technical-writing](skills/technical-writing/SKILL.md) | 日本語の技術文書の書き方                 |
| [teach](skills/teach/SKILL.md)                         | 専門用語を保った分かりやすい説明         |
| [bro](skills/bro/SKILL.md)                             | 平易な日本語への言い換え                 |
| [how](skills/how/SKILL.md)                             | 仕組みの説明と委譲先の日本語出力         |
| [why](skills/why/SKILL.md)                             | 根拠・確信度を保った日本語の調査報告     |

原作者: Lauren Tan · [MIT License](LICENSE)
