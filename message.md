# Message
## Description
A drone captured the location of the wanted hacker After the police arrived, he must have run away and left a message What is that message? (hint:something is wrong wrong) Fortmat flag: `flag{a-b-c-d-f}`

[UIT.png](https://cnsc.uit.edu.vn/ctf/files/fb8ff59b5ee1cae676c962ec3ffdd176/UIT.png?token=eyJ1c2VyX2lkIjo3MjksInRlYW1faWQiOjI0OSwiZmlsZV9pZCI6MTIzfQ.YW1tWA.Hxa8rcnygkNAAZUx3GJbvgqCuFM)

## Solution
`UIT.png` là một file ảnh chụp từ trên cao UIT thông qua Google Earth.  

![image](https://user-images.githubusercontent.com/44528004/137734197-7f1da946-9dbf-4b12-8e34-035e12c64207.png)  

Vì challenge hint nói là *something is wrong wrong*, nhưng khi mình soi kỹ bản đồ UIT trên Google Earth thì chẳng thấy gì bất thường cả. Do đó mình chuyển qua Google Maps xem thử có gì *wrong wrong* hay không.  

![image](https://user-images.githubusercontent.com/44528004/137734589-f89d62a8-bb22-4e6f-9681-e42465a2d226.png)

Tiếp theo, mình mở thử chế đô street view và xem thử từng view có thể xem trên map.  

![image](https://user-images.githubusercontent.com/44528004/137734669-85c5702e-82dd-4696-8c05-c7d3691736c5.png)

Khi xem tới node này thì mình có phát hiện điều đặc biệt:  

![image](https://user-images.githubusercontent.com/44528004/137734740-e3b1105b-5e44-49f9-958d-d35b1051e977.png)


Trên bảng có dòng chữ sau:  

![image](https://user-images.githubusercontent.com/44528004/137734779-62a44efc-897b-41e1-b16e-9fa9ccb80a52.png)

Với format flag là `flag{a-b-c-d-f}`, mình đoán là mình cần nhập lại các chữ này với `-` ngăn cách giữa các chữ.  
```
flag{Co-gi-ddo-Sai-Sai-Sai-gi-do-dung-dung}
```

Và kết quả là đây là flag đúng!

