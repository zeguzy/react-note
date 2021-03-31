### 什么是redux
- 类似 vue中的vuex，负责管理应用中所有全局状态。
- 将组件state移到组件之外，放在全局的store中
- 通用的状态管理框架
###　redux特性　　

1. Single source of truth  组件中尽量不保存状态。
2. 可预测性　　　state + action = new state
3. 纯函数更新store

### redux三个核心概念
#### Store
- 数据存放的地方
- tree的结构 和view 的结构对应
#### actions
- 描述行为的数据结构
 
#### reducer
- 处理和分发action的地方

#### 几个工具函数
1. createStore      创建ｓｔｏｒｅ
2. bindActionCreator　处理了ａｃｔｉｏｎ函数，默认ｄｉｓｐａｔｃｈ
3. combineReducers　　组合多个ｒｅｄｕｃｔｏｒ

### 使用ｒｅｄｕｘ＋ｊｓ
1. 创建　初始化的　ｓｔａｔｅ
2. 编写　ｒｅｄｕｃｔｅｒｓ
3. createStore 传入　ｒｅｄｕｃｅｒ
4. 调用　ｓｔｏｒｅ的ｄｉｓｐａｔｃｈ方法
