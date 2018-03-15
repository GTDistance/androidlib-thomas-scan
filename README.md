# androidlib-thomas-scan
## 配置
##### 1.在根的build.gradle文件中添加以下资源

```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
##### 2. 子module添加依赖

```
dependencies {
	  compile 'com.github.GTDistance:androidlib-thomas-scan:1.0.4'
}
```
