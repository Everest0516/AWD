# AWD
### AWD线下攻防常用自动化脚本 Python2.7

已经在平台测试过了，全部可用，适用鲁棒性有待检查。

Author:@ZacharyZcR @Virtua1

有任何问题请联系QQ：2903735704

#### Vision 2.0.0

#### 现在脚本只对PHP AWD环境有效，Python和jsp，asp等框架还在研究。

全部重构代码。

把一些常用的操作封装成模块了，详情各位表哥自己调用看看。

主要功能文件tools.py

提供功能

1.植入木马 

2.植入文件 

3.获取flag 

4.储存flag

5.提交flag

6.RCE 

7.批量RCE 

8.配置确认 

9.存活检测 

启动文件main.py

具体说明在tools.py里加了注释。

本次更新自动攻击框架，自动加固框架正在努力搬砖。

#### Vision 2.1.0

优化了攻击框架的部分代码逻辑。

#### 新增AWD自动防御框架

框架提供功能

1.构建目录树

2.文件守护

3.PHP文件添加log

4.源码备份

5.PHP文件危险函数检测

欢迎各位表哥试用

#### Vision 2.1.1

修复了防御框架中的一个错误。

该错误会导致目录下文件被删除而无法正常修复。

#### Vision 2.1.2

修复了防御框架中的无法处理文件夹被删除的错误。

现在框架会正确处理文件夹被删除的自动恢复问题。

在文件守护选项中增加了自动备份功能。

增加两个新功能：

1.备份移除

2.PHP文件统计

另外在文件守护中可以直观看到目录和文件数目了。

增加了使用说明，配图。

#### Vision 2.1.3

感谢@Virtua1表哥的混淆模块。

在Extend_Module中可以直接使用独立脚本。

整合工作进行中，欢迎Fork。
