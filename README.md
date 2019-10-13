# Style Lab

這裡記錄了UI練習結果，同時方便日後取用。:art:
<br />
<br />

## 從零開始

`npm start`安裝packages並啟動gulp的建置與監聽。
<br />
<br />

## 建立分類

1. 於`src/views/pages`中建立`yourTaxonomy.html`
2. 於你建立的html中貼上以下code
    ```handlebars
    ---
    fabricator: true
    ---

    <h1 data-f-toggle="labels">yourTaxonomy</h1>

    {{#each materials.yourTaxonomy.items}}

    {{> f-item this}}

    {{/each}}
    ```
3. 以上的`yourTaxonomy`改成自己的分類名稱
4. 於`src/materials`中建立資料夾並命名成你的分類名稱
5. 資料夾內的html檔案名稱就會成為分類中的項目囉！:tada:
<br />
<br />



   

