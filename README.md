# maven 

```
allprojects {
    repositories {
        google()
        mavenCentral()
        maven {
            url 'https://yuxiaormobileteam.github.io/maven/'
        }
    }
}
```

# libs
```
dependencies {
    //飞书登录
    implementation 'com.ss.android:larksso:3.0.3'
    //手机号一键登录
    implementation 'com.mobile.auth:gatewayauth:2.11.1.1'

}
```
