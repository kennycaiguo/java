# java

<b><details><summary>.classpath文件详解</summary></b>

.classpath文件用于记录项目编译环境的所有信息，包括：源文件路径、编译后class文件存放路径、依赖的jar包路径、运行的容器信息、依赖的外部project等信息。如果把该文件删除，则eclipse不能讲该工程识别为一个正常的java工程，仅仅当做普通的文件夹而导致不能正常运行。

1.kind="src"

src：即source 源文件，代表的是一个源文件，path=”src”是一个相对路径，相对.classpath文件本身，即path=”src”表示文件夹src与.classpath在同一个目录，且代表源文件

2.kind="output"

output用于指定java源文件编译后的class文件存放路径

3.kind="con"

con即是container,就是程序运行的容器，或者就说是运行环境也OK，它实际上是在Myeclipse最初的时候要配置installed JREs中指定（一般情况下我们指定的是JDK），但是这里实际使用的是JDK下的JRE中的jar包，就是JDK_HOME/jre/lib就是对应的这条语句。

</details>

<b><details><summary>float 和 double 的取值范围</summary></b>

</details>

<b><details><summary>JAVA中path和classpath具体是什么意思？</summary></b>

path 路径，是java编译时需要调用的程序（如java，javac等）所在的地方
classpath 类的路径，在编译运行java程序时，如果有调用到其他类的时候，在classpath中寻找需要的类。

</details>

