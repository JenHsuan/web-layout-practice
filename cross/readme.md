# Description
* 交錯排版
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/cross/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 交錯漂浮版 NO004 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=aN7zFs_AT8s)

# References
### flex-shrink
* 0: 不要壓縮
* 1: 大家被壓縮的比例相同 (預設值)
* [Day24 Flex 空間分配 flex-grow / flex-shrink / flex-basis](https://ithelp.ithome.com.tw/articles/10208741)

### box-sizing: border-box
* [重新認識 CSS - box-sizing](https://titangene.github.io/article/css-box-sizing.html)
* 當width + padding會超出範圍時

### 頭選取器: 選取第一個元素
```
.item > :first-child {
    margin-right: -10%;
}

```

### n選取器: 選取第n個元素
* 可用於操作特定單一元素
```
.item:nth-child(1) .txt{
    background-color: rgb(212, 170, 182, 0.7);
}
```
