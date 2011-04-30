[CoffeeScript][]関係のngスクリプト

Description
===========
## CS-Compiler.ng

CofeeScriptをNILScript(SpiderMonkey)を使ってコンパイルします.

同じディレクトリにCS-Compiler.ng と [coffee-script.js][](自分で最新にして)を置きます。

Compile CofeeScript by NILScript (SpiderMonkey Engine).

Put CS-Compiler.ng and [coffee-script.js][] into same directory.

### Usage
Command line(コマンドライン向け)

####Command Line:
>    $ng.exe CS-Compiler.ng "FilePath" or "DirectoryPath"

####command line options:
>    --watch(-w)  - Now whenever you change code.coffee, will automatically update code.js with the changes.

### Exsample

#### Compile file

>$ng CS-Compiler.ng code.coffee

>$ng CS-Compiler.ng /path/to/code.coffee

#### Compile mutiple files

>$ng CS-Compiler.ng code.coffee heloo.coffee

#### Compile directory (match /.*?\/$/)

>$ng CS-Compiler.ng path/to/directory/

#### Watch file modify

>$ng CS-Compiler.ng code.coffee --watch


[CoffeeScript]:<http://jashkenas.github.com/coffee-script/> "CoffeeScript"
[coffee-script.js]:<https://github.com/jashkenas/coffee-script/blob/master/extras/coffee-script.js>