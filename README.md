# 軟體工程大作業-線上零食銷售系統
>（Online snack sales system）

## 目 錄

### 第1章 引言

  >1.1 研究背景

  >1.2 國內外研究現狀

  >1.3 目標和意義

### 第2章 可行性分析

  >2.1 技術可行性分析

  >2.2 經濟可行性分析

  >2.3 運行可行性分析

### 第3章 需求分析

  >3.1 系統用例建模

  >3.3.1 系統用例分析

  >3.1.2 系統用例說明

  >3.2 需求分析

  >3.2.1 業務需求分析

  >3.2.2 用戶需求分析

  >3.2.3 功能需求分析

  >3.2.4 非功能需求分析
  
  >3.2.5 約束條件分析

  >3.2.6 業務規則分析

  >3.2.7 外部介面需求分析

### 第4章 系統設計

  >4.1 實體類別模型設計

  >4.2 動態模型設計

  >4.3 資料模型設計

### 第5章 系統實現

  >5.1 開發環境

  >5.2 新聞發布模組實現

  >5.3 新聞管理模組實現

### 第6章 系統測試

  >6.1 測試工具

  >6.2 單元測試

  >6.3 壓力測試

# 第一章 引言

## 1.1 研究背景

>電子商務是當今社會應該去了解的一項重要的環節，目前國內的電商產業已經初具模型，並逐漸走向正軌。 電子商務將會影響市場發展的格局，對經濟的發展帶來極大影響，人們可以在家中享受購物的快感，還有大量的折扣促銷。 電商經過這些年的發展，其影響力正緩步上升。 隨著時代的發展，目前人們已經逐漸步入了互聯網時代，人們的工作生活越來越離不開計算機和互聯網，網絡已經漸漸步入每一個人的家門，人們的衣食住行，樣樣都可以利用 網路來實現，電子商務作為一種新興起的經營方式，在人們的日常生活中都取得了顯著的成效。 這對個人而言，電子商務其表現最為直覺和方便的一大功能就是網上購物，同時這也是電子商務中B2C（企業到消費者）這一模式的最完美的體現，同時這一過程也是電子 發展的必然趨勢。 隨著科技的發展、網路知識的普及、電腦操作及管理日趨簡化,企業透過網路可以快速地獲取資料資訊並贏取更多的發展空間。

>網路能為企業帶來巨大的機會,企業透過網路可以輕易地把業務和服務推向全世界並提供即時的資訊。 在國內很多中小城市的商品不能達到人們的需求,所以大多數人透過網路來購買商品。 透過建立購物網站來方便人們進行網上購物,足不出戶有更好的消費體驗。 首先，它需要網路的便利條件，使人們可以購買他們需要的零食。 這就避免了交通壅塞購物造成的身體勞累。 其次，它可以讓人們選擇他們需要購買零的數量，包括零食的類型，節省時間，空出時間可以做其他方面事情，提高生活品質。 最後，零食銷售系統可以共享整個數據訊息，用戶無需透過現場購買商品即可購買零食。 這提高了組織服務的質量，也改善了對零食商品的查詢，大範圍、高效的接受添加零食到購物車，添加地址，修改購買訂單，刪除訂單等多種應有的的服務，並積極接受 用戶的不滿和建議再去完善，進而提高用戶對服務的滿意度。

## 1.2 國內外研究現狀

>國內現況目前我國網購市場發展的比較紅火,各大企業間激烈競爭,但是縱觀發展現狀,網上購物發展越來越符合我國國情。 網路科技日新月異,網民數量不斷激增。 龐大的上網人口提供了網路購物的發展基礎,讓網路成為僅次於傳統實體通路之外最重要的銷售管道。 在我國,隨著消費者消費觀念的逐漸普及,消費者的購物行為從傳統實體商店延伸到新形態的網絡商店,網絡購物市場獲得了長足的發展,通過Internert進行交易已經成為潮流。 基於電子商務而推出的商品交易方式,為資訊科技帶來了許多新的機會,並逐漸成為國際資訊市場的競爭焦點如此前景保持下去,中國網購市場已成全球亮點。

