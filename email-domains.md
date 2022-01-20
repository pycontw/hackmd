---
tags: 2021-organize, organize
---

🔙 Back to [歷年 PyCon TW Organizing 共筆](/ryPr7SFyP/%2FHM5mHCFKQCu7-W5ea8ITcw%3Fview)
🔙 Back to [PyCon TW 2021 Organizing 共筆](/Wb9vQrfJQk-5tPoPR23hwA)
🔙 Back to [PyCon TW 2020 Organizing 共筆](/5u84SOprTUeQYBR57TH49w)

[TOC]


# PyCon TW Email Domain 管理辦法

PyCon Taiwan 志工組織擁有下列兩個 email domain ：

- pycon.tw (owner[name=yyc])
    - email service 綁定古早以前的免費版 google workspace （現在叫做 legacy google workspace）
- python.tw (owner [name=tai])
    - email service 綁定在 Open Culture Foundation (OCF) 提供的非營利組織 google workspace
        - 2022 May 1 開始會轉移到 google workspace， Jul 1 前要決定要不要課金續命。請見 [google 公告](https://support.google.com/a/answer/2855120?hl=en)。


## 管理通則

- 未來僅提供 python.tw domain for new email accounts。
    - pycon.tw 先出現，之後才是 python.tw 。 基於資源與已綁定既有功能的考量，自 2019 年後停止建立與發送新的 python.tw email address。所有新的 email address 需求，改為 python.tw 提供。
        - 資源：希望繼續維持使用免費的/legacy google workspace ，但該 legacy google workspace 帳戶名額已達使用上限
        - 已綁定既有功能的 pycon.tw email addresses ：例如好幾年前就已經拿去註冊某些迄今仍在使用的基礎服務。
- python.tw 的 email service ，是透過 Open Culture Foundation (OCF) 提供的非營利組織 google workspace 所提供。藉由在該 workspace 下建立一個新的 gmail user account 實踐。因此該 user account 自然受該 google workspace a.k.a. OCF workspace 權限管理，使用限制也承襲同一個 workspace 的規定。

### 與 OCF Google Workspace 合作通則

- 由 domain owner 擔任 PyCon TW 與 OCF 聯繫的窗口；下稱 **「 domain 管理員」或「管理員」**。
- 由 domain owner 管理 OCF 所開設的對應的 domain user group 。
- 以 `python.tw` 而言， [name=tai] 是目前擔任上述兩者角色的人，因為 python.tw owner is [name=tai]

#### OCF Google Workspace 管理員權責

- 明確告知 OCF 配發 new user account 的計畫
- 可以在所屬 user group 新增 member a.k.a. user account
- (有權限但請勿輕易使用) 因為技術限制，管理員在建立 new user account 的時候可以選擇其他已經 OCF Google Workspace 已經支援的 email domain。請管理員使用自己管理的 domain 就好。例如 python.tw 管理員請選 python.tw，不要手賤去選 coscup.tw 。
- 管理員自身帳號有義務開啟 2FA 協助組織保護系統安全


### 更多 Domain 管理員須知

- 可多採用 mail group 而不是開帳號
    - 開 mail group 可考慮開 conversation 來建立 email archive、保存信件往來，方便未來查閱與交接。
    - pycon.tw email domain 似乎沒提供這個功能；可能是 legacy workspace 方案的關係吧。
    - conversation history 舉例：ossconf@ocf.tw 這個 mail group 就有這個功能，參考 https://groups.google.com/a/ocf.tw/g/ossconf (需 mail group member 身份才看得到內容)
    - mail group 非常適合下列使用情境：
        - 只需要收信功能
        - 需要與眾多使用者大量、平行交換、與對齊資訊
        - 一次性專案
- Rule of thumbs
    - 開給特殊用途的功能性帳號（例如贊助、議程、公關等等）：
        - 只會收信：用 mail group。僅僅只用在註冊某些服務的情境，有時只要收信功能也就很夠了。
        - 需要發信：就可考慮開 new account


## 誰會有 python.tw 的 Email Address

### 常態性

- 歷屆總召（含副總召，if any）
- 歷屆議程與贊助組長/負責人（含副組長）
- 其他對 PyCon Taiwan 社群有特殊貢獻或任務者
- (TBD) 是不是所有組長都配一個 email address? 這要先與 OCF 協商資源可用性才能決定。

也就是每年會新增 3~6 名左右的新帳號。


### 一次性

- 支援部份早期 pycon.tw 名額用罄的帳號轉移使用，大約 3~4 個。


## python.tw email domain 一般使用者須知

- 此帳號雖然說配有 30 GB ，但**建議僅使用收發 email**。
    - 其他服務，例如相簿、 drive 等等，因為我們是搭「非營利組織方案」，使用條款隨時會被 google 更改/中止也不一定。但時候要移植會很痛苦。
- 此帳號有的功能請參考 Google Workspace 各方案說明中「 Google Workspace for Nonprofits 」的方案 https://www.google.com/nonprofits/workspace/compare/

## 總召交接
- 新增當屆總召與 core leads into organizers@pycon.tw
- 提供 g-admin 權限
- 建立 python.tw 帳號給新任總召，與瀏覽 python.tw mail group 權限（特別是 archive@python.tw )
- rename google forum 為當年度

## 其他相關文件

[PyCon TW Mail Group Naming Convention](/xGPsR6WZQpKdZnFzFqePuw)


## 文件版權宣告

PyCon TW Email Domain 管理辦法，2021 © Taihsiang Ho (tai271828), CC-BY-SA-3.0-TW-or-later @ HackMD

