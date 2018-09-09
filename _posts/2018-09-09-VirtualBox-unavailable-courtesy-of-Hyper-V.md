---
title: VirtualBox VM Startup error "Raw-mode is unavailable courtesy of Hyper-V"
---
# Error

Upon VM startup, 
```
error:  Raw-mode is unavailable courtesy of Hyper-V. (VERR_SUPDRV_NO_RAW_MODE_HYPER_V_ROOT)
```

# Cause
Windows Defender coming with new feature since Version 1803: "Core isolation", with _Memory integrity_ set on. 

# Solution
__Turn off "Memory integrity" in Windows Denfender Device protection panel.__

ref: https://forums.virtualbox.org/viewtopic.php?f=6&t=89065
