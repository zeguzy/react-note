###　原理
ｒｅａｃｔ中使用ｒｅｄｕｘ　用到了　高阶组件的特点。


### 使用方法：
- 引入依赖   redux react-redux
- 编写 state  reducter  'action create'
- createStore
- 编写组件
- 编写 state map to  props函数
- 编写 dispatch map to props 函数
- connect  格式 connect(mapStateToProps,mapDispatchToProps)(组件）
- 在根节点中  使用  react-redux提供的 Provider 标签 并添加  store属性（第5步创建的store）
- 加入自己编写的组件标签
