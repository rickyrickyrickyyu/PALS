# PALS 2025 Navigator

**Pediatric Advanced Life Support (PALS) 2025** 即時急救引導工具，基於 AHA/台灣混合 Guidelines。

單一 HTML 檔案，無需安裝，手機 / 平板 / 桌機直接開啟即可使用。

## Features

- **體重導向劑量計算** — 所有藥物與電擊能量皆依體重 (J/kg, mg/kg) 自動計算
- **四大模組**：VF/pVT、PEA/Asystole、Bradycardia、Tachycardia
- **CPR 計時器** — 2 分鐘循環，110bpm 閃爍節拍器
- **Epinephrine 計時器** — 3-5 分鐘提醒
- **即時事件記錄** — 含時間戳，一鍵複製 / SOAP 格式輸出
- **深色 / 日間模式** 切換
- **手機優化** — 單手操作設計

## Protocols (PALS 2025)

| Module | Key Parameters |
|--------|---------------|
| VF/pVT | Shock: 2→4→≥4 J/kg |
| Cardiac Arrest | Epi: 0.01 mg/kg (max 1mg) q3-5min |
| Anti-arrhythmic | Amiodarone 5 mg/kg / Lidocaine 1 mg/kg |
| Bradycardia | HR<60 + Poor Perfusion → CPR → Epi → Atropine 0.02 mg/kg |
| Tachycardia (Unstable) | Sedation 0.1 mg/kg → Cardioversion 0.5-1 / 2 J/kg |
| Tachycardia (SVT) | Adenosine 0.1→0.2 mg/kg |

## Usage
            
1. 開啟 `index.html`（或使用 [GitHub Pages 線上版](https://rickyrickyrickyyu.github.io/PALS/)）
2. 輸入病患體重 (kg) → 點擊 START
3. 輸入心率 (可選) → 選擇對應模組
4. 依畫面引導操作
5. 結束後複製記錄

## Deployment

### GitHub Pages
1. Fork 此 repo
2. Settings → Pages → Source: `main` branch, `/ (root)`
3. 等待部署完成後即可透過 `https://yourusername.github.io/PALS/` 存取

### Local
直接用瀏覽器開啟 `index.html` 即可。

## Disclaimer

> ⚠️ 本工具僅供教學與臨床輔助參考，**不可取代專業醫療判斷**。使用者應具備 PALS 認證資格。藥物劑量請以最新指引及院內規範為準。

## License

MIT License — 詳見 [LICENSE](LICENSE)
