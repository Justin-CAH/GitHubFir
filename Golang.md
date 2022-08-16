# Golang

## 一、GoLang环境安装

###  （一）官网地址安装包

​      地址：<https://go.dev/>

###       (二)   配置环境变量

   1.系统变量配置：变量->GOPATH  值：项目地址（随意）

   2.变量->GOROOT  值：msi文件安装后install的目录

   3.变量：path  值：%GOROOT%\bin

## 二、GoLang编写第一次

### （一）.如下图：

![1659361514835.jpg](C:\Users\CAH\Pictures\1659361514835(1).jpg)

### （二）.代码解释：

- Go程序的后缀是 .go

- Go项目结构通常采用：GOPROJECT -> src -> go_code -> 项目名称

- <u>package main</u>：表示test01.go文件所在包是main，在go中，每个文件都必须归属于一个包

- <u>import "fmt"</u>表示引入了一个包，包名为fmt，引入该包后就能使用其函数，比如fmt.Println
- <u>func main() {</u>：这是一个关键字，后面对应是一个函数。main是主函数，即程序的入口。
- <u>fmt.Println(“hello, My name is Eastmount!”)</u>：调用fmt包中函数输出内容。

### （三）.执行go文件

  3.1  可go build 文件名，将其打包成exe运行，打包即可任意地方用dos命令运行无需go环境，但相比源文件要大。

  3.2   go run 文件名

## 三、 Golang转义字符和编码风格

### 1.如下图：

![1659362605928.jpg](C:\Users\CAH\Pictures\1659362605928.jpg)

### 2.使用gofmt自动对齐（gofmt -w 文件名）

## 四、Dos常用指令

### 1.常用命令：

1. dir : 查看当前目录

2. cd ... : 切换上一级目录

3.  cd  \  :  切换到根目录

4.  md ：新建文件夹 

5. rd  :删除目录及子目录文件 

   ### 2.文件操作指令：

   - 新建一个空文件：type nul>eastmount.txt
   - 新建或追加内容到文件：echo hello > eastmount.txt
   - 显示文件内容：type eastmount.txt
   - 复制文件并重新文件名：copy eastmount.txt d:\yxz.txt
   - 移动文件：move d:\yxz.txt c:\
   - 删除指定文件：del d:\yxz.txt
   - 删除指定目录中txt结尾所有文件：del *.txt











