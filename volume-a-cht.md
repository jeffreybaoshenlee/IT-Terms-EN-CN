#（此文檔擬總結開頭為A或a的英文術語）

##artifact

* 英文　　　　　　　**｛經由某種軟件的製作機理或工序而產生的｝artifact**
* 建議譯法　　　　　**（經由某機理或工序所產生的）【製品/產物】**；**由……所產生的物品**
* 提議人　　　　　　jeffreybaoshenlee
* 註解　　　　　　　artifact一詞之含義，可參考：https://en.wiktionary.org/wiki/artifact ，尤其注意第3義項，即「可視作人類概念或人類工具之產物，而非固有元素之物」。此義項的大概意思可能是「（由人工擬合的）產物」。
* 示例
  * 例句　　　　　　due to compiler-generated artifacts, ...
  * 譯文　　　　　　由於各種編譯器在生成方法簽名時所用的機理不同，……
  * 出處　　　　　　[LYBB, JVMS2014]，4.7.9.1，第123頁，第1段，第1行

##A is assignment compatible with B
* 英文　　　　　　　**A is assignment compatible with B**
* 建議譯法　　　　　**A兼容（於）B**；**A賦值兼容於B**；**A具備對B的賦值兼容性**
* 提議人　　　　　　jeffreybaoshenlee
* 註解　　　　　　　如果甲表達式的類型```A```可以通過賦值轉換操作，轉化成乙變量的類型```B```，那麼```A```類型就具備對```B```類型的賦值兼容性（A is assignment compatible with B）。例如通過```Object o= new Integer(1);```可知，```Integer```具備對```Object```的賦值兼容性，或者說```Integer```能夠兼容```Object```、```Integer```與```Object```相兼容。
* 示例
  * 出處　　　　　　[LYBB, JVMS2014]，4.9.2，第165頁，第5段，第1至2行