>國外現況歐美國家的網購市場相對國內,有著更完善的智慧財產權保護,信用體係以及物流配送體系,這使得網購市場更好的發展。 近年來,歐美國家這年不斷修訂專利法,版權法,商標法等智慧財產權法。 智慧財產權法以及其執法活動已經成為歐美國家法律制度中最活躍的部分,歐美國家有著有著完善的信用體系,沒有風險,而且快捷便利。 正是因為這些歐美國家的網購市場才能順利發展。

## 1.3 目標和意義

>經營成本低,借助日益發展的科學技術,網上銷售通常能夠省卻從生產到銷售過程中的許多環節,從而有效降低經營成本與交易成本,給消費者、商家帶來雙贏的局面。

>不用為地段憂愁。 對於傳統的有形店舖來說,門店的選址、地段的優劣,幾乎能夠決定其未來經營的成敗,而城市中的商業網點資源,尤其是優質的商業網點資源一般非常稀缺,網上銷售網站則 大多不存在地段方面的限制。

>風險相對小。 無論是對於企業或個人來說,網上銷售網站店等無店舖零售業態的准入門檻相對較低、更加快捷和高覆蓋，運轉比較靈活,即使遇到風險,也有船小好掉頭的優勢。 同時消費者也方便對商品的包裝、定價、服務等一系列問題發表意見。

# 第二章 可行性分析

>該系統是對線上零食銷售進行設計的，可行性分析是依據初步調查結果做出系統開發可行與否的結論的過程。 這是保證正確投資的必要工作，從專案的審批程序上看這也會是必不可少的一步。 可行性研究是要求以全面、系統的分析為主要方法,經濟效益為核心,圍繞影響項目的各種因素,運用大量的數據資料論證擬建項目是否可行。

## 2.1 技術可行性分析

>這次開發的線上考試系統是基於B/S模式的多用戶線上考試。 它運作方便、操作簡單、效率很高。 採用MYSQL資料庫與Tomcat伺服器。 在Eclipse開源軟體下進行編譯，方便修改測試，用瀏覽器就可以進行系統的測試，Tomcat 伺服器方便快捷，配置完成就可以使用，簡單又快速。 JDK版本也可以進行修改，可以引入對應的檔案包，確保對應框架的結合使用。 總之本系統在技術上的要求不高，現在普遍使用的計算機都可以運行該系統，因此在技術上是可行的。

## 2.2 經濟可行性分析

>該系統不需要高階設備，如電腦內存，處理器，圖形卡等。 它還與程式的操作環境相容，因此，延遲的系統功率將主要用於版本管理和系統載入的開發和維護。 因此，一旦系統運行，不僅可以減少先前的預訂，還可以降低車站的建造成本和人員需求，方便用戶使用。 因此，該系統在經濟上是可行的。

## 2.3 運行可行性分析

>線上零食銷售系統採用B/S模式，無需另外安裝別的軟體，使用者很容易掌握並熟練使用。 系統實施成功以後也會大幅減少商品銷售的時間，容易推廣使用，因此具有操作可行性。

# 第三章 需求分析

## 3.1 系統用例建模

## 3.3.1 系統用例分析
![imge](3.1.png)

>圖3-1 系統用例圖

>系統的使用者總共有兩類使用者：管理員和顧客，不同使用者有不同的權限。 系統用例圖如圖3-1所示:

## 3.1.2 系統用例說明

>1.登入使用案例使用者輸入自己已註冊完成的帳號，密碼，登陸成功後進入前台介面瀏覽商品選購商品如下表3-1所示：

>表3-1 顧客登入使用案例說明表
>![imge](3-1.png)

>2.商品管理功能用例是對前台顯示的商品資訊進行維護等操作。 詳細描述如下表 3-2所示：

>表3-2 商品管理功能用例描述
>![imge](3-2.png)

>3.購物車用例對需要買的商品進行添加購物車操作，瀏覽商品訊息，對商品進行購買。 詳細描述如下表 3-3所示：

>表3-3 購物車用例描述
>![imge](3-3.png)

## 3.2 需求分析

## 3.2.1 業務需求分析

>系統應符合以下業務需求：

