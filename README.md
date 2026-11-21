# Pocket Joy Studio 工作室首頁

`https://pocketjoystudio.com/`（繁中）、`/en/`（英文）。用 GitHub Pages 公開，這個 repo 只有網頁檔案（HTML、CSS、圖片），沒有任何 App 或伺服器的程式。

- 網域 pocketjoystudio.com 在 Cloudflare，是工作室共用網域：信箱（sonia@ 收信、Resend 寄信）、`meow.`（喵的又要上班了的挽回信回覆）都在用。主網域只加 GitHub Pages 的 A／AAAA 紀錄，不要動 MX、TXT 和其他子網域。`CNAME` 檔不要刪。
- 每個 App 的官網在各自的子網域、各自的 repo：

| App | 官網 |
|---|---|
| 喵的，又要上班了 Meowshift | https://meowshift.pocketjoystudio.com/ |
| 額度雷達 QuotaRadar | https://quotaradar.pocketjoystudio.com/ |
| 職缺體檢 | https://jobcheck.pocketjoystudio.com/ |
| 提醒喵 RemindCat | https://remindcat.pocketjoystudio.com/ |
| 喵途 Meowmoir | https://meowmoir.pocketjoystudio.com/ |
| 投資袋著走 | https://investtogo.pocketjoystudio.com/ |

- **App 上架或下架時要改**：兩個 `index.html` 裡那張卡片的標籤（`tag soon`「即將上架」）和商店按鈕。
- 圖：`assets/img/logo.jpg`、`hero.jpg` 來自工作室的刺繡布章大頭貼和 X 橫幅 A；`assets/icons/` 是各 App 的圖示縮成 192px；`og.jpg` 是分享預覽圖。
- 沒有外部字型、沒有追蹤碼、不需要 build。
