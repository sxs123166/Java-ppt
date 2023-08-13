# Java执行原理



###### 1.编程语言发展历程

- 机器语言
- 汇编语言
- 高级语言



###### 2.原理

1. 经过javac命令将java源文件编译生成相应的class文件
2. 使用java命令之后会由jvm中的类装载器将class文件装载到内存中
3. jvm中的执行引擎负责读取class文件中的指令
4. 执行引擎将指令发送给OS（operating system，操作系统）
5. 操作系统再去调用相应的device（设备，例如打印机）

![](/Users/beifengchuiluoyanlei/Documents/Java/Java编译过程.png)