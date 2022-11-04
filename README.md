# maven
自用maven仓库

仓库地址：`https://raw.githubusercontent.com/ImKujio/maven/master`

## Android

#### 添加仓库

在`settings.gradle[:Project]`添加：

```groovy
dependencyResolutionManagement {
    repositories {
        ...
        maven { url "https://raw.githubusercontent.com/ImKujio/maven/master" }
    }
}
```

#### kandroidutils

在`build.gradle[:Module]`添加

```groovy
dependencies {
    ...
    implementation 'me.kujio:kandroidutils:1.0'
}
```

