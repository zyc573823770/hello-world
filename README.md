# 一级标题  
## 二级标题
### 三级标题
*斜体*  
_斜体_  
**粗体**  
__粗体__  
***粗斜体***  
***
分割线  
***  
~~删除线~~  
* 无序1  
* 无序2  
* 无序3  
1. 有序1  
    1. 子列表1  
        1. 子子列表1
            * 需要注意和前面标记有个空格
        2. 子子列表2
    2. 子列表2
2. 有序2  
3. 有序3  
> 这是  
> 一个  
> 块  
  
>这个是  
>>块  
>>嵌套

> 1. 块里有序1  
> 2. 块里有序2  
> * 块里无序1  
> * 块里无序2  
  
1. 有序1  
    > 有序1里有块1  
    > 有序1里有块2  
2. 有序2  
    > 有序2里有块1  
    > 有序2里有块2  
* > 有序1里有块  
* > 无序2里有块  
---
和C一样使用\\来转义  
用\`\`\`包裹显示代码,\`\`\`c++可以高亮
```c++
#include<bits/stdc++>
using namespace std;
int main(){
    cout<<"Hello Markdown"<<endl;
    return 0;
}
```  
---
变量可以用\`变量\`来高亮，`a`  
超链接为\[显示的值\]\(实际访问的地址\)[百度](https://www.baidu.com/)  
使用\<链接\>直接访问链接地址<https://www.baidu.com/>  
只想复制网址就可以用\`\`来把网址框起来，比如   `www.baidu.com`  
***  
## 图片  
本地图片无法调用，需要给出网络连接，最简单的就是直接上传到本项目里，然后链接调用  
\!\[我猜这里是无法加载图片显示的文字\]\(图片的链接\)和网址区别在于前面多一个\!  
![测试图片](https://github.com/zyc573823770/hello-world/blob/master/AttnGAN.png?raw=true)  
可以使用\<img\>标签调整图片属性，下图为`<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">`
<img src="http://static.runoob.com/images/runoob-logo.png" width="50%">  
***
## 表格  
|表头|表头|
|-|-|
|单元格|单元格|
|单元格|单元格|  
  
  
|左对齐左对齐左对齐左对齐|右对齐右对齐右对齐右对齐|居中对齐居中对齐居中对齐居中对齐|
|:-|-:|:-:|
|单元格|单元格|单元格|
|单元格|单元格|单元格|
***  
## 数学公式  
LeTax公式，慢慢学吧，学无止境  
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
