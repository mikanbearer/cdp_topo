# topo

將cisco設備的terminal output轉換成topology的小工具
內容必須包含show ip interface brief、show cdp neighbors

輸出為中繼的.xlsx與最終的html

d3的template參考[https://github.com/semonalbertyeah/d3-network-topology](https://github.com/semonalbertyeah/d3-network-topology)


使用方法：

* 1 將terminal output log放進./config
* 2 python topo_generator.py
* 3 查看./output內產生的檔案 
