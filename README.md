# SmartExam - 一個支援程式設計的線上測驗平台

* [http://smartexam.csie.nptu.edu.tw/](http://smartexam.csie.nptu.edu.tw/)
* 屏東大學 資訊工程學系 106學年度專題實作  
* 2017年資訊學院專題競賽軟體 系統與雲端應用組 **第一名**
* 支援 C 、 C++ 、 JAVA
* **自動批改**考試與作業，不需耗費人力
* 便捷的程式碼編輯環境與**即時編譯**功能
* **考試作弊偵測**、**監考系統**、**詳細記錄**、**成績**及**作答詳細**
* **已實際上線於屏東大學資工系程式設計課程的相關作業以及考試的進行**
* 考試時使用**SmartExam考試專用程式**開啟Chrome內建的Kiosk模式，強制全螢幕

## 簡介
　　本專題希望能跳脫出傳統的筆試，讓程式設計相關課程都可以使用 SmartExam 讓學生們可以在線上進行程式碼的編寫，並可以即時地完成程式碼編譯與執行，即時地檢查其執行結果是否和題目要求的一致。透過作弊偵測的功能，還可以有效地避免學生進行作弊。Smart Exam 亦考慮了考試現場的需求，設計了專供監考人員使用的功能，使其可以在考場巡視的同時，仍能透過監考輔助功能掌握全班作答的動態。我們要在此強調，Smart Exam 並不是只有線上考試功能而已，它還可以支援線上作業、題庫、練習、課程以及班級管理等相關的功能，將來可以支援程式設計相關課程的完整授課活動。

## 開發環境
* CentOS 7
* PHP 5.5.21
* Apache HTTP Server 2.4.6
* MariaDB 5.5.52
* phpMyAdmin 4.5.0.2

## 使用模板、框架、工具
* [Spectral](https://html5up.net/spectral)
* [tinyMCE](https://www.tinymce.com/)
* [tinyMCE 圖片上傳插件]( https://github.com/vikdiesel/justboil.me)
* [ace editor](https://ace.c9.io/)
* [sweetalert](https://sweetalert.js.org/)
* [reCAPTCHA](https://developers.google.com/recaptcha/)
* [jQuery](https://jquery.com/)

## 重點功能介紹
#### CODING畫面
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic15.png)
* 程式碼編輯器就像是真正的IDE一樣，關鍵字會使用不同的顏色區分，也可以使用Tab鍵做縮排動作，編輯器左側也會顯示行數方便debug。
換行符號使用圖示表示，讓畫面看起來更舒服。  

#### 作弊偵測
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic04.png)
* 使用者離開考試頁面去搜尋答案時，考試頁面時將會有一個需要輸入密碼的視窗佔據整個考試畫面，若監考人員判定無作弊行為將可輸入密碼後於監考畫面點擊解鎖該學生的考試。

#### 即時監考
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic03.jpg)
* 在考試進行時，監考人員可以選擇自動刷新的時間，來查看學生考試時的動作。

#### 自動批改&成績統計
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic10.png)
* 考試與作業將會自動批改，老師與助教可以見到所有同學的各題成績與總成績，作答詳細亦可。

#### 學生操作紀錄
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic20.png)
* 學生在考試時的操作將會記錄起來，供老師與助教調閱。

#### 作答詳細
![](https://github.com/MTsung/SmartExam/raw/master/upimages/pic12.png)
* 學生可使用作答詳細觀看之前撰寫的程式碼，以便得知錯在哪裡。

## 身分功能圖
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/%E8%BA%AB%E5%88%86%E5%8A%9F%E8%83%BD%E5%9C%96.png)

## 實際上線成果圖
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/%E5%AF%A6%E9%9A%9B%E5%9C%96%E7%89%87/%E6%9C%AA%E5%91%BD%E5%90%8D%20-%203.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/%E5%AF%A6%E9%9A%9B%E5%9C%96%E7%89%87/%E6%9C%AA%E5%91%BD%E5%90%8D%20-%2051.png)

## 專題文件
[專題文件](https://github.com/MTsung/SmartExam/blob/master/SmartExam-%E4%B8%80%E5%80%8B%E6%94%AF%E6%8F%B4%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88%E7%9A%84%E7%B7%9A%E4%B8%8A%E6%B8%AC%E9%A9%97%E5%B9%B3%E5%8F%B0.pdf)

## 專題展海報
![專題展海報](https://github.com/MTsung/SmartExam/raw/master/SmartExam-%E4%B8%80%E5%80%8B%E6%94%AF%E6%8F%B4%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88%E7%9A%84%E7%B7%9A%E4%B8%8A%E6%B8%AC%E9%A9%97%E5%B9%B3%E5%8F%B0.png)

## 專題展說明簡報
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-001.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-002.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-003.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-004.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-005.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-006.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-007.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-008.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-009.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-010.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-011.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-012.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-013.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-014.png)
![](https://github.com/MTsung/SmartExam/raw/master/%E6%96%87%E4%BB%B6/PPT/%E5%9C%96%E7%89%87/cbhan-2zxew-015.png)

## 說明
因原始碼凌亂不堪且有資安漏洞，故只放上文件及成果圖