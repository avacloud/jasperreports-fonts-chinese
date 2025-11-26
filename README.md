# jasperreports-fonts-chinese
Jasper Reports 中文字体扩展包

## 项目结构 | Projects
* .../chinese/SourceHanSansCN-Regular.ttf       思源黑体
* .../chinese/SourceHanSerifCN-Regular.ttf      思源宋体

## 使用说明 | Instructions
* 报表设计器中可以字体名称
~~~
宋体、黑体
~~~
* 其他项目使用，pom.xml配置
~~~
<dependency>
	<groupId>com.github.avacloud</groupId>
	<artifactId>jasperreports-fonts-chinese</artifactId>
	<version>0.1.0</version>
</dependency>
~~~

## 编译&发布 | Builds
* 编译
~~~
mvn clean package install -DpomFile=./pom.xml
~~~
* 发布
~~~
mvn deploy:deploy-file \
  -Dfile=./target/jasperreports-fonts-chinese-0.1.0.jar \
  -DpomFile=./pom.xml \
  -Durl=https://maven.avacloud.com.cn/repository/maven-3rdparty \
  -DrepositoryId=ibas-maven \
  -Dpackaging=jar
~~~

## 鸣谢 | Thanks
[牛加人等于朱](http://baike.baidu.com/view/1769.htm "NiurenZhu")<br>