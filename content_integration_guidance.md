# 網站內容整合與風格更新指南 (WordPress)

## 前言

本指南旨在協助您將先前撰寫的部落格文章以及網站風格建議整合至 `https://buylemon.com.tw/` (鴻福有機檸檬園) 的 WordPress 網站中。我們將提供步驟說明和一般性建議，幫助您順利完成更新。

## 1. 新增部落格文章至 WordPress

以下是如何在 WordPress 中新增部落格文章的一般步驟：

1.  **登入 WordPress 後台：**
    通常是透過 `您的網域名稱/wp-admin` (例如 `https://buylemon.com.tw/wp-admin`) 進入。

2.  **導航至「文章」：**
    在左側的管理選單中，找到「文章」(Posts)，點擊它。

3.  **新增文章：**
    點擊「文章」旁邊的「新增文章」(Add New) 按鈕。

4.  **新增標題：**
    *   在最上方的「新增標題」(Add title) 輸入框中，複製並貼上您部落格文章的標題。
    *   例如，從 `blog_post_1.md` 文件中複製「檸檬水對皮膚和消化系統的好處」。

5.  **新增內文：**
    *   在標題下方的內容編輯區塊（可能是傳統編輯器或區塊編輯器），複製並貼上對應部落格文章的內文。
    *   Markdown 文件 (`.md`) 中的內容是純文字，您可以直接貼上。WordPress 編輯器支援 Markdown 的基本語法，或者您可以手動調整格式 (如標題層級 H2, H3, 列表等)。
    *   **區塊編輯器提示：** 如果您使用的是區塊編輯器 (Gutenberg)，每個段落、標題、列表都會是獨立的區塊。您可以點擊 `+` 按鈕新增不同類型的區塊。

6.  **上傳與插入圖片：**
    *   **準備圖片：** 根據部落格文章中「圖片建議」的部分，準備好相應的圖片檔案。
    *   **插入圖片：**
        *   在編輯器中，將游標置於您想插入圖片的位置。
        *   點擊「新增媒體」(Add Media) 按鈕（傳統編輯器）或點擊 `+` 選擇「圖片」(Image) 區塊（區塊編輯器）。
        *   選擇「上傳檔案」(Upload Files)，然後從您的電腦中選取圖片。
        *   **加入替代文字 (Alt Text)：** 上傳後，在右側的「附件詳細資料」(Attachment Details) 中，務必填寫「替代文字」(Alt Text)。替代文字應簡潔描述圖片內容，這對 SEO 和無障礙瀏覽非常重要（例如：「一杯清新的檸檬水和幾片檸檬」）。
        *   選擇圖片尺寸（建議選擇「中型」或「大型」，視版面而定），然後點擊「插入至文章」(Insert into post)。

7.  **設定分類與標籤 (Categories and Tags)：**
    *   在編輯器右側的「文件」(Document) 設定欄中，找到「分類」(Categories) 和「標籤」(Tags) 區塊。
    *   **分類：** 為您的文章選擇或新增一個合適的分類（例如：「檸檬健康」、「美容護膚」、「農場點滴」）。分類有助於組織內容。
    *   **標籤：** 新增幾個與文章內容相關的關鍵字作為標籤（例如：「檸檬水」、「維生素C」、「DIY面膜」、「有機」）。標籤有助於訪客發現相關文章。

8.  **（選擇性）設定特色圖片 (Featured Image)：**
    *   在右側「文件」設定欄中，找到「特色圖片」(Featured Image) 區塊。
    *   點擊「設定特色圖片」，上傳一張最能代表該文章的圖片。特色圖片通常會顯示在部落格列表頁或文章頂部。

9.  **SEO 優化 (搜尋引擎優化)：**
    *   **SEO 外掛：** 如果您的網站安裝了 SEO 外掛（如 Yoast SEO, All in One SEO Pack），通常在編輯頁面下方會有相應的設定區塊。
    *   **焦點關鍵字：** 設定文章的主要關鍵字。
    *   **SEO 標題與 Meta 描述：** 撰寫吸引人的 SEO 標題和 Meta 描述。Meta 描述是搜尋結果中顯示在標題下方的簡短摘要，應包含關鍵字並鼓勵點擊。
    *   **內容可讀性：** 許多 SEO 外掛也會分析內容的可讀性，您可以根據建議進行調整。

