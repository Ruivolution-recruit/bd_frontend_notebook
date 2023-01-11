# JS 篇

## 基本数据类型和类型转换

### 基本数据类型

- 字符串String：通过单引号或者双引号定义
  - 可以在单引号里使用双引号，或者反过来
  - 单引号里使用单引号要转义

```javascript
console.log('say "Hello world!"')
console.log("say 'Hello world'")
console.log("say \"Hellow world\"")
```

- 数值类型：只有浮点数
  - 不过，字符串和数字用 `+`连接时会进行类型转换
  - 也可以强制转换为数字

```javascript
1+'1' \\ '11'
+(1+'1') \\ 11
+'is a number' \\ NaN
```

- 空值：Null 或者 Undefine
  - Null代表本该是个对象
  - Undefine代表未赋值
