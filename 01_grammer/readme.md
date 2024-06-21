# 语法

本章介绍基本语法。

## 关键字

go语言的全部25个关键字：

``````
break      default       func     interface   select
case       defer         go       map         struct
chan       else          goto     package     switch
const      fallthrough   if       range       type
continue   for           import   return      var
``````

以及一些其他被占用的：

``````
内建常量: true false iota nil

内建类型: int int8 int16 int32 int64
         uint uint8 uint16 uint32 uint64 uintptr
         float32 float64 complex128 complex64
         bool byte rune string error

内建函数: make len cap new append copy close delete
         complex real imag
         panic recover
``````

总体来说，当你能够会用上述的所有关键字，就表示你掌握了go语言。