>隨著電腦的日益發展和完善，電子商務越來越普及，設計的系統越來越完善，都 可能受到時間和空間上的限制。 所以，在設計每個專案開始，必須對系統實施可行性 分析，這樣可以降低系統的執行力，降低損耗。 為了確保零食銷售系統的成功開發和正常運行，分別從技術、經濟等多方面對本系統進行需求分析。

## 3.2.2 用戶需求分析

>系統的使用者總共有兩類使用者：管理員、顧客。

>1.管理員可以修改零食資訊、刪除零食資訊、加入零食資訊、維護零食資訊、維護購物車、管理留言等操作都能夠執行。

>2.顧客可以對購物車進行管理、瀏覽搜尋商品、填寫訂單、選擇付款方式、查詢訂單、刪除訂單、使用者退出、查看、修改個人資訊。

## 3.2.3 功能需求分析

>線上零食銷售系統要實現的整體功能是具有以下幾個重要的功能需求：

  >1.可以讓顧客在平台上瀏覽商品。

  >2.可以讓顧客在網路上進行支付。

  >3.可以讓顧客申請退貨、換貨。

  >4.顧客可以對購物車進行管理。

  >4.管理員可以對商品資訊進行增刪改查。

  >5.管理員、顧客可以進行註冊登入。

  >6.管理員對顧客留言進行管理

## 3.2.4 非功能需求分析

>（1）系統應在5秒內回應所有使用者請求。

>（2）系統應同時對應1000以上用戶請求。

>（3）系統應每時對應10,000以上用戶業務請求。

>（4）系統應在每天24小時、每週7天都可以正常使用。

>（5）登入和操作系統必須是合法的操作員才能夠進行操作，並對其進行嚴格的管理和篩選過濾，進而確保系統操作證的合法性和系統的安全性。

>（7）應用系統安全上要有一定的保障，記錄資訊應全部記錄齊，不可遺漏訊息，並保障系統不會因為人為的操作錯誤而死機或崩潰；

>（8）系統應有較好的可維修性，以便在系統故障時能在24小時內恢復運作。

## 3.2.5 約束條件分析

>（1）系統必須使用Java語言，並採用SSH框架編寫。

>（2）系統必須使用MySql資料庫應用系統。

>（3）系統開發過程和交付文件必須遵循GB/T 8567-2006標準。

>（4）系統服務必須運作在Win7以上64位元作業系統。

>（5）系統應與IE、火狐、360等主流瀏覽器相容。

## 3.2.6 業務規則分析

>（1）如果操作員是管理員，則能管理本系統的相關資訊。

>（2）如果操作員是顧客，則僅能進行帳號註冊和登錄，瀏覽商品和購置商品。

>（3）如果顧客對商品有想買的意願，則可以先將商品加入購物車。

>（4）如果系統出現商品添加，刪除，查詢不成功等狀況，則將資訊回饋給管理員。

>（5）如果系統在商品管理未維護好之前，則將限制顧客進行購買功能。

## 3.2.7 外部介面需求分析

>（1）系統應提供符合Web應用程式的人機互動介面。

>（2）系統設定檔必須採用XML檔案格式。

>（3）各模組過程之間採用函數呼叫、參數傳遞、傳回值的方式進行訊息傳遞。

>（4）介面傳遞的訊息將是以資料結構封裝了的數據，以參數傳遞或傳回值的形式在模組之間傳遞。

# 第四章 系統設計

## 4.1 實體類別模型設計

>線上零食銷售系統，主要有兩大實體，顧客和管理員。 管理員和顧客是一對多的聯繫，系統實例類別及關係如圖4-1所示:
>![imge](4.1.png)

>圖4-1 系統實體類別關係圖

## 4.2 動態模型設計

## 1.購物車活動建模

>購物車操作主要步驟如下所示:

  >1.顧客先登入購物車介面。
  
  >2.顧客選擇要執行的操作。
  
  >3.購買商品。

  >4.結束進程。 如圖4-2所示:

>![imge](4.2.png)


>圖4-2 購物車活動圖

## 2.商品管理活動建模

