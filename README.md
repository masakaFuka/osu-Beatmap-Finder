# osu! Beatmap Finder

一個可以讓你更快速、更方便尋找 osu! 圖譜的小工具！

<img src="https://i.pinimg.com/736x/fd/2c/d0/fd2cd0e5b4c618e4c4370ddbb4389dde.jpg" alt="osu-Beatmap-Finder" width="200">

## 關於程式

<sub>
本程式使用 <b>Python + QML</b> 開發，並透過 <b>Nuitka</b> 編譯及打包為 Windows <code>.exe</code> 執行檔<br>
本程式<b>不包含病毒、木馬或其他惡意程式碼</b><br>
由於 Python 程式經 Nuitka 編譯及打包後，產生的執行檔、內嵌資源與相關元件可能觸發部分防毒軟體的啟發式偵測，加上沒有購買 Code Signing Certificate（程式碼簽章憑證），因此部分防毒軟體或 VirusTotal 引擎可能會將程式標記為 <code>Unsafe</code>、<code>Malicious</code> 或其他風險項目<br>
若偵測同樣是由上述打包特徵、低檔案信譽或缺少數位簽章所造成，通常屬於 <b>False Positive（誤判）</b>，並不代表程式本身具有惡意行為<br>
Windows SmartScreen 顯示 <b>未知的發行者</b>，則是因為目前沒有受信任的數位簽章，與程式是否包含病毒沒有直接關係
</sub>

## 原始碼

<sub>
本程式目前<b>不公開原始碼</b>，僅提供經 Nuitka 編譯後的執行檔<br>
主要原因是我不希望自己撰寫的程式碼被直接取得、複製、修改後重新發布，或在未經允許的情況下被使用於其他專案<br>
是否公開原始碼與程式是否安全並沒有直接關係，不公開原始碼單純是為了保護自己的程式碼與開發成果
</sub>

<br> ![osu-Beatmap-Finder](https://i.pinimg.com/736x/b6/52/e9/b652e9f5d717397321f8b3eb1c0ff49c.jpg)

### 小知識
<sub>
Code Signing Certificate（程式碼簽章憑證）通常不是一次性買斷，而是以年為單位購買或續期<br>
以個人開發者可申請的方案來說，憑證本身常見價格大約從每年 <b>US$100～300（約 NT$3,200～9,500）</b> 起，實際價格會依憑證供應商、驗證類型與購買年限而有所不同<br>
此外，自 2023 年 6 月 1 日起，公開信任的 Code Signing Certificate，其私鑰必須在符合規範的 Hardware Crypto Module 中產生、保存及使用，因此通常需要搭配符合要求的硬體 Token、HSM、Cloud HSM 或 Signing Service，實際使用成本可能會高於單純購買憑證的價格<br><br>
例如以 <b>SSL.com</b> 的個人 IV Code Signing Certificate 為例，1 年方案約為 <b>US$129（約 NT$4,100）</b>，購買多年方案則會降低平均年費，例如 2 年方案平均約為 <b>US$116.10 / 年</b>、3 年方案平均約為 <b>US$109.65 / 年</b><br>
如果使用 SSL.com 的 <b>eSigner Cloud Signing</b>，Tier 1 年繳方案約為 <b>US$180 / 年（平均 US$15 / 月，約 NT$5,700 / 年）</b>，包含每年 240 次 Signing<br>加上 1 年 IV Code Signing Certificate 後，第一年合計約為 <b>US$309（約 NT$9,800）</b><br><br>
如果改用實體硬體 Token，SSL.com 目前提供的 <b>YubiKey FIPS USB Token</b> 約為 <b>US$379 / 個（約 NT$12,000）</b>，需要另外支付硬體設備費用<br>
另外，依 CA/Browser Forum 現行規範，自 2026年3月1日起，新簽發的 publicly trusted Code Signing Certificate 單張憑證有效期不得超過 <b>460 天</b><br>SSL.com 自身則採用較嚴格的 <b>458 天</b> 上限，並自 2026 年 2 月 27 日起開始套用，因此即使購買多年方案，也不代表會取得一張連續有效數年的單一憑證<br>而是在訂購期間依供應商流程重新簽發新的憑證
</sub>

<br> ![osu-Beatmap-Finder](https://i.pinimg.com/736x/6a/89/ba/6a89baaba9fff614ceb340a216e566f3.jpg)
