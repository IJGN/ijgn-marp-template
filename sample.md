---
marp: true
theme: ijgn
footer: '&copy; IJGN GROUP Inc.'
paginate: true
---
<!--
_class: hero
_footer: ''
_paginate: false
-->
# マークアップ勉強会

ver2.0

---
<!--
_class: default
-->
## 文字装飾

- ふつう
- *イタリック*
- **強調**
- ~~打ち消し~~
- [リンク](https://ijgn.jp)

### 見出し 3

テキスト

> 引用

---
<!--
_class: default
-->
## 画像

![w:400](https://storage.googleapis.com/studio-design-asset-files/projects/VGOKvryjWn/s-2400x621_v-frms_webp_695b6ef8-230d-4486-8102-79e8de042ca8_small.webp)

## テーブル

| 項目     | 進捗率 | 前回比 |
|:-------- | ------:| ------:|
| タスク A |    75% |   +05% |
| タスク B |    50% |   +50% |
| （補足） |      - |      - |
| タスク C |    20% |   +20% |

---
<!--
_class: default
-->
## コード

```jsx
function Video({ video }) {
  return (
    <div>
      <Thumbnail video={video} />
      <a href={video.url}>
        <h3>{video.title}</h3>
        <p>{video.description}</p>
      </a>
      <LikeButton video={video} />
    </div>
  );
}
```

---
<!--
_class: last
_footer: ''
_paginate: false
-->
