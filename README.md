# 獅尾繁中黑體 Swei Fan Sans

獅尾繁中黑體基於[思源黑體](https://github.com/adobe-fonts/source-han-sans)的簡轉繁字型；可以免費商用，歡迎大家自由應用、自由優化、自由改作！

獅尾繁中黑體的特色是：簡體字轉成繁體字的字型檔，沒有很完美，比完全沒轉換好一點。不能處理「一簡對多繁」，下列的簡體中文會維持原樣：「'干','了','卜','乃','才','亏','于','千','','么','巨','丑','仇','云','扎','夭','凶','夫','斗','只','布','出','冬','发','它','他','占','扑','扣','托','奶','札','汇','吊','奸','夸','回','同','团','曲','伙','仿','后','朱','合','吃','匡','庄','村','志','里','别','谷','克','困','沈','佛','余','折','助','沄','芸','肖','坛','杆','表','杯','板','松','范','苧','刮','卷','弥','弦','舍','昆','岳','征','制','虮','杰','面','厘','咸','须','茧','药','荡','挂','挑','尝','秋','洒','适','洁','洼','荐','咱','炫','鸩','恹','钥','剃','咽','咯','背','炼','姜','拐','咨','恤','荫','昵','垒','党','获','借','脏','致','蚕','赶','家','晒','症','离','恶','娘','殷','栖','盏','绦','','唉','席','捂','挽','效','核','栗','疱','瓶','疴','莼','浩','浚','涌','涂','凌','凄','准','烟','挨','焊','蝎','象','雇','游','剩','棹','搜','逾','愧','踊','演','历','升','划','向','冲','并','苏','系','你','刨','弄','泛','抵','呼','周','胡','炮','迹','宴','捆','崎','麻','棱','毁','暗','橹','台','局','采','复','蒙','雕'」由於無法處理，所以會直接略過。

「獅尾繁中黑體」與「獅尾繁腿黑體」差別在有沒有拔腳，「拔腳」就是會有較少的筆畫，例如移除「口」字的左右下角會多出的短線條。有拔腳的字會較圓，但是會造成有些字因直接去掉腿後左右不平衡、左右不對襯的「懸空」問題。改使用「腿」系列字體就不會有這個問題。

![字體預覽](https://github.com/max32002/swei-fan-sans/raw/master/preview/welcome.png)
說明：由於「發」和「髮」在簡中是同一個字「发」，目前不知如何處理一對多的對應，所以部份簡體字還是維持原本的形態。

「獅尾繁中黑體」設計上針對筆畫粗細支援7種字重，所以不論大標、小標、簡單的段落排版都能清晰辨識。

可以處理「一簡對多繁」的字型，請參考「繁媛明朝」專案：https://github.com/ayaka14732/FanWunMing

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

## 更新日誌
[點擊此處](https://github.com/max32002/swei-fan-sans/blob/master/change_log.md) 查看更新記錄。

## 下載字型

請點選GitHub此畫面右上綠色「Clone or download」按鈕，並選擇「Download ZIP」，或點進想下載的ttf字型檔案，再點「Download」的按鈕進行下載。

## 網頁字型(Web Font)服務

網頁字型用於網頁上的字型顯示，訪客不需預先安裝字型檔，一樣能夠看到特殊的字型效果。不只是電腦，在智慧型手機和平板裝置的瀏覽器上也可正常顯示。實現該功能的原理是在瀏覽時才下載字型檔。

可以服用下面的css:
```
@font-face {
  font-family: SweiFanSansCJKtc-Regular;
  src: url(https://cdn.jsdelivr.net/gh/max32002/swei-fan-sans@2.0/WebFont/CJK%20TC/SweiFanSansCJKtc-Regular.woff2) format("woff2")
  , url(https://cdn.jsdelivr.net/gh/max32002/swei-fan-sans@2.0/WebFont/CJK%20TC/SweiFanSansCJKtc-Regular.woff) format("woff");
}
```

## 已知問題

* 這不是一個專業的字型檔案。
* 希望有贊助者，或其他勇者繼續改良和調整很多怪怪的小細節。
* 由於小編對字體編碼方式完全不清楚，相較於原版的思源黑體，可能有掉一些符號或不常用的字。

## 著作權與授權

* 本字型是基於 SIL Open Font License 1.1 改造Adobe和Google所開發、發表的「[思源黑體](https://github.com/adobe-fonts/source-han-sans)」字型。
* 本字型亦基於 SIL Open Font License 1.1 授權條款免費公開，關於授權合約的內容、免責事項等細節，請詳讀 License 文件。
    * 可自由商用 不需付費、知會或標明作者，即可自由使用此字型，亦可做商業應用。
    * 可自由傳布 可自由分享檔案、將檔案安裝於任何軟硬體中。
    * 可自由改作為其他字型 將字型檔案修改重製為其他字型檔案，改作後的字型檔案須同樣依 Open Font License 釋出。

字體授權小提示：本字型採用 SIL Open Font License 1.1 授權發表，可以免費商用。在 github 上有附上 SIL Open Font License 1.1 的授權文件，如甲方或公司需要出示授權文件，直接使用此文件即可。
    
## 相關網頁

花園家族：
* B2花園 B2 Hana
https://max-everyday.com/2020/08/b2-hana-font/
* 花園肉丸 Hana Meatball
https://max-everyday.com/2020/08/hana-meatball/

簡體/繁體轉換家族：
* 獅尾簡腿黑體 Swei Jay Leg
https://max-everyday.com/2020/11/swei-jay-leg/
* 獅尾簡中黑體 Swei Jay Sans
https://max-everyday.com/2020/11/swei-jay-sans/
* 獅尾簡中宋體 Swei Jay Serif
https://max-everyday.com/2020/11/swei-jay-serif/
* 獅尾繁腿黑體 Swei Fan Leg
https://max-everyday.com/2020/11/swei-fan-leg/
* 獅尾繁中黑體 Swei Fan Sans
https://max-everyday.com/2020/11/swei-fan-sans/
* 獅尾繁中宋體 Swei Fan Serif
https://max-everyday.com/2020/11/swei-fan-serif/

獅尾黑體家族：
* 獅尾飛腿黑體 Swei Dart Leg
https://max-everyday.com/2020/11/swei-dart-leg/
* 獅尾飛鏢黑體 Swei Dart Sans
https://max-everyday.com/2020/11/swei-dart-sans/
* 獅尾火腿黑體 Swei Match Leg
https://max-everyday.com/2020/11/swei-match-leg/
* 獅尾火柴黑體 Swei Match Sans
https://max-everyday.com/2020/11/swei-match-sans/
* 獅尾骨腿黑體 Swei Bone Leg
https://max-everyday.com/2020/11/swei-bone-leg/
* 獅尾骨頭黑體 Swei Bone Sans
https://max-everyday.com/2020/11/swei-bone-sans/
* 獅尾斧腿黑體 Swei Ax Leg
https://max-everyday.com/2020/11/swei-ax-leg/
* 獅尾斧頭黑體 Swei Ax Sans
https://max-everyday.com/2020/11/swei-ax-sans/
* 獅尾喇腿黑體 Swei Bell Leg
https://max-everyday.com/2020/11/swei-bell-leg/
* 獅尾喇叭黑體 Swei Bell Sans
https://max-everyday.com/2020/11/swei-bell-sans/
* 獅尾惡腿黑體 Swei Devil Leg
https://max-everyday.com/2020/11/swei-devil-leg/
* 獅尾惡魔黑體 Swei Devil Sans
https://max-everyday.com/2020/11/swei-devil-sans/
* 獅尾麥腿黑體 Swei Marker Leg
https://max-everyday.com/2020/10/swei-marker-leg/
* 獅尾麥克黑體 Swei Marker Sans
https://max-everyday.com/2020/10/swei-marker-sans/
* 獅尾詠腿黑體 Swei Fist Leg
https://max-everyday.com/2020/10/swei-fist-leg/
* 獅尾詠春黑體 Swei Fist Sans
https://max-everyday.com/2020/10/swei-fist-sans/
* 獅尾鋸腿黑體 Swei Alias Leg
https://max-everyday.com/2020/10/swei-alias-leg/
* 獅尾鋸齒黑體 Swei Alias Sans
https://max-everyday.com/2020/10/swei-alias-sans/
* 獅尾尖腿黑體 Swei Spike Leg
https://max-everyday.com/2020/10/swei-spike-leg/
* 獅尾尖刺黑體 Swei Spike Sans
https://max-everyday.com/2020/10/swei-spike-sans/
* 獅尾快腿黑體 Swei Shear Leg
https://max-everyday.com/2020/09/swei-shear-leg/
* 獅尾快剪黑體 Swei Shear Sans
https://max-everyday.com/2020/09/swei-shear-sans/
* 獅尾福腿黑體 Swei Gospel Leg
https://max-everyday.com/2020/09/swei-gospel-leg/
* 獅尾福音黑體 Swei Gospel Sans
https://max-everyday.com/2020/09/swei-gospel-sans/
* 獅尾D滷腿黑體 Swei Del Luna Leg
https://max-everyday.com/2020/09/swei-del-luna-leg/
* 獅尾德魯納黑體 Swei Del Luna Sans
https://max-everyday.com/2020/09/swei-del-luna-sans/
* 獅尾彎腿黑體 Swei Curve Leg
https://max-everyday.com/2020/09/swei-curve-leg/
* 獅尾彎黑體 Swei Curve Sans
https://max-everyday.com/2020/09/swei-curve-sans/
* 獅尾霓腿黑體 Swei Bow Leg
https://max-everyday.com/2020/09/swei-bow-leg/
* 獅尾霓黑體 Swei Bow Sans
https://max-everyday.com/2020/09/swei-bow-sans/
* 獅尾蝙蝠圓體 Swei Bat Sans
https://max-everyday.com/2020/09/swei-bat-sans/
* 獅尾牙膏圓體 Swei Toothpaste
https://max-everyday.com/2020/09/swei-toothpaste/
* 獅尾三腿黑體 Swei 3T Leg
https://max-everyday.com/2020/09/swei-3t-leg/
* 獅尾三角黑體 Swei 3T Sans
https://max-everyday.com/2020/08/swei-3t-sans/
* 獅尾螺帽腿黑體 Swei Nut Leg
https://max-everyday.com/2020/08/swei-nut-leg/
* 獅尾螺帽黑體 Swei Nut Sans
https://max-everyday.com/2020/08/swei-nut-sans/
* 獅尾B2腿黑體 Swei B2 Leg
https://max-everyday.com/2020/07/swei-b2-leg/
* 獅尾B2黑體 Swei B2 Sans
https://max-everyday.com/2020/07/swei-b2-sans/
* 獅尾腿圓 Swei Gothic Leg
https://max-everyday.com/2020/08/swei-gothic-leg/
* 獅尾彩虹腿 Swei Rainbow Leg
https://max-everyday.com/2020/08/swei-rainbow-leg/
* 獅尾XD珍珠 Swei XD Pearl
https://max-everyday.com/2020/07/swei-xd-pearl/
* 獅尾D露西 Swei D Lucy
https://max-everyday.com/2020/07/swei-d-lucy/
* 獅尾半月字體 Swei Gothic
https://max-everyday.com/2020/04/swei-half-moon/
* 台灣圓體 TaiwanPearl
https://max-everyday.com/2020/06/taiwanpearl/
* 獅尾圓體 Swei Gothic
https://max-everyday.com/2020/04/swei-gothic/
* 獅尾黑體 Swei Sans
https://max-everyday.com/2020/03/swei-sans/

獅尾宋體家族：
* 獅尾B2加糖宋體 Swei B2 Sugar
https://max-everyday.com/2020/11/swei-b2-sugar/
* 獅尾加糖宋體 Swei Sugar
https://max-everyday.com/2020/11/swei-sugar/
* 獅尾B2宋朝 Swei B2 Serif
https://max-everyday.com/2020/07/swei-b2-serif/
* 獅尾肉丸 Swei Meatball
https://max-everyday.com/2020/06/swei-meatball/
* 獅尾四季春字體 Swei Spring
https://max-everyday.com/2020/04/swei-spring/

其他字體：
* 苦累蛙圓體 Kurewa Gothic
https://max-everyday.com/2021/06/kurewa-gothic/
* 何某手寫體 Nani Font
https://max-everyday.com/2020/09/nanifont/
* 內海字體  Naikai Font
https://max-everyday.com/2020/03/naikaifont/
* 莫大毛筆字體 Bakudai Font
https://max-everyday.com/2020/03/bakudaifont/
* 正風毛筆字體 Masa Font
https://max-everyday.com/2020/05/masafont/
* 假粉圓體 Fake Pearl 
https://max-everyday.com/2020/03/open-huninn-font/
* 俊羽圓體 Yu Pearl 
https://max-everyday.com/2020/03/yupearl/

其他網站：
* 清松手寫體 JasonHandWriting
https://jasonfonts.max-everyday.com/
* Max學習字體相關的筆記
https://codereview.max-everyday.com/font-readme/

## 贊助Max

很高興可以替中華民國美學盡一分心力、讓台灣擁有更好的文字風景，希望能提供另一種美學讓大家選擇，如果你覺得這篇文章寫的很好，想打賞Max，贊助方式如下：
https://max-everyday.com/about/#donate
