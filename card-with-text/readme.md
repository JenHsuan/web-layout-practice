# Description
* 基本的卡片排版, 以及滑鼠移動時浮現的文字
* ![Preview](https://raw.githubusercontent.com/JenHsuan/web-layout-practice/master/card-with-text/preview/preview.png)

# Material
* [金魚都能懂的網頁切版 : 互動圖文卡片 NO002 | 切版教學 | HTML教學 | 網頁教學 | 網頁切版](https://www.youtube.com/watch?v=IocyLERRdko)

# References
### position: absolute
* Condition 1: if the position style of the parent component is default (static) - It will perform as fixed
* Condition 2: if the position style of the parent component is one of the following position style - The absolute component will move with the parent component when scrolling the window
* [Day 31 of #100DaysOfCode:Review CSS-Position](https://dev.to/jenhsuan/day-31-of-100daysofcode-review-css-position-4ba5)

### Centering
* One item
```
.vertical-container {
  display: -webkit-flex;
  display:         flex;
  -webkit-align-items: center;
          align-items: center;
  -webkit-justify-content: center;
          justify-content: center;
}
```
* Multiple items
```
.vertical-container {
  display: -webkit-flex;
  display:         flex;
  -webkit-justify-content: center;
          justify-content: center;
  flex-direction: column;
}
```
* [Day 34 of #100DaysOfCode: Review CSS-Three ways to center the HTML element](https://dev.to/jenhsuan/day-34-of-100daysofcode-review-css-three-way3-to-center-the-html-element-266i)

### Fake image service
* [fakeimg](http://fakeimg.pl/500x400)
* [picsum](http://picsum.photos/500/400)

### Transition
### Set hot keys for VS code
* [DevTools — Tips for Using Visual Studio Code](https://medium.com/a-layman/devtools-tips-for-using-visual-studio-code-e50f65a7f996)
