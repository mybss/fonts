# 獅尾彎黑體 Swei Curve Sans

獅尾彎黑體基於[思源黑體](https://github.com/adobe-fonts/source-han-sans)的變圓和拔腳改造，更加簡明現代化的字體。支援简体中文、繁體中文、韓文與日文；可以免費商用，歡迎大家自由應用、自由優化、自由改作！

「獅尾彎黑體」與「獅尾圓體」差別在筆觸是否有做調整，獅尾彎黑體所套用的效果較少，在筆觸沒有做調整。

![字體預覽](https://github.com/max32002/swei-curve-sans/raw/master/preview/welcome.png)

和思源黑體一樣，支援7種的字重：
![字體比較預覽](https://github.com/max32002/swei-curve-sans/raw/master/preview/compare_style.png)
附註：目前有些筆畫還沒有套用到效果，是程式需要改進的地方。

## 與其他字體的比較
* 在「刂」的筆畫，獅尾比較相似台灣(教育部國字標準字體)教育部推薦字體筆順。
* 在「肉」、「糸」、「女」、「辶」、「食」的筆畫，獅尾比較相似台灣教育部推薦字體筆順，適合教育用途。
* 在「草」部的筆畫，獅尾是分開的二個部份。
* 字體裡的「草字頭部首」中間該不該連起來，「肉字旁部首」該不該變成「月」，要不要把手寫習慣代入印刷字體？整體看來，會不會影響視覺的延伸性？會不會影響印刷的可行性與閱讀的便利性？這個答案我也不清楚，如果你是台灣教育部標準字符的愛好者，獅尾字體應該是一個不錯的選擇。

### 字體後面的 SC,JP,TC是什意思？
* SC是 Simplified Chinese 简体中文，代表大陸習慣字形。
* TC是 Traditional Chinese 繁体中文，代表港台習慣的字形。
* JP是 Japanese 日文，代表日本習慣字形。
* 相同一個字，在不地區的書寫方式可能會略有不同。

### 「CJK TC」和「CJK SC」的比較：
![TC和SC比較](https://github.com/max32002/swei-curve-sans/raw/master/preview/compare_tc_sc.png)
* 在「肉」、「糸」、「女」、「辶」、「食」的筆畫不同，CJK SC 「肉字旁部首」變成「月」。 
* 在「草」部的筆畫，CJK SC 中間連起來。
* 「體」字的骨上方方向相反。
* 「角」字下面穿頭。
* 雨、身、戶、舟、北、㕣、酋字寫法不同。

### 「CJK TC」和「CJK JP」的比較：
![TC和SC比較](https://github.com/max32002/swei-curve-sans/raw/master/preview/compare_tc_jp.png)
* 在「肉」、「糸」、「女」、「辶」、「食」的筆畫不同，CJK JP 「肉字旁部首」變成「月」。 
* 在「草」部的筆畫，CJK JP 中間連起來。
* 雨、言、青、兌、賣、直、真、曾、戶、北、㕣、酋字寫法不同。其他[常見與日系字型的差異](https://max-everyday.com/2020/06/taiwanpearl/#diff)。

## 更新日誌
[點擊此處](https://github.com/max32002/swei-curve-sans/blob/master/change_log.md) 查看更新記錄。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

可以服用下面的css:
```
@font-face {
  font-family: SweiCurveSansCJKtc-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/swei-curve-sans@2.129/WebFont/CJK%20TC/SweiCurveSansCJKtc-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/swei-curve-sans@2.129/WebFont/CJK%20TC/SweiCurveSansCJKtc-Regular.woff) format("woff");
}
```

