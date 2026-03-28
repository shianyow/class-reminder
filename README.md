# 上課提醒

在教室投影幕上顯示上課時間與提醒訊息。

## 使用方式

直接開啟頁面：

```
https://shianyow.github.io/class-reminder/
```

也可以透過網址參數預設上課時間和提示文字：

```
https://shianyow.github.io/class-reminder/?time=09:00&note=請提前進教室
```

| 參數 | 說明 | 範例 |
|------|------|------|
| `time` | 上課時間（HH:MM） | `time=09:00` |
| `note` | 提示文字 | `note=請提前進教室` |
| `bg` | 背景色（顏色名稱、hex 色碼、`transparent`） | `bg=darkgreen`、`bg=%23003f7d` |
| `fg` | 字體顏色 | `fg=yellow`、`fg=%23ff6600` |
| `textbox` | 顯示文字底框 | `textbox` |

### OBS 疊加使用

可作為 OBS 瀏覽器來源疊加在其他畫面上：

```
https://shianyow.github.io/class-reminder/?time=09:00&bg=transparent&textbox
```

## 頁面操作

- **點擊時間** → 修改上課時間、上傳背景圖
- **點擊提示文字** → 修改提示訊息
