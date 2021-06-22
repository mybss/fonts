「假粉圓體」是基於[jf open 粉圓](https://github.com/justfont/open-huninn-font)的開放原始碼中文字型。

假粉圓，有字重的粉圓字體。

## 5種字重(Style)
* ExtraLight
* Light
* Regular
* Medium
* SemiBold

原本的粉圓字體放在Regular 字重裡，透過程式自動產生ExtraLight、Light、Medium、SemiBold 新的字重。

在ExtraLight和Light字重是把原本的粉圓字體微微調細一點點。在Light的字重裡，可能會因為筆劃太細造成某些筆畫消失。

在SemiBold和Medium的字重裡，可能會因為筆劃太粗造成某些筆畫重疊難以識別，有粗體字的需求，可以先挑戰使用SemiBold字重看看，如果發現效果不如預期，Medium字重。

![字體預覽](https://github.com/max32002/FakePearl/raw/master/preview/preview.png)

不能確定自動產生出來的字重裡每一個都是完整的字，畢盡程式會誤判是常有的事情，所以不是在Regular字重裡的筆劃可能會消失。

由於是程式自動產生字重，有些字的方向可能會錯亂，請再回報有問題的字，小弟有空就幫忙修正。您也可以自行使用FontForget開啟「Regular」字重的 ttf 字型檔，就可以透過「Expand Stroke」這一個功能調整字型到您喜歡的字重。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

可以服用下面的css:
```
@font-face {
  font-family: FakePearl-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/FakePearl@1.1/webfont/FakePearl-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/FakePearl@1.1/webfont/FakePearl-Regular.woff) format("woff");
}
```

## 著作權與授權
* 本字型是基於 SIL Open Font License 1.1 改造just-font公司所開發、發表的「[jf open 粉圓](https://github.com/justfont/open-huninn-font)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

字體授權小提示：本字型採用 SIL Open Font License 1.1 授權發表，可以免費商用。在 github 上有附上 SIL Open Font License 1.1 的授權文件，如甲方或公司需要出示授權文件，直接使用此文件即可。

