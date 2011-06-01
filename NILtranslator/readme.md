選択した文章を翻訳するソフト

##スクリプト説明

文字列を選択した状態でコピーまたはショートカットを押すことで、辞書や翻訳をするソフトウェアです。

### 対応辞書サービス

* [KingSoft辞書]
* 英辞郎辞書ローカル検索(ご自分で英辞郎辞書を用意する必要があります)

**英辞郎辞書は同梱していません**のでご自分のものを使用するとよいです。
http://www.eijiro.jp/

### 対応翻訳サービス

* [Google翻訳]
* [Excite翻訳]

#### 英辞郎辞書の導入

ローカルの英辞郎辞書を使うためには、英辞郎辞書をデータベース形式に変換する必要があります。

辞書の変換形式は[EijiroX]と全く同じものを使用しています。
そのため[EijiroX]の変換方法をよく読み、databaseというファイル名のデータベースファイルを生成してください。

データベースファイルはできれば database → database.db(eijiro.dbなど)の拡張子として.dbにリネームした方がよいです(内部処理的に)

設定画面からdatabase.dbを設定し、辞書サービスとして英辞郎を選択すれば利用できるようになります。

## 捕捉

付属のCSSは表示パネルの表示を調整する。

## License

The MIT License

Copyright © 2011 azu

* NILtranslator は [EijiroX] の common_tokens.jsを利用しています

[KingSoft辞書]:http://www.kingsoft.jp/dictionary/
[Google翻訳]:http://translate.google.co.jp/
[Excite翻訳]:http://www.excite.co.jp/world/
[EijiroX]:http://d.hatena.ne.jp/edvakf/20101122/1290423802