# 循环

## for 循环

for 循环有三种格式

```go
for init; condition; post{}
for condition{}
for {}
```

举个栗子

```go
s := "abc"
// 1
for i, n = 0, len(s); i < n; i++ {
    println(s[i])
}
// 2
n := len(s)
for n > 0 {
    println(s[n])
    n--
}
// 3
for{
    println(s)
}
```

## range 

将 range 关键字作用域 for 循环，可以操作 slice map 数组 字符串

```go
for key, value := range oldMap{
    newMap[key] = value
}
```

本质上是对 oldMap 复制之后操作



