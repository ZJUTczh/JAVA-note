# JAVA-note
## 基础
JDK(Java Development Kit)>JRE(Java Runtime Environment)>JVM(Java Virtual Machine)

JDK=JRE+java开发工具(javac.exe,java.exe,javadoc.exe)

JRE=JVM+java核心类库

一旦显式地定义了类的构造器，系统就不再提供默认的空参构造器。

JavaBean：类是公共的，有一个无参构造器，有属性，且有对应的get、set方法。

## 继承
class student extends person{}子类A继承父类后获取父类所有属性和方法，但不能直接访问父类中私有的属性和方法。

一个子类只能继承一个父类，一个父类可被多个子类继承（Java中只能单继承，C++中允许多继承）。如：A被B继承，B被C继承，B是C的直接父类，A是C的间接父类。

子类中的方法会覆盖与父类同名的方法（参数列表相同）。

所有类（除jaca.lang.Object类）都直接或间接地继承了Object类。
