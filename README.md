# 測試任務（一）

資料夾 `data sci paper` 提供六篇 Papers。

文件一、二先看過，根據以下問題寫 docx。若對於自然語言處理感興趣，參考文件三。


## [Basic]

* What is PCA, 原理是什麼，怎麼運作的？

* What is SVD, 原理是什麼，怎麼運作的？

* What is the SVD++, 原理是什麼，怎麼運作的？

* What is CF,原理是什麼，怎麼運作的？

文件四、五、六，擇其中 1 ~ 2 篇，提供 A4 one page 長度內，回覆該 paper 所提出的價值點。


## [Advance]

推薦系統如何把時間因素考量進去？可參考文件一、文件二或不限定可提供其他研究發表回答。 


---


# 測試任務（二）

請根據以下任務需求，評估完成此測試任務的時間。


## 任務需求1：情緒預測模型 

Dataset 為 `Ch_trainfile_Sentiment_3000.txt`

請使用svm進行情緒預測模型。另外，請再想任何一個模型要能比svm好，用相同資料當驗證。

* Input：句子 or 一個段落

* Output：-2, -1, 0, 1, 2

建議採用 5-fold cross validation，回覆數據是多少。

如：用 SVM 做完 5-fold cross validation 後的精準度為 80.12%


## 任務需求2：recommendation task

Dataset 為 `rs.csv`

Columns: (user：顧客／會員編號, item：商品編號, qty：交易量, datetime：交易時間)

1. 建模預測顧客購買行為（顧客-> List[商品]）

2. 自行split dataset：5-Fold CV + testSet，實現驗證方式。

3. 以AUC呈現驗證結果。
