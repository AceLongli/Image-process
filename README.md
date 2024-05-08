下載Tesseract https://github.com/UB-Mannheim/tesseract/wiki
更改電腦環境變數:檔案->本機右鍵->內容->進階系統設定->環境變數->編輯變數path->貼上C:\Users\C4\AppData\Local\Programs\Python\Python312\Scripts ; C:\Users\C4\AppData\Local\Programs\Python\Python312 ; C:\Program Files\Tesseract-OCR
以系統管理員身分打開命令提示字元
安裝virtualenv:在命令欄pip install virtualenv
在C槽自件檔案->在命令欄輸入cd 檔案位置->輸入virtualenv 自訂名稱 #確認後檔案內會多一個檔案
啟動虛擬環境:在命令欄輸入 cd 剛建立的檔案中的scripts的檔案位置->在命令欄輸入activate
