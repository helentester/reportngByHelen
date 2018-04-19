# Reportng
1. 添加了主页显示饼图
2. 测试结果显示的时候按照测试的时间顺序排序，原来是名称顺序
3. 本地化了部分显示内容

显示效果：  
![](http://ww1.sinaimg.cn/mw690/78090649jw1f5efogko5cj21gx0l2mzs.jpg)

## 使用修改后的reportng
jar包[下载](http://o9mrk1bm4.bkt.clouddn.com/reportng-1.1.5.jar)
```xml
<!-- 依赖reportNg 关联testNg -->
		<dependency>
			<groupId>org.uncommons</groupId>
			<artifactId>reportng</artifactId>
			<version>1.1.5</version>
			<scope>system</scope>
			<exclusions>
				<exclusion>
					<groupId>org.testng</groupId>
					<artifactId>testng</artifactId>
				</exclusion>
			</exclusions>
			<systemPath>${project.basedir}/lib/reportng-1.1.5.jar</systemPath>
		</dependency>
		<dependency>
			<groupId>velocity</groupId>
			<artifactId>velocity</artifactId>
			<version>1.4</version>
		</dependency>
```
