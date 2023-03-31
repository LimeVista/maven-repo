# maven repo
Meven Repo

## 使用（Usage）
* 添加源（add repository）
```groovy
allprojects {
  repositories {
    // ...
    maven { url "https://raw.githubusercontent.com/LimeVista/maven-repo/master/repos" }
  }
}
```
