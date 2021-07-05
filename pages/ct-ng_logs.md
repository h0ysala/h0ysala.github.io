---
 layout: post
 title: Barely formatted work log and thoughts related to crosstool-ng 
---

## crosstool-ng

* crosstool-ng has moved fast-forward compared to its stable releases on Linux distros. For example, my local build host with latest stable crosstool-ng from zypper failed to build basic platforms. Blame on good fixes like  [issue-631](https://github.com/crosstool-ng/crosstool-ng/issues/631), [issue-1217](https://github.com/crosstool-ng/crosstool-ng/issues/1217). 

* x86_64-w64-mingw32 failed to build due to [fallthrough](https://gcc.gnu.org/onlinedocs/gcc/Statement-Attributes.html#:~:text=fallthrough) - which can be fixed updating sources, but hope latest source already taken care of this.

* I went ahead to fetch sources and build ct-ng locally. 

* Build with './configure --enable-local' failed, [issue-993](https://github.com/crosstool-ng/crosstool-ng/issues/993) is already covering this though.

* While trying to find solutions, I found really good write ups by [ilyas-hmadouche](https://ilyas-hamadouche.medium.com/creating-a-cross-platform-toolchain-for-raspberry-pi-4-5c626d908b9d), [ltekieli](https://ltekieli.com/using-crosstool-ng-to-generate-a-gcc-toolchain/) and ofcourse crosstool-ng [Documentation](https://crosstool-ng.github.io/docs/) itself is as simple as crosstool-ng.


##### Updated 05.07.2021 | Created 05.07.2021 -- @H0YSALA
