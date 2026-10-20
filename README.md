# Next B3A · 城巴 B3A 實時到站

Citybus B3A 線實時到站顯示板（富泰邨 ⇄ 深圳灣口岸）。

- 純靜態單頁，無需建置，直接部署在 GitHub Pages
- 資料來源：香港政府 DATA.GOV.HK — `rt.data.gov.hk/v2/transport/citybus/eta`
- 每 30 秒自動更新，亦可手動重整
- 支援深色模式與手機版面

## 站點

| 方向 | 站點 | Stop ID |
| --- | --- | --- |
| 往深圳灣口岸 | 富泰邨 | `003261` |
| 往屯門山景邨 | 深圳灣口岸 | `003208` |

## 本地預覽

```
python -m http.server 8123
# 打開 http://127.0.0.1:8123/
```

資料由香港政府資料一線通（data.gov.hk）以公開 API 提供。
