CoffeeScript関係のngスクリプト
http://jashkenas.github.com/coffee-script/

== Description

* CS-Compiler.ng
CofeeScriptをNILScript(SpiderMonkey)を使ってコンパイルします.
同じディレクトリにCS-Compiler.ng と coffee-script.js(自分で最新にして)を置きます。
- https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js にある

Compile CofeeScript by NILScript (SpiderMonkey Engine).
put CS-Compiler.ng and coffee-script.js into same directory.
- https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js

== usage
Command line(コマンドライン向け)
= Compile file
$ng CS-Compiler.ng code.coffee
$ng CS-Compiler.ng /path/to/code.coffee
= Compile mutiple files
$ng CS-Compiler.ng code.coffee heloo.coffee
= Compile directory (match /\/$/ ,  depth limit is 3)
$ng CS-Compiler.ng path/to/directory/
= Watch file modify
$ng CS-Compiler.ng code.coffee --watch
