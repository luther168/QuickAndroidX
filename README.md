# QuickAndroidX
Migrate from https://github.com/luther168/QuickAndroid
Add this into the root build.gradle:
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
Add the dependency:
dependencies {
    implementation 'com.github.luther168:QuickAndroidX:Lastest Version'
}