# 官网
	- http://groovy-lang.org/

# 环境
	## 开发环境
		- GDK(Groovy Development Kit)
		- command:
			+ groovy -v
			+ groovyc
			+ groovysh
			+ groovyConsole.bat(Windows GUI)
	## 环境变量
		- $JAVA_HOME

		- $GROOVY_HOME
	## 环境管理
		- GVM(Groovy Enviroment Manager)
		- command:
			+ gvm list groovy
			+ gvm use groovy 2.1.1
# 包管理


# 语言特点
	+ 全面兼容Java语法	
	+ 默认导入了常用类和包
	+ 支持安全导航操作符？
	+ 不必强制处理受检异常	
	+ Return语句是可选的
	+ 方法和类默认Public
	+ 分号；是可选的
	+ 类型是可选的，自动推断
	+ 具名参数初始化JavaBean
	+ 静态方法内可以使用this来指代Class对象
	+ 支持可选参数-Default Value
	+ 支持多赋值
	+ def用于定义方法，属性和局部变量
	+ in用于在for循环中指定循环区间
	+ it是单参数闭包中的参数默认名称


# 语法特点


# 工程结构



# 程序组织


# 代码注释


# 类新系统
## 变量定义

## 常量定义

## 基本类型
	### 字符串
		+字面量
			- “string”
			- ‘String’
		+ 转移符
			“\$”
		+ 多行字符串
			‘’‘multiline string’‘’
			“”“multiline string“”“
		+ 变量替换
			- “$foo.bar is a test”
			- “${foo.bar} is a test”
	### 枚举

## 集合类型
	### List
	### Map

# 逻辑系统
  ## 表达式
  	### 布尔求值
  		+ Boolean值为ture
  		+ Collection集合不为空
  		+ Character值不为0
  		+ CharSequence长度大于0
  		+ Enumration的HasMoreElements为true
  		+ Iterator的HasNext为true
  		+ Number值不为0
  		+ Map不为空
  		+ Matcher至少有一个匹配
  		+ Object[]长度大于0
  		+ 其他任何类型引用不为null
  	### 操作符重载
  		+ 每个操作符对会映射到一个标准方法，在Java中按名使用方法，在Groovy中既可以按名使用方法或者使用操作符


  ## 语句
  	+ 多赋值
  		def (first,second,third) = ['Tom', "Jerry"]

  	+ 条件

  	+ 循环
  		for(greet in greetings){
  			println greet
  		}

  	+ 输出
  		print ......
  		println ......


  ## 函数
  	- 参数默认值
  	- 变长参数
  	- 闭包
  		+ {}
  		+ { x, y ->

  		}
  	- 科里化
  		<closure>.curry(...)
  		<closure>.rcurry(...)
  		<closure>.ncurry(...)	
  
  ## 类
  	### 定义：
  		#### 匿名内部类 {}

  	### 成员：
    	#### 方法
    		<modifiers> def [return-type] methodName(... parameters){

    		}

    	#### 属性
    		<modifiers> <propName>
     		<modifiers> def <propName> 


  ## 接口
  	### 定义
  	### 实现
  	{ Code Block } as <InterfaceName>

  ## 泛型

  ## 注解

  	
  ## 包
    ### 定义
    ### 导入
    ### 默认导入
      + java.lang
      + java.util
      + java.io
      + java.net
      + java.math.BigDecimal
      + java.math.BigInteger
      + groovy.lang
      + groovy.util
    ### 静态导入
# GDK
 ## Object类的扩展
 ## java.lang的扩展
 ## java.io的扩展	
 ## java.util的扩展	


