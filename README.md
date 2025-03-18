# VMX-ARM-x64-Translation-Genymotion
This is a ARM x64 Translation for Genymotion ( Android VM on Linux )
## Step 1 Just add these code into your ADB first :
> Open the Android 11 Emulator ( NOTE : only Android 11 )
> Copy these below into **/system/build.prop and** **/system/vendor/build.prop**
```
ro.product.cpu.abilist=x86_64,x86,arm64-v8a,armeabi-v7a,armeabi
ro.product.cpu.abilist32=x86,armeabi-v7a,armeabi
ro.product.cpu.abilist64=x86_64,arm64-v8a
ro.vendor.product.cpu.abilist=x86_64,x86,arm64-v8a,armeabi-v7a,armeabi
ro.vendor.product.cpu.abilist32=x86,armeabi-v7a,armeabi
ro.vendor.product.cpu.abilist64=x86_64,arm64-v8a
ro.odm.product.cpu.abilist=x86_64,x86,arm64-v8a,armeabi-v7a,armeabi
ro.odm.product.cpu.abilist32=x86,armeabi-v7a,armeabi
ro.odm.product.cpu.abilist64=x86_64,arm64-v8a
ro.dalvik.vm.native.bridge=libhoudini.so
ro.enable.native.bridge.exec=1
ro.enable.native.bridge.exec64=1
ro.dalvik.vm.isa.arm=x86
ro.dalvik.vm.isa.arm64=x86_64
ro.zygote=zygote64_32
```
## Step 2 : Install Lib in folder "lib" and flash archive into your VM
> Download the lib [here](https://www.mediafire.com/file/dg3duvzw0l4i0pn/system.zip/file)
