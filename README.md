pikia-1
===================================  
简单的图像搜索
    
主页地址  
-----------------------------------  
  http://localhost:8080/picSearch/d/index
### Tomcat server.xml 需要加入: 
      <Context crossContext="true" docBase="/home/methew/workspace/pic" path="/picSearch/upload" reloadable="true"/>	        docBase  本机放置图片的地址
      
      小标题的格式如下 ### 小标题<br />  
      注意#和标题字符中间要有空格  
      
### 注意!!!下面所有语法的提示我都先用小标题提醒了!!!   
      
### 单行文本框  
    这是一个单行的文本框,只要两个Tab再输入文字即可  
              
### java.lang.ClassNotFoundException: org.springframework.web.context.ContextLoaderListener  
    解决方法:
    项目 —> 属性 -> Deployment Assembly -> Add -> Java Build Path Entries -> 选择Maven Dependencies -> Finish -> OK
      
    ### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧  
        public class HelloWorld {  
      
          /**  
          * @param args  
       */  
       public static void main(String[] args) {  
       System.out.println("HelloWorld!");  
      
       }  
      
        }  
### 链接  
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />  
2.[点击这里我你可以链接到我的博客](http://guoyunsky.iteye.com)<br />  
      
###只是显示图片  
![github](http://github.com/unicorn.png "github")  
      
###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com  
[![image]](http://www.github.com/)  
[image]: http://github.com/github.png "github"  
      
### 文字被些字符包围  
> 文字被些字符包围  
>  
> 只要再文字前面加上>空格即可  
>  
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
> 但> 只能放在行首才有效  
      
### 文字被些字符包围,多重包围  
> 文字被些字符包围开始  
>  
> > 只要再文字前面加上>空格即可  
>  
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字  
>  
> > > > 但> 只能放在行首才有效  
      
### 特殊字符处理  
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />  
你想换行的话其实可以直接用html标签\<br /\>  
