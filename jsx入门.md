### 什么是jsx
jsx是一种javaScript语法拓展（不是react独占），react配合jsx使用效果很好，不是模版语法，而是语法糖，能让你在js中直接写html标签


### 语法规范
1. 与vue模版语法类似，区别有jsx中嵌入js代码由｛｝包裹
2. **jsx是一个表达式**，编译之后会被转换成js函数返回一个js对象
3. 对于标签属性，如果由双引号 包裹 则被当作字符串类型的值，如果使用大括号包裹则认为a它是一个js表达式。

```js
const name = 'test name'
const element = <h1> ... {name}  </h1>
cosnt element2 = <div class="test"  data={name}></div>
```

### 对于react中的jsx
1. react 认为 大写的是react组件，小写的标签是html原生组件。
2. jsx可以直接使用属性语法。