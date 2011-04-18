エクスプローラー上で使用するngスクリプトです。

主にファイルパスやディレクトリパスを渡して使うモノが多いです。

###スクリプト説明

* flatten_out_dir.ng

    D&Dしたディレクトリ以下をフラットにする

* folder_breaker.ng

    渡したフォルダを分解する

* remove_less_FolderSize.ng

    一定以下のフォルダサイズなら削除

* tree_command.ng

    treeコマンド的にディレクトリ構造を文字で表してクリップボードにコピー

* any_excure_recursively.ng

    指定したコマンドをディレクトリに対して再帰的に行う。

    引数なしでany_excure_recursively.ngを起動した場合はGUIにコマンドを書いて、対象ファイルをD&Dします。

    >$ng any_excure_recursively.ng exsample.exe path/to/dir/

    コマンド内で"で囲みたい場合cmdでは大変なので、代わりに$$と書けば内部的に"に変換します

    >$ng any_excure_recursively.ng "$$command$$" path/to/dir/
