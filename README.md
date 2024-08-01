
    $ make
    icpx -O3 -std=c++17 -fsycl -Wpedantic -Werror -c -o global_vars.o global_vars.cpp
    In file included from <built-in>:1:
    /tmp/icpx-b301457e57/global_vars-header-d514ac.h:25:36: error: zero size arrays are an extension [-Werror,-Wzero-length-array]
       25 | const char* const kernel_names[] = {
          |                                    ^
    1 error generated.
    make: *** [GNUmakefile:5: global_vars.o] Error 1
