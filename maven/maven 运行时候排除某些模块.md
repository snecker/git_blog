有时为了提高打包速度，会把不相关的模块排除掉

```
mvn clean install -pl \!module,\!module/submodule,\!groupId:artifactId
```

注意：多个模块之间不能有空格