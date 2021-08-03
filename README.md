# travis-ibm-ppc64le-toolchain-test
Travis CI IBM `ppc64le` toolchain test

```yaml
script:
- uname -a 
- uname -r 
- dpkg -l | grep toolchain
- ls /etc/apt/sources.list.d/
```
First lets print out some info of the kernel, look for something called tool chain, and then list some sources we are pulling from. 

