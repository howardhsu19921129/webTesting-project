參考資料: https://backlog.com/git-tutorial/tw/stepup/stepup1_1.html

git remote : 內容可能是網址，指向remote的 repo的位址。可能有http / SSh 等不同的連線方式

git clone <url> : 整坨抓下來，預設branch會在master上

git checkout <branchname> : 切換到分支<branchname>上面

git branch <new_branchname> : 建立新的分支，會從當下所在的分支長出去

git commit : 其實就是建立一個正式的版本。每個commit會有一個獨立的亂數id用以辨識。

        commit記得寫message

git merge : 簡單來說就是合併兩個分支。會在使用者當下所在的branch後面接著長一個新的commit，該commit屬於該branch上的一個新版本

git push : 將一個新的commit推上repo上的某個branch(當下所在的branch)


        merge出狀況如何解決?
        如何放棄merge?
        how to force merge
        如何刪除分支?
        fetch vs pull ?
        local branch 與 traking branch的關係?
        "master" 這個名稱出現時，指的是local or remote端的branch?
        "origin" 應該是指remote 的名稱?



