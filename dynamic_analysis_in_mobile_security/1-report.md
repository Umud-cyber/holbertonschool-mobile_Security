# Native Hooking Report: Apk_task1

## Objective
Extract the decrypted flag processed in memory by `libnative-lib.so` via `Java_com_example_app_Native_getSecretMessage`.
ution:** Evaluated the return handle (`jstring`) during `onLeave` by calling `Java.vm.getEnv().getStringUtfChars()` to retrieve the unencrypted string directly from heap space before garbage collection or scope destruction.
