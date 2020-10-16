# 20201015 作業：錢包問題（cash.cpp）

最少有多少個銅板+紙鈔可以湊到給定金額？

- 幣值：`1000`, `500`, `100`, `50`, `10`, `5`, `1`, `0.5`, `0.1`
- 金額有可能大於四位數
- 金額有可能有小數

## 測試範例 1
```
金額：1666.6
9
```

## 測試範例 2
```
金額：248.6
12
```

## 作業注意事項

- 含有小數點的金額可能會有誤，你需要先將金額轉換成整數處理。
- 請使用 Do-While 確認使用者輸入正確金額
- 請注意浮點數的不準確性，你應該要將使用者輸入的金額都轉換成以「角」（0.1 元）為單位，意即把 `float` 轉為 `int`，以避免相加的錯誤。
- 當然，不要只是將使用者的輸入從 `float` 轉換為 `int`！一角等於多少元？

---

Pull Request 前請確認以下事項：

* 已閱讀 [作業繳交方式](https://hackmd.io/@nssh/nscsc/%2F%40nssh%2Fsummit-homework)
* 在下方附上 Repl 連結
* 檔案放在自己學號的目錄下
* 標題以「班級座號、學號、姓名」作為開頭
* 其他說明事項可以在下面補充
