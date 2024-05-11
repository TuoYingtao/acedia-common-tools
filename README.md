# acedia-common-tools

```text
acedia-common-tools
├── acedia-common-core -- 核心模块
├── acedia-common-limiting -- 限流模块
├── acedia-common-log -- 日志模块
├── acedia-common-mybatis -- ORM模块
├── acedia-common-redis -- 缓存模块
└── acedia-common-swagger -- API文档模块
```
## 1 核心模块 [acedia-common-core](acedia-common-core)

### 1.1 config 配置

[1.1.1 全局配置类](docs%2Facedia-common-core%2Fconfig.md#全局配置类)

[1.1.2 Validation 配置类](docs%2Facedia-common-core%2Fconfig.md#validation配置类)

[1.1.3 线程池配置](docs%2Facedia-common-core%2Fconfig.md#线程池配置)

### 1.2 常量

[1.2.1 通用常量信息](docs%2Facedia-common-core%2Fconstant.md#通用常量信息)

[1.2.2 返回状态码](docs%2Facedia-common-core%2Fconstant.md#返回状态码)

[1.2.3 任务调度通用常量](docs%2Facedia-common-core%2Fconstant.md#任务调度通用常量)

[1.2.4 权限相关通用常量](docs%2Facedia-common-core%2Fconstant.md#权限相关通用常量)

[1.2.5 Token的Key常量](docs%2Facedia-common-core%2Fconstant.md#token的key常量)

[1.2.6 用户常量信息](docs%2Facedia-common-core%2Fconstant.md#用户常量信息)

[1.2.7 缓存常量信息](docs%2Facedia-common-core%2Fconstant.md#缓存常量信息)

[1.2.8 代码生成通用常量](docs%2Facedia-common-core%2Fconstant.md#代码生成通用常量)

### 1.3 枚举

[1.3.1 异常响应枚举](docs%2Facedia-common-core%2Fenums.md#异常响应枚举)

[1.3.2 用户状态枚举](docs%2Facedia-common-core%2Fenums.md#用户状态枚举)

### 1.4 异常信息

[1.4.1 全局异常处理器](docs%2Facedia-common-core%2Fexception.md#全局异常处理器)

[1.4.2 异常基类](docs%2Facedia-common-core%2Fexception.md#异常基类)

[1.4.3 断言-业务异常](docs%2Facedia-common-core%2Fexception.md#断言-业务异常)

[1.4.4 业务异常](docs%2Facedia-common-core%2Fexception.md#业务异常)

[1.4.5 请求响应异常](docs%2Facedia-common-core%2Fexception.md#请求响应异常)

[1.4.6 工具类异常](docs%2Facedia-common-core%2Fexception.md#工具类异常)

[1.4.7 文件信息异常类](docs%2Facedia-common-core%2Fexception.md#文件信息异常类)

[1.4.8 文件名称超长限制异常类](docs%2Facedia-common-core%2Fexception.md#文件名称超长限制异常类)

[1.4.9 文件名大小限制异常类](docs%2Facedia-common-core%2Fexception.md#文件名大小限制异常类)

[1.4.10 文件上传异常类](docs%2Facedia-common-core%2Fexception.md#文件上传异常类)

[1.4.11 文件上传 误异常类](docs%2Facedia-common-core%2Fexception.md#文件上传误异常类)

### 1.5 响应信息主体

[1.5.1 响应信息主体](docs%2Facedia-common-core%2Fdomain.md)

### 1.6 上下文信息

[1.6.1 TTL 获取当前线程变量中的 用户id、用户名称、Token等信息](docs%2Facedia-common-core%2Fcontext.md#ttl获取当前线程变量中的用户id用户名称token等信息)

### 1.7 属性配置信息

[1.7.1 线程池配置类](docs%2Facedia-common-core%2Fproperties.md#线程池配置类)

### 1.8 注解

[1.8.1 Logic 指定数字校验注解](docs%2Facedia-common-core%2Fannotation.md#logic指定数字校验注解)

[1.8.2 LogicStr 指定字母校验注解](docs%2Facedia-common-core%2Fannotation.md#logicstr指定字母校验注解)

[1.8.3 PhoneNumber 手机号校验注解](docs%2Facedia-common-core%2Fannotation.md#phonenumber手机号校验注解)

[1.8.4 Xss 自定义xss校验注解](docs%2Facedia-common-core%2Fannotation.md#xss自定义xss校验注解)

### 1.9 断言

[1.9.1 断言](docs%2Facedia-common-core%2Fasserts.md)

### 1.10 logback 日志自定义样式配置

[1.10.1 Logging 日志自定义日志等级高亮转换器](docs%2Facedia-common-core%2Flogback.md#logging日志自定义日志等级高亮转换器)

[1.10.2 Logging 日志自定义线程ID 转换器](docs%2Facedia-common-core%2Flogback.md#logging日志自定义线程id转换器)

### 1.11 text 文本信息

[1.11.1 字符集工具类](docs%2Facedia-common-core%2Ftext.md#字符集工具类)

[1.11.2 类型转换器](docs%2Facedia-common-core%2Ftext.md#类型转换器)

[1.11.3 字符串格式化](docs%2Facedia-common-core%2Ftext.md#字符串格式化)

### 1.12 utils 工具

[1.12.1 时间工具类](docs%2Facedia-common-core%2Futils.md#时间工具类)

[1.12.2 错误信息处理类](docs%2Facedia-common-core%2Futils.md#错误信息处理类)

[1.12.3 Http请求客户端工具类](docs%2Facedia-common-core%2Futils.md#http请求客户端工具类)

[1.12.4 JWT工具类](docs%2Facedia-common-core%2Futils.md#jwt工具类)

[1.12.5 Servlet客户端工具类](docs%2Facedia-common-core%2Futils.md#servlet客户端工具类)

[1.12.6 ApplicationContext全局上下文信息获取工具](docs%2Facedia-common-core%2Futils.md#applicationcontext全局上下文信息获取工具)

[1.12.7 SpringBean管理工具](docs%2Facedia-common-core%2Futils.md#springbean管理工具)

[1.12.8 字符串工具类](docs%2Facedia-common-core%2Futils.md#字符串工具类)

[1.12.9 线程相关工具类](docs%2Facedia-common-core%2Futils.md#线程相关工具类)

#### 1.12.1 BeanUtils 工具

[1.12.1.1 Bean 工具类](docs%2Facedia-common-core%2Futils.md#bean工具类)

[1.12.1.2 bean对象属性验证](docs%2Facedia-common-core%2Futils.md#bean对象属性验证)

#### 1.12.2 文件工具

[1.12.2.1 文件类型工具类](docs%2Facedia-common-core%2Futils.md#文件类型工具类)

[1.12.2.2 文件上传工具类](docs%2Facedia-common-core%2Futils.md#文件上传工具类)

[1.12.2.3 文件处理工具类](docs%2Facedia-common-core%2Futils.md#文件处理工具类)

[1.12.2.4 图片处理工具类](docs%2Facedia-common-core%2Futils.md#图片处理工具类)

[1.12.2.5 媒体类型工具类](docs%2Facedia-common-core%2Futils.md#媒体类型工具类)

#### 1.12.3 经纬度工具

[1.12.3.1 经纬度计算工具](docs%2Facedia-common-core%2Futils.md#经纬度计算工具)

#### 1.12.4 html 工具

[1.12.4.1 转义和反转义工具类](docs%2Facedia-common-core%2Futils.md#转义和反转义工具类)

[1.12.4.2 HTML过滤器，用于去除XSS漏洞隐患](docs%2Facedia-common-core%2Futils.md#html过滤器用于去除xss漏洞隐患)

[1.12.4.3 SQL过滤](docs%2Facedia-common-core%2Futils.md#sql过滤)

#### 1.12.5 获取IP 工具

[1.12.5.1 获取IP方法](docs%2Facedia-common-core%2Futils.md#获取ip方法)

#### 1.12.6 JSON 工具

[1.12.6.1 Jackson工具](docs%2Facedia-common-core%2Futils.md#jackson工具)

#### 1.12.7 Math计算工具

[1.12.7.1 精确的浮点数运算](docs%2Facedia-common-core%2Futils.md#精确的浮点数运算)

[1.12.7.2 金融计算工具](docs%2Facedia-common-core%2Futils.md#金融计算工具)

#### 1.12.8 反射工具类

[1.12.8.1 ReflectUtils反射工具类](docs%2Facedia-common-core%2Futils.md#reflectutils反射工具类)

#### 1.12.9 Sign工具类

[1.12.9.1 Base64工具类](docs%2Facedia-common-core%2Futils.md#base64工具类)

#### 1.12.10 SQL工具类

[1.12.10.1 SQL操作工具类](docs%2Facedia-common-core%2Futils.md#sql操作工具类)

#### 1.12.11 UUID工具

[1.12.11.1 ID生成器工具类](docs%2Facedia-common-core%2Futils.md#id生成器工具类)

[1.12.11.2 序列生成类](docs%2Facedia-common-core%2Futils.md#序列生成类)

[1.12.11.3 提供通用唯一识别码实现](docs%2Facedia-common-core%2Futils.md#提供通用唯一识别码实现)

### 1.x 资源文件

[1.x.1 Logback的XML配置.md](docs%2Facedia-common-core%2Fresources.md#logback的xml配置)

## 2 限流模块 [acedia-common-limiting](acedia-common-limiting)


## 3 日志模块 [acedia-common-log](acedia-common-log)

## 4 ORM模块 [acedia-common-mybatis](acedia-common-mybatis)

## 5 缓存模块 [acedia-common-redis](acedia-common-redis)

## 6 API文档模块 [acedia-common-swagger](acedia-common-swagger)
