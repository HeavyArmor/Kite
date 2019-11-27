# Kite
Kite(风筝)编程语言
>## 关键字
|关键字|关键字|关键字|
|:---:|:---:|:---:|
|import|boolean|string|
|char|int|float|
|double|long|short|
|null|public|private|
|static|class|interface|  
|try|catch|throws|  
|for|do|while|
|if|else|switch|
|case|default|return|
|continue|true|false|  
|class|interface|this|
|super|extends|implements|
>## 内置函数  
typeof,instanceof  

>## 语法样例  
```Kite
import {Test} from com.ha.test;  

public interface TestInterface extends Test{  
    public name: string;  
    public age?: integer;  
    public height?: double;  
    public getName(): string;  
}  

public class TestImpl implements Test {  
    name: string = "12345";  
    age: int = 24;  
    height: double = 134.56;  

    public test(name: string, age?: integer, height?: double): void {  
        this.name = name;  
        this.age = age;  
        this.height = height;  
    }  

    public getName(): string {  
        return this.name;  
    }  
}
```  
>## 泛型  
<T: extends interface|implements interface|class1|class2|string|boolean|char>  

>## 运算符
### 算术运算符
|运算符|描述|
|:---:|:--|
|+|相加|
|-|相减|
|*|相乘|
|/|相除|
|%|求余|
### 关系运算符  
|运算符|描述|
|:---:|:--|
|==|检查两个值是否相等，如果相等返回 True 否则返回 False|
|!=|检查两个值是否不相等，如果不相等返回 True 否则返回 False|
|>|检查左边值是否大于右边值，如果是返回 True 否则返回 False|
|<|检查左边值是否小于右边值，如果是返回 True 否则返回 False|
|>=|检查左边值是否大于等于右边值，如果是返回 True 否则返回 False|
|<=|检查左边值是否小于等于右边值，如果是返回 True 否则返回 False|
### 逻辑运算符
|运算符|描述|
|:---:|:--|
|&&|逻辑 AND 运算符。 如果两边的操作数都是 True，则条件 True，否则为 False|
|\||逻辑 OR 运算符。 如果两边的操作数有一个 True，则条件 True，否则为 False|
|!|逻辑 NOT 运算符。 如果条件为 True，则逻辑 NOT 条件 False，否则为 True|
### 位运算符
|运算符|描述|
|:---:|:--|
|&|按位与运算符"&"是双目运算符。 其功能是参与运算的两数各对应的二进位相与|
|\||按位或运算符"|"是双目运算符。 其功能是参与运算的两数各对应的二进位相或|
|^|按位异或运算符"^"是双目运算符。 其功能是参与运算的两数各对应的二进位相异或，当两对应的二进位相异时|
|<<|左移运算符"<<"是双目运算符。左移n位就是乘以2的n次方。 其功能把"<<"左边的运算数的各二进位全部左移若干位，由"<<"右边的数指定移动的位数，高位丢弃，低位补0|
|>>|右移运算符">>"是双目运算符。右移n位就是除以2的n次方。 其功能是把">>"左边的运算数的各二进位全部右移若干位，">>"右边的数指定移动的位数。|

>## 反射

>## 语法要点  
1、动态、强类型语言  
2、缺省参数和动态参数  
3、泛型  
4、反射  
