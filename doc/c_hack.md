# Some skills in C language

## 不完全类型

公有文件中只定义结构体的标识符，实际的定义由私有头文件传递给公有头文件。

不完全类型只能使用指针，即指向不完全类型的指针的变量无法被声明，不完全类型本身也无法声明变量，对不完全类型无法使用sizeof。

## 静态变量的许可范围

静态变量在多线程的编译时会引发问题，然而编译静态变量的过程速度是极快的，可以使用一个全局锁的方式解决问题。

# stdarg使用可变参数, 占位符接受参数列表