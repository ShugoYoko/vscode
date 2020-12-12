# vscode
最小限の操作方法(メモ書き)

-コマンドパレットを開くのは Ctrl+Shift+P

-Git 連携
1. 新規リポジトリ作成

Git-code<br>
https://github.com/ShugoYoko/vscode.git

2. ローカルで作成

vscode-terminal<br>
cd [ローカルリポジトリのパス]<br>
git clone https://github.com/ShugoYoko/vscode.git<br>


3. ローカルでCommit<br>

vscode-terminal<br>

コマンド<br>
git add [ファイル名]<br>
git rm [ファイル名] //ファイル削除<br>
git commit -a -m "任意のコメント"  //コミット (-aオプションは変更を自動検出してくれる)<br>
//git push origin master  //masterを更新<br>

vscode-ソースコントローラでpush<br>
pushできない場合<br>
https://qiita.com/y-tsutsu/items/ec984831e6c8262d3ff7

-Debug<br>
launch.json