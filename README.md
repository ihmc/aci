# ACI
Agile Computing Infrastructure Releases

You can find source code and more information on the [nomads](https://github.com/ihmc/nomads) repo.

## Gradle
Add [jitpack](https://jitpack.io/) repository:
```
repositories {
    ...
    maven { url "https://jitpack.io" }
}
```

Include dependency:
```
dependencies {
   ...
   compile 'com.github.ihmc:aci:v1.1'
}
```

If building for Android use `com.github.ihmc:aci-android:v1.1`.