10. **預覽與發佈：**
    *   完成編輯後，點擊右上角的「預覽」(Preview) 按鈕，在新分頁中查看文章在網站前台的顯示效果。
    *   確認無誤後，點擊「發佈」(Publish) 按鈕。您可以選擇立即發佈或設定排程發佈。

對 `blog_post_1.md`、`blog_post_2.md` 和 `blog_post_3.md` 重複以上步驟。

## 2. 實施風格建議至 WordPress

以下是如何將 `styling_recommendations.md` 中的風格建議應用到您的 WordPress 網站。

### A. 使用 Custom CSS (自訂 CSS)

大部分的顏色、字體和一些版面微調可以透過自訂 CSS 來實現。

*   **添加位置：**
    1.  **WordPress Customizer (外觀 > 自訂 > 附加 CSS)：**
        *   這是最簡單直接的方法。進入 WordPress 後台，導航至「外觀」(Appearance) > 「自訂」(Customize)。
        *   在自訂器介面中，尋找「附加 CSS」(Additional CSS) 或類似選項。
        *   將您的 CSS 規則貼在此處。您可以即時預覽變更。
        *   點擊「發佈」(Publish) 保存。
    2.  **子佈景主題 (Child Theme)：**
        *   **推薦原因：** 如果您需要進行較多或較複雜的 CSS 修改，或者未來可能修改佈景主題的範本檔案 (`.php`)，強烈建議使用子佈景主題。子佈景主題會繼承主佈景主題的所有功能和樣式，但您的自訂修改會保存在子佈景主題中。這樣，當主佈景主題更新時，您的自訂內容不會遺失。
        *   **如何操作：** 建立子佈景主題需要一些技術知識。您可以搜尋相關教學（例如 "如何建立 WordPress 子佈景主題"）或請開發者協助。一旦啟用子佈景主題，您可以將自訂 CSS 添加到子佈景主題的 `style.css` 檔案中。
    3.  **自訂 CSS 外掛：**
        *   如果您不想使用子佈景主題，但希望更有條理地管理 CSS，可以使用如 "Simple Custom CSS and JS" 之類的 WordPress 外掛。

*   **CSS 範例 (僅供說明，非完整代碼)：**
    以下是如何將 `styling_recommendations.md` 中的建議轉換為 CSS 規則的簡單範例：

    ```css
    /* --- 來自 styling_recommendations.md 的範例 --- */

    /* 1. 色彩搭配 - 主要背景色 */
    body {
        background-color: #F5F0E6; /* 大地米 */
    }

    /* 1. 色彩搭配 - 主要內文顏色 */
    body, p {
        color: #8A7967; /* 橄欖褐 */
    }

    /* 2. 字體排印 - 標題字體 (假設您的標題是 h1, h2, h3) */
    h1, h2, h3 {
        font-family: 'Noto Serif TC', serif;
    }

    /* 2. 字體排印 - 內文字體 */
    body, p, li, span, div { /* 您可能需要更精確的選擇器 */
        font-family: 'Noto Sans TC', sans-serif;
        line-height: 1.7; /* 建議的行高 */
    }

    /* 4. 版面配置與元素風格 - 按鈕 */
    .wp-block-button__link, input[type="submit"] { /* WordPress 預設按鈕及提交按鈕的常見選擇器 */
        background-color: #A0BCA6; /* 鼠尾草綠 */
        color: #FEFBF6; /* 乳白色文字 */
        border-radius: 4px; /* 輕微圓角 */
        padding: 10px 20px;
        text-decoration: none;
        border: none;
    }

    .wp-block-button__link:hover, input[type="submit"]:hover {
        background-color: #8EAB97; /* 鼠尾草綠稍深色 */
    }
    ```
    **注意：** 上述 CSS 選擇器 (`body`, `h1`, `.wp-block-button__link` 等) 是通用範例。您可能需要使用瀏覽器的「開發者工具」(通常按 F12，選擇「元素」或「檢查器」) 來找到您網站上特定元素的正確 CSS 選擇器。

### B. 整合 Google Fonts (字體)

根據風格建議，我們推薦了 Noto Serif TC 和 Noto Sans TC。

1.  **檢查佈景主題內建支援：**
    *   進入「外觀」(Appearance) > 「自訂」(Customize)。瀏覽您的佈景主題提供的選項，特別是關於「排印」(Typography) 或「字體」(Fonts) 的部分。有些佈景主題允許您直接從 Google Fonts 列表中選擇字體。

