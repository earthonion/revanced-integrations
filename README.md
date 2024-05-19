# 🔩 ReVanced rehab mode

## buffering bug:

kinda a hacky way to circumvent the buffering bug. clicking on a video (should) open the video externally.

eg. newpipe, libretube 

The official ReVanced Integrations containing classes to be merged by ReVanced Patcher.

## ❓ How to use debugging:

- Usage on Windows: ```adb logcat | findstr "revanced" > log.txt```
- Usage on Linux: ```adb logcat | grep --line-buffered "revanced" > log.txt```
  
This will write the log to a file called log.txt which you can view then.
