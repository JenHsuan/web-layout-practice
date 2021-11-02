# Description
* 文字排版
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/article_4/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 文字排版-中集 NO023 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=YYHqbVVXIGM)

### Horizontal Centering
```
        .container {
            position: relative;
        }
        .container h1 {
            width: 400px;
            position: absolute;
            left:0;
            right: 0;
            top: 0;
            margin: auto;
        }

```

### 首字大寫
```
.container p:first-child::first-letter{
            font-size: 40px;
            float: left;
            padding-right: 6px;
        }

```
