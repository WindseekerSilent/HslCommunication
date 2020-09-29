<pre>
本库从 Richard.Hu 那里fork过来的。原仓库地址https://github.com/dathlin/HslCommunication
</pre>

## License
使用请遵循LGPL-3.0协议说明，除了协议中已经规定的内容外，附加下面三个条款（与原协议如有冲突以附加条款为准）：

* 允许用户使用本工具库（从NuGet下载）集成到自己的项目中作为闭源软件一部分，只需要声明版权出处并出具一份LGPL-3.0的授权协议即可。
* 禁止复制中间的代码及参考思路开发出类似的组件库。
* 源代码仅作为个人学习使用。

## Environment
* IDE: **Visual Studio 2017** 必须这个版本及以上，不然会语法报错
* .Net Framework环境下：支持.Net 3.5及以上环境，功能最完善。
* .Net Standard环境下：.Net 2.0以上，目前仅仅实现PLC读写，modbus tcp读写，日志记录。
* java环境下：**Intellij Idea 2018.1**

## Project Target
本项目的目标在于开发一个.Net及java下大多数软件系统都会包含了基础类库功能，实现一些常用的数据通信，日志记录等等类，以及版本类，网络通讯类，PLC数据访问类。并且实现C#和java无缝通信集成。

The goal of this project is to develop a .Net and java. Most software systems will include the basic class library functions, implement some common data communications, log records, etc., as well as version classes, network communications, and PLC data access classes. And to achieve seamless integration of C# and java communications.
