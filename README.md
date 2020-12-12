# vscode
最小限の操作方法

-コマンドパレットを開くのは Ctrl+Shift+P

-Git 連携
1. 新規リポジトリ作成

Git-code
https://github.com/ShugoYoko/vscode.git

2. ローカルで作成

vscode-terminal
cd [ローカルリポジトリのパス]
git clone https://github.com/ShugoYoko/vscode.git


3. ローカルでCommit

vscode-ソースコントローラ
Commit All

コマンド
git add [ファイル名]
git commit -a -m "任意のコメント"  //コミット (-aオプションは変更を自動検出してくれる)
git push origin master  //masterを更新

-Debug
launch.json