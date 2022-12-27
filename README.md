# 前端笔记
> Front-end blog

## 一、vue 和 react 的优缺点！

React和Vue相当于汽车自动挡和手动挡的区别

Vue:自动挡，入门门槛低，方便，省心，缺点是官方依赖度高，技术自由度相对较低
React:手动挡，自由度高，注重技术机械驾驶体验感，缺点就是入门门槛高

## 二、杀手级的javascript单行代码

```javascript
Math.random().toString(36).slice(2); // 生成随机数

const filename = 'file.docx';
filename.substring(filename.lastIndexOf('.')); // 取文件名后缀
```

## 三、html 本地调用

```html
<a href="mailto:xxxx@163.com?subject=[此处标题]&body=[此处内容]">单击此处打开邮箱</a>
```

## 四、判断数据类型
```javascript
Object.prototype.toString.call('xxx')
```


## 五、toFixed 精确计算，四舍五入精度问题

[1.Javascript toFixed Not Rounding](https://stackoverflow.com/questions/10015027/javascript-tofixed-not-rounding)

[2.JavaScript 中精度问题以及解决方案](https://www.runoob.com/w3cnote/js-precision-problem-and-solution.html)
