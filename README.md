Hello JNI
=========

TL;DR
-----

```
docker run -it --rm -v $PWD:/src --workdir=/src davidsiaw/android-builder gradle build
docker run -it --rm -v $PWD:/src --workdir=/src --privileged davidsiaw/android-builder adb install app/build/outputs/apk/arm7/debug/app-arm7-debug.apk

adb shell
am start -n com.example.hellojni/com.example.hellojni.HelloJni
```

About
-----

Based off the hello-jni example project https://github.com/android/ndk-samples/tree/main/hello-jni