2.  **使用外掛：**
    *   如果佈景主題不支援，最簡單的方法是使用外掛。例如：
        *   **Easy Google Fonts:** 允許您在 Customizer 中輕鬆選擇和分配 Google Fonts 給不同的元素。
        *   **Google Fonts Typography:** 提供更細緻的控制，可以選擇字重、樣式等。
    *   安裝並啟用外掛後，依照外掛的指示設定 Noto Serif TC 和 Noto Sans TC。

3.  **手動加入 (進階選項，建議透過子佈景主題)：**
    *   您可以透過編輯子佈景主題的 `functions.php` 檔案來載入 Google Fonts。這需要在 `<head>` 中加入相應的 `<link>` 標籤。例如：
        ```php
        function my_theme_enqueue_styles() {
            // ... 其他已有的 enqueue ...

            // 載入 Google Fonts
            wp_enqueue_style( 'google-fonts', 'https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;700&family=Noto+Serif+TC:wght@400;700&display=swap', false );
        }
        add_action( 'wp_enqueue_scripts', 'my_theme_enqueue_styles' );
        ```
    *   然後在您的 CSS 中直接使用 `font-family: 'Noto Serif TC', serif;`。

### C. 檢查佈景主題選項/自訂器 (Theme Options/Customizer)

在進行大量 CSS 修改前，務必先徹底檢查您的佈景主題提供的內建選項。
*   路徑：「外觀」(Appearance) > 「自訂」(Customize)。
*   許多佈景主題允許您直接更改：
    *   **顏色：** 背景色、文字顏色、連結顏色等。
    *   **字體：** 如上所述，部分佈景主題內建字體選擇。
    *   **Logo 上傳。**
    *   **頁首/頁尾佈局和顏色。**
*   優先使用佈景主題的內建選項，這樣可以減少自訂 CSS 的需求。

### D. 頁面編輯器 (Page Builders)

如果您的網站或特定頁面是使用頁面編輯器（如 Elementor, Beaver Builder, WPBakery 等）建立的：
*   這些編輯器通常有自己的樣式設定面板。您可以直接在編輯器介面中調整特定區塊、欄、或元素的背景顏色、字體、邊距、圓角等。
*   對於由頁面編輯器控制的內容，其提供的樣式選項可能會覆蓋您在「附加 CSS」或佈景主題選項中設定的樣式。

## 3. 一般建議

在進行任何重大修改之前，請務必注意以下事項：

*   **備份網站 (非常重要！)：**
    *   在進行任何風格修改、安裝新佈景主題/外掛或加入自訂程式碼之前，**務必完整備份您的 WordPress 網站**。備份應包含您的網站檔案和資料庫。
    *   您可以使用 WordPress 的備份外掛 (如 UpdraftPlus, All-in-One WP Migration 等) 或透過您的主機服務提供商的備份功能。
    *   如果發生任何問題，您可以從備份中還原網站。

*   **測試環境 (Staging Site)：**
    *   如果您的主機提供商支援，或您有能力建立一個「測試環境」(staging site)，這是一個與您正式網站隔離的複製站點。
    *   先在測試環境中實施所有變更並進行測試。確認一切運作正常且外觀符合預期後，再將變更同步到正式上線的網站。
    *   如果沒有測試環境，請在流量較低的時候進行修改，並在修改後立即仔細檢查網站的各個部分。

*   **逐步實施與測試：**
    *   不要一次進行所有修改。可以先從顏色或字體開始，保存並檢查效果。然後再進行其他調整。這樣更容易找出問題所在。

*   **清除快取 (Clear Cache)：**
    *   如果您使用了快取外掛 (e.g., WP Rocket, LiteSpeed Cache) 或 CDN (如 Cloudflare)，在進行 CSS 或樣式變更後，記得清除所有快取，這樣才能看到最新的變更。瀏覽器快取也可能需要清除 (Ctrl+Shift+R 或 Cmd+Shift+R 強制重新整理)。

*   **尋求專業協助：**
    *   如果您對執行某些步驟（尤其是涉及程式碼修改、子佈景主題建立）感到不自在，或者修改後遇到無法解決的問題，建議尋求專業 WordPress 開發人員的協助。

希望這份指南能幫助您順利地將新的部落格內容和風格融入您的網站，打造一個更具吸引力的「鴻福有機檸檬園」線上平台！
