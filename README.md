# MOSTLink_LoRa_Gateway
# Raspberry Pi
操作說明：
1. 解壓縮後會兩個檔案 gwTxUtility (Raspberry Pi Gateway Utility)，loraConf1 (Config file)。
2. 請先將gwTxUtility及loraConf1這2個檔案傳送到raspberry pi上，gwTxUtility及loraConf1需在同一目錄下。
3. 設定 loraConf1
    * "#"代表此行註解
    * ttyName為LM-130H1插入raspberry pi後在/dev所出現的檔名，請務必輸入正確並包含完整路徑
    * 檔名 (loraConf1) 不可改變
    * pollMac設定Node LoRa MAC。
4. 輸入"chmod 777 gwTxUtility”改變檔案權限，然後再輸入 "sudo ./gwTxUtility”執行程式。
5. 執行後會根據loraConf1設定的Node來執行輪詢資料的動作。

建議使用環境：
- raspberry pi os: 2017-07-05 raspbian jessie
- SD card: SanDisk Ultra microSDHC UHS-I  16G


# Windows
MOSTLink configuration
