# Lab2-MAXI-and-Stream-interface-
用HLS 實作 MAXI and Stream interface 不同 

基本實作方式與lab1相同
有些地方需要額外設定 請參考以下網址  
https://github.com/bol-edu/course-lab_2/blob/2022.1/2022.1-Workbook-Lab2-KV260.pdf

以下補充幾點網址內尚未說明的部分:
1. MAXI directive 插入請按照下面圖片操作
![image](https://github.com/MODKWODK/Lab2-MAXI-and-Stream-interface-/assets/145253191/d9e9bb8a-a394-4313-b446-49f22b03ae8a)  
  
2. 在FIR.CPP檔案中需要另外設定LOOP次數，才可以得到需要的program time 如下圖line 23  
   ![image](https://github.com/MODKWODK/Lab2-MAXI-and-Stream-interface-/assets/145253191/55e284c8-e1e7-4996-abff-07639fc21053)

3. 最後選擇FPGA時需要根據自己選的BOARD位址更改 (此LAB 兩個BOARD都可以使用 請自行選擇)  
   BOARD：KV260
   ![image](https://github.com/MODKWODK/Lab2-MAXI-and-Stream-interface-/assets/145253191/8df20b0f-8b9b-45f0-a72b-b7a34150c7ba)
   BOARD: PYNQ
   ![image](https://github.com/MODKWODK/Lab2-MAXI-and-Stream-interface-/assets/145253191/b146a93b-6094-4df8-9cd5-d8170d2628b5)





