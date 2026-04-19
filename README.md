# 上課提醒

在教室投影幕上顯示上課時間與提醒訊息。

## 使用方式

直接開啟頁面：

```
https://shianyow.github.io/class-reminder/
```

## 網址參數

| 參數 | 說明 | 預設 | 範例 |
|------|------|------|------|
| `time` | 上課時間（`HH:MM`） | `--:--` | `time=09:00` |
| `note` | 提示文字 | `請提前 5 分鐘進教室` | `note=請提前進教室` |
| `bg` | 背景色（名稱、hex、`transparent`） | 深藍 `#003f7d` | `bg=darkgreen`、`bg=transparent`、`bg=%23003f7d` |
| `fg` | 字體顏色（名稱或 hex） | 白色 | `fg=yellow`、`fg=%23ff6600` |
| `textbox` | 顯示文字底框，可選填透明度 0~1 | 不顯示（啟用後預設 0.3） | `textbox`、`textbox=0.6` |
| `shadow` | 啟用文字陰影 | 不啟用 | `shadow` |

> 使用 hex 色碼時，`#` 需編碼為 `%23`。

## 常見組合範例

**基本使用**

```
?time=09:00&note=請提前進教室
```

**OBS 疊加（透明背景 + 底框 + 陰影）**

```
?time=09:00&bg=transparent&textbox&shadow
```

**自訂配色**

```
?time=09:00&bg=darkgreen&fg=white
```

**投影在圖片上（半透明底框增加對比）**

```
?time=09:00&bg=transparent&textbox=0.6&shadow
```

## 頁面操作

- **點擊時間** → 修改上課時間、上傳背景圖
- **點擊提示文字** → 修改提示訊息
