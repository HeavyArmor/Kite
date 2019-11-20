# Kite
Kite(风筝)编程语言
## 关键字
import  
boolean,string,char,integer,float,double,long,short,null  
public,private,static,class,interface  
try,catch,throws    
for,do,while,if,else,switch,case,default  
return,continue  

## 语法样例
import {Test} from com.ha.test;  
public interface TestInterface extends Test{  
    public name: string;  
    public age?: integer;  
    public height?: double;  
    public getName(): string;  
}

public class TestImpl implements Test {  
    name: string = "12345";  
    age: integer = 24;  
    height: double = 134.56;  
    public test(name: string, age?: integer, height?: double): void {  
        this.name = name;  
        this.age = age;  
        this.height = height;  
    }  

    public getName(): string {  
        return this,name  
    }
}



