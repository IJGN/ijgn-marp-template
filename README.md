# IJGN Marp Template

## Marp

- [Marp: Markdown Presentation Ecosystem](https://marp.app/)

## Set up

### プラグイン

[Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) プラグインを、VSCodeに追加しておきます。

プロジェクトに `.vscode/settings.json` を追加。

```json
{
  "markdown.marp.themes": [
    "https://marp.ijgn.jp/themes/ijgn.css",
    "./themes/ijgn.css"
  ]
}
```

## Usage

```text
---
marp: true
theme: ijgn
footer: '&copy; IJGN GROUP Inc.<span class="confidential">Confidential</span>'
paginate: true
---
```
