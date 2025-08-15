# irdirectsdk_downloads
Download Area for the Software Development Kit (SDK) for Optris Imagers.

# Provided Binaries
A short description of the provided binaries for different operating systems and the environment they were built in. On request, additional binaries could be provided. For this, reach out to [direct-sdk@optris.com](mailto:direct-sdk@optris.com).

> Note: You can use the following commands to find out the version of your GLIBC and GLIBCXX. Afterwards, chose a build of the library that uses the same or a older GLIBC/GLIBCXX version.
```bash
# GLIBC
ldd --version

# GLIBCXX
strings /usr/lib/x86_64-linux-gnu/libstdc++.so.6 | grep GLIBCXX
```


## Ubuntu 24.04 LTS
### Environment
- Compiler: gcc
- Compiler version: 13.3.0
  - GLIBC: 2.39
  - GLIBCXX: 3.4.33
### Architectures
- amd64
- i386
- arm64

## Ubuntu 22.04 LTS
### Environment
- Compiler: gcc
- Compiler version: 11.4.0
  - GLIBC: 2.35
  - GLIBCXX: 3.4.30
### Architectures
- amd64
- i386
- arm64

## Ubuntu 20.04 LTS
### Environment
- Compiler: gcc
- Compiler version: 9.4.0
  - GLIBC: 2.31
  - GLIBCXX: 3.4.28
### Architectures
- amd64
- arm64

## Windows
### Environment
- Compiler: MSVC
- Toolset: v143
- Windows SDK Version: 10.0
### Architectures
- amd64
- win32

# Further Documentation
You can find the documentation to this SDK on the official [Optris website](https://sdk.optris.com/libirimager2/html/index.html).
