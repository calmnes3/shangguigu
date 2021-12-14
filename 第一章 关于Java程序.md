# 第一章 关于Java程序

#### 1.bit（比特）是计算机最小的存储单位；最基本的存储单元byte（字节）；

  **一个字节有八个比特组成；**

千字节（kilobyte，KB）= 1024B

兆字节（megabyte，MB）= 1024KB

千兆字节（gigabyte，GB）= 1024MB

万亿字节（terabyte，TB）= 1024GB

#### 2.java语言运行机制

用户--字节码文件--jvm--操作系统--硬件

#### 3.jdk、jre、jvm关系

JDK=JRE+开发工具集

JRE=JVM+Java SE标准类库

#### 4.文档注释   **/\**  \*/**

**命令：javadoc -d 文件名 -author -version XXX.java**

#### 5.**API(应用程序编程接口)   IDE（集成开发环境）**

#### 6.小结

###### 1.Java程序编写-编译运行过程

编写：我们将编写的Java代码保存在以".java"结尾的源文件中

编译：使用javac.exe命令编译我们的Java源文件。格式javac源文件名.java

运行：使用java.exe命令解释运行我们的字节码文件。格式：java 类名

###### 2.在一个Java源文件中可以声明多个class。但是，只能最多有一个类声明为public的。

而且要求声明为public的类的类名必须与源文件名相同。

###### 3.程序的入口是main()方法。格式是固定的。

###### 4.输出语句：

System.out.println();   先输出数据然后换行

System.out.print();     只输出数据

###### 5.每一行执行语句都以“；”结束。

###### 6.编译的过程：编译之后，会生成一个或多个字节码文件。字节码文件的文件名与Java源文件中的类名相同.

###### 7.配置环境path变量的目的：希望Java工具（javac.exe，java.exe）在任何路径下都能执行成功