# 学习的新知识
## 一、swagger注解
- @Api：放在controller上面，用于描述controller的功能
- @ApiOperation：放在方法上面，用于描述方法的功能
- @ApiModel：放在类上面，描述类
- @ApiModelProperty：放在具有@ApiModel的类下面的属性上面
## 二、线程
- ThreadLocal：是线程局部变量，在这个线程中都可以直接使用，具有**线程隔离**
## 三、依赖工具
- PageHelper：分页工具类，使用PageHelper.startPage()方法分页，自动在查询语句中添加分页条件（limit）

