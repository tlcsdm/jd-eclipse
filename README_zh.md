# JD-Eclipse

JD-Eclipse，Eclipse 平台的 Java 反编译器插件。

![](https://raw.githubusercontent.com/tlcsdm/jd-eclipse/master/src/website/img/jd-eclipse.png)

- Java 反编译器项目主页：[http://java-decompiler.github.io](http://java-decompiler.github.io)

- JD-Eclipse 源代码：[https://github.com/tlcsdm/jd-eclipse](https://github.com/tlcsdm/jd-eclipse)

## 描述
JD-Eclipse 是 Eclipse 平台的插件。它允许您在调试过程中显示所有 Java 源代码，即使您没有所有源代码。

## 如何构建 JD-Eclipse？
```
> git clone https://github.com/tlcsdm/jd-eclipse.git
> cd jd-eclipse
> ./gradlew build
```
generate _"build/distributions/jd-eclipse-x.y.z.zip"_

## 如何安装 JD-Eclipse ?
更新站点:

在 Eclipse 中创建一个新的更新站点，内容如下:

* 站点名称：Java Decompiler Eclipse Plug-in
* 站点 URL：https://raw.githubusercontent.com/tlcsdm/jd-eclipse/master/org.jd.ide.eclipse.site/site.xml

## 如何检查文件关联？
点击 _"窗口 > 首选项 > 常规 > 编辑器 > 文件关联"_
- _"*.class"_ : _Eclipse_ _"Class File Viewer"_ 默认选中。
- “*.class without source”：默认选择“JD Class File Viewer”。

## 如何卸载 JD-Eclipse？

1. 点击“帮助 > 关于 Eclipse > 安装详细信息”，

2. 选择“JD-Eclipse 插件”，

3. 点击“卸载...”。

## 许可证
根据 [GNU GPL v3](LICENSE) 发布。