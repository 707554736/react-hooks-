hooks的核心优点：
1. 方便进行逻辑复用
2. 关注分离

# 如何创建自定义hooks
声明一个名字use开头的函数。而hooks和普通函数载语义上是有区别的：函数周是否用到其他的hooks？
用了才是 不用只是一个普通的函数

抽离hook的作用：1. 逻辑重用 2. 代码更加语义化，便于理解和维护

# 封装通用逻辑： 
1. 请求的处理
2. 监听浏览器状态
3. 拆分复杂组件