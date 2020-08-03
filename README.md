# The Traditional Chinese Language Pack for SonarQube
SonarQube 繁體中文套件(Traditional Chinese Language Pack)
This is the Traditional Chinese Language Pack of SonarQube.

## Author 
- Tim Lee <wentin.lee@gmail.com>
- Vongola <vongola12324@coder.tw>

## Release
Latest version: https://github.com/vongola12324/sonar-l10n-zh-tw/releases/latest

Compatibility Matrix: 

|**SonarQube** |**8.0**|**8.1**|**8.2**|**8.3**|**8.4**|       |       |       |       |       |
--------------|-------|-------|-------|-------|-------|-------|-------|-------|-------|-------|
sonar-l10n-zhtw |1.0    |       |       |      |       |       |       |       |       |       |
|**SonarQube** |**7.5**|**7.6**|**7.7**|**7.8**|**7.9**|
sonar-l10n-zhtw |1.0   |1.0   |1.0   |1.0   |1.0   |

## Issue
If there is any problem, like typo, missing translation, or wrong translation, you can just open an issue and let me know it or just send a PR.
如果有任何問題，像是：錯字、缺少翻譯或是翻譯錯誤，你可以開一個issue讓我知道，或是直接發PR過來。
Issue Tracker: https://github.com/vongola12324/sonar-l10n-zh-tw/issues
（因為我沒有SonarQube開發者版或企業版，所以有部分頁面我沒辦法測試。）

## Not to translate list
除了一些對應到外部網站的專有名詞，仍有部分單詞因為某些原因沒有翻成中文，這邊就列出來，有疑問一樣也歡迎開issue討論。
| Original (原文)  | Chinese (可能翻譯) | 原因 |
| --------------- | ---------------| ----|
| Repository | 倉庫、倉、庫 | 翻譯後可能反而看不懂 |
| Class      | 類別 | 可能會跟 type(類型)/category(分類、類別) 等相似字搞混 |
| Commit     | 提交 | 可能會跟 submit(提交、送出) 等相似字搞混 |
| Token      | 令牌、權杖、代幣 | Token 在繁體中文裡應該沒有正確翻譯(據我所知)，硬翻後可能反而看不懂 |
| Bug        | 臭蟲 | 翻譯後可能反而看不懂 |
| SCM | 原始碼版本管理 | 因為翻譯後會導致字串過長 |
| Sonar way |  | 此為官方規則名稱 |
| SAML | 安全主張標記式語言 | 因為翻譯後會導致字串過長，且翻譯後可能反而看不懂 |
| API | 應用程式開發介面 | 翻譯後可能反而看不懂 |
| ALM | 生命週期管理 | 翻譯後可能反而看不懂 |
| CI | 持續整合 | 翻譯後可能反而看不懂 |