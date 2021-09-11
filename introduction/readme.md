
# Description
* 內容介紹排版, 以及滑鼠移動時的動畫
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/introduction/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 人員介紹卡片 NO003 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=2Qs0EuqJIYA)

# References
### 三角型做法
1. 利用border-right, border-left, border-top (設為transparent)
2. 將pseudo-element的position設為absolute, 父元件設為relative

```
    .item .txt:before {
        content: '';
        position: absolute;
        width: 0;
        height: 0;
        left: 0;
        top: 0;
        border-top: 50px solid transparent;
        border-left: 184px solid #fff;
        border-right: 184px solid #fff;
        transform: translateY(-100%);
    }
```
