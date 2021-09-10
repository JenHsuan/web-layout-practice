# Description
*Footer排版
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/footer/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 網頁頁尾版塊 NO006 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=Y02yl_QQNv0&list=RDCMUCQfjTYYrqxPg5LJmDBUesbQ&index=3)

# References
### flex-grow
* [分配剩餘空間的比例](https://ithelp.ithome.com.tw/articles/10208741)
* 平均分配空間: 先將width設為0, 再將flex-grow設為1

```
.footer-item {
    width: 0;
    flex-grow: 1;
    margin: 0 20px;
}

```
* 佔滿空間
```
.footer-subscribe input[type="text"] {
    width: 0;
    flex-grow: 1;
}

```
### Vertical centering
```

    .footer-subscribe {
        display: flex;
        flex-direction: column;
    }
    .footer-subscribe form{
        display: flex;
        width: 100%;
        margin: auto 0px;
    }

```
