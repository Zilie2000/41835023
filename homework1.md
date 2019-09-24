
# INTRO TO IT       Homework    

***
## 2:14 What is IT
>**IT concept**   
- *the use of digital technology,like computers and the internet, to store and process data into useful information*  
  使用数码技术，如用电脑和英特网，去存储和处理数据，使之成为有用的信息   
- *powerful and valuable tools to help people get their work done and enable us to connect with each other*   
  强有力且有价值的工具：可以帮助人们完成工作和更好的与人联系   
- *ranging from hardware technician to replace and repair components to desktop support personnels who make sure the users can use softwares properly*   
  硬件工程师的工作有更换或维修原件，技术支持工作人员的工作是使用户的软件畅快运行
- *it isn't just about building computers and using the internet,it's really about the people,by helping people solve meaningful problems*     不是仅仅只有安装电脑和使用英特网，其实it更多的是有关人们，帮助他们解决有意义的问题 
- *vital tool of modern society*   
  当代社会的中的一种关键工具

***
## 40:03 computer architecture overview
- **four main layers**   

> *hardware layer* 硬件   
  made up of the physical components of a computer   
  组成电脑的物理部件，比如手机，电脑，显示器，键盘 
  
> *operating system* 操作系统  
  allows hardware to communicate with the system   
  搭建硬件与系统的沟通，操作系统允许硬件和系统的一起使用而不管其来自哪里。有苹果操作系统，微软的操作系统，安卓操作系统等等。   
  
> *software* 软件    
  how we as humans interact with our computer      
  使用者通过软件与电脑交互，无论是移动应用程序，网络浏览器，文字处理器还是操作系统本身
  
> *users* 用户   
  interacts with the computer  
  用户可以与计算机交互，能操作，维护甚至编写计算机程序，是最重要的层之一    
 

***
## 47:48 programs and hardware
>**programs** 程序  
- instructions that tell the computer what to do   
  告诉计算机做什么的指令  
  
  EDB(external data bus)外部总数据线    
  CPU与外部数据传输的通道。外部数据总线一次可传输二进制数据的位数越大，CPU与外部交换数据的能力越强。有32位，64位等  
  
  CPU 中央处理器   
  功能主要是解释计算机指令以及处理计算机软件中的数据.负责读取指令，对指令译码并执行指令的核心部件。   
  包括几个部分，控制器、运算器，高速缓冲存储器，外部数据总线。   
  
  RAM
  主存，是与CPU直接交换数据的内部存储器。可以随时读写，速度很快，作为运行中的程序的临时数据存储介质。   
  可以随时从任何一个指定的地址写入或读出信息。       
  
  Register  
  寄存器是中央处理器内的组成部分。是有限存贮容量的高速存贮部件，它们可用来暂存指令、数据和地址。
  
  Address Bus  
  地址总线属于一种电脑总线，是由CPU或有DMA能力的单元，用来沟通这些单元想要存取（读取/写入）电脑内存元件/地方的实体位址。地址总线的位数决定了CPU可直接寻址的内存空间大小，
  
  Memory controller chip
  内存控制器是计算机系统内部控制内存并且通过内存控制器使内存与CPU之间交换数据的重要组成部分。内存控制器决定了计算机系统所能使用的最大内存容量、内存BANK数、内存类型和速度、等等重要参数，决定了计算机系统的内存性能。
  
  Cache  高速缓冲存储器   
  位于CPU和主存储器DRAM之间，速度很高的存储器，Cache的功能是提高CPU数据输入输出的速率。    
  
**cpu和ram的工作原理**   
将程序(program)复制到内存(ram)中，ram是电脑的短期记忆,它存储信息且可以让cpu很快读写。cpu处理信息和从硬盘中读取二进制数字。外部数据总线（edb）作为以跟连接电脑的数据线，像一个巴士，当传输数据时，数据处于开的状态表示为1，关闭（off）则为0。edb有不同的一次可传输的二进制数据的位数，位数越大传输能力越强。传输的数据存储在cpu的寄存器（register）之中，寄存器在cpu的内部，cpu有不同数量的多个寄存器。内存控制器（MCC)是cpu和ram之间的桥梁，地址总线（AB)是cpu和MCC之前的链接桥梁。cpu发送数据的地址给mcc，却不是数据本身，mcc拿到了地址，并且找到数据，数据通过EDB传输给cpu。cpu也会使用高速缓冲存储器（cache），cache速度很快，它存储经常使用的数据。cache有不同的等级L1,L2,L3。

