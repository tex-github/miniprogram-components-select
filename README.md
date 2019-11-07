# miniprogram-components-select
**效果图**<br>
![效果图](https://github.com/tex-github/miniprogram-components-select/blob/下拉组件Select/2dc2e7c34d617c85a1f4666fe9b95b2a_0_wx_fmt%3Dpng.png)

在你页面中的json中添加引用，路径根据你的实际工程目录来写。<br>
```
{
  "usingComponents": {
    "Select": "/components/select/select"
  }
}
```

**wxml中**<br>
```
<Select title="类别" options="{{optionArry}}" isRequired="true" bind:mySelectItem='onSelectItem' name='formkey' showkey='name' />
```
**tips:**<br>
可以动态传递对象数组在组件中显示的属性名，类似picker的range-key;使用cover-view解决当组件展开时遮住原生组件时的点击击穿问题。
  
