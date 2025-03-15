### 终端词法语法分析器 ---- JGX compiler
---
<p align="right">[计算001 贾皋肖](https://github.com/IammyselfJGX) <br>
<b>学号</b>:120171080212 <br>
点击链接访问 [JGX](https://github.com/IammyselfJGX/JGX_compiler) 
</p>

#### 支持运算法
|    运算符    |               符号               |
|   :----:    |             :----:               |
| 算术运算符    |       +  -  *  /  %             |
| 关系运算符    |	<  <=   ==   >   >=   !=      |
| 逻辑运算符	|           ！  &&  \|\|          | - 取反
| 位运算符	    |        <<   >>   ~  |  ^  &     | ^ | & ~
| 赋值运算符    |	= 及其扩展（+= -= 等）          |   += -=
| 条件运算符    |	             ?:               | *
| 逗号运算符    |       	    ，                | *
| 下标运算符    |           	[]               |  *

#### 支持流程控制
    > 1.支持条件控制if、循环控制while、for<br>
    > 不允许悬空else，所以改用 elsif ，支持break、continue、return语句<br>
