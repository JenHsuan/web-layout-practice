# Description
* 麵包屑: 使用者所在的頁面索引
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/breadCrumbs/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 互動圖文卡片 NO002 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=IocyLERRdko)

# References
### 親代選取器: 排除第一個item的做法
```
.breadcrumb li +  li {
    padding-left: 0;
}

```

### psuedo-element 偽元素
* 一定要有contemt

```
.breadcrumb li +  li:before {
    content: '>>';
    color: #fff;
    margin-left: 20px;
}

```
