# Description
* 導覽列
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/timeline/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 時間軸 NO019 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=AiR22hCQOGs)

# references
* 上下左右交錯排版
```
        .timeline li:nth-child(odd) {
            float: left;
            padding-right: 100px;
        }
        .timeline li:nth-child(even) {
            float: right;
            padding-left: 100px;
            transform: translateY(50%);
        }
```

* 垂直居中
```
        .timeline li:before {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background-color: #aaa;
            z-index: 2;
            top: 0;
            bottom: 0;
            margin: auto;
        }
```
