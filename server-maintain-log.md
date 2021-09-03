# 伺服器維護日誌
[![hackmd-github-sync-badge](https://hackmd.io/6all3-thSN6ITI5STobGxg/badge)](https://hackmd.io/6all3-thSN6ITI5STobGxg) [![](https://badgen.net/badge/icon/GitHub/black?icon=github&label)](https://github.com/2D2C-TW/hackmd.io/blob/main/server-maintain-log.md) [![2d2c-discord](https://badgen.net/discord/members/2d2c)](https://discord.gg/2d2c)

## 伺服器狀態 [![24h-uptime](https://badgen.net/uptime-robot/day/ur1372305-af90c383417375fc57522eb0)](https://status.2d2c.org)

### 主入口主機 [![status](https://badgen.net/uptime-robot/status/m788686890-1c7de12ab6a67e885a4ca7db)](https://stats.uptimerobot.com/nmxvpuG8qv/788686890) ![](https://badgen.net/badge/address/mc.2d2c.org/blue)


### 副入口主機 [![status](https://badgen.net/uptime-robot/status/m788686904-3542d91c79fc8c9ffca59c4f)](https://stats.uptimerobot.com/nmxvpuG8qv/788686904) ![](https://badgen.net/badge/address/mc2.2d2c.org/blue) 


### 後端主機 [![status](https://badgen.net/uptime-robot/status/m788686910-d8c4afbddfaedf13b186f861)](https://stats.uptimerobot.com/nmxvpuG8qv/788686910) ![](https://badgen.net/badge/locate/Taiwan/cyan)


## 定期維護

### 🟢 R1-資源一服 每周日零點定期刷新

#### #5 2021/09/05 00:00

- 🚧 **影響**
  - `R-1`
- ⏰ **耗時**
  - 15 分鐘
- 📑 **事由**
  - 資源服刷新

## 維護排程預告

### 暫無

## 過去的維護

### 🔴 2021/09/02 20:30 ~ 2021/09/02 20:45

- 🚧 **影響**
  - `大廳` `S-1` `S-2` `S-3` `S-4` `S-5` `R-1`
- ⏰ **耗時**
  - 15 分鐘
- 📑 **事由**
  - 生效伺服器運行配置，修正生怪異常
  - 修改容器記憶體容許上限


### 🟡 2021/09/02 00:00 ~ 2021/09/02 02:00

- 🚧 **影響**
  - `大廳` `S-1` `S-2` `S-3` `S-4` `S-5` `R-1`
- ⏰ **耗時**
  -  120 分鐘
- 📑 **事由** 
  - 換下同批雙通道記憶體，以便送修
  - 更新個伺服器插件與運行核心
  - 更新伺服器管理後台
 

### 🟢 2021/08/30 12:08 主入口目前已切換至新VPS(AWS-JP線路)

### 🔴 2021/08/29 11:02 主入口(`mc.2d2c.org`)通訊異常

### 🟢 2021/08/29 00:00 資源服刷新#4

### 🟢 2021/08/22 00:30 資源服刷新#3

### 🔴 2021/08/21 23:11

- 🚧 **影響**
  - `S-2`
- ⏰ **耗時**
  - 不適用(即刻執行)
- 📑 **事由**
  - 排查S-2異常問題，暫時停機進行一次完整備份

### 🔴 2021/08/21 22:56

- 🚧 **影響**
  - `S-2`
- ⏰ **耗時**
  - 不適用(即刻執行)
- 📑 **事由**
  - 排查S-2異常問題，緊急重啟進行測試

### ~~🟡 2021/08/14 20:00 CST ~ 2021/08/14 22:30 CST~~*已取消*

- 🚧 **影響** 
  - `S-4` `R-1`
- ⏰ **耗時**
  - 150 分鐘
- 📑 **事由**
  - 為配合 UHC 活動舉辦，釋放部分運算與連線資源

### 🟢 2021/08/13 00:00 資源服刷新#2

### 🟢 2021/08/09 00:00 資源服刷新#1

### 🔴 2021/08/05 00:30 ~ 2021/08/05 01:30
  
- 🚧 **影響**
  - `主入口` `副入口` `S-1` `S-2` `S-3` `S-4` `S-5`
- ⏰ **耗時**
  - 60 分鐘
- 📑 **事由**
  - 網路設備維護
  - 更新管理後台
  - ~~暫時停用 BetterSleep4 插件 (以原生 `playersSleepingPercentage` [30%] 暫時替代)~~
<br>_將持續觀察，若持續有一些異常狀況，將會於下次維護一併排除。_</br>
  - 入口整合 (使用相同的Velocity Proxy管理低延遲與一般入口的連線)
  - 變更 container image

### 🟡 2021/08/02 00:30

- 🚧 **影響**
  - `主入口` `副入口` `S-1` `S-2` `S-3` `S-4` `S-5`
- ⏰ **耗時**
  - 120 分鐘
- 📑 **事由**
  - 開放 `R-1 資源一服`
  - 升級伺服器執行檔至1.17.1
  - 更新多項插件
  - 修改新的聊天訊息樣式
  - 加入基岩版功能支援(尚未開放)

<!--

### 🔴🟡🟢 2021/xx/xx 00:00

- 🚧 **影響**
  - `主入口` `副入口` `S-1` `S-2` `S-3` `S-4` `S-5`
- ⏰ **耗時**
  - x 分鐘
- 📑 **事由**

-->