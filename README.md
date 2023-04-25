# JavaParserBasedOnJS`
这是一个JS编写的Java解析工具，analyzer是我提供的解析方法模板，使用```let compilationUnit = MyJavaParser.parser(file);```将文件转化为容器树，你可以自己编写方法操纵容器树获取想要的信息。  
ps：文件间没有相互引用，需要引入这个包中的所有文件才能正常使用
