#（此文檔擬總結開頭為M或m的英文術語）

##MapReduce

* 英文　　　　　　　**MapReduce ; map reduce ; map-reduce**
* 常見譯法　　　　　映射——歸納；映射——【推演/推導】；映射——化簡
* 註解　　　　　　　若以兩詞首字母均大寫，且中間不加空格的形式出現，則可保留英文原樣不翻譯。
* 參考資料　　　　　https://en.wikipedia.org/wiki/MapReduce 、 https://zh.wikipedia.org/wiki/MapReduce
* 示例
  * 出處　　　　　　【Sullivan, NFMM2015】，11.3.2.3，第354頁，第1段，第1項

##mask

* 英文　　　　　　　**mask**
* 常見譯法　　　　　掩碼
* 辨析　　　　　　　該詞有兩種用法。
  * 用法一　　　　經典含義。用來同位段（bit field）求「與」運算，以判斷某標誌位是否開啓的數字。比如，對於長度為8的位段來說，想判斷右起第2個標誌位是否打開，則可以把位段同`0b0000 0010`（十六進制的`0x02`）取`&`運算，若不為`0`，則表示該標誌已開啓。
  * 用法二　　　　泛用含義。由各標誌位所構成的位段。該用法可見於[LYBB, JVMS2014]，4.7.6，第116頁，第1段，第1行

##meta

* 英文　　　　　　　**meta ｛技術詞語｝X；meta-X；metaX**
* 常見譯法　　　　　元X；描述X
* 其它譯法　　　　　關於X的X、高於X而又【超越/超乎】X的X、能夠製作X的X、形而上的X、X模板、
* 　　　　　　　　　模板式（的）X、生成式（的）X、X生成模板
* 註解　　　　　　　這個詞的具體含義最好根據文意來推敲。在可以詳加解釋的場合，不一定總要譯為「元……」。
* 舉例　　　　　　　metaclass：元類、描述類

