# project1
## 如何使用GIT
1. 先到該資料夾最頂端，使用右鍵開啟`git bash`
2. 於git bash中輸入`git init`初始化git資料庫
3. 輸入`git add .`把變更的文件加入緩存區，`git add`後與`.`要有空白，`.`的意思代表該目錄下所有文件
4. 設定git使用者，`git config --global user.email "yourmail@mail"`和`git config --global user.name "yourname"`
5. 把緩存區的資料存入git資料庫中`git commit -m "本次提交進資料庫的訊息ex.Add set user function..."`，如果沒有打`-m`會進入vim編輯器中，輸入`:wq`後按enter可以離開
6. 把遠端資料庫(github)的節點加入至本地資料庫`git remote add origin [url]`，`origin`代表遠端節點的名稱，`[url]`為遠端資料庫的網址，如此遠端資料庫`https://github.com/Kevin-1215/project1.git `
7. 把本地資料庫推至遠端資料庫節點`git push`，第一次`git push`惠要求指定節點和分支名稱，依照log複製貼上即可，例如輸入`git push`得到` git push --set-upstream origin master
`，之後把` git push --set-upstream origin master`重打一遍即可。
完成!
