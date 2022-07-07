# 变量定义

## 变量声明

1. 标准声明格式为

   ```go
   // var 变量名 变量类型
   var name string
   var arg int
   ```

2. 批量声明格式为

   ```go
   /*
   var(
   	变量名 变量类型
   	……
   )
   */
   var(
   	name string
      	age int
   )
   ```

3. 带初始化的声明

   ```go
   // var 变量名 类型 = 表达式
   var name string = "hello world!!!"
   // 变量类型推导
   var name = "hello world!!!"
   // var 变量名1, 变量名2，…… = 表达式1， 表达式2，……
   var name, age = "cain", 1
   ```

4. 短变量声明

   在函数内部采用的方式

   ```go
   func main(){
       n := 10
       m := 20
       fmt.Println(m, n)
   }
   ```

5. 匿名变量

   ```go
   // 当不想要某一个值的时候使用 _， 不占用内存k 
   x, _ = foo()
   ```

   
