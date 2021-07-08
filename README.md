# C++  Basics-and-Operations
c++的基础知识和习题
（大部分的代码采用外链式写法）
题目：
1、构造一个类CalculateFun，公有部分包含构造、析构函数、外部接口函数void AllByOne()、和静态成员函数static void ShowSequence()。私有部分包含：void InsideCalculation()、void SetData()、int x、int y和静态成员变量static int snCount。

2、构造函数CalculateFun()初始化x和y的值，InsideCalculation和SetData函数仅供AllByOne函数调用，而外部main函数中对于Calculation的任意对象仅仅调用AllByOne就可以实现从键盘上输入x、y的值，求出(x+2)*(y+3)的结果并显示出来。其中SetData用于键盘输入x和y的值，InsideCalculation用于计算(x+2)*(y+3)并显示结果。

3、建立void ObjectOperating(CalculateFun *pObject)普通函数，功能是对形参中的对象指针调用其接口函数AllByOne()，并且调用静态成员函数ShowSequence来显示是第几次调用对象。

4、main函数中建立一个含三个元素的对象指针数组pArr，分别对其三个元素new出三个对象，并调用ObjectOperating函数。完了后用delete释放new出的内存。