***
## 1:23:41 OS intro
>operating system 操作系统
- the whole package that manages our computer's resources and lets us interact with it  
  管理我们电脑资源并是我们与之交流的一个系统包
  
**two main parts**   
*kernel space* 内核空间   
是操作系统的核心，直接与硬件进行通信
- process manager 进程管理器    
  管理程序运行的顺序，占用的资源，运行的时间等      

- memory manager 记忆管理器   
  最大化记忆使用效用，使电脑应用有足够的空间运行   

- file manager 文件管理器   
  管理、存储文件，文件可以是图片，音频，可以用folders,directorys 以管理文件致使其不混乱    

- I/O manager I/O管理器  
  输入输出管理器可以让用户输入输出数据，链接有外部设备显示器，键盘，鼠标，打印机等    

*user space* 用户空间  
使用者不直接与内核进行交互，而是通过用户空间进行交互，比如系统程序，用户界面
- applications 应用 

>major ones 主要的操作系统
- windows(PC)
- mac
- linux 开源，软件免费共享，常见的linux发行版有 Ubuntu\Debian\Red Hat



***
## 1:41:09 interation with the ios 与操作系统互动
**two ways to interact**   
*Shell* 用户界面   
操作系统和用户之间的桥梁。用户界面是一个程序，它翻译了文本命令，并将它们送入操作系统去执行，被广泛地应用去运行命令。   
不同的操作系统背后是相同的概念，如shell bash和bourne again shell  

*Graphical user interface* 图形用户界面    
一种可视化交互方式，用鼠标点击和拖动文件夹等      
微软的windows和苹果的MAC OS的菜单和图标设计就存在区别   


***
## 2:13:45 basics of networking
- 互联网就是把世界各地的计算机连接起来
- 万维网WORLD WIDE WEB不同于互联网，互联网是全世界计算机和电线的物理的链接  
- Web则是互联网上的信息，用户通过 www.com 的链接方式使用网去链接互联网，万维网并不是用户访问互联网的唯一方式。  
- 管理、建设、设计网络也被称为网络工程，它是一个巨大且重要的领域   
- 互联网是由巨大的卫星、蜂窝网络和物理电缆等组成的，用户实际上不直接连接到互联网，是被称为服务器的计算机直接与互联网连接，服务器存储我们所使用的媒体网站    
- 网站提供的内容，我们使用的机器如手机电脑游戏机等都被称为客户端（clients），客户端从服务器请求诸如图片网站的内容，客户端不直接连接到互联网，而是连接到由互联网服务商（ISP)提供的网络  
- ISP已经建立了网络并运行所有必要的物理电缆，连接了数以百万计的计算机于一个网络中。同时它们也链接了其他网络和ISP，基本上，世界上所有的网络一起组成了一个巨大的计算机网络。  
- 网络上的计算机有一个称为IP地址的标识符，IP地址由数字组成
- MAC address通常是永久性的而且是硬编码于设备上的，当你从互联网上发送或接收数据时你需要同时拥有IP地址和MAC地址
- 通过互联网发送的数据是通过数据包发送的，即0和1。举个例子，用户的电脑发送一个数据包询问是否可以访问谷歌网站，数据包知道谷歌网站的ip地址，却不知道如何到达，数据包就从一个地方到另一个地方，最终它会被路由到另一个目的地，越来越接近谷歌网站，一旦到达一个可以将数据包发送到谷歌的目的地，谷歌就会发送回一个数据包，告诉用户它可以访问。



***
## 2:31:08 how the internet works
- 直到20世纪70年代，人类采取的重大的突破，解决了网络无法沟通的问题。人类创造了称之为传输控制协议和互联网协议的方法，即TCP/IP,之后世界各地的人可以相互发送数据，但仍存在问题，即他们发送的信息也就是文本，他不是集中式的（wasn't centralized)，并且相当乏味。
- 到了20世纪90年代，人类发明了万维网，它利用不同的协议在web页面上显示信息，成为主要的通信和访问internet的方式


```python

```
