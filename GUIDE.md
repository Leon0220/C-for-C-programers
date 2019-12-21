//在大部分学校中，软件及计算机相关的专业的入门第一课，无非都是C语言，但是，从我个人的角度来看，对于编程初学者来说，C语言似乎过于繁琐，并不如C++友好。
//›本教程中，我的侧重点将在C++之上，让读者在学习C++的过程中去学会并深入理解C语言。本教程分为入门篇及进阶篇，笔者也是在校学生，如有错误，请多体谅。
/**C++初入门*/
//工欲善其事，必先利其器。在正式进入C++的开发之旅之前，我想先带领大家准备好Vistal Studio这一强大的开发环境。
//以下的学习，主要都是基于Visual Studio 2013(以下简称VS2013)和Mac环境下xcode进行的。关于Mac端下的C语言环境配置，笔者会在后续文章中进行说明。
//官网提供的为最新版本的VS2019,而我这里也会提供VS2013的下载链接：https://www.nocang.com/visual-studio-ultimate-2013/

/**D_1 C++/C输出Hello World/

//算机输出“Hello world”基本上是一门语言入门的第一步，以下，我们来看看一些其他的语言如何实现：
//java
public class HelloWorld {
public static void main (String[ ] args) {
      System.out.println(“Hello World”);
   }
}
//Python
print”Hello World” //解释型语言，一行实现
//Racket
displayln “Hello world” //笔者很喜欢的一门语言，推荐学习
//相比之下，C和C++的输出实现可能相对繁琐，具体如下;
//C++                                //C
#include <iostream>                 #include <stdio.h>
  using namespace std;                int main()
  int main()                          {
  {                                    printf("Hello World");
  cout<<"Hello World"<<endl;           return 0;
  return 0;                            }
  }
  //对比之下，我们不难发现C与C++之间的异曲同工之处，在下一章中，我们将开始C++与C的正式学习--基本数据类型
