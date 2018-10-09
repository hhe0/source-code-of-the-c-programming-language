# 《C程序语言设计》源代码一览
## chap 1
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/01.md">1.1 复制文本输入到输出</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/02.md">1.2 字符计数</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/03.md">1.3 行计数</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/04.md">1.4 编写一个将输入复制到输出的程序，并将其中连续的多个空格用一个空格代替。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/05.md">1.5 单词计数</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/06.md">1.6 编写一个程序，以每行一个单词的形式打印其输入。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/07.md">1.7 统计一段文本中各个数字、空白符（空格符、制表符及换行符）以及所有其他字符出现的次数。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/08.md">1.8 读入一组文本行，并把最长的文本行打印出来。如果存在多个最长的文本行，则打印最后一个文本行。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/09.md">1.9 修改1.8中的程序，使得程序可以打印任意长度的输入行的长度，并尽可能多地打印文本信息。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/10.md">1.10 编写一个程序，删除每个输入行末尾的空格及制表符，并删除完全是空格的行。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/11.md">1.11 编写函数reverse(s)，将字符串s中的字符顺序颠倒过来。使用该函数编写一个程序，每次颠倒一个输入行中的字符顺序。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/12.md">1.12 编写程序detab，将输入中的制表符替换成适当数目的空格，使空格充满到下一个制表符终止位的地方。假设制表符终止位的位置是固定的，比如每隔n位就会出现一个制表符终止符。n应该作为变量还是符号变量呢？</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/13.md">1.13 编写程序entab，将空格串替换为最少数量的制表符和空格，但要保持单词之间的间隔不变。假设制表符终止位的位置与上一个detab程序相同。但要使用一个制表符或者一个空格都可以达到下一个制表符终止位时，选用哪一种替换字符比较好？</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/14.md">1.14 编写一个程序，把较长的输入行“折”成短一些的两行或多行，折行的位置在输入行的第n列之前的最后一个非空格之后。要保证程序能够智能地处理输入行很长以及在指定的列前没有空格或制表符时的情况。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/15.md">1.15 编写一个删除C语言程序中所有的注释语句。要正确处理带引号的字符串与字符常量。在C语言中，注释不允许嵌套。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%201/16.md">1.16 编写一个程序，查找C语言程序中的基本语法错误，如圆括号、方括号、花括号不配对等。要正确处理引号（包括单引号和双引号）、转义字符与注释。</a>

## chap 2
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/01.md">2.1 编写一个程序以确定分别由signed及unsigned限定的char、short、int与long类型变量的取值范围。采用打印标准头文件中的相应值以及直接计算两种方式实现。后一种方法的实现较困难一些，因为要确定各种浮点类型的取值范围。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/02.md">2.2 编写函数strlen()用于返回字符串的长度。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/03.md">2.3 判断一个年份是闰年还是平年。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/04.md">2.4 编写函数atoi()，将字符串s转换为相应的整型数。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/05.md">2.5 编写函数lower()，将一个字符转换为小写形式。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/06.md">2.6 编写函数htoi()，把由十六进制数字组成的字符串（包括可选的前缀0x或0X）转换为与之等价的整型值。字符串中允许包含的数字包括：0-9、a-f以及A-F。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/07.md">2.7 编写函数squeeze()，从字符串中删除字符c。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/08.md">2.8 编写函数strcat()，将字符串t连接到字符串s的尾部，s必须有足够大的空间。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/09.md">2.9 重新编写函数squeeze(s1, s2)，将字符串s1中任何与字符串s2中字符匹配的字符都删除。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/10.md">2.10 编写函数any(s1, s2)，将字符串s2中的任一字符在字符串s1中第一次出现的位置作为结果返回。如果s1中不包含s2中的字符，则返回-1。（标准库函数strpbrk具有同样的功能，但它返回的是指向该位置的指针）。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/11.md">2.11 编写函数getbits(unsigned x, int p, int n)，返回x中从第p位开始的n位。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/12.md">2.12 编写一个函数setbits(x, p, n, y)，该函数返回对x执行下列操作后的结果值：将x中从第p位开始的n个（二进制）位设置为y中最右边n位的值，x的其余各位保持不变。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/13.md">2.13 编写一个函数invert(x, p, n)，该函数返回对x执行下列操作后的结果值：将x中从第p位开始的nge（二进制）位求反（即，变成0,0变成1），x的其余各位保持不变。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/14.md">2.14 编写一个函数rightrot(x, n)，该函数返回将x循环右移（即从最右端移出的位将从最左端移入）n（二进制）位后所得到的值。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/15.md">2.15 编写bitcount函数：统计x中值为1的二进制位数。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%202/16.md">2.16 在求对二的补码时，表达式x&=(x-1)可以删除x中最右边值为1的一个二进制位。请解释这样做的道理。用这一方法重写bitcount函数，以加快其执行速度。</a>

