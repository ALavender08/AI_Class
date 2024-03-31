# 關於 Jupyter Notebook 的使用方法
> 不定期更新，有什麼問題問我，我之後在補上細節  
> 影片的播放清單　>>　[戳這裡](https://www.youtube.com/playlist?list=PL0-uiq-OFO1ys5PpUKkppPlFdBUOwtQO6)



## 下載各種套件:
<b> 到終端機 (Win+R -> 輸入cmd) (不一定要依序) 輸入以下各行程式: </b>
- pip3 install torch torchvision
- pip install matplotlib
- pip install numpy
- pip install notebook

> 上方程式所載入的套件分別為:
> - torch + torchvision　(別問我為什麼他們一起載， pytorch 官網就這麼寫的)
> - matplotlib
> - numpy
> - notebook (指 jupyter notebook )

## 開啟 Jupyter Notebook

**在終端機直接輸入:**
- jupyter notebook

> 直接打，不要懷疑，這真的是一行程式  
> 程式打完後(應該)會跳到一個網頁

## 使用 Jupyter Notebook 網頁示範影片:
- [在 Jupyter Notebook 中開啟新的 Notebook](https://youtu.be/TZ81gjLyYKg)  
- [直接從 Jupyter Notebook 執行已下載的檔案](https://youtu.be/x0rgQY7Qvyk)  
- [Notebook 中的基本操作使用說明](https://youtu.be/E_7NEvCanpI)
- [如何擷取程式成 PDF 檔 (作業繳交格式)](https://youtu.be/lc8GR-Cc_SY)

> 還有其他問題會補上影片


## 其他:
- **原本在 colab 的程式中有與Google雲端資料夾連動，那部分的程式要改　(沒改也會報錯叫你改)**  
  **我的作法是 : 將整個 cifar-10 資料夾+字型的資料夾下載到電腦，folder那邊的程式改成我下載到電腦的位置，就可以跑程式了**  
  **(這大概是跑最久的部分，60000張照片 :sweat_smile: )**    
  要下載的資料夾如果不知道在哪　>>　[戳這裡](https://youtu.be/3BjOIPf1Gso)
  
- **如果沒辦法安裝模組 ( pip install 的程式會報錯 ) ，可能要先下載 python**  
  下載方式　>>　[戳這裡](https://www.youtube.com/watch?v=Oz9OzteWziU&list=PLG_Hgxt_V3Jh6HRKSfzuPLvLDtoS3lnGs&index=3&t=190s)
