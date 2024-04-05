# common-publish

## Usage

作为submodule 导入

```shell
git submodule add https://github.com/storytellerF/common-publish.git common-publish
```

在gradle 中导入
>settings.gradle.kts

```
pluginManagement
    //...
    includeBuild("common-publish")
    //...
}
```

作为插件在子模块中使用

```
plugins {
    //...
    id("common-publish")
}
```
