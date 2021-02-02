# anvill-windows
build anvill on Windows with LLVM11

bin/Bitcode.cpp need add  #define STDOUT_FILENO 1 on Windows 
cmake\anvillConfig.cmake.in 
modified:
set(ANVILL_LIBRARY_LOCATION "${CMAKE_INSTALL_PREFIX}/anvill/lib/anvill-${REMILL_LLVM_VERSION}.lib")
    set(ANVILL_INCLUDE_LOCATION "${CMAKE_INSTALL_PREFIX}/anvill/include")
