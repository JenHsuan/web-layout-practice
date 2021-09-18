# Description
* 導覽列
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/square/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 方塊酥版面 NO010 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=Xhhzzc9YZW4)

# References
* 頭選選取器:第一個item與其餘item不同的作法 (width比例等)

```
        .item:first-child {
            width: 50%;
        }
        .item:first-child ~ .item {
            width: 25%;
        }
```
