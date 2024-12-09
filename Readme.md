# SVG Vertical Text Helper
入力された文字列から、縦書きテキスト用SVGを生成するWebアプリ  
(Kritaの縦書きテキストを手作業で書くことに辟易したため突貫で作成したものを少し整備)

## 機能
- 以下のパラメータの変更が可能です
  * 背景色 (bg)
    + HTML側で変更しているため、出力SVGの背景は常に透過状態になります
  * 文字色 (fill)
  * フォントサイズ (fontsize)
  * 行間 (linespacing)
  * 強制改行文字数 (linefeed)
    + 。と、と」と』は改行されません
  * フォント (font)
    + 「Century, Noto Serif CJK JP」のようにカンマ区切りでグリフの代替指定可能
  * 強制的に等幅にする (force monospace)
    + 複数フォントを使用する際に役に立ちます
- プレビューの表示が可能
  * 全ての環境で同様のレンダリング結果が得られるとは限らないことに注意
- クエリパラメータ(str=???)で文字列を事前入力可能
  * [https://mr-ojii.github.io/SVG-VerticalTextHelper?str=こんにちは](https://mr-ojii.github.io/SVG-VerticalTextHelper?str=こんにちは)
