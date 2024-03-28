# 内容
## CSS
层叠样式表，像重叠的峰峦一样，看到的是叠在前面的。
![alt text](img/image16.png)
怎么找到它？通过选择器去找到对应的元素
## 选择器
- class用.，id用#，普通标签直接写，多个标签用逗号隔开![alt text](img/image1.png)
- 要选中某个标签中的某个class，如h1的class，用h1.class表示![alt text](img/image2.png)
- 后代选择器，要精确控制的话，父级选择器后空格接上子级，如 ul空格li![alt text](img/image3.png)
- 子元素选择器，中间没有隔着别的层级，要精确控制，用>连接，如ul>li![alt text](img/image4.png)
- 相邻兄弟选择器，用+连接，会选中后面相邻的兄弟，如#d+div，会选中id=d的元素相邻的div![alt text](img/image5.png)
- 普通兄弟选择器，会选中后面的所有普通兄弟![alt text](img/image6.png)
## 伪元素
用双冒号表示，一个选择器只能有一个伪元素
- p::first-letter,选中第一个字母进行控制![alt text](img/image7.png)
- p::first-line,选中第一行进行控制，第一行会随着窗口的大小改变，改变后会重新渲染![alt text](img/image8.png)
- ::marker,列表的标记框![alt text](img/image9.png)
- ::selection,所选中的文本![alt text](img/image10.png)
- p:nth-of-type(2)::selection,第二段被选中的部分，nth-of-type是指同类型标签的位置，前面的p让他精确到p标签![alt text](img/image11.png)
- ::placeholder,选中input输入框的placeholder![alt text](img/image12.png)
## Style
样式有放在标签里的属性，放在head里的标签，单独的css文件
应用的样式取决于最近的，就近原则![alt text](img/image13.png)

- 盒子模型box-model

    padding内间距，margin外间距，border厚度

    单独写时，参数的顺序是上右下左，2个参数顺序为上下，左右

    div块级元素，默认独占一行，span没有块级属性，行内元素内容多大就多大

- pre标签

    包裹的内容以原来的样子展示

* * *
感兴趣的样式
![alt text](img/image14.png)![alt text](img/image15.png)