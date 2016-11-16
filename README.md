个人使用的Spring/MyBatis项目脚手架

### 安装
```
git clone https://github.com/wucao/xxg-webstart.git
cd xxg-webstart
mvn install
```

### 创建项目
```
mvn archetype:generate -B -DarchetypeGroupId=com.xxg -DarchetypeArtifactId=xxg-webstart -DarchetypeVersion=1.0.1 -DgroupId=my.group -DartifactId=my-artifact -Dversion=1.0-SNAPSHOT -DarchetypeCatalog=internal
```