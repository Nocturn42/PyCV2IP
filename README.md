# PyCV2IP
# 操作介面
## 功能
| 按鈕                | 敘述                   |
|---------------------|---------------------------|
| 選擇圖片                | 開啟資料夾選擇圖片                  |
| 直方圖等化              | 進行直方圖等化                     |
| 直方圖匹配       | 進行直方圖匹配                  |

# Datasets & Models
## 須在 Swin_JDE/src/lib/opt.py 中以及各數據集json檔中修改數據集路徑
## 1.將FTP中的資料庫放入此資料夾
### 1.1 從FTP中取得資料庫與訓練權重
`實驗室成員 -> 冠宇 -> Datasets -> datasets.zip`
`實驗室成員 -> 冠宇 -> Models -> models.zip`
### 1.2 解壓縮 
#### 將 datasets.zip & models.zip 放入 Swin_JDE中
    $  unzip datasets.zip 
    $  unzip models.zip 


