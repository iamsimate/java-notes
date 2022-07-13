###数据结构与算法笔记

**java基础知识**
* 如何在vscode上配置java环境
1、下载以下插件

![](https://files.mdnice.com/user/17204/a53a6e69-fb71-4399-84d2-2111415f71dd.png)

2、下载并安装jdk，在vscode里会直接推送，只需点击进入页面下载即可

![](https://files.mdnice.com/user/17204/82f4d78e-03b7-4517-944d-66faf8a30ba1.png)


3、配置java的环境变量

右键“此电脑”→“属性”→“高级系统设置”→“高级”→“环境变量”

![](https://img-blog.csdnimg.cn/20210313230345963.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl81MTQ1NjU3Mw==,size_16,color_FFFFFF,t_70#pic_center)

![](https://img-blog.csdnimg.cn/20210313230610899.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl81MTQ1NjU3Mw==,size_16,color_FFFFFF,t_70#pic_center)

变量名为“JAVA_HOME”,变量值为刚刚下载jdk的位置，我的位置是

![](https://files.mdnice.com/user/17204/74eba222-0e66-4ad7-b5f1-659e81075391.png)

![](https://files.mdnice.com/user/17204/ca8a59a2-5f4c-4666-85c6-dc0c89e4e4c6.png)

配置完JAVA_HOME之后，双击系统配置下面的“path”→“新建”，把这两个添加进去：%JAVA_HOME%\bin %JAVA_HOME%\jre\bin

![](https://img-blog.csdnimg.cn/20210314094446338.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl81MTQ1NjU3Mw==,size_16,color_FFFFFF,t_70#pic_center)

接下来我们在cmd中查看配置结果，出现下图即配置成功
![](https://files.mdnice.com/user/17204/dea55d66-92fb-4c04-a278-29122613dc5f.png)


* java的基本语法  
 ```java
public class hello{
  public static void main(String[] args){
  System.out.println("hello world");
  int score = 70;
int record=score>=80 ? 0:1;
  System.out.println(record);  
  } \三元判断

}

