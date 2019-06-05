# study

## algo
数据结构与算法

### array

数组（Array）是一种线性表数据结构。它用一组连续的内存空间，来存 储一组具有相同类型的数据。

1.Java ArrayList 无法存储基本类型，比如 int 、 long ，需要封装为 Integer 、 Long 类，而 Autoboxing 、 Unboxing 
则有一定的性能消耗，所以如果特别关注性能，或者希望使用基本类型，就可以选用数组。 
2. 如果数据大小事先已知，并且对数据的操作非常简单，用不到 ArrayList 提供的大部分方法，也可以直接使用数组。 
3.还有一个是我个人的喜好，当要表示多维数组时，用数组往往会更加直观。比如Object[][] array；
而用容器的话则需要这样定义：ArrayList array。

对于业务开发，直接使用容器就足够了，省时省力。毕竟损耗一丢丢性能，完全不会影响到系统整体的性能。
但如果你是做一些非常底层的开发， 比如开发网络框架，性能的优化需要做到极致，这个时候数组就会优于容器，成为首选

