# rime-essay-singlechar
Solution to allow only single characters to be suggested on RIME. RIME選字時只顯示單詞方案

## 解釋
我早前下載了[鼠鬚管（RIME Mac版）](http://rime.im/)，用來打倉頡。在依定製指南的指示移除了倉頡拼音混打之後，在倉頡的選字區裡會出現詞組（不是指帶有太極圖章「☯」的連打詞句選項）。

看過了定製指南，好像沒有說明讓它只顯示單字的解法（也有可能是我看漏眼了），於是我就研究出了以下的方法。

如您知道有更好的解決方案，歡迎在此提出，謝謝！

## 使用方法
* 下載`cangjie5.singlechar.dict.yaml`和`essay-singlechar.txt`。
* 把以上兩個檔案放到您的[用戶資料夾](https://github.com/rime/home/wiki/RimeWithSchemata#user-content-rime-%E4%B8%AD%E7%9A%84%E6%95%B8%E6%93%9A%E6%96%87%E4%BB%B6%E5%88%86%E4%BD%88%E5%8F%8A%E4%BD%9C%E7%94%A8)。
```
用戶資料夾
【中州韻】 ~/.config/ibus/rime/ （0.9.1 以下版本爲 ~/.ibus/rime/)
【小狼毫】 "%APPDATA%\Rime"
【鼠鬚管】 ~/Library/Rime/
```
* 在您的`cangjie5.custom.yaml`裡，加入`translator/dictionary: cangjie5.singlechar`

如需在其他輸入法使用此方法，對`cangjie5.singlechar.dict.yaml`稍加修改即可。
