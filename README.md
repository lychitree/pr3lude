# pr3lude
## [spaghetti code warning]
 
Simple bash script for macOS to tether boot iPod3,1 (n18ap)

IPSWs found here: [Google Drive folder](https://drive.google.com/drive/folders/1RRR08B6sR2wEwuT9NQDYhb0pZjLxvB3c?usp=sharing)

**Supported versions:** 

3.1.1 (7C145), 3.1.1a (7C146), 3.1.2 (7D11), 3.1.3 (7E18)

4.0 (8A293), 4.0.2 (8A400), 4.1 (8B117), 4.2 (8C134), 4.2.1 (8C148)

4.3 (8F190), 4.3.1 (8G4), 4.3.2 (8H7), 4.3.3 (8J1), 4.3.4 (8K2), 4.3.5 (8L1).

5.0 (9A334), 5.0.1 (9A405), 5.1 (9B176), 5.1.1 (9B206). [in beta, no IPSWs yet]

# Usage

**Run `pr3lude -d` before using to download all binaries required**

```
Version: 3.0b [2023/11/09]
Usage: pr3lude [VERSION] <args>
Allows for tetherbooting iPod touch 3G
iOS 3-5, iPod3,1 only
5.x support in beta.

  -d  --dependencies         Downloads all binaries.
  -b, --boot                 Tether boot directly.
  
  arguments:
  -v                         Verbose boot. 
```

# Example

```
$ ./pr3lude 3.1.3
Version: 3.0b [2023/11/09]
Usage: pr3lude [VERSION] <args>
Allows for tetherbooting iPod touch 3G
iOS 3-5, iPod3,1 only
5.x support in beta.

Firmware detected: 3.1.3
Downloading Firmware files...
Patching iBSS...
Cleaning up...

Would you like to boot?
Y/N: N
$
```
# Credits

ih8sn0w and dora2ios for iBoot32Patcher

planetbeing for xpwn

dora2ios for iPwnder32

dayt0n et al. for irecovery

tihmstar et al. for partialZipBrowser

# Special thanks to

ud327 for helping test and giving me the idea to do this in the first place.

iPhoneGuy1101 for patched/signed 3.1.3 CFW and 4.1 CFW

Mo/Vanam for the sick '89 Honda Prelude <3
