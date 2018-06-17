

### 第二十八天到第三十天：给爱的人发个邮件吧
* [邮箱输入框提示](http://htmlpreview.github.io/?https://github.com/xszi/ife/blob/master/28_30th/mailtips.html)[`代码`](https://github.com/xszi/ife/blob/master/28_30th/mailtips.html)

### 小结：
* 1、输入框空格去除的方法email_input.value.trim();
* 2、流程图的画法([工具processOn](https://www.processon.com/))，很多时候把流程捋清楚，自然就会写了;
* 3、keyup,keypress,keydown以及oninput的监听用户输入时的区别：
 ！[对照图](https://github.com/xszi/ife/blob/master/28_30th/1.png)
* 4、判断一个字符是否在一个字符串中，以及一个字符串是否在另一个字符串中毒可以使用indexOf 方法；此外，还可以正则表达式。
* 5、slice的用法：slice(startIndex,endIndex),不包括endIndex;
* 6、学习了新的遍历方法：for...of，属于ES6范畴.此外其与for...in的区别如下：
    for in更适合遍历对象，不要使用for in遍历数组;
    for in遍历的是数组的索引（即键名），而for of遍历的是数组元素值;
    使用for in会遍历数组所有的可枚举属性，包括原型。例如上栗的原型方法method和name属性;
    for of 遍历的只是数组内的元素，而不包括数组的原型属性method和索引name.
* 7、web安全与攻防：</br>
    img标签是自动触发而受到攻击的，p标签是引诱出发而受到攻击的的，而iframe则是广告植入攻击的。
    [参考链接](https://blog.csdn.net/ganyingxie123456/article/details/70230486)
* 8、innerText(ie支持)；textContent(火狐，google支持);
* 9、可以通过className和setAttribute为块添加css样式;
* 10、if...else条件判断的使用;
* 11、关于up，down键的疑惑：为什么我最开始想象中的up逻辑却是down呢？</br>
    我的理解就是：因为每次页面更新之后，此时已经是按键之后的selectedTipIndex了，按键为现在减一！)
*景，这次直接复制的代码。
* 13、Esc的使用还是没能选中输入的全部内容。
* 心得：像其中的“先将按键之前的选定选择框的背景色清除”||“当用户输入发生改变的时候，选择状态都重新切回到第一个提示”||“条件语句if...else和switch的选择”||“email—input.value值老是获取不到（enter）”，但是这些东西在自己休息一下，或是借鉴比人的代码之后就解决了。所以在前进过程中，我们时常会迷失，但是我们需要停下来想一想，或者与别人交流交流，而不是你们造车。
