aec-data
========

本處存放原能會所公佈各項資料的 JSON 版本。經由
https://github.com/g0v/aec-process/ 中的程式處理過後，自動發佈於此。

Data URL
========

每分鐘更新一次。注意：json 為 utf8 編碼，但 csv 皆為 big5 編碼。本地另存與來源相
同的 csv 用意在於對照，以遍日後檢驗問題。

- 最新幅射偵測: http://g0v.github.io/aec-data/latest/gammamonitor.json
  - 來源網址: http://www.aec.gov.tw/open/spds.csv
  - 本地對照: http://g0v.github.io/aec-data/latest/gammamonitor.json

- 最新核電廠機組狀態: http://g0v.github.io/aec-data/latest/spds.json
  - 來源網址: http://www.aec.gov.tw/open/gammamonitor.csv
  - 本地對照: http://g0v.github.io/aec-data/latest/spds.csv
