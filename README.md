# QR_stamp_rally
this is web application that stamp rally by QR marker

<dt>「構成」</dt>

```
    ・start_screen.html  : スタート画面 
    ・allmap.html        : 全体マップの表示 
    ・app_screen.html    : スタンプラリー画面 
```

<dt>「仕様」</dt>

```
    start_screen.html　・スタートボタンでページ遷移、ユーザー登録
                       ・注意書きや説明文の記載 (未実装)

    allmap.html        ・全体マップから大学の位置をクリックするとページ遷移

    app_screen.html    ・戻るボタンで全体マップへページ遷移可能
                       ・スポットクリック時、詳細画像表示 (未実装)
                       ・読み込み時にデータベースにアクセス、スタンプラリーの表示
                       ・右下のボタンでカメラ起動、×ボタンでカメラ停止
                       ・QRコード読み込み後、データベースの更新、ページの再読み込み
                       ・QRコード読み込み時にコラム表示、完成時ポップアップの表示　(未実装)
```

<dt>「TODOリスト」</dt>

```
    ・スタート画面を押した後Cookieをサーバーに送信、存在しない場合ユーザー登録としてレコードとCookieの作成　　「start_screen.html」
    ・ページ読み込み時にデータベースからデータを読み込み、スタンプの達成状況を反映　　「app_screen.html」
    ・QRコード読み込み時に読み取ったデータをサーバーに送信してデータベースを更新　　　「app_screen.html」
```

  
