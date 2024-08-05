"#Hw2024"
'20240722'
```bash!
ls '列出資料夾中的檔案'
cd '前往位址'
pwd '現在資料夾位址'
grep '搜尋及擷取特定資料'
sed
''

'20240729'
1.1 su
1.1.1 su的功用主要在於使用者的切換
      'su [-lm] [-c 指令] [username]'
      'exit' 離開su的環境
1.1.2 su跟su-的差別
      'su' 讀取的變數設定方式為non-login shell，導致許多原本的變數不會被改變。即便將原先的使用者切換到root下，也不會進到root所在的環境中。
      'su -' 讀取的變數設定方式為login shell。將使用者切換到root後，透過密碼的驗證便能進入root所在的環境。便能直接使用root中的指令，PATH等路徑也都能導向root。
