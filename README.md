### realm-java
---
https://github.com/realm/realm-java

```
```

```sh
ndk.dir=~/Users/Library/Android/android-ndk-r10e/r10e
export ANDROID_HOME=~/Library/Android/sdk
export ANDROID_NDK_HOME=~/Library/Android/android-ndk-r10e
launchctl setenv ANDROID_HOME "$ANDROID_HOME"
launchctl setenv ANDROID_NDK_HOME "$ANDORID_NDK_HOME"
export REALM_CORE_DOWNLOAD_DIR=~/.realmCore
launchctl setenv REALM_CORE_DOWNLOAD_DIR "$REALM_CORE_DOWNLOAD_DIR"
./gradew assemble
```

```
```


