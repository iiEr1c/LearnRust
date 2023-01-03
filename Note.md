# cargo

```shell
cargo new project_name
cargo build
cargo run
cargo check
cargo update
```

todo: windows上debug rust. 

# !符号
println是函数, println!则是宏.

# 特性
+ 变量默认不可变, 如果要可变则加mut修饰. => cpp's const修饰符
+ 和cpp相似的引用&, 也分为可变引用(加mut修饰)和不可变引用
+ println的占位符和cpp的fmtlib相似
+ variable shadow => 增加复杂性?