## chap 3
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/01.md">3.1 编写binsearch函数：在v[0]<=v[1]<=v[2]<=...<=v[n-1]中查找x。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/02.md">3.2 编写一个函数escape(s, t)，将字符串t复制到字符串s中，并在复制过程中将换行符、制表符等不可见的字符分别转换\n、\t等相应的可见的转义字符序列。要求使用switch语句。再编写一个具有相反功能的函数，在复制过程中将转义字符序列转换为实际字符。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/03.md">3.3 编写shellsort函数，：按递增顺序对v[0]...v[n-1]进行排序。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/04.md">3.4 编写reverse()函数：倒置字符串s中各个字符的位置。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/05.md">3.5 编写函数expand(s1, s2)，将字符串s1中类似于a-z一类的速记符号在字符串s2中扩展为等价的完整列表abc...xyz。该函数可以处理大小写字母和数字，并可以处理a-b-c、a-z0-9与-a-z等类似的情况。作为前导和尾随的-字符原样打印。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/06.md">3.6 在数的对二补码表示中，我们编写的itoa函数处理最大的负数。请解释器原因。修改该函数使它在任何机器上都能打印出正确的值。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/07.md">3.7 编写函数itob(n, s, b)，将整数n转换为以b为底的数，并将转换结果以字符的形式保存到字符串s中。例如，itob(n, s, 16)把整数n化成十六进制整数保存在s中。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/08.md">3.8 修改itoa函数，使得该函数可以接受三个参数。其中，第三个参数为最小字段宽度。为了保证转换后所得的结果至少具有第三个参数指定的最小宽度，在必要时应在所得结果的左边填充一定的空格。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%203/09.md">3.9 编写trim函数：删除字符串尾部的空格符、制表符与换行符。</a>

## chap 4
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/01.md">4.1 编写程序查找字符串中某个字符模式匹配的次数。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/02.md">4.2 编写函数strindex(s, t)，它返回字符串t在s中最右边出现的位置。如果s中不包含t，则返回-1。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/03.md">4.3 编写atof函数，把字符串s转换为相应的双精度浮点数。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/04.md">4.4 对atof函数进行扩充，使它可以处理形如123.45e-6的科学表示法，其中，浮点数后面可能会紧跟一个E或者e以及一个指数（可能有正负号）。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/05.md">4.5 编写计算器程序用来处理逆波兰表示法表示的四则运算。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/06.md">4.6 在有了基本框架后，对计算器程序进行扩充就比较简单了。在该程序中加入取模(%)运算符，并注意考虑负数的情况。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/07.md">4.7 在栈操作中添加几个命令，分别用于在不弹出元素的情况下打印栈顶元素；复制栈顶元素；交换栈顶两个元素的值。另外增加一个命令用于清空栈。</a>
* <a href="https://github.com/hhe0/source-code-of-the-c-programming-language/blob/master/chap%204/08.md">4.8 给计算器程序增加访问sin、exp与pow等库函数的操作。</a>
