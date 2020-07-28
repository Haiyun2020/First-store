#  标题的用法 `#`
# 一级标题  
##  二级标题
### 三级标题
#### 四级标题
##### 五级标题 
备注 # 符号需要再英文输入法状态下输入，并且符号和标题之间需要有一个以上空格 ，文件名后缀一定是.md
# GitHub上如何创建文件夹`/`
# 项目符号`*+空格，按tab分级`
* 首先是进入所要创建文件夹的库中点击Create new file
  * 接着是继续输入当我们按下一个“/”后就变成下面的样子了，此时new file 就变成了一个文件夹了
    * 后一步（因为github不允许创建空文件夹）我们需要在新文件夹下创建一个文件，至于什么文件随意
      * 创建了文件后拉到最后，点击Commit new file
        * 备注：如果删除文件夹下面的所有文件，文件夹也会消失（github不允许创建空文件夹）    
   
[创建文件夹方法-引自](https://www.cnblogs.com/wuyepeng/p/9742690.html"悬停显示文字")    【`空行分段`高亮】
# 文字超链接`[文字](地址/网址)  `
[我的GitHub](https://github.com/Haiyun2020"悬停显示文字")  
 # 插入网络图片 `![图片名]（图片地址）`
![图片](https://upload-images.jianshu.io/upload_images/1874524-b9be15e31c25eba2.jpg)  
或 ![图片名][1]  
[1]:http://latex.codecogs.com/gif.latex?\prod%20\(n_{i}\)+1
# 缩进 `>`
>一盏灯， 一片昏黄； 一简书， 一杯淡茶。 
>>守着那一份淡定， 品读属于自己的寂寞。 
>>>保持淡定， 才能欣赏到最美丽的风景！ 保持淡定， 人生从此不再寂寞。
# 单行代码引用
`hellow world`  
在代码前后加上\`
# 多行代码引用 
```
let pauseBtn = UIButton(frame: CGRect(x: 50, y: HEIGHT-100, width: 100, height: 50))
pauseBtn.addTarget(self, action: #selector(btnClick(_:)), for: .touchUpInside)
pauseBtn.setTitle("暂停", for: .normal)
pauseBtn.tag = 11
pauseBtn.setTitleColor(UIColor.black, for: .normal)
```
在代码前后加上```
# 粗体和斜体
    *斜体字* 
    **粗体字** 
    ***加粗斜体字***
    
   # 表格 `| 和-减号`
   |第一列|第二列|第三列|
   |----|----|----|
   |第二行|第二行||
   |第三行|第三行||
   
`备注：行数由第一行|间的间隔以及第二行的|--决定,两行|数量一样多--表示横线，根表格分开加一个空格`
# 分割线`三个连续*`
***
# 删除线`~包围要删除内容`
~删除~  
# 文字背景高亮\`包围
# 换行`<br> ,Tab缩进`
## 单行文本
换行,注意\<br>前加了反斜杠转译（右斜），或者用符号\``进行原样输出<br> 
使用两个Tab符实现单行文本。
## 多行文本
多行文本和单行文本异曲同工，只要在每行行首加两个Tab  
句尾两个空格可以分段   空行分段  
 1.  
 2.  
 3.  
# 参考
  [GitHub的ReadMe.md文档编辑语法](https://www.jianshu.com/p/9ab92efc286a)  
  [GitHub上README.md排版样式教程](https://blog.csdn.net/u012067966/article/details/50736647)
