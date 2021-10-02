# Description
* 導覽列
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/specialBorder/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 不規則邊緣 NO021 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=7SFuF9XE24s)

# References
* 利用陰影製作多個圓圈
```
   .sec::after {
            position: absolute;
            content: '';
            display: block;
            width: 200px;
            height: 200px;
            background-color: #fff;
            box-shadow: 150px 0px 0px 30px #fff,
                        250px 0px 0px -10px #fff,
                        370px 0px 0px 20px #fff,
                        500px 0px 0px -5px #fff,
                        550px 0px 0px 5px #fff,
                        650px 0px 0px -10px #fff;
            top: 0;
            left: 50%;
            transform: translateY(-30%);
            border-radius: 50%;
            z-index:1;

        }
```
