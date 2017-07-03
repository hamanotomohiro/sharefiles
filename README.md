
README.md

 ### docファイルの差し替え ###
 1) > git clone https://github.com/hamanotomohiro/sharefiles.git で、git cloneを実施する。
 2)  httpRequest\routes の doc.zip を該当のドキュメントに差し替える
 3)  2)のファイルは、必ず doc.zipにすること
 4) > cd ./sharefiles
 5) > git status
 6) > git add [該当ファイル]
 7) > git commit -m "comment"
 8) > git push origin master


 ### herokuへの公開 ###
 1) > git clone https://github.com/hamanotomohiro/sharefiles.git
 2) > cd ./sharefiles
 3) > rm -rf .git
 4) > npm install
 5) > git init
 6) > git add -A
 7) > git commit -m "heroku update"
 8) > heroku create tomosharefiles
 9) > git push heroku master
 