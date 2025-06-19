# Nokia KiaOS Boot Patcher

##Hardware
* Nokia 6300 4G (codename "Leo")
* Nokia 8000 4G (codename "Sparkler")
* Nokia 2720 Flip (firmware version 30.00.17.05 or later)
* Nokia 800 Tough (firmware version 30.00.17.05 or later)


## Effect
Patches firmwares to do the following:
* disable basic security checks
* updates the ADB daemon to the permanently rooted one
* adds statically linked Lua scripting engine 
* switches SELinux to permissive mode.

## Usage

```
bootpatcher.sh <path to boot.img>
```
