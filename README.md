# 编译器开发
实现一个完整的编译器，实现不同AI framework代码的转化，从High-level -> High-level representation。

**Features**
从机器学习工作流的角度实现编译器AST, 不同于其它AST从代码层面的转化，我们从如下角度构建新的AST，进行IR级别的转化，通过不同的后端（可拓展），编译为其它框架的代码

* 数据处理
* 模型结构
* 损失函数和优化算法
* 训练过程
* 测试和调试

