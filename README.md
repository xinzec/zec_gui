## This project is no longer updating and is included in a new project, Miner_GUI. Please kindly get the latest news from the following URL.

## 這個計畫已經停止更新，並且已被一個新計畫Miner_GUI所包含，請從下列網址取得最新的訊息。

## https://github.com/xinzec/miner_gui
 

 

 

 

# zec_gui
This is a simple GUI tool for Zcash miners. The main purpose of this program is to popularize GPU mining to those who are interested in GPU mining but unskilled in computer programs and operations.
Furthermore, we add some features to improve user experiences in monitoring and maintenance.

這是一個針對Zcash挖礦程式開發的圖形化用戶介面工具，此程式主要的目的是將顯示卡挖礦推廣給對顯示卡挖礦有興趣但又不熟悉電腦程式與系統操作的人們。此外，我們加入了一些功能來強化狀態監看與程式維護的體驗。

# Start mining with an easy miner tool
https://drive.google.com/drive/folders/0B4bhHjcQpa3tTjRjZ0RLN2tMRUE?usp=sharing

### easy to use
![p2](https://user-images.githubusercontent.com/29690888/27525910-5c14ec68-5a74-11e7-84da-f074059f848e.png)
![p1](https://user-images.githubusercontent.com/29690888/27518341-2afeaa74-5a10-11e7-903d-afec759aa3c9.png)

## zec_gui 0.0.2
bug fixing

## zec_gui 0.0.1
All the strings in this first release are encode in zh-hant and it is eaiser to use for those who understand Chinese.


### Features:  
auto-restart: Auto-restart the miner if the process was down. We add this feature because it seems some miners will no longer work after CUDA thread exited(e.g. unstable since overclocking).
    
### Currently supported miner:  
EWBF's miner 0.3.4b

### Performance:  
Basically, the performance is as good as the miner without this GUI tool.

### Fee:  
no additional fee from users.

### Notice:  
**64bit Visual C++ Redistributable for Visual Studio 2015** is required. You can download it from https://www.microsoft.com/en-us/download/details.aspx?id=48145 or https://drive.google.com/drive/folders/0B4bhHjcQpa3tVTlTaGEtSW1hV1k
**cudart64_80.dll** is required. It should be there after you install GPU drivers. You can also download it from https://drive.google.com/drive/folders/0B4bhHjcQpa3tVTlTaGEtSW1hV1k

## zec_gui 0.0.2
修正錯誤

## zec_gui 0.0.1
在這個第一版的程式中所有文字都使用繁體中文，讓不熟悉英文的中文使用者可以更容易使用。

### 功能:  
自動重新啟動: 如果挖礦程式出錯，將會自動重新啟動。我們加入此功能是因為，如果CUDA thread出錯(例如 因為超頻導致的不穩定)，部分挖礦程式無法繼續工作。
    
### 目前支持的挖礦程式:  
EWBF's miner 0.3.4b

### 效能:  
基本上，效能與不使用此GUI工具的挖礦程式相同。

### 費用:  
不向使用者收取額外費用

### 注意事項:  
**64位元 適用於 Visual Studio 2015 的 Visual C++ 可轉散髮套件** 是必須的，您可以從以下連結下載安裝檔https://www.microsoft.com/zh-TW/download/details.aspx?id=48145 或者 https://drive.google.com/drive/folders/0B4bhHjcQpa3tVTlTaGEtSW1hV1k
**cudart64_80.dll** 是必須的。安裝完顯示卡驅動程式後應該會出現在電腦中，您也可以從以下連結下載 https://drive.google.com/drive/folders/0B4bhHjcQpa3tVTlTaGEtSW1hV1k
