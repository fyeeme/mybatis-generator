## Spring boot Mybatis generate

maven -> plugin -> mybatis-generator:generate

## how to use 

1. create database and table
2. update src/main/resources/generatorConfig.xml, change tableName
3. run maven command

## Q&A

1. The content of element type "context" must match "(property*,plugin*,commentGenerator?
    配置文件 generatorConfig.xml 里面的context的子元素必须按照它给出的顺序，如错误提示的match“……”部分。 当然也可能是你xml文件有错（这个容易检查出来）

2. IDEA reported URI is not registered (Setting | Project Settings | Schemas and DTDs
    https://programmersought.com/article/53273975280/