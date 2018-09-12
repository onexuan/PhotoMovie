### Gradle
``` groovy 
    allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}
```

``` groovy 
	dependencies {
	        implementation 'com.github.yellowcath:PhotoMovie:1.5.0'
	}
```

详细说明请移步[https://blog.csdn.net/yellowcath/article/details/82664987](https://blog.csdn.net/yellowcath/article/details/82664987)

![image](https://github.com/yellowcath/PhotoMovie/raw/master/readme/filter.gif)
![image](https://github.com/yellowcath/PhotoMovie/raw/master/readme/transfer.gif)