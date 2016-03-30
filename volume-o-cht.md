#（此文檔擬總結開頭為O或o的英文術語）
  
##｛系統工程圖表用語｝object-process diagram (OPD)
* 英文　　　　　　　｛系統工程圖表用語｝object-process diagram (OPD)
* 常見譯法　　　　　對象過程圖
* 提議人　　　　　　jeffreybaoshenlee
* 參考資料　　　　　https://en.wikipedia.org/wiki/Object_process_methodology#Object_process_diagram
* 示例
  * 出處　　　　　　【CCS, SA2015】，章節問題.第5章，426頁，倒數第1段，第1行。

##open-headed arrow
* 英文　　　　　　　open-headed arrow
* 常見譯法　　　　　開尾式箭頭
* 提議人　　　　　　jeffreybaoshenlee
* 註解　　　　　　　具體含義和譯法存疑。似乎是尾端有些分岔的實心箭頭，與尾段尾端的實心箭頭（solid-headed）相對。這一說法請參考E. J. Lowe所著的《Forms of Thought: A Study in Philosophical Logic》一書第38頁第3段第3行，Cambridge University Press，2013年。另一種說法為：open-headed arrow是指尾部平齊的空心箭頭，參考：https://en.wikipedia.org/wiki/Arrow_(symbol)#Arrows_in_Unicode 。
* 參考資料　　　　　【1】http://www.zftrans.com/favorite/vocabulary/2007-9/12/190507912190530140954.html
* 　　　　　　　　　【2】http://www.taiwan921.lib.ntu.edu.tw/mypdf/drawing10.pdf
* 示例
  * 出處　　　　　　【CCS, SA2015】，5.5.4小節，104頁，第1段，第3行。

##｛網站的｝operations team
* 英文　　　　　　　｛網站的｝operations team
* 常見譯法　　　　　【1】運維團隊【2】運營團隊；營運團隊
* 提議人　　　　　　jeffreybaoshenlee
* 註解　　　　　　　具體含義應根據語境來推斷。
* 示例
  * 出處　　　　　　【Slatkin, EP2015】，第8章，Item54，第201頁，第2段，第5行

##orthogonal

* 英文　　　　　　　｛「定語——中心語」式偏正短語裡的形容詞｝**orthogonal**
* 語境　　　　　　　重點在於強調某套軟件設計方案對其中各個門類的涵蓋度，而不在於強調兩個因素之間沒有關聯（翔按：如果重點在於強調後一種意思，那我建議譯為「正交的」、「可分開對待的」、「各是各的」、「各管一攤的」、「職能方面沒有重疊的」）
* 常見譯法　　　　　正交的
* 建議譯法　　　　　**完備的**；**完全涵蓋的**；**能涵蓋每一種A的每一種B**
* 提議人　　　　　　jeffreybaoshenlee
* 示例
  * 例句　　　　　　As a compromise, the Java Virtual Machine does not provide equal support for all data types: it is not completely orthogonal
  * 譯文　　　　　　……這套指令集並不能完全涵蓋每一種數據類型的每一種操作
  * 註解　　　　　　這句話暗含的意思是，有些指令無法涵蓋每一種數據類型（例如無法針對short、byte、int、double等類型全都各自提供一個版本）。比方說，if_cmp指令族就只提供了int版（if_icmp...)和引用版(if_acmp...)，而沒有為其它幾個類型提供對應的版本（例如沒有提供if_scmp、if_bcmp）。
  * 出處　　　　　　[LYBB, JVMS2014]，3.2，第43頁，倒數第2段，第4行

##A is orthogonal to B
* 英文　　　　　　　｛用來描述兩個科技概念之關係的句式｝**A is orthogonal to B**
* 建議譯法　　　　　【1】**A與B無關**；**A不參與B**；**無法由A推斷出B（會不會發生/是否成立）**
* 建議譯法　　　　　【2】**A與B互相獨立**；**A與B完全分離**；**A與B可區分對待**；**A與B可分開對待**
* 提議人　　　　　　jeffreybaoshenlee
* 註解　　　　　　　這兩個義項均可參考 http://dictionary.reference.com/browse/orthogonal 網頁的 orthogonal in Technology 部分。
* 示例
  * 例句　　　　　　（針對第【1】義項）because it is orthogonal to overriding
  * 譯文　　　　　　因為無法據此推斷出是不是有```final```方法遭到覆蓋
  * 出處　　　　　　[LYBB, JVMS2014]，4.10.1.5，第185頁，第2段，第2行
