# view_1

 Version: 0.9.1

 date    : 2026/05/10

 update :

***

C++ Window Webview2 , LLVM CLang

* LLVM CLang use
* visual studio 2026 community
* windows11

***
### vcpkg install
```
vcpkg install webview2:x64-windows
```

***
### build

```
clang++ -target x86_64-pc-windows-msvc -m64 -std=c++17 -O2 main.cpp -o main.exe ^
  -I/prog/vcpkg/installed/x64-windows/include ^
  -L/prog/vcpkg/installed/x64-windows/lib ^
  -lWebView2Loader.dll -luser32 -lgdi32 -lole32 -loleaut32
```

***
