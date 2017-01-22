Dew Parent
--
基于Spring Cloud的Dew 构建框架

#### 使用

    <parent>
            <groupId>com.ecfront.dew</groupId>
            <artifactId>parent</artifactId>
            <version>1.0.0-SNAPSHOT</version>
    </parent>
    
**子项目需要重写`<mainClass></mainClass>`，使用自己的main class**

NOTE: 打包输入目录：./target/deploy/

#### 打包方式

     打成带lib目录的包：`package`
     只打项目包（不包含依赖）：`jar:jar`
     打成fat包：`assembly:assembly`
    