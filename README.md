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
> <a href="https://worklifefun.net/marp-own-css/#:~:text=uncover-,Marp%E3%81%A7%E7%8B%AC%E8%87%AACSS%E3%82%92%E4%BD%BF%E3%81%86%E6%96%B9%E6%B3%95,-3%E3%81%A4%E3%81%AE" target="_blank">Marpで独自CSSを使う方法</a>
