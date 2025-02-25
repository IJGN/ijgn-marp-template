# Marp Template

## Set up

### プラグイン
`Marp for VS Code`プラグインを、VSCodeに追加しておきます。
> <a href="https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode" target="_blank">Marp for VS Code</a>


### CSS反映
今回はMarpの既存テーマでなく、自作スタイルシートで制作。<br />
自作したCSSを適用するためにはVSCodeの`settings.json`に追記が必要で、下記の参考資料での順序で設定を行う。<br />
実際に設定する相対パスは以下の`css`である。

```
./assets/css/style.css
```

#### 参考資料
> <a href="" target="_blank">Marpで独自CSSを使う方法</a>
