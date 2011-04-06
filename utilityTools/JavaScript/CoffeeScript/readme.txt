CoffeeScript関係のngスクリプト
http://jashkenas.github.com/coffee-script/


== Description

* CoffeeScript-Complier.ng
CofeeScriptをNILScript(SpiderMonkey)を使ってコンパイルします.
同じディレクトリにCoffeeScript-Complier.ng と coffee-script.js(自分で最新にして)を置きます。
- https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js にある

Compile CofeeScript by NILScript (SpiderMonkey Engine).
put CoffeeScript-Complier.ng and coffee-script.js into same directory.
- https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js

== usage
Command line(コマンドライン向け)
= Complie file
$ng CoffeeScript-Complier.ng code.coffee
= Complie mutiple files
$ng CoffeeScript-Complier.ng code.coffee heloo.coffee
= Watch file modify
$ng CoffeeScript-Complier.ng code.coffee --watch
