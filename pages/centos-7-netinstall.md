---
 layout: post
 title: CentOS 7 NetInstall : Adding mirror list 
---
## CentOS 7 - NetInstall

A good friend of mine wanted to try out CentOS-7 x86, but stumbled into install issue on his age old system. While helping him out, I figured out documentation on several tricks/tips are buried 6 feet down. I'm adding few screen shots for the needy once.

#### Path for mirrorlist on the network  

![](https://heritage.h0ysala.net/_/b6feffad6314c83bfb616793459a4dee3a5caa8bc17da07a46137fe08bfd8f78.png)

Additional repositories can be added, example for AppStream is shown but not enabled. Another one is "extras" where lot more packages are found, for that replace "os" with "extra" as additional repository.

For x86_64 use arch=x86_64, x86 shown here is for 32 bit release.

#### Mirrorlist how installer in NetInstall wants 
![](https://heritage.h0ysala.net/_/767555660ad3501a87b00dbc98d76a7a55e6ca0b4d060556e0cac01604de56af.png)


#### Content listing on a mirror, for BaseOS  
![](https://heritage.h0ysala.net/_/70ddf617ecf61282bd5545c60879d09a971eaa1d4cdf355a79fec976d200fe86.png)


##### Created 29.07.2021 -- @H0YSALA
