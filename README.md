# PyCV2IP
# 環境
## 1. 環境版本
| tool                | version                   |
|---------------------|---------------------------|
| OS                | Windows10                  |
| python              | 3.6.9                     |
| opencv-python       | 4.2.0.32                  |

# 安裝DCNv2 1.7
## 下載DCNv2 1.7 by lbin
    $ git clone https://github.com/lbin/DCNv2.git
## 安裝DCNv2 (若無法安裝先刪除build資料夾)
    $ cd DCNv2 
    $ python3 setup.py build develop

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


