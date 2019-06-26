# frida_script
Useful and Powerful Frida JS gadgets


# Usage
## android_frida_trace_myTrace
trace method calls
```
frida -U -f com.xxx.xxx.xxx --no-pause -l raptor_frida_android_trace.js
```
## Frida-Android-unpack
```
frida -U -f com.xxx.xxx.xxx -l dupDex.js --no-pause
```
