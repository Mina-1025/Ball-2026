Unity 6 與 GitHub 版本管理期中作業
一、專案資料
專案名稱：DCD2026-ball
Unity 版本：6000.3.17f1
使用電腦：Windows 11
使用工具：Unity Hub、Unity Editor、JetBrains Rider、GitHub
GitHub 網址：https://github.com/sz982-web/DCD2026-ball
二、這次作業要做什麼
這次期中作業主要是要建立一個 Unity 專案，再把專案放到自己的 GitHub 上面。

以前我沒有很清楚 GitHub 是怎麼使用的，所以這次主要就是練習怎麼把 Unity 專案和 GitHub 連起來，還有了解 Commit、Push、Pull 是什麼意思。

三、我的操作過程
1. 建立 Unity 專案
   我先打開 Unity Hub，確認使用的版本是 6000.3.17f1，然後建立專案。

建立好之後，我有用 Unity Editor 打開，確認專案可以正常開啟。

2. 確認專案裡面的資料夾
   接著我檢查專案裡面的檔案，確認有 Assets、Packages、ProjectSettings 這幾個資料夾。

一開始我不太清楚 Unity 哪些資料夾需要上傳，後來才知道有些是專案需要的檔案，有些只是 Unity 自己產生的暫存資料。

3. 設定 .gitignore
   我有檢查 .gitignore，裡面會排除像 Library、Temp、Obj 這些資料夾。

我原本以為整個 Unity 資料夾都要上傳，後來才知道不用，不然會把很多不必要的檔案也一起放到 GitHub。

4. 使用 Rider 做 Commit
   我使用 JetBrains Rider 裡面的 Git 功能來操作。

操作的時候，我有遇到一個問題，就是明明已經輸入 Commit Message，卻沒辦法提交。後來才發現是因為我沒有勾選要提交的檔案。

勾選之後，我就成功完成 Commit，這次的提交訊息是「更新Unity場景設定」。

5. Push 到 GitHub
   完成 Commit 後，我再按 Push，把修改上傳到 GitHub。

一開始我不太確定有沒有成功，所以又打開 GitHub 網頁確認。後來看到最新的提交紀錄出現在 GitHub 上，才知道已經成功上傳。

6. 修改 README
   最後我在 GitHub 網頁上修改 README.md，把這次作業使用的工具、操作過程和學到的觀念記錄下來。

四、我對 Commit、Push、Pull 的理解
Commit 是什麼？
我把 Commit 理解成「在自己的電腦上存一個版本紀錄」。

例如我今天修改了一個檔案，做完 Commit 之後，Git 就會記住這次修改。

不過 Commit 不代表已經上傳到 GitHub。

Push 是什麼？
Push 就是把自己電腦上已經 Commit 的紀錄上傳到 GitHub。

我這次也是先 Commit，再 Push，最後去 GitHub 網頁確認有沒有成功。

Pull 是什麼？
Pull 就是把 GitHub 上比較新的修改抓回自己的電腦。

例如我在 GitHub 網頁直接修改 README，如果之後還要在 Rider 裡繼續編輯，就可以先 Pull，讓電腦上的版本跟 GitHub 同步。

五、這次作業的心得
這次作業花了我一些時間，主要是因為我之前不熟悉 GitHub 和 Rider 的 Git 功能。

剛開始我分不太清楚 Commit 和 Push，也不知道為什麼有時候按了按鈕卻沒有反應。後來實際操作過一次，才比較了解兩者的差別。

我印象比較深的是 Commit 那一步，因為我忘記勾選檔案，所以一直沒辦法提交。找到原因之後才順利完成。

另外，我也學到 Unity 專案不是所有檔案都需要上傳，.gitignore 可以幫忙排除一些不必要的資料夾。

這次雖然沒有做很複雜的遊戲內容，但我至少知道怎麼建立 Unity 專案、把檔案上傳到 GitHub，以及怎麼確認自己有沒有上傳成功。
