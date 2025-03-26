An modified art library source.

Currently works with Android Q.

Method invocation path is inspired by the traditional Xposed frameowork, throught the proxyinvokation approach

Might be integrated to higher or lower versions.


NOTE:
  
  Semi-xposed classes are defined in framework.jar.
    
    Like "com.android.os.xxxxBridge.handleHookedMethod", "com.android.os.xxxxBridge.invokeOriginalMethod"
    
    Sample java classes are given in this respoitory.

  Thus, "build from source" is required, due to native method registration timings.
  
  Dangeous hacking may cause system crash at boot-phase.


Inspired By:

[Xposed-art](https://github.com/rovo89/android_art)

[LSPosed/LSPlant](https://github.com/LSPosed/LSPlant)