>商品管理操作主要步驟如下所示:

  >1.管理員先登入商品管理系統介面。

  >2.管理員選擇要執行的操作。

  >3.管理商品資訊。

  >4.結束進程。 如圖4-3所示:
>>![imge](4.3.png)

>圖4-3 商品管理活動圖

>2.購物車時序建模

>購物車時序圖是顧客選擇商品後對商品進行瀏覽，進行購買後會回傳下單結果。 如圖4-4所示：
>>![imge](4.4.png)

>圖4-4 購物車時序圖

>3. 商品管理時序建模

>商品管理時序圖是管理員進入系統前台介面對商品進行添加，刪除，查詢，維護等操作。 如圖4-5 所示：
>>![imge](4.5.png)

>圖4-5 商品管理時序圖

## 4.3 資料模型設計
>根據系統用例模型和實體類別模型，可以建立了以下資料庫邏輯結構，僅列出新聞發布所使用的各資料表的詳細說明。

# 第五章 系統實現
## 5.1 開發環境
### 1． 軟體環境

  >（1）MySQL資料庫系統；

  >（2）MyEclipse開發環境；

  >（3）Spring、Struts、Hibernate框架。

### 2． 硬體環境

  >（1）CPU類型： Intel Haswell CPU

  >（2）CPU速度： 2.8GHz
  
  >（3）硬碟容量：500G
  
  >（4）內存容量：4G

## 5.2 商品資訊管理模組實現
>商品資訊管理頁面列出了新增的商品信息，包括商品名稱，商品價格，商品數量，商品類型。 此系統前景頁如圖5-1所示：
>>![imge](5.1.png)

>圖5-1 商品資訊管理模組效果圖

## 5.3 管理購物車模組實現
>本單元實現購物車的資訊管理功能。 點擊網站瀏覽購物車並進入購物車的管理介面，顯示目前購買的零食信息，顧客可以刪除購物車中的特定記錄，或者可以創建請求並提交購物車的內容，效果圖如圖5-2所示 。
>>>![imge](5.2.png)


>圖5-2 管理購物車效果圖

# 第六章 系統測試
## 6.1 測試工具
  >（1）手工測試。

  >（2）LoadRunner自動化測試工具。

## 6.2 單元測試
>本次採用黑盒子等價類劃分法對新聞發布模組進行測試。

>1. 建立等價類表
>>>![imge](https://github.com/11024228/final_report/blob/8b563e439a3519f53325d2b9cacbe2a2fdd2f055/6-1.png)

>表 6-1 等價類例表


>2. 設計測試案例
>>![imge](https://github.com/11024228/final_report/blob/8b563e439a3519f53325d2b9cacbe2a2fdd2f055/6-2.png)

>表 6-2 測試案例表


>偏差：無

>測試結果：能夠驗證使用者名稱和密碼的正確性，系統登入功能正常實現。

## 6.3 壓力測試

>在壓力測試中，使用LoadRun自動化測試工具完成整體系統的測試工作，主要測試項目如下：

  >1. 回應時間

>回應時間是指使用者從客戶端發出請求到接收完伺服器回傳結果的整個過程所需花費的時間，包含網路傳輸時間以及伺服器處理時間。 從使用者角度來看，回應時間應該從客戶端電腦處理使用者操作並發出請求到客戶端程式收到伺服器端回傳結果並顯示出來的時間。

>結果：<1秒

  >2. 並髮用戶數

>並髮用戶數是指在一定時間內，某一時刻同時與伺服器進行會話操作的用戶數，並髮用戶數的類型包括：系統用戶數、同時在線用戶數，業務並髮用戶數。

>結果：>1000

  >3. 吞吐量

>吞吐量是指單位時間內，系統處理使用者的請求數或頁面數量，可直接反映軟體的承載量。 一般來說，利用每秒鐘的請求數或頁面數量來衡量吞吐量；從業務的角度來看，也可以用每天的訪問人數或每小時處理的業務數來衡量。

>結果：3×24 50000次/h
>
## 資料來源 
>https://blog.csdn.net/qq_46628483/article/details/128112711
## 組員

>11024228葉承翰
>11024230陳嘉偉
