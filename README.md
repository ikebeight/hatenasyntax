# エディター「Mery」向けはてな記法シンタックスハイライト
テキストエディター「[Mery](http://www.haijin-boys.com/)」向けのはてな記法の構文ファイルです。  
はてなダイアリーで使うことを想定し、[はてなダイアリーの記法一覧](http://hatenadiary.g.hatena.ne.jp/keyword/%E3%81%AF%E3%81%A6%E3%81%AA%E8%A8%98%E6%B3%95%E4%B8%80%E8%A6%A7)に記載された構文を正規表現によりハイライトします。  
This is a setting file for the text editor ["Mery"](http://www.haijin-boys.com/), that is able to support syntax highlighting for "Hatena Kihō"(Hatena Method of Writing) with this plugin.

## 制約など
- 色分けはMonokai向けに調整しました
- Meryの“複数行にまたがるシンタックスハイライトはできない”仕様により、引用記法は開くタグと閉じるタグだけハイライトしています
- Meryの“ハイライトは実際の一行でなく見た目の一行しかハイライトしない”仕様により、折り返し機能で2行目に跨った部分はハイライト市内場合があります（する場合もあるようです）
- [はてな記法一覧ページ](http://hatenadiary.g.hatena.ne.jp/keyword/%E3%81%AF%E3%81%A6%E3%81%AA%E8%A8%98%E6%B3%95%E4%B8%80%E8%A6%A7)に記載のあるものをまずは対応しました
- [詳しい入力ルール](http://g.hatena.ne.jp/help#editrule)はこれから対応します
