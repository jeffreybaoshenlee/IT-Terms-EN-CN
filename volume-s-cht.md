#（此文檔擬總結開頭為S或s的英文術語）

##｛數據庫用語｝schema

* 英文　　　　　　　**schema**
* 常見譯法　　　　　模式；結構；架構；綱要；概要；大綱
* 註解　　　　　　　為了與pattern（設計與使用方面的模式）及mode（狀態與運作方面的模式）相區隔，有時可以改用其它詞語來靈活翻譯。

##｛數據庫用語｝soft state

* 英文　　　　　　　**soft state**
* 常見譯法　　　　　軟狀態；柔性狀態
* 註解　　　　　　　大意是指不刷就會過期的信息。參見：https://en.wikipedia.org/wiki/Soft_state
* 示例
  * 出處　　　　　　【Sullivan, NFMM2015】，2.2.2，第56頁，第2段，第1行

##specification （簡稱 spec）

* 英文　　　　　　　**specification**
* 常見譯法　　　　　【1】規範書；規範【2】規格書；規格
* 辨析　　　　　　　小愛以為，在描述**軟件、軟體或概念**時，可將其譯為規範書或規範，而在描述**硬件、硬體或實物**時，則不妨譯為規格書或規格。

##subroutine

* 英文　　　　　　　**subroutine**
* 常見譯法　　　　　子例程；子程序
* 示例
  * 出處　　　　　　[LYBB, JVMS2014]，3.13，第64頁，第3段，第5行

##｛廣義的｝superclass

* 英文　　　　　　　**｛廣義的｝superclass**
* 常見譯法　　　　　**超類**
* 辨析　　　　　　　該詞泛指某類型的直接上級或間接上級。與狹義用法之區別見「｛狹義的｝superclass」詞條。

##｛狹義的｝superclass

* 英文　　　　　　　**｛狹義的｝superclass**
* 常見譯法　　　　　**直接超類；父類**
* 其它譯法　　　　　｛戲謔的｝頂頭上司類
* 辨析　　　　　　　該詞特指某類型的直接上級。比如Java中的`ArrayList`直接繼承自`AbstractList`，而`AbstractList`又直接繼承自`AbstractCollection`，則`AbstractList`是`ArrayList`的直接超類（也就是狹義超類），而`AbstractCollection`則是`ArrayList`的間接超類。`AbstractList`、`AbstractCollection`及`Object`均可稱為`ArrayList`的廣義超類。
