```bash
export PATH=$ANDROID_NDK_HOME/toolchains/llvm/prebuilt/darwin-x86_64/bin:$PATH
ARCH=aarch64 CROSS_TARGET=aarch64-linux-android31 OCSD_ROOT=../../decoder make DEBUG=1
```
