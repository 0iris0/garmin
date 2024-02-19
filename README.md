garmin變更管理流程優化

1.問題確認
變更管理的制度於2021年8月才開始實施，因當時都未實施管理但工安事故及設備問題頻傳，礙於時間壓力設計出簡易流程，希望能在設備用於生產前經歷完整安全等一系列評估，後來實施一段期間後發現卻無法大幅改善現況，主要問題是時程拖很久才完成。因設備開發期限最晚是6個月內完成，其中也針對超過預計期程時間(未超過6個月但超過自行評估預計完成日)與超過6個月內案件分析。
於是瞭解現況並經查核後，因目前申請系統紀錄的數據量太少，建議在填寫時新增欄位：每個階段完成的時間記錄、超時原因(採用順序資料收集)。


2.資料處理
雖有缺少一些資訊紀錄及資料量較小(n<50)，討論後不採用資料填補方式，因系統中有些案件仍在進行中，且因案件數較少若將缺失天數填補平均值或中位數皆會對資料有巨大影響，以現有完整資料先進行分析。
每次跳下一階段重新填寫日期時，safe examine日期也會隨時重新填寫，如果safe examine超過今天代表案件已逾期。
Apply date與safe examine相距若超過半年，代表時程推延太久影響產能進度。
廠區間在上述兩項資訊的狀況比較。


3.資料分析(時間截止日：112.02.22)
視覺化呈現現有資料：
https://github.com/0iris0/project/blob/main/%E7%8B%80%E6%85%8Bvs%E4%BB%B6%E6%95%B8.png?raw=true
圖一、狀態對應申請件數
從系統開始記錄時統計，大多案件已結案。

https://github.com/0iris0/project/blob/main/%E5%BB%A0%E5%8D%80vs%E4%BB%B6%E6%95%B8.png?raw=true
圖二、廠區對應申請件數
T5廠申請件數占全台41.4%居冠，其次依序為T3廠、T1廠、T2廠。

https://github.com/0iris0/project/blob/main/%E5%BB%A0%E5%8D%80vs%20over6m.png?raw=true
圖三、各廠申請案件平均結案天數(過去已結案共94件)
因結案時間超過半年即代表嚴重需及時改善對象，各廠結案天數並未有超過半年的。平均最長結案天數為T3廠約48.8天，其次依序為T2廠約40.9天、T5廠約29.8天、T1廠約27.6天。


圖四、未結案案件各廠平均逾期天數(共41件)
針對未結案件，每次申請資料時皆會填寫該部門期程規劃的當階段完成可以安全評估的日期，超過安全評估日至時間截點仍未結案，以T5廠平均173.7天最久，其次依序為T3廠105.7天、T1廠20.0天、T2廠10.5天。


圖五、未結案案件各狀態平均逾期天數(共41件)
針對未結案件，各狀態逾期天數，以設計階段為最久平均328.7天，其次依序為上線171.6天、驗收86.3天、製造11.0天。


分析1：申請件數最多為T5廠67件：因為近年新建廠區，申請皆有照新制規定走，廠區規模也較大。T3廠44件居二，但結案天數較長。如需關注改善狀況，可從T5及T3觀察或優先改善。結案天數T3廠48.8天最久，現況也因廠區較舊，人員常未依照新制規定走。且各舊廠皆存在一項共同誤差因素，因現有申請大多都未從設計階段開始申請，本圖僅計算從申請開始的階段到結案天數，實際情形預估可能更長。變更管理實施從2020年開始，但實際到2022年才嚴格執行，之前案件大多是從驗收階段才HS部門要求申請紀錄，因為補申請案件，無紀錄到設計、製造階段，驗收階段時間記錄不完整，因此結案天數較少。於是以下針對未結案案件進行分析。
分析2：未結案件分析(較貼近目前執行現況)：
(1)T5廠逾期天數173.7天將近6個月，因為是新廠區，變更管理流程有宣導及有嚴格要求，詳實紀錄。T3雖為舊廠區，但因廠區較大案件數也較多，在變更管理流程執行下，也顯示設備平均逾期天數105.7天約3個多月。兩廠與現有執行狀況也相符。
(2)設計狀態是逾期328.7天最久的階段，應為影響逾期天數之主因。如欲降低逾期率，應詳細分析設計過程SOP及規劃內容提升效率。
設計階段負責單位：機構、軟體、安衛
製造階段負責單位：機構、軟體
驗收階段負責單位：軟體、安衛
上線階段負責單位：機構
經瞭解，於設計討論階段可能未詳盡列出所有需求、提前符合安規內容、各部門溝通仍有未達共識之項目未解，耗費較多時日，雖製造階段僅需11.0天，但其實在設計階段與各部門討論時就已開始組裝機台以符合設計要求。然而上述未達共識項目會延至驗收階段被稽核未過關為仍需86.3天之因素。最後上線天數171.6天較長，因為除了修改驗收不足之處，機構、軟體與安規符合後，需準備SOP文件及針對作業員進行教育訓練等排程。
建議明確於設計階段分工，並於製造階段如遇狀況與各部門討論，而非等到該部門驗收才進行改善，甚至可以提前在設計階段先預擬作流程以利後續教育訓練文件可加生成，教育訓練可改由線上測驗減低因實體上課占用工作時間難安排因素。
備註：預計每半年定期自動跑上述圖表分析，追蹤變更管理改善狀況。
