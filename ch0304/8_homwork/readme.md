# 練習作業

設計一個假的帳號登入，指定帳密為admin/1234需要驗證，如果帳密不對出現警告(alert)

1. 建立login.php，設計為表單有帳號跟密碼欄位以及提交按鈕
2. 該表單會action到check.php進行驗證
3. 驗證過程，如果帳號ID不等於admin時，出現alert
4. 驗證過程，如果密碼不等於1234時，出現alert
5. 如果驗證某環節失敗，回到login.php畫面
6. 如果驗證都沒問題，出現alert('歡迎登入')，接著轉址到google.com