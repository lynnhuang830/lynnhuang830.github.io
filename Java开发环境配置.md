### 常用DOS命令
|  操作   | 说明  |
|  :----:  | :----:  |
| 盘符名称:  | 盘符切换 |
| dir  | 查看当前路径下的内容 |
| cd 目录 | 进入单级目录 |
| cd ..  | 回退到上一级目录 |
| cd 目录1\目录2\..  | 进入多级目录 |
| cd \  | 回退到盘符目录 |
| cls  | 清屏 |
| exit  | 退出cmd |
### 环境变量
为什么要配置环境变量：<br>
javac和java这些命令在bin目录下，为了方便实用，需要配置**Path环境变量**<br>

要配的系统变量：<br>
- Path
- JAVA_HOME
- CLASSPATH

CLASSPATH：指定Java类所在的目录<br>
- 初始目录是：.，代表当前目录
- 通常配置为：**.;\%JAVA_HOME\%\lib\tolls.jar;\%JAVA_HOME\%lib\dt.jar**

\*配置多个环境变量方法：
1. 新建**JAVA_HOME8**和**JAVA_HOME11**，指到对应JDK的目录
2. Path：**\%JAVA_HOME\%\bin**
3. 新建**JAVA_HOME**，设置成%JAVA_HOME8% or \%JAVA_HOME11\%，以此实现**切换JDK版本的目的**
### Java开发
开发流程：编写程序 - 编译程序 - 运行程序
