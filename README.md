# Kite
Kite(风筝)编程语言
## 关键词
import  
boolean,string,char,int,float,double,long,short,null  
public,private,static,class,interface  
try,catch,throws  
for,do,while,if,else,switch,case,default  
return,continue  
true,false  
class,interface  
this,super  
extends,implements
## 内置函数  
typeof,instanceof  

## 语法样例  
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
## 泛型  
<T: extends interface|implements interface|class1|class2|string|boolean|char>  
## 反射

## 语法要点
1、动态、强类型语言
2、缺省参数和动态参数
3、泛型  
4、反射
