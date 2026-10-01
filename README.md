# Wedding Pages Sample v2

GitHub Pages 用の3ページ構成サンプルです。

- `index.html` : TOPページ
- `profile.html` : プロフィール
- `album.html` : アルバム
- `.nojekyll`

TOPページからProfile/Albumへ遷移できます。

個別ゲスト表示の例:
- `?guest=father`
- `?guest=mother`
- `?guest=test`

Profile/Albumへ移動しても `guest` パラメータを引き継ぎます。

## GitHubへの反映
既存の `WebPageTest` リポジトリのルートに、このZIPの中身をアップロードしてください。
既存の `index.html` は上書きでOKです。

## 写真を追加する場合
`images` フォルダを作り、`photo01.jpg` などを配置します。
その後 `album.html` のプレースホルダーを、例えば次のように置き換えます。

```html
<div class="photo"><img src="images/photo01.jpg" alt="思い出の写真"></div>
```
