# ACI
Agile Computing Infrastructure Releases

You can find source code and more information on the [nomads](https://github.com/ihmc/nomads) repo.

If building on android please refer to the [ACI Android repository](https://github.com/ihmc/aci-android)

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
## Dependencies
If not included already you will also need
- slf4j (`'org.slf4j', name: 'slf4j-api', version: '1.7.25'`